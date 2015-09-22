TaxRulesGroupCore
===============






* Class name: TaxRulesGroupCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/tax/TaxRulesGroup.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L28)





Properties
----------

* [$name](#property-$name)
* [$active](#property-$active)
* [$deleted](#property-$deleted)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)
* [$_taxes](#property-$_taxes)

Methods
-------
* [update](#method-update)
* [historize](#method-historize)
* [getIdTaxRuleGroupFromHistorizedId](#method-getIdTaxRuleGroupFromHistorizedId)
* [getTaxRulesGroups](#method-getTaxRulesGroups)
* [getTaxRulesGroupsForOptions](#method-getTaxRulesGroupsForOptions)
* [delete](#method-delete)
* [getAssociatedTaxRatesByIdCountry](#method-getAssociatedTaxRatesByIdCountry)
* [getIdByName](#method-getIdByName)
* [hasUniqueTaxRuleForCountry](#method-hasUniqueTaxRuleForCountry)
* [isUsed](#method-isUsed)
* [getTaxesRate](#method-getTaxesRate)
* [getTaxes](#method-getTaxes)




Properties
----------


### <a name="property-$name"></a>$name

    public mixed $name





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesGroup.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L30)


### <a name="property-$active"></a>$active

    public boolean $active





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesGroup.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L33)


### <a name="property-$deleted"></a>$deleted

    public mixed $deleted





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesGroup.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L35)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesGroup.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L38)


### <a name="property-$date_upd"></a>$date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesGroup.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L41)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'tax_rules_group', 'primary' => 'id_tax_rules_group', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/tax/TaxRulesGroup.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L46)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'tax_rule_groups', 'objectNodeName' => 'tax_rule_group', 'fields' => array())





* Visibility: **protected**
* This property is defined in [classes/tax/TaxRulesGroup.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L58)


### <a name="property-$_taxes"></a>$_taxes

    protected mixed $_taxes = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/tax/TaxRulesGroup.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L65)


Methods
-------


### <a name="method-update"></a>update

    mixed TaxRulesGroupCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesGroup.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L68)


#### Arguments
* $null_values **mixed**



### <a name="method-historize"></a>historize

    mixed TaxRulesGroupCore::historize(\TaxRulesGroup $tax_rules_group)

Save the object with the field deleted to true

@return bool

* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesGroup.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L87)


#### Arguments
* $tax_rules_group **[TaxRulesGroup](TaxRulesGroupCore)**



### <a name="method-getIdTaxRuleGroupFromHistorizedId"></a>getIdTaxRuleGroupFromHistorizedId

    mixed TaxRulesGroupCore::getIdTaxRuleGroupFromHistorizedId($id_tax_rule)





* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesGroup.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L118)


#### Arguments
* $id_tax_rule **mixed**



### <a name="method-getTaxRulesGroups"></a>getTaxRulesGroups

    mixed TaxRulesGroupCore::getTaxRulesGroups($only_active)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRulesGroup.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L136)


#### Arguments
* $only_active **mixed**



### <a name="method-getTaxRulesGroupsForOptions"></a>getTaxRulesGroupsForOptions

    array TaxRulesGroupCore::getTaxRulesGroupsForOptions()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRulesGroup.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L149)




### <a name="method-delete"></a>delete

    mixed TaxRulesGroupCore::delete()





* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesGroup.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L155)




### <a name="method-getAssociatedTaxRatesByIdCountry"></a>getAssociatedTaxRatesByIdCountry

    array TaxRulesGroupCore::getAssociatedTaxRatesByIdCountry($id_country)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRulesGroup.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L163)


#### Arguments
* $id_country **mixed**



### <a name="method-getIdByName"></a>getIdByName

    integer TaxRulesGroupCore::getIdByName(string $name)

Returns the tax rules group id corresponding to the name



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRulesGroup.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L189)


#### Arguments
* $name **string**



### <a name="method-hasUniqueTaxRuleForCountry"></a>hasUniqueTaxRuleForCountry

    mixed TaxRulesGroupCore::hasUniqueTaxRuleForCountry($id_country, $id_state, $id_tax_rule)





* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesGroup.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L198)


#### Arguments
* $id_country **mixed**
* $id_state **mixed**
* $id_tax_rule **mixed**



### <a name="method-isUsed"></a>isUsed

    mixed TaxRulesGroupCore::isUsed()





* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesGroup.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L210)




### <a name="method-getTaxesRate"></a>getTaxesRate

    mixed TaxRulesGroupCore::getTaxesRate($id_tax_rules_group, $id_country, $id_state, $zipcode)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRulesGroup.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L222)


#### Arguments
* $id_tax_rules_group **mixed**
* $id_country **mixed**
* $id_state **mixed**
* $zipcode **mixed**



### <a name="method-getTaxes"></a>getTaxes

    mixed TaxRulesGroupCore::getTaxes($id_tax_rules_group, $id_country, $id_state, $id_county)

Return taxes associated to this para



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRulesGroup.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L237)


#### Arguments
* $id_tax_rules_group **mixed**
* $id_country **mixed**
* $id_state **mixed**
* $id_county **mixed**


