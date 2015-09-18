Core_Business_CMS_CMSRoleRepository
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


* Class name: Core_Business_CMS_CMSRoleRepository
* Namespace: 
* Parent class: [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository.md)





Properties
----------


### $entityManager

    protected mixed $entityManager





* Visibility: **protected**


### $db

    protected mixed $db





* Visibility: **protected**


### $tablesPrefix

    protected mixed $tablesPrefix





* Visibility: **protected**


### $entityMetaData

    protected mixed $entityMetaData





* Visibility: **protected**


### $queryBuilder

    protected mixed $queryBuilder





* Visibility: **protected**


Methods
-------


### getCMSRolesAssociated

    array|null Core_Business_CMS_CMSRoleRepository::getCMSRolesAssociated()

Return all CMSRoles which are already associated



* Visibility: **public**




### __construct

    mixed Core_Foundation_Database_EntityRepository::__construct(\Core_Foundation_Database_EntityManager $entityManager, $tablesPrefix, \Core_Foundation_Database_EntityMetaData $entityMetaData)





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository.md)


#### Arguments
* $entityManager **[Core_Foundation_Database_EntityManager](Core_Foundation_Database_EntityManager.md)**
* $tablesPrefix **mixed**
* $entityMetaData **[Core_Foundation_Database_EntityMetaData](Core_Foundation_Database_EntityMetaData.md)**



### __call

    mixed Core_Foundation_Database_EntityRepository::__call($method, $arguments)





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository.md)


#### Arguments
* $method **mixed**
* $arguments **mixed**



### convertToDbFieldName

    string Core_Foundation_Database_EntityRepository::convertToDbFieldName($camel_case_field_name)

Convert a camelCase field name to a snakeCase one
e.g.: findAllByIdCMS => id_cms



* Visibility: **private**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository.md)


#### Arguments
* $camel_case_field_name **mixed**



### getIdFieldName

    mixed Core_Foundation_Database_EntityRepository::getIdFieldName()

Return ID field name



* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository.md)




### getTableNameWithPrefix

    mixed Core_Foundation_Database_EntityRepository::getTableNameWithPrefix()

Returns escaped+prefixed current table name



* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository.md)




### getPrefix

    mixed Core_Foundation_Database_EntityRepository::getPrefix()

Returns escaped DB table prefix



* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository.md)




### getNewEntity

    mixed Core_Foundation_Database_EntityRepository::getNewEntity()

Return a new empty Entity depending on current Repository selected



* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository.md)




### hydrateOne

    mixed Core_Foundation_Database_EntityRepository::hydrateOne(array $rows)

This function takes an array of database rows as input
and returns an hydrated entity if there is one row only.

Null is returned when there are no rows, and an exception is thrown
if there are too many rows.

* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository.md)


#### Arguments
* $rows **array** - &lt;p&gt;Database rows&lt;/p&gt;



### hydrateMany

    mixed Core_Foundation_Database_EntityRepository::hydrateMany(array $rows)





* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository.md)


#### Arguments
* $rows **array**



### doFind

    array|mixed|null Core_Foundation_Database_EntityRepository::doFind($one, array $cumulativeConditions)

Constructs and performs 'SELECT' in DB



* Visibility: **private**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository.md)


#### Arguments
* $one **mixed**
* $cumulativeConditions **array**



### findOne

    array|mixed|null Core_Foundation_Database_EntityRepository::findOne($id)

Find one entity in DB



* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository.md)


#### Arguments
* $id **mixed**



### findAll

    array Core_Foundation_Database_EntityRepository::findAll()

Find all entities in DB



* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository.md)



