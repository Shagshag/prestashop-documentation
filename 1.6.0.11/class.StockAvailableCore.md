Class StockAvailableCore
=====================

Represents quantities available
It is either synchronized with Stock or manualy set by the seller



* Class name: StockAvailableCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/StockAvailable.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L33)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$depends_on_stock](#property-$depends_on_stock)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$out_of_stock](#property-$out_of_stock)
* [$quantity](#property-$quantity)
* [$webserviceParameters](#property-$webserviceParameters)
* [$db](#property-$db)
* [$def](#property-$def)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$force_id](#property-$force_id)
* [$get_shop_from_context](#property-$get_shop_from_context)
* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop_list](#property-$id_shop_list)
* [$identifier](#property-$identifier)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$loaded_classes](#property-$loaded_classes)
* [$table](#property-$table)
* [$tables](#property-$tables)
* [$update_fields](#property-$update_fields)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [addSqlShopParams](#method-addSqlShopParams)
* [addSqlShopRestriction](#method-addSqlShopRestriction)
* [associateTo](#method-associateTo)
* [cacheFieldsRequiredDatabase](#method-cacheFieldsRequiredDatabase)
* [clearCache](#method-clearCache)
* [copyStockAvailableFromShopToShop](#method-copyStockAvailableFromShopToShop)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [dependsOnStock](#method-dependsOnStock)
* [displayFieldName](#method-displayFieldName)
* [duplicateObject](#method-duplicateObject)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAssociatedShops](#method-getAssociatedShops)
* [getDefinition](#method-getDefinition)
* [getFieldByLang](#method-getFieldByLang)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getFieldsShop](#method-getFieldsShop)
* [getQuantityAvailableByProduct](#method-getQuantityAvailableByProduct)
* [getStockAvailableIdByProductId](#method-getStockAvailableIdByProductId)
* [getTranslationsFields](#method-getTranslationsFields)
* [getValidationRules](#method-getValidationRules)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isLangMultishop](#method-isLangMultishop)
* [isMultiShopField](#method-isMultiShopField)
* [isMultishop](#method-isMultishop)
* [makeTranslationFields](#method-makeTranslationFields)
* [outOfStock](#method-outOfStock)
* [postSave](#method-postSave)
* [removeProductFromStockAvailable](#method-removeProductFromStockAvailable)
* [resetProductFromStockAvailableByShopGroup](#method-resetProductFromStockAvailableByShopGroup)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [setProductDependsOnStock](#method-setProductDependsOnStock)
* [setProductOutOfStock](#method-setProductOutOfStock)
* [setQuantity](#method-setQuantity)
* [synchronize](#method-synchronize)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [updateMultishopTable](#method-updateMultishopTable)
* [updateQuantity](#method-updateQuantity)
* [updateWs](#method-updateWs)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'stock_available', 'primary' => 'id_stock_available', 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_product_attribute' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_shop_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'depends_on_stock' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'out_of_stock' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/StockAvailable.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L59).


### <a name="property-$depends_on_stock"></a>$depends_on_stock

```php
public boolean $depends_on_stock = false
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L51).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L36).


### <a name="property-$id_product_attribute"></a>$id_product_attribute

```php
public integer $id_product_attribute
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L39).


### <a name="property-$id_shop"></a>$id_shop

```php
public integer $id_shop
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L42).


### <a name="property-$id_shop_group"></a>$id_shop_group

```php
public integer $id_shop_group
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L45).


### <a name="property-$out_of_stock"></a>$out_of_stock

```php
public boolean $out_of_stock = false
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L54).


### <a name="property-$quantity"></a>$quantity

```php
public integer $quantity
```





* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L48).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_product' => array('xlink_resource' => 'products'), 'id_product_attribute' => array('xlink_resource' => 'combinations'), 'id_shop' => array('xlink_resource' => 'shops'), 'id_shop_group' => array('xlink_resource' => 'shop_groups')), 'hidden_fields' => array(), 'objectMethods' => array('add' => 'addWs', 'update' => 'updateWs'))
```





* Visibility: **protected**
* Source: [classes/stock/StockAvailable.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L76).


### <a name="property-$db"></a>$db

```php
protected \Db $db = false
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L143).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L133).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L81).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L66).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L96).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L86).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L101).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L91).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L106).


### <a name="property-$force_id"></a>$force_id

```php
public \boolean, $force_id = false
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L148).


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

```php
protected mixed $get_shop_from_context = true
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L64).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L55).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L58).


### <a name="property-$id_shop_list"></a>$id_shop_list

```php
public mixed $id_shop_list = null
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L62).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L76).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L117).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L120).


### <a name="property-$loaded_classes"></a>$loaded_classes

```php
protected mixed $loaded_classes = array()
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L128).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L71).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L111).


### <a name="property-$update_fields"></a>$update_fields

```php
protected array $update_fields = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L138).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 176](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L176)


#### Arguments
* $id **integer** - Existing object id in order to load object (optional)
* $id_lang **integer** - Required if object is multilingual (optional)
* $id_shop **integer** - ID shop for objects with multishop on langs



### <a name="method-add"></a>add

```php
mixed StockAvailableCore::add($autodate, $null_values)
```

Upgrades total_quantity_available after having saved



* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 370](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L370)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1238](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1238)


#### Arguments
* $fields **mixed**



### <a name="method-addSqlShopParams"></a>addSqlShopParams

```php
mixed StockAvailableCore::addSqlShopParams(array $params, integer $id_shop)
```

Add sql params for shops fields - specific to StockAvailable



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 762](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L762)


#### Arguments
* $params **array** - Reference to the params array
* $id_shop **integer** - Optional : The shop ID



### <a name="method-addSqlShopRestriction"></a>addSqlShopRestriction

```php
mixed StockAvailableCore::addSqlShopRestriction(\DbQuery $sql, $shop, string $alias)
```

Add an sql restriction for shops fields - specific to StockAvailable



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 699](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L699)


#### Arguments
* $sql **[DbQuery](class.DbQueryCore.md)**
* $shop **mixed**
* $alias **string** - Optional : The current table alias



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1290](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1290)


#### Arguments
* $id_shops **integer|array**



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

```php
mixed ObjectModelCore::cacheFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1225](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1225)


#### Arguments
* $all **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1252](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1252)


#### Arguments
* $all **mixed**



### <a name="method-copyStockAvailableFromShopToShop"></a>copyStockAvailableFromShopToShop

```php
boolean StockAvailableCore::copyStockAvailableFromShopToShop(integer $src_shop_id, integer $dst_shop_id)
```

Copies stock available content table



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 808](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L808)


#### Arguments
* $src_shop_id **integer**
* $dst_shop_id **integer**



### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Delete current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 717](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L717)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage($force_delete)
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1421](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1421)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 763](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L763)


#### Arguments
* $selection **array**



### <a name="method-dependsOnStock"></a>dependsOnStock

```php
boolean StockAvailableCore::dependsOnStock(integer $id_product, integer $id_shop)
```

For a given product, tells if it depends on the physical (usable) stock



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 651](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L651)


#### Arguments
* $id_product **integer**
* $id_shop **integer** - Optional : gets context if null @see Context::getContext()



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $class, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1008](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1008)


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
* Source: [classes/ObjectModel.php line 543](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L543)




### <a name="method-duplicateShops"></a>duplicateShops

```php
mixed ObjectModelCore::duplicateShops($id)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1334](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1334)


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
* Source: [classes/ObjectModel.php line 1458](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1458)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $type, integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 342](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L342)


#### Arguments
* $type **integer** - FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP
* $id_lang **integer** - If this parameter is given, only take lang fields



### <a name="method-formatValue"></a>formatValue

```php
mixed ObjectModelCore::formatValue(mixed $value, integer $type, $with_quotes, $purify)
```

Format a data



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 389](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L389)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**
* $purify **mixed**



### <a name="method-getAssociatedShops"></a>getAssociatedShops

```php
array ObjectModelCore::getAssociatedShops()
```

Get the list of associated id_shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1319](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1319)




### <a name="method-getDefinition"></a>getDefinition

```php
array ObjectModelCore::getDefinition(string $class, string $field)
```

Get object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1564](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1564)


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
* Source: [classes/ObjectModel.php line 1671](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1671)


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
* Source: [classes/ObjectModel.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L270)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L307)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1217](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1217)


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
* Source: [classes/ObjectModel.php line 293](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L293)




### <a name="method-getQuantityAvailableByProduct"></a>getQuantityAvailableByProduct

```php
integer StockAvailableCore::getQuantityAvailableByProduct(integer $id_product, integer $id_product_attribute, integer $id_shop)
```

For a given id_product and id_product_attribute, gets its stock available



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 341](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L341)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $id_shop **integer** - Optional : gets context by default



### <a name="method-getStockAvailableIdByProductId"></a>getStockAvailableIdByProductId

```php
mixed StockAvailableCore::getStockAvailableIdByProductId($id_product, $id_product_attribute, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L107)


#### Arguments
* $id_product **mixed**
* $id_product_attribute **mixed**
* $id_shop **mixed**



### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fields_array)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 798](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L798)


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
* Source: [classes/ObjectModel.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L156)


#### Arguments
* $class **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1158)


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
* Source: [classes/ObjectModel.php line 1080](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1080)


#### Arguments
* $ws_params_attribute_name **mixed**



### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

```php
boolean ObjectModelCore::hasMultishopEntries()
```

Check if there is more than one entries in associated shop table for current entity



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1359](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1359)




### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1496](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1496)


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
* Source: [classes/ObjectModel.php line 1515](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1515)


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
* Source: [classes/ObjectModel.php line 1267](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1267)


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
* Source: [classes/ObjectModel.php line 1476](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1476)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1376](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1376)




### <a name="method-isMultiShopField"></a>isMultiShopField

```php
mixed ObjectModelCore::isMultiShopField($field)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1371](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1371)


#### Arguments
* $field **mixed**



### <a name="method-isMultishop"></a>isMultishop

```php
mixed ObjectModelCore::isMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1366](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1366)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fields_array, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 814](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L814)


#### Arguments
* $fields **mixed**
* $fields_array **mixed**
* $id_language **mixed**



### <a name="method-outOfStock"></a>outOfStock

```php
boolean StockAvailableCore::outOfStock(integer $id_product, integer $id_shop)
```

For a given product, get its "out of stock" flag



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 674](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L674)


#### Arguments
* $id_product **integer**
* $id_shop **integer** - Optional : gets context if null @see Context::getContext()



### <a name="method-postSave"></a>postSave

```php
mixed StockAvailableCore::postSave()
```

Upgrades total_quantity_available after having saved



* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 397](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L397)




### <a name="method-removeProductFromStockAvailable"></a>removeProductFromStockAvailable

```php
mixed StockAvailableCore::removeProductFromStockAvailable(integer $id_product, integer $id_product_attribute, $shop)
```

Removes a given product from the stock available



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L559)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $shop **mixed**



### <a name="method-resetProductFromStockAvailableByShopGroup"></a>resetProductFromStockAvailableByShopGroup

```php
mixed StockAvailableCore::resetProductFromStockAvailableByShopGroup(\ShopGroup $shop_group)
```

Removes all product quantities from all a group of shops
If stocks are shared, remoe all old available quantities for all shops of the group
Else remove all available quantities for the current group



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 619](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L619)


#### Arguments
* $shop_group **[ShopGroup](class.ShopGroupCore.md)** - the ShopGroup object



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L440)


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
* Source: [classes/ObjectModel.php line 1602](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1602)




### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

```php
mixed ObjectModelCore::setFieldsToUpdate(array $fields)
```

Set a list of specific fields to update
array(field1 => true, field2 => false, langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1697](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1697)


#### Arguments
* $fields **array**



### <a name="method-setProductDependsOnStock"></a>setProductDependsOnStock

```php
mixed StockAvailableCore::setProductDependsOnStock(integer $id_product, integer $depends_on_stock, integer $id_shop, $id_product_attribute)
```

For a given id_product, sets if stock available depends on stock



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L267)


#### Arguments
* $id_product **integer**
* $depends_on_stock **integer** - Optional : true by default
* $id_shop **integer** - Optional : gets context by default
* $id_product_attribute **mixed**



### <a name="method-setProductOutOfStock"></a>setProductOutOfStock

```php
mixed StockAvailableCore::setProductOutOfStock(integer $id_product, integer $out_of_stock, integer $id_shop, $id_product_attribute)
```

For a given id_product, sets if product is available out of stocks



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 304](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L304)


#### Arguments
* $id_product **integer**
* $out_of_stock **integer** - Optional false by default
* $id_shop **integer** - Optional gets context by default
* $id_product_attribute **mixed**



### <a name="method-setQuantity"></a>setQuantity

```php
mixed StockAvailableCore::setQuantity(integer $id_product, integer $id_product_attribute, $quantity, integer $id_shop)
```

For a given id_product and id_product_attribute sets the quantity available



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 488](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L488)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $quantity **mixed**
* $id_shop **integer** - Optional



### <a name="method-synchronize"></a>synchronize

```php
mixed StockAvailableCore::synchronize(integer $id_product, $order_id_shop)
```

For a given id_product, synchronizes StockAvailable::quantity with Stock::usable_quantity



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L129)


#### Arguments
* $id_product **integer**
* $order_id_shop **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 779](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L779)




### <a name="method-update"></a>update

```php
mixed StockAvailableCore::update($null_values)
```

Upgrades total_quantity_available after having update



* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 383](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L383)


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
* Source: [classes/ObjectModel.php line 1391](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1391)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - Only executed for common table



### <a name="method-updateQuantity"></a>updateQuantity

```php
mixed StockAvailableCore::updateQuantity(integer $id_product, integer $id_product_attribute, integer $delta_quantity, integer $id_shop)
```

For a given id_product and id_product_attribute updates the quantity available



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockAvailable.php line 441](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L441)


#### Arguments
* $id_product **integer**
* $id_product_attribute **integer** - Optional
* $delta_quantity **integer** - The delta quantity to update
* $id_shop **integer** - Optional



### <a name="method-updateWs"></a>updateWs

```php
integer StockAvailableCore::updateWs()
```

For a given {id_product, id_product_attribute and id_shop}, gets the stock available id associated



* Visibility: **public**
* Source: [classes/stock/StockAvailable.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/stock/StockAvailable.php#L100)




### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1026](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1026)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1032](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1032)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang, $skip, $human_errors)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L925)


#### Arguments
* $field **string** - Field name
* $value **mixed** - Field value
* $id_lang **integer**
* $skip **mixed**
* $human_errors **mixed**



### <a name="method-validateFields"></a>validateFields

```php
boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)
```

Check for fields validity before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L852)


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
* Source: [classes/ObjectModel.php line 881](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L881)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

```php
mixed ObjectModelCore::validateFieldsRequiredDatabase($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1194](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/ObjectModel.php#L1194)


#### Arguments
* $htmlentities **mixed**


