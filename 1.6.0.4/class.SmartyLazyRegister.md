Class SmartyLazyRegister
=====================

Used to delay loading of external classes with smarty-&gt;register_plugin



* Class name: SmartyLazyRegister
* Source: [config/smarty.config.inc.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/config/smarty.config.inc.php#L212)


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
* Source: [config/smarty.config.inc.php line 215](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/config/smarty.config.inc.php#L215).


### <a name="property-$registry"></a>$registry

```php
protected mixed $registry = array()
```





* Visibility: **protected**
* Source: [config/smarty.config.inc.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/config/smarty.config.inc.php#L214).


Methods
-------


### <a name="method-__call"></a>__call

```php
mixed SmartyLazyRegister::__call(string $name, mixed $arguments)
```

Dynamically call static function or method



* Visibility: **public**
* Source: [config/smarty.config.inc.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/config/smarty.config.inc.php#L236)


#### Arguments
* $name **string** - function name
* $arguments **mixed** - function argument



### <a name="method-getInstance"></a>getInstance

```php
mixed SmartyLazyRegister::getInstance()
```





* Visibility: **public**
* This method is **static**.
* Source: [config/smarty.config.inc.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/config/smarty.config.inc.php#L257)




### <a name="method-register"></a>register

```php
mixed SmartyLazyRegister::register(string|array $params)
```

Register a function or method to be dynamically called later



* Visibility: **public**
* Source: [config/smarty.config.inc.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/config/smarty.config.inc.php#L221)


#### Arguments
* $params **string|array** - function name or array(object name, method name)


