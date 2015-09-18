CarrierCore
===============






* Class name: CarrierCore
* Namespace: 
* Parent class: ObjectModel



Constants
----------


### PS_CARRIERS_ONLY

    const PS_CARRIERS_ONLY = 1





### CARRIERS_MODULE

    const CARRIERS_MODULE = 2





### CARRIERS_MODULE_NEED_RANGE

    const CARRIERS_MODULE_NEED_RANGE = 3





### PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE

    const PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE = 4





### ALL_CARRIERS

    const ALL_CARRIERS = 5





### SHIPPING_METHOD_DEFAULT

    const SHIPPING_METHOD_DEFAULT = 0





### SHIPPING_METHOD_WEIGHT

    const SHIPPING_METHOD_WEIGHT = 1





### SHIPPING_METHOD_PRICE

    const SHIPPING_METHOD_PRICE = 2





### SHIPPING_METHOD_FREE

    const SHIPPING_METHOD_FREE = 3





### SHIPPING_PRICE_EXCEPTION

    const SHIPPING_PRICE_EXCEPTION = 0





### SHIPPING_WEIGHT_EXCEPTION

    const SHIPPING_WEIGHT_EXCEPTION = 1





### SHIPPING_SIZE_EXCEPTION

    const SHIPPING_SIZE_EXCEPTION = 2





### SORT_BY_PRICE

    const SORT_BY_PRICE = 0





### SORT_BY_POSITION

    const SORT_BY_POSITION = 1





### SORT_BY_ASC

    const SORT_BY_ASC = 0





### SORT_BY_DESC

    const SORT_BY_DESC = 1





Properties
----------


### $id_reference

    public integer $id_reference





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $url

    public string $url





* Visibility: **public**


### $delay

    public string $delay





* Visibility: **public**


### $active

    public boolean $active = true





* Visibility: **public**


### $deleted

    public boolean $deleted





* Visibility: **public**


### $shipping_handling

    public boolean $shipping_handling = true





* Visibility: **public**


### $range_behavior

    public integer $range_behavior





* Visibility: **public**


### $is_module

    public boolean $is_module





* Visibility: **public**


### $is_free

    public boolean $is_free = false





* Visibility: **public**


### $shipping_method

    public integer $shipping_method





* Visibility: **public**


### $shipping_external

    public boolean $shipping_external





* Visibility: **public**


### $external_module_name

    public string $external_module_name = null





* Visibility: **public**


### $need_range

    public boolean $need_range





* Visibility: **public**


### $position

    public integer $position





* Visibility: **public**


### $max_width

    public integer $max_width





* Visibility: **public**


### $max_height

    public integer $max_height





* Visibility: **public**


### $max_depth

    public integer $max_depth





* Visibility: **public**


### $max_weight

    public integer $max_weight





* Visibility: **public**


### $grade

    public integer $grade





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'carrier', 'primary' => 'id_carrier', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_reference' => array('type' => self::TYPE_INT), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isCarrierName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'is_free' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'url' => array('type' => self::TYPE_STRING, 'validate' => 'isAbsoluteUrl'), 'shipping_handling' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shipping_external' => array('type' => self::TYPE_BOOL), 'range_behavior' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shipping_method' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_width' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_height' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_depth' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'grade' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 1), 'external_module_name' => array('type' => self::TYPE_STRING, 'size' => 64), 'is_module' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'need_range' => array('type' => self::TYPE_BOOL), 'position' => array('type' => self::TYPE_INT), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'delay' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))





* Visibility: **public**
* This property is **static**.


### $price_by_weight

    protected mixed $price_by_weight = array()





* Visibility: **protected**
* This property is **static**.


### $price_by_weight2

    protected mixed $price_by_weight2 = array()





* Visibility: **protected**
* This property is **static**.


### $price_by_price

    protected mixed $price_by_price = array()





* Visibility: **protected**
* This property is **static**.


### $price_by_price2

    protected mixed $price_by_price2 = array()





* Visibility: **protected**
* This property is **static**.


### $cache_tax_rule

    protected mixed $cache_tax_rule = array()





* Visibility: **protected**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('deleted' => array(), 'is_module' => array(), 'id_tax_rules_group' => array('getter' => 'getIdTaxRulesGroup', 'setter' => 'setTaxRulesGroup', 'xlink_resource' => array('resourceName' => 'tax_rule_groups'))))





* Visibility: **protected**


Methods
-------


### __construct

    mixed CarrierCore::__construct($id, $id_lang)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### add

    mixed CarrierCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### delete

    mixed CarrierCore::delete()





* Visibility: **public**




### setConfiguration

    mixed CarrierCore::setConfiguration(integer $id_old)

Change carrier id in delivery prices when updating a carrier



* Visibility: **public**


