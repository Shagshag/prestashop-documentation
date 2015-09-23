Class DiscountCore
=====================





* Class name: DiscountCore
* Parent class: [CartRule](class.CartRuleCore.md)
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.
* Source: [classes/Discount.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L31)


Contents
--------

### Constants

* [AMOUNT](#constant-AMOUNT)
* [FREE_SHIPPING](#constant-FREE_SHIPPING)
* [PERCENT](#constant-PERCENT)

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
* [$id](#property-$id)
* [$id_customer](#property-$id_customer)
* [$minimum_amount](#property-$minimum_amount)
* [$minimum_amount_currency](#property-$minimum_amount_currency)
* [$minimum_amount_shipping](#property-$minimum_amount_shipping)
* [$minimum_amount_tax](#property-$minimum_amount_tax)
* [$name](#property-$name)
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
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__call](#method-__call)
* [__construct](#method-__construct)
* [__get](#method-__get)
* [__set](#method-__set)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [autoAddToCart](#method-autoAddToCart)
* [autoRemoveFromCart](#method-autoRemoveFromCart)
* [cartRuleExists](#method-cartRuleExists)
* [checkProductRestrictions](#method-checkProductRestrictions)
* [checkValidity](#method-checkValidity)
* [clearCache](#method-clearCache)
* [copyConditions](#method-copyConditions)
* [createOrderDiscount](#method-createOrderDiscount)
* [delete](#method-delete)
* [deleteByIdCustomer](#method-deleteByIdCustomer)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [discountExists](#method-discountExists)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAssociatedRestrictions](#method-getAssociatedRestrictions)
* [getCartRuleCombinations](#method-getCartRuleCombinations)
* [getCartsRuleByCode](#method-getCartsRuleByCode)
* [getContextualValue](#method-getContextualValue)
* [getCustomerCartRules](#method-getCustomerCartRules)
* [getCustomerDiscounts](#method-getCustomerDiscounts)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getIdByCode](#method-getIdByCode)
* [getIdByName](#method-getIdByName)
* [getProductRuleGroups](#method-getProductRuleGroups)
* [getProductRules](#method-getProductRules)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getValue](#method-getValue)
* [getVouchersToCartDisplay](#method-getVouchersToCartDisplay)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isFeatureActive](#method-isFeatureActive)
* [isLangMultishop](#method-isLangMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [usedByCustomer](#method-usedByCustomer)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)


Constants
----------


### <a name="constant-AMOUNT"></a>AMOUNT

```php
const AMOUNT = 2
```





* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* Source: [classes/Discount.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L34).


### <a name="constant-FREE_SHIPPING"></a>FREE_SHIPPING

```php
const FREE_SHIPPING = 3
```





* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* Source: [classes/Discount.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L35).


### <a name="constant-PERCENT"></a>PERCENT

```php
const PERCENT = 1
```





* **Warning:** this constant is **deprecated**. This means that this constant will likely be removed in a future version.
* Source: [classes/Discount.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L33).


Properties
----------


### <a name="property-$active"></a>$active

```php
public mixed $active = 1
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L64).


### <a name="property-$carrier_restriction"></a>$carrier_restriction

```php
public mixed $carrier_restriction
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L51).


### <a name="property-$cart_rule_restriction"></a>$cart_rule_restriction

```php
public mixed $cart_rule_restriction
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L53).


### <a name="property-$code"></a>$code

```php
public mixed $code
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L45).


### <a name="property-$country_restriction"></a>$country_restriction

```php
public mixed $country_restriction
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L50).


### <a name="property-$date_add"></a>$date_add

```php
public mixed $date_add
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L65).


### <a name="property-$date_from"></a>$date_from

```php
public mixed $date_from
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L38).


### <a name="property-$date_to"></a>$date_to

```php
public mixed $date_to
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L39).


### <a name="property-$date_upd"></a>$date_upd

```php
public mixed $date_upd
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L66).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'cart_rule', 'primary' => 'id_cart_rule', 'multilang' => true, 'fields' => array('id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'date_from' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'date_to' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'description' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 65534), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'quantity_per_user' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'priority' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'partial_use' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'code' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 254), 'minimum_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'minimum_amount_tax' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'minimum_amount_currency' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'minimum_amount_shipping' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'country_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'carrier_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'group_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cart_rule_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'product_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shop_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'free_shipping' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'reduction_percent' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'reduction_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'reduction_tax' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'reduction_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'reduction_product' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'gift_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'gift_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 254)))
```





* Visibility: **public**
* This property is **static**.
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L71).


### <a name="property-$description"></a>$description

```php
public mixed $description
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L40).


### <a name="property-$free_shipping"></a>$free_shipping

```php
public mixed $free_shipping
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L56).


### <a name="property-$gift_product"></a>$gift_product

```php
public mixed $gift_product
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L62).


### <a name="property-$gift_product_attribute"></a>$gift_product_attribute

```php
public mixed $gift_product_attribute
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L63).


### <a name="property-$group_restriction"></a>$group_restriction

```php
public mixed $group_restriction
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L52).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L35).


### <a name="property-$id_customer"></a>$id_customer

```php
public mixed $id_customer
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L37).


### <a name="property-$minimum_amount"></a>$minimum_amount

```php
public mixed $minimum_amount
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L46).


### <a name="property-$minimum_amount_currency"></a>$minimum_amount_currency

```php
public mixed $minimum_amount_currency
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L48).


### <a name="property-$minimum_amount_shipping"></a>$minimum_amount_shipping

```php
public mixed $minimum_amount_shipping
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L49).


### <a name="property-$minimum_amount_tax"></a>$minimum_amount_tax

```php
public mixed $minimum_amount_tax
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L47).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L36).


### <a name="property-$partial_use"></a>$partial_use

```php
public mixed $partial_use = 1
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L44).


### <a name="property-$priority"></a>$priority

```php
public mixed $priority = 1
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L43).


### <a name="property-$product_restriction"></a>$product_restriction

```php
public mixed $product_restriction
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L54).


### <a name="property-$quantity"></a>$quantity

```php
public mixed $quantity = 1
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L41).


### <a name="property-$quantity_per_user"></a>$quantity_per_user

```php
public mixed $quantity_per_user = 1
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L42).


### <a name="property-$reduction_amount"></a>$reduction_amount

```php
public mixed $reduction_amount
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L58).


### <a name="property-$reduction_currency"></a>$reduction_currency

```php
public mixed $reduction_currency
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L60).


### <a name="property-$reduction_percent"></a>$reduction_percent

```php
public mixed $reduction_percent
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L57).


### <a name="property-$reduction_product"></a>$reduction_product

```php
public mixed $reduction_product
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L61).


### <a name="property-$reduction_tax"></a>$reduction_tax

```php
public mixed $reduction_tax
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L59).


### <a name="property-$shop_restriction"></a>$shop_restriction

```php
public mixed $shop_restriction
```





* Visibility: **public**
* This property is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L55).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L97).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L53).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L108).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L111).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L102).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L105).


Methods
-------


### <a name="method-__call"></a>__call

```php
mixed DiscountCore::__call($method, $args)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L125)


#### Arguments
* $method **mixed**
* $args **mixed**



### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L150)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **integer** - ID shop for objects with multishop on langs



### <a name="method-__get"></a>__get

```php
mixed DiscountCore::__get($key)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L37)


#### Arguments
* $key **mixed**



### <a name="method-__set"></a>__set

```php
mixed DiscountCore::__set($key, $value)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L77)


#### Arguments
* $key **mixed**
* $value **mixed**



### <a name="method-add"></a>add

```php
mixed DiscountCore::add($autodate, $nullValues, $categories)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L137)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $categories **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L925)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 973](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L973)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-autoAddToCart"></a>autoAddToCart

```php
mixed CartRuleCore::autoAddToCart(\Context|null $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 923](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L923)


#### Arguments
* $context **[Context](class.ContextCore.md)|null**



### <a name="method-autoRemoveFromCart"></a>autoRemoveFromCart

```php
mixed CartRuleCore::autoRemoveFromCart($context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 898](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L898)


#### Arguments
* $context **mixed**



### <a name="method-cartRuleExists"></a>cartRuleExists

```php
boolean CartRuleCore::cartRuleExists($name)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L287)


#### Arguments
* $name **mixed**



### <a name="method-checkProductRestrictions"></a>checkProductRestrictions

```php
mixed CartRuleCore::checkProductRestrictions(\Context $context, $return_products)
```





* Visibility: **protected**
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 535](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L535)


#### Arguments
* $context **[Context](class.ContextCore.md)**
* $return_products **mixed**



### <a name="method-checkValidity"></a>checkValidity

```php
boolean|mixed|string CartRuleCore::checkValidity(\Context $context, boolean $alreadyInCart)
```

Check if this cart rule can be applied



* Visibility: **public**
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 367](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L367)


#### Arguments
* $context **[Context](class.ContextCore.md)**
* $alreadyInCart **boolean**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L939)


#### Arguments
* $all **mixed**



### <a name="method-copyConditions"></a>copyConditions

```php
mixed CartRuleCore::copyConditions(integer $id_cart_rule_source, integer $id_cart_rule_destination)
```

Copy conditions from one cart rule to an other



* Visibility: **public**
* This method is **static**.
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L154)


#### Arguments
* $id_cart_rule_source **integer**
* $id_cart_rule_destination **integer**



### <a name="method-createOrderDiscount"></a>createOrderDiscount

```php
mixed DiscountCore::createOrderDiscount($order, $productList, $qtyList, $name, $shipping_cost, $id_category, $subcategory)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L204)


#### Arguments
* $order **mixed**
* $productList **mixed**
* $qtyList **mixed**
* $name **mixed**
* $shipping_cost **mixed**
* $id_category **mixed**
* $subcategory **mixed**



### <a name="method-delete"></a>delete

```php
mixed CartRuleCore::delete()
```





* Visibility: **public**
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L127)




### <a name="method-deleteByIdCustomer"></a>deleteByIdCustomer

```php
boolean CartRuleCore::deleteByIdCustomer($id_customer)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L303)


#### Arguments
* $id_customer **mixed**



### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1047](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1047)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L559)


#### Arguments
* $selection **array**



### <a name="method-discountExists"></a>discountExists

```php
mixed DiscountCore::discountExists($discountName, $id_discount)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L196)


#### Arguments
* $discountName **mixed**
* $id_discount **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 757](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L757)


#### Arguments
* $field **mixed**
* $class **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1017](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1017)


