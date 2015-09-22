Class Core_Foundation_IoC_Container
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

* Class name: Core_Foundation_IoC_Container
* Source: [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L27)


Contents
--------


### Properties

* [$bindings](#property-$bindings)
* [$instances](#property-$instances)
* [$namespaceAliases](#property-$namespaceAliases)

### Methods

* [aliasNamespace](#method-aliasNamespace)
* [bind](#method-bind)
* [doMake](#method-doMake)
* [knows](#method-knows)
* [knowsNamespaceAlias](#method-knowsNamespaceAlias)
* [make](#method-make)
* [makeInstanceFromClassName](#method-makeInstanceFromClassName)
* [resolveClassName](#method-resolveClassName)




Properties
----------


### <a name="property-$bindings"></a>$bindings

```php
private mixed $bindings = array()
```





* Visibility: **private**
* Source: [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L29).


### <a name="property-$instances"></a>$instances

```php
private mixed $instances = array()
```





* Visibility: **private**
* Source: [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L30).


### <a name="property-$namespaceAliases"></a>$namespaceAliases

```php
private mixed $namespaceAliases = array()
```





* Visibility: **private**
* Source: [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L31).


Methods
-------


### <a name="method-aliasNamespace"></a>aliasNamespace

```php
mixed Core_Foundation_IoC_Container::aliasNamespace($alias, $namespacePrefix)
```





* Visibility: **public**
* Source: [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L59)


#### Arguments
* $alias **mixed**
* $namespacePrefix **mixed**



### <a name="method-bind"></a>bind

```php
mixed Core_Foundation_IoC_Container::bind($serviceName, $constructor, $shared)
```





* Visibility: **public**
* Source: [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L43)


#### Arguments
* $serviceName **mixed**
* $constructor **mixed**
* $shared **mixed**



### <a name="method-doMake"></a>doMake

```php
mixed Core_Foundation_IoC_Container::doMake($serviceName, array $alreadySeen)
```





* Visibility: **private**
* Source: [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L128)


#### Arguments
* $serviceName **mixed**
* $alreadySeen **array**



### <a name="method-knows"></a>knows

```php
mixed Core_Foundation_IoC_Container::knows($serviceName)
```





* Visibility: **public**
* Source: [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L33)


#### Arguments
* $serviceName **mixed**



### <a name="method-knowsNamespaceAlias"></a>knowsNamespaceAlias

```php
mixed Core_Foundation_IoC_Container::knowsNamespaceAlias($alias)
```





* Visibility: **private**
* Source: [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L38)


#### Arguments
* $alias **mixed**



### <a name="method-make"></a>make

```php
mixed Core_Foundation_IoC_Container::make($serviceName)
```





* Visibility: **public**
* Source: [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L168)


#### Arguments
* $serviceName **mixed**



### <a name="method-makeInstanceFromClassName"></a>makeInstanceFromClassName

```php
mixed Core_Foundation_IoC_Container::makeInstanceFromClassName($className, array $alreadySeen)
```





* Visibility: **private**
* Source: [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L88)


#### Arguments
* $className **mixed**
* $alreadySeen **array**



### <a name="method-resolveClassName"></a>resolveClassName

```php
mixed Core_Foundation_IoC_Container::resolveClassName($className)
```





* Visibility: **public**
* Source: [Core/Foundation/IoC/Core_Foundation_IoC_Container.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/IoC/Core_Foundation_IoC_Container.php#L74)


#### Arguments
* $className **mixed**


