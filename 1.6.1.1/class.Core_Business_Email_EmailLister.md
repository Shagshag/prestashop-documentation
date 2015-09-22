Class Core_Business_Email_EmailLister
=====================

2007-2015 PrestaShop

NOTICE OF LICENSE

This source file is subject to the Open Software License (OSL 3.0)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
http://opensource.org/licenses/osl-3.0.php
If you did not receive a copy of the license and are unable to
obtain it through the world-wide-web, please send an email
to license@prestashop.com so we can send you a copy immediately.

DISCLAIMER

Do not edit or add to this file if you wish to upgrade PrestaShop to newer
versions in the future. If you wish to customize PrestaShop for your
needs please refer to http://www.prestashop.com for more information.

* Class name: Core_Business_Email_EmailLister
* Source: [Core/Business/Email/Core_Business_Email_EmailLister.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Email/Core_Business_Email_EmailLister.php#L27)



Properties
----------

* [$filesystem](#property-$filesystem)

Methods
-------
* [__construct](#method-__construct)
* [getAvailableMails](#method-getAvailableMails)
* [getCleanedMailName](#method-getCleanedMailName)




Properties
----------


### <a name="property-$filesystem"></a>$filesystem

    private mixed $filesystem





* Visibility: **private**
* Source: [Core/Business/Email/Core_Business_Email_EmailLister.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Email/Core_Business_Email_EmailLister.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed Core_Business_Email_EmailLister::__construct(\Core_Foundation_FileSystem_FileSystem $fs)





* Visibility: **public**
* Source: [Core/Business/Email/Core_Business_Email_EmailLister.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Email/Core_Business_Email_EmailLister.php#L31)


#### Arguments
* $fs **[Core_Foundation_FileSystem_FileSystem](class.Core_Foundation_FileSystem_FileSystem.md)**



### <a name="method-getAvailableMails"></a>getAvailableMails

    array|null Core_Business_Email_EmailLister::getAvailableMails(null $dir)

Return the list of available mails



* Visibility: **public**
* Source: [Core/Business/Email/Core_Business_Email_EmailLister.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Email/Core_Business_Email_EmailLister.php#L43)


#### Arguments
* $dir **null**



### <a name="method-getCleanedMailName"></a>getCleanedMailName

    string Core_Business_Email_EmailLister::getCleanedMailName($mail_name)

Give in input getAvailableMails(), will output a human readable and proper string name



* Visibility: **public**
* Source: [Core/Business/Email/Core_Business_Email_EmailLister.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Email/Core_Business_Email_EmailLister.php#L77)


#### Arguments
* $mail_name **mixed**


