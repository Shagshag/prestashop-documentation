Class CarrierCore
=====================





* Class name: CarrierCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Carrier.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L27)


Contents
--------

### Constants

* [ALL_CARRIERS](#constant-ALL_CARRIERS)
* [CARRIERS_MODULE](#constant-CARRIERS_MODULE)
* [CARRIERS_MODULE_NEED_RANGE](#constant-CARRIERS_MODULE_NEED_RANGE)
* [PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE](#constant-PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE)
* [PS_CARRIERS_ONLY](#constant-PS_CARRIERS_ONLY)
* [SHIPPING_METHOD_DEFAULT](#constant-SHIPPING_METHOD_DEFAULT)
* [SHIPPING_METHOD_FREE](#constant-SHIPPING_METHOD_FREE)
* [SHIPPING_METHOD_PRICE](#constant-SHIPPING_METHOD_PRICE)
* [SHIPPING_METHOD_WEIGHT](#constant-SHIPPING_METHOD_WEIGHT)
* [SHIPPING_PRICE_EXCEPTION](#constant-SHIPPING_PRICE_EXCEPTION)
* [SHIPPING_SIZE_EXCEPTION](#constant-SHIPPING_SIZE_EXCEPTION)
* [SHIPPING_WEIGHT_EXCEPTION](#constant-SHIPPING_WEIGHT_EXCEPTION)
* [SORT_BY_ASC](#constant-SORT_BY_ASC)
* [SORT_BY_DESC](#constant-SORT_BY_DESC)
* [SORT_BY_POSITION](#constant-SORT_BY_POSITION)
* [SORT_BY_PRICE](#constant-SORT_BY_PRICE)

### Properties

* [$active](#property-$active)
* [$cache_tax_rule](#property-$cache_tax_rule)
* [$definition](#property-$definition)
* [$delay](#property-$delay)
* [$deleted](#property-$deleted)
* [$external_module_name](#property-$external_module_name)
* [$grade](#property-$grade)
* [$id_reference](#property-$id_reference)
* [$is_free](#property-$is_free)
* [$is_module](#property-$is_module)
* [$max_depth](#property-$max_depth)
* [$max_height](#property-$max_height)
* [$max_weight](#property-$max_weight)
* [$max_width](#property-$max_width)
* [$name](#property-$name)
* [$need_range](#property-$need_range)
* [$position](#property-$position)
* [$price_by_price](#property-$price_by_price)
* [$price_by_price2](#property-$price_by_price2)
* [$price_by_weight](#property-$price_by_weight)
* [$price_by_weight2](#property-$price_by_weight2)
* [$range_behavior](#property-$range_behavior)
* [$shipping_external](#property-$shipping_external)
* [$shipping_handling](#property-$shipping_handling)
* [$shipping_method](#property-$shipping_method)
* [$url](#property-$url)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addDeliveryPrice](#method-addDeliveryPrice)
* [addZone](#method-addZone)
* [assignGroupToAllCarriers](#method-assignGroupToAllCarriers)
* [checkCarrierZone](#method-checkCarrierZone)
* [checkDeliveryPriceByPrice](#method-checkDeliveryPriceByPrice)
* [checkDeliveryPriceByWeight](#method-checkDeliveryPriceByWeight)
* [cleanPositions](#method-cleanPositions)
* [copyCarrierData](#method-copyCarrierData)
* [delete](#method-delete)
* [deleteDeliveryPrice](#method-deleteDeliveryPrice)
* [deleteTaxRulesGroup](#method-deleteTaxRulesGroup)
* [deleteZone](#method-deleteZone)
* [getAvailableCarrierList](#method-getAvailableCarrierList)
* [getCarrierByReference](#method-getCarrierByReference)
* [getCarrierNameFromShopName](#method-getCarrierNameFromShopName)
* [getCarriers](#method-getCarriers)
* [getCarriersForOrder](#method-getCarriersForOrder)
* [getDefaultCarrierSelection](#method-getDefaultCarrierSelection)
* [getDeliveredCountries](#method-getDeliveredCountries)
* [getDeliveryPriceByPrice](#method-getDeliveryPriceByPrice)
* [getDeliveryPriceByRanges](#method-getDeliveryPriceByRanges)
* [getDeliveryPriceByWeight](#method-getDeliveryPriceByWeight)
* [getGroups](#method-getGroups)
* [getHigherPosition](#method-getHigherPosition)
* [getIdTaxRulesGroup](#method-getIdTaxRulesGroup)
* [getIdTaxRulesGroupByIdCarrier](#method-getIdTaxRulesGroupByIdCarrier)
* [getIdTaxRulesGroupMostUsed](#method-getIdTaxRulesGroupMostUsed)
* [getMaxDeliveryPriceByPrice](#method-getMaxDeliveryPriceByPrice)
* [getMaxDeliveryPriceByWeight](#method-getMaxDeliveryPriceByWeight)
* [getRangeObject](#method-getRangeObject)
* [getRangeSuffix](#method-getRangeSuffix)
* [getRangeTable](#method-getRangeTable)
* [getShippingMethod](#method-getShippingMethod)
* [getTaxCalculator](#method-getTaxCalculator)
* [getTaxesRate](#method-getTaxesRate)
* [getZone](#method-getZone)
* [getZones](#method-getZones)
* [isUsed](#method-isUsed)
* [setConfiguration](#method-setConfiguration)
* [setGroups](#method-setGroups)
* [setTaxRulesGroup](#method-setTaxRulesGroup)
* [sqlDeliveryRangeShop](#method-sqlDeliveryRangeShop)
* [updatePosition](#method-updatePosition)


Constants
----------


### <a name="constant-ALL_CARRIERS"></a>ALL_CARRIERS

```php
const ALL_CARRIERS = 5
```





* Source: [classes/Carrier.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L36).


### <a name="constant-CARRIERS_MODULE"></a>CARRIERS_MODULE

```php
const CARRIERS_MODULE = 2
```





* Source: [classes/Carrier.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L33).


### <a name="constant-CARRIERS_MODULE_NEED_RANGE"></a>CARRIERS_MODULE_NEED_RANGE

```php
const CARRIERS_MODULE_NEED_RANGE = 3
```





* Source: [classes/Carrier.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L34).


### <a name="constant-PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE"></a>PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE

```php
const PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE = 4
```





* Source: [classes/Carrier.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L35).


### <a name="constant-PS_CARRIERS_ONLY"></a>PS_CARRIERS_ONLY

```php
const PS_CARRIERS_ONLY = 1
```

getCarriers method filter



* Source: [classes/Carrier.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L32).


### <a name="constant-SHIPPING_METHOD_DEFAULT"></a>SHIPPING_METHOD_DEFAULT

```php
const SHIPPING_METHOD_DEFAULT = 0
```





* Source: [classes/Carrier.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L38).


### <a name="constant-SHIPPING_METHOD_FREE"></a>SHIPPING_METHOD_FREE

```php
const SHIPPING_METHOD_FREE = 3
```





* Source: [classes/Carrier.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L41).


### <a name="constant-SHIPPING_METHOD_PRICE"></a>SHIPPING_METHOD_PRICE

```php
const SHIPPING_METHOD_PRICE = 2
```





* Source: [classes/Carrier.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L40).


### <a name="constant-SHIPPING_METHOD_WEIGHT"></a>SHIPPING_METHOD_WEIGHT

```php
const SHIPPING_METHOD_WEIGHT = 1
```





* Source: [classes/Carrier.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L39).


### <a name="constant-SHIPPING_PRICE_EXCEPTION"></a>SHIPPING_PRICE_EXCEPTION

```php
const SHIPPING_PRICE_EXCEPTION = 0
```





* Source: [classes/Carrier.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L43).


### <a name="constant-SHIPPING_SIZE_EXCEPTION"></a>SHIPPING_SIZE_EXCEPTION

```php
const SHIPPING_SIZE_EXCEPTION = 2
```





* Source: [classes/Carrier.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L45).


### <a name="constant-SHIPPING_WEIGHT_EXCEPTION"></a>SHIPPING_WEIGHT_EXCEPTION

```php
const SHIPPING_WEIGHT_EXCEPTION = 1
```





* Source: [classes/Carrier.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L44).


### <a name="constant-SORT_BY_ASC"></a>SORT_BY_ASC

```php
const SORT_BY_ASC = 0
```





* Source: [classes/Carrier.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L50).


### <a name="constant-SORT_BY_DESC"></a>SORT_BY_DESC

```php
const SORT_BY_DESC = 1
```





* Source: [classes/Carrier.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L51).


### <a name="constant-SORT_BY_POSITION"></a>SORT_BY_POSITION

```php
const SORT_BY_POSITION = 1
```





* Source: [classes/Carrier.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L48).


### <a name="constant-SORT_BY_PRICE"></a>SORT_BY_PRICE

```php
const SORT_BY_PRICE = 0
```





* Source: [classes/Carrier.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L47).


Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Carrier.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L66).


### <a name="property-$cache_tax_rule"></a>$cache_tax_rule

```php
protected mixed $cache_tax_rule = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L153).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'carrier', 'primary' => 'id_carrier', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_reference' => array('type' => self::TYPE_INT), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isCarrierName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'is_free' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'url' => array('type' => self::TYPE_STRING, 'validate' => 'isAbsoluteUrl'), 'shipping_handling' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shipping_external' => array('type' => self::TYPE_BOOL), 'range_behavior' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shipping_method' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_width' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_height' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_depth' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'grade' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 1), 'external_module_name' => array('type' => self::TYPE_STRING, 'size' => 64), 'is_module' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'need_range' => array('type' => self::TYPE_BOOL), 'position' => array('type' => self::TYPE_INT), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'delay' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Carrier.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L116).


### <a name="property-$delay"></a>$delay

```php
public string $delay
```





* Visibility: **public**
* Source: [classes/Carrier.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L63).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Carrier.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L69).


### <a name="property-$external_module_name"></a>$external_module_name

```php
public string $external_module_name = null
```





* Visibility: **public**
* Source: [classes/Carrier.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L90).


### <a name="property-$grade"></a>$grade

```php
public integer $grade
```





* Visibility: **public**
* Source: [classes/Carrier.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L111).


### <a name="property-$id_reference"></a>$id_reference

```php
public integer $id_reference
```





* Visibility: **public**
* Source: [classes/Carrier.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L54).


### <a name="property-$is_free"></a>$is_free

```php
public boolean $is_free = false
```





* Visibility: **public**
* Source: [classes/Carrier.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L81).


### <a name="property-$is_module"></a>$is_module

```php
public boolean $is_module
```





* Visibility: **public**
* Source: [classes/Carrier.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L78).


### <a name="property-$max_depth"></a>$max_depth

```php
public integer $max_depth
```





* Visibility: **public**
* Source: [classes/Carrier.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L105).


### <a name="property-$max_height"></a>$max_height

```php
public integer $max_height
```





* Visibility: **public**
* Source: [classes/Carrier.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L102).


### <a name="property-$max_weight"></a>$max_weight

```php
public integer $max_weight
```





* Visibility: **public**
* Source: [classes/Carrier.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L108).


### <a name="property-$max_width"></a>$max_width

```php
public integer $max_width
```





* Visibility: **public**
* Source: [classes/Carrier.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L99).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Carrier.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L57).


### <a name="property-$need_range"></a>$need_range

```php
public boolean $need_range
```





* Visibility: **public**
* Source: [classes/Carrier.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L93).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/Carrier.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L96).


### <a name="property-$price_by_price"></a>$price_by_price

```php
protected mixed $price_by_price = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L150).


### <a name="property-$price_by_price2"></a>$price_by_price2

```php
protected mixed $price_by_price2 = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L151).


### <a name="property-$price_by_weight"></a>$price_by_weight

```php
protected mixed $price_by_weight = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L148).


### <a name="property-$price_by_weight2"></a>$price_by_weight2

```php
protected mixed $price_by_weight2 = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L149).


### <a name="property-$range_behavior"></a>$range_behavior

```php
public integer $range_behavior
```





* Visibility: **public**
* Source: [classes/Carrier.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L75).


### <a name="property-$shipping_external"></a>$shipping_external

```php
public boolean $shipping_external
```





* Visibility: **public**
* Source: [classes/Carrier.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L87).


### <a name="property-$shipping_handling"></a>$shipping_handling

```php
public boolean $shipping_handling = true
```





* Visibility: **public**
* Source: [classes/Carrier.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L72).


### <a name="property-$shipping_method"></a>$shipping_method

```php
public integer $shipping_method
```





* Visibility: **public**
* Source: [classes/Carrier.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L84).


### <a name="property-$url"></a>$url

```php
public string $url
```





* Visibility: **public**
* Source: [classes/Carrier.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L60).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('deleted' => array(), 'is_module' => array(), 'id_tax_rules_group' => array('getter' => 'getIdTaxRulesGroup', 'setter' => 'setTaxRulesGroup', 'xlink_resource' => array('resourceName' => 'tax_rule_groups'))))
```





* Visibility: **protected**
* Source: [classes/Carrier.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L155).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CarrierCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L169)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed CarrierCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 193](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L193)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addDeliveryPrice"></a>addDeliveryPrice

```php
boolean CarrierCore::addDeliveryPrice($price_list, $delete)
```

Add new delivery prices



* Visibility: **public**
* Source: [classes/Carrier.php line 808](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L808)


#### Arguments
* $price_list **mixed**
* $delete **mixed**



### <a name="method-addZone"></a>addZone

```php
mixed CarrierCore::addZone($id_zone)
```

Add zone



* Visibility: **public**
* Source: [classes/Carrier.php line 719](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L719)


#### Arguments
* $id_zone **mixed**



### <a name="method-assignGroupToAllCarriers"></a>assignGroupToAllCarriers

```php
mixed CarrierCore::assignGroupToAllCarriers(integer|array $id_group_list, array $exception)
```

Assign one (ore more) group to all carriers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1366](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1366)


#### Arguments
* $id_group_list **integer|array** - group id or list of group ids
* $exception **array** - list of id carriers to ignore



### <a name="method-checkCarrierZone"></a>checkCarrierZone

```php
mixed CarrierCore::checkCarrierZone($id_carrier, $id_zone)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 668](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L668)


#### Arguments
* $id_carrier **mixed**
* $id_zone **mixed**



### <a name="method-checkDeliveryPriceByPrice"></a>checkDeliveryPriceByPrice

```php
float CarrierCore::checkDeliveryPriceByPrice(integer $id_carrier, float $order_total, integer $id_zone, integer|null $id_currency)
```

Check delivery prices for a given order



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L364)


#### Arguments
* $id_carrier **integer**
* $order_total **float** - Order total to pay
* $id_zone **integer** - Zone id (for customer delivery address)
* $id_currency **integer|null**



### <a name="method-checkDeliveryPriceByWeight"></a>checkDeliveryPriceByWeight

```php
mixed CarrierCore::checkDeliveryPriceByWeight($id_carrier, $total_weight, $id_zone)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L270)


#### Arguments
* $id_carrier **mixed**
* $total_weight **mixed**
* $id_zone **mixed**



### <a name="method-cleanPositions"></a>cleanPositions

```php
boolean CarrierCore::cleanPositions()
```

Reorders carrier positions.

Called after deleting a carrier.

* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1187)




### <a name="method-copyCarrierData"></a>copyCarrierData

```php
mixed CarrierCore::copyCarrierData($old_id)
```

Copy old carrier informations when update carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 860](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L860)


#### Arguments
* $old_id **mixed**



### <a name="method-delete"></a>delete

```php
mixed CarrierCore::delete()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L214)




### <a name="method-deleteDeliveryPrice"></a>deleteDeliveryPrice

```php
boolean CarrierCore::deleteDeliveryPrice($range_table)
```

Clean delivery prices (weight/price)



* Visibility: **public**
* Source: [classes/Carrier.php line 788](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L788)


#### Arguments
* $range_table **mixed**



### <a name="method-deleteTaxRulesGroup"></a>deleteTaxRulesGroup

```php
mixed CarrierCore::deleteTaxRulesGroup(array $shops)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 1045](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1045)


#### Arguments
* $shops **array**



### <a name="method-deleteZone"></a>deleteZone

```php
mixed CarrierCore::deleteZone($id_zone)
```

Delete zone



* Visibility: **public**
* Source: [classes/Carrier.php line 752](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L752)


#### Arguments
* $id_zone **mixed**



### <a name="method-getAvailableCarrierList"></a>getAvailableCarrierList

```php
array CarrierCore::getAvailableCarrierList(\Product $product, $id_warehouse, integer $id_address_delivery, integer $id_shop, \Cart $cart, $error)
```

For a given {product, warehouse}, gets the carrier available



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1235)


#### Arguments
* $product **[Product](class.ProductCore.md)** - The id of the product, or an array with at least the package size and weight
* $id_warehouse **mixed**
* $id_address_delivery **integer**
* $id_shop **integer**
* $cart **[Cart](class.CartCore.md)**
* $error **mixed**



### <a name="method-getCarrierByReference"></a>getCarrierByReference

```php
mixed CarrierCore::getCarrierByReference($id_reference)
```

Get carrier using the reference id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 947](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L947)


#### Arguments
* $id_reference **mixed**



### <a name="method-getCarrierNameFromShopName"></a>getCarrierNameFromShopName

```php
string CarrierCore::getCarrierNameFromShopName()
```

Return the carrier name from the shop name (e.g. if the carrier name is '0').

The returned carrier name is the shop name without '#' and ';' because this is not the same validation.

* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1417](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1417)




### <a name="method-getCarriers"></a>getCarriers

```php
array CarrierCore::getCarriers(integer $id_lang, boolean $active, $delete, $id_zone, $ids_group, $modules_filters)
```

Get all carriers in a given language



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 443](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L443)


#### Arguments
* $id_lang **integer** - Language id
* $active **boolean** - Returns only active carriers when true
* $delete **mixed**
* $id_zone **mixed**
* $ids_group **mixed**
* $modules_filters **mixed**



### <a name="method-getCarriersForOrder"></a>getCarriersForOrder

```php
Array CarrierCore::getCarriersForOrder(integer $id_zone, Array $groups, $cart, $error)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 578](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L578)


#### Arguments
* $id_zone **integer**
* $groups **Array** - group of the customer
* $cart **mixed**
* $error **mixed**



### <a name="method-getDefaultCarrierSelection"></a>getDefaultCarrierSelection

```php
\number CarrierCore::getDefaultCarrierSelection(array $carriers, $default_carrier)
```

Return the default carrier to use



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 555](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L555)


#### Arguments
* $carriers **array**
* $default_carrier **mixed**



### <a name="method-getDeliveredCountries"></a>getDeliveredCountries

```php
mixed CarrierCore::getDeliveredCountries($id_lang, $active_countries, $active_carriers, $contain_states)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L514)


#### Arguments
* $id_lang **mixed**
* $active_countries **mixed**
* $active_carriers **mixed**
* $contain_states **mixed**



### <a name="method-getDeliveryPriceByPrice"></a>getDeliveryPriceByPrice

```php
float CarrierCore::getDeliveryPriceByPrice(float $order_total, integer $id_zone, integer|null $id_currency)
```

Get delivery prices for a given order



* Visibility: **public**
* Source: [classes/Carrier.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L323)


#### Arguments
* $order_total **float** - Order total to pay
* $id_zone **integer** - Zone id (for customer delivery address)
* $id_currency **integer|null**



### <a name="method-getDeliveryPriceByRanges"></a>getDeliveryPriceByRanges

```php
array CarrierCore::getDeliveryPriceByRanges($range_table, $id_carrier)
```

Get delivery prices for a given shipping method (price/weight)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 417](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L417)


#### Arguments
* $range_table **mixed**
* $id_carrier **mixed**



### <a name="method-getDeliveryPriceByWeight"></a>getDeliveryPriceByWeight

```php
float CarrierCore::getDeliveryPriceByWeight(float $total_weight, integer $id_zone)
```

Get delivery prices for a given order



* Visibility: **public**
* Source: [classes/Carrier.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L241)


#### Arguments
* $total_weight **float** - Total order weight
* $id_zone **integer** - Zone ID (for customer delivery address)



### <a name="method-getGroups"></a>getGroups

```php
array CarrierCore::getGroups()
```

Gets a specific group



* Visibility: **public**
* Source: [classes/Carrier.php line 774](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L774)




### <a name="method-getHigherPosition"></a>getHigherPosition

```php
integer CarrierCore::getHigherPosition()
```

Gets the highest carrier position



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1213)




### <a name="method-getIdTaxRulesGroup"></a>getIdTaxRulesGroup

```php
mixed CarrierCore::getIdTaxRulesGroup(\Context $context)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 1023](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1023)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-getIdTaxRulesGroupByIdCarrier"></a>getIdTaxRulesGroupByIdCarrier

```php
mixed CarrierCore::getIdTaxRulesGroupByIdCarrier($id_carrier, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1028](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1028)


#### Arguments
* $id_carrier **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getIdTaxRulesGroupMostUsed"></a>getIdTaxRulesGroupMostUsed

```php
mixed CarrierCore::getIdTaxRulesGroupMostUsed()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 498](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L498)




### <a name="method-getMaxDeliveryPriceByPrice"></a>getMaxDeliveryPriceByPrice

```php
mixed CarrierCore::getMaxDeliveryPriceByPrice($id_zone)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L393)


#### Arguments
* $id_zone **mixed**



### <a name="method-getMaxDeliveryPriceByWeight"></a>getMaxDeliveryPriceByWeight

```php
mixed CarrierCore::getMaxDeliveryPriceByWeight($id_zone)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L296)


#### Arguments
* $id_zone **mixed**



### <a name="method-getRangeObject"></a>getRangeObject

```php
mixed CarrierCore::getRangeObject($shipping_method)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 1001](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1001)


#### Arguments
* $shipping_method **mixed**



### <a name="method-getRangeSuffix"></a>getRangeSuffix

```php
mixed CarrierCore::getRangeSuffix($currency)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 1013](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1013)


#### Arguments
* $currency **mixed**



### <a name="method-getRangeTable"></a>getRangeTable

```php
mixed CarrierCore::getRangeTable()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 991](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L991)




### <a name="method-getShippingMethod"></a>getShippingMethod

```php
mixed CarrierCore::getShippingMethod()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 972](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L972)




### <a name="method-getTaxCalculator"></a>getTaxCalculator

```php
 CarrierCore::getTaxCalculator(\Address $address, $id_order, $use_average_tax_of_products)
```

Returns the taxes calculator associated to the carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 1099](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1099)


#### Arguments
* $address **[Address](class.AddressCore.md)**
* $id_order **mixed**
* $use_average_tax_of_products **mixed**



### <a name="method-getTaxesRate"></a>getTaxesRate

```php
 CarrierCore::getTaxesRate(\Address $address)
```

Returns the taxes rate associated to the carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 1086](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1086)


#### Arguments
* $address **[Address](class.AddressCore.md)**



### <a name="method-getZone"></a>getZone

```php
array CarrierCore::getZone($id_zone)
```

Get a specific zones



* Visibility: **public**
* Source: [classes/Carrier.php line 707](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L707)


#### Arguments
* $id_zone **mixed**



### <a name="method-getZones"></a>getZones

```php
array CarrierCore::getZones()
```

Get all zones



* Visibility: **public**
* Source: [classes/Carrier.php line 693](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L693)




### <a name="method-isUsed"></a>isUsed

```php
integer CarrierCore::isUsed()
```

Check if carrier is used (at least one order placed)



* Visibility: **public**
* Source: [classes/Carrier.php line 962](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L962)




### <a name="method-setConfiguration"></a>setConfiguration

```php
mixed CarrierCore::setConfiguration(integer $id_old)
```

Change carrier id in delivery prices when updating a carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L229)


#### Arguments
* $id_old **integer** - Old id carrier



### <a name="method-setGroups"></a>setGroups

```php
mixed CarrierCore::setGroups($groups, $delete)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 1397](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1397)


#### Arguments
* $groups **mixed**
* $delete **mixed**



### <a name="method-setTaxRulesGroup"></a>setTaxRulesGroup

```php
mixed CarrierCore::setTaxRulesGroup($id_tax_rules_group, $all_shops)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 1056](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1056)


#### Arguments
* $id_tax_rules_group **mixed**
* $all_shops **mixed**



### <a name="method-sqlDeliveryRangeShop"></a>sqlDeliveryRangeShop

```php
string CarrierCore::sqlDeliveryRangeShop($range_table, $alias)
```

This tricky method generates a sql clause to check if ranged data are overloaded by multishop



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1116)


#### Arguments
* $range_table **mixed**
* $alias **mixed**



### <a name="method-updatePosition"></a>updatePosition

```php
boolean CarrierCore::updatePosition(boolean $way, integer $position)
```

Moves a carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 1147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Carrier.php#L1147)


#### Arguments
* $way **boolean** - Up (1) or Down (0)
* $position **integer**


