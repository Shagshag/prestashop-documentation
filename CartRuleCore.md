CartRuleCore
===============






* Class name: CartRuleCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\CartRule.php line 27



Constants
----------


### FILTER_ACTION_ALL

    const FILTER_ACTION_ALL = 1



* This constant is defined in classes\CartRule.php line 30


### FILTER_ACTION_SHIPPING

    const FILTER_ACTION_SHIPPING = 2



* This constant is defined in classes\CartRule.php line 31


### FILTER_ACTION_REDUCTION

    const FILTER_ACTION_REDUCTION = 3



* This constant is defined in classes\CartRule.php line 32


### FILTER_ACTION_GIFT

    const FILTER_ACTION_GIFT = 4



* This constant is defined in classes\CartRule.php line 33


### FILTER_ACTION_ALL_NOCAP

    const FILTER_ACTION_ALL_NOCAP = 5



* This constant is defined in classes\CartRule.php line 34


### BO_ORDER_CODE_PREFIX

    const BO_ORDER_CODE_PREFIX = 'BO_ORDER_'



* This constant is defined in classes\CartRule.php line 36


Properties
----------


### $only_one_gift

    protected mixed $only_one_gift = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\CartRule.php line 39


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in classes\CartRule.php line 41


### $name

    public mixed $name





* Visibility: **public**
* This property is defined in classes\CartRule.php line 42


### $id_customer

    public mixed $id_customer





* Visibility: **public**
* This property is defined in classes\CartRule.php line 43


### $date_from

    public mixed $date_from





* Visibility: **public**
* This property is defined in classes\CartRule.php line 44


### $date_to

    public mixed $date_to





* Visibility: **public**
* This property is defined in classes\CartRule.php line 45


### $description

    public mixed $description





* Visibility: **public**
* This property is defined in classes\CartRule.php line 46


### $quantity

    public mixed $quantity = 1





* Visibility: **public**
* This property is defined in classes\CartRule.php line 47


### $quantity_per_user

    public mixed $quantity_per_user = 1





* Visibility: **public**
* This property is defined in classes\CartRule.php line 48


### $priority

    public mixed $priority = 1





* Visibility: **public**
* This property is defined in classes\CartRule.php line 49


### $partial_use

    public mixed $partial_use = 1





* Visibility: **public**
* This property is defined in classes\CartRule.php line 50


### $code

    public mixed $code





* Visibility: **public**
* This property is defined in classes\CartRule.php line 51


### $minimum_amount

    public mixed $minimum_amount





* Visibility: **public**
* This property is defined in classes\CartRule.php line 52


### $minimum_amount_tax

    public mixed $minimum_amount_tax





* Visibility: **public**
* This property is defined in classes\CartRule.php line 53


### $minimum_amount_currency

    public mixed $minimum_amount_currency





* Visibility: **public**
* This property is defined in classes\CartRule.php line 54


### $minimum_amount_shipping

    public mixed $minimum_amount_shipping





* Visibility: **public**
* This property is defined in classes\CartRule.php line 55


### $country_restriction

    public mixed $country_restriction





* Visibility: **public**
* This property is defined in classes\CartRule.php line 56


### $carrier_restriction

    public mixed $carrier_restriction





* Visibility: **public**
* This property is defined in classes\CartRule.php line 57


### $group_restriction

    public mixed $group_restriction





* Visibility: **public**
* This property is defined in classes\CartRule.php line 58


### $cart_rule_restriction

    public mixed $cart_rule_restriction





* Visibility: **public**
* This property is defined in classes\CartRule.php line 59


### $product_restriction

    public mixed $product_restriction





* Visibility: **public**
* This property is defined in classes\CartRule.php line 60


### $shop_restriction

    public mixed $shop_restriction





* Visibility: **public**
* This property is defined in classes\CartRule.php line 61


### $free_shipping

    public mixed $free_shipping





* Visibility: **public**
* This property is defined in classes\CartRule.php line 62


