Class AdminCartRulesControllerCore
=====================





* Class name: AdminCartRulesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCartRulesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L30)



Properties
----------

* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [afterAdd](#method-afterAdd)
* [afterUpdate](#method-afterUpdate)
* [ajaxProcess](#method-ajaxProcess)
* [ajaxProcessLoadCartRules](#method-ajaxProcessLoadCartRules)
* [ajaxProcessSearchProducts](#method-ajaxProcessSearchProducts)
* [displayAjaxSearchCartRuleVouchers](#method-displayAjaxSearchCartRuleVouchers)
* [getProductRuleDisplay](#method-getProductRuleDisplay)
* [getProductRuleGroupDisplay](#method-getProductRuleGroupDisplay)
* [getProductRuleGroupsDisplay](#method-getProductRuleGroupsDisplay)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [postProcess](#method-postProcess)
* [processAdd](#method-processAdd)
* [renderForm](#method-renderForm)
* [searchProducts](#method-searchProducts)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$object"></a>$object

    public \CartRule $object





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L30).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminCartRulesControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L32)




### <a name="method-afterAdd"></a>afterAdd

    void AdminCartRulesControllerCore::afterAdd(\ObjectModel $currentObject)





* Visibility: **protected**
* Source: [controllers/admin/AdminCartRulesController.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L272)


#### Arguments
* $currentObject **[ObjectModel](class.ObjectModelCore.md)**



### <a name="method-afterUpdate"></a>afterUpdate

    mixed AdminCartRulesControllerCore::afterUpdate($current_object)





* Visibility: **protected**
* Source: [controllers/admin/AdminCartRulesController.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L234)


#### Arguments
* $current_object **mixed**



### <a name="method-ajaxProcess"></a>ajaxProcess

    mixed AdminCartRulesControllerCore::ajaxProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 509](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L509)




### <a name="method-ajaxProcessLoadCartRules"></a>ajaxProcessLoadCartRules

    mixed AdminCartRulesControllerCore::ajaxProcessLoadCartRules()





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L57)




### <a name="method-ajaxProcessSearchProducts"></a>ajaxProcessSearchProducts

    mixed AdminCartRulesControllerCore::ajaxProcessSearchProducts()





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L577)




### <a name="method-displayAjaxSearchCartRuleVouchers"></a>displayAjaxSearchCartRuleVouchers

    mixed AdminCartRulesControllerCore::displayAjaxSearchCartRuleVouchers()





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 708](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L708)




### <a name="method-getProductRuleDisplay"></a>getProductRuleDisplay

    mixed AdminCartRulesControllerCore::getProductRuleDisplay($product_rule_group_id, $product_rule_id, $product_rule_type, $selected)





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 412](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L412)


#### Arguments
* $product_rule_group_id **mixed**
* $product_rule_id **mixed**
* $product_rule_type **mixed**
* $selected **mixed**



### <a name="method-getProductRuleGroupDisplay"></a>getProductRuleGroupDisplay

    mixed AdminCartRulesControllerCore::getProductRuleGroupDisplay($product_rule_group_id, $product_rule_group_quantity, $product_rules)





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 403](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L403)


#### Arguments
* $product_rule_group_id **mixed**
* $product_rule_group_quantity **mixed**
* $product_rules **mixed**



### <a name="method-getProductRuleGroupsDisplay"></a>getProductRuleGroupsDisplay

    array AdminCartRulesControllerCore::getProductRuleGroupsDisplay(\CartRule $cart_rule)

Retrieve the cart rule product rule groups in the POST data
if available, and in the database if there is none



* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L364)


#### Arguments
* $cart_rule **[CartRule](class.CartRuleCore.md)**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminCartRulesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L131)




### <a name="method-postProcess"></a>postProcess

    mixed AdminCartRulesControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L144)




### <a name="method-processAdd"></a>processAdd

    mixed AdminCartRulesControllerCore::processAdd()





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L252)




### <a name="method-renderForm"></a>renderForm

    mixed AdminCartRulesControllerCore::renderForm()





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 583](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L583)




### <a name="method-searchProducts"></a>searchProducts

    mixed AdminCartRulesControllerCore::searchProducts($search)





* Visibility: **protected**
* Source: [controllers/admin/AdminCartRulesController.php line 541](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L541)


#### Arguments
* $search **mixed**



### <a name="method-setMedia"></a>setMedia

    mixed AdminCartRulesControllerCore::setMedia()





* Visibility: **public**
* Source: [controllers/admin/AdminCartRulesController.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartRulesController.php#L125)



