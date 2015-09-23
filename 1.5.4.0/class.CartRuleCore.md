Class CartRuleCore
=====================





* Class name: CartRuleCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/CartRule.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L27)


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
* [$db](#property-$db)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$get_shop_from_context](#property-$get_shop_from_context)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$id_shop_list](#property-$id_shop_list)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$update_fields](#property-$update_fields)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [array_uintersect](#method-array_uintersect)
* [array_uintersect_compare](#method-array_uintersect_compare)
* [associateTo](#method-associateTo)
* [autoAddToCart](#method-autoAddToCart)
* [autoRemoveFromCart](#method-autoRemoveFromCart)
* [cartRuleExists](#method-cartRuleExists)
* [checkProductRestrictions](#method-checkProductRestrictions)
* [checkValidity](#method-checkValidity)
* [cleanCache](#method-cleanCache)
* [cleanProductRuleIntegrity](#method-cleanProductRuleIntegrity)
* [clearCache](#method-clearCache)
* [copyConditions](#method-copyConditions)
* [delete](#method-delete)
* [deleteByIdCustomer](#method-deleteByIdCustomer)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateObject](#method-duplicateObject)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAssociatedRestrictions](#method-getAssociatedRestrictions)
* [getAssociatedShops](#method-getAssociatedShops)
* [getCartRuleCombinations](#method-getCartRuleCombinations)
* [getCartsRuleByCode](#method-getCartsRuleByCode)
* [getContextualValue](#method-getContextualValue)
* [getCustomerCartRules](#method-getCustomerCartRules)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getIdByCode](#method-getIdByCode)
* [getProductRuleGroups](#method-getProductRuleGroups)
* [getProductRules](#method-getProductRules)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isFeatureActive](#method-isFeatureActive)
* [isLangMultishop](#method-isLangMultishop)
* [isMultishop](#method-isMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateMultishopTable](#method-updateMultishopTable)
* [usedByCustomer](#method-usedByCustomer)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)


Constants
----------


### <a name="constant-BO_ORDER_CODE_PREFIX"></a>BO_ORDER_CODE_PREFIX

```php
const BO_ORDER_CODE_PREFIX = 'BO_ORDER_'
```





* Source: [classes/CartRule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L36).


### <a name="constant-FILTER_ACTION_ALL"></a>FILTER_ACTION_ALL

```php
const FILTER_ACTION_ALL = 1
```





* Source: [classes/CartRule.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L30).


### <a name="constant-FILTER_ACTION_ALL_NOCAP"></a>FILTER_ACTION_ALL_NOCAP

```php
const FILTER_ACTION_ALL_NOCAP = 5
```





* Source: [classes/CartRule.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L34).


### <a name="constant-FILTER_ACTION_GIFT"></a>FILTER_ACTION_GIFT

```php
const FILTER_ACTION_GIFT = 4
```





* Source: [classes/CartRule.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L33).


### <a name="constant-FILTER_ACTION_REDUCTION"></a>FILTER_ACTION_REDUCTION

```php
const FILTER_ACTION_REDUCTION = 3
```





* Source: [classes/CartRule.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L32).


### <a name="constant-FILTER_ACTION_SHIPPING"></a>FILTER_ACTION_SHIPPING

```php
const FILTER_ACTION_SHIPPING = 2
```





* Source: [classes/CartRule.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L31).


Properties
----------


### <a name="property-$active"></a>$active

```php
public mixed $active = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L71).


### <a name="property-$carrier_restriction"></a>$carrier_restriction

```php
public mixed $carrier_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L57).


### <a name="property-$cart_rule_restriction"></a>$cart_rule_restriction

```php
public mixed $cart_rule_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L59).


### <a name="property-$code"></a>$code

```php
public mixed $code
```





* Visibility: **public**
* Source: [classes/CartRule.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L51).


### <a name="property-$country_restriction"></a>$country_restriction

```php
public mixed $country_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L56).


### <a name="property-$date_add"></a>$date_add

```php
public mixed $date_add
```





* Visibility: **public**
* Source: [classes/CartRule.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L72).


### <a name="property-$date_from"></a>$date_from

```php
public mixed $date_from
```





* Visibility: **public**
* Source: [classes/CartRule.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L44).


### <a name="property-$date_to"></a>$date_to

```php
public mixed $date_to
```





* Visibility: **public**
* Source: [classes/CartRule.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L45).


### <a name="property-$date_upd"></a>$date_upd

```php
public mixed $date_upd
```





* Visibility: **public**
* Source: [classes/CartRule.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L73).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'cart_rule', 'primary' => 'id_cart_rule', 'multilang' => true, 'fields' => array('id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'date_from' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'date_to' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true), 'description' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 65534), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'quantity_per_user' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'priority' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'partial_use' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'code' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 254), 'minimum_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'minimum_amount_tax' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'minimum_amount_currency' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'minimum_amount_shipping' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'country_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'carrier_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'group_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'cart_rule_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'product_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shop_restriction' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'free_shipping' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'reduction_percent' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPercentage'), 'reduction_amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'reduction_tax' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'reduction_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'reduction_product' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'gift_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'gift_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'highlight' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 254)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/CartRule.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L78).


### <a name="property-$description"></a>$description

```php
public mixed $description
```





* Visibility: **public**
* Source: [classes/CartRule.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L46).


### <a name="property-$free_shipping"></a>$free_shipping

```php
public mixed $free_shipping
```





* Visibility: **public**
* Source: [classes/CartRule.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L62).


### <a name="property-$gift_product"></a>$gift_product

```php
public mixed $gift_product
```





* Visibility: **public**
* Source: [classes/CartRule.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L68).


### <a name="property-$gift_product_attribute"></a>$gift_product_attribute

```php
public mixed $gift_product_attribute
```





* Visibility: **public**
* Source: [classes/CartRule.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L69).


### <a name="property-$group_restriction"></a>$group_restriction

```php
public mixed $group_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L58).


### <a name="property-$highlight"></a>$highlight

```php
public mixed $highlight
```





* Visibility: **public**
* Source: [classes/CartRule.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L70).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/CartRule.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L41).


### <a name="property-$id_customer"></a>$id_customer

```php
public mixed $id_customer
```





* Visibility: **public**
* Source: [classes/CartRule.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L43).


### <a name="property-$minimum_amount"></a>$minimum_amount

```php
public mixed $minimum_amount
```





* Visibility: **public**
* Source: [classes/CartRule.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L52).


### <a name="property-$minimum_amount_currency"></a>$minimum_amount_currency

```php
public mixed $minimum_amount_currency
```





* Visibility: **public**
* Source: [classes/CartRule.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L54).


### <a name="property-$minimum_amount_shipping"></a>$minimum_amount_shipping

```php
public mixed $minimum_amount_shipping
```





* Visibility: **public**
* Source: [classes/CartRule.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L55).


### <a name="property-$minimum_amount_tax"></a>$minimum_amount_tax

```php
public mixed $minimum_amount_tax
```





* Visibility: **public**
* Source: [classes/CartRule.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L53).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/CartRule.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L42).


### <a name="property-$only_one_gift"></a>$only_one_gift

```php
protected mixed $only_one_gift = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/CartRule.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L39).


### <a name="property-$partial_use"></a>$partial_use

```php
public mixed $partial_use = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L50).


### <a name="property-$priority"></a>$priority

```php
public mixed $priority = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L49).


### <a name="property-$product_restriction"></a>$product_restriction

```php
public mixed $product_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L60).


### <a name="property-$quantity"></a>$quantity

```php
public mixed $quantity = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L47).


### <a name="property-$quantity_per_user"></a>$quantity_per_user

```php
public mixed $quantity_per_user = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L48).


### <a name="property-$reduction_amount"></a>$reduction_amount

```php
public mixed $reduction_amount
```





* Visibility: **public**
* Source: [classes/CartRule.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L64).


### <a name="property-$reduction_currency"></a>$reduction_currency

```php
public mixed $reduction_currency
```





* Visibility: **public**
* Source: [classes/CartRule.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L66).


### <a name="property-$reduction_percent"></a>$reduction_percent

```php
public mixed $reduction_percent
```





* Visibility: **public**
* Source: [classes/CartRule.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L63).


### <a name="property-$reduction_product"></a>$reduction_product

```php
public mixed $reduction_product
```





* Visibility: **public**
* Source: [classes/CartRule.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L67).


### <a name="property-$reduction_tax"></a>$reduction_tax

```php
public mixed $reduction_tax
```





* Visibility: **public**
* Source: [classes/CartRule.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L65).


### <a name="property-$shop_restriction"></a>$shop_restriction

```php
public mixed $shop_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L61).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L140).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L130).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L80).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L65).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L95).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L85).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L100).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L90).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L105).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L63).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L57).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L59).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L61).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L75).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L116).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L119).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L70).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L110).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L135).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L113).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L168)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **integer** - ID shop for objects with multishop on langs



