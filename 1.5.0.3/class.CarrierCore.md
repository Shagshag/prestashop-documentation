Class CarrierCore
=====================





* Class name: CarrierCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Carrier.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L28)


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
* [$definition](#property-$definition)
* [$delay](#property-$delay)
* [$deleted](#property-$deleted)
* [$external_module_name](#property-$external_module_name)
* [$grade](#property-$grade)
* [$id_reference](#property-$id_reference)
* [$id_tax_rules_group](#property-$id_tax_rules_group)
* [$is_free](#property-$is_free)
* [$is_module](#property-$is_module)
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
* [$url](#property-$url)
* [$webserviceParameters](#property-$webserviceParameters)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$table](#property-$table)
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
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAvailableCarrierList](#method-getAvailableCarrierList)
* [getCarrierByReference](#method-getCarrierByReference)
* [getCarriers](#method-getCarriers)
* [getCarriersForOrder](#method-getCarriersForOrder)
* [getDefaultCarrierSelection](#method-getDefaultCarrierSelection)
* [getDefinition](#method-getDefinition)
* [getDeliveredCountries](#method-getDeliveredCountries)
* [getDeliveryPriceByPrice](#method-getDeliveryPriceByPrice)
* [getDeliveryPriceByRanges](#method-getDeliveryPriceByRanges)
* [getDeliveryPriceByWeight](#method-getDeliveryPriceByWeight)
* [getEntity](#method-getEntity)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getGroups](#method-getGroups)
* [getHigherPosition](#method-getHigherPosition)
* [getIdTaxRulesGroupByIdCarrier](#method-getIdTaxRulesGroupByIdCarrier)
* [getMaxDeliveryPriceByPrice](#method-getMaxDeliveryPriceByPrice)
* [getMaxDeliveryPriceByWeight](#method-getMaxDeliveryPriceByWeight)
* [getRangeObject](#method-getRangeObject)
* [getRangeSuffix](#method-getRangeSuffix)
* [getRangeTable](#method-getRangeTable)
* [getShippingMethod](#method-getShippingMethod)
* [getTaxesRate](#method-getTaxesRate)
* [getTranslationsFields](#method-getTranslationsFields)
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
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [sqlDeliveryRangeShop](#method-sqlDeliveryRangeShop)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updatePosition](#method-updatePosition)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)


Constants
----------


### <a name="constant-ALL_CARRIERS"></a>ALL_CARRIERS

```php
const ALL_CARRIERS = 5
```





* Source: [classes/Carrier.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L37).


### <a name="constant-CARRIERS_MODULE"></a>CARRIERS_MODULE

```php
const CARRIERS_MODULE = 2
```





* Source: [classes/Carrier.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L34).


### <a name="constant-CARRIERS_MODULE_NEED_RANGE"></a>CARRIERS_MODULE_NEED_RANGE

```php
const CARRIERS_MODULE_NEED_RANGE = 3
```





* Source: [classes/Carrier.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L35).


### <a name="constant-PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE"></a>PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE

```php
const PS_CARRIERS_AND_CARRIER_MODULES_NEED_RANGE = 4
```





* Source: [classes/Carrier.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L36).


### <a name="constant-PS_CARRIERS_ONLY"></a>PS_CARRIERS_ONLY

```php
const PS_CARRIERS_ONLY = 1
```

getCarriers method filter



* Source: [classes/Carrier.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L33).


### <a name="constant-SHIPPING_METHOD_DEFAULT"></a>SHIPPING_METHOD_DEFAULT

```php
const SHIPPING_METHOD_DEFAULT = 0
```





* Source: [classes/Carrier.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L39).


### <a name="constant-SHIPPING_METHOD_FREE"></a>SHIPPING_METHOD_FREE

```php
const SHIPPING_METHOD_FREE = 3
```





* Source: [classes/Carrier.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L42).


### <a name="constant-SHIPPING_METHOD_PRICE"></a>SHIPPING_METHOD_PRICE

```php
const SHIPPING_METHOD_PRICE = 2
```





* Source: [classes/Carrier.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L41).


### <a name="constant-SHIPPING_METHOD_WEIGHT"></a>SHIPPING_METHOD_WEIGHT

```php
const SHIPPING_METHOD_WEIGHT = 1
```





* Source: [classes/Carrier.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L40).


### <a name="constant-SORT_BY_ASC"></a>SORT_BY_ASC

```php
const SORT_BY_ASC = 0
```





* Source: [classes/Carrier.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L47).


### <a name="constant-SORT_BY_DESC"></a>SORT_BY_DESC

```php
const SORT_BY_DESC = 1
```





* Source: [classes/Carrier.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L48).


### <a name="constant-SORT_BY_POSITION"></a>SORT_BY_POSITION

```php
const SORT_BY_POSITION = 1
```





* Source: [classes/Carrier.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L45).


### <a name="constant-SORT_BY_PRICE"></a>SORT_BY_PRICE

```php
const SORT_BY_PRICE = 0
```





* Source: [classes/Carrier.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L44).


Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Carrier.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L66).


### <a name="property-$cache_tax_rule"></a>$cache_tax_rule

```php
protected mixed $cache_tax_rule = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L154).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'carrier', 'primary' => 'id_carrier', 'multilang' => true, 'multishop' => true, 'fields' => array('id_reference' => array('type' => self::TYPE_INT), 'id_tax_rules_group' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isCarrierName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'is_free' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'url' => array('type' => self::TYPE_STRING, 'validate' => 'isAbsoluteUrl'), 'shipping_handling' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shipping_external' => array('type' => self::TYPE_BOOL), 'range_behavior' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'shipping_method' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_width' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_height' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_depth' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'max_weight' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'grade' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'size' => 1), 'external_module_name' => array('type' => self::TYPE_STRING, 'size' => 64), 'is_module' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'need_range' => array('type' => self::TYPE_BOOL), 'position' => array('type' => self::TYPE_INT), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'delay' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Carrier.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L116).


### <a name="property-$delay"></a>$delay

```php
public string $delay
```





* Visibility: **public**
* Source: [classes/Carrier.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L63).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Carrier.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L69).


### <a name="property-$external_module_name"></a>$external_module_name

```php
public string $external_module_name = null
```





* Visibility: **public**
* Source: [classes/Carrier.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L90).


### <a name="property-$grade"></a>$grade

```php
public integer $grade
```





* Visibility: **public**
* Source: [classes/Carrier.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L111).


### <a name="property-$id_reference"></a>$id_reference

```php
public integer $id_reference
```





* Visibility: **public**
* Source: [classes/Carrier.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L54).


### <a name="property-$id_tax_rules_group"></a>$id_tax_rules_group

```php
public integer $id_tax_rules_group
```





* Visibility: **public**
* Source: [classes/Carrier.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L51).


### <a name="property-$is_free"></a>$is_free

```php
public boolean $is_free = false
```





* Visibility: **public**
* Source: [classes/Carrier.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L81).


### <a name="property-$is_module"></a>$is_module

```php
public boolean $is_module
```





* Visibility: **public**
* Source: [classes/Carrier.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L78).


### <a name="property-$max_depth"></a>$max_depth

```php
public integer $max_depth
```





* Visibility: **public**
* Source: [classes/Carrier.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L105).


### <a name="property-$max_height"></a>$max_height

```php
public integer $max_height
```





* Visibility: **public**
* Source: [classes/Carrier.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L102).


### <a name="property-$max_weight"></a>$max_weight

```php
public integer $max_weight
```





* Visibility: **public**
* Source: [classes/Carrier.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L108).


### <a name="property-$max_width"></a>$max_width

```php
public integer $max_width
```





* Visibility: **public**
* Source: [classes/Carrier.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L99).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Carrier.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L57).


### <a name="property-$need_range"></a>$need_range

```php
public boolean $need_range
```





* Visibility: **public**
* Source: [classes/Carrier.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L93).


### <a name="property-$position"></a>$position

```php
public integer $position
```





* Visibility: **public**
* Source: [classes/Carrier.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L96).


### <a name="property-$price_by_price"></a>$price_by_price

```php
protected mixed $price_by_price = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L151).


### <a name="property-$price_by_price2"></a>$price_by_price2

```php
protected mixed $price_by_price2 = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L152).


### <a name="property-$price_by_weight"></a>$price_by_weight

```php
protected mixed $price_by_weight = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L149).


### <a name="property-$price_by_weight2"></a>$price_by_weight2

```php
protected mixed $price_by_weight2 = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Carrier.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L150).


### <a name="property-$range_behavior"></a>$range_behavior

```php
public integer $range_behavior
```





* Visibility: **public**
* Source: [classes/Carrier.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L75).


### <a name="property-$shipping_external"></a>$shipping_external

```php
public boolean $shipping_external
```





* Visibility: **public**
* Source: [classes/Carrier.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L87).


### <a name="property-$shipping_handling"></a>$shipping_handling

```php
public boolean $shipping_handling = true
```





* Visibility: **public**
* Source: [classes/Carrier.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L72).


### <a name="property-$shipping_method"></a>$shipping_method

```php
public integer $shipping_method
```





* Visibility: **public**
* Source: [classes/Carrier.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L84).


### <a name="property-$url"></a>$url

```php
public string $url
```





* Visibility: **public**
* Source: [classes/Carrier.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L60).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_tax_rules_group' => array(), 'deleted' => array(), 'is_module' => array()))
```





* Visibility: **protected**
* Source: [classes/Carrier.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L156).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L97).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L48).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L53).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L108).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L111).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L102).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CarrierCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L164)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed CarrierCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L171)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addDeliveryPrice"></a>addDeliveryPrice

```php
boolean CarrierCore::addDeliveryPrice($price_list, \Shop $shop)
```

Add new delivery prices



* Visibility: **public**
* Source: [classes/Carrier.php line 691](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L691)


#### Arguments
* $price_list **mixed**
* $shop **[Shop](class.ShopCore.md)** - Optionnal



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 961](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L961)


#### Arguments
* $fields **mixed**



### <a name="method-addZone"></a>addZone

```php
mixed CarrierCore::addZone($id_zone)
```

Add zone



* Visibility: **public**
* Source: [classes/Carrier.php line 628](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L628)


#### Arguments
* $id_zone **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1009](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1009)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-checkCarrierZone"></a>checkCarrierZone

```php
mixed CarrierCore::checkCarrierZone($id_carrier, $id_zone)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 582](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L582)


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
* Source: [classes/Carrier.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L316)


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
* Source: [classes/Carrier.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L239)


#### Arguments
* $id_carrier **mixed**
* $total_weight **mixed**
* $id_zone **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-cleanPositions"></a>cleanPositions

```php
boolean CarrierCore::cleanPositions()
```

Reorders carrier positions.

Called after deleting a carrier.

* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 984](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L984)




### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L975)


#### Arguments
* $all **mixed**



### <a name="method-copyCarrierData"></a>copyCarrierData

```php
mixed CarrierCore::copyCarrierData($old_id)
```

Copy old carrier informations when update carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 737](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L737)


#### Arguments
* $old_id **mixed**



### <a name="method-delete"></a>delete

```php
mixed CarrierCore::delete()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L192)




### <a name="method-deleteDeliveryPrice"></a>deleteDeliveryPrice

```php
boolean CarrierCore::deleteDeliveryPrice($range_table, \Shop $shop)
```

Clean delivery prices (weight/price)



* Visibility: **public**
* Source: [classes/Carrier.php line 666](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L666)


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
* Source: [classes/ObjectModel.php line 1079](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1079)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 553](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L553)


#### Arguments
* $selection **array**



### <a name="method-deleteZone"></a>deleteZone

```php
mixed CarrierCore::deleteZone($id_zone)
```

Delete zone



* Visibility: **public**
* Source: [classes/Carrier.php line 638](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L638)


#### Arguments
* $id_zone **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $className, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 740](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L740)


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
* Source: [classes/ObjectModel.php line 1049](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1049)


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
* Source: [classes/ObjectModel.php line 1113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1113)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L272)


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
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L319)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAvailableCarrierList"></a>getAvailableCarrierList

```php
array CarrierCore::getAvailableCarrierList(\Product $product, $id_warehouse, $id_address_delivery, $id_shop)
```

For a given {product, warehouse}, gets the carrier available



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1026](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L1026)


#### Arguments
* $product **[Product](class.ProductCore.md)** - The id of the product, or an array with at least the package size and weight
* $id_warehouse **mixed**
* $id_address_delivery **mixed**
* $id_shop **mixed**



### <a name="method-getCarrierByReference"></a>getCarrierByReference

```php
mixed CarrierCore::getCarrierByReference($id_reference)
```

Get carrier using the reference id



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 794](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L794)


#### Arguments
* $id_reference **mixed**



### <a name="method-getCarriers"></a>getCarriers

```php
array CarrierCore::getCarriers(integer $id_lang, boolean $active, $delete, $id_zone, $ids_group, $modules_filters)
```

Get all carriers in a given language



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 387](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L387)


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
* Source: [classes/Carrier.php line 507](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L507)


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
* Source: [classes/Carrier.php line 485](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L485)


#### Arguments
* $carriers **array**
* $default_carrier **mixed**



### <a name="method-getDefinition"></a>getDefinition

```php
mixed ObjectModelCore::getDefinition($class, $field)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1209](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1209)


#### Arguments
* $class **mixed**
* $field **mixed**



### <a name="method-getDeliveredCountries"></a>getDeliveredCountries

```php
mixed CarrierCore::getDeliveredCountries($id_lang, $active_countries, $active_carriers, $contain_states)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 447](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L447)


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
* Source: [classes/Carrier.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L281)


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
* Source: [classes/Carrier.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L360)


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
* Source: [classes/Carrier.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L216)


#### Arguments
* $total_weight **mixed**
* $id_zone **integer** - Zone id (for customer delivery address)
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getEntity"></a>getEntity

```php
mixed ObjectModelCore::getEntity($entity)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1269](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1269)


#### Arguments
* $entity **mixed**



### <a name="method-getFields"></a>getFields

```php
array ObjectModelCore::getFields()
```

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval.

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L234)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L249)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 953](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L953)


#### Arguments
* $all **mixed**



### <a name="method-getGroups"></a>getGroups

```php
array CarrierCore::getGroups()
```

Gets a specific group



* Visibility: **public**
* Source: [classes/Carrier.php line 652](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L652)




### <a name="method-getHigherPosition"></a>getHigherPosition

```php
integer CarrierCore::getHigherPosition()
```

Gets the highest carrier position



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 1010](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L1010)




### <a name="method-getIdTaxRulesGroupByIdCarrier"></a>getIdTaxRulesGroupByIdCarrier

```php
mixed CarrierCore::getIdTaxRulesGroupByIdCarrier(integer $id_carrier)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 872](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L872)


#### Arguments
* $id_carrier **integer**



### <a name="method-getMaxDeliveryPriceByPrice"></a>getMaxDeliveryPriceByPrice

```php
mixed CarrierCore::getMaxDeliveryPriceByPrice($id_zone, \Shop $shop)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L339)


#### Arguments
* $id_zone **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getMaxDeliveryPriceByWeight"></a>getMaxDeliveryPriceByWeight

```php
mixed CarrierCore::getMaxDeliveryPriceByWeight($id_zone, \Shop $shop)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L259)


#### Arguments
* $id_zone **mixed**
* $shop **[Shop](class.ShopCore.md)**



### <a name="method-getRangeObject"></a>getRangeObject

```php
mixed CarrierCore::getRangeObject()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 848](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L848)




### <a name="method-getRangeSuffix"></a>getRangeSuffix

```php
mixed CarrierCore::getRangeSuffix($currency)
```





* Visibility: **public**
* Source: [classes/Carrier.php line 858](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L858)


#### Arguments
* $currency **mixed**



### <a name="method-getRangeTable"></a>getRangeTable

```php
mixed CarrierCore::getRangeTable()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 838](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L838)




### <a name="method-getShippingMethod"></a>getShippingMethod

```php
mixed CarrierCore::getShippingMethod()
```





* Visibility: **public**
* Source: [classes/Carrier.php line 819](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L819)




### <a name="method-getTaxesRate"></a>getTaxesRate

```php
 CarrierCore::getTaxesRate(\Address $address)
```

Returns the taxes rate associated to the carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 893](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L893)


#### Arguments
* $address **[Address](class.AddressCore.md)**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fieldsArray)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 589](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L589)


#### Arguments
* $fieldsArray **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
array ObjectModelCore::getValidationRules(string $className)
```

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L130)


#### Arguments
* $className **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 929](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L929)


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
* Source: [classes/ObjectModel.php line 799](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L799)


#### Arguments
* $wsParamsAttributeName **mixed**



### <a name="method-getZone"></a>getZone

```php
array CarrierCore::getZone($id_zone)
```

Get a specific zones



* Visibility: **public**
* Source: [classes/Carrier.php line 616](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L616)


#### Arguments
* $id_zone **mixed**



### <a name="method-getZones"></a>getZones

```php
array CarrierCore::getZones()
```

Get all zones



* Visibility: **public**
* Source: [classes/Carrier.php line 602](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L602)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1148)


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
* Source: [classes/ObjectModel.php line 1167](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1167)


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
* Source: [classes/ObjectModel.php line 1035](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1035)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 990](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L990)


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
* Source: [classes/ObjectModel.php line 1131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1131)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1069](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1069)




### <a name="method-isUsed"></a>isUsed

```php
integer CarrierCore::isUsed()
```

Check if carrier is used (at least one order placed)



* Visibility: **public**
* Source: [classes/Carrier.php line 809](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L809)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fieldsArray, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L605)


#### Arguments
* $fields **mixed**
* $fieldsArray **mixed**
* $id_language **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L360)


#### Arguments
* $null_values **boolean**
* $autodate **boolean**



### <a name="method-setConfiguration"></a>setConfiguration

```php
mixed CarrierCore::setConfiguration(integer $id_old)
```

Change carrier id in delivery prices when updating a carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L204)


#### Arguments
* $id_old **integer** - Old id carrier



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

```php
mixed ObjectModelCore::setDefinitionRetrocompatibility()
```

Retrocompatibility for classes without $definition static
Remove this in 1.6 !



* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1224](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L1224)




### <a name="method-sqlDeliveryRangeShop"></a>sqlDeliveryRangeShop

```php
string CarrierCore::sqlDeliveryRangeShop($range_table, \Shop $shop, $alias)
```

This tricky method generates a sql clause to check if ranged data are overloaded by multishop



* Visibility: **public**
* This method is **static**.
* Source: [classes/Carrier.php line 908](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L908)


#### Arguments
* $range_table **mixed**
* $shop **[Shop](class.ShopCore.md)**
* $alias **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L569)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L444)


#### Arguments
* $null_values **boolean**



### <a name="method-updatePosition"></a>updatePosition

```php
boolean CarrierCore::updatePosition(boolean $way, integer $position)
```

Moves a carrier



* Visibility: **public**
* Source: [classes/Carrier.php line 944](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Carrier.php#L944)


#### Arguments
* $way **boolean** - Up (1) or Down (0)
* $position **integer**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L753)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L759)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 704](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L704)


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
* Source: [classes/ObjectModel.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L643)


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
* Source: [classes/ObjectModel.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/ObjectModel.php#L669)


#### Arguments
* $die **boolean**
* $error_return **boolean**


