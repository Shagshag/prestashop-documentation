Class Core_Business_CMS_CMSRepository
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

* Class name: Core_Business_CMS_CMSRepository
* Parent class: [Core_Foundation_Database_EntityRepository](class.Core_Foundation_Database_EntityRepository.md)
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L27)


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
* [getLanguageTableNameWithPrefix](#method-getLanguageTableNameWithPrefix)
* [getNewEntity](#method-getNewEntity)
* [getPrefix](#method-getPrefix)
* [getTableNameWithPrefix](#method-getTableNameWithPrefix)
* [hydrateMany](#method-hydrateMany)
* [hydrateOne](#method-hydrateOne)
* [i10nFindAll](#method-i10nFindAll)
* [i10nFindOneById](#method-i10nFindOneById)




Properties
----------


### <a name="property-$db"></a>$db

```php
protected mixed $db
```





* Visibility: **protected**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L30).


### <a name="property-$entityManager"></a>$entityManager

```php
protected mixed $entityManager
```





* Visibility: **protected**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L29).


### <a name="property-$entityMetaData"></a>$entityMetaData

```php
protected mixed $entityMetaData
```





* Visibility: **protected**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L32).


### <a name="property-$queryBuilder"></a>$queryBuilder

```php
protected mixed $queryBuilder
```





* Visibility: **protected**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L33).


### <a name="property-$tablesPrefix"></a>$tablesPrefix

```php
protected mixed $tablesPrefix
```





* Visibility: **protected**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L31).


Methods
-------


### <a name="method-__call"></a>__call

```php
mixed Core_Business_CMS_CMSRepository::__call($method, $arguments)
```





* Visibility: **public**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L48)


#### Arguments
* $method **mixed**
* $arguments **mixed**



### <a name="method-__construct"></a>__construct

```php
mixed Core_Business_CMS_CMSRepository::__construct(\Core_Foundation_Database_EntityManager $entityManager, $tablesPrefix, \Core_Foundation_Database_EntityMetaData $entityMetaData)
```





* Visibility: **public**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L35)


#### Arguments
* $entityManager **[Core_Foundation_Database_EntityManager](class.Core_Foundation_Database_EntityManager.md)**
* $tablesPrefix **mixed**
* $entityMetaData **[Core_Foundation_Database_EntityMetaData](class.Core_Foundation_Database_EntityMetaData.md)**



### <a name="method-convertToDbFieldName"></a>convertToDbFieldName

```php
string Core_Business_CMS_CMSRepository::convertToDbFieldName($camel_case_field_name)
```

Convert a camelCase field name to a snakeCase one
e.g.: findAllByIdCMS => id_cms



* Visibility: **private**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L81)


#### Arguments
* $camel_case_field_name **mixed**



### <a name="method-doFind"></a>doFind

```php
array|mixed|null Core_Business_CMS_CMSRepository::doFind($one, array $cumulativeConditions)
```

Constructs and performs 'SELECT' in DB



* Visibility: **private**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L183)


#### Arguments
* $one **mixed**
* $cumulativeConditions **array**



### <a name="method-findAll"></a>findAll

```php
array Core_Business_CMS_CMSRepository::findAll()
```

Find all entities in DB



* Visibility: **public**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L216)




### <a name="method-findOne"></a>findOne

```php
array|mixed|null Core_Business_CMS_CMSRepository::findOne($id)
```

Find one entity in DB



* Visibility: **public**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L204)


#### Arguments
* $id **mixed**



### <a name="method-getIdFieldName"></a>getIdFieldName

```php
mixed Core_Business_CMS_CMSRepository::getIdFieldName()
```

Return ID field name



* Visibility: **protected**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L91)




### <a name="method-getLanguageTableNameWithPrefix"></a>getLanguageTableNameWithPrefix

```php
string Core_Business_CMS_CMSRepository::getLanguageTableNameWithPrefix()
```

Return CMSRepository lang associative table name



* Visibility: **private**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L33)




### <a name="method-getNewEntity"></a>getNewEntity

```php
mixed Core_Business_CMS_CMSRepository::getNewEntity()
```

Return a new empty Entity depending on current Repository selected



* Visibility: **public**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L136)




### <a name="method-getPrefix"></a>getPrefix

```php
mixed Core_Business_CMS_CMSRepository::getPrefix()
```

Returns escaped DB table prefix



* Visibility: **protected**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L127)




### <a name="method-getTableNameWithPrefix"></a>getTableNameWithPrefix

```php
mixed Core_Business_CMS_CMSRepository::getTableNameWithPrefix()
```

Returns escaped+prefixed current table name



* Visibility: **protected**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L118)




### <a name="method-hydrateMany"></a>hydrateMany

```php
mixed Core_Business_CMS_CMSRepository::hydrateMany(array $rows)
```





* Visibility: **protected**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L165)


#### Arguments
* $rows **array**



### <a name="method-hydrateOne"></a>hydrateOne

```php
mixed Core_Business_CMS_CMSRepository::hydrateOne(array $rows)
```

This function takes an array of database rows as input
and returns an hydrated entity if there is one row only.

Null is returned when there are no rows, and an exception is thrown
if there are too many rows.

* Visibility: **protected**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L151)


#### Arguments
* $rows **array** - Database rows



### <a name="method-i10nFindAll"></a>i10nFindAll

```php
array|null Core_Business_CMS_CMSRepository::i10nFindAll($id_lang, $id_shop)
```

Return all CMSRepositories depending on $id_lang/$id_shop tuple



* Visibility: **public**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L44)


#### Arguments
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-i10nFindOneById"></a>i10nFindOneById

```php
\CMS|null Core_Business_CMS_CMSRepository::i10nFindOneById($id_cms, $id_lang, $id_shop)
```

Return all CMSRepositories depending on $id_lang/$id_shop tuple



* Visibility: **public**
* Source: [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L66)


#### Arguments
* $id_cms **mixed**
* $id_lang **mixed**
* $id_shop **mixed**


