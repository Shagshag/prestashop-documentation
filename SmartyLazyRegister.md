SmartyLazyRegister
===============

Used to delay loading of external classes with smarty-&gt;register_plugin




* Class name: SmartyLazyRegister
* Namespace: 





Properties
----------


### $registry

    protected mixed $registry = array()





* Visibility: **protected**


### $instance

    protected mixed $instance





* Visibility: **protected**
* This property is **static**.


Methods
-------


### register

    mixed SmartyLazyRegister::register(string|array $params)

Register a function or method to be dynamically called later



* Visibility: **public**


#### Arguments
* $params **string|array** - &lt;p&gt;function name or array(object name, method name)&lt;/p&gt;



### __call

    mixed SmartyLazyRegister::__call(string $name, mixed $arguments)

Dynamically call static function or method



* Visibility: **public**


#### Arguments
* $name **string** - &lt;p&gt;function name&lt;/p&gt;
* $arguments **mixed** - &lt;p&gt;function argument&lt;/p&gt;



### getInstance

    mixed SmartyLazyRegister::getInstance()





* Visibility: **public**
* This method is **static**.