### $reduction_percent

    public mixed $reduction_percent





* Visibility: **public**
* This property is defined in classes\CartRule.php line 63


### $reduction_amount

    public mixed $reduction_amount





* Visibility: **public**
* This property is defined in classes\CartRule.php line 64


### $reduction_tax

    public mixed $reduction_tax





* Visibility: **public**
* This property is defined in classes\CartRule.php line 65


### $reduction_currency

    public mixed $reduction_currency





* Visibility: **public**
* This property is defined in classes\CartRule.php line 66


### $reduction_product

    public mixed $reduction_product





* Visibility: **public**
* This property is defined in classes\CartRule.php line 67


### $gift_product

    public mixed $gift_product





* Visibility: **public**
* This property is defined in classes\CartRule.php line 68


### $gift_product_attribute

    public mixed $gift_product_attribute





* Visibility: **public**
* This property is defined in classes\CartRule.php line 69


### $highlight

    public mixed $highlight





* Visibility: **public**
* This property is defined in classes\CartRule.php line 70


### $active

    public mixed $active = 1





* Visibility: **public**
* This property is defined in classes\CartRule.php line 71


### $date_add

    public mixed $date_add





* Visibility: **public**
* This property is defined in classes\CartRule.php line 72


### $date_upd

    public mixed $date_upd





* Visibility: **public**
* This property is defined in classes\CartRule.php line 73


