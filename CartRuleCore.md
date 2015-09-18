CartRuleCore
===============






* Class name: CartRuleCore
* Namespace: 
* Parent class: ObjectModel



Constants
----------


### FILTER_ACTION_ALL

    const FILTER_ACTION_ALL = 1





### FILTER_ACTION_SHIPPING

    const FILTER_ACTION_SHIPPING = 2





### FILTER_ACTION_REDUCTION

    const FILTER_ACTION_REDUCTION = 3





### FILTER_ACTION_GIFT

    const FILTER_ACTION_GIFT = 4





### FILTER_ACTION_ALL_NOCAP

    const FILTER_ACTION_ALL_NOCAP = 5





### BO_ORDER_CODE_PREFIX

    const BO_ORDER_CODE_PREFIX = 'BO_ORDER_'





Properties
----------


### $only_one_gift

    protected mixed $only_one_gift = array()





* Visibility: **protected**
* This property is **static**.


### $id

    public mixed $id





* Visibility: **public**


### $name

    public mixed $name





* Visibility: **public**


### $id_customer

    public mixed $id_customer





* Visibility: **public**


### $date_from

    public mixed $date_from





* Visibility: **public**


### $date_to

    public mixed $date_to





* Visibility: **public**


### $description

    public mixed $description





* Visibility: **public**


### $quantity

    public mixed $quantity = 1





* Visibility: **public**


### $quantity_per_user

    public mixed $quantity_per_user = 1





* Visibility: **public**


### $priority

    public mixed $priority = 1





* Visibility: **public**


### $partial_use

    public mixed $partial_use = 1





* Visibility: **public**


### $code

    public mixed $code





* Visibility: **public**


### $minimum_amount

    public mixed $minimum_amount





* Visibility: **public**


### $minimum_amount_tax

    public mixed $minimum_amount_tax





* Visibility: **public**


### $minimum_amount_currency

    public mixed $minimum_amount_currency





* Visibility: **public**


### $minimum_amount_shipping

    public mixed $minimum_amount_shipping





* Visibility: **public**


### $country_restriction

    public mixed $country_restriction





* Visibility: **public**


### $carrier_restriction

    public mixed $carrier_restriction





* Visibility: **public**


### $group_restriction

    public mixed $group_restriction





* Visibility: **public**


### $cart_rule_restriction

    public mixed $cart_rule_restriction





* Visibility: **public**


### $product_restriction

    public mixed $product_restriction





* Visibility: **public**


### $shop_restriction

    public mixed $shop_restriction





* Visibility: **public**


### $free_shipping

    public mixed $free_shipping





* Visibility: **public**


### $reduction_percent

    public mixed $reduction_percent





* Visibility: **public**


### $reduction_amount

    public mixed $reduction_amount





* Visibility: **public**


### $reduction_tax

    public mixed $reduction_tax





* Visibility: **public**


### $reduction_currency

    public mixed $reduction_currency





* Visibility: **public**


### $reduction_product

    public mixed $reduction_product





* Visibility: **public**


### $gift_product

    public mixed $gift_product





* Visibility: **public**


### $gift_product_attribute

    public mixed $gift_product_attribute





* Visibility: **public**


### $highlight

    public mixed $highlight





* Visibility: **public**


### $active

    public mixed $active = 1





* Visibility: **public**


### $date_add

    public mixed $date_add





* Visibility: **public**


