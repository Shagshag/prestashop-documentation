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
* Parent class: [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)

* This class is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#27)





Properties
----------


### $entityManager

    protected mixed $entityManager





* Visibility: **protected**
* This property is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#29)


### $db

    protected mixed $db





* Visibility: **protected**
* This property is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#30)


### $tablesPrefix

    protected mixed $tablesPrefix





* Visibility: **protected**
* This property is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#31)


### $entityMetaData

    protected mixed $entityMetaData





* Visibility: **protected**
* This property is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#32)


### $queryBuilder

    protected mixed $queryBuilder





* Visibility: **protected**
* This property is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#33)


Methods
-------


### getCMSRolesAssociated

    array|null Core_Business_CMS_CMSRoleRepository::getCMSRolesAssociated()

Return all CMSRoles which are already associated



* Visibility: **public**
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#33)




### __construct

    mixed Core_Foundation_Database_EntityRepository::__construct(\Core_Foundation_Database_EntityManager $entityManager, $tablesPrefix, \Core_Foundation_Database_EntityMetaData $entityMetaData)





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#35)


#### Arguments
* $entityManager **[Core_Foundation_Database_EntityManager](Core_Foundation_Database_EntityManager)**
* $tablesPrefix **mixed**
* $entityMetaData **[Core_Foundation_Database_EntityMetaData](Core_Foundation_Database_EntityMetaData)**



### __call

    mixed Core_Foundation_Database_EntityRepository::__call($method, $arguments)





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#47)


#### Arguments
* $method **mixed**
* $arguments **mixed**



### convertToDbFieldName

    string Core_Foundation_Database_EntityRepository::convertToDbFieldName($camel_case_field_name)

Convert a camelCase field name to a snakeCase one
e.g.: findAllByIdCMS => id_cms



* Visibility: **private**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#80)


#### Arguments
* $camel_case_field_name **mixed**



### getIdFieldName

    mixed Core_Foundation_Database_EntityRepository::getIdFieldName()

Return ID field name



* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#90)




### getTableNameWithPrefix

    mixed Core_Foundation_Database_EntityRepository::getTableNameWithPrefix()

Returns escaped+prefixed current table name



* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#117)




### getPrefix

    mixed Core_Foundation_Database_EntityRepository::getPrefix()

Returns escaped DB table prefix



* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#126)




### getNewEntity

    mixed Core_Foundation_Database_EntityRepository::getNewEntity()

Return a new empty Entity depending on current Repository selected



* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#135)




### hydrateOne

    mixed Core_Foundation_Database_EntityRepository::hydrateOne(array $rows)

This function takes an array of database rows as input
and returns an hydrated entity if there is one row only.

Null is returned when there are no rows, and an exception is thrown
if there are too many rows.

* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#150)


#### Arguments
* $rows **array** - &lt;p&gt;Database rows&lt;/p&gt;



### hydrateMany

    mixed Core_Foundation_Database_EntityRepository::hydrateMany(array $rows)





* Visibility: **protected**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#164)


#### Arguments
* $rows **array**



### doFind

    array|mixed|null Core_Foundation_Database_EntityRepository::doFind($one, array $cumulativeConditions)

Constructs and performs 'SELECT' in DB



* Visibility: **private**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#182)


#### Arguments
* $one **mixed**
* $cumulativeConditions **array**



### findOne

    array|mixed|null Core_Foundation_Database_EntityRepository::findOne($id)

Find one entity in DB



* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#203)


#### Arguments
* $id **mixed**



### findAll

    array Core_Foundation_Database_EntityRepository::findAll()

Find all entities in DB



* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityRepository](Core_Foundation_Database_EntityRepository)
* This method is defined in [Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/CMS/Core_Business_CMS_CMSRoleRepository.php#215)