#### Arguments
* $id **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1081](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1081)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L272)


#### Arguments
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L319)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAssociatedRestrictions"></a>getAssociatedRestrictions

```php
mixed CartRuleCore::getAssociatedRestrictions($type, $active_only, $i18n)
```





* Visibility: **public**
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 859](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L859)


#### Arguments
* $type **mixed**
* $active_only **mixed**
* $i18n **mixed**



### <a name="method-getCartRuleCombinations"></a>getCartRuleCombinations

```php
mixed CartRuleCore::getCartRuleCombinations()
```





* Visibility: **protected**
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L827)




### <a name="method-getCartsRuleByCode"></a>getCartsRuleByCode

```php
array CartRuleCore::getCartsRuleByCode($name, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 997](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L997)


#### Arguments
* $name **mixed**
* $id_lang **mixed**



### <a name="method-getContextualValue"></a>getContextualValue

```php
float|integer|string CartRuleCore::getContextualValue(boolean $useTax, \Context $context, $filter)
```

The reduction value is POSITIVE



* Visibility: **public**
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 670](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L670)


#### Arguments
* $useTax **boolean**
* $context **[Context](class.ContextCore.md)**
* $filter **mixed**



### <a name="method-getCustomerCartRules"></a>getCustomerCartRules

```php
array CartRuleCore::getCustomerCartRules($id_lang, $id_customer, boolean $active, boolean $includeGeneric, boolean $inStock, \Cart|null $cart)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L202)


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**
* $active **boolean**
* $includeGeneric **boolean**
* $inStock **boolean**
* $cart **[Cart](class.CartCore.md)|null**



