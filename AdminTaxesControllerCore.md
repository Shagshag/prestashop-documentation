AdminTaxesControllerCore
===============






* Class name: AdminTaxesControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $object

    public \Tax $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminTaxesControllerCore::__construct()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminTaxesControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### displayDeleteLink

    string AdminTaxesControllerCore::displayDeleteLink(string|null $token, integer $id)

Display delete action link



* Visibility: **public**


#### Arguments
* $token **string|null**
* $id **integer**



### displayEnableLink

    mixed AdminTaxesControllerCore::displayEnableLink(string $token, integer $id, integer $value, string $active, integer $id_category, integer $id_product)

Fetch the template for action enable



* Visibility: **public**


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




### postProcess

    mixed AdminTaxesControllerCore::postProcess()





* Visibility: **public**




### updateOptionPsUseEcotax

    mixed AdminTaxesControllerCore::updateOptionPsUseEcotax($value)





* Visibility: **public**


#### Arguments
* $value **mixed**