### <a name="method-add"></a>add

```php
mixed CartRuleCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L123)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1146](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1146)


#### Arguments
* $fields **mixed**



### <a name="method-array_uintersect"></a>array_uintersect

```php
mixed CartRuleCore::array_uintersect($array1, $array2)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/CartRule.php line 703](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L703)


#### Arguments
* $array1 **mixed**
* $array2 **mixed**



### <a name="method-array_uintersect_compare"></a>array_uintersect_compare

```php
mixed CartRuleCore::array_uintersect_compare($a, $b)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/CartRule.php line 716](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L716)


#### Arguments
* $a **mixed**
* $b **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1193](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1193)


#### Arguments
* $id_shops **integer|array**



### <a name="method-autoAddToCart"></a>autoAddToCart

```php
mixed CartRuleCore::autoAddToCart(\Context|null $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 1075](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L1075)


#### Arguments
* $context **[Context](class.ContextCore.md)|null**



### <a name="method-autoRemoveFromCart"></a>autoRemoveFromCart

```php
mixed CartRuleCore::autoRemoveFromCart($context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 1050](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L1050)


#### Arguments
* $context **mixed**



### <a name="method-cartRuleExists"></a>cartRuleExists

```php
boolean CartRuleCore::cartRuleExists($name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L301)


