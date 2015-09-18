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





Properties
----------


### $db

    private mixed $db





* Visibility: **private**


### $configuration

    private mixed $configuration





* Visibility: **private**


### $entityMetaData

    private mixed $entityMetaData = array()





* Visibility: **private**


Methods
-------


### __construct

    mixed Core_Foundation_Database_EntityManager::__construct(\Core_Foundation_Database_DatabaseInterface $db, \Core_Business_ConfigurationInterface $configuration)





* Visibility: **public**


#### Arguments
* $db **[Core_Foundation_Database_DatabaseInterface](Core_Foundation_Database_DatabaseInterface.md)**
* $configuration **[Core_Business_ConfigurationInterface](Core_Business_ConfigurationInterface.md)**



### getDatabase

    \Core_Foundation_Database_DatabaseInterface Core_Foundation_Database_EntityManager::getDatabase()

Return current database object used



* Visibility: **public**




### getRepository

    mixed Core_Foundation_Database_EntityManager::getRepository($className)

Return current repository used



* Visibility: **public**


#### Arguments
* $className **mixed**



### getEntityMetaData

    mixed Core_Foundation_Database_EntityManager::getEntityMetaData($className)

Return entity's meta data



* Visibility: **public**


#### Arguments
* $className **mixed**



### save

    \Core_Foundation_Database_EntityManager Core_Foundation_Database_EntityManager::save(\Core_Foundation_Database_EntityInterface $entity)

Flush entity to DB



* Visibility: **public**


#### Arguments
* $entity **[Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface.md)**



### delete

    \Core_Foundation_Database_EntityManager Core_Foundation_Database_EntityManager::delete(\Core_Foundation_Database_EntityInterface $entity)

DElete entity from DB



* Visibility: **public**


#### Arguments
* $entity **[Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface.md)**


