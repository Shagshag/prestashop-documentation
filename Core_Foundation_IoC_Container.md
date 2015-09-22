Core_Foundation_IoC_Container
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


* Class name: Core_Foundation_IoC_Container
* Namespace: 

* This class is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#27)





Properties
----------


### $bindings

    private mixed $bindings = array()





* Visibility: **private**
* This property is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#29)


### $instances

    private mixed $instances = array()





* Visibility: **private**
* This property is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#30)


### $namespaceAliases

    private mixed $namespaceAliases = array()





* Visibility: **private**
* This property is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#31)


Methods
-------


### knows

    mixed Core_Foundation_IoC_Container::knows($serviceName)





* Visibility: **public**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#33)


#### Arguments
* $serviceName **mixed**



### knowsNamespaceAlias

    mixed Core_Foundation_IoC_Container::knowsNamespaceAlias($alias)





* Visibility: **private**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#38)


#### Arguments
* $alias **mixed**



### bind

    mixed Core_Foundation_IoC_Container::bind($serviceName, $constructor, $shared)





* Visibility: **public**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#43)


#### Arguments
* $serviceName **mixed**
* $constructor **mixed**
* $shared **mixed**



### aliasNamespace

    mixed Core_Foundation_IoC_Container::aliasNamespace($alias, $namespacePrefix)





* Visibility: **public**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#59)


#### Arguments
* $alias **mixed**
* $namespacePrefix **mixed**



### resolveClassName

    mixed Core_Foundation_IoC_Container::resolveClassName($className)





* Visibility: **public**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#74)


#### Arguments
* $className **mixed**



### makeInstanceFromClassName

    mixed Core_Foundation_IoC_Container::makeInstanceFromClassName($className, array $alreadySeen)





* Visibility: **private**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#88)


#### Arguments
* $className **mixed**
* $alreadySeen **array**



### doMake

    mixed Core_Foundation_IoC_Container::doMake($serviceName, array $alreadySeen)





* Visibility: **private**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#128)


#### Arguments
* $serviceName **mixed**
* $alreadySeen **array**



### make

    mixed Core_Foundation_IoC_Container::make($serviceName)





* Visibility: **public**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#168)


#### Arguments
* $serviceName **mixed**


