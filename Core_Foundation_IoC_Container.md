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





Properties
----------


### $bindings

    private mixed $bindings = array()





* Visibility: **private**


### $instances

    private mixed $instances = array()





* Visibility: **private**


### $namespaceAliases

    private mixed $namespaceAliases = array()





* Visibility: **private**


Methods
-------


### knows

    mixed Core_Foundation_IoC_Container::knows($serviceName)





* Visibility: **public**


#### Arguments
* $serviceName **mixed**



### knowsNamespaceAlias

    mixed Core_Foundation_IoC_Container::knowsNamespaceAlias($alias)





* Visibility: **private**


#### Arguments
* $alias **mixed**



### bind

    mixed Core_Foundation_IoC_Container::bind($serviceName, $constructor, $shared)





* Visibility: **public**


#### Arguments
* $serviceName **mixed**
* $constructor **mixed**
* $shared **mixed**



### aliasNamespace

    mixed Core_Foundation_IoC_Container::aliasNamespace($alias, $namespacePrefix)





* Visibility: **public**


#### Arguments
* $alias **mixed**
* $namespacePrefix **mixed**



### resolveClassName

    mixed Core_Foundation_IoC_Container::resolveClassName($className)





* Visibility: **public**


#### Arguments
* $className **mixed**



### makeInstanceFromClassName

    mixed Core_Foundation_IoC_Container::makeInstanceFromClassName($className, array $alreadySeen)





* Visibility: **private**


#### Arguments
* $className **mixed**
* $alreadySeen **array**



### doMake

    mixed Core_Foundation_IoC_Container::doMake($serviceName, array $alreadySeen)





* Visibility: **private**


#### Arguments
* $serviceName **mixed**
* $alreadySeen **array**



### make

    mixed Core_Foundation_IoC_Container::make($serviceName)





* Visibility: **public**


#### Arguments
* $serviceName **mixed**


