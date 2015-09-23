Class CarrierCore
=====================





* Class name: CarrierCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Carrier.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L27)


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





* Source: [classes/Carrier.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L36).


### <a name="constant-CARRIERS_MODULE"></a>CARRIERS_MODULE

```php
const CARRIERS_MODULE = 2
```





* Source: [classes/Carrier.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L33).


### <a name="constant-CARRIERS_MODULE_NEED_RANGE"></a>CARRIERS_MODULE_NEED_RANGE

```php
const CARRIERS_MODULE_NEED_RANGE = 3
```





* Source: [classes/Carrier.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L34).


### <a name="constant-PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE"></a>PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE

```php
const PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE = 4
```





* Source: [classes/Carrier.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L35).


### <a name="constant-PS_CARRIERS_ONLY"></a>PS_CARRIERS_ONLY

```php
const PS_CARRIERS_ONLY = 1
```

getCarriers method filter



* Source: [classes/Carrier.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L32).


### <a name="constant-SHIPPING_METHOD_DEFAULT"></a>SHIPPING_METHOD_DEFAULT

```php
const SHIPPING_METHOD_DEFAULT = 0
```





* Source: [classes/Carrier.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L38).


### <a name="constant-SHIPPING_METHOD_FREE"></a>SHIPPING_METHOD_FREE

```php
const SHIPPING_METHOD_FREE = 3
```





* Source: [classes/Carrier.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L41).


### <a name="constant-SHIPPING_METHOD_PRICE"></a>SHIPPING_METHOD_PRICE

```php
const SHIPPING_METHOD_PRICE = 2
```





* Source: [classes/Carrier.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L40).


### <a name="constant-SHIPPING_METHOD_WEIGHT"></a>SHIPPING_METHOD_WEIGHT

```php
const SHIPPING_METHOD_WEIGHT = 1
```





* Source: [classes/Carrier.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L39).


### <a name="constant-SORT_BY_ASC"></a>SORT_BY_ASC

```php
const SORT_BY_ASC = 0
```





* Source: [classes/Carrier.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L46).


### <a name="constant-SORT_BY_DESC"></a>SORT_BY_DESC

```php
const SORT_BY_DESC = 1
```





* Source: [classes/Carrier.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L47).


### <a name="constant-SORT_BY_POSITION"></a>SORT_BY_POSITION

```php
const SORT_BY_POSITION = 1
```





* Source: [classes/Carrier.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L44).


### <a name="constant-SORT_BY_PRICE"></a>SORT_BY_PRICE

```php
const SORT_BY_PRICE = 0
```





* Source: [classes/Carrier.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L43).


Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Carrier.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L62).


### <a name="property-$cache_tax_rule"></a>$cache_tax_rule

```php
protected mixed $cache_tax_rule = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L149).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'carrier', 'primary' => 'id_carrier', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_reference' => array('type' => self::TYPE_INT), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isCarrierName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'is_free' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'url' => array('type' => self::TYPE_STRING, 'validate' => 'isAbsoluteUrl'), 'shipping_handling' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shipping_external' => array('type' => self::TYPE_BOOL), 'range_behavior' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shipping_method' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_width' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_height' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_depth' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'grade' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 1), 'external_module_name' => array('type' => self::TYPE_STRING, 'size' => 64), 'is_module' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'need_range' => array('type' => self::TYPE_BOOL), 'position' => array('type' => self::TYPE_INT), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'delay' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Carrier.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L112).


### <a name="property-$delay"></a>$delay

```php
public string $delay
```





* Visibility: **public**
* Source: [classes/Carrier.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L59).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Carrier.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L65).


### <a name="property-$external_module_name"></a>$external_module_name

```php
public string $external_module_name = null
```





* Visibility: **public**
* Source: [classes/Carrier.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L86).


### <a name="property-$grade"></a>$grade

```php
public integer $grade
```





* Visibility: **public**
* Source: [classes/Carrier.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L107).


### <a name="property-$id_reference"></a>$id_reference

```php
public integer $id_reference
```





* Visibility: **public**
* Source: [classes/Carrier.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L50).


### <a name="property-$is_free"></a>$is_free

```php
public boolean $is_free = false
```





* Visibility: **public**
* Source: [classes/Carrier.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L77).


### <a name="property-$is_module"></a>$is_module

```php
public boolean $is_module
```





* Visibility: **public**
* Source: [classes/Carrier.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L74).


### <a name="property-$max_depth"></a>$max_depth

```php
public integer $max_depth
```





* Visibility: **public**
* Source: [classes/Carrier.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L101).


### <a name="property-$max_height"></a>$max_height

```php
public integer $max_height
```





* Visibility: **public**
* Source: [classes/Carrier.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L98).


### <a name="property-$max_weight"></a>$max_weight

```php
public integer $max_weight
```





* Visibility: **public**
* Source: [classes/Carrier.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L104).


### <a name="property-$max_width"></a>$max_width

```php
public integer $max_width
```





* Visibility: **public**
* Source: [classes/Carrier.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L95).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Carrier.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L53).


### <a name="property-$need_range"></a>$need_range

```php
public boolean $need_range
```





* Visibility: **public**
* Source: [classes/Carrier.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L89).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/Carrier.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L92).


### <a name="property-$price_by_price"></a>$price_by_price

```php
protected mixed $price_by_price = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L146).


