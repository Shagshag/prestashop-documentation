AdminTaxRulesGroupControllerCore
===============






* Class name: AdminTaxRulesGroupControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminTaxRulesGroupController.php line 30





Properties
----------


### $tax_rule

    public mixed $tax_rule





* Visibility: **public**
* This property is defined in controllers\admin\AdminTaxRulesGroupController.php line 32


### $selected_countries

    public mixed $selected_countries = array()





* Visibility: **public**
* This property is defined in controllers\admin\AdminTaxRulesGroupController.php line 33


### $selected_states

    public mixed $selected_states = array()





* Visibility: **public**
* This property is defined in controllers\admin\AdminTaxRulesGroupController.php line 34


### $errors_tax_rule

    public mixed $errors_tax_rule





* Visibility: **public**
* This property is defined in controllers\admin\AdminTaxRulesGroupController.php line 35


### $object

    public \TaxRulesGroup $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminTaxRulesGroupController.php line 30


Methods
-------


### __construct

    mixed AdminTaxRulesGroupControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 37




### initPageHeaderToolbar

    mixed AdminTaxRulesGroupControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 78




### renderList

    mixed AdminTaxRulesGroupControllerCore::renderList()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 91




### initRulesList

    mixed AdminTaxRulesGroupControllerCore::initRulesList($id_group)





* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 99


#### Arguments
* $id_group **mixed**



### renderForm

    mixed AdminTaxRulesGroupControllerCore::renderForm()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 164




### initRuleForm

    mixed AdminTaxRulesGroupControllerCore::initRuleForm()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 236




### initProcess

    mixed AdminTaxRulesGroupControllerCore::initProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 379




### processCreateRule

    mixed AdminTaxRulesGroupControllerCore::processCreateRule()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 404




### processBulkDeleteTaxRules

    mixed AdminTaxRulesGroupControllerCore::processBulkDeleteTaxRules()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 496




### processDeleteTaxRule

    mixed AdminTaxRulesGroupControllerCore::processDeleteTaxRule()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 501




### deleteTaxRule

    mixed AdminTaxRulesGroupControllerCore::deleteTaxRule(array $id_tax_rule_list)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 506


#### Arguments
* $id_tax_rule_list **array**



### validateTaxRule

    array AdminTaxRulesGroupControllerCore::validateTaxRule(\TaxRule $tr)

Check if the tax rule could be added in the database



* Visibility: **protected**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 534


#### Arguments
* $tr **[TaxRule](TaxRuleCore)**



### displayAjaxUpdateTaxRule

    mixed AdminTaxRulesGroupControllerCore::displayAjaxUpdateTaxRule()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 540




### updateTaxRulesGroup

    \TaxRulesGroup AdminTaxRulesGroupControllerCore::updateTaxRulesGroup(\TaxRulesGroup $object)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminTaxRulesGroupController.php line 558


#### Arguments
* $object **[TaxRulesGroup](TaxRulesGroupCore)**