#### Arguments
* $id_old **integer** - &lt;p&gt;Old id carrier&lt;/p&gt;



### getDeliveryPriceByWeight

    float CarrierCore::getDeliveryPriceByWeight(float $total_weight, integer $id_zone)

Get delivery prices for a given order



* Visibility: **public**


#### Arguments
* $total_weight **float** - &lt;p&gt;Total order weight&lt;/p&gt;
* $id_zone **integer** - &lt;p&gt;Zone ID (for customer delivery address)&lt;/p&gt;



### checkDeliveryPriceByWeight

    mixed CarrierCore::checkDeliveryPriceByWeight($id_carrier, $total_weight, $id_zone)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_carrier **mixed**
* $total_weight **mixed**
* $id_zone **mixed**



### getMaxDeliveryPriceByWeight

    mixed CarrierCore::getMaxDeliveryPriceByWeight($id_zone)





* Visibility: **public**


#### Arguments
* $id_zone **mixed**



### getDeliveryPriceByPrice

    float CarrierCore::getDeliveryPriceByPrice(float $order_total, integer $id_zone, integer|null $id_currency)

Get delivery prices for a given order



* Visibility: **public**


#### Arguments
* $order_total **float** - &lt;p&gt;Order total to pay&lt;/p&gt;
* $id_zone **integer** - &lt;p&gt;Zone id (for customer delivery address)&lt;/p&gt;
* $id_currency **integer|null**



### checkDeliveryPriceByPrice

    float CarrierCore::checkDeliveryPriceByPrice(integer $id_carrier, float $order_total, integer $id_zone, integer|null $id_currency)

Check delivery prices for a given order



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_carrier **integer**
* $order_total **float** - &lt;p&gt;Order total to pay&lt;/p&gt;
* $id_zone **integer** - &lt;p&gt;Zone id (for customer delivery address)&lt;/p&gt;
* $id_currency **integer|null**



### getMaxDeliveryPriceByPrice

    mixed CarrierCore::getMaxDeliveryPriceByPrice($id_zone)





* Visibility: **public**


#### Arguments
* $id_zone **mixed**



### getDeliveryPriceByRanges

    array CarrierCore::getDeliveryPriceByRanges($range_table, $id_carrier)

Get delivery prices for a given shipping method (price/weight)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $range_table **mixed**
* $id_carrier **mixed**



### getCarriers

    array CarrierCore::getCarriers(integer $id_lang, boolean $active, $delete, $id_zone, $ids_group, $modules_filters)

Get all carriers in a given language



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $active **boolean** - &lt;p&gt;Returns only active carriers when true&lt;/p&gt;
* $delete **mixed**
* $id_zone **mixed**
* $ids_group **mixed**
* $modules_filters **mixed**



### getIdTaxRulesGroupMostUsed

    mixed CarrierCore::getIdTaxRulesGroupMostUsed()





* Visibility: **public**
* This method is **static**.




### getDeliveredCountries

    mixed CarrierCore::getDeliveredCountries($id_lang, $active_countries, $active_carriers, $contain_states)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $active_countries **mixed**
* $active_carriers **mixed**
* $contain_states **mixed**



### getDefaultCarrierSelection

    \number CarrierCore::getDefaultCarrierSelection(array $carriers, $default_carrier)

Return the default carrier to use



* Visibility: **public**
* This method is **static**.


#### Arguments
* $carriers **array**
* $default_carrier **mixed**



### getCarriersForOrder

    Array CarrierCore::getCarriersForOrder(integer $id_zone, Array $groups, $cart, $error)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_zone **integer**
* $groups **Array** - &lt;p&gt;group of the customer&lt;/p&gt;
* $cart **mixed**
* $error **mixed**



### checkCarrierZone

    mixed CarrierCore::checkCarrierZone($id_carrier, $id_zone)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_carrier **mixed**
* $id_zone **mixed**



### getZones

    array CarrierCore::getZones()

Get all zones



* Visibility: **public**




### getZone

    array CarrierCore::getZone($id_zone)

Get a specific zones



* Visibility: **public**


#### Arguments
* $id_zone **mixed**



### addZone

    mixed CarrierCore::addZone($id_zone)

Add zone



* Visibility: **public**


#### Arguments
* $id_zone **mixed**



### deleteZone

    mixed CarrierCore::deleteZone($id_zone)

Delete zone



* Visibility: **public**


#### Arguments
* $id_zone **mixed**



### getGroups

    array CarrierCore::getGroups()

Gets a specific group



* Visibility: **public**




### deleteDeliveryPrice

    boolean CarrierCore::deleteDeliveryPrice($range_table)

Clean delivery prices (weight/price)



* Visibility: **public**


#### Arguments
* $range_table **mixed**