### <a name="property-$price_by_price2"></a>$price_by_price2

```php
protected mixed $price_by_price2 = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L147).


### <a name="property-$price_by_weight"></a>$price_by_weight

```php
protected mixed $price_by_weight = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L144).


### <a name="property-$price_by_weight2"></a>$price_by_weight2

```php
protected mixed $price_by_weight2 = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L145).


### <a name="property-$range_behavior"></a>$range_behavior

```php
public integer $range_behavior
```





* Visibility: **public**
* Source: [classes/Carrier.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L71).


### <a name="property-$shipping_external"></a>$shipping_external

```php
public boolean $shipping_external
```





* Visibility: **public**
* Source: [classes/Carrier.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L83).


### <a name="property-$shipping_handling"></a>$shipping_handling

```php
public boolean $shipping_handling = true
```





* Visibility: **public**
* Source: [classes/Carrier.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L68).


### <a name="property-$shipping_method"></a>$shipping_method

```php
public integer $shipping_method
```





* Visibility: **public**
* Source: [classes/Carrier.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L80).


### <a name="property-$url"></a>$url

```php
public string $url
```





* Visibility: **public**
* Source: [classes/Carrier.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L56).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('deleted' => array(), 'is_module' => array(), 'id_tax_rules_group' => array('getter' => 'getIdTaxRulesGroup', 'setter' => 'setTaxRulesGroup', 'xlink_resource' => array('resourceName' => 'tax_rules_group'))))
```





* Visibility: **protected**
* Source: [classes/Carrier.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L151).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CarrierCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L165)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed CarrierCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L187)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addDeliveryPrice"></a>addDeliveryPrice

```php
boolean CarrierCore::addDeliveryPrice($price_list, $delete)
```

Add new delivery prices



* Visibility: **public**
* Source: [classes/Carrier.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L753)


#### Arguments
* $price_list **mixed**
* $delete **mixed**



### <a name="method-addZone"></a>addZone

```php
mixed CarrierCore::addZone($id_zone)
```

Add zone



* Visibility: **public**
* Source: [classes/Carrier.php line 664](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L664)


#### Arguments
* $id_zone **mixed**



### <a name="method-assignGroupToAllCarriers"></a>assignGroupToAllCarriers

```php
mixed CarrierCore::assignGroupToAllCarriers(integer|array $id_group_list, array $exception)
```

Assign one (ore more) group to all carriers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1263](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L1263)


#### Arguments
* $id_group_list **integer|array** - group id or list of group ids
* $exception **array** - list of id carriers to ignore



### <a name="method-checkCarrierZone"></a>checkCarrierZone

```php
mixed CarrierCore::checkCarrierZone($id_carrier, $id_zone)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 618](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L618)


#### Arguments
* $id_carrier **mixed**
* $id_zone **mixed**



### <a name="method-checkDeliveryPriceByPrice"></a>checkDeliveryPriceByPrice

```php
float CarrierCore::checkDeliveryPriceByPrice($id_carrier, $order_total, integer $id_zone, integer $id_currency)
```

Check delivery prices for a given order



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L338)


#### Arguments
* $id_carrier **mixed**
* $order_total **mixed**
* $id_zone **integer** - Zone id (for customer delivery address)
* $id_currency **integer**



### <a name="method-checkDeliveryPriceByWeight"></a>checkDeliveryPriceByWeight

```php
mixed CarrierCore::checkDeliveryPriceByWeight($id_carrier, $total_weight, $id_zone)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L258)


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
* Source: [classes/Carrier.php line 1126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L1126)




### <a name="method-copyCarrierData"></a>copyCarrierData

```php
mixed CarrierCore::copyCarrierData($old_id)
```

