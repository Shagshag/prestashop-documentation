Class TaxRuleCore
=====================





* Class name: TaxRuleCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/tax/TaxRule.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L28)


Contents
--------


### Properties

* [$behavior](#property-$behavior)
* [$definition](#property-$definition)
* [$description](#property-$description)
* [$id_country](#property-$id_country)
* [$id_state](#property-$id_state)
* [$id_tax](#property-$id_tax)
* [$id_tax_rules_group](#property-$id_tax_rules_group)
* [$webserviceParameters](#property-$webserviceParameters)
* [$zipcode_from](#property-$zipcode_from)
* [$zipcode_to](#property-$zipcode_to)
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
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [breakDownZipCode](#method-breakDownZipCode)
* [clearCache](#method-clearCache)
* [delete](#method-delete)
* [deleteByGroupId](#method-deleteByGroupId)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [deleteTaxRuleByIdCounty](#method-deleteTaxRuleByIdCounty)
* [deleteTaxRuleByIdTax](#method-deleteTaxRuleByIdTax)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getTaxRulesByGroupId](#method-getTaxRulesByGroupId)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToGroupShop](#method-isAssociatedToGroupShop)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [isTaxInUse](#method-isTaxInUse)
* [makeTranslationFields](#method-makeTranslationFields)
* [retrieveById](#method-retrieveById)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [swapTaxId](#method-swapTaxId)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)




Properties
----------


### <a name="property-$behavior"></a>$behavior

```php
public mixed $behavior
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L36).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'tax_rule', 'primary' => 'id_tax_rule', 'fields' => array('id_tax_rules_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'zipcode_from' => array('type' => self::TYPE_INT, 'validate' => 'isPostCode'), 'zipcode_to' => array('type' => self::TYPE_INT, 'validate' => 'isPostCode'), 'id_tax' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'behavior' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'description' => array('type' => self::TYPE_STRING, 'validate' => 'isString')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/tax/TaxRule.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L42).


### <a name="property-$description"></a>$description

```php
public mixed $description
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L37).


### <a name="property-$id_country"></a>$id_country

```php
public mixed $id_country
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L31).


### <a name="property-$id_state"></a>$id_state

```php
public mixed $id_state
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L32).


### <a name="property-$id_tax"></a>$id_tax

```php
public mixed $id_tax
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L35).


### <a name="property-$id_tax_rules_group"></a>$id_tax_rules_group

```php
public mixed $id_tax_rules_group
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L30).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_tax_rules_group' => array('xlink_resource' => 'tax_rule_groups'), 'id_state' => array('xlink_resource' => 'states'), 'id_country' => array('xlink_resource' => 'countries')))
```





* Visibility: **protected**
* Source: [classes/tax/TaxRule.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L57).


### <a name="property-$zipcode_from"></a>$zipcode_from

```php
public mixed $zipcode_from
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L33).


### <a name="property-$zipcode_to"></a>$zipcode_to

```php
public mixed $zipcode_to
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L34).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L97).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L48).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L53).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L108).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L111).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L102).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L150)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **integer** - ID shop for objects with multishop on langs



### <a name="method-add"></a>add

```php
boolean ObjectModelCore::add(boolean $autodate, boolean $null_values)
```

Add current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L372)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L925)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 973](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L973)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-breakDownZipCode"></a>breakDownZipCode

```php
array TaxRuleCore::breakDownZipCode($zip_codes)
```





* Visibility: **public**
* Source: [classes/tax/TaxRule.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L136)


#### Arguments
* $zip_codes **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L939)


#### Arguments
* $all **mixed**



### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Delete current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 521](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L521)




### <a name="method-deleteByGroupId"></a>deleteByGroupId

```php
mixed TaxRuleCore::deleteByGroupId($id_group)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L65)


#### Arguments
* $id_group **mixed**



### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1047](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1047)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L559)


#### Arguments
* $selection **array**



### <a name="method-deleteTaxRuleByIdCounty"></a>deleteTaxRuleByIdCounty

```php
mixed TaxRuleCore::deleteTaxRuleByIdCounty($id_county)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L114)


#### Arguments
* $id_county **mixed**



### <a name="method-deleteTaxRuleByIdTax"></a>deleteTaxRuleByIdTax

```php
mixed TaxRuleCore::deleteTaxRuleByIdTax($id_tax)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L102)


#### Arguments
* $id_tax **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 757](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L757)


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
* Source: [classes/ObjectModel.php line 1017](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1017)


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
* Source: [classes/ObjectModel.php line 1081](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1081)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L272)


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
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L319)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1184](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1184)


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
* Source: [classes/ObjectModel.php line 1261](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1261)


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
* Source: [classes/ObjectModel.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L234)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L249)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 917](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L917)


#### Arguments
* $all **mixed**



### <a name="method-getTaxRulesByGroupId"></a>getTaxRulesByGroupId

```php
mixed TaxRuleCore::getTaxRulesByGroupId($id_lang, $id_group)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L83)


#### Arguments
* $id_lang **mixed**
* $id_group **mixed**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 595](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L595)


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
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L130)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L890)


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
* Source: [classes/ObjectModel.php line 816](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L816)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1116)


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
* Source: [classes/ObjectModel.php line 1135](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1135)


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
* Source: [classes/ObjectModel.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1003)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 954](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L954)


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
* Source: [classes/ObjectModel.php line 1099](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1099)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1037](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1037)




### <a name="method-isTaxInUse"></a>isTaxInUse

```php
boolean TaxRuleCore::isTaxInUse(integer $id_tax)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L124)


#### Arguments
* $id_tax **integer**



### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L611)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-retrieveById"></a>retrieveById

```php
mixed TaxRuleCore::retrieveById($id_tax_rule)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L76)


#### Arguments
* $id_tax_rule **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L360)


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
* Source: [classes/ObjectModel.php line 1207](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L1207)




### <a name="method-swapTaxId"></a>swapTaxId

```php
mixed TaxRuleCore::swapTaxId(integer $old_id, integer $new_id)
```

Replace a tax_rule id by an other one in the tax_rule table



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRule.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/tax/TaxRule.php#L172)


#### Arguments
* $old_id **integer**
* $new_id **integer**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L575)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 446](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L446)


#### Arguments
* $null_values **boolean**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L772)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 778](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L778)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 710](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L710)


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
* Source: [classes/ObjectModel.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L649)


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
* Source: [classes/ObjectModel.php line 675](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/ObjectModel.php#L675)


#### Arguments
* $die **boolean**
* $error_return **boolean**