### <a name="method-getCustomerDiscounts"></a>getCustomerDiscounts

```php
mixed DiscountCore::getCustomerDiscounts($id_lang, $id_customer, $active, $includeGenericOnes, $hasStock, \Cart $cart)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L165)


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**
* $active **mixed**
* $includeGenericOnes **mixed**
* $hasStock **mixed**
* $cart **[Cart](class.CartCore.md)**



### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1184](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1184)


#### Arguments
* $class **string** - Name of object
* $field **string** - Name of field if we want the definition of one field only



### <a name="method-getFieldByLang"></a>getFieldByLang

```php
mixed ObjectModelCore::getFieldByLang($field_name, null $id_lang)
```

Return the field value for the specified language if the field is multilang, else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1261](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1261)


#### Arguments
* $field_name **mixed**
* $id_lang **null**



### <a name="method-getFields"></a>getFields

```php
array ObjectModelCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval.

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L234)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L249)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 917](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L917)


#### Arguments
* $all **mixed**



### <a name="method-getIdByCode"></a>getIdByCode

```php
integer|boolean CartRuleCore::getIdByCode(string $code)
```

Retrieves the id associated to the given code



* Visibility: **public**
* This method is **static**.
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L185)


#### Arguments
* $code **string**



### <a name="method-getIdByName"></a>getIdByName

