TaxRulesGroupCore
===============






* Class name: TaxRulesGroupCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $name

    public mixed $name





* Visibility: **public**


### $active

    public boolean $active





* Visibility: **public**


### $deleted

    public mixed $deleted





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'tax_rules_group', 'primary' => 'id_tax_rules_group', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'tax_rule_groups', 'objectNodeName' => 'tax_rule_group', 'fields' => array())





* Visibility: **protected**


### $_taxes

    protected mixed $_taxes = array()





* Visibility: **protected**
* This property is **static**.


Methods
-------


### update

    mixed TaxRulesGroupCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### historize

    mixed TaxRulesGroupCore::historize(\TaxRulesGroup $tax_rules_group)

Save the object with the field deleted to true

@return bool

* Visibility: **public**


#### Arguments
* $tax_rules_group **TaxRulesGroup**



### getIdTaxRuleGroupFromHistorizedId

    mixed TaxRulesGroupCore::getIdTaxRuleGroupFromHistorizedId($id_tax_rule)





* Visibility: **public**


#### Arguments
* $id_tax_rule **mixed**



### getTaxRulesGroups

    mixed TaxRulesGroupCore::getTaxRulesGroups($only_active)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $only_active **mixed**



### getTaxRulesGroupsForOptions

    array TaxRulesGroupCore::getTaxRulesGroupsForOptions()





* Visibility: **public**
* This method is **static**.




### delete

    mixed TaxRulesGroupCore::delete()





* Visibility: **public**




### getAssociatedTaxRatesByIdCountry

    array TaxRulesGroupCore::getAssociatedTaxRatesByIdCountry($id_country)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_country **mixed**



### getIdByName

    integer TaxRulesGroupCore::getIdByName(string $name)

Returns the tax rules group id corresponding to the name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string**



### hasUniqueTaxRuleForCountry

    mixed TaxRulesGroupCore::hasUniqueTaxRuleForCountry($id_country, $id_state, $id_tax_rule)





* Visibility: **public**


#### Arguments
* $id_country **mixed**
* $id_state **mixed**
* $id_tax_rule **mixed**



### isUsed

    mixed TaxRulesGroupCore::isUsed()





* Visibility: **public**




### getTaxesRate

    mixed TaxRulesGroupCore::getTaxesRate($id_tax_rules_group, $id_country, $id_state, $zipcode)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_tax_rules_group **mixed**
* $id_country **mixed**
* $id_state **mixed**
* $zipcode **mixed**



### getTaxes

    mixed TaxRulesGroupCore::getTaxes($id_tax_rules_group, $id_country, $id_state, $id_county)

Return taxes associated to this para



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_tax_rules_group **mixed**
* $id_country **mixed**
* $id_state **mixed**
* $id_county **mixed**


