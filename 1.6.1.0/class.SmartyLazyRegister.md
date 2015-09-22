Class SmartyLazyRegister
=====================

Used to delay loading of external classes with smarty-&gt;register_plugin



* Class name: SmartyLazyRegister
* Source: [config/smarty.config.inc.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/config/smarty.config.inc.php#L216)


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
* Source: [config/smarty.config.inc.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/config/smarty.config.inc.php#L219).


### <a name="property-$registry"></a>$registry

```php
protected mixed $registry = array()
```





* Visibility: **protected**
* Source: [config/smarty.config.inc.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/config/smarty.config.inc.php#L218).


Methods
-------


### <a name="method-__call"></a>__call

```php
mixed SmartyLazyRegister::__call(string $name, mixed $arguments)
```

Dynamically call static function or method



* Visibility: **public**
* Source: [config/smarty.config.inc.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/config/smarty.config.inc.php#L240)


#### Arguments
* $name **string** - function name
* $arguments **mixed** - function argument



### <a name="method-getInstance"></a>getInstance

```php
mixed SmartyLazyRegister::getInstance()
```





* Visibility: **public**
* This method is **static**.
* Source: [config/smarty.config.inc.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/config/smarty.config.inc.php#L261)




### <a name="method-register"></a>register

```php
mixed SmartyLazyRegister::register(string|array $params)
```

Register a function or method to be dynamically called later



* Visibility: **public**
* Source: [config/smarty.config.inc.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/config/smarty.config.inc.php#L225)


#### Arguments
* $params **string|array** - function name or array(object name, method name)


