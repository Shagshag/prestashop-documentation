AdminCartRulesControllerCore
===============






* Class name: AdminCartRulesControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminCartRulesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L30)





Properties
----------

* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [ajaxProcessLoadCartRules](#method-ajaxProcessLoadCartRules)
* [setMedia](#method-setMedia)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [postProcess](#method-postProcess)
* [afterUpdate](#method-afterUpdate)
* [processAdd](#method-processAdd)
* [afterAdd](#method-afterAdd)
* [getProductRuleGroupsDisplay](#method-getProductRuleGroupsDisplay)
* [getProductRuleGroupDisplay](#method-getProductRuleGroupDisplay)
* [getProductRuleDisplay](#method-getProductRuleDisplay)
* [ajaxProcess](#method-ajaxProcess)
* [searchProducts](#method-searchProducts)
* [ajaxProcessSearchProducts](#method-ajaxProcessSearchProducts)
* [renderForm](#method-renderForm)
* [displayAjaxSearchCartRuleVouchers](#method-displayAjaxSearchCartRuleVouchers)




Properties
----------


### <a name="property-$object"></a>$object

    public \CartRule $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminCartRulesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminCartRulesControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L32)




### <a name="method-ajaxProcessLoadCartRules"></a>ajaxProcessLoadCartRules

    mixed AdminCartRulesControllerCore::ajaxProcessLoadCartRules()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L57)




### <a name="method-setMedia"></a>setMedia

    mixed AdminCartRulesControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L125)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminCartRulesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L131)




### <a name="method-postProcess"></a>postProcess

    mixed AdminCartRulesControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L144)




### <a name="method-afterUpdate"></a>afterUpdate

    mixed AdminCartRulesControllerCore::afterUpdate($current_object)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L234)


#### Arguments
* $current_object **mixed**



### <a name="method-processAdd"></a>processAdd

    mixed AdminCartRulesControllerCore::processAdd()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L252)




### <a name="method-afterAdd"></a>afterAdd

    void AdminCartRulesControllerCore::afterAdd(\ObjectModel $currentObject)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L272)


#### Arguments
* $currentObject **[ObjectModel](ObjectModelCore)**



### <a name="method-getProductRuleGroupsDisplay"></a>getProductRuleGroupsDisplay

    array AdminCartRulesControllerCore::getProductRuleGroupsDisplay(\CartRule $cart_rule)

Retrieve the cart rule product rule groups in the POST data
if available, and in the database if there is none



* Visibility: **public**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L364)


#### Arguments
* $cart_rule **[CartRule](CartRuleCore)**



### <a name="method-getProductRuleGroupDisplay"></a>getProductRuleGroupDisplay

    mixed AdminCartRulesControllerCore::getProductRuleGroupDisplay($product_rule_group_id, $product_rule_group_quantity, $product_rules)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 403](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L403)


#### Arguments
* $product_rule_group_id **mixed**
* $product_rule_group_quantity **mixed**
* $product_rules **mixed**



### <a name="method-getProductRuleDisplay"></a>getProductRuleDisplay

    mixed AdminCartRulesControllerCore::getProductRuleDisplay($product_rule_group_id, $product_rule_id, $product_rule_type, $selected)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 412](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L412)


#### Arguments
* $product_rule_group_id **mixed**
* $product_rule_id **mixed**
* $product_rule_type **mixed**
* $selected **mixed**



### <a name="method-ajaxProcess"></a>ajaxProcess

    mixed AdminCartRulesControllerCore::ajaxProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 509](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L509)




### <a name="method-searchProducts"></a>searchProducts

    mixed AdminCartRulesControllerCore::searchProducts($search)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 541](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L541)


#### Arguments
* $search **mixed**



### <a name="method-ajaxProcessSearchProducts"></a>ajaxProcessSearchProducts

    mixed AdminCartRulesControllerCore::ajaxProcessSearchProducts()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L577)




### <a name="method-renderForm"></a>renderForm

    mixed AdminCartRulesControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 583](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L583)




### <a name="method-displayAjaxSearchCartRuleVouchers"></a>displayAjaxSearchCartRuleVouchers

    mixed AdminCartRulesControllerCore::displayAjaxSearchCartRuleVouchers()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCartRulesController.php line 708](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L708)



