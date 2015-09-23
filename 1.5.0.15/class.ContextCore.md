Class ContextCore
=====================





* Class name: ContextCore
* Source: [classes/Context.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L31)


Contents
--------


### Properties

* [$cart](#property-$cart)
* [$controller](#property-$controller)
* [$cookie](#property-$cookie)
* [$country](#property-$country)
* [$currency](#property-$currency)
* [$customer](#property-$customer)
* [$employee](#property-$employee)
* [$instance](#property-$instance)
* [$language](#property-$language)
* [$link](#property-$link)
* [$shop](#property-$shop)
* [$smarty](#property-$smarty)
* [$tab](#property-$tab)

### Methods

* [cloneContext](#method-cloneContext)
* [getContext](#method-getContext)




Properties
----------


### <a name="property-$cart"></a>$cart

```php
public \Cart $cart
```





* Visibility: **public**
* Source: [classes/Context.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L41).


### <a name="property-$controller"></a>$controller

```php
public \Controller $controller
```





* Visibility: **public**
* Source: [classes/Context.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L71).


### <a name="property-$cookie"></a>$cookie

```php
public \Cookie $cookie
```





* Visibility: **public**
* Source: [classes/Context.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L51).


### <a name="property-$country"></a>$country

```php
public \Country $country
```





* Visibility: **public**
* Source: [classes/Context.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L61).


### <a name="property-$currency"></a>$currency

```php
public \Currency $currency
```





* Visibility: **public**
* Source: [classes/Context.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L81).


### <a name="property-$customer"></a>$customer

```php
public \Customer $customer
```





* Visibility: **public**
* Source: [classes/Context.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L46).


### <a name="property-$employee"></a>$employee

```php
public \Employee $employee
```





* Visibility: **public**
* Source: [classes/Context.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L66).


### <a name="property-$instance"></a>$instance

```php
protected \Context $instance
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Context.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L36).


### <a name="property-$language"></a>$language

```php
public \Language $language
```





* Visibility: **public**
* Source: [classes/Context.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L76).


### <a name="property-$link"></a>$link

```php
public \Link $link
```





* Visibility: **public**
* Source: [classes/Context.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L56).


### <a name="property-$shop"></a>$shop

```php
public \Shop $shop
```





* Visibility: **public**
* Source: [classes/Context.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L91).


### <a name="property-$smarty"></a>$smarty

```php
public \Smarty $smarty
```





* Visibility: **public**
* Source: [classes/Context.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L96).


### <a name="property-$tab"></a>$tab

```php
public \AdminTab $tab
```





* Visibility: **public**
* Source: [classes/Context.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L86).


Methods
-------


### <a name="method-cloneContext"></a>cloneContext

```php
\Context ContextCore::cloneContext()
```

Clone current context



* Visibility: **public**
* Source: [classes/Context.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L115)




### <a name="method-getContext"></a>getContext

```php
\Context ContextCore::getContext()
```

Get a singleton context



* Visibility: **public**
* This method is **static**.
* Source: [classes/Context.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.15/classes/Context.php#L103)



