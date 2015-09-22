SmartyLazyRegister
===============

Used to delay loading of external classes with smarty-&gt;register_plugin




* Class name: SmartyLazyRegister
* Namespace: 
* This class is defined in config\smarty.config.inc.php line 225





Properties
----------


### $registry

    protected mixed $registry = array()





* Visibility: **protected**
* This property is defined in config\smarty.config.inc.php line 227


### $instance

    protected mixed $instance





* Visibility: **protected**
* This property is **static**.
* This property is defined in config\smarty.config.inc.php line 228


Methods
-------


### register

    mixed SmartyLazyRegister::register(string|array $params)

Register a function or method to be dynamically called later



* Visibility: **public**
* This method is defined in config\smarty.config.inc.php line 234


#### Arguments
* $params **string|array** - &lt;p&gt;function name or array(object name, method name)&lt;/p&gt;



### __call

    mixed SmartyLazyRegister::__call(string $name, mixed $arguments)

Dynamically call static function or method



* Visibility: **public**
* This method is defined in config\smarty.config.inc.php line 250


#### Arguments
* $name **string** - &lt;p&gt;function name&lt;/p&gt;
* $arguments **mixed** - &lt;p&gt;function argument&lt;/p&gt;



### getInstance

    mixed SmartyLazyRegister::getInstance()





* Visibility: **public**
* This method is **static**.
* This method is defined in config\smarty.config.inc.php line 272



