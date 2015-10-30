Class Adapter_Database
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

* Class name: Adapter_Database
* Source: [Adapter/Adapter_Database.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Adapter/Adapter_Database.php#L27)
* This class implements: [Core_Foundation_Database_DatabaseInterface](interface.Core_Foundation_Database_DatabaseInterface.md)

Contents
--------



### Methods

* [escape](#method-escape)
* [select](#method-select)






Methods
-------


### <a name="method-escape"></a>escape

```php
string Adapter_Database::escape($unsafeData)
```

Escape $unsafe to be used into a SQL statement



* Visibility: **public**
* Source: [Adapter/Adapter_Database.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Adapter/Adapter_Database.php#L45)


#### Arguments
* $unsafeData **mixed**



### <a name="method-select"></a>select

```php
array|false Adapter_Database::select($sqlString)
```

Perform a SELECT sql statement



* Visibility: **public**
* Source: [Adapter/Adapter_Database.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Adapter/Adapter_Database.php#L35)


#### Arguments
* $sqlString **mixed**


