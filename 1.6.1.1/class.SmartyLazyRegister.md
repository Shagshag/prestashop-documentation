Class SmartyLazyRegister
=====================

Used to delay loading of external classes with smarty-&gt;register_plugin



* Class name: SmartyLazyRegister
* Source: [config/smarty.config.inc.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/config/smarty.config.inc.php#L225)



Properties
----------

* [$instance](#property-$instance)
* [$registry](#property-$registry)

Methods
-------
* [__call](#method-__call)
* [getInstance](#method-getInstance)
* [register](#method-register)




Properties
----------


### <a name="property-$instance"></a>$instance

    protected mixed $instance





* Visibility: **protected**
* This property is **static**.
* Source: [config/smarty.config.inc.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/config/smarty.config.inc.php#L228).


### <a name="property-$registry"></a>$registry

    protected mixed $registry = array()





* Visibility: **protected**
* Source: [config/smarty.config.inc.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/config/smarty.config.inc.php#L227).


Methods
-------


### <a name="method-__call"></a>__call

    mixed SmartyLazyRegister::__call(string $name, mixed $arguments)

Dynamically call static function or method



* Visibility: **public**
* Source: [config/smarty.config.inc.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/config/smarty.config.inc.php#L250)


#### Arguments
* $name **string** - function name
* $arguments **mixed** - function argument



### <a name="method-getInstance"></a>getInstance

    mixed SmartyLazyRegister::getInstance()





* Visibility: **public**
* This method is **static**.
* Source: [config/smarty.config.inc.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/config/smarty.config.inc.php#L272)




### <a name="method-register"></a>register

    mixed SmartyLazyRegister::register(string|array $params)

Register a function or method to be dynamically called later



* Visibility: **public**
* Source: [config/smarty.config.inc.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/config/smarty.config.inc.php#L234)


#### Arguments
* $params **string|array** - function name or array(object name, method name)


