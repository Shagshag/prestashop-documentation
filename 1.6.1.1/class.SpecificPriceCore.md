Class SpecificPriceCore
=====================





* Class name: SpecificPriceCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/SpecificPrice.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L27)



Properties
----------

* [$_cache_priorities](#property-$_cache_priorities)
* [$_specificPriceCache](#property-$_specificPriceCache)
* [$definition](#property-$definition)
* [$from](#property-$from)
* [$from_quantity](#property-$from_quantity)
* [$id_cart](#property-$id_cart)
* [$id_country](#property-$id_country)
* [$id_currency](#property-$id_currency)
* [$id_customer](#property-$id_customer)
* [$id_group](#property-$id_group)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$id_specific_price_rule](#property-$id_specific_price_rule)
* [$price](#property-$price)
* [$reduction](#property-$reduction)
* [$reduction_tax](#property-$reduction_tax)
* [$reduction_type](#property-$reduction_type)
* [$to](#property-$to)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [_getScoreQuery](#method-_getScoreQuery)
* [add](#method-add)
* [delete](#method-delete)
* [deleteByIdCart](#method-deleteByIdCart)
* [deleteByProductId](#method-deleteByProductId)
* [deletePriorities](#method-deletePriorities)
* [duplicate](#method-duplicate)
* [exists](#method-exists)
* [getByProductId](#method-getByProductId)
* [getIdsByProductId](#method-getIdsByProductId)
* [getPriority](#method-getPriority)
* [getProductIdByDate](#method-getProductIdByDate)
* [getQuantityDiscount](#method-getQuantityDiscount)
* [getQuantityDiscounts](#method-getQuantityDiscounts)
* [getSpecificPrice](#method-getSpecificPrice)
* [isFeatureActive](#method-isFeatureActive)
* [setPriorities](#method-setPriorities)
* [setSpecificPriority](#method-setSpecificPriority)
* [update](#method-update)




Properties
----------


### <a name="property-$_cache_priorities"></a>$_cache_priorities

    protected mixed $_cache_priorities = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/SpecificPrice.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L92).


### <a name="property-$_specificPriceCache"></a>$_specificPriceCache

    protected mixed $_specificPriceCache = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/SpecificPrice.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L91).


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'specific_price', 'primary' => 'id_specific_price', 'fields' => array('id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_cart' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_specific_price_rule' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isNegativePrice', 'required' => true), 'from_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'reduction' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'reduction_tax' => array('type' => self::TYPE_INT, 'validate' => 'isBool', 'required' => true), 'reduction_type' => array('type' => self::TYPE_STRING, 'validate' => 'isReductionType', 'required' => true), 'from' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat', 'required' => true), 'to' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat', 'required' => true)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/SpecificPrice.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L50).


### <a name="property-$from"></a>$from

    public mixed $from





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L44).


### <a name="property-$from_quantity"></a>$from_quantity

    public mixed $from_quantity





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L40).


### <a name="property-$id_cart"></a>$id_cart

    public mixed $id_cart





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L31).


### <a name="property-$id_country"></a>$id_country

    public mixed $id_country





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L36).


### <a name="property-$id_currency"></a>$id_currency

    public mixed $id_currency





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L35).


### <a name="property-$id_customer"></a>$id_customer

    public mixed $id_customer





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L38).


### <a name="property-$id_group"></a>$id_group

    public mixed $id_group





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L37).


### <a name="property-$id_product"></a>$id_product

    public mixed $id_product





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L29).


### <a name="property-$id_product_attribute"></a>$id_product_attribute

    public mixed $id_product_attribute





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L32).


### <a name="property-$id_shop"></a>$id_shop

    public mixed $id_shop





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L33).


### <a name="property-$id_shop_group"></a>$id_shop_group

    public mixed $id_shop_group





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L34).


### <a name="property-$id_specific_price_rule"></a>$id_specific_price_rule

    public mixed $id_specific_price_rule





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L30).


### <a name="property-$price"></a>$price

    public mixed $price





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L39).


### <a name="property-$reduction"></a>$reduction

    public mixed $reduction





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L41).


### <a name="property-$reduction_tax"></a>$reduction_tax

    public mixed $reduction_tax = 1





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L42).


### <a name="property-$reduction_type"></a>$reduction_type

    public mixed $reduction_type





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L43).


### <a name="property-$to"></a>$to

    public mixed $to





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L45).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'specific_prices', 'objectNodeName' => 'specific_price', 'fields' => array('id_shop_group' => array('xlink_resource' => 'shop_groups'), 'id_shop' => array('xlink_resource' => 'shops', 'required' => true), 'id_cart' => array('xlink_resource' => 'carts', 'required' => true), 'id_product' => array('xlink_resource' => 'products', 'required' => true), 'id_product_attribute' => array('xlink_resource' => 'product_attributes'), 'id_currency' => array('xlink_resource' => 'currencies', 'required' => true), 'id_country' => array('xlink_resource' => 'countries', 'required' => true), 'id_group' => array('xlink_resource' => 'groups', 'required' => true), 'id_customer' => array('xlink_resource' => 'customers', 'required' => true)))





* Visibility: **protected**
* Source: [classes/SpecificPrice.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L74).


Methods
-------


### <a name="method-_getScoreQuery"></a>_getScoreQuery

    mixed SpecificPriceCore::_getScoreQuery($id_product, $id_shop, $id_currency, $id_country, $id_group, $id_customer)

score generation for quantity discount



* Visibility: **protected**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L162)


#### Arguments
* $id_product **mixed**
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $id_customer **mixed**



### <a name="method-add"></a>add

    mixed SpecificPriceCore::add($autodate, $nullValues)





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L94)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-delete"></a>delete

    mixed SpecificPriceCore::delete()





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L118)




### <a name="method-deleteByIdCart"></a>deleteByIdCart

    mixed SpecificPriceCore::deleteByIdCart($id_cart, $id_product, $id_product_attribute)





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L141)


#### Arguments
* $id_cart **mixed**
* $id_product **mixed**
* $id_product_attribute **mixed**



### <a name="method-deleteByProductId"></a>deleteByProductId

    mixed SpecificPriceCore::deleteByProductId($id_product)





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L384)


#### Arguments
* $id_product **mixed**



### <a name="method-deletePriorities"></a>deletePriorities

    mixed SpecificPriceCore::deletePriorities()





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L255)




### <a name="method-duplicate"></a>duplicate

    mixed SpecificPriceCore::duplicate($id_product)





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 394](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L394)


#### Arguments
* $id_product **mixed**



### <a name="method-exists"></a>exists

    mixed SpecificPriceCore::exists($id_product, $id_product_attribute, $id_shop, $id_group, $id_country, $id_currency, $id_customer, $from_quantity, $from, $to, $rule)





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 418](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L418)


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



### <a name="method-getByProductId"></a>getByProductId

    mixed SpecificPriceCore::getByProductId($id_product, $id_product_attribute, $id_cart)





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L131)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_cart **mixed**



### <a name="method-getIdsByProductId"></a>getIdsByProductId

    mixed SpecificPriceCore::getIdsByProductId($id_product, $id_product_attribute, $id_cart)





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L149)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_cart **mixed**



### <a name="method-getPriority"></a>getPriority

    mixed SpecificPriceCore::getPriority($id_product)





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L176)


#### Arguments
* $id_product **mixed**



### <a name="method-getProductIdByDate"></a>getProductIdByDate

    mixed SpecificPriceCore::getProductIdByDate($id_shop, $id_currency, $id_country, $id_group, $beginning, $ending, $id_customer, $with_combination_id)





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 353](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L353)


