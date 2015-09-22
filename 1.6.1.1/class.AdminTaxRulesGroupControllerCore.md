Class AdminTaxRulesGroupControllerCore
=====================





* Class name: AdminTaxRulesGroupControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L30)



Properties
----------

* [$errors_tax_rule](#property-$errors_tax_rule)
* [$object](#property-$object)
* [$selected_countries](#property-$selected_countries)
* [$selected_states](#property-$selected_states)
* [$tax_rule](#property-$tax_rule)

Methods
-------
* [__construct](#method-__construct)
* [deleteTaxRule](#method-deleteTaxRule)
* [displayAjaxUpdateTaxRule](#method-displayAjaxUpdateTaxRule)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [initRuleForm](#method-initRuleForm)
* [initRulesList](#method-initRulesList)
* [processBulkDeleteTaxRules](#method-processBulkDeleteTaxRules)
* [processCreateRule](#method-processCreateRule)
* [processDeleteTaxRule](#method-processDeleteTaxRule)
* [renderForm](#method-renderForm)
* [renderList](#method-renderList)
* [updateTaxRulesGroup](#method-updateTaxRulesGroup)
* [validateTaxRule](#method-validateTaxRule)




Properties
----------


### <a name="property-$errors_tax_rule"></a>$errors_tax_rule

    public mixed $errors_tax_rule





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L35)


### <a name="property-$object"></a>$object

    public \TaxRulesGroup $object





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L30)


### <a name="property-$selected_countries"></a>$selected_countries

    public mixed $selected_countries = array()





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L33)


### <a name="property-$selected_states"></a>$selected_states

    public mixed $selected_states = array()





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L34)


### <a name="property-$tax_rule"></a>$tax_rule

    public mixed $tax_rule





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L32)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminTaxRulesGroupControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L37)




### <a name="method-deleteTaxRule"></a>deleteTaxRule

    mixed AdminTaxRulesGroupControllerCore::deleteTaxRule(array $id_tax_rule_list)





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L506)


#### Arguments
* $id_tax_rule_list **array**



### <a name="method-displayAjaxUpdateTaxRule"></a>displayAjaxUpdateTaxRule

    mixed AdminTaxRulesGroupControllerCore::displayAjaxUpdateTaxRule()





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 540](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L540)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminTaxRulesGroupControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L78)




### <a name="method-initProcess"></a>initProcess

    mixed AdminTaxRulesGroupControllerCore::initProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 379](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L379)




### <a name="method-initRuleForm"></a>initRuleForm

    mixed AdminTaxRulesGroupControllerCore::initRuleForm()





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L236)




### <a name="method-initRulesList"></a>initRulesList

    mixed AdminTaxRulesGroupControllerCore::initRulesList($id_group)





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L99)


#### Arguments
* $id_group **mixed**



### <a name="method-processBulkDeleteTaxRules"></a>processBulkDeleteTaxRules

    mixed AdminTaxRulesGroupControllerCore::processBulkDeleteTaxRules()





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 496](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L496)




### <a name="method-processCreateRule"></a>processCreateRule

    mixed AdminTaxRulesGroupControllerCore::processCreateRule()





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L404)




### <a name="method-processDeleteTaxRule"></a>processDeleteTaxRule

    mixed AdminTaxRulesGroupControllerCore::processDeleteTaxRule()





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 501](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L501)




### <a name="method-renderForm"></a>renderForm

    mixed AdminTaxRulesGroupControllerCore::renderForm()





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L164)




### <a name="method-renderList"></a>renderList

    mixed AdminTaxRulesGroupControllerCore::renderList()





* Visibility: **public**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L91)




### <a name="method-updateTaxRulesGroup"></a>updateTaxRulesGroup

    \TaxRulesGroup AdminTaxRulesGroupControllerCore::updateTaxRulesGroup(\TaxRulesGroup $object)





* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L558)


#### Arguments
* $object **[TaxRulesGroup](class.TaxRulesGroupCore.md)**



### <a name="method-validateTaxRule"></a>validateTaxRule

    array AdminTaxRulesGroupControllerCore::validateTaxRule(\TaxRule $tr)

Check if the tax rule could be added in the database



* Visibility: **protected**
* Source: [controllers/admin/AdminTaxRulesGroupController.php line 534](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#L534)


#### Arguments
* $tr **[TaxRule](class.TaxRuleCore.md)**


