Class TaxRulesGroupCore
=====================





* Class name: TaxRulesGroupCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/tax/TaxRulesGroup.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L28)


Contents
--------


### Properties

* [$_taxes](#property-$_taxes)
* [$active](#property-$active)
* [$definition](#property-$definition)
* [$name](#property-$name)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [delete](#method-delete)
* [getAssociatedTaxRatesByIdCountry](#method-getAssociatedTaxRatesByIdCountry)
* [getIdByName](#method-getIdByName)
* [getTaxRulesGroups](#method-getTaxRulesGroups)
* [getTaxRulesGroupsForOptions](#method-getTaxRulesGroupsForOptions)
* [getTaxes](#method-getTaxes)
* [getTaxesRate](#method-getTaxesRate)
* [hasUniqueTaxRuleForCountry](#method-hasUniqueTaxRuleForCountry)




Properties
----------


### <a name="property-$_taxes"></a>$_taxes

```php
protected mixed $_taxes = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L54).


### <a name="property-$active"></a>$active

```php
public boolean $active
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L33).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'tax_rules_group', 'primary' => 'id_tax_rules_group', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L38).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L30).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'tax_rule_groups', 'objectNodeName' => 'tax_rule_group', 'fields' => array())
```





* Visibility: **protected**
* Source: [classes/tax/TaxRulesGroup.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L47).


Methods
-------


### <a name="method-delete"></a>delete

```php
mixed TaxRulesGroupCore::delete()
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L76)




### <a name="method-getAssociatedTaxRatesByIdCountry"></a>getAssociatedTaxRatesByIdCountry

```php
array TaxRulesGroupCore::getAssociatedTaxRatesByIdCountry($id_country)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L84)


#### Arguments
* $id_country **mixed**



### <a name="method-getIdByName"></a>getIdByName

```php
integer TaxRulesGroupCore::getIdByName($name)
```

Returns the tax rules group id corresponding to the name



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L109)


#### Arguments
* $name **mixed**



### <a name="method-getTaxRulesGroups"></a>getTaxRulesGroups

```php
mixed TaxRulesGroupCore::getTaxRulesGroups($only_active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L56)


#### Arguments
* $only_active **mixed**



### <a name="method-getTaxRulesGroupsForOptions"></a>getTaxRulesGroupsForOptions

```php
array TaxRulesGroupCore::getTaxRulesGroupsForOptions()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L70)




### <a name="method-getTaxes"></a>getTaxes

```php
mixed TaxRulesGroupCore::getTaxes($id_tax_rules_group, $id_country, $id_state, $id_county)
```

Return taxes associated to this para



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L145)


#### Arguments
* $id_tax_rules_group **mixed**
* $id_country **mixed**
* $id_state **mixed**
* $id_county **mixed**



### <a name="method-getTaxesRate"></a>getTaxesRate

```php
mixed TaxRulesGroupCore::getTaxesRate($id_tax_rules_group, $id_country, $id_state, $zipcode)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L131)


#### Arguments
* $id_tax_rules_group **mixed**
* $id_country **mixed**
* $id_state **mixed**
* $zipcode **mixed**



### <a name="method-hasUniqueTaxRuleForCountry"></a>hasUniqueTaxRuleForCountry

```php
mixed TaxRulesGroupCore::hasUniqueTaxRuleForCountry($id_country, $id_state, $id_tax_rule)
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/tax/TaxRulesGroup.php#L118)


#### Arguments
* $id_country **mixed**
* $id_state **mixed**
* $id_tax_rule **mixed**


