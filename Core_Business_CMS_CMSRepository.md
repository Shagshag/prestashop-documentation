Core_Business_CMS_CMSRepository
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


* Class name: Core_Business_CMS_CMSRepository
* Parent class: [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This class is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L27)





Properties
----------

* [$entityManager](#property-$entityManager)
* [$db](#property-$db)
* [$tablesPrefix](#property-$tablesPrefix)
* [$entityMetaData](#property-$entityMetaData)
* [$queryBuilder](#property-$queryBuilder)

Methods
-------
* [getLanguageTableNameWithPrefix](#method-getLanguageTableNameWithPrefix)
* [i10nFindAll](#method-i10nFindAll)
* [i10nFindOneById](#method-i10nFindOneById)
* [__construct](#method-__construct)
* [__call](#method-__call)
* [convertToDbFieldName](#method-convertToDbFieldName)
* [getIdFieldName](#method-getIdFieldName)
* [getTableNameWithPrefix](#method-getTableNameWithPrefix)
* [getPrefix](#method-getPrefix)
* [getNewEntity](#method-getNewEntity)
* [hydrateOne](#method-hydrateOne)
* [hydrateMany](#method-hydrateMany)
* [doFind](#method-doFind)
* [findOne](#method-findOne)
* [findAll](#method-findAll)




Properties
----------


### <a name="property-$entityManager"></a>$entityManager

    protected mixed $entityManager





* Visibility: **protected**
* This property is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L29)


### <a name="property-$db"></a>$db

    protected mixed $db





* Visibility: **protected**
* This property is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L30)


### <a name="property-$tablesPrefix"></a>$tablesPrefix

    protected mixed $tablesPrefix





* Visibility: **protected**
* This property is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L31)


### <a name="property-$entityMetaData"></a>$entityMetaData

    protected mixed $entityMetaData





* Visibility: **protected**
* This property is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L32)


### <a name="property-$queryBuilder"></a>$queryBuilder

    protected mixed $queryBuilder





* Visibility: **protected**
* This property is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L33)


Methods
-------


### <a name="method-getLanguageTableNameWithPrefix"></a>getLanguageTableNameWithPrefix

    string Core_Business_CMS_CMSRepository::getLanguageTableNameWithPrefix()

Return CMSRepository lang associative table name



* Visibility: **private**
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L33)




### <a name="method-i10nFindAll"></a>i10nFindAll

    array|null Core_Business_CMS_CMSRepository::i10nFindAll($id_lang, $id_shop)

Return all CMSRepositories depending on $id_lang/$id_shop tuple



* Visibility: **public**
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L44)


#### Arguments
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-i10nFindOneById"></a>i10nFindOneById

    \CMS|null Core_Business_CMS_CMSRepository::i10nFindOneById($id_cms, $id_lang, $id_shop)

Return all CMSRepositories depending on $id_lang/$id_shop tuple



* Visibility: **public**
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L66)


#### Arguments
* $id_cms **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-__construct"></a>__construct

    mixed Core_Foundation_Database_EntityRepository::__construct(\Core_Foundation_Database_EntityManager $entityManager, $tablesPrefix, \Core_Foundation_Database_EntityMetaData $entityMetaData)





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L35)


#### Arguments
* $entityManager **[Core_Foundation_Database_EntityManager](Core_Foundation_Database_EntityManager)**
* $tablesPrefix **mixed**
* $entityMetaData **[Core_Foundation_Database_EntityMetaData](Core_Foundation_Database_EntityMetaData)**



### <a name="method-__call"></a>__call

    mixed Core_Foundation_Database_EntityRepository::__call($method, $arguments)





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L47)


#### Arguments
* $method **mixed**
* $arguments **mixed**



### <a name="method-convertToDbFieldName"></a>convertToDbFieldName

    string Core_Foundation_Database_EntityRepository::convertToDbFieldName($camel_case_field_name)

Convert a camelCase field name to a snakeCase one
e.g.: findAllByIdCMS => id_cms



* Visibility: **private**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L80)


#### Arguments
* $camel_case_field_name **mixed**



### <a name="method-getIdFieldName"></a>getIdFieldName

    mixed Core_Foundation_Database_EntityRepository::getIdFieldName()

Return ID field name



* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L90)




### <a name="method-getTableNameWithPrefix"></a>getTableNameWithPrefix

    mixed Core_Foundation_Database_EntityRepository::getTableNameWithPrefix()

Returns escaped+prefixed current table name



* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L117)




### <a name="method-getPrefix"></a>getPrefix

    mixed Core_Foundation_Database_EntityRepository::getPrefix()

Returns escaped DB table prefix



* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L126)




### <a name="method-getNewEntity"></a>getNewEntity

    mixed Core_Foundation_Database_EntityRepository::getNewEntity()

Return a new empty Entity depending on current Repository selected



* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L135)




### <a name="method-hydrateOne"></a>hydrateOne

    mixed Core_Foundation_Database_EntityRepository::hydrateOne(array $rows)

This function takes an array of database rows as input
and returns an hydrated entity if there is one row only.

Null is returned when there are no rows, and an exception is thrown
if there are too many rows.

* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L150)


#### Arguments
* $rows **array** - &lt;p&gt;Database rows&lt;/p&gt;



### <a name="method-hydrateMany"></a>hydrateMany

    mixed Core_Foundation_Database_EntityRepository::hydrateMany(array $rows)





* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L164)


#### Arguments
* $rows **array**



### <a name="method-doFind"></a>doFind

    array|mixed|null Core_Foundation_Database_EntityRepository::doFind($one, array $cumulativeConditions)

Constructs and performs 'SELECT' in DB



* Visibility: **private**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L182)


#### Arguments
* $one **mixed**
* $cumulativeConditions **array**



### <a name="method-findOne"></a>findOne

    array|mixed|null Core_Foundation_Database_EntityRepository::findOne($id)

Find one entity in DB



* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L203)


#### Arguments
* $id **mixed**



### <a name="method-findAll"></a>findAll

    array Core_Foundation_Database_EntityRepository::findAll()

Find all entities in DB



* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRepository.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRepository.php#L215)