### $definition

    public mixed $definition = array('table' => 'cart_rule', 'primary' => 'id_cart_rule', 'multilang' => true, 'fields' => array('id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'date_from' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'date_to' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'description' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 65534), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'quantity_per_user' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'priority' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'partial_use' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'code' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 254), 'minimum_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'minimum_amount_tax' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'minimum_amount_currency' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'minimum_amount_shipping' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'country_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'carrier_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'group_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cart_rule_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'product_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shop_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'free_shipping' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'reduction_percent' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPercentage'), 'reduction_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'reduction_tax' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'reduction_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'reduction_product' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'gift_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'gift_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'highlight' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 254)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\CartRule.php line 78


Methods
-------


### add

    mixed CartRuleCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in classes\CartRule.php line 123


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed CartRuleCore::update($null_values)





* Visibility: **public**
* This method is defined in classes\CartRule.php line 137


#### Arguments
* $null_values **mixed**



### delete

    mixed CartRuleCore::delete()





* Visibility: **public**
* This method is defined in classes\CartRule.php line 151




### copyConditions

    mixed CartRuleCore::copyConditions(integer $id_cart_rule_source, integer $id_cart_rule_destination)

Copy conditions from one cart rule to an other



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CartRule.php line 180


#### Arguments
* $id_cart_rule_source **integer**
* $id_cart_rule_destination **integer**



### getIdByCode

    integer|boolean CartRuleCore::getIdByCode(string $code)

Retrieves the id associated to the given code



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CartRule.php line 243


#### Arguments
* $code **string**



### getCustomerCartRules

    array CartRuleCore::getCustomerCartRules($id_lang, $id_customer, boolean $active, boolean $includeGeneric, boolean $inStock, \Cart|null $cart, boolean $free_shipping_only, boolean $highlight_only)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CartRule.php line 263


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**
* $active **boolean**
* $includeGeneric **boolean**
* $inStock **boolean**
* $cart **[Cart](CartCore)|null**
* $free_shipping_only **boolean**
* $highlight_only **boolean**



### usedByCustomer

    boolean CartRuleCore::usedByCustomer($id_customer)





* Visibility: **public**
* This method is defined in classes\CartRule.php line 399


#### Arguments
* $id_customer **mixed**



### cartRuleExists

    boolean CartRuleCore::cartRuleExists($name)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CartRule.php line 413


#### Arguments
* $name **mixed**



### deleteByIdCustomer

    boolean CartRuleCore::deleteByIdCustomer($id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CartRule.php line 429


#### Arguments
* $id_customer **mixed**



### getProductRuleGroups

    array CartRuleCore::getProductRuleGroups()





* Visibility: **public**
* This method is defined in classes\CartRule.php line 443




### getProductRules

    array CartRuleCore::getProductRules($id_product_rule_group)





* Visibility: **public**
* This method is defined in classes\CartRule.php line 464


#### Arguments
* $id_product_rule_group **mixed**



### checkValidity

    boolean|mixed|string CartRuleCore::checkValidity(\Context $context, boolean $alreadyInCart, boolean $display_error, $check_carrier)

Check if this cart rule can be applied



* Visibility: **public**
* This method is defined in classes\CartRule.php line 493


#### Arguments
* $context **[Context](ContextCore)**
* $alreadyInCart **boolean** - &lt;p&gt;Check if the voucher is already on the cart&lt;/p&gt;
* $display_error **boolean** - &lt;p&gt;Display error&lt;/p&gt;
* $check_carrier **mixed**



### checkProductRestrictions

    mixed CartRuleCore::checkProductRestrictions(\Context $context, $return_products, $display_error, $already_in_cart)





* Visibility: **protected**
* This method is defined in classes\CartRule.php line 678


#### Arguments
* $context **[Context](ContextCore)**
* $return_products **mixed**
* $display_error **mixed**
* $already_in_cart **mixed**



### array_uintersect

    mixed CartRuleCore::array_uintersect($array1, $array2)





* Visibility: **protected**
* This method is **static**.
* This method is defined in classes\CartRule.php line 832


#### Arguments
* $array1 **mixed**
* $array2 **mixed**



### array_uintersect_compare

    mixed CartRuleCore::array_uintersect_compare($a, $b)





* Visibility: **protected**
* This method is **static**.
* This method is defined in classes\CartRule.php line 846


#### Arguments
* $a **mixed**
* $b **mixed**



### getContextualValue

    float|integer|string CartRuleCore::getContextualValue(boolean $use_tax, \Context $context, $filter, $package, boolean $use_cache)

The reduction value is POSITIVE



* Visibility: **public**
* This method is defined in classes\CartRule.php line 869


#### Arguments
* $use_tax **boolean**
* $context **[Context](ContextCore)**
* $filter **mixed**
* $package **mixed**
* $use_cache **boolean** - &lt;p&gt;Allow using cache to avoid multiple free gift using multishipping&lt;/p&gt;



### cleanCache

    mixed CartRuleCore::cleanCache()

Make sure caches are empty
Must be called before calling multiple time getContextualValue()



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CartRule.php line 1136




### getCartRuleCombinations

    array CartRuleCore::getCartRuleCombinations(integer $offset, integer $limit, string $search)





* Visibility: **protected**
* This method is defined in classes\CartRule.php line 1147


#### Arguments
* $offset **integer**
* $limit **integer**
* $search **string**



### getAssociatedRestrictions

    array|boolean CartRuleCore::getAssociatedRestrictions(string $type, boolean $active_only, boolean $i18n, integer $offset, integer $limit, string $search_cart_rule_name)





* Visibility: **public**
* This method is defined in classes\CartRule.php line 1198


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
* This method is defined in classes\CartRule.php line 1257


#### Arguments
* $context **mixed**



### autoAddToCart

    mixed CartRuleCore::autoAddToCart(\Context|null $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CartRule.php line 1281


#### Arguments
* $context **[Context](ContextCore)|null**



### isFeatureActive

    boolean CartRuleCore::isFeatureActive()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CartRule.php line 1354




### cleanProductRuleIntegrity

    mixed CartRuleCore::cleanProductRuleIntegrity($type, $list)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CartRule.php line 1364


#### Arguments
* $type **mixed**
* $list **mixed**



### getCartsRuleByCode

    array CartRuleCore::getCartsRuleByCode($name, $id_lang, $extended)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\CartRule.php line 1412


#### Arguments
* $name **mixed**
* $id_lang **mixed**
* $extended **mixed**


