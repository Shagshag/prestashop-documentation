Class TaxRulesGroupCore
=====================





* Class name: TaxRulesGroupCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/tax/TaxRulesGroup.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L28)


Contents
--------


### Properties

* [$_taxes](#property-$_taxes)
* [$active](#property-$active)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$name](#property-$name)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [delete](#method-delete)
* [getAssociatedTaxRatesByIdCountry](#method-getAssociatedTaxRatesByIdCountry)
* [getIdByName](#method-getIdByName)
* [getIdTaxRuleGroupFromHistorizedId](#method-getIdTaxRuleGroupFromHistorizedId)
* [getTaxRulesGroups](#method-getTaxRulesGroups)
* [getTaxRulesGroupsForOptions](#method-getTaxRulesGroupsForOptions)
* [getTaxes](#method-getTaxes)
* [getTaxesRate](#method-getTaxesRate)
* [hasUniqueTaxRuleForCountry](#method-hasUniqueTaxRuleForCountry)
* [historize](#method-historize)
* [isUsed](#method-isUsed)
* [update](#method-update)




Properties
----------


### <a name="property-$_taxes"></a>$_taxes

```php
protected mixed $_taxes = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L65).


### <a name="property-$active"></a>$active

```php
public boolean $active
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L33).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L38).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L41).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'tax_rules_group', 'primary' => 'id_tax_rules_group', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L46).


### <a name="property-$deleted"></a>$deleted

```php
public mixed $deleted
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L35).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L30).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'tax_rule_groups', 'objectNodeName' => 'tax_rule_group', 'fields' => array())
```





* Visibility: **protected**
* Source: [classes/tax/TaxRulesGroup.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L58).


Methods
-------


### <a name="method-delete"></a>delete

```php
mixed TaxRulesGroupCore::delete()
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L155)




### <a name="method-getAssociatedTaxRatesByIdCountry"></a>getAssociatedTaxRatesByIdCountry

```php
array TaxRulesGroupCore::getAssociatedTaxRatesByIdCountry($id_country)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L163)


#### Arguments
* $id_country **mixed**



### <a name="method-getIdByName"></a>getIdByName

```php
integer TaxRulesGroupCore::getIdByName(string $name)
```

Returns the tax rules group id corresponding to the name



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L189)


#### Arguments
* $name **string**



### <a name="method-getIdTaxRuleGroupFromHistorizedId"></a>getIdTaxRuleGroupFromHistorizedId

```php
mixed TaxRulesGroupCore::getIdTaxRuleGroupFromHistorizedId($id_tax_rule)
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L118)


#### Arguments
* $id_tax_rule **mixed**



### <a name="method-getTaxRulesGroups"></a>getTaxRulesGroups

```php
mixed TaxRulesGroupCore::getTaxRulesGroups($only_active)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L136)


#### Arguments
* $only_active **mixed**



### <a name="method-getTaxRulesGroupsForOptions"></a>getTaxRulesGroupsForOptions

```php
array TaxRulesGroupCore::getTaxRulesGroupsForOptions()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L149)




### <a name="method-getTaxes"></a>getTaxes

```php
mixed TaxRulesGroupCore::getTaxes($id_tax_rules_group, $id_country, $id_state, $id_county)
```

Return taxes associated to this para



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesGroup.php line 237](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L237)


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
* Source: [classes/tax/TaxRulesGroup.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L222)


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
* Source: [classes/tax/TaxRulesGroup.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L198)


#### Arguments
* $id_country **mixed**
* $id_state **mixed**
* $id_tax_rule **mixed**



### <a name="method-historize"></a>historize

```php
mixed TaxRulesGroupCore::historize(\TaxRulesGroup $tax_rules_group)
```

Save the object with the field deleted to true

@return bool

* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L87)


#### Arguments
* $tax_rules_group **[TaxRulesGroup](class.TaxRulesGroupCore.md)**



### <a name="method-isUsed"></a>isUsed

```php
mixed TaxRulesGroupCore::isUsed()
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L210)




### <a name="method-update"></a>update

```php
mixed TaxRulesGroupCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesGroup.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesGroup.php#L68)


#### Arguments
* $null_values **mixed**


