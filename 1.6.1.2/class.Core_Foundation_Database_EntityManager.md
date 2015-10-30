Class Core_Foundation_Database_EntityManager
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

* Class name: Core_Foundation_Database_EntityManager
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityManager.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/Core_Foundation_Database_EntityManager.php#L27)


Contents
--------


### Properties

* [$configuration](#property-$configuration)
* [$db](#property-$db)
* [$entityMetaData](#property-$entityMetaData)

### Methods

* [__construct](#method-__construct)
* [delete](#method-delete)
* [getDatabase](#method-getDatabase)
* [getEntityMetaData](#method-getEntityMetaData)
* [getRepository](#method-getRepository)
* [save](#method-save)




Properties
----------


### <a name="property-$configuration"></a>$configuration

```php
private mixed $configuration
```





* Visibility: **private**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityManager.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/Core_Foundation_Database_EntityManager.php#L30).


### <a name="property-$db"></a>$db

```php
private mixed $db
```





* Visibility: **private**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityManager.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/Core_Foundation_Database_EntityManager.php#L29).


### <a name="property-$entityMetaData"></a>$entityMetaData

```php
private mixed $entityMetaData = array()
```





* Visibility: **private**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityManager.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/Core_Foundation_Database_EntityManager.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed Core_Foundation_Database_EntityManager::__construct(\Core_Foundation_Database_DatabaseInterface $db, \Core_Business_ConfigurationInterface $configuration)
```





* Visibility: **public**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityManager.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/Core_Foundation_Database_EntityManager.php#L34)


#### Arguments
* $db **Core_Foundation_Database_DatabaseInterface**
* $configuration **Core_Business_ConfigurationInterface**



### <a name="method-delete"></a>delete

```php
\Core_Foundation_Database_EntityManager Core_Foundation_Database_EntityManager::delete(\Core_Foundation_Database_EntityInterface $entity)
```

DElete entity from DB



* Visibility: **public**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityManager.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/Core_Foundation_Database_EntityManager.php#L109)


#### Arguments
* $entity **Core_Foundation_Database_EntityInterface**



### <a name="method-getDatabase"></a>getDatabase

```php
\Core_Foundation_Database_DatabaseInterface Core_Foundation_Database_EntityManager::getDatabase()
```

Return current database object used



* Visibility: **public**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityManager.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/Core_Foundation_Database_EntityManager.php#L46)




### <a name="method-getEntityMetaData"></a>getEntityMetaData

```php
mixed Core_Foundation_Database_EntityManager::getEntityMetaData($className)
```

Return entity's meta data



* Visibility: **public**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityManager.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/Core_Foundation_Database_EntityManager.php#L83)


#### Arguments
* $className **mixed**



### <a name="method-getRepository"></a>getRepository

```php
mixed Core_Foundation_Database_EntityManager::getRepository($className)
```

Return current repository used



* Visibility: **public**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityManager.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/Core_Foundation_Database_EntityManager.php#L56)


#### Arguments
* $className **mixed**



### <a name="method-save"></a>save

```php
\Core_Foundation_Database_EntityManager Core_Foundation_Database_EntityManager::save(\Core_Foundation_Database_EntityInterface $entity)
```

Flush entity to DB



* Visibility: **public**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityManager.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/Core/Foundation/Database/Core_Foundation_Database_EntityManager.php#L98)


#### Arguments
* $entity **Core_Foundation_Database_EntityInterface**


