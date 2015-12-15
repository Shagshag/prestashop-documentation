Class Core_Foundation_Database_EntityRepository
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

* Class name: Core_Foundation_Database_EntityRepository
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L27)


Contents
--------


### Properties

* [$db](#property-$db)
* [$entityManager](#property-$entityManager)
* [$entityMetaData](#property-$entityMetaData)
* [$queryBuilder](#property-$queryBuilder)
* [$tablesPrefix](#property-$tablesPrefix)

### Methods

* [__call](#method-__call)
* [__construct](#method-__construct)
* [convertToDbFieldName](#method-convertToDbFieldName)
* [doFind](#method-doFind)
* [findAll](#method-findAll)
* [findOne](#method-findOne)
* [getIdFieldName](#method-getIdFieldName)
* [getNewEntity](#method-getNewEntity)
* [getPrefix](#method-getPrefix)
* [getTableNameWithPrefix](#method-getTableNameWithPrefix)
* [hydrateMany](#method-hydrateMany)
* [hydrateOne](#method-hydrateOne)




Properties
----------


### <a name="property-$db"></a>$db

```php
protected mixed $db
```





* Visibility: **protected**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L30).


### <a name="property-$entityManager"></a>$entityManager

```php
protected mixed $entityManager
```





* Visibility: **protected**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L29).


### <a name="property-$entityMetaData"></a>$entityMetaData

```php
protected mixed $entityMetaData
```





* Visibility: **protected**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L32).


### <a name="property-$queryBuilder"></a>$queryBuilder

```php
protected mixed $queryBuilder
```





* Visibility: **protected**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L33).


### <a name="property-$tablesPrefix"></a>$tablesPrefix

```php
protected mixed $tablesPrefix
```





* Visibility: **protected**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L31).


Methods
-------


### <a name="method-__call"></a>__call

```php
mixed Core_Foundation_Database_EntityRepository::__call($method, $arguments)
```





* Visibility: **public**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L47)


#### Arguments
* $method **mixed**
* $arguments **mixed**



### <a name="method-__construct"></a>__construct

```php
mixed Core_Foundation_Database_EntityRepository::__construct(\Core_Foundation_Database_EntityManager $entityManager, $tablesPrefix, \Core_Foundation_Database_EntityMetaData $entityMetaData)
```





* Visibility: **public**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L35)


#### Arguments
* $entityManager **[Core_Foundation_Database_EntityManager](class.Core_Foundation_Database_EntityManager.md)**
* $tablesPrefix **mixed**
* $entityMetaData **[Core_Foundation_Database_EntityMetaData](class.Core_Foundation_Database_EntityMetaData.md)**



### <a name="method-convertToDbFieldName"></a>convertToDbFieldName

```php
string Core_Foundation_Database_EntityRepository::convertToDbFieldName($camel_case_field_name)
```

Convert a camelCase field name to a snakeCase one
e.g.: findAllByIdCMS => id_cms



* Visibility: **private**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L80)


#### Arguments
* $camel_case_field_name **mixed**



### <a name="method-doFind"></a>doFind

```php
array|mixed|null Core_Foundation_Database_EntityRepository::doFind($one, array $cumulativeConditions)
```

Constructs and performs 'SELECT' in DB



* Visibility: **private**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L182)


#### Arguments
* $one **mixed**
* $cumulativeConditions **array**



### <a name="method-findAll"></a>findAll

```php
array Core_Foundation_Database_EntityRepository::findAll()
```

Find all entities in DB



* Visibility: **public**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L215)




### <a name="method-findOne"></a>findOne

```php
array|mixed|null Core_Foundation_Database_EntityRepository::findOne($id)
```

Find one entity in DB



* Visibility: **public**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L203)


#### Arguments
* $id **mixed**



### <a name="method-getIdFieldName"></a>getIdFieldName

```php
mixed Core_Foundation_Database_EntityRepository::getIdFieldName()
```

Return ID field name



* Visibility: **protected**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L90)




### <a name="method-getNewEntity"></a>getNewEntity

```php
mixed Core_Foundation_Database_EntityRepository::getNewEntity()
```

Return a new empty Entity depending on current Repository selected



* Visibility: **public**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L135)




### <a name="method-getPrefix"></a>getPrefix

```php
mixed Core_Foundation_Database_EntityRepository::getPrefix()
```

Returns escaped DB table prefix



* Visibility: **protected**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L126)




### <a name="method-getTableNameWithPrefix"></a>getTableNameWithPrefix

```php
mixed Core_Foundation_Database_EntityRepository::getTableNameWithPrefix()
```

Returns escaped+prefixed current table name



* Visibility: **protected**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L117)




### <a name="method-hydrateMany"></a>hydrateMany

```php
mixed Core_Foundation_Database_EntityRepository::hydrateMany(array $rows)
```





* Visibility: **protected**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L164)


#### Arguments
* $rows **array**



### <a name="method-hydrateOne"></a>hydrateOne

```php
mixed Core_Foundation_Database_EntityRepository::hydrateOne(array $rows)
```

This function takes an array of database rows as input
and returns an hydrated entity if there is one row only.

Null is returned when there are no rows, and an exception is thrown
if there are too many rows.

* Visibility: **protected**
* Source: [Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/Core/Foundation/Database/Core_Foundation_Database_EntityRepository.php#L150)


#### Arguments
* $rows **array** - Database rows


