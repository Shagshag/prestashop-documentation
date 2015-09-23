Class CarrierCore
=====================





* Class name: CarrierCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Carrier.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L28)


Contents
--------

### Constants

* [ALL_CARRIERS](#constant-ALL_CARRIERS)
* [CARRIERS_MODULE](#constant-CARRIERS_MODULE)
* [CARRIERS_MODULE_NEED_RANGE](#constant-CARRIERS_MODULE_NEED_RANGE)
* [PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE](#constant-PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE)
* [PS_CARRIERS_ONLY](#constant-PS_CARRIERS_ONLY)
* [SHIPPING_METHOD_DEFAULT](#constant-SHIPPING_METHOD_DEFAULT)
* [SHIPPING_METHOD_FREE](#constant-SHIPPING_METHOD_FREE)
* [SHIPPING_METHOD_PRICE](#constant-SHIPPING_METHOD_PRICE)
* [SHIPPING_METHOD_WEIGHT](#constant-SHIPPING_METHOD_WEIGHT)
* [SORT_BY_ASC](#constant-SORT_BY_ASC)
* [SORT_BY_DESC](#constant-SORT_BY_DESC)
* [SORT_BY_POSITION](#constant-SORT_BY_POSITION)
* [SORT_BY_PRICE](#constant-SORT_BY_PRICE)

### Properties

* [$active](#property-$active)
* [$cache_tax_rule](#property-$cache_tax_rule)
* [$delay](#property-$delay)
* [$deleted](#property-$deleted)
* [$external_module_name](#property-$external_module_name)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$grade](#property-$grade)
* [$id_reference](#property-$id_reference)
* [$id_tax_rules_group](#property-$id_tax_rules_group)
* [$identifier](#property-$identifier)
* [$is_free](#property-$is_free)
* [$is_module](#property-$is_module)
* [$langMultiShop](#property-$langMultiShop)
* [$max_depth](#property-$max_depth)
* [$max_height](#property-$max_height)
* [$max_weight](#property-$max_weight)
* [$max_width](#property-$max_width)
* [$name](#property-$name)
* [$need_range](#property-$need_range)
* [$position](#property-$position)
* [$price_by_price](#property-$price_by_price)
* [$price_by_price2](#property-$price_by_price2)
* [$price_by_weight](#property-$price_by_weight)
* [$price_by_weight2](#property-$price_by_weight2)
* [$range_behavior](#property-$range_behavior)
* [$shipping_external](#property-$shipping_external)
* [$shipping_handling](#property-$shipping_handling)
* [$shipping_method](#property-$shipping_method)
* [$table](#property-$table)
* [$url](#property-$url)
* [$webserviceParameters](#property-$webserviceParameters)
* [$_cache](#property-$_cache)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$tables](#property-$tables)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addDeliveryPrice](#method-addDeliveryPrice)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [addZone](#method-addZone)
* [associateTo](#method-associateTo)
* [checkCarrierZone](#method-checkCarrierZone)
* [checkDeliveryPriceByPrice](#method-checkDeliveryPriceByPrice)
* [checkDeliveryPriceByWeight](#method-checkDeliveryPriceByWeight)
* [cleanPositions](#method-cleanPositions)
* [clearCache](#method-clearCache)
* [copyCarrierData](#method-copyCarrierData)
* [delete](#method-delete)
* [deleteDeliveryPrice](#method-deleteDeliveryPrice)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [deleteZone](#method-deleteZone)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [getAvailableCarrierList](#method-getAvailableCarrierList)
* [getCarrierByReference](#method-getCarrierByReference)
* [getCarriers](#method-getCarriers)
* [getCarriersForOrder](#method-getCarriersForOrder)
* [getDefaultCarrierSelection](#method-getDefaultCarrierSelection)
* [getDeliveredCountries](#method-getDeliveredCountries)
* [getDeliveryPriceByPrice](#method-getDeliveryPriceByPrice)
* [getDeliveryPriceByRanges](#method-getDeliveryPriceByRanges)
* [getDeliveryPriceByWeight](#method-getDeliveryPriceByWeight)
* [getFields](#method-getFields)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsValidateLang](#method-getFieldsValidateLang)
* [getGroups](#method-getGroups)
* [getHigherPosition](#method-getHigherPosition)
* [getIdTaxRulesGroupByIdCarrier](#method-getIdTaxRulesGroupByIdCarrier)
* [getIdentifier](#method-getIdentifier)
* [getMaxDeliveryPriceByPrice](#method-getMaxDeliveryPriceByPrice)
* [getMaxDeliveryPriceByWeight](#method-getMaxDeliveryPriceByWeight)
* [getRangeObject](#method-getRangeObject)
* [getRangeSuffix](#method-getRangeSuffix)
* [getRangeTable](#method-getRangeTable)
* [getShippingMethod](#method-getShippingMethod)
* [getTaxesRate](#method-getTaxesRate)
* [getTranslationsFields](#method-getTranslationsFields)
* [getTranslationsFieldsChild](#method-getTranslationsFieldsChild)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getZone](#method-getZone)
* [getZones](#method-getZones)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [isUsed](#method-isUsed)
* [makeTranslationFields](#method-makeTranslationFields)
* [save](#method-save)
* [setConfiguration](#method-setConfiguration)
* [sqlDeliveryRangeShop](#method-sqlDeliveryRangeShop)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updatePosition](#method-updatePosition)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)


Constants
----------


### <a name="constant-ALL_CARRIERS"></a>ALL_CARRIERS

```php
const ALL_CARRIERS = 5
```





* Source: [classes/Carrier.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L37).


### <a name="constant-CARRIERS_MODULE"></a>CARRIERS_MODULE

```php
const CARRIERS_MODULE = 2
```





* Source: [classes/Carrier.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L34).


### <a name="constant-CARRIERS_MODULE_NEED_RANGE"></a>CARRIERS_MODULE_NEED_RANGE

```php
const CARRIERS_MODULE_NEED_RANGE = 3
```





* Source: [classes/Carrier.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L35).


### <a name="constant-PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE"></a>PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE

```php
const PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE = 4
```





* Source: [classes/Carrier.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L36).


### <a name="constant-PS_CARRIERS_ONLY"></a>PS_CARRIERS_ONLY

```php
const PS_CARRIERS_ONLY = 1
```

getCarriers method filter



* Source: [classes/Carrier.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L33).


### <a name="constant-SHIPPING_METHOD_DEFAULT"></a>SHIPPING_METHOD_DEFAULT

```php
const SHIPPING_METHOD_DEFAULT = 0
```





* Source: [classes/Carrier.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L39).


### <a name="constant-SHIPPING_METHOD_FREE"></a>SHIPPING_METHOD_FREE

```php
const SHIPPING_METHOD_FREE = 3
```





* Source: [classes/Carrier.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L42).


### <a name="constant-SHIPPING_METHOD_PRICE"></a>SHIPPING_METHOD_PRICE

```php
const SHIPPING_METHOD_PRICE = 2
```





* Source: [classes/Carrier.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L41).


### <a name="constant-SHIPPING_METHOD_WEIGHT"></a>SHIPPING_METHOD_WEIGHT

```php
const SHIPPING_METHOD_WEIGHT = 1
```





* Source: [classes/Carrier.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L40).


### <a name="constant-SORT_BY_ASC"></a>SORT_BY_ASC

```php
const SORT_BY_ASC = 0
```





* Source: [classes/Carrier.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L47).


### <a name="constant-SORT_BY_DESC"></a>SORT_BY_DESC

```php
const SORT_BY_DESC = 1
```





* Source: [classes/Carrier.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L48).


### <a name="constant-SORT_BY_POSITION"></a>SORT_BY_POSITION

```php
const SORT_BY_POSITION = 1
```





* Source: [classes/Carrier.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L45).


### <a name="constant-SORT_BY_PRICE"></a>SORT_BY_PRICE

```php
const SORT_BY_PRICE = 0
```





* Source: [classes/Carrier.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L44).


Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Carrier.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L66).


### <a name="property-$cache_tax_rule"></a>$cache_tax_rule

```php
protected mixed $cache_tax_rule = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L133).


### <a name="property-$delay"></a>$delay

```php
public string $delay
```





* Visibility: **public**
* Source: [classes/Carrier.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L63).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Carrier.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L69).


### <a name="property-$external_module_name"></a>$external_module_name

```php
public string $external_module_name = null
```





* Visibility: **public**
* Source: [classes/Carrier.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L90).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array('name', 'active')
```





* Visibility: **protected**
* Source: [classes/Carrier.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L115).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array('delay')
```





* Visibility: **protected**
* Source: [classes/Carrier.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L121).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array('name' => 64, 'grade' => 1)
```





* Visibility: **protected**
* Source: [classes/Carrier.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L116).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array('delay' => 128)
```





* Visibility: **protected**
* Source: [classes/Carrier.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L122).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array('id_tax_rules_group' => 'isInt', 'name' => 'isCarrierName', 'active' => 'isBool', 'is_free' => 'isBool', 'url' => 'isAbsoluteUrl', 'shipping_handling' => 'isBool', 'range_behavior' => 'isBool', 'shipping_method' => 'isUnsignedInt', 'max_width' => 'isUnsignedInt', 'max_height' => 'isUnsignedInt', 'max_deep' => 'isUnsignedInt', 'max_weight' => 'isUnsignedInt', 'grade' => 'isUnsignedInt')
```





* Visibility: **protected**
* Source: [classes/Carrier.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L117).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array('delay' => 'isGenericName')
```





* Visibility: **protected**
* Source: [classes/Carrier.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L123).


### <a name="property-$grade"></a>$grade

```php
public integer $grade
```





* Visibility: **public**
* Source: [classes/Carrier.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L111).


### <a name="property-$id_reference"></a>$id_reference

```php
public integer $id_reference
```





* Visibility: **public**
* Source: [classes/Carrier.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L54).


### <a name="property-$id_tax_rules_group"></a>$id_tax_rules_group

```php
public integer $id_tax_rules_group
```





* Visibility: **public**
* Source: [classes/Carrier.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L51).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier = 'id_carrier'
```





* Visibility: **protected**
* Source: [classes/Carrier.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L126).


### <a name="property-$is_free"></a>$is_free

```php
public boolean $is_free = false
```





* Visibility: **public**
* Source: [classes/Carrier.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L81).


### <a name="property-$is_module"></a>$is_module

```php
public boolean $is_module
```





* Visibility: **public**
* Source: [classes/Carrier.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L78).


### <a name="property-$langMultiShop"></a>$langMultiShop

```php
protected mixed $langMultiShop = true
```





* Visibility: **protected**
* Source: [classes/Carrier.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L113).


### <a name="property-$max_depth"></a>$max_depth

```php
public integer $max_depth
```





* Visibility: **public**
* Source: [classes/Carrier.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L105).


### <a name="property-$max_height"></a>$max_height

```php
public integer $max_height
```





* Visibility: **public**
* Source: [classes/Carrier.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L102).


### <a name="property-$max_weight"></a>$max_weight

```php
public integer $max_weight
```





* Visibility: **public**
* Source: [classes/Carrier.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L108).


### <a name="property-$max_width"></a>$max_width

```php
public integer $max_width
```





* Visibility: **public**
* Source: [classes/Carrier.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L99).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Carrier.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L57).


### <a name="property-$need_range"></a>$need_range

```php
public boolean $need_range
```





* Visibility: **public**
* Source: [classes/Carrier.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L93).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/Carrier.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L96).


### <a name="property-$price_by_price"></a>$price_by_price

```php
protected mixed $price_by_price = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L130).


### <a name="property-$price_by_price2"></a>$price_by_price2

```php
protected mixed $price_by_price2 = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L131).


### <a name="property-$price_by_weight"></a>$price_by_weight

```php
protected mixed $price_by_weight = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L128).


### <a name="property-$price_by_weight2"></a>$price_by_weight2

```php
protected mixed $price_by_weight2 = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L129).


### <a name="property-$range_behavior"></a>$range_behavior

```php
public integer $range_behavior
```





* Visibility: **public**
* Source: [classes/Carrier.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L75).


### <a name="property-$shipping_external"></a>$shipping_external

```php
public boolean $shipping_external
```





* Visibility: **public**
* Source: [classes/Carrier.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L87).


### <a name="property-$shipping_handling"></a>$shipping_handling

```php
public boolean $shipping_handling = true
```





* Visibility: **public**
* Source: [classes/Carrier.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L72).


### <a name="property-$shipping_method"></a>$shipping_method

```php
public integer $shipping_method
```





* Visibility: **public**
* Source: [classes/Carrier.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L84).


### <a name="property-$table"></a>$table

```php
protected mixed $table = 'carrier'
```





* Visibility: **protected**
* Source: [classes/Carrier.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L125).


### <a name="property-$url"></a>$url

```php
public string $url
```





* Visibility: **public**
* Source: [classes/Carrier.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L60).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_tax_rules_group' => array(), 'deleted' => array(), 'is_module' => array()))
```





* Visibility: **protected**
* Source: [classes/Carrier.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L135).


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


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L31).


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


### <a name="property-$tables"></a>$tables

```php
protected array $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L70).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CarrierCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L169)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed CarrierCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L187)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addDeliveryPrice"></a>addDeliveryPrice

```php
boolean CarrierCore::addDeliveryPrice($price_list, \Shop $shop)
```

Add new delivery prices



* Visibility: **public**
* Source: [classes/Carrier.php line 701](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L701)


#### Arguments
* $price_list **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 780](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L780)


#### Arguments
* $fields **mixed**



### <a name="method-addZone"></a>addZone

```php
mixed CarrierCore::addZone($id_zone)
```

Add zone



* Visibility: **public**
* Source: [classes/Carrier.php line 640](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L640)


#### Arguments
* $id_zone **mixed**



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



### <a name="method-checkCarrierZone"></a>checkCarrierZone

```php
mixed CarrierCore::checkCarrierZone($id_carrier, $id_zone)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 594](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L594)


#### Arguments
* $id_carrier **mixed**
* $id_zone **mixed**



### <a name="method-checkDeliveryPriceByPrice"></a>checkDeliveryPriceByPrice

```php
float CarrierCore::checkDeliveryPriceByPrice($id_carrier, $order_total, integer $id_zone, integer $id_currency, \Shop $shop)
```

Check delivery prices for a given order



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 328](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L328)


#### Arguments
* $id_carrier **mixed**
* $order_total **mixed**
* $id_zone **integer** - Zone id (for customer delivery address)
* $id_currency **integer**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-checkDeliveryPriceByWeight"></a>checkDeliveryPriceByWeight

```php
mixed CarrierCore::checkDeliveryPriceByWeight($id_carrier, $total_weight, $id_zone, \Shop $shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L251)


#### Arguments
* $id_carrier **mixed**
* $total_weight **mixed**
* $id_zone **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-cleanPositions"></a>cleanPositions

```php
boolean CarrierCore::cleanPositions()
```

Reorder carrier position.

Call it after deleting a carrier.

* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 986](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L986)




### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 794](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L794)


#### Arguments
* $all **mixed**



### <a name="method-copyCarrierData"></a>copyCarrierData

```php
mixed CarrierCore::copyCarrierData($old_id)
```

Copy old carrier informations when update carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 747](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L747)


#### Arguments
* $old_id **mixed**



### <a name="method-delete"></a>delete

```php
mixed CarrierCore::delete()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L204)




### <a name="method-deleteDeliveryPrice"></a>deleteDeliveryPrice

```php
boolean CarrierCore::deleteDeliveryPrice($range_table, \Shop $shop)
```

Clean delivery prices (weight/price)



* Visibility: **public**
* Source: [classes/Carrier.php line 677](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L677)


#### Arguments
* $range_table **mixed**
* $shop **[Shop](class.ShopCore.md)**



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



### <a name="method-deleteZone"></a>deleteZone

```php
mixed CarrierCore::deleteZone($id_zone)
```

Delete zone



* Visibility: **public**
* Source: [classes/Carrier.php line 650](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L650)


#### Arguments
* $id_zone **mixed**



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



### <a name="method-getAvailableCarrierList"></a>getAvailableCarrierList

```php
mixed CarrierCore::getAvailableCarrierList($product, $id_warehouse, $id_shop)
```

For a given {product, warehouse}, gets the carrier available



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1027](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L1027)


#### Arguments
* $product **mixed** - integer The id of the product, or an array with at least the package size and weight
* $id_warehouse **mixed**
* $id_shop **mixed**



### <a name="method-getCarrierByReference"></a>getCarrierByReference

```php
mixed CarrierCore::getCarrierByReference($id_reference)
```

Get carrier using the reference id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 804](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L804)


#### Arguments
* $id_reference **mixed**



### <a name="method-getCarriers"></a>getCarriers

```php
array CarrierCore::getCarriers(integer $id_lang, boolean $active, $delete, $id_zone, $ids_group, $modules_filters)
```

Get all carriers in a given language



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 399](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L399)


#### Arguments
* $id_lang **integer** - Language id
* $active **boolean** - Returns only active carriers when true
* $delete **mixed**
* $id_zone **mixed**
* $ids_group **mixed**
* $modules_filters **mixed**



### <a name="method-getCarriersForOrder"></a>getCarriersForOrder

```php
Array CarrierCore::getCarriersForOrder(integer $id_zone, Array $groups)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 519](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L519)


#### Arguments
* $id_zone **integer**
* $groups **Array** - group of the customer



### <a name="method-getDefaultCarrierSelection"></a>getDefaultCarrierSelection

```php
\number CarrierCore::getDefaultCarrierSelection(array $carriers, $default_carrier)
```

Return the default carrier to use



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 497](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L497)


#### Arguments
* $carriers **array**
* $default_carrier **mixed**



### <a name="method-getDeliveredCountries"></a>getDeliveredCountries

```php
mixed CarrierCore::getDeliveredCountries($id_lang, $active_countries, $active_carriers, $contain_states)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 459](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L459)


#### Arguments
* $id_lang **mixed**
* $active_countries **mixed**
* $active_carriers **mixed**
* $contain_states **mixed**



### <a name="method-getDeliveryPriceByPrice"></a>getDeliveryPriceByPrice

```php
float CarrierCore::getDeliveryPriceByPrice($order_total, integer $id_zone, $id_currency, \Shop $shop)
```

Get delivery prices for a given order



* Visibility: **public**
* Source: [classes/Carrier.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L293)


#### Arguments
* $order_total **mixed**
* $id_zone **integer** - Zone id (for customer delivery address)
* $id_currency **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getDeliveryPriceByRanges"></a>getDeliveryPriceByRanges

```php
array CarrierCore::getDeliveryPriceByRanges($range_table, $id_carrier, \Shop $shop)
```

Get delivery prices for a given shipping method (price/weight)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L372)


#### Arguments
* $range_table **mixed**
* $id_carrier **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getDeliveryPriceByWeight"></a>getDeliveryPriceByWeight

```php
float CarrierCore::getDeliveryPriceByWeight($total_weight, integer $id_zone, \Shop $shop)
```

Get delivery prices for a given order



* Visibility: **public**
* Source: [classes/Carrier.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L228)


#### Arguments
* $total_weight **mixed**
* $id_zone **integer** - Zone id (for customer delivery address)
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getFields"></a>getFields

```php
mixed CarrierCore::getFields()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L143)




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




### <a name="method-getGroups"></a>getGroups

```php
array CarrierCore::getGroups()
```

Get a specific group



* Visibility: **public**
* Source: [classes/Carrier.php line 663](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L663)




### <a name="method-getHigherPosition"></a>getHigherPosition

```php
integer CarrierCore::getHigherPosition()
```

getHigherPosition

Get the higher carrier position

* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1013](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L1013)




### <a name="method-getIdTaxRulesGroupByIdCarrier"></a>getIdTaxRulesGroupByIdCarrier

```php
mixed CarrierCore::getIdTaxRulesGroupByIdCarrier($id_carrier)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 878](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L878)


#### Arguments
* $id_carrier **mixed**



### <a name="method-getIdentifier"></a>getIdentifier

```php
string ObjectModelCore::getIdentifier()
```

Get object identifier name



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L964)




### <a name="method-getMaxDeliveryPriceByPrice"></a>getMaxDeliveryPriceByPrice

```php
mixed CarrierCore::getMaxDeliveryPriceByPrice($id_zone, \Shop $shop)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L351)


#### Arguments
* $id_zone **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getMaxDeliveryPriceByWeight"></a>getMaxDeliveryPriceByWeight

```php
mixed CarrierCore::getMaxDeliveryPriceByWeight($id_zone, \Shop $shop)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 271](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L271)


#### Arguments
* $id_zone **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getRangeObject"></a>getRangeObject

```php
mixed CarrierCore::getRangeObject()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 858](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L858)




### <a name="method-getRangeSuffix"></a>getRangeSuffix

```php
mixed CarrierCore::getRangeSuffix($currency)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 868](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L868)


#### Arguments
* $currency **mixed**



### <a name="method-getRangeTable"></a>getRangeTable

```php
mixed CarrierCore::getRangeTable()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 848](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L848)




### <a name="method-getShippingMethod"></a>getShippingMethod

```php
mixed CarrierCore::getShippingMethod()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 829](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L829)




### <a name="method-getTaxesRate"></a>getTaxesRate

```php
mixed CarrierCore::getTaxesRate(\Address $address)
```

Return the taxes rate associated to the carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 898](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L898)


#### Arguments
* $address **[Address](class.AddressCore.md)**



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
array CarrierCore::getTranslationsFieldsChild()
```

Check then return multilingual fields for database interaction



* Visibility: **public**
* Source: [classes/Carrier.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L181)




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



### <a name="method-getZone"></a>getZone

```php
array CarrierCore::getZone($id_zone)
```

Get a specific zones



* Visibility: **public**
* Source: [classes/Carrier.php line 628](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L628)


#### Arguments
* $id_zone **mixed**



### <a name="method-getZones"></a>getZones

```php
array CarrierCore::getZones()
```

Get all zones



* Visibility: **public**
* Source: [classes/Carrier.php line 614](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L614)




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



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 888](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/ObjectModel.php#L888)




### <a name="method-isUsed"></a>isUsed

```php
integer CarrierCore::isUsed()
```

Check if carrier is used (at least one order placed)



* Visibility: **public**
* Source: [classes/Carrier.php line 819](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L819)




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



### <a name="method-setConfiguration"></a>setConfiguration

```php
mixed CarrierCore::setConfiguration(integer $id_old)
```

Change carrier id in delivery prices when updating a carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L216)


#### Arguments
* $id_old **integer** - Old id carrier



### <a name="method-sqlDeliveryRangeShop"></a>sqlDeliveryRangeShop

```php
string CarrierCore::sqlDeliveryRangeShop($range_table, \Shop $shop, $alias)
```

This tricky method generate a sql clause to check if ranged data are overloaded by multishop



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 913](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L913)


#### Arguments
* $range_table **mixed**
* $shop **[Shop](class.ShopCore.md)**
* $alias **mixed**



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



### <a name="method-updatePosition"></a>updatePosition

```php
boolean CarrierCore::updatePosition(boolean $way, integer $position)
```

Move a carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 947](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/Carrier.php#L947)


#### Arguments
* $way **boolean** - Up (1)  or Down (0)
* $position **integer**



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