Copy old carrier informations when update carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 805](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L805)


#### Arguments
* $old_id **mixed**



### <a name="method-delete"></a>delete

```php
mixed CarrierCore::delete()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L208)




### <a name="method-deleteDeliveryPrice"></a>deleteDeliveryPrice

```php
boolean CarrierCore::deleteDeliveryPrice($range_table)
```

Clean delivery prices (weight/price)



* Visibility: **public**
* Source: [classes/Carrier.php line 733](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L733)


#### Arguments
* $range_table **mixed**



### <a name="method-deleteTaxRulesGroup"></a>deleteTaxRulesGroup

```php
mixed CarrierCore::deleteTaxRulesGroup(array $shops)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 988](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L988)


#### Arguments
* $shops **array**



### <a name="method-deleteZone"></a>deleteZone

```php
mixed CarrierCore::deleteZone($id_zone)
```

Delete zone



* Visibility: **public**
* Source: [classes/Carrier.php line 697](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L697)


#### Arguments
* $id_zone **mixed**



### <a name="method-getAvailableCarrierList"></a>getAvailableCarrierList

```php
array CarrierCore::getAvailableCarrierList(\Product $product, $id_warehouse, $id_address_delivery, $id_shop, $cart)
```

For a given {product, warehouse}, gets the carrier available



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L1168)


#### Arguments
* $product **[Product](class.ProductCore.md)** - The id of the product, or an array with at least the package size and weight
* $id_warehouse **mixed**
* $id_address_delivery **mixed**
* $id_shop **mixed**
* $cart **mixed**



### <a name="method-getCarrierByReference"></a>getCarrierByReference

```php
mixed CarrierCore::getCarrierByReference($id_reference)
```

Get carrier using the reference id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 892](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L892)


#### Arguments
* $id_reference **mixed**



### <a name="method-getCarriers"></a>getCarriers

```php
array CarrierCore::getCarriers(integer $id_lang, boolean $active, $delete, $id_zone, $ids_group, $modules_filters)
```

Get all carriers in a given language



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 411](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L411)


#### Arguments
* $id_lang **integer** - Language id
* $active **boolean** - Returns only active carriers when true
* $delete **mixed**
* $id_zone **mixed**
* $ids_group **mixed**
* $modules_filters **mixed**



### <a name="method-getCarriersForOrder"></a>getCarriersForOrder

```php
Array CarrierCore::getCarriersForOrder(integer $id_zone, Array $groups, $cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 542](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L542)


#### Arguments
* $id_zone **integer**
* $groups **Array** - group of the customer
* $cart **mixed**



### <a name="method-getDefaultCarrierSelection"></a>getDefaultCarrierSelection

```php
\number CarrierCore::getDefaultCarrierSelection(array $carriers, $default_carrier)
```

Return the default carrier to use



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 520](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L520)


#### Arguments
* $carriers **array**
* $default_carrier **mixed**



### <a name="method-getDeliveredCountries"></a>getDeliveredCountries

```php
mixed CarrierCore::getDeliveredCountries($id_lang, $active_countries, $active_carriers, $contain_states)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L479)


#### Arguments
* $id_lang **mixed**
* $active_countries **mixed**
* $active_carriers **mixed**
* $contain_states **mixed**



### <a name="method-getDeliveryPriceByPrice"></a>getDeliveryPriceByPrice

```php
float CarrierCore::getDeliveryPriceByPrice($order_total, integer $id_zone, $id_currency)
```

Get delivery prices for a given order



* Visibility: **public**
* Source: [classes/Carrier.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L303)


#### Arguments
* $order_total **mixed**
* $id_zone **integer** - Zone id (for customer delivery address)
* $id_currency **mixed**



### <a name="method-getDeliveryPriceByRanges"></a>getDeliveryPriceByRanges

```php
array CarrierCore::getDeliveryPriceByRanges($range_table, $id_carrier)
```

Get delivery prices for a given shipping method (price/weight)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 385](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L385)


#### Arguments
* $range_table **mixed**
* $id_carrier **mixed**



### <a name="method-getDeliveryPriceByWeight"></a>getDeliveryPriceByWeight

```php
float CarrierCore::getDeliveryPriceByWeight($total_weight, integer $id_zone)
```

Get delivery prices for a given order



* Visibility: **public**
* Source: [classes/Carrier.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L235)


#### Arguments
* $total_weight **mixed**
* $id_zone **integer** - Zone id (for customer delivery address)



### <a name="method-getGroups"></a>getGroups

```php
array CarrierCore::getGroups()
```

