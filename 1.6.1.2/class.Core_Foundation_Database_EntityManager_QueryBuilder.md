Class Core_Foundation_Database_EntityManager_QueryBuilder
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

* Class name: Core_Foundation_Database_EntityManager_QueryBuilder
* Source: [Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php#L27)


Contents
--------


### Properties

* [$db](#property-$db)

### Methods

* [__construct](#method-__construct)
* [buildWhereConditions](#method-buildWhereConditions)
* [quote](#method-quote)




Properties
----------


### <a name="property-$db"></a>$db

```php
private mixed $db
```





* Visibility: **private**
* Source: [Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed Core_Foundation_Database_EntityManager_QueryBuilder::__construct(\Core_Foundation_Database_DatabaseInterface $db)
```





* Visibility: **public**
* Source: [Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php#L31)


#### Arguments
* $db **Core_Foundation_Database_DatabaseInterface**



### <a name="method-buildWhereConditions"></a>buildWhereConditions

```php
mixed Core_Foundation_Database_EntityManager_QueryBuilder::buildWhereConditions($andOrOr, array $conditions)
```





* Visibility: **public**
* Source: [Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php#L47)


#### Arguments
* $andOrOr **mixed**
* $conditions **array**



### <a name="method-quote"></a>quote

```php
mixed Core_Foundation_Database_EntityManager_QueryBuilder::quote($value)
```





* Visibility: **public**
* Source: [Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php#L36)


#### Arguments
* $value **mixed**


