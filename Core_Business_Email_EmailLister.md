Core_Business_Email_EmailLister
===============

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
* Namespace: 

* This class is defined in [Core/Business/Email/Core_Business_Email_EmailLister.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Email/Core_Business_Email_EmailLister.php#27)





Properties
----------


### $filesystem

    private mixed $filesystem





* Visibility: **private**
* This property is defined in [Core/Business/Email/Core_Business_Email_EmailLister.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Email/Core_Business_Email_EmailLister.php#29)


Methods
-------


### __construct

    mixed Core_Business_Email_EmailLister::__construct(\Core_Foundation_FileSystem_FileSystem $fs)





* Visibility: **public**
* This method is defined in [Core/Business/Email/Core_Business_Email_EmailLister.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Email/Core_Business_Email_EmailLister.php#31)


#### Arguments
* $fs **[Core_Foundation_FileSystem_FileSystem](Core_Foundation_FileSystem_FileSystem)**



### getAvailableMails

    array|null Core_Business_Email_EmailLister::getAvailableMails(null $dir)

Return the list of available mails



* Visibility: **public**
* This method is defined in [Core/Business/Email/Core_Business_Email_EmailLister.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Email/Core_Business_Email_EmailLister.php#43)


#### Arguments
* $dir **null**



### getCleanedMailName

    string Core_Business_Email_EmailLister::getCleanedMailName($mail_name)

Give in input getAvailableMails(), will output a human readable and proper string name



* Visibility: **public**
* This method is defined in [Core/Business/Email/Core_Business_Email_EmailLister.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Email/Core_Business_Email_EmailLister.php#77)


#### Arguments
* $mail_name **mixed**


