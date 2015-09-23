Class SmartyLazyRegister
=====================

Used to delay loading of external classes with smarty-&gt;register_plugin



* Class name: SmartyLazyRegister
* Source: [config/smarty.config.inc.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/config/smarty.config.inc.php#L206)


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
* Source: [config/smarty.config.inc.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/config/smarty.config.inc.php#L209).


### <a name="property-$registry"></a>$registry

```php
protected mixed $registry = array()
```





* Visibility: **protected**
* Source: [config/smarty.config.inc.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/config/smarty.config.inc.php#L208).


Methods
-------


### <a name="method-__call"></a>__call

```php
mixed SmartyLazyRegister::__call(string $name, mixed $arguments)
```

Dynamically call static function or method



* Visibility: **public**
* Source: [config/smarty.config.inc.php line 230](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/config/smarty.config.inc.php#L230)


#### Arguments
* $name **string** - function name
* $arguments **mixed** - function argument



### <a name="method-getInstance"></a>getInstance

```php
mixed SmartyLazyRegister::getInstance()
```





* Visibility: **public**
* This method is **static**.
* Source: [config/smarty.config.inc.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/config/smarty.config.inc.php#L251)




### <a name="method-register"></a>register

```php
mixed SmartyLazyRegister::register(string|array $params)
```

Register a function or method to be dynamically called later



* Visibility: **public**
* Source: [config/smarty.config.inc.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/config/smarty.config.inc.php#L215)


#### Arguments
* $params **string|array** - function name or array(object name, method name)


