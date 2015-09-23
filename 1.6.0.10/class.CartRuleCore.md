Class CartRuleCore
=====================





* Class name: CartRuleCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/CartRule.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L27)


Contents
--------

### Constants

* [BO_ORDER_CODE_PREFIX](#constant-BO_ORDER_CODE_PREFIX)
* [FILTER_ACTION_ALL](#constant-FILTER_ACTION_ALL)
* [FILTER_ACTION_ALL_NOCAP](#constant-FILTER_ACTION_ALL_NOCAP)
* [FILTER_ACTION_GIFT](#constant-FILTER_ACTION_GIFT)
* [FILTER_ACTION_REDUCTION](#constant-FILTER_ACTION_REDUCTION)
* [FILTER_ACTION_SHIPPING](#constant-FILTER_ACTION_SHIPPING)

### Properties

* [$active](#property-$active)
* [$carrier_restriction](#property-$carrier_restriction)
* [$cart_rule_restriction](#property-$cart_rule_restriction)
* [$code](#property-$code)
* [$country_restriction](#property-$country_restriction)
* [$date_add](#property-$date_add)
* [$date_from](#property-$date_from)
* [$date_to](#property-$date_to)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$description](#property-$description)
* [$free_shipping](#property-$free_shipping)
* [$gift_product](#property-$gift_product)
* [$gift_product_attribute](#property-$gift_product_attribute)
* [$group_restriction](#property-$group_restriction)
* [$highlight](#property-$highlight)
* [$id](#property-$id)
* [$id_customer](#property-$id_customer)
* [$minimum_amount](#property-$minimum_amount)
* [$minimum_amount_currency](#property-$minimum_amount_currency)
* [$minimum_amount_shipping](#property-$minimum_amount_shipping)
* [$minimum_amount_tax](#property-$minimum_amount_tax)
* [$name](#property-$name)
* [$only_one_gift](#property-$only_one_gift)
* [$partial_use](#property-$partial_use)
* [$priority](#property-$priority)
* [$product_restriction](#property-$product_restriction)
* [$quantity](#property-$quantity)
* [$quantity_per_user](#property-$quantity_per_user)
* [$reduction_amount](#property-$reduction_amount)
* [$reduction_currency](#property-$reduction_currency)
* [$reduction_percent](#property-$reduction_percent)
* [$reduction_product](#property-$reduction_product)
* [$reduction_tax](#property-$reduction_tax)
* [$shop_restriction](#property-$shop_restriction)

### Methods

* [add](#method-add)
* [array_uintersect](#method-array_uintersect)
* [array_uintersect_compare](#method-array_uintersect_compare)
* [autoAddToCart](#method-autoAddToCart)
* [autoRemoveFromCart](#method-autoRemoveFromCart)
* [cartRuleExists](#method-cartRuleExists)
* [checkProductRestrictions](#method-checkProductRestrictions)
* [checkValidity](#method-checkValidity)
* [cleanCache](#method-cleanCache)
* [cleanProductRuleIntegrity](#method-cleanProductRuleIntegrity)
* [copyConditions](#method-copyConditions)
* [delete](#method-delete)
* [deleteByIdCustomer](#method-deleteByIdCustomer)
* [getAssociatedRestrictions](#method-getAssociatedRestrictions)
* [getCartRuleCombinations](#method-getCartRuleCombinations)
* [getCartsRuleByCode](#method-getCartsRuleByCode)
* [getContextualValue](#method-getContextualValue)
* [getCustomerCartRules](#method-getCustomerCartRules)
* [getIdByCode](#method-getIdByCode)
* [getProductRuleGroups](#method-getProductRuleGroups)
* [getProductRules](#method-getProductRules)
* [isFeatureActive](#method-isFeatureActive)
* [update](#method-update)
* [usedByCustomer](#method-usedByCustomer)


Constants
----------


### <a name="constant-BO_ORDER_CODE_PREFIX"></a>BO_ORDER_CODE_PREFIX

```php
const BO_ORDER_CODE_PREFIX = 'BO_ORDER_'
```





* Source: [classes/CartRule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L36).


### <a name="constant-FILTER_ACTION_ALL"></a>FILTER_ACTION_ALL

```php
const FILTER_ACTION_ALL = 1
```





* Source: [classes/CartRule.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L30).


### <a name="constant-FILTER_ACTION_ALL_NOCAP"></a>FILTER_ACTION_ALL_NOCAP

```php
const FILTER_ACTION_ALL_NOCAP = 5
```





* Source: [classes/CartRule.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L34).


### <a name="constant-FILTER_ACTION_GIFT"></a>FILTER_ACTION_GIFT

```php
const FILTER_ACTION_GIFT = 4
```





* Source: [classes/CartRule.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L33).


### <a name="constant-FILTER_ACTION_REDUCTION"></a>FILTER_ACTION_REDUCTION

```php
const FILTER_ACTION_REDUCTION = 3
```





* Source: [classes/CartRule.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L32).


### <a name="constant-FILTER_ACTION_SHIPPING"></a>FILTER_ACTION_SHIPPING

```php
const FILTER_ACTION_SHIPPING = 2
```





* Source: [classes/CartRule.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L31).


Properties
----------


### <a name="property-$active"></a>$active

```php
public mixed $active = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L71).


### <a name="property-$carrier_restriction"></a>$carrier_restriction

```php
public mixed $carrier_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L57).


### <a name="property-$cart_rule_restriction"></a>$cart_rule_restriction

```php
public mixed $cart_rule_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L59).


### <a name="property-$code"></a>$code

```php
public mixed $code
```





* Visibility: **public**
* Source: [classes/CartRule.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L51).


### <a name="property-$country_restriction"></a>$country_restriction

```php
public mixed $country_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L56).


### <a name="property-$date_add"></a>$date_add

```php
public mixed $date_add
```





* Visibility: **public**
* Source: [classes/CartRule.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L72).


### <a name="property-$date_from"></a>$date_from

```php
public mixed $date_from
```





* Visibility: **public**
* Source: [classes/CartRule.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L44).


### <a name="property-$date_to"></a>$date_to

```php
public mixed $date_to
```





* Visibility: **public**
* Source: [classes/CartRule.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L45).


### <a name="property-$date_upd"></a>$date_upd

```php
public mixed $date_upd
```





* Visibility: **public**
* Source: [classes/CartRule.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L73).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'cart_rule', 'primary' => 'id_cart_rule', 'multilang' => true, 'fields' => array('id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'date_from' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'date_to' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'description' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 65534), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'quantity_per_user' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'priority' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'partial_use' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'code' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 254), 'minimum_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'minimum_amount_tax' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'minimum_amount_currency' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'minimum_amount_shipping' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'country_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'carrier_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'group_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cart_rule_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'product_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shop_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'free_shipping' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'reduction_percent' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPercentage'), 'reduction_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'reduction_tax' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'reduction_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'reduction_product' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'gift_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'gift_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'highlight' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 254)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/CartRule.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L78).


### <a name="property-$description"></a>$description

```php
public mixed $description
```





* Visibility: **public**
* Source: [classes/CartRule.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L46).


### <a name="property-$free_shipping"></a>$free_shipping

```php
public mixed $free_shipping
```





* Visibility: **public**
* Source: [classes/CartRule.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L62).


### <a name="property-$gift_product"></a>$gift_product

```php
public mixed $gift_product
```





* Visibility: **public**
* Source: [classes/CartRule.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L68).


### <a name="property-$gift_product_attribute"></a>$gift_product_attribute

```php
public mixed $gift_product_attribute
```





* Visibility: **public**
* Source: [classes/CartRule.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L69).


### <a name="property-$group_restriction"></a>$group_restriction

```php
public mixed $group_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L58).


### <a name="property-$highlight"></a>$highlight

```php
public mixed $highlight
```





* Visibility: **public**
* Source: [classes/CartRule.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L70).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/CartRule.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L41).


### <a name="property-$id_customer"></a>$id_customer

```php
public mixed $id_customer
```





* Visibility: **public**
* Source: [classes/CartRule.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L43).


### <a name="property-$minimum_amount"></a>$minimum_amount

```php
public mixed $minimum_amount
```





* Visibility: **public**
* Source: [classes/CartRule.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L52).


### <a name="property-$minimum_amount_currency"></a>$minimum_amount_currency

```php
public mixed $minimum_amount_currency
```





* Visibility: **public**
* Source: [classes/CartRule.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L54).


### <a name="property-$minimum_amount_shipping"></a>$minimum_amount_shipping

```php
public mixed $minimum_amount_shipping
```





* Visibility: **public**
* Source: [classes/CartRule.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L55).


### <a name="property-$minimum_amount_tax"></a>$minimum_amount_tax

```php
public mixed $minimum_amount_tax
```





* Visibility: **public**
* Source: [classes/CartRule.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L53).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/CartRule.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L42).


### <a name="property-$only_one_gift"></a>$only_one_gift

```php
protected mixed $only_one_gift = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/CartRule.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L39).


### <a name="property-$partial_use"></a>$partial_use

```php
public mixed $partial_use = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L50).


### <a name="property-$priority"></a>$priority

```php
public mixed $priority = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L49).


### <a name="property-$product_restriction"></a>$product_restriction

```php
public mixed $product_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L60).


### <a name="property-$quantity"></a>$quantity

```php
public mixed $quantity = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L47).


### <a name="property-$quantity_per_user"></a>$quantity_per_user

```php
public mixed $quantity_per_user = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L48).


### <a name="property-$reduction_amount"></a>$reduction_amount

```php
public mixed $reduction_amount
```





* Visibility: **public**
* Source: [classes/CartRule.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L64).


### <a name="property-$reduction_currency"></a>$reduction_currency

```php
public mixed $reduction_currency
```





* Visibility: **public**
* Source: [classes/CartRule.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L66).


### <a name="property-$reduction_percent"></a>$reduction_percent

```php
public mixed $reduction_percent
```





* Visibility: **public**
* Source: [classes/CartRule.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L63).


### <a name="property-$reduction_product"></a>$reduction_product

```php
public mixed $reduction_product
```





* Visibility: **public**
* Source: [classes/CartRule.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L67).


### <a name="property-$reduction_tax"></a>$reduction_tax

```php
public mixed $reduction_tax
```





* Visibility: **public**
* Source: [classes/CartRule.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L65).


### <a name="property-$shop_restriction"></a>$shop_restriction

```php
public mixed $shop_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L61).


Methods
-------


### <a name="method-add"></a>add

```php
mixed CartRuleCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L123)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-array_uintersect"></a>array_uintersect

```php
mixed CartRuleCore::array_uintersect($array1, $array2)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/CartRule.php line 764](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L764)


#### Arguments
* $array1 **mixed**
* $array2 **mixed**



### <a name="method-array_uintersect_compare"></a>array_uintersect_compare

```php
mixed CartRuleCore::array_uintersect_compare($a, $b)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/CartRule.php line 777](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L777)


#### Arguments
* $a **mixed**
* $b **mixed**



### <a name="method-autoAddToCart"></a>autoAddToCart

```php
mixed CartRuleCore::autoAddToCart(\Context|null $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 1135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L1135)


#### Arguments
* $context **[Context](class.ContextCore.md)|null**



### <a name="method-autoRemoveFromCart"></a>autoRemoveFromCart

```php
mixed CartRuleCore::autoRemoveFromCart($context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 1110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L1110)


#### Arguments
* $context **mixed**



### <a name="method-cartRuleExists"></a>cartRuleExists

```php
boolean CartRuleCore::cartRuleExists($name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L381)


#### Arguments
* $name **mixed**



### <a name="method-checkProductRestrictions"></a>checkProductRestrictions

```php
mixed CartRuleCore::checkProductRestrictions(\Context $context, $return_products, $display_error, $alreadyInCart)
```





* Visibility: **protected**
* Source: [classes/CartRule.php line 623](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L623)


#### Arguments
* $context **[Context](class.ContextCore.md)**
* $return_products **mixed**
* $display_error **mixed**
* $alreadyInCart **mixed**



### <a name="method-checkValidity"></a>checkValidity

```php
boolean|mixed|string CartRuleCore::checkValidity(\Context $context, boolean $alreadyInCart, boolean $display_error)
```

Check if this cart rule can be applied



* Visibility: **public**
* Source: [classes/CartRule.php line 458](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L458)


#### Arguments
* $context **[Context](class.ContextCore.md)**
* $alreadyInCart **boolean** - Check if the voucher is already on the cart
* $display_error **boolean** - Display error



### <a name="method-cleanCache"></a>cleanCache

```php
mixed CartRuleCore::cleanCache()
```

Make sure caches are empty
Must be called before calling multiple time getContextualValue()



* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 1023](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L1023)




### <a name="method-cleanProductRuleIntegrity"></a>cleanProductRuleIntegrity

```php
mixed CartRuleCore::cleanProductRuleIntegrity($type, $list)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 1212](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L1212)


#### Arguments
* $type **mixed**
* $list **mixed**



### <a name="method-copyConditions"></a>copyConditions

```php
mixed CartRuleCore::copyConditions(integer $id_cart_rule_source, integer $id_cart_rule_destination)
```

Copy conditions from one cart rule to an other



* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L168)


#### Arguments
* $id_cart_rule_source **integer**
* $id_cart_rule_destination **integer**



### <a name="method-delete"></a>delete

```php
mixed CartRuleCore::delete()
```





* Visibility: **public**
* Source: [classes/CartRule.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L141)




### <a name="method-deleteByIdCustomer"></a>deleteByIdCustomer

```php
boolean CartRuleCore::deleteByIdCustomer($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 397](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L397)


#### Arguments
* $id_customer **mixed**



### <a name="method-getAssociatedRestrictions"></a>getAssociatedRestrictions

```php
mixed CartRuleCore::getAssociatedRestrictions($type, $active_only, $i18n)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 1059](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L1059)


#### Arguments
* $type **mixed**
* $active_only **mixed**
* $i18n **mixed**



### <a name="method-getCartRuleCombinations"></a>getCartRuleCombinations

```php
mixed CartRuleCore::getCartRuleCombinations()
```





* Visibility: **protected**
* Source: [classes/CartRule.php line 1028](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L1028)




### <a name="method-getCartsRuleByCode"></a>getCartsRuleByCode

```php
array CartRuleCore::getCartsRuleByCode($name, $id_lang, $extended)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 1257](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L1257)


#### Arguments
* $name **mixed**
* $id_lang **mixed**
* $extended **mixed**



### <a name="method-getContextualValue"></a>getContextualValue

```php
float|integer|string CartRuleCore::getContextualValue(boolean $use_tax, \Context $context, $filter, $package, boolean $use_cache)
```

The reduction value is POSITIVE



* Visibility: **public**
* Source: [classes/CartRule.php line 798](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L798)


#### Arguments
* $use_tax **boolean**
* $context **[Context](class.ContextCore.md)**
* $filter **mixed**
* $package **mixed**
* $use_cache **boolean** - Allow using cache to avoid multiple free gift using multishipping



### <a name="method-getCustomerCartRules"></a>getCustomerCartRules

```php
array CartRuleCore::getCustomerCartRules($id_lang, $id_customer, boolean $active, boolean $includeGeneric, boolean $inStock, \Cart|null $cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L250)


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**
* $active **boolean**
* $includeGeneric **boolean**
* $inStock **boolean**
* $cart **[Cart](class.CartCore.md)|null**



### <a name="method-getIdByCode"></a>getIdByCode

```php
integer|boolean CartRuleCore::getIdByCode(string $code)
```

Retrieves the id associated to the given code



* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L233)


#### Arguments
* $code **string**



### <a name="method-getProductRuleGroups"></a>getProductRuleGroups

```php
array CartRuleCore::getProductRuleGroups()
```





* Visibility: **public**
* Source: [classes/CartRule.php line 410](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L410)




### <a name="method-getProductRules"></a>getProductRules

```php
array CartRuleCore::getProductRules($id_product_rule_group)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L430)


#### Arguments
* $id_product_rule_group **mixed**



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean CartRuleCore::isFeatureActive()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 1203](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L1203)




### <a name="method-update"></a>update

```php
mixed CartRuleCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L132)


#### Arguments
* $null_values **mixed**



### <a name="method-usedByCustomer"></a>usedByCustomer

```php
boolean CartRuleCore::usedByCustomer($id_customer)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 366](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CartRule.php#L366)


#### Arguments
* $id_customer **mixed**


