TaxRulesGroupCore
===============






* Class name: TaxRulesGroupCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/tax/TaxRulesGroup.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L28)





Properties
----------


### $name

    public mixed $name





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesGroup.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#30)


### $active

    public boolean $active





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesGroup.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#33)


### $deleted

    public mixed $deleted





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesGroup.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#35)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesGroup.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#38)


### $date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesGroup.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#41)


### $definition

    public mixed $definition = array('table' => 'tax_rules_group', 'primary' => 'id_tax_rules_group', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/tax/TaxRulesGroup.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#46)


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'tax_rule_groups', 'objectNodeName' => 'tax_rule_group', 'fields' => array())





* Visibility: **protected**
* This property is defined in [classes/tax/TaxRulesGroup.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#58)


### $_taxes

    protected mixed $_taxes = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/tax/TaxRulesGroup.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#65)


Methods
-------


### update

    mixed TaxRulesGroupCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesGroup.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#68)


#### Arguments
* $null_values **mixed**



### historize

    mixed TaxRulesGroupCore::historize(\TaxRulesGroup $tax_rules_group)

Save the object with the field deleted to true

@return bool

* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesGroup.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#87)


#### Arguments
* $tax_rules_group **[TaxRulesGroup](TaxRulesGroupCore)**



### getIdTaxRuleGroupFromHistorizedId

    mixed TaxRulesGroupCore::getIdTaxRuleGroupFromHistorizedId($id_tax_rule)





* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesGroup.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#118)


#### Arguments
* $id_tax_rule **mixed**



### getTaxRulesGroups

    mixed TaxRulesGroupCore::getTaxRulesGroups($only_active)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRulesGroup.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#136)


#### Arguments
* $only_active **mixed**



### getTaxRulesGroupsForOptions

    array TaxRulesGroupCore::getTaxRulesGroupsForOptions()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRulesGroup.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#149)




### delete

    mixed TaxRulesGroupCore::delete()





* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesGroup.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#155)




### getAssociatedTaxRatesByIdCountry

    array TaxRulesGroupCore::getAssociatedTaxRatesByIdCountry($id_country)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRulesGroup.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#163)


#### Arguments
* $id_country **mixed**



### getIdByName

    integer TaxRulesGroupCore::getIdByName(string $name)

Returns the tax rules group id corresponding to the name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRulesGroup.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#189)


#### Arguments
* $name **string**



### hasUniqueTaxRuleForCountry

    mixed TaxRulesGroupCore::hasUniqueTaxRuleForCountry($id_country, $id_state, $id_tax_rule)





* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesGroup.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#198)


#### Arguments
* $id_country **mixed**
* $id_state **mixed**
* $id_tax_rule **mixed**



### isUsed

    mixed TaxRulesGroupCore::isUsed()





* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesGroup.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#210)




### getTaxesRate

    mixed TaxRulesGroupCore::getTaxesRate($id_tax_rules_group, $id_country, $id_state, $zipcode)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRulesGroup.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#222)


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
* This method is defined in [classes/tax/TaxRulesGroup.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#237)


#### Arguments
* $id_tax_rules_group **mixed**
* $id_country **mixed**
* $id_state **mixed**
* $id_county **mixed**


