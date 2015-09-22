ModuleFrontControllerCore
===============






* Class name: ModuleFrontControllerCore
* Namespace: 
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in classes\controller\ModuleFrontController.php line 30





Properties
----------


### $module

    public \Module $module





* Visibility: **public**
* This property is defined in classes\controller\ModuleFrontController.php line 33


Methods
-------


### __construct

    mixed ModuleFrontControllerCore::__construct()





* Visibility: **public**
* This method is defined in classes\controller\ModuleFrontController.php line 35




### setTemplate

    mixed ModuleFrontControllerCore::setTemplate(string $template)

Assigns module template for page content



* Visibility: **public**
* This method is defined in classes\controller\ModuleFrontController.php line 63


#### Arguments
* $template **string** - &lt;p&gt;Template filename&lt;/p&gt;



### getTemplatePath

    string|false ModuleFrontControllerCore::getTemplatePath(string $template)

Finds and returns module front template that take the highest precedence



* Visibility: **public**
* This method is defined in classes\controller\ModuleFrontController.php line 78


#### Arguments
* $template **string** - &lt;p&gt;Template filename&lt;/p&gt;