### addDeliveryPrice

    boolean CarrierCore::addDeliveryPrice($price_list, $delete)

Add new delivery prices



* Visibility: **public**


#### Arguments
* $price_list **mixed**
* $delete **mixed**



### copyCarrierData

    mixed CarrierCore::copyCarrierData($old_id)

Copy old carrier informations when update carrier



* Visibility: **public**


#### Arguments
* $old_id **mixed**



### getCarrierByReference

    mixed CarrierCore::getCarrierByReference($id_reference)

Get carrier using the reference id



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_reference **mixed**



### isUsed

    integer CarrierCore::isUsed()

Check if carrier is used (at least one order placed)



* Visibility: **public**




### getShippingMethod

    mixed CarrierCore::getShippingMethod()





* Visibility: **public**




### getRangeTable

    mixed CarrierCore::getRangeTable()





* Visibility: **public**




### getRangeObject

    mixed CarrierCore::getRangeObject($shipping_method)





* Visibility: **public**


#### Arguments
* $shipping_method **mixed**



### getRangeSuffix

    mixed CarrierCore::getRangeSuffix($currency)





* Visibility: **public**


#### Arguments
* $currency **mixed**



### getIdTaxRulesGroup

    mixed CarrierCore::getIdTaxRulesGroup(\Context $context)





* Visibility: **public**


#### Arguments
* $context **Context**



### getIdTaxRulesGroupByIdCarrier

    mixed CarrierCore::getIdTaxRulesGroupByIdCarrier($id_carrier, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_carrier **mixed**
* $context **Context**



### deleteTaxRulesGroup

    mixed CarrierCore::deleteTaxRulesGroup(array $shops)





* Visibility: **public**


#### Arguments
* $shops **array**



### setTaxRulesGroup

    mixed CarrierCore::setTaxRulesGroup($id_tax_rules_group, $all_shops)





* Visibility: **public**


#### Arguments
* $id_tax_rules_group **mixed**
* $all_shops **mixed**



### getTaxesRate

     CarrierCore::getTaxesRate(\Address $address)

Returns the taxes rate associated to the carrier



* Visibility: **public**


#### Arguments
* $address **Address**



### getTaxCalculator

     CarrierCore::getTaxCalculator(\Address $address, $id_order, $use_average_tax_of_products)

Returns the taxes calculator associated to the carrier



* Visibility: **public**


#### Arguments
* $address **Address**
* $id_order **mixed**
* $use_average_tax_of_products **mixed**



### sqlDeliveryRangeShop

    string CarrierCore::sqlDeliveryRangeShop($range_table, $alias)

This tricky method generates a sql clause to check if ranged data are overloaded by multishop



* Visibility: **public**
* This method is **static**.


#### Arguments
* $range_table **mixed**
* $alias **mixed**



### updatePosition

    boolean CarrierCore::updatePosition(boolean $way, integer $position)

Moves a carrier



* Visibility: **public**


#### Arguments
* $way **boolean** - &lt;p&gt;Up (1) or Down (0)&lt;/p&gt;
* $position **integer**



### cleanPositions

    boolean CarrierCore::cleanPositions()

Reorders carrier positions.

Called after deleting a carrier.

* Visibility: **public**
* This method is **static**.




### getHigherPosition

    integer CarrierCore::getHigherPosition()

Gets the highest carrier position



* Visibility: **public**
* This method is **static**.




### getAvailableCarrierList

    array CarrierCore::getAvailableCarrierList(\Product $product, $id_warehouse, integer $id_address_delivery, integer $id_shop, \Cart $cart, $error)

For a given {product, warehouse}, gets the carrier available



* Visibility: **public**
* This method is **static**.


#### Arguments
* $product **Product** - &lt;p&gt;The id of the product, or an array with at least the package size and weight&lt;/p&gt;
* $id_warehouse **mixed**
* $id_address_delivery **integer**
* $id_shop **integer**
* $cart **Cart**
* $error **mixed**



### assignGroupToAllCarriers

    mixed CarrierCore::assignGroupToAllCarriers(integer|array $id_group_list, array $exception)

Assign one (ore more) group to all carriers



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_group_list **integer|array** - &lt;p&gt;group id or list of group ids&lt;/p&gt;
* $exception **array** - &lt;p&gt;list of id carriers to ignore&lt;/p&gt;



### setGroups

    mixed CarrierCore::setGroups($groups, $delete)





* Visibility: **public**


#### Arguments
* $groups **mixed**
* $delete **mixed**



### getCarrierNameFromShopName

    string CarrierCore::getCarrierNameFromShopName()

Return the carrier name from the shop name (e.g. if the carrier name is '0').

The returned carrier name is the shop name without '#' and ';' because this is not the same validation.

* Visibility: **public**
* This method is **static**.



