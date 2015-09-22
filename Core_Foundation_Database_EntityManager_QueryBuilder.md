Core_Foundation_Database_EntityManager_QueryBuilder
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


* Class name: Core_Foundation_Database_EntityManager_QueryBuilder
* This class is defined in [Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php#L27)





Properties
----------


### $db

    private mixed $db





* Visibility: **private**
* This property is defined in [Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php#29)


Methods
-------


### __construct

    mixed Core_Foundation_Database_EntityManager_QueryBuilder::__construct(\Core_Foundation_Database_DatabaseInterface $db)





* Visibility: **public**
* This method is defined in [Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php#31)


#### Arguments
* $db **[Core_Foundation_Database_DatabaseInterface](Core_Foundation_Database_DatabaseInterface)**



### quote

    mixed Core_Foundation_Database_EntityManager_QueryBuilder::quote($value)





* Visibility: **public**
* This method is defined in [Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php#36)


#### Arguments
* $value **mixed**



### buildWhereConditions

    mixed Core_Foundation_Database_EntityManager_QueryBuilder::buildWhereConditions($andOrOr, array $conditions)





* Visibility: **public**
* This method is defined in [Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/Database/EntityManager/Core_Foundation_Database_EntityManager_QueryBuilder.php#47)


#### Arguments
* $andOrOr **mixed**
* $conditions **array**


