ModuleFrontControllerCore
===============






* Class name: ModuleFrontControllerCore
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in [classes/controller/ModuleFrontController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/ModuleFrontController.php#L30)





Properties
----------

* [$module](#property-$module)

Methods
-------
* [__construct](#method-__construct)
* [setTemplate](#method-setTemplate)
* [getTemplatePath](#method-getTemplatePath)




Properties
----------


### <a name="property-$module"></a>$module

    public \Module $module





* Visibility: **public**
* This property is defined in [classes/controller/ModuleFrontController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/ModuleFrontController.php#L33)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed ModuleFrontControllerCore::__construct()





* Visibility: **public**
* This method is defined in [classes/controller/ModuleFrontController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/ModuleFrontController.php#L35)




### <a name="method-setTemplate"></a>setTemplate

    mixed ModuleFrontControllerCore::setTemplate(string $template)

Assigns module template for page content



* Visibility: **public**
* This method is defined in [classes/controller/ModuleFrontController.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/ModuleFrontController.php#L63)


#### Arguments
* $template **string** - &lt;p&gt;Template filename&lt;/p&gt;



### <a name="method-getTemplatePath"></a>getTemplatePath

    string|false ModuleFrontControllerCore::getTemplatePath(string $template)

Finds and returns module front template that take the highest precedence



* Visibility: **public**
* This method is defined in [classes/controller/ModuleFrontController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/controller/ModuleFrontController.php#L78)


#### Arguments
* $template **string** - &lt;p&gt;Template filename&lt;/p&gt;


