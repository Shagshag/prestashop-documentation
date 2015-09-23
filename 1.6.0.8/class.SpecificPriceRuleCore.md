Class SpecificPriceRuleCore
=====================





* Class name: SpecificPriceRuleCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/SpecificPriceRule.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L27)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$from](#property-$from)
* [$from_quantity](#property-$from_quantity)
* [$id_country](#property-$id_country)
* [$id_currency](#property-$id_currency)
* [$id_group](#property-$id_group)
* [$id_shop](#property-$id_shop)
* [$name](#property-$name)
* [$price](#property-$price)
* [$reduction](#property-$reduction)
* [$reduction_type](#property-$reduction_type)
* [$rules_application_enable](#property-$rules_application_enable)
* [$to](#property-$to)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [addConditions](#method-addConditions)
* [apply](#method-apply)
* [applyAllRules](#method-applyAllRules)
* [applyRuleToProduct](#method-applyRuleToProduct)
* [delete](#method-delete)
* [deleteConditions](#method-deleteConditions)
* [disableAnyApplication](#method-disableAnyApplication)
* [enableAnyApplication](#method-enableAnyApplication)
* [getAffectedProducts](#method-getAffectedProducts)
* [getConditions](#method-getConditions)
* [resetApplication](#method-resetApplication)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'specific_price_rule', 'primary' => 'id_specific_price_rule', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'required' => true), 'id_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'from_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isNegativePrice', 'required' => true), 'reduction' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'reduction_type' => array('type' => self::TYPE_STRING, 'validate' => 'isReductionType', 'required' => true), 'from' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat', 'required' => false), 'to' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat', 'required' => false)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/SpecificPriceRule.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L46).


### <a name="property-$from"></a>$from

```php
public mixed $from
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L38).


### <a name="property-$from_quantity"></a>$from_quantity

```php
public mixed $from_quantity
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L34).


### <a name="property-$id_country"></a>$id_country

```php
public mixed $id_country
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L32).


### <a name="property-$id_currency"></a>$id_currency

```php
public mixed $id_currency
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L31).


### <a name="property-$id_group"></a>$id_group

```php
public mixed $id_group
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L33).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L30).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L29).


### <a name="property-$price"></a>$price

```php
public mixed $price
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L35).


### <a name="property-$reduction"></a>$reduction

```php
public mixed $reduction
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L36).


### <a name="property-$reduction_type"></a>$reduction_type

```php
public mixed $reduction_type
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L37).


### <a name="property-$rules_application_enable"></a>$rules_application_enable

```php
protected mixed $rules_application_enable = true
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/SpecificPriceRule.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L41).


### <a name="property-$to"></a>$to

```php
public mixed $to
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L39).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'specific_price_rules', 'objectNodeName' => 'specific_price_rule', 'fields' => array('id_shop' => array('xlink_resource' => 'shops', 'required' => true), 'id_country' => array('xlink_resource' => 'countries', 'required' => true), 'id_currency' => array('xlink_resource' => 'currencies', 'required' => true), 'id_group' => array('xlink_resource' => 'groups', 'required' => true)))
```





* Visibility: **protected**
* Source: [classes/SpecificPriceRule.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L64).


Methods
-------


### <a name="method-addConditions"></a>addConditions

```php
mixed SpecificPriceRuleCore::addConditions($conditions)
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L105)


#### Arguments
* $conditions **mixed**



### <a name="method-apply"></a>apply

```php
mixed SpecificPriceRuleCore::apply($products)
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L129)


#### Arguments
* $products **mixed**



### <a name="method-applyAllRules"></a>applyAllRules

```php
mixed SpecificPriceRuleCore::applyAllRules(array $products)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPriceRule.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L151)


#### Arguments
* $products **array**



### <a name="method-applyRuleToProduct"></a>applyRuleToProduct

```php
mixed SpecificPriceRuleCore::applyRuleToProduct($id_rule, $id_product, $id_product_attribute)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPriceRule.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L288)


#### Arguments
* $id_rule **mixed**
* $id_product **mixed**
* $id_product_attribute **mixed**



### <a name="method-delete"></a>delete

```php
mixed SpecificPriceRuleCore::delete()
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L75)




### <a name="method-deleteConditions"></a>deleteConditions

```php
mixed SpecificPriceRuleCore::deleteConditions()
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L82)




### <a name="method-disableAnyApplication"></a>disableAnyApplication

```php
mixed SpecificPriceRuleCore::disableAnyApplication()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPriceRule.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L95)




### <a name="method-enableAnyApplication"></a>enableAnyApplication

```php
mixed SpecificPriceRuleCore::enableAnyApplication()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPriceRule.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L100)




### <a name="method-getAffectedProducts"></a>getAffectedProducts

```php
mixed SpecificPriceRuleCore::getAffectedProducts($products)
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L189)


#### Arguments
* $products **mixed**



### <a name="method-getConditions"></a>getConditions

```php
mixed SpecificPriceRuleCore::getConditions()
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L161)




### <a name="method-resetApplication"></a>resetApplication

```php
mixed SpecificPriceRuleCore::resetApplication($products)
```





* Visibility: **public**
* Source: [classes/SpecificPriceRule.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/SpecificPriceRule.php#L140)


#### Arguments
* $products **mixed**


