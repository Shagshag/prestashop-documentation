Class SmartyLazyRegister
=====================

Used to delay loading of external classes with smarty-&gt;register_plugin



* Class name: SmartyLazyRegister
* Source: [config/smarty.config.inc.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/config/smarty.config.inc.php#L204)


Contents
--------


### Properties

* [$instance](#property-$instance)
* [$registry](#property-$registry)

### Methods

* [__call](#method-__call)
* [getInstance](#method-getInstance)
* [register](#method-register)




Properties
----------


### <a name="property-$instance"></a>$instance

```php
protected mixed $instance
```





* Visibility: **protected**
* This property is **static**.
* Source: [config/smarty.config.inc.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/config/smarty.config.inc.php#L207).


### <a name="property-$registry"></a>$registry

```php
protected mixed $registry = array()
```





* Visibility: **protected**
* Source: [config/smarty.config.inc.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/config/smarty.config.inc.php#L206).


Methods
-------


### <a name="method-__call"></a>__call

```php
mixed SmartyLazyRegister::__call($name, $arguments)
```

Dynamically call static function or method



* Visibility: **public**
* Source: [config/smarty.config.inc.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/config/smarty.config.inc.php#L228)


#### Arguments
* $name **mixed** - function name
* $arguments **mixed** - function argument



### <a name="method-getInstance"></a>getInstance

```php
mixed SmartyLazyRegister::getInstance()
```





* Visibility: **public**
* This method is **static**.
* Source: [config/smarty.config.inc.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/config/smarty.config.inc.php#L249)




### <a name="method-register"></a>register

```php
mixed SmartyLazyRegister::register($params)
```

Register a function or method to be dynamically called later



* Visibility: **public**
* Source: [config/smarty.config.inc.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/config/smarty.config.inc.php#L213)


#### Arguments
* $params **mixed** - function name or array(object name, method name)