#### Arguments
* $name **mixed**



### <a name="method-checkProductRestrictions"></a>checkProductRestrictions

```php
mixed CartRuleCore::checkProductRestrictions(\Context $context, $return_products, $display_error)
```





* Visibility: **protected**
* Source: [classes/CartRule.php line 568](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L568)


#### Arguments
* $context **[Context](class.ContextCore.md)**
* $return_products **mixed**
* $display_error **mixed**



### <a name="method-checkValidity"></a>checkValidity

```php
boolean|mixed|string CartRuleCore::checkValidity(\Context $context, boolean $alreadyInCart, boolean $display_error)
```

Check if this cart rule can be applied



* Visibility: **public**
* Source: [classes/CartRule.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L381)


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
* Source: [classes/CartRule.php line 962](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L962)




### <a name="method-cleanProductRuleIntegrity"></a>cleanProductRuleIntegrity

```php
mixed CartRuleCore::cleanProductRuleIntegrity($type, $list)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 1150](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L1150)


#### Arguments
* $type **mixed**
* $list **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1160](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1160)


#### Arguments
* $all **mixed**



### <a name="method-copyConditions"></a>copyConditions

```php
mixed CartRuleCore::copyConditions(integer $id_cart_rule_source, integer $id_cart_rule_destination)
```

Copy conditions from one cart rule to an other



* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L168)


#### Arguments
* $id_cart_rule_source **integer**
* $id_cart_rule_destination **integer**



### <a name="method-delete"></a>delete

```php
mixed CartRuleCore::delete()
```





* Visibility: **public**
* Source: [classes/CartRule.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L141)




### <a name="method-deleteByIdCustomer"></a>deleteByIdCustomer

```php
boolean CartRuleCore::deleteByIdCustomer($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 317](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L317)


#### Arguments
* $id_customer **mixed**



### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage($force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1319](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1319)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 737](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L737)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L939)


#### Arguments
* $field **mixed**
* $class **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateObject"></a>duplicateObject

```php
\new ObjectModelCore::duplicateObject()
```

Duplicate current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 528](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L528)




### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1237](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1237)


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
* Source: [classes/ObjectModel.php line 1356](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1356)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L335)


