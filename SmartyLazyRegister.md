SmartyLazyRegister
===============

Used to delay loading of external classes with smarty-&gt;register_plugin




* Class name: SmartyLazyRegister
* This class is defined in [config/smarty.config.inc.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/config/smarty.config.inc.php#L225)





Properties
----------

* [$registry](#property-$registry)
* [$instance](#property-$instance)

Methods
-------
* [register](#method-register)
* [__call](#method-__call)
* [getInstance](#method-getInstance)




Properties
----------


### <a name="property-$registry"></a>$registry

    protected mixed $registry = array()





* Visibility: **protected**
* This property is defined in [config/smarty.config.inc.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/config/smarty.config.inc.php#L227)


### <a name="property-$instance"></a>$instance

    protected mixed $instance





* Visibility: **protected**
* This property is **static**.
* This property is defined in [config/smarty.config.inc.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/config/smarty.config.inc.php#L228)


Methods
-------


### <a name="method-register"></a>register

    mixed SmartyLazyRegister::register(string|array $params)

Register a function or method to be dynamically called later



* Visibility: **public**
* This method is defined in [config/smarty.config.inc.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/config/smarty.config.inc.php#L234)


#### Arguments
* $params **string|array** - &lt;p&gt;function name or array(object name, method name)&lt;/p&gt;



### <a name="method-__call"></a>__call

    mixed SmartyLazyRegister::__call(string $name, mixed $arguments)

Dynamically call static function or method



* Visibility: **public**
* This method is defined in [config/smarty.config.inc.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/config/smarty.config.inc.php#L250)


#### Arguments
* $name **string** - &lt;p&gt;function name&lt;/p&gt;
* $arguments **mixed** - &lt;p&gt;function argument&lt;/p&gt;



### <a name="method-getInstance"></a>getInstance

    mixed SmartyLazyRegister::getInstance()





* Visibility: **public**
* This method is **static**.
* This method is defined in [config/smarty.config.inc.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/config/smarty.config.inc.php#L272)



