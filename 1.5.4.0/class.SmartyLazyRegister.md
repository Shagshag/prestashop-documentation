Class SmartyLazyRegister
=====================

Used to delay loading of external classes with smarty-&gt;register_plugin



* Class name: SmartyLazyRegister
* Source: [config/smarty.config.inc.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/config/smarty.config.inc.php#L197)


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
* Source: [config/smarty.config.inc.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/config/smarty.config.inc.php#L200).


### <a name="property-$registry"></a>$registry

```php
protected mixed $registry = array()
```





* Visibility: **protected**
* Source: [config/smarty.config.inc.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/config/smarty.config.inc.php#L199).


Methods
-------


### <a name="method-__call"></a>__call

```php
mixed SmartyLazyRegister::__call($name, $arguments)
```

Dynamically call static function or method



* Visibility: **public**
* Source: [config/smarty.config.inc.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/config/smarty.config.inc.php#L221)


#### Arguments
* $name **mixed** - function name
* $arguments **mixed** - function argument



### <a name="method-getInstance"></a>getInstance

```php
mixed SmartyLazyRegister::getInstance()
```





* Visibility: **public**
* This method is **static**.
* Source: [config/smarty.config.inc.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/config/smarty.config.inc.php#L242)




### <a name="method-register"></a>register

```php
mixed SmartyLazyRegister::register($params)
```

Register a function or method to be dynamically called later



* Visibility: **public**
* Source: [config/smarty.config.inc.php line 206](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/config/smarty.config.inc.php#L206)


#### Arguments
* $params **mixed** - function name or array(object name, method name)