#### Arguments
* $type **integer** - FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L381)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAssociatedRestrictions"></a>getAssociatedRestrictions

```php
mixed CartRuleCore::getAssociatedRestrictions($type, $active_only, $i18n)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 999](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L999)


#### Arguments
* $type **mixed**
* $active_only **mixed**
* $i18n **mixed**



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1222](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1222)




### <a name="method-getCartRuleCombinations"></a>getCartRuleCombinations

```php
mixed CartRuleCore::getCartRuleCombinations()
```





* Visibility: **protected**
* Source: [classes/CartRule.php line 967](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L967)




### <a name="method-getCartsRuleByCode"></a>getCartsRuleByCode

```php
array CartRuleCore::getCartsRuleByCode($name, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 1195](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L1195)


#### Arguments
* $name **mixed**
* $id_lang **mixed**



### <a name="method-getContextualValue"></a>getContextualValue

```php
float|integer|string CartRuleCore::getContextualValue(boolean $use_tax, \Context $context, $filter, $package, boolean $use_cache)
```

The reduction value is POSITIVE



* Visibility: **public**
* Source: [classes/CartRule.php line 737](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L737)


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
* Source: [classes/CartRule.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L216)


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**
* $active **boolean**
* $includeGeneric **boolean**
* $inStock **boolean**
* $cart **[Cart](class.CartCore.md)|null**



### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1462](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1462)


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
* Source: [classes/ObjectModel.php line 1560](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1560)


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
* Source: [classes/ObjectModel.php line 263](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L263)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 300](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L300)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1138](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1138)


#### Arguments
* $all **mixed**



### <a name="method-getFieldsShop"></a>getFieldsShop

```php
array ObjectModelCore::getFieldsShop()
```

Prepare fields for multishop
Fields are not validated here, we considere they are already validated in getFields() method, this
not the best solution but this is the only one possible for retro compatibility.



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L286)




### <a name="method-getIdByCode"></a>getIdByCode

```php
integer|boolean CartRuleCore::getIdByCode(string $code)
```

Retrieves the id associated to the given code



* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L199)


#### Arguments
* $code **string**



### <a name="method-getProductRuleGroups"></a>getProductRuleGroups

```php
array CartRuleCore::getProductRuleGroups()
```





* Visibility: **public**
* Source: [classes/CartRule.php line 330](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L330)




### <a name="method-getProductRules"></a>getProductRules

```php
array CartRuleCore::getProductRules($id_product_rule_group)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 353](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L353)


#### Arguments
* $id_product_rule_group **mixed**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 769](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L769)


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
* Source: [classes/ObjectModel.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L148)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1080](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1080)


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
* Source: [classes/ObjectModel.php line 1006](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1006)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is more than one entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1262](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1262)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1394](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1394)


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
* Source: [classes/ObjectModel.php line 1413](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1413)


#### Arguments
* $class **string** - Class of objects to hydrate
* $datas **array** - List of data (multi-dimensional array)
* $id_lang **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1175](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1175)


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
* Source: [classes/ObjectModel.php line 1374](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1374)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean CartRuleCore::isFeatureActive()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 1141](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L1141)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1274](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1274)




### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1269](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1269)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 785](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L785)


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
* Source: [classes/ObjectModel.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L425)


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
* Source: [classes/ObjectModel.php line 1500](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1500)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1586](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1586)


#### Arguments
* $fields **array**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L753)




### <a name="method-update"></a>update

```php
mixed CartRuleCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L132)


#### Arguments
* $null_values **mixed**



### <a name="method-updateMultishopTable"></a>updateMultishopTable

```php
boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)
```

Update a table and splits the common datas and the shop datas



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1289](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1289)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-usedByCustomer"></a>usedByCustomer

```php
boolean CartRuleCore::usedByCustomer($id_customer)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/CartRule.php#L286)


#### Arguments
* $id_customer **mixed**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 954](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L954)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 960](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L960)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 892](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L892)


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
* Source: [classes/ObjectModel.php line 823](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L823)


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
* Source: [classes/ObjectModel.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L852)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/ObjectModel.php#L1116)


#### Arguments
* $htmlentities **mixed**