#### Arguments
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $beginning **mixed**
* $ending **mixed**
* $id_customer **mixed**
* $with_combination_id **mixed**



### <a name="method-getQuantityDiscount"></a>getQuantityDiscount

    mixed SpecificPriceCore::getQuantityDiscount($id_product, $id_shop, $id_currency, $id_country, $id_group, $quantity, $id_product_attribute, $id_customer)





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L323)


#### Arguments
* $id_product **mixed**
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $quantity **mixed**
* $id_product_attribute **mixed**
* $id_customer **mixed**



### <a name="method-getQuantityDiscounts"></a>getQuantityDiscounts

    mixed SpecificPriceCore::getQuantityDiscounts($id_product, $id_shop, $id_currency, $id_country, $id_group, $id_product_attribute, $all_combinations, $id_customer)





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 276](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L276)


#### Arguments
* $id_product **mixed**
* $id_shop **mixed**
* $id_currency **mixed**
* $id_country **mixed**
* $id_group **mixed**
* $id_product_attribute **mixed**
* $all_combinations **mixed**
* $id_customer **mixed**



### <a name="method-getSpecificPrice"></a>getSpecificPrice

    mixed SpecificPriceCore::getSpecificPrice($id_product, $id_shop, $id_currency, $id_country, $id_group, $quantity, $id_product_attribute, $id_customer, $id_cart, $real_quantity)





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L201)


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



### <a name="method-isFeatureActive"></a>isFeatureActive

    boolean SpecificPriceCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L408)




### <a name="method-setPriorities"></a>setPriorities

    mixed SpecificPriceCore::setPriorities($priorities)





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L241)


#### Arguments
* $priorities **mixed**



### <a name="method-setSpecificPriority"></a>setSpecificPriority

    mixed SpecificPriceCore::setSpecificPriority($id_product, $priorities)





* Visibility: **public**
* This method is **static**.
* Source: [classes/SpecificPrice.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L262)


#### Arguments
* $id_product **mixed**
* $priorities **mixed**



### <a name="method-update"></a>update

    mixed SpecificPriceCore::update($null_values)





* Visibility: **public**
* Source: [classes/SpecificPrice.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/SpecificPrice.php#L107)


#### Arguments
* $null_values **mixed**


