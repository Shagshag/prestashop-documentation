AdminTaxRulesGroupControllerCore
===============






* Class name: AdminTaxRulesGroupControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)

* This class is defined in [controllers/admin/AdminTaxRulesGroupController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#30)





Properties
----------


### $tax_rule

    public mixed $tax_rule





* Visibility: **public**
* This property is defined in [controllers/admin/AdminTaxRulesGroupController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#32)


### $selected_countries

    public mixed $selected_countries = array()





* Visibility: **public**
* This property is defined in [controllers/admin/AdminTaxRulesGroupController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#33)


### $selected_states

    public mixed $selected_states = array()





* Visibility: **public**
* This property is defined in [controllers/admin/AdminTaxRulesGroupController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#34)


### $errors_tax_rule

    public mixed $errors_tax_rule





* Visibility: **public**
* This property is defined in [controllers/admin/AdminTaxRulesGroupController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#35)


### $object

    public \TaxRulesGroup $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminTaxRulesGroupController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#30)


Methods
-------


### __construct

    mixed AdminTaxRulesGroupControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#37)




### initPageHeaderToolbar

    mixed AdminTaxRulesGroupControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#78)




### renderList

    mixed AdminTaxRulesGroupControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#91)




### initRulesList

    mixed AdminTaxRulesGroupControllerCore::initRulesList($id_group)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#99)


#### Arguments
* $id_group **mixed**



### renderForm

    mixed AdminTaxRulesGroupControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#164)




### initRuleForm

    mixed AdminTaxRulesGroupControllerCore::initRuleForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#236)




### initProcess

    mixed AdminTaxRulesGroupControllerCore::initProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 379](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#379)




### processCreateRule

    mixed AdminTaxRulesGroupControllerCore::processCreateRule()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 404](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#404)




### processBulkDeleteTaxRules

    mixed AdminTaxRulesGroupControllerCore::processBulkDeleteTaxRules()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 496](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#496)




### processDeleteTaxRule

    mixed AdminTaxRulesGroupControllerCore::processDeleteTaxRule()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 501](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#501)




### deleteTaxRule

    mixed AdminTaxRulesGroupControllerCore::deleteTaxRule(array $id_tax_rule_list)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#506)


#### Arguments
* $id_tax_rule_list **array**



### validateTaxRule

    array AdminTaxRulesGroupControllerCore::validateTaxRule(\TaxRule $tr)

Check if the tax rule could be added in the database



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 534](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#534)


#### Arguments
* $tr **[TaxRule](TaxRuleCore)**



### displayAjaxUpdateTaxRule

    mixed AdminTaxRulesGroupControllerCore::displayAjaxUpdateTaxRule()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 540](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#540)




### updateTaxRulesGroup

    \TaxRulesGroup AdminTaxRulesGroupControllerCore::updateTaxRulesGroup(\TaxRulesGroup $object)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminTaxRulesGroupController.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminTaxRulesGroupController.php#558)


#### Arguments
* $object **[TaxRulesGroup](TaxRulesGroupCore)**


