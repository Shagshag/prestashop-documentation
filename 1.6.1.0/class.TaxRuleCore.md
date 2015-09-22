Class TaxRuleCore
=====================





* Class name: TaxRuleCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/tax/TaxRule.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L27)


Contents
--------


### Properties

* [$behavior](#property-$behavior)
* [$definition](#property-$definition)
* [$description](#property-$description)
* [$id_country](#property-$id_country)
* [$id_state](#property-$id_state)
* [$id_tax](#property-$id_tax)
* [$id_tax_rules_group](#property-$id_tax_rules_group)
* [$webserviceParameters](#property-$webserviceParameters)
* [$zipcode_from](#property-$zipcode_from)
* [$zipcode_to](#property-$zipcode_to)

### Methods

* [breakDownZipCode](#method-breakDownZipCode)
* [deleteByGroupId](#method-deleteByGroupId)
* [deleteTaxRuleByIdCounty](#method-deleteTaxRuleByIdCounty)
* [deleteTaxRuleByIdTax](#method-deleteTaxRuleByIdTax)
* [getTaxRulesByGroupId](#method-getTaxRulesByGroupId)
* [isTaxInUse](#method-isTaxInUse)
* [retrieveById](#method-retrieveById)
* [swapTaxId](#method-swapTaxId)




Properties
----------


### <a name="property-$behavior"></a>$behavior

```php
public mixed $behavior
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L35).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'tax_rule', 'primary' => 'id_tax_rule', 'fields' => array('id_tax_rules_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'zipcode_from' => array('type' => self::TYPE_STRING, 'validate' => 'isPostCode'), 'zipcode_to' => array('type' => self::TYPE_STRING, 'validate' => 'isPostCode'), 'id_tax' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'behavior' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'description' => array('type' => self::TYPE_STRING, 'validate' => 'isString')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/tax/TaxRule.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L41).


### <a name="property-$description"></a>$description

```php
public mixed $description
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L36).


### <a name="property-$id_country"></a>$id_country

```php
public mixed $id_country
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L30).


### <a name="property-$id_state"></a>$id_state

```php
public mixed $id_state
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L31).


### <a name="property-$id_tax"></a>$id_tax

```php
public mixed $id_tax
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L34).


### <a name="property-$id_tax_rules_group"></a>$id_tax_rules_group

```php
public mixed $id_tax_rules_group
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L29).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_tax_rules_group' => array('xlink_resource' => 'tax_rule_groups'), 'id_state' => array('xlink_resource' => 'states'), 'id_country' => array('xlink_resource' => 'countries')))
```





* Visibility: **protected**
* Source: [classes/tax/TaxRule.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L56).


### <a name="property-$zipcode_from"></a>$zipcode_from

```php
public mixed $zipcode_from
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L32).


### <a name="property-$zipcode_to"></a>$zipcode_to

```php
public mixed $zipcode_to
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L33).


Methods
-------


### <a name="method-breakDownZipCode"></a>breakDownZipCode

```php
array TaxRuleCore::breakDownZipCode($zip_codes)
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L141)


#### Arguments
* $zip_codes **mixed**



### <a name="method-deleteByGroupId"></a>deleteByGroupId

```php
mixed TaxRuleCore::deleteByGroupId($id_group)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L64)


#### Arguments
* $id_group **mixed**



### <a name="method-deleteTaxRuleByIdCounty"></a>deleteTaxRuleByIdCounty

```php
mixed TaxRuleCore::deleteTaxRuleByIdCounty($id_county)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L114)


#### Arguments
* $id_county **mixed**



### <a name="method-deleteTaxRuleByIdTax"></a>deleteTaxRuleByIdTax

```php
mixed TaxRuleCore::deleteTaxRuleByIdTax($id_tax)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L103)


#### Arguments
* $id_tax **mixed**



### <a name="method-getTaxRulesByGroupId"></a>getTaxRulesByGroupId

```php
mixed TaxRuleCore::getTaxRulesByGroupId($id_lang, $id_group)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L82)


#### Arguments
* $id_lang **mixed**
* $id_group **mixed**



### <a name="method-isTaxInUse"></a>isTaxInUse

```php
boolean TaxRuleCore::isTaxInUse(integer $id_tax)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L124)


#### Arguments
* $id_tax **integer**



### <a name="method-retrieveById"></a>retrieveById

```php
mixed TaxRuleCore::retrieveById($id_tax_rule)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L75)


#### Arguments
* $id_tax_rule **mixed**



### <a name="method-swapTaxId"></a>swapTaxId

```php
mixed TaxRuleCore::swapTaxId(integer $old_id, integer $new_id)
```

Replace a tax_rule id by an other one in the tax_rule table



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxRule.php#L177)


#### Arguments
* $old_id **integer**
* $new_id **integer**