### $date_upd

    public mixed $date_upd





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'cart_rule', 'primary' => 'id_cart_rule', 'multilang' => true, 'fields' => array('id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'date_from' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'date_to' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'description' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 65534), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'quantity_per_user' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'priority' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'partial_use' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'code' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 254), 'minimum_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'minimum_amount_tax' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'minimum_amount_currency' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'minimum_amount_shipping' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'country_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'carrier_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'group_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cart_rule_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'product_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shop_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'free_shipping' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'reduction_percent' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPercentage'), 'reduction_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'reduction_tax' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'reduction_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'reduction_product' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'gift_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'gift_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'highlight' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 254)))





* Visibility: **public**
* This property is **static**.


Methods
-------


### add

    mixed CartRuleCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed CartRuleCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### delete

    mixed CartRuleCore::delete()





* Visibility: **public**




### copyConditions

    mixed CartRuleCore::copyConditions(integer $id_cart_rule_source, integer $id_cart_rule_destination)

Copy conditions from one cart rule to an other



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_cart_rule_source **integer**
* $id_cart_rule_destination **integer**



### getIdByCode

    integer|boolean CartRuleCore::getIdByCode(string $code)

Retrieves the id associated to the given code



* Visibility: **public**
* This method is **static**.


#### Arguments
* $code **string**



### getCustomerCartRules

    array CartRuleCore::getCustomerCartRules($id_lang, $id_customer, boolean $active, boolean $includeGeneric, boolean $inStock, \Cart|null $cart, boolean $free_shipping_only, boolean $highlight_only)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**
* $active **boolean**
* $includeGeneric **boolean**
* $inStock **boolean**
* $cart **Cart|null**
* $free_shipping_only **boolean**
* $highlight_only **boolean**



### usedByCustomer

    boolean CartRuleCore::usedByCustomer($id_customer)





* Visibility: **public**


#### Arguments
* $id_customer **mixed**



### cartRuleExists

    boolean CartRuleCore::cartRuleExists($name)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **mixed**



### deleteByIdCustomer

    boolean CartRuleCore::deleteByIdCustomer($id_customer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**



### getProductRuleGroups

    array CartRuleCore::getProductRuleGroups()





* Visibility: **public**




### getProductRules

    array CartRuleCore::getProductRules($id_product_rule_group)





* Visibility: **public**


#### Arguments
* $id_product_rule_group **mixed**



### checkValidity

    boolean|mixed|string CartRuleCore::checkValidity(\Context $context, boolean $alreadyInCart, boolean $display_error, $check_carrier)

Check if this cart rule can be applied



* Visibility: **public**


#### Arguments
* $context **Context**
* $alreadyInCart **boolean** - &lt;p&gt;Check if the voucher is already on the cart&lt;/p&gt;
* $display_error **boolean** - &lt;p&gt;Display error&lt;/p&gt;
* $check_carrier **mixed**



### checkProductRestrictions

    mixed CartRuleCore::checkProductRestrictions(\Context $context, $return_products, $display_error, $already_in_cart)





* Visibility: **protected**


#### Arguments
* $context **Context**
* $return_products **mixed**
* $display_error **mixed**
* $already_in_cart **mixed**



### array_uintersect

    mixed CartRuleCore::array_uintersect($array1, $array2)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $array1 **mixed**
* $array2 **mixed**



### array_uintersect_compare

    mixed CartRuleCore::array_uintersect_compare($a, $b)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $a **mixed**
* $b **mixed**



### getContextualValue

    float|integer|string CartRuleCore::getContextualValue(boolean $use_tax, \Context $context, $filter, $package, boolean $use_cache)

The reduction value is POSITIVE



* Visibility: **public**


#### Arguments
* $use_tax **boolean**
* $context **Context**
* $filter **mixed**
* $package **mixed**
* $use_cache **boolean** - &lt;p&gt;Allow using cache to avoid multiple free gift using multishipping&lt;/p&gt;



### cleanCache

    mixed CartRuleCore::cleanCache()

Make sure caches are empty
Must be called before calling multiple time getContextualValue()



* Visibility: **public**
* This method is **static**.




### getCartRuleCombinations

    array CartRuleCore::getCartRuleCombinations(integer $offset, integer $limit, string $search)





* Visibility: **protected**


#### Arguments
* $offset **integer**
* $limit **integer**
* $search **string**



### getAssociatedRestrictions

    array|boolean CartRuleCore::getAssociatedRestrictions(string $type, boolean $active_only, boolean $i18n, integer $offset, integer $limit, string $search_cart_rule_name)





* Visibility: **public**


#### Arguments
* $type **string**
* $active_only **boolean**
* $i18n **boolean**
* $offset **integer**
* $limit **integer**
* $search_cart_rule_name **string**



### autoRemoveFromCart

    mixed CartRuleCore::autoRemoveFromCart($context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $context **mixed**



### autoAddToCart

    mixed CartRuleCore::autoAddToCart(\Context|null $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $context **Context|null**



### isFeatureActive

    boolean CartRuleCore::isFeatureActive()





* Visibility: **public**
* This method is **static**.




### cleanProductRuleIntegrity

    mixed CartRuleCore::cleanProductRuleIntegrity($type, $list)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $type **mixed**
* $list **mixed**



### getCartsRuleByCode

    array CartRuleCore::getCartsRuleByCode($name, $id_lang, $extended)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **mixed**
* $id_lang **mixed**
* $extended **mixed**


