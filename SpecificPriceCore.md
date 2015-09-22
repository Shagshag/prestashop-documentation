SpecificPriceCore
===============






* Class name: SpecificPriceCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/SpecificPrice.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L27)





Properties
----------


### $id_product

    public mixed $id_product





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#29)


### $id_specific_price_rule

    public mixed $id_specific_price_rule





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#30)


### $id_cart

    public mixed $id_cart





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#31)


### $id_product_attribute

    public mixed $id_product_attribute





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#32)


### $id_shop

    public mixed $id_shop





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#33)


### $id_shop_group

    public mixed $id_shop_group





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#34)


### $id_currency

    public mixed $id_currency





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#35)


### $id_country

    public mixed $id_country





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#36)


### $id_group

    public mixed $id_group





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#37)


### $id_customer

    public mixed $id_customer





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#38)


### $price

    public mixed $price





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#39)


### $from_quantity

    public mixed $from_quantity





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#40)


### $reduction

    public mixed $reduction





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#41)


### $reduction_tax

    public mixed $reduction_tax = 1





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#42)


### $reduction_type

    public mixed $reduction_type





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#43)


### $from

    public mixed $from





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#44)


### $to

    public mixed $to





* Visibility: **public**
* This property is defined in [classes/SpecificPrice.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#45)


### $definition

    public mixed $definition = array('table' => 'specific_price', 'primary' => 'id_specific_price', 'fields' => array('id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_cart' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_specific_price_rule' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isNegativePrice', 'required' => true), 'from_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'reduction' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'reduction_tax' => array('type' => self::TYPE_INT, 'validate' => 'isBool', 'required' => true), 'reduction_type' => array('type' => self::TYPE_STRING, 'validate' => 'isReductionType', 'required' => true), 'from' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat', 'required' => true), 'to' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/SpecificPrice.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#50)


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'specific_prices', 'objectNodeName' => 'specific_price', 'fields' => array('id_shop_group' => array('xlink_resource' => 'shop_groups'), 'id_shop' => array('xlink_resource' => 'shops', 'required' => true), 'id_cart' => array('xlink_resource' => 'carts', 'required' => true), 'id_product' => array('xlink_resource' => 'products', 'required' => true), 'id_product_attribute' => array('xlink_resource' => 'product_attributes'), 'id_currency' => array('xlink_resource' => 'currencies', 'required' => true), 'id_country' => array('xlink_resource' => 'countries', 'required' => true), 'id_group' => array('xlink_resource' => 'groups', 'required' => true), 'id_customer' => array('xlink_resource' => 'customers', 'required' => true)))





* Visibility: **protected**
* This property is defined in [classes/SpecificPrice.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#74)


### $_specificPriceCache

    protected mixed $_specificPriceCache = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/SpecificPrice.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#91)


### $_cache_priorities

    protected mixed $_cache_priorities = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/SpecificPrice.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#92)


Methods
-------


### add

    mixed SpecificPriceCore::add($autodate, $nullValues)





* Visibility: **public**
* This method is defined in [classes/SpecificPrice.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#94)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### update

    mixed SpecificPriceCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/SpecificPrice.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#107)


#### Arguments
* $null_values **mixed**



### delete

    mixed SpecificPriceCore::delete()





* Visibility: **public**
* This method is defined in [classes/SpecificPrice.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#118)




### getByProductId

    mixed SpecificPriceCore::getByProductId($id_product, $id_product_attribute, $id_cart)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#131)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_cart **mixed**



### deleteByIdCart

    mixed SpecificPriceCore::deleteByIdCart($id_cart, $id_product, $id_product_attribute)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#141)


#### Arguments
* $id_cart **mixed**
* $id_product **mixed**
* $id_product_attribute **mixed**



### getIdsByProductId

    mixed SpecificPriceCore::getIdsByProductId($id_product, $id_product_attribute, $id_cart)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#149)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_cart **mixed**



### _getScoreQuery

    mixed SpecificPriceCore::_getScoreQuery($id_product, $id_shop, $id_currency, $id_country, $id_group, $id_customer)

score generation for quantity discount



* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#162)


#### Arguments
* $id_product **mixed**
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $id_customer **mixed**



### getPriority

    mixed SpecificPriceCore::getPriority($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#176)


#### Arguments
* $id_product **mixed**



### getSpecificPrice

    mixed SpecificPriceCore::getSpecificPrice($id_product, $id_shop, $id_currency, $id_country, $id_group, $quantity, $id_product_attribute, $id_customer, $id_cart, $real_quantity)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#201)


#### Arguments
* $id_product **mixed**
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $quantity **mixed**
* $id_product_attribute **mixed**
* $id_customer **mixed**
* $id_cart **mixed**
* $real_quantity **mixed**



### setPriorities

    mixed SpecificPriceCore::setPriorities($priorities)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#241)


#### Arguments
* $priorities **mixed**



### deletePriorities

    mixed SpecificPriceCore::deletePriorities()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#255)




### setSpecificPriority

    mixed SpecificPriceCore::setSpecificPriority($id_product, $priorities)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#262)


#### Arguments
* $id_product **mixed**
* $priorities **mixed**



### getQuantityDiscounts

    mixed SpecificPriceCore::getQuantityDiscounts($id_product, $id_shop, $id_currency, $id_country, $id_group, $id_product_attribute, $all_combinations, $id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#276)


#### Arguments
* $id_product **mixed**
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $id_product_attribute **mixed**
* $all_combinations **mixed**
* $id_customer **mixed**



### getQuantityDiscount

    mixed SpecificPriceCore::getQuantityDiscount($id_product, $id_shop, $id_currency, $id_country, $id_group, $quantity, $id_product_attribute, $id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#323)


#### Arguments
* $id_product **mixed**
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $quantity **mixed**
* $id_product_attribute **mixed**
* $id_customer **mixed**



### getProductIdByDate

    mixed SpecificPriceCore::getProductIdByDate($id_shop, $id_currency, $id_country, $id_group, $beginning, $ending, $id_customer, $with_combination_id)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 353](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#353)


#### Arguments
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $beginning **mixed**
* $ending **mixed**
* $id_customer **mixed**
* $with_combination_id **mixed**



### deleteByProductId

    mixed SpecificPriceCore::deleteByProductId($id_product)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#384)


#### Arguments
* $id_product **mixed**



### duplicate

    mixed SpecificPriceCore::duplicate($id_product)





* Visibility: **public**
* This method is defined in [classes/SpecificPrice.php line 394](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#394)


#### Arguments
* $id_product **mixed**



### isFeatureActive

    boolean SpecificPriceCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#408)




### exists

    mixed SpecificPriceCore::exists($id_product, $id_product_attribute, $id_shop, $id_group, $id_country, $id_currency, $id_customer, $from_quantity, $from, $to, $rule)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/SpecificPrice.php line 418](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#418)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_shop **mixed**
* $id_group **mixed**
* $id_country **mixed**
* $id_currency **mixed**
* $id_customer **mixed**
* $from_quantity **mixed**
* $from **mixed**
* $to **mixed**
* $rule **mixed**