Gets a specific group



* Visibility: **public**
* Source: [classes/Carrier.php line 719](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L719)




### <a name="method-getHigherPosition"></a>getHigherPosition

```php
integer CarrierCore::getHigherPosition()
```

Gets the highest carrier position



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L1152)




### <a name="method-getIdTaxRulesGroup"></a>getIdTaxRulesGroup

```php
mixed CarrierCore::getIdTaxRulesGroup(\Context $context)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 968](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L968)


#### Arguments
* $context **[Context](class.ContextCore.md)**



### <a name="method-getIdTaxRulesGroupByIdCarrier"></a>getIdTaxRulesGroupByIdCarrier

```php
mixed CarrierCore::getIdTaxRulesGroupByIdCarrier($id_carrier, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 973](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L973)


#### Arguments
* $id_carrier **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getIdTaxRulesGroupMostUsed"></a>getIdTaxRulesGroupMostUsed

```php
mixed CarrierCore::getIdTaxRulesGroupMostUsed()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 463](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L463)




### <a name="method-getMaxDeliveryPriceByPrice"></a>getMaxDeliveryPriceByPrice

```php
mixed CarrierCore::getMaxDeliveryPriceByPrice($id_zone)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 361](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L361)


#### Arguments
* $id_zone **mixed**



### <a name="method-getMaxDeliveryPriceByWeight"></a>getMaxDeliveryPriceByWeight

```php
mixed CarrierCore::getMaxDeliveryPriceByWeight($id_zone)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L278)


#### Arguments
* $id_zone **mixed**



### <a name="method-getRangeObject"></a>getRangeObject

```php
mixed CarrierCore::getRangeObject($shipping_method)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 946](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L946)


#### Arguments
* $shipping_method **mixed**



### <a name="method-getRangeSuffix"></a>getRangeSuffix

```php
mixed CarrierCore::getRangeSuffix($currency)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 958](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L958)


#### Arguments
* $currency **mixed**



### <a name="method-getRangeTable"></a>getRangeTable

```php
mixed CarrierCore::getRangeTable()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 936](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L936)




### <a name="method-getShippingMethod"></a>getShippingMethod

```php
mixed CarrierCore::getShippingMethod()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 917](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L917)




### <a name="method-getTaxCalculator"></a>getTaxCalculator

```php
 CarrierCore::getTaxCalculator(\Address $address)
```

Returns the taxes calculator associated to the carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 1042](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L1042)


#### Arguments
* $address **[Address](class.AddressCore.md)**



### <a name="method-getTaxesRate"></a>getTaxesRate

```php
 CarrierCore::getTaxesRate(\Address $address)
```

Returns the taxes rate associated to the carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 1029](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L1029)


#### Arguments
* $address **[Address](class.AddressCore.md)**



### <a name="method-getZone"></a>getZone

```php
array CarrierCore::getZone($id_zone)
```

Get a specific zones



* Visibility: **public**
* Source: [classes/Carrier.php line 652](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L652)


#### Arguments
* $id_zone **mixed**



### <a name="method-getZones"></a>getZones

```php
array CarrierCore::getZones()
```

Get all zones



* Visibility: **public**
* Source: [classes/Carrier.php line 638](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L638)




### <a name="method-isUsed"></a>isUsed

```php
integer CarrierCore::isUsed()
```

Check if carrier is used (at least one order placed)



* Visibility: **public**
* Source: [classes/Carrier.php line 907](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L907)




### <a name="method-setConfiguration"></a>setConfiguration

```php
mixed CarrierCore::setConfiguration(integer $id_old)
```

Change carrier id in delivery prices when updating a carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L223)


#### Arguments
* $id_old **integer** - Old id carrier



### <a name="method-setGroups"></a>setGroups

```php
mixed CarrierCore::setGroups($groups, $delete)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 1294](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L1294)


#### Arguments
* $groups **mixed**
* $delete **mixed**



### <a name="method-setTaxRulesGroup"></a>setTaxRulesGroup

```php
mixed CarrierCore::setTaxRulesGroup($id_tax_rules_group, $all_shops)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 999](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L999)


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
* Source: [classes/Carrier.php line 1055](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L1055)


#### Arguments
* $range_table **mixed**
* $alias **mixed**



### <a name="method-updatePosition"></a>updatePosition

```php
boolean CarrierCore::updatePosition(boolean $way, integer $position)
```

Moves a carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 1086](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/Carrier.php#L1086)


#### Arguments
* $way **boolean** - Up (1) or Down (0)
* $position **integer**


