Core_Foundation_Database_EntityManager
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


* Class name: Core_Foundation_Database_EntityManager
* Namespace: 
* This class is defined in Core\Foundation\Database\Core_Foundation_Database_EntityManager.php line 27





Properties
----------


### $db

    private mixed $db





* Visibility: **private**
* This property is defined in Core\Foundation\Database\Core_Foundation_Database_EntityManager.php line 29


### $configuration

    private mixed $configuration





* Visibility: **private**
* This property is defined in Core\Foundation\Database\Core_Foundation_Database_EntityManager.php line 30


### $entityMetaData

    private mixed $entityMetaData = array()





* Visibility: **private**
* This property is defined in Core\Foundation\Database\Core_Foundation_Database_EntityManager.php line 32


Methods
-------


### __construct

    mixed Core_Foundation_Database_EntityManager::__construct(\Core_Foundation_Database_DatabaseInterface $db, \Core_Business_ConfigurationInterface $configuration)





* Visibility: **public**
* This method is defined in Core\Foundation\Database\Core_Foundation_Database_EntityManager.php line 34


#### Arguments
* $db **[Core_Foundation_Database_DatabaseInterface](Core_Foundation_Database_DatabaseInterface)**
* $configuration **[Core_Business_ConfigurationInterface](Core_Business_ConfigurationInterface)**



### getDatabase

    \Core_Foundation_Database_DatabaseInterface Core_Foundation_Database_EntityManager::getDatabase()

Return current database object used



* Visibility: **public**
* This method is defined in Core\Foundation\Database\Core_Foundation_Database_EntityManager.php line 46




### getRepository

    mixed Core_Foundation_Database_EntityManager::getRepository($className)

Return current repository used



* Visibility: **public**
* This method is defined in Core\Foundation\Database\Core_Foundation_Database_EntityManager.php line 56


#### Arguments
* $className **mixed**



### getEntityMetaData

    mixed Core_Foundation_Database_EntityManager::getEntityMetaData($className)

Return entity's meta data



* Visibility: **public**
* This method is defined in Core\Foundation\Database\Core_Foundation_Database_EntityManager.php line 83


#### Arguments
* $className **mixed**



### save

    \Core_Foundation_Database_EntityManager Core_Foundation_Database_EntityManager::save(\Core_Foundation_Database_EntityInterface $entity)

Flush entity to DB



* Visibility: **public**
* This method is defined in Core\Foundation\Database\Core_Foundation_Database_EntityManager.php line 98


#### Arguments
* $entity **[Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)**



### delete

    \Core_Foundation_Database_EntityManager Core_Foundation_Database_EntityManager::delete(\Core_Foundation_Database_EntityInterface $entity)

DElete entity from DB



* Visibility: **public**
* This method is defined in Core\Foundation\Database\Core_Foundation_Database_EntityManager.php line 109


#### Arguments
* $entity **[Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)**


