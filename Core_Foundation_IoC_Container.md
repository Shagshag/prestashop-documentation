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
* This class is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L27)





Properties
----------

* [$bindings](#property-$bindings)
* [$instances](#property-$instances)
* [$namespaceAliases](#property-$namespaceAliases)

Methods
-------
* [knows](#method-knows)
* [knowsNamespaceAlias](#method-knowsNamespaceAlias)
* [bind](#method-bind)
* [aliasNamespace](#method-aliasNamespace)
* [resolveClassName](#method-resolveClassName)
* [makeInstanceFromClassName](#method-makeInstanceFromClassName)
* [doMake](#method-doMake)
* [make](#method-make)




Properties
----------


### <a name="property-$bindings"></a>$bindings

    private mixed $bindings = array()





* Visibility: **private**
* This property is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L29)


### <a name="property-$instances"></a>$instances

    private mixed $instances = array()





* Visibility: **private**
* This property is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L30)


### <a name="property-$namespaceAliases"></a>$namespaceAliases

    private mixed $namespaceAliases = array()





* Visibility: **private**
* This property is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L31)


Methods
-------


### <a name="method-knows"></a>knows

    mixed Core_Foundation_IoC_Container::knows($serviceName)





* Visibility: **public**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L33)


#### Arguments
* $serviceName **mixed**



### <a name="method-knowsNamespaceAlias"></a>knowsNamespaceAlias

    mixed Core_Foundation_IoC_Container::knowsNamespaceAlias($alias)





* Visibility: **private**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L38)


#### Arguments
* $alias **mixed**



### <a name="method-bind"></a>bind

    mixed Core_Foundation_IoC_Container::bind($serviceName, $constructor, $shared)





* Visibility: **public**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L43)


#### Arguments
* $serviceName **mixed**
* $constructor **mixed**
* $shared **mixed**



### <a name="method-aliasNamespace"></a>aliasNamespace

    mixed Core_Foundation_IoC_Container::aliasNamespace($alias, $namespacePrefix)





* Visibility: **public**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L59)


#### Arguments
* $alias **mixed**
* $namespacePrefix **mixed**



### <a name="method-resolveClassName"></a>resolveClassName

    mixed Core_Foundation_IoC_Container::resolveClassName($className)





* Visibility: **public**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L74)


#### Arguments
* $className **mixed**



### <a name="method-makeInstanceFromClassName"></a>makeInstanceFromClassName

    mixed Core_Foundation_IoC_Container::makeInstanceFromClassName($className, array $alreadySeen)





* Visibility: **private**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L88)


#### Arguments
* $className **mixed**
* $alreadySeen **array**



### <a name="method-doMake"></a>doMake

    mixed Core_Foundation_IoC_Container::doMake($serviceName, array $alreadySeen)





* Visibility: **private**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L128)


#### Arguments
* $serviceName **mixed**
* $alreadySeen **array**



### <a name="method-make"></a>make

    mixed Core_Foundation_IoC_Container::make($serviceName)





* Visibility: **public**
* This method is defined in [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L168)


#### Arguments
* $serviceName **mixed**


