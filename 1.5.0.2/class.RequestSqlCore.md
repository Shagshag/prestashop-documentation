Class RequestSqlCore
=====================





* Class name: RequestSqlCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/RequestSql.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L28)


Contents
--------


### Properties

* [$attributes](#property-$attributes)
* [$definition](#property-$definition)
* [$error_sql](#property-$error_sql)
* [$name](#property-$name)
* [$sql](#property-$sql)
* [$tested](#property-$tested)
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
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [associateTo](#method-associateTo)
* [attributExistInTable](#method-attributExistInTable)
* [checkedFrom](#method-checkedFrom)
* [checkedGroupBy](#method-checkedGroupBy)
* [checkedHaving](#method-checkedHaving)
* [checkedLimit](#method-checkedLimit)
* [checkedOrder](#method-checkedOrder)
* [checkedSelect](#method-checkedSelect)
* [checkedWhere](#method-checkedWhere)
* [clearCache](#method-clearCache)
* [cutAttribute](#method-cutAttribute)
* [cutJoin](#method-cutJoin)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [deleteSelection](#method-deleteSelection)
* [displayFieldName](#method-displayFieldName)
* [duplicateShops](#method-duplicateShops)
* [existsInDatabase](#method-existsInDatabase)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [getAttributesByTable](#method-getAttributesByTable)
* [getDefinition](#method-getDefinition)
* [getEntity](#method-getEntity)
* [getFields](#method-getFields)
* [getFieldsLang](#method-getFieldsLang)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [getRequestSql](#method-getRequestSql)
* [getRequestSqlById](#method-getRequestSqlById)
* [getTables](#method-getTables)
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
* [makeTranslationFields](#method-makeTranslationFields)
* [parsingSql](#method-parsingSql)
* [returnNameTable](#method-returnNameTable)
* [save](#method-save)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [testedRequired](#method-testedRequired)
* [testedUnauthorized](#method-testedUnauthorized)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [validateField](#method-validateField)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateParser](#method-validateParser)
* [validateSql](#method-validateSql)




Properties
----------


### <a name="property-$attributes"></a>$attributes

```php
public mixed $attributes = array('passwd' => '*******************', 'secure_key' => '*******************')
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L60).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'request_sql', 'primary' => 'id_request_sql', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 200), 'sql' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true, 'size' => 400)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/RequestSql.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L36).


### <a name="property-$error_sql"></a>$error_sql

```php
public mixed $error_sql = array()
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L63).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L30).


### <a name="property-$sql"></a>$sql

```php
public mixed $sql
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L31).


### <a name="property-$tested"></a>$tested

```php
public mixed $tested = array('required' => array('SELECT', 'FROM'), 'option' => array('WHERE', 'ORDER', 'LIMIT', 'HAVING', 'GROUP', 'UNION'), 'operator' => array('AND', '&&', 'BETWEEN', 'AND', 'BINARY', '&', '~', '|', '^', 'CASE', 'WHEN', 'END', 'DIV', '/', '<=>', '=', '>=', '>', 'IS', 'NOT', 'NULL', '<<', '<=', '<', 'LIKE', '-', '%', '!=', '<>', 'REGEXP', '!', '||', 'OR', '+', '>>', 'RLIKE', 'SOUNDS', '*', '-', 'XOR', 'IN'), 'function' => array('AVG', 'SUM', 'COUNT', 'MIN', 'MAX', 'STDDEV', 'STDDEV_SAMP', 'STDDEV_POP', 'VARIANCE', 'VAR_SAMP', 'VAR_POP', 'GROUP_CONCAT', 'BIT_AND', 'BIT_OR', 'BIT_XOR'), 'unauthorized' => array('DELETE', 'ALTER', 'INSERT', 'REPLACE', 'CREATE', 'TRUNCATE', 'OPTIMIZE', 'GRANT', 'REVOKE', 'SHOW', 'HANDLER', 'LOAD', 'ROLLBACK', 'SAVEPOINT', 'UNLOCK', 'INSTALL', 'UNINSTALL', 'ANALZYE', 'BACKUP', 'CHECK', 'CHECKSUM', 'REPAIR', 'RESTORE', 'CACHE', 'DESCRIBE', 'EXPLAIN', 'USE', 'HELP', 'SET', 'DUPLICATE', 'VALUES', 'INTO', 'RENAME', 'CALL', 'PROCEDURE', 'FUNCTION', 'DATABASE', 'SERVER', 'LOGFILE', 'DEFINER', 'RETURNS', 'EVENT', 'TABLESPACE', 'VIEW', 'TRIGGER', 'DATA', 'DO', 'PASSWORD', 'USER', 'PLUGIN', 'FLUSH', 'KILL', 'RESET', 'START', 'STOP', 'PURGE', 'EXECUTE', 'PREPARE', 'DEALLOCATE', 'LOCK', 'USING', 'DROP', 'FOR', 'UPDATE', 'BEGIN', 'BY', 'ALL', 'SHARE', 'MODE', 'TO', 'KEY', 'DISTINCTROW', 'DISTINCT', 'HIGH_PRIORITY', 'LOW_PRIORITY', 'DELAYED', 'IGNORE', 'FORCE', 'STRAIGHT_JOIN', 'SQL_SMALL_RESULT', 'SQL_BIG_RESULT', 'QUICK', 'SQL_BUFFER_RESULT', 'SQL_CACHE', 'SQL_NO_CACHE', 'SQL_CALC_FOUND_ROWS', 'WITH'))
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L45).


### <a name="property-$def"></a>$def

```php
protected array $def
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L122).


### <a name="property-$fieldsRequired"></a>$fieldsRequired

```php
protected mixed $fieldsRequired = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L72).


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

```php
protected mixed $fieldsRequiredDatabase = null
```





* Visibility: **protected**
* This property is **static**.
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L57).


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

```php
protected mixed $fieldsRequiredLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L87).


### <a name="property-$fieldsSize"></a>$fieldsSize

```php
protected mixed $fieldsSize = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L77).


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

```php
protected mixed $fieldsSizeLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L92).


### <a name="property-$fieldsValidate"></a>$fieldsValidate

```php
protected mixed $fieldsValidate = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L82).


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

```php
protected mixed $fieldsValidateLang = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L97).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L48).


### <a name="property-$id_lang"></a>$id_lang

```php
protected integer $id_lang = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L51).


### <a name="property-$id_shop"></a>$id_shop

```php
protected mixed $id_shop = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L53).


### <a name="property-$identifier"></a>$identifier

```php
protected mixed $identifier
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L67).


### <a name="property-$image_dir"></a>$image_dir

```php
protected string $image_dir = null
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L108).


### <a name="property-$image_format"></a>$image_format

```php
protected string $image_format = 'jpg'
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L111).


### <a name="property-$table"></a>$table

```php
protected mixed $table
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L62).


### <a name="property-$tables"></a>$tables

```php
protected mixed $tables = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L102).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected array $webserviceParameters = array()
```





* Visibility: **protected**
* This property is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L105).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ObjectModelCore::__construct(integer $id, integer $id_lang, integer $id_shop)
```

Build object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L150)


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
* Source: [classes/ObjectModel.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L372)


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

```php
mixed ObjectModelCore::addFieldsRequiredDatabase($fields)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 961](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L961)


#### Arguments
* $fields **mixed**



### <a name="method-associateTo"></a>associateTo

```php
boolean ObjectModelCore::associateTo(integer|array $id_shops, string $type)
```

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1009](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1009)


#### Arguments
* $id_shops **integer|array**
* $type **string**



### <a name="method-attributExistInTable"></a>attributExistInTable

```php
mixed RequestSqlCore::attributExistInTable($attr, $table)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L223)


#### Arguments
* $attr **mixed**
* $table **mixed**



### <a name="method-checkedFrom"></a>checkedFrom

```php
mixed RequestSqlCore::checkedFrom($from)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L256)


#### Arguments
* $from **mixed**



### <a name="method-checkedGroupBy"></a>checkedGroupBy

```php
mixed RequestSqlCore::checkedGroupBy($group, $from)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 463](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L463)


#### Arguments
* $group **mixed**
* $from **mixed**



### <a name="method-checkedHaving"></a>checkedHaving

```php
mixed RequestSqlCore::checkedHaving($having, $from)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 390](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L390)


#### Arguments
* $having **mixed**
* $from **mixed**



### <a name="method-checkedLimit"></a>checkedLimit

```php
mixed RequestSqlCore::checkedLimit($limit)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 493](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L493)


#### Arguments
* $limit **mixed**



### <a name="method-checkedOrder"></a>checkedOrder

```php
mixed RequestSqlCore::checkedOrder($order, $from)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 433](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L433)


#### Arguments
* $order **mixed**
* $from **mixed**



### <a name="method-checkedSelect"></a>checkedSelect

```php
mixed RequestSqlCore::checkedSelect($select, $from, $in)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L298)


#### Arguments
* $select **mixed**
* $from **mixed**
* $in **mixed**



### <a name="method-checkedWhere"></a>checkedWhere

```php
mixed RequestSqlCore::checkedWhere($where, $from, $sql)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 343](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L343)


#### Arguments
* $where **mixed**
* $from **mixed**
* $sql **mixed**



### <a name="method-clearCache"></a>clearCache

```php
mixed ObjectModelCore::clearCache($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L975)


#### Arguments
* $all **mixed**



### <a name="method-cutAttribute"></a>cutAttribute

```php
mixed RequestSqlCore::cutAttribute($attr, $from)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L173)


#### Arguments
* $attr **mixed**
* $from **mixed**



### <a name="method-cutJoin"></a>cutJoin

```php
mixed RequestSqlCore::cutJoin($attrs, $from)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L160)


#### Arguments
* $attrs **mixed**
* $from **mixed**



### <a name="method-delete"></a>delete

```php
boolean ObjectModelCore::delete()
```

Delete current object from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 517](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L517)




### <a name="method-deleteImage"></a>deleteImage

```php
boolean ObjectModelCore::deleteImage()
```

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1079](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1079)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean ObjectModelCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 553](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L553)


#### Arguments
* $selection **array**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed ObjectModelCore::displayFieldName($field, $className, $htmlentities, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 740](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L740)


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
* Source: [classes/ObjectModel.php line 1049](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1049)


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
* Source: [classes/ObjectModel.php line 1113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1113)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-formatFields"></a>formatFields

```php
array ObjectModelCore::formatFields(integer $id_lang)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L272)


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
* Source: [classes/ObjectModel.php line 319](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L319)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **mixed**



### <a name="method-getAttributesByTable"></a>getAttributesByTable

```php
mixed RequestSqlCore::getAttributesByTable($table)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L155)


#### Arguments
* $table **mixed**



### <a name="method-getDefinition"></a>getDefinition

```php
mixed ObjectModelCore::getDefinition($class, $field)
```





* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1209](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1209)


#### Arguments
* $class **mixed**
* $field **mixed**



### <a name="method-getEntity"></a>getEntity

```php
mixed ObjectModelCore::getEntity($entity)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1269](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1269)


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
* Source: [classes/ObjectModel.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L234)




### <a name="method-getFieldsLang"></a>getFieldsLang

```php
array ObjectModelCore::getFieldsLang()
```

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L249)




### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

```php
mixed ObjectModelCore::getFieldsRequiredDatabase($all)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 953](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L953)


#### Arguments
* $all **mixed**



### <a name="method-getRequestSql"></a>getRequestSql

```php
mixed RequestSqlCore::getRequestSql()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/RequestSql.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L65)




### <a name="method-getRequestSqlById"></a>getRequestSqlById

```php
mixed RequestSqlCore::getRequestSqlById($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/RequestSql.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L75)


#### Arguments
* $id **mixed**



### <a name="method-getTables"></a>getTables

```php
mixed RequestSqlCore::getTables()
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L144)




### <a name="method-getTranslationsFields"></a>getTranslationsFields

```php
mixed ObjectModelCore::getTranslationsFields($fieldsArray)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 589](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L589)


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
* Source: [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L130)


#### Arguments
* $className **string** - Child class name for static use (optional)



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

```php
mixed ObjectModelCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 929](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L929)


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
* Source: [classes/ObjectModel.php line 799](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L799)


#### Arguments
* $wsParamsAttributeName **mixed**



### <a name="method-hydrate"></a>hydrate

```php
mixed ObjectModelCore::hydrate(array $data, integer $id_lang)
```

Fill an object with given data. Data must be an array with this syntax: array(objProperty => value, objProperty2 => value, etc.)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1148)


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
* Source: [classes/ObjectModel.php line 1167](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1167)


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
* Source: [classes/ObjectModel.php line 1035](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1035)


#### Arguments
* $id_group_shop **integer**



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

```php
boolean ObjectModelCore::isAssociatedToShop(integer $id_shop)
```

Check if current object is associated to a shop



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 990](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L990)


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
* Source: [classes/ObjectModel.php line 1131](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1131)


#### Arguments
* $table **string** - name of table linked to entity
* $has_active_column **boolean** - true if the table has an active column



### <a name="method-isLangMultishop"></a>isLangMultishop

```php
mixed ObjectModelCore::isLangMultishop()
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 1069](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1069)




### <a name="method-makeTranslationFields"></a>makeTranslationFields

```php
mixed ObjectModelCore::makeTranslationFields($fields, $fieldsArray, $id_language)
```





* Visibility: **protected**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L605)


#### Arguments
* $fields **mixed**
* $fieldsArray **mixed**
* $id_language **mixed**



### <a name="method-parsingSql"></a>parsingSql

```php
mixed RequestSqlCore::parsingSql($sql)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L80)


#### Arguments
* $sql **mixed**



### <a name="method-returnNameTable"></a>returnNameTable

```php
mixed RequestSqlCore::returnNameTable($alias, $tables)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L200)


#### Arguments
* $alias **mixed**
* $tables **mixed**



### <a name="method-save"></a>save

```php
boolean ObjectModelCore::save(boolean $null_values, boolean $autodate)
```

Save current object to database (add or update)



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L360)


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
* Source: [classes/ObjectModel.php line 1224](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L1224)




### <a name="method-testedRequired"></a>testedRequired

```php
mixed RequestSqlCore::testedRequired($tab)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L234)


#### Arguments
* $tab **mixed**



### <a name="method-testedUnauthorized"></a>testedUnauthorized

```php
mixed RequestSqlCore::testedUnauthorized($tab)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L245)


#### Arguments
* $tab **mixed**



### <a name="method-toggleStatus"></a>toggleStatus

```php
boolean ObjectModelCore::toggleStatus()
```

Toggle object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L569)




### <a name="method-update"></a>update

```php
boolean ObjectModelCore::update(boolean $null_values)
```

Update current object to database



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L444)


#### Arguments
* $null_values **boolean**



### <a name="method-validateControler"></a>validateControler

```php
mixed ObjectModelCore::validateControler($htmlentities)
```

TODO: refactor rename all calls to this to validateController



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L753)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateController"></a>validateController

```php
mixed ObjectModelCore::validateController($htmlentities)
```





* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 759](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L759)


#### Arguments
* $htmlentities **mixed**



### <a name="method-validateField"></a>validateField

```php
boolean|string ObjectModelCore::validateField(string $field, mixed $value, integer $id_lang)
```

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](class.ObjectModelCore.md).
* Source: [classes/ObjectModel.php line 704](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L704)


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
* Source: [classes/ObjectModel.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L643)


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
* Source: [classes/ObjectModel.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/ObjectModel.php#L669)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateParser"></a>validateParser

```php
mixed RequestSqlCore::validateParser($tab, $in, $sql)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L85)


#### Arguments
* $tab **mixed**
* $in **mixed**
* $sql **mixed**



### <a name="method-validateSql"></a>validateSql

```php
mixed RequestSqlCore::validateSql($tab, $in, $sql)
```





* Visibility: **public**
* Source: [classes/RequestSql.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/RequestSql.php#L103)


#### Arguments
* $tab **mixed**
* $in **mixed**
* $sql **mixed**


