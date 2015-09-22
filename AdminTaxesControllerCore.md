AdminTaxesControllerCore
===============






* Class name: AdminTaxesControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminTaxesController.php line 30





Properties
----------


### $object

    public \Tax $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminTaxesController.php line 30


Methods
-------


### __construct

    mixed AdminTaxesControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxesController.php line 32




### initPageHeaderToolbar

    mixed AdminTaxesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxesController.php line 117




### displayDeleteLink

    string AdminTaxesControllerCore::displayDeleteLink(string|null $token, integer $id)

Display delete action link



* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxesController.php line 140


#### Arguments
* $token **string|null**
* $id **integer**



### displayEnableLink

    mixed AdminTaxesControllerCore::displayEnableLink(string $token, integer $id, integer $value, string $active, integer $id_category, integer $id_product)

Fetch the template for action enable



* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxesController.php line 173


#### Arguments
* $token **string**
* $id **integer**
* $value **integer** - &lt;p&gt;state enabled or not&lt;/p&gt;
* $active **string** - &lt;p&gt;status&lt;/p&gt;
* $id_category **integer**
* $id_product **integer**



### renderForm

    mixed AdminTaxesControllerCore::renderForm()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxesController.php line 189




### postProcess

    mixed AdminTaxesControllerCore::postProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxesController.php line 241




### updateOptionPsUseEcotax

    mixed AdminTaxesControllerCore::updateOptionPsUseEcotax($value)





* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxesController.php line 284


#### Arguments
* $value **mixed**