```php
mixed DiscountCore::getIdByName($code)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L157)


#### Arguments
* $code **mixed**



### <a name="method-getProductRuleGroups"></a>getProductRuleGroups

```php
array CartRuleCore::getProductRuleGroups()
```





* Visibility: **public**
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L316)




### <a name="method-getProductRules"></a>getProductRules

```php
array CartRuleCore::getProductRules($id_product_rule_group)
```





* Visibility: **public**
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L339)


#### Arguments
* $id_product_rule_group **mixed**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L595)


#### Arguments
* $fields_array **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $class)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L130)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getValue"></a>getValue

```php
mixed DiscountCore::getValue($nb_discounts, $order_total_products, $shipping_fees, $id_cart, $useTax, \Currency $currency, \Shop $shop)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L181)


#### Arguments
* $nb_discounts **mixed**
* $order_total_products **mixed**
* $shipping_fees **mixed**
* $id_cart **mixed**
* $useTax **mixed**
* $currency **[Currency](class.CurrencyCore.md)**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getVouchersToCartDisplay"></a>getVouchersToCartDisplay

```php
mixed DiscountCore::getVouchersToCartDisplay($id_lang, $id_customer)
```





* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L173)


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L890)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
mixed ObjectModelCore::getWebserviceParameters($ws_params_attribute_name)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 816](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L816)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1116)


#### Arguments
* $data **array**
* $id_lang **integer**



### <a name="method-hydrateCollection"></a>hydrateCollection

```php
array ObjectModelCore::hydrateCollection(string $class, array $datas, integer $id_lang)
```

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1135)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-isAssociatedToGroupShop"></a>isAssociatedToGroupShop

```php
boolean ObjectModelCore::isAssociatedToGroupShop(integer $id_group_shop)
```

Check if current object is associated to a group shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1003)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 954](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L954)


#### Arguments
* $id_shop **integer**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

```php
boolean ObjectModelCore::isCurrentlyUsed(string $table, boolean $has_active_column)
```

This method is allow to know if a entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1099](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1099)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean CartRuleCore::isFeatureActive()
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 986](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L986)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1037](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1037)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L611)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L360)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1207](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L1207)




### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L575)




### <a name="method-update"></a>update

```php
mixed DiscountCore::update($autodate, $nullValues, $categories)
```





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* Source: [classes/Discount.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Discount.php#L147)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**
* $categories **mixed**



### <a name="method-usedByCustomer"></a>usedByCustomer

```php
boolean CartRuleCore::usedByCustomer($id_customer)
```





* Visibility: **public**
* This method is defined by [CartRuleCore](class.CartRuleCore.md).
* Source: [classes/CartRule.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/CartRule.php#L272)


#### Arguments
* $id_customer **mixed**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L772)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L778)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L710)


#### Arguments
* $field **string** - Field name
* $value **mixed** - Field value
* $id_lang **integer**



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L649)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
boolean|string ObjectModelCore::validateFieldsLang(boolean $die, boolean $error_return)
```

Check for multilingual fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/ObjectModel.php#L675)


#### Arguments
* $die **boolean**
* $error_return **boolean**


