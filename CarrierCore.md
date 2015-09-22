CarrierCore
===============






* Class name: CarrierCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Carrier.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L27)



Constants
----------

* [PS_CARRIERS_ONLY](#constant-PS_CARRIERS_ONLY)
* [CARRIERS_MODULE](#constant-CARRIERS_MODULE)
* [CARRIERS_MODULE_NEED_RANGE](#constant-CARRIERS_MODULE_NEED_RANGE)
* [PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE](#constant-PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE)
* [ALL_CARRIERS](#constant-ALL_CARRIERS)
* [SHIPPING_METHOD_DEFAULT](#constant-SHIPPING_METHOD_DEFAULT)
* [SHIPPING_METHOD_WEIGHT](#constant-SHIPPING_METHOD_WEIGHT)
* [SHIPPING_METHOD_PRICE](#constant-SHIPPING_METHOD_PRICE)
* [SHIPPING_METHOD_FREE](#constant-SHIPPING_METHOD_FREE)
* [SHIPPING_PRICE_EXCEPTION](#constant-SHIPPING_PRICE_EXCEPTION)
* [SHIPPING_WEIGHT_EXCEPTION](#constant-SHIPPING_WEIGHT_EXCEPTION)
* [SHIPPING_SIZE_EXCEPTION](#constant-SHIPPING_SIZE_EXCEPTION)
* [SORT_BY_PRICE](#constant-SORT_BY_PRICE)
* [SORT_BY_POSITION](#constant-SORT_BY_POSITION)
* [SORT_BY_ASC](#constant-SORT_BY_ASC)
* [SORT_BY_DESC](#constant-SORT_BY_DESC)

Properties
----------

* [$id_reference](#property-$id_reference)
* [$name](#property-$name)
* [$url](#property-$url)
* [$delay](#property-$delay)
* [$active](#property-$active)
* [$deleted](#property-$deleted)
* [$shipping_handling](#property-$shipping_handling)
* [$range_behavior](#property-$range_behavior)
* [$is_module](#property-$is_module)
* [$is_free](#property-$is_free)
* [$shipping_method](#property-$shipping_method)
* [$shipping_external](#property-$shipping_external)
* [$external_module_name](#property-$external_module_name)
* [$need_range](#property-$need_range)
* [$position](#property-$position)
* [$max_width](#property-$max_width)
* [$max_height](#property-$max_height)
* [$max_depth](#property-$max_depth)
* [$max_weight](#property-$max_weight)
* [$grade](#property-$grade)
* [$definition](#property-$definition)
* [$price_by_weight](#property-$price_by_weight)
* [$price_by_weight2](#property-$price_by_weight2)
* [$price_by_price](#property-$price_by_price)
* [$price_by_price2](#property-$price_by_price2)
* [$cache_tax_rule](#property-$cache_tax_rule)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [__construct](#method-__construct)
* [add](#method-add)
* [delete](#method-delete)
* [setConfiguration](#method-setConfiguration)
* [getDeliveryPriceByWeight](#method-getDeliveryPriceByWeight)
* [checkDeliveryPriceByWeight](#method-checkDeliveryPriceByWeight)
* [getMaxDeliveryPriceByWeight](#method-getMaxDeliveryPriceByWeight)
* [getDeliveryPriceByPrice](#method-getDeliveryPriceByPrice)
* [checkDeliveryPriceByPrice](#method-checkDeliveryPriceByPrice)
* [getMaxDeliveryPriceByPrice](#method-getMaxDeliveryPriceByPrice)
* [getDeliveryPriceByRanges](#method-getDeliveryPriceByRanges)
* [getCarriers](#method-getCarriers)
* [getIdTaxRulesGroupMostUsed](#method-getIdTaxRulesGroupMostUsed)
* [getDeliveredCountries](#method-getDeliveredCountries)
* [getDefaultCarrierSelection](#method-getDefaultCarrierSelection)
* [getCarriersForOrder](#method-getCarriersForOrder)
* [checkCarrierZone](#method-checkCarrierZone)
* [getZones](#method-getZones)
* [getZone](#method-getZone)
* [addZone](#method-addZone)
* [deleteZone](#method-deleteZone)
* [getGroups](#method-getGroups)
* [deleteDeliveryPrice](#method-deleteDeliveryPrice)
* [addDeliveryPrice](#method-addDeliveryPrice)
* [copyCarrierData](#method-copyCarrierData)
* [getCarrierByReference](#method-getCarrierByReference)
* [isUsed](#method-isUsed)
* [getShippingMethod](#method-getShippingMethod)
* [getRangeTable](#method-getRangeTable)
* [getRangeObject](#method-getRangeObject)
* [getRangeSuffix](#method-getRangeSuffix)
* [getIdTaxRulesGroup](#method-getIdTaxRulesGroup)
* [getIdTaxRulesGroupByIdCarrier](#method-getIdTaxRulesGroupByIdCarrier)
* [deleteTaxRulesGroup](#method-deleteTaxRulesGroup)
* [setTaxRulesGroup](#method-setTaxRulesGroup)
* [getTaxesRate](#method-getTaxesRate)
* [getTaxCalculator](#method-getTaxCalculator)
* [sqlDeliveryRangeShop](#method-sqlDeliveryRangeShop)
* [updatePosition](#method-updatePosition)
* [cleanPositions](#method-cleanPositions)
* [getHigherPosition](#method-getHigherPosition)
* [getAvailableCarrierList](#method-getAvailableCarrierList)
* [assignGroupToAllCarriers](#method-assignGroupToAllCarriers)
* [setGroups](#method-setGroups)
* [getCarrierNameFromShopName](#method-getCarrierNameFromShopName)


Constants
----------


### <a name="constant-PS_CARRIERS_ONLY"></a>PS_CARRIERS_ONLY

    const PS_CARRIERS_ONLY = 1



* This constant is defined in [classes/Carrier.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L32)


### <a name="constant-CARRIERS_MODULE"></a>CARRIERS_MODULE

    const CARRIERS_MODULE = 2



* This constant is defined in [classes/Carrier.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L33)


### <a name="constant-CARRIERS_MODULE_NEED_RANGE"></a>CARRIERS_MODULE_NEED_RANGE

    const CARRIERS_MODULE_NEED_RANGE = 3



* This constant is defined in [classes/Carrier.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L34)


### <a name="constant-PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE"></a>PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE

    const PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE = 4



* This constant is defined in [classes/Carrier.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L35)


### <a name="constant-ALL_CARRIERS"></a>ALL_CARRIERS

    const ALL_CARRIERS = 5



* This constant is defined in [classes/Carrier.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L36)


### <a name="constant-SHIPPING_METHOD_DEFAULT"></a>SHIPPING_METHOD_DEFAULT

    const SHIPPING_METHOD_DEFAULT = 0



* This constant is defined in [classes/Carrier.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L38)


### <a name="constant-SHIPPING_METHOD_WEIGHT"></a>SHIPPING_METHOD_WEIGHT

    const SHIPPING_METHOD_WEIGHT = 1



* This constant is defined in [classes/Carrier.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L39)


### <a name="constant-SHIPPING_METHOD_PRICE"></a>SHIPPING_METHOD_PRICE

    const SHIPPING_METHOD_PRICE = 2



* This constant is defined in [classes/Carrier.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L40)


### <a name="constant-SHIPPING_METHOD_FREE"></a>SHIPPING_METHOD_FREE

    const SHIPPING_METHOD_FREE = 3



* This constant is defined in [classes/Carrier.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L41)


### <a name="constant-SHIPPING_PRICE_EXCEPTION"></a>SHIPPING_PRICE_EXCEPTION

    const SHIPPING_PRICE_EXCEPTION = 0



* This constant is defined in [classes/Carrier.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L43)


### <a name="constant-SHIPPING_WEIGHT_EXCEPTION"></a>SHIPPING_WEIGHT_EXCEPTION

    const SHIPPING_WEIGHT_EXCEPTION = 1



* This constant is defined in [classes/Carrier.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L44)


### <a name="constant-SHIPPING_SIZE_EXCEPTION"></a>SHIPPING_SIZE_EXCEPTION

    const SHIPPING_SIZE_EXCEPTION = 2



* This constant is defined in [classes/Carrier.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L45)


### <a name="constant-SORT_BY_PRICE"></a>SORT_BY_PRICE

    const SORT_BY_PRICE = 0



* This constant is defined in [classes/Carrier.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L47)


### <a name="constant-SORT_BY_POSITION"></a>SORT_BY_POSITION

    const SORT_BY_POSITION = 1



* This constant is defined in [classes/Carrier.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L48)


### <a name="constant-SORT_BY_ASC"></a>SORT_BY_ASC

    const SORT_BY_ASC = 0



* This constant is defined in [classes/Carrier.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L50)


### <a name="constant-SORT_BY_DESC"></a>SORT_BY_DESC

    const SORT_BY_DESC = 1



* This constant is defined in [classes/Carrier.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L51)


Properties
----------


### <a name="property-$id_reference"></a>$id_reference

    public integer $id_reference





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L54)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L57)


### <a name="property-$url"></a>$url

    public string $url





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L60)


### <a name="property-$delay"></a>$delay

    public string $delay





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L63)


### <a name="property-$active"></a>$active

    public boolean $active = true





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L66)


### <a name="property-$deleted"></a>$deleted

    public boolean $deleted





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L69)


### <a name="property-$shipping_handling"></a>$shipping_handling

    public boolean $shipping_handling = true





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L72)


### <a name="property-$range_behavior"></a>$range_behavior

    public integer $range_behavior





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L75)


### <a name="property-$is_module"></a>$is_module

    public boolean $is_module





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L78)


### <a name="property-$is_free"></a>$is_free

    public boolean $is_free = false





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L81)


### <a name="property-$shipping_method"></a>$shipping_method

    public integer $shipping_method





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L84)


### <a name="property-$shipping_external"></a>$shipping_external

    public boolean $shipping_external





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L87)


### <a name="property-$external_module_name"></a>$external_module_name

    public string $external_module_name = null





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L90)


### <a name="property-$need_range"></a>$need_range

    public boolean $need_range





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L93)


### <a name="property-$position"></a>$position

    public integer $position





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L96)


### <a name="property-$max_width"></a>$max_width

    public integer $max_width





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L99)


### <a name="property-$max_height"></a>$max_height

    public integer $max_height





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L102)


### <a name="property-$max_depth"></a>$max_depth

    public integer $max_depth





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L105)


### <a name="property-$max_weight"></a>$max_weight

    public integer $max_weight





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L108)


### <a name="property-$grade"></a>$grade

    public integer $grade





* Visibility: **public**
* This property is defined in [classes/Carrier.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L111)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'carrier', 'primary' => 'id_carrier', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_reference' => array('type' => self::TYPE_INT), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isCarrierName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'is_free' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'url' => array('type' => self::TYPE_STRING, 'validate' => 'isAbsoluteUrl'), 'shipping_handling' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shipping_external' => array('type' => self::TYPE_BOOL), 'range_behavior' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shipping_method' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_width' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_height' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_depth' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'grade' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 1), 'external_module_name' => array('type' => self::TYPE_STRING, 'size' => 64), 'is_module' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'need_range' => array('type' => self::TYPE_BOOL), 'position' => array('type' => self::TYPE_INT), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'delay' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Carrier.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L116)


### <a name="property-$price_by_weight"></a>$price_by_weight

    protected mixed $price_by_weight = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Carrier.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L148)


### <a name="property-$price_by_weight2"></a>$price_by_weight2

    protected mixed $price_by_weight2 = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Carrier.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L149)


### <a name="property-$price_by_price"></a>$price_by_price

    protected mixed $price_by_price = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Carrier.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L150)


### <a name="property-$price_by_price2"></a>$price_by_price2

    protected mixed $price_by_price2 = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Carrier.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L151)


### <a name="property-$cache_tax_rule"></a>$cache_tax_rule

    protected mixed $cache_tax_rule = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Carrier.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L153)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('deleted' => array(), 'is_module' => array(), 'id_tax_rules_group' => array('getter' => 'getIdTaxRulesGroup', 'setter' => 'setTaxRulesGroup', 'xlink_resource' => array('resourceName' => 'tax_rule_groups'))))





* Visibility: **protected**
* This property is defined in [classes/Carrier.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L155)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed CarrierCore::__construct($id, $id_lang)





* Visibility: **public**
* This method is defined in [classes/Carrier.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L169)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

    mixed CarrierCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Carrier.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L196)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-delete"></a>delete

    mixed CarrierCore::delete()





* Visibility: **public**
* This method is defined in [classes/Carrier.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L221)




### <a name="method-setConfiguration"></a>setConfiguration

    mixed CarrierCore::setConfiguration(integer $id_old)

Change carrier id in delivery prices when updating a carrier



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L236)


#### Arguments
* $id_old **integer** - &lt;p&gt;Old id carrier&lt;/p&gt;



### <a name="method-getDeliveryPriceByWeight"></a>getDeliveryPriceByWeight

    float CarrierCore::getDeliveryPriceByWeight(float $total_weight, integer $id_zone)

Get delivery prices for a given order



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 248](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L248)


#### Arguments
* $total_weight **float** - &lt;p&gt;Total order weight&lt;/p&gt;
* $id_zone **integer** - &lt;p&gt;Zone ID (for customer delivery address)&lt;/p&gt;



### <a name="method-checkDeliveryPriceByWeight"></a>checkDeliveryPriceByWeight

    mixed CarrierCore::checkDeliveryPriceByWeight($id_carrier, $total_weight, $id_zone)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L278)


#### Arguments
* $id_carrier **mixed**
* $total_weight **mixed**
* $id_zone **mixed**



### <a name="method-getMaxDeliveryPriceByWeight"></a>getMaxDeliveryPriceByWeight

    mixed CarrierCore::getMaxDeliveryPriceByWeight($id_zone)





* Visibility: **public**
* This method is defined in [classes/Carrier.php line 304](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L304)


#### Arguments
* $id_zone **mixed**



### <a name="method-getDeliveryPriceByPrice"></a>getDeliveryPriceByPrice

    float CarrierCore::getDeliveryPriceByPrice(float $order_total, integer $id_zone, integer|null $id_currency)

Get delivery prices for a given order



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L330)


#### Arguments
* $order_total **float** - &lt;p&gt;Order total to pay&lt;/p&gt;
* $id_zone **integer** - &lt;p&gt;Zone id (for customer delivery address)&lt;/p&gt;
* $id_currency **integer|null**



### <a name="method-checkDeliveryPriceByPrice"></a>checkDeliveryPriceByPrice

    float CarrierCore::checkDeliveryPriceByPrice(integer $id_carrier, float $order_total, integer $id_zone, integer|null $id_currency)

Check delivery prices for a given order



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 373](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L373)


#### Arguments
* $id_carrier **integer**
* $order_total **float** - &lt;p&gt;Order total to pay&lt;/p&gt;
* $id_zone **integer** - &lt;p&gt;Zone id (for customer delivery address)&lt;/p&gt;
* $id_currency **integer|null**



### <a name="method-getMaxDeliveryPriceByPrice"></a>getMaxDeliveryPriceByPrice

    mixed CarrierCore::getMaxDeliveryPriceByPrice($id_zone)





* Visibility: **public**
* This method is defined in [classes/Carrier.php line 403](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L403)


#### Arguments
* $id_zone **mixed**



### <a name="method-getDeliveryPriceByRanges"></a>getDeliveryPriceByRanges

    array CarrierCore::getDeliveryPriceByRanges($range_table, $id_carrier)

Get delivery prices for a given shipping method (price/weight)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 426](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L426)


#### Arguments
* $range_table **mixed**
* $id_carrier **mixed**



### <a name="method-getCarriers"></a>getCarriers

    array CarrierCore::getCarriers(integer $id_lang, boolean $active, $delete, $id_zone, $ids_group, $modules_filters)

Get all carriers in a given language



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 452](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L452)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $active **boolean** - &lt;p&gt;Returns only active carriers when true&lt;/p&gt;
* $delete **mixed**
* $id_zone **mixed**
* $ids_group **mixed**
* $modules_filters **mixed**



### <a name="method-getIdTaxRulesGroupMostUsed"></a>getIdTaxRulesGroupMostUsed

    mixed CarrierCore::getIdTaxRulesGroupMostUsed()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 511](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L511)




### <a name="method-getDeliveredCountries"></a>getDeliveredCountries

    mixed CarrierCore::getDeliveredCountries($id_lang, $active_countries, $active_carriers, $contain_states)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L527)


#### Arguments
* $id_lang **mixed**
* $active_countries **mixed**
* $active_carriers **mixed**
* $contain_states **mixed**



### <a name="method-getDefaultCarrierSelection"></a>getDefaultCarrierSelection

    \number CarrierCore::getDefaultCarrierSelection(array $carriers, $default_carrier)

Return the default carrier to use



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 573](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L573)


#### Arguments
* $carriers **array**
* $default_carrier **mixed**



### <a name="method-getCarriersForOrder"></a>getCarriersForOrder

    Array CarrierCore::getCarriersForOrder(integer $id_zone, Array $groups, $cart, $error)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 602](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L602)


#### Arguments
* $id_zone **integer**
* $groups **Array** - &lt;p&gt;group of the customer&lt;/p&gt;
* $cart **mixed**
* $error **mixed**



### <a name="method-checkCarrierZone"></a>checkCarrierZone

    mixed CarrierCore::checkCarrierZone($id_carrier, $id_zone)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 689](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L689)


#### Arguments
* $id_carrier **mixed**
* $id_zone **mixed**



### <a name="method-getZones"></a>getZones

    array CarrierCore::getZones()

Get all zones



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 713](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L713)




### <a name="method-getZone"></a>getZone

    array CarrierCore::getZone($id_zone)

Get a specific zones



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 727](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L727)


#### Arguments
* $id_zone **mixed**



### <a name="method-addZone"></a>addZone

    mixed CarrierCore::addZone($id_zone)

Add zone



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 739](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L739)


#### Arguments
* $id_zone **mixed**



### <a name="method-deleteZone"></a>deleteZone

    mixed CarrierCore::deleteZone($id_zone)

Delete zone



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 774](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L774)


#### Arguments
* $id_zone **mixed**



### <a name="method-getGroups"></a>getGroups

    array CarrierCore::getGroups()

Gets a specific group



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 795](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L795)




### <a name="method-deleteDeliveryPrice"></a>deleteDeliveryPrice

    boolean CarrierCore::deleteDeliveryPrice($range_table)

Clean delivery prices (weight/price)



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 809](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L809)


#### Arguments
* $range_table **mixed**



### <a name="method-addDeliveryPrice"></a>addDeliveryPrice

    boolean CarrierCore::addDeliveryPrice($price_list, $delete)

Add new delivery prices



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 830](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L830)


#### Arguments
* $price_list **mixed**
* $delete **mixed**



### <a name="method-copyCarrierData"></a>copyCarrierData

    mixed CarrierCore::copyCarrierData($old_id)

Copy old carrier informations when update carrier



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 887](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L887)


#### Arguments
* $old_id **mixed**



### <a name="method-getCarrierByReference"></a>getCarrierByReference

    mixed CarrierCore::getCarrierByReference($id_reference)

Get carrier using the reference id



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L977)


#### Arguments
* $id_reference **mixed**



### <a name="method-isUsed"></a>isUsed

    integer CarrierCore::isUsed()

Check if carrier is used (at least one order placed)



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 993](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L993)




### <a name="method-getShippingMethod"></a>getShippingMethod

    mixed CarrierCore::getShippingMethod()





* Visibility: **public**
* This method is defined in [classes/Carrier.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1003)




### <a name="method-getRangeTable"></a>getRangeTable

    mixed CarrierCore::getRangeTable()





* Visibility: **public**
* This method is defined in [classes/Carrier.php line 1023](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1023)




### <a name="method-getRangeObject"></a>getRangeObject

    mixed CarrierCore::getRangeObject($shipping_method)





* Visibility: **public**
* This method is defined in [classes/Carrier.php line 1034](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1034)


#### Arguments
* $shipping_method **mixed**



### <a name="method-getRangeSuffix"></a>getRangeSuffix

    mixed CarrierCore::getRangeSuffix($currency)





* Visibility: **public**
* This method is defined in [classes/Carrier.php line 1048](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1048)


#### Arguments
* $currency **mixed**



### <a name="method-getIdTaxRulesGroup"></a>getIdTaxRulesGroup

    mixed CarrierCore::getIdTaxRulesGroup(\Context $context)





* Visibility: **public**
* This method is defined in [classes/Carrier.php line 1060](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1060)


#### Arguments
* $context **[Context](ContextCore)**



### <a name="method-getIdTaxRulesGroupByIdCarrier"></a>getIdTaxRulesGroupByIdCarrier

    mixed CarrierCore::getIdTaxRulesGroupByIdCarrier($id_carrier, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 1065](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1065)


#### Arguments
* $id_carrier **mixed**
* $context **[Context](ContextCore)**



### <a name="method-deleteTaxRulesGroup"></a>deleteTaxRulesGroup

    mixed CarrierCore::deleteTaxRulesGroup(array $shops)





* Visibility: **public**
* This method is defined in [classes/Carrier.php line 1082](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1082)


#### Arguments
* $shops **array**



### <a name="method-setTaxRulesGroup"></a>setTaxRulesGroup

    mixed CarrierCore::setTaxRulesGroup($id_tax_rules_group, $all_shops)





* Visibility: **public**
* This method is defined in [classes/Carrier.php line 1095](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1095)


#### Arguments
* $id_tax_rules_group **mixed**
* $all_shops **mixed**



### <a name="method-getTaxesRate"></a>getTaxesRate

     CarrierCore::getTaxesRate(\Address $address)

Returns the taxes rate associated to the carrier



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 1128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1128)


#### Arguments
* $address **[Address](AddressCore)**



### <a name="method-getTaxCalculator"></a>getTaxCalculator

     CarrierCore::getTaxCalculator(\Address $address, $id_order, $use_average_tax_of_products)

Returns the taxes calculator associated to the carrier



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 1141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1141)


#### Arguments
* $address **[Address](AddressCore)**
* $id_order **mixed**
* $use_average_tax_of_products **mixed**



### <a name="method-sqlDeliveryRangeShop"></a>sqlDeliveryRangeShop

    string CarrierCore::sqlDeliveryRangeShop($range_table, $alias)

This tricky method generates a sql clause to check if ranged data are overloaded by multishop



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 1158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1158)


#### Arguments
* $range_table **mixed**
* $alias **mixed**



### <a name="method-updatePosition"></a>updatePosition

    boolean CarrierCore::updatePosition(boolean $way, integer $position)

Moves a carrier



* Visibility: **public**
* This method is defined in [classes/Carrier.php line 1190](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1190)


#### Arguments
* $way **boolean** - &lt;p&gt;Up (1) or Down (0)&lt;/p&gt;
* $position **integer**



### <a name="method-cleanPositions"></a>cleanPositions

    boolean CarrierCore::cleanPositions()

Reorders carrier positions.

Called after deleting a carrier.

* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 1234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1234)




### <a name="method-getHigherPosition"></a>getHigherPosition

    integer CarrierCore::getHigherPosition()

Gets the highest carrier position



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 1261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1261)




### <a name="method-getAvailableCarrierList"></a>getAvailableCarrierList

    array CarrierCore::getAvailableCarrierList(\Product $product, $id_warehouse, integer $id_address_delivery, integer $id_shop, \Cart $cart, $error)

For a given {product, warehouse}, gets the carrier available



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 1283](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1283)


#### Arguments
* $product **[Product](ProductCore)** - &lt;p&gt;The id of the product, or an array with at least the package size and weight&lt;/p&gt;
* $id_warehouse **mixed**
* $id_address_delivery **integer**
* $id_shop **integer**
* $cart **[Cart](CartCore)**
* $error **mixed**



### <a name="method-assignGroupToAllCarriers"></a>assignGroupToAllCarriers

    mixed CarrierCore::assignGroupToAllCarriers(integer|array $id_group_list, array $exception)

Assign one (ore more) group to all carriers



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 1420](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1420)


#### Arguments
* $id_group_list **integer|array** - &lt;p&gt;group id or list of group ids&lt;/p&gt;
* $exception **array** - &lt;p&gt;list of id carriers to ignore&lt;/p&gt;



### <a name="method-setGroups"></a>setGroups

    mixed CarrierCore::setGroups($groups, $delete)





* Visibility: **public**
* This method is defined in [classes/Carrier.php line 1451](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1451)


#### Arguments
* $groups **mixed**
* $delete **mixed**



### <a name="method-getCarrierNameFromShopName"></a>getCarrierNameFromShopName

    string CarrierCore::getCarrierNameFromShopName()

Return the carrier name from the shop name (e.g. if the carrier name is '0').

The returned carrier name is the shop name without '#' and ';' because this is not the same validation.

* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Carrier.php line 1474](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Carrier.php#L1474)



