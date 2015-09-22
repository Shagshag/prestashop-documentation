AdminCartRulesControllerCore
===============






* Class name: AdminCartRulesControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminCartRulesController.php line 30





Properties
----------


### $object

    public \CartRule $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminCartRulesController.php line 30


Methods
-------


### __construct

    mixed AdminCartRulesControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCartRulesController.php line 32




### ajaxProcessLoadCartRules

    mixed AdminCartRulesControllerCore::ajaxProcessLoadCartRules()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCartRulesController.php line 57




### setMedia

    mixed AdminCartRulesControllerCore::setMedia()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCartRulesController.php line 125




### initPageHeaderToolbar

    mixed AdminCartRulesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCartRulesController.php line 131




### postProcess

    mixed AdminCartRulesControllerCore::postProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCartRulesController.php line 144




### afterUpdate

    mixed AdminCartRulesControllerCore::afterUpdate($current_object)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminCartRulesController.php line 234


#### Arguments
* $current_object **mixed**



### processAdd

    mixed AdminCartRulesControllerCore::processAdd()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCartRulesController.php line 252




### afterAdd

    void AdminCartRulesControllerCore::afterAdd(\ObjectModel $currentObject)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminCartRulesController.php line 272


#### Arguments
* $currentObject **[ObjectModel](ObjectModelCore)**



### getProductRuleGroupsDisplay

    array AdminCartRulesControllerCore::getProductRuleGroupsDisplay(\CartRule $cart_rule)

Retrieve the cart rule product rule groups in the POST data
if available, and in the database if there is none



* Visibility: **public**
* This method is defined in controllers\admin\AdminCartRulesController.php line 364


#### Arguments
* $cart_rule **[CartRule](CartRuleCore)**



### getProductRuleGroupDisplay

    mixed AdminCartRulesControllerCore::getProductRuleGroupDisplay($product_rule_group_id, $product_rule_group_quantity, $product_rules)





* Visibility: **public**
* This method is defined in controllers\admin\AdminCartRulesController.php line 403


#### Arguments
* $product_rule_group_id **mixed**
* $product_rule_group_quantity **mixed**
* $product_rules **mixed**



### getProductRuleDisplay

    mixed AdminCartRulesControllerCore::getProductRuleDisplay($product_rule_group_id, $product_rule_id, $product_rule_type, $selected)





* Visibility: **public**
* This method is defined in controllers\admin\AdminCartRulesController.php line 412


#### Arguments
* $product_rule_group_id **mixed**
* $product_rule_id **mixed**
* $product_rule_type **mixed**
* $selected **mixed**



### ajaxProcess

    mixed AdminCartRulesControllerCore::ajaxProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCartRulesController.php line 509




### searchProducts

    mixed AdminCartRulesControllerCore::searchProducts($search)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminCartRulesController.php line 541


#### Arguments
* $search **mixed**



### ajaxProcessSearchProducts

    mixed AdminCartRulesControllerCore::ajaxProcessSearchProducts()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCartRulesController.php line 577




### renderForm

    mixed AdminCartRulesControllerCore::renderForm()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCartRulesController.php line 583




### displayAjaxSearchCartRuleVouchers

    mixed AdminCartRulesControllerCore::displayAjaxSearchCartRuleVouchers()





* Visibility: **public**
* This method is defined in controllers\admin\AdminCartRulesController.php line 708



