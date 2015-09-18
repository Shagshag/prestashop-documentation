AdminTaxRulesGroupControllerCore
===============






* Class name: AdminTaxRulesGroupControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $tax_rule

    public mixed $tax_rule





* Visibility: **public**


### $selected_countries

    public mixed $selected_countries = array()





* Visibility: **public**


### $selected_states

    public mixed $selected_states = array()





* Visibility: **public**


### $errors_tax_rule

    public mixed $errors_tax_rule





* Visibility: **public**


### $object

    public \TaxRulesGroup $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminTaxRulesGroupControllerCore::__construct()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminTaxRulesGroupControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### renderList

    mixed AdminTaxRulesGroupControllerCore::renderList()





* Visibility: **public**




### initRulesList

    mixed AdminTaxRulesGroupControllerCore::initRulesList($id_group)





* Visibility: **public**


#### Arguments
* $id_group **mixed**



### renderForm

    mixed AdminTaxRulesGroupControllerCore::renderForm()





* Visibility: **public**




### initRuleForm

    mixed AdminTaxRulesGroupControllerCore::initRuleForm()





* Visibility: **public**




### initProcess

    mixed AdminTaxRulesGroupControllerCore::initProcess()





* Visibility: **public**




### processCreateRule

    mixed AdminTaxRulesGroupControllerCore::processCreateRule()





* Visibility: **protected**




### processBulkDeleteTaxRules

    mixed AdminTaxRulesGroupControllerCore::processBulkDeleteTaxRules()





* Visibility: **protected**




### processDeleteTaxRule

    mixed AdminTaxRulesGroupControllerCore::processDeleteTaxRule()





* Visibility: **protected**




### deleteTaxRule

    mixed AdminTaxRulesGroupControllerCore::deleteTaxRule(array $id_tax_rule_list)





* Visibility: **protected**


#### Arguments
* $id_tax_rule_list **array**



### validateTaxRule

    array AdminTaxRulesGroupControllerCore::validateTaxRule(\TaxRule $tr)

Check if the tax rule could be added in the database



* Visibility: **protected**


#### Arguments
* $tr **TaxRule**



### displayAjaxUpdateTaxRule

    mixed AdminTaxRulesGroupControllerCore::displayAjaxUpdateTaxRule()





* Visibility: **protected**




### updateTaxRulesGroup

    \TaxRulesGroup AdminTaxRulesGroupControllerCore::updateTaxRulesGroup(\TaxRulesGroup $object)





* Visibility: **protected**


#### Arguments
* $object **TaxRulesGroup**


