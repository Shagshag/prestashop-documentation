Class CartRuleCore
=====================





* Class name: CartRuleCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/CartRule.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L28)


Contents
--------


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
* [$description](#property-$description)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$free_shipping](#property-$free_shipping)
* [$gift_product](#property-$gift_product)
* [$group_restriction](#property-$group_restriction)
* [$id](#property-$id)
* [$id_customer](#property-$id_customer)
* [$identifier](#property-$identifier)
* [$minimum_amount](#property-$minimum_amount)
* [$minimum_amount_currency](#property-$minimum_amount_currency)
* [$minimum_amount_shipping](#property-$minimum_amount_shipping)
* [$minimum_amount_tax](#property-$minimum_amount_tax)
* [$name](#property-$name)
* [$priority](#property-$priority)
* [$product_restriction](#property-$product_restriction)
* [$quantity](#property-$quantity)
* [$quantity_per_user](#property-$quantity_per_user)
* [$reduction_amount](#property-$reduction_amount)
* [$reduction_currency](#property-$reduction_currency)
* [$reduction_percent](#property-$reduction_percent)
* [$reduction_product](#property-$reduction_product)
* [$reduction_tax](#property-$reduction_tax)
* [$table](#property-$table)
* [$_cache](#property-$_cache)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$langMultiShop](#property-$langMultiShop)
* [$tables](#property-$tables)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [autoAddToCart](#method-autoAddToCart)
* [autoRemoveFromCart](#method-autoRemoveFromCart)
* [cartRuleExists](#method-cartRuleExists)
* [checkValidity](#method-checkValidity)
* [clearCache](#method-clearCache)
* [copyConditions](#method-copyConditions)
* [delete](#method-delete)
* [deleteByIdCustomer](#method-deleteByIdCustomer)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [getAssociatedRestrictions](#method-getAssociatedRestrictions)
* [getCartRuleCombinations](#method-getCartRuleCombinations)
* [getCartsRuleByCode](#method-getCartsRuleByCode)
* [getContextualValue](#method-getContextualValue)
* [getCustomerCartRules](#method-getCustomerCartRules)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getIdByCode](#method-getIdByCode)
* [getIdentifier](#method-getIdentifier)
* [getProductRules](#method-getProductRules)
* [getTranslationsFields](#method-getTranslationsFields)
* [getTranslationsFieldsChild](#method-getTranslationsFieldsChild)
* [getValidationRules](#method-getValidationRules)
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
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [usedByCustomer](#method-usedByCustomer)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$active"></a>$active

```php
public mixed $active = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L56).


### <a name="property-$carrier_restriction"></a>$carrier_restriction

```php
public mixed $carrier_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L45).


### <a name="property-$cart_rule_restriction"></a>$cart_rule_restriction

```php
public mixed $cart_rule_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L47).


### <a name="property-$code"></a>$code

```php
public mixed $code
```





* Visibility: **public**
* Source: [classes/CartRule.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L39).


### <a name="property-$country_restriction"></a>$country_restriction

```php
public mixed $country_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L44).


### <a name="property-$date_add"></a>$date_add

```php
public mixed $date_add
```





* Visibility: **public**
* Source: [classes/CartRule.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L57).


### <a name="property-$date_from"></a>$date_from

```php
public mixed $date_from
```





* Visibility: **public**
* Source: [classes/CartRule.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L33).


### <a name="property-$date_to"></a>$date_to

```php
public mixed $date_to
```





* Visibility: **public**
* Source: [classes/CartRule.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L34).


### <a name="property-$date_upd"></a>$date_upd

```php
public mixed $date_upd
```





* Visibility: **public**
* Source: [classes/CartRule.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L58).


### <a name="property-$description"></a>$description

```php
public mixed $description
```





* Visibility: **public**
* Source: [classes/CartRule.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L35).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('date_from', 'date_to')
```





* Visibility: **protected**
* Source: [classes/CartRule.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L63).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array('name')
```





* Visibility: **protected**
* Source: [classes/CartRule.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L94).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array('code' => 254, 'description' => 65534)
```





* Visibility: **protected**
* Source: [classes/CartRule.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L64).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array('name' => 254)
```





* Visibility: **protected**
* Source: [classes/CartRule.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L95).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('id_customer' => 'isUnsignedId', 'date_from' => 'isDate', 'date_to' => 'isDate', 'description' => 'isCleanHtml', 'quantity' => 'isUnsignedInt', 'quantity_per_user' => 'isUnsignedInt', 'priority' => 'isUnsignedInt', 'code' => 'isCleanHtml', 'minimum_amount' => 'isFloat', 'minimum_amount_tax' => 'isBool', 'minimum_amount_currency' => 'isInt', 'minimum_amount_shipping' => 'isBool', 'country_restriction' => 'isBool', 'carrier_restriction' => 'isBool', 'group_restriction' => 'isBool', 'cart_rule_restriction' => 'isBool', 'product_restriction' => 'isBool', 'free_shipping' => 'isBool', 'reduction_percent' => 'isFloat', 'reduction_amount' => 'isFloat', 'reduction_tax' => 'isBool', 'reduction_currency' => 'isUnsignedId', 'reduction_product' => 'isInt', 'gift_product' => 'isUnsignedId', 'active' => 'isBool', 'date_add' => 'isDate', 'date_upd' => 'isDate')
```





* Visibility: **protected**
* Source: [classes/CartRule.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L65).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array('name' => 'isCleanHtml')
```





* Visibility: **protected**
* Source: [classes/CartRule.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L96).


### <a name="property-$free_shipping"></a>$free_shipping

```php
public mixed $free_shipping
```





* Visibility: **public**
* Source: [classes/CartRule.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L49).


### <a name="property-$gift_product"></a>$gift_product

```php
public mixed $gift_product
```





* Visibility: **public**
* Source: [classes/CartRule.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L55).


### <a name="property-$group_restriction"></a>$group_restriction

```php
public mixed $group_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L46).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/CartRule.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L30).


### <a name="property-$id_customer"></a>$id_customer

```php
public mixed $id_customer
```





* Visibility: **public**
* Source: [classes/CartRule.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L32).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_cart_rule'
```





* Visibility: **protected**
* Source: [classes/CartRule.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L61).


### <a name="property-$minimum_amount"></a>$minimum_amount

```php
public mixed $minimum_amount
```





* Visibility: **public**
* Source: [classes/CartRule.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L40).


### <a name="property-$minimum_amount_currency"></a>$minimum_amount_currency

```php
public mixed $minimum_amount_currency
```





* Visibility: **public**
* Source: [classes/CartRule.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L42).


### <a name="property-$minimum_amount_shipping"></a>$minimum_amount_shipping

```php
public mixed $minimum_amount_shipping
```





* Visibility: **public**
* Source: [classes/CartRule.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L43).


### <a name="property-$minimum_amount_tax"></a>$minimum_amount_tax

```php
public mixed $minimum_amount_tax
```





* Visibility: **public**
* Source: [classes/CartRule.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L41).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/CartRule.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L31).


### <a name="property-$priority"></a>$priority

```php
public mixed $priority = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L38).


### <a name="property-$product_restriction"></a>$product_restriction

```php
public mixed $product_restriction
```





* Visibility: **public**
* Source: [classes/CartRule.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L48).


### <a name="property-$quantity"></a>$quantity

```php
public mixed $quantity = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L36).


### <a name="property-$quantity_per_user"></a>$quantity_per_user

```php
public mixed $quantity_per_user = 1
```





* Visibility: **public**
* Source: [classes/CartRule.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L37).


### <a name="property-$reduction_amount"></a>$reduction_amount

```php
public mixed $reduction_amount
```





* Visibility: **public**
* Source: [classes/CartRule.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L51).


### <a name="property-$reduction_currency"></a>$reduction_currency

```php
public mixed $reduction_currency
```





* Visibility: **public**
* Source: [classes/CartRule.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L53).


### <a name="property-$reduction_percent"></a>$reduction_percent

```php
public mixed $reduction_percent
```





* Visibility: **public**
* Source: [classes/CartRule.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L50).


### <a name="property-$reduction_product"></a>$reduction_product

```php
public mixed $reduction_product
```





* Visibility: **public**
* Source: [classes/CartRule.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L54).


### <a name="property-$reduction_tax"></a>$reduction_tax

```php
public mixed $reduction_tax
```





* Visibility: **public**
* Source: [classes/CartRule.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L52).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'cart_rule'
```





* Visibility: **protected**
* Source: [classes/CartRule.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L60).


### <a name="property-$_cache"></a>$_cache

```php
protected mixed $_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L75).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected \fieldsRequiredDatabase $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L50).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L34).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L36).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L78).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L81).


### <a name="property-$langMultiShop"></a>$langMultiShop

```php
protected mixed $langMultiShop = false
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L67).


### <a name="property-$tables"></a>$tables

```php
protected array $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L70).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L73).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L115)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **mixed**



### <a name="method-add"></a>add

```php
mixed CartRuleCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L138)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L780)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 828](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L828)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-autoAddToCart"></a>autoAddToCart

```php
mixed CartRuleCore::autoAddToCart($context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 652](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L652)


#### Arguments
* $context **mixed**



### <a name="method-autoRemoveFromCart"></a>autoRemoveFromCart

```php
mixed CartRuleCore::autoRemoveFromCart($context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 630](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L630)


#### Arguments
* $context **mixed**



### <a name="method-cartRuleExists"></a>cartRuleExists

```php
mixed CartRuleCore::cartRuleExists($name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L233)


#### Arguments
* $name **mixed**



### <a name="method-checkValidity"></a>checkValidity

```php
mixed CartRuleCore::checkValidity(\Context $context, $alreadyInCart)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L275)


#### Arguments
* $context **[Context](class.ContextCore.md)**
* $alreadyInCart **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 794](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L794)


#### Arguments
* $all **mixed**



### <a name="method-copyConditions"></a>copyConditions

```php
mixed CartRuleCore::copyConditions($id_cart_rule_source, $id_cart_rule_destination)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L162)


#### Arguments
* $id_cart_rule_source **mixed**
* $id_cart_rule_destination **mixed**



### <a name="method-delete"></a>delete

```php
mixed CartRuleCore::delete()
```





* Visibility: **public**
* Source: [classes/CartRule.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L147)




### <a name="method-deleteByIdCustomer"></a>deleteByIdCustomer

```php
mixed CartRuleCore::deleteByIdCustomer($id_customer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L244)


#### Arguments
* $id_customer **mixed**



### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 898](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L898)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed ObjectModelCore::deleteSelection($selection)
```

Delete several objects from database

return boolean Deletion result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L387)


#### Arguments
* $selection **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $className, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 558](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L558)


#### Arguments
* $field **mixed**
* $className **mixed**
* $htmlentities **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 868](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L868)


#### Arguments
* $id **mixed**



### <a name="method-existsInDatabase"></a>existsInDatabase

```php
boolean ObjectModelCore::existsInDatabase($id_entity, $table)
```

Specify if an ObjectModel is already in database



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 931](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L931)


#### Arguments
* $id_entity **mixed** - entity id
* $table **mixed**



### <a name="method-getAssociatedRestrictions"></a>getAssociatedRestrictions

```php
mixed CartRuleCore::getAssociatedRestrictions($type, $active)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 591](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L591)


#### Arguments
* $type **mixed**
* $active **mixed**



### <a name="method-getCartRuleCombinations"></a>getCartRuleCombinations

```php
mixed CartRuleCore::getCartRuleCombinations()
```





* Visibility: **protected**
* Source: [classes/CartRule.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L559)




### <a name="method-getCartsRuleByCode"></a>getCartsRuleByCode

```php
mixed CartRuleCore::getCartsRuleByCode($name, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 711](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L711)


#### Arguments
* $name **mixed**
* $id_lang **mixed**



### <a name="method-getContextualValue"></a>getContextualValue

```php
mixed CartRuleCore::getContextualValue($useTax, \Context $context)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 442](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L442)


#### Arguments
* $useTax **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getCustomerCartRules"></a>getCustomerCartRules

```php
mixed CartRuleCore::getCustomerCartRules($id_lang, $id_customer, $active, $includeGeneric, $inStock, \Cart $cart)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L190)


#### Arguments
* $id_lang **mixed**
* $id_customer **mixed**
* $active **mixed**
* $includeGeneric **mixed**
* $inStock **mixed**
* $cart **[Cart](class.CartCore.md)**



### <a name="method-getFields"></a>getFields

```php
mixed CartRuleCore::getFields()
```





* Visibility: **public**
* Source: [classes/CartRule.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L98)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L772)


#### Arguments
* $all **mixed**



### <a name="method-getFieldsValidateLang"></a>getFieldsValidateLang

```php
array ObjectModelCore::getFieldsValidateLang()
```

Get list of fields related to language to validate



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L975)




### <a name="method-getIdByCode"></a>getIdByCode

```php
mixed CartRuleCore::getIdByCode($code)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L183)


#### Arguments
* $code **mixed**



### <a name="method-getIdentifier"></a>getIdentifier

```php
string ObjectModelCore::getIdentifier()
```

Get object identifier name



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L964)




### <a name="method-getProductRules"></a>getProductRules

```php
mixed CartRuleCore::getProductRules()
```





* Visibility: **public**
* Source: [classes/CartRule.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L254)




### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields(array $fieldsArray)
```

Prepare multilingual fields for database insertion



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 430](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L430)


#### Arguments
* $fieldsArray **array** - Multilingual fields to prepare
return array Prepared fields for database insertion



### <a name="method-getTranslationsFieldsChild"></a>getTranslationsFieldsChild

```php
mixed CartRuleCore::getTranslationsFieldsChild()
```





* Visibility: **public**
* Source: [classes/CartRule.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L131)




### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $className)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L89)


#### Arguments
* $className **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 747](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L747)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

```php
mixed ObjectModelCore::getWebserviceParameters($wsParamsAttributeName)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 617](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L617)


#### Arguments
* $wsParamsAttributeName **mixed**



### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 987](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L987)


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
* Source: [classes/ObjectModel.php line 1006](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L1006)


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
* Source: [classes/ObjectModel.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L854)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 809](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L809)


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
* Source: [classes/ObjectModel.php line 948](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L948)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
mixed CartRuleCore::isFeatureActive()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CartRule.php line 706](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L706)




### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 888](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L888)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fieldsArray, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L447)


#### Arguments
* $fields **mixed**
* $fieldsArray **mixed**
* $id_language **mixed**



### <a name="method-save"></a>save

```php
mixed ObjectModelCore::save($nullValues, $autodate)
```

Save current object to database (add or update)

return boolean Insertion result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L192)


#### Arguments
* $nullValues **mixed**
* $autodate **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
mixed ObjectModelCore::toggleStatus()
```

Toggle object status in database

return boolean Update result

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L405)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update($nullValues)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L274)


#### Arguments
* $nullValues **mixed**



### <a name="method-usedByCustomer"></a>usedByCustomer

```php
mixed CartRuleCore::usedByCustomer($id_customer)
```





* Visibility: **public**
* Source: [classes/CartRule.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/CartRule.php#L223)


#### Arguments
* $id_customer **mixed**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 571](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L571)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 577](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L577)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateFields"></a>validateFields

```php
mixed ObjectModelCore::validateFields($die, $errorReturn)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 481](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L481)


#### Arguments
* $die **mixed**
* $errorReturn **mixed**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

```php
mixed ObjectModelCore::validateFieldsLang($die, $errorReturn)
```

Check for multilingual fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 514](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L514)


#### Arguments
* $die **mixed**
* $errorReturn **mixed**


