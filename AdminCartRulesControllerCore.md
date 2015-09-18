AdminCartRulesControllerCore
===============






* Class name: AdminCartRulesControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $object

    public \CartRule $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminCartRulesControllerCore::__construct()





* Visibility: **public**




### ajaxProcessLoadCartRules

    mixed AdminCartRulesControllerCore::ajaxProcessLoadCartRules()





* Visibility: **public**




### setMedia

    mixed AdminCartRulesControllerCore::setMedia()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminCartRulesControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### postProcess

    mixed AdminCartRulesControllerCore::postProcess()





* Visibility: **public**




### afterUpdate

    mixed AdminCartRulesControllerCore::afterUpdate($current_object)





* Visibility: **protected**


#### Arguments
* $current_object **mixed**



### processAdd

    mixed AdminCartRulesControllerCore::processAdd()





* Visibility: **public**




### afterAdd

    void AdminCartRulesControllerCore::afterAdd(\ObjectModel $currentObject)





* Visibility: **protected**


#### Arguments
* $currentObject **ObjectModel**



### getProductRuleGroupsDisplay

    array AdminCartRulesControllerCore::getProductRuleGroupsDisplay(\CartRule $cart_rule)

Retrieve the cart rule product rule groups in the POST data
if available, and in the database if there is none



* Visibility: **public**


#### Arguments
* $cart_rule **CartRule**



### getProductRuleGroupDisplay

    mixed AdminCartRulesControllerCore::getProductRuleGroupDisplay($product_rule_group_id, $product_rule_group_quantity, $product_rules)





* Visibility: **public**


#### Arguments
* $product_rule_group_id **mixed**
* $product_rule_group_quantity **mixed**
* $product_rules **mixed**



### getProductRuleDisplay

    mixed AdminCartRulesControllerCore::getProductRuleDisplay($product_rule_group_id, $product_rule_id, $product_rule_type, $selected)





* Visibility: **public**


#### Arguments
* $product_rule_group_id **mixed**
* $product_rule_id **mixed**
* $product_rule_type **mixed**
* $selected **mixed**



### ajaxProcess

    mixed AdminCartRulesControllerCore::ajaxProcess()





* Visibility: **public**




### searchProducts

    mixed AdminCartRulesControllerCore::searchProducts($search)





* Visibility: **protected**


#### Arguments
* $search **mixed**



### ajaxProcessSearchProducts

    mixed AdminCartRulesControllerCore::ajaxProcessSearchProducts()





* Visibility: **public**




### renderForm

    mixed AdminCartRulesControllerCore::renderForm()





* Visibility: **public**




### displayAjaxSearchCartRuleVouchers

    mixed AdminCartRulesControllerCore::displayAjaxSearchCartRuleVouchers()





* Visibility: **public**



