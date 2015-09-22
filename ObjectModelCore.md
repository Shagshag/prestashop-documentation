ObjectModelCore
===============

2007-2015 PrestaShop

NOTICE OF LICENSE

This source file is subject to the Open Software License (OSL 3.0)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
http://opensource.org/licenses/osl-3.0.php
If you did not receive a copy of the license and are unable to
obtain it through the world-wide-web, please send an email
to license@prestashop.com so we can send you a copy immediately.

DISCLAIMER

Do not edit or add to this file if you wish to upgrade PrestaShop to newer
versions in the future. If you wish to customize PrestaShop for your
needs please refer to http://www.prestashop.com for more information.


* Class name: ObjectModelCore
* This is an **abstract** class
* This class is defined in [classes/ObjectModel.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L27)
* This class implements: [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)


Constants
----------

* [TYPE_INT](#constant-TYPE_INT)
* [TYPE_BOOL](#constant-TYPE_BOOL)
* [TYPE_STRING](#constant-TYPE_STRING)
* [TYPE_FLOAT](#constant-TYPE_FLOAT)
* [TYPE_DATE](#constant-TYPE_DATE)
* [TYPE_HTML](#constant-TYPE_HTML)
* [TYPE_NOTHING](#constant-TYPE_NOTHING)
* [TYPE_SQL](#constant-TYPE_SQL)
* [FORMAT_COMMON](#constant-FORMAT_COMMON)
* [FORMAT_LANG](#constant-FORMAT_LANG)
* [FORMAT_SHOP](#constant-FORMAT_SHOP)
* [HAS_ONE](#constant-HAS_ONE)
* [HAS_MANY](#constant-HAS_MANY)

Properties
----------

* [$id](#property-$id)
* [$id_lang](#property-$id_lang)
* [$id_shop](#property-$id_shop)
* [$id_shop_list](#property-$id_shop_list)
* [$get_shop_from_context](#property-$get_shop_from_context)
* [$fieldsRequiredDatabase](#property-$fieldsRequiredDatabase)
* [$table](#property-$table)
* [$identifier](#property-$identifier)
* [$fieldsRequired](#property-$fieldsRequired)
* [$fieldsSize](#property-$fieldsSize)
* [$fieldsValidate](#property-$fieldsValidate)
* [$fieldsRequiredLang](#property-$fieldsRequiredLang)
* [$fieldsSizeLang](#property-$fieldsSizeLang)
* [$fieldsValidateLang](#property-$fieldsValidateLang)
* [$tables](#property-$tables)
* [$webserviceParameters](#property-$webserviceParameters)
* [$image_dir](#property-$image_dir)
* [$image_format](#property-$image_format)
* [$definition](#property-$definition)
* [$loaded_classes](#property-$loaded_classes)
* [$def](#property-$def)
* [$update_fields](#property-$update_fields)
* [$db](#property-$db)
* [$force_id](#property-$force_id)
* [$cache_objects](#property-$cache_objects)

Methods
-------
* [getRepositoryClassName](#method-getRepositoryClassName)
* [getValidationRules](#method-getValidationRules)
* [__construct](#method-__construct)
* [getFields](#method-getFields)
* [getFieldsShop](#method-getFieldsShop)
* [getFieldsLang](#method-getFieldsLang)
* [formatFields](#method-formatFields)
* [formatValue](#method-formatValue)
* [save](#method-save)
* [add](#method-add)
* [duplicateObject](#method-duplicateObject)
* [update](#method-update)
* [delete](#method-delete)
* [deleteSelection](#method-deleteSelection)
* [toggleStatus](#method-toggleStatus)
* [getTranslationsFields](#method-getTranslationsFields)
* [makeTranslationFields](#method-makeTranslationFields)
* [validateFields](#method-validateFields)
* [validateFieldsLang](#method-validateFieldsLang)
* [validateField](#method-validateField)
* [displayFieldName](#method-displayFieldName)
* [validateControler](#method-validateControler)
* [validateController](#method-validateController)
* [getWebserviceParameters](#method-getWebserviceParameters)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [validateFieldsRequiredDatabase](#method-validateFieldsRequiredDatabase)
* [getFieldsRequiredDatabase](#method-getFieldsRequiredDatabase)
* [cacheFieldsRequiredDatabase](#method-cacheFieldsRequiredDatabase)
* [addFieldsRequiredDatabase](#method-addFieldsRequiredDatabase)
* [clearCache](#method-clearCache)
* [isAssociatedToShop](#method-isAssociatedToShop)
* [associateTo](#method-associateTo)
* [getAssociatedShops](#method-getAssociatedShops)
* [duplicateShops](#method-duplicateShops)
* [hasMultishopEntries](#method-hasMultishopEntries)
* [isMultishop](#method-isMultishop)
* [isMultiShopField](#method-isMultiShopField)
* [isLangMultishop](#method-isLangMultishop)
* [updateMultishopTable](#method-updateMultishopTable)
* [deleteImage](#method-deleteImage)
* [existsInDatabase](#method-existsInDatabase)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [hydrate](#method-hydrate)
* [hydrateCollection](#method-hydrateCollection)
* [getDefinition](#method-getDefinition)
* [setDefinitionRetrocompatibility](#method-setDefinitionRetrocompatibility)
* [getFieldByLang](#method-getFieldByLang)
* [setFieldsToUpdate](#method-setFieldsToUpdate)
* [enableCache](#method-enableCache)
* [disableCache](#method-disableCache)


Constants
----------


### <a name="constant-TYPE_INT"></a>TYPE_INT

    const TYPE_INT = 1



* This constant is defined in [classes/ObjectModel.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L32)


### <a name="constant-TYPE_BOOL"></a>TYPE_BOOL

    const TYPE_BOOL = 2



* This constant is defined in [classes/ObjectModel.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L33)


### <a name="constant-TYPE_STRING"></a>TYPE_STRING

    const TYPE_STRING = 3



* This constant is defined in [classes/ObjectModel.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L34)


### <a name="constant-TYPE_FLOAT"></a>TYPE_FLOAT

    const TYPE_FLOAT = 4



* This constant is defined in [classes/ObjectModel.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L35)


### <a name="constant-TYPE_DATE"></a>TYPE_DATE

    const TYPE_DATE = 5



* This constant is defined in [classes/ObjectModel.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L36)


### <a name="constant-TYPE_HTML"></a>TYPE_HTML

    const TYPE_HTML = 6



* This constant is defined in [classes/ObjectModel.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L37)


### <a name="constant-TYPE_NOTHING"></a>TYPE_NOTHING

    const TYPE_NOTHING = 7



* This constant is defined in [classes/ObjectModel.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L38)


### <a name="constant-TYPE_SQL"></a>TYPE_SQL

    const TYPE_SQL = 8



* This constant is defined in [classes/ObjectModel.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L39)


### <a name="constant-FORMAT_COMMON"></a>FORMAT_COMMON

    const FORMAT_COMMON = 1



* This constant is defined in [classes/ObjectModel.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L44)


### <a name="constant-FORMAT_LANG"></a>FORMAT_LANG

    const FORMAT_LANG = 2



* This constant is defined in [classes/ObjectModel.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L45)


### <a name="constant-FORMAT_SHOP"></a>FORMAT_SHOP

    const FORMAT_SHOP = 3



* This constant is defined in [classes/ObjectModel.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L46)


### <a name="constant-HAS_ONE"></a>HAS_ONE

    const HAS_ONE = 1



* This constant is defined in [classes/ObjectModel.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L51)


### <a name="constant-HAS_MANY"></a>HAS_MANY

    const HAS_MANY = 2



* This constant is defined in [classes/ObjectModel.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L52)


Properties
----------


### <a name="property-$id"></a>$id

    public integer $id





* Visibility: **public**
* This property is defined in [classes/ObjectModel.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L55)


### <a name="property-$id_lang"></a>$id_lang

    protected integer $id_lang = null





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L58)


### <a name="property-$id_shop"></a>$id_shop

    protected integer $id_shop = null





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L61)


### <a name="property-$id_shop_list"></a>$id_shop_list

    public array $id_shop_list = null





* Visibility: **public**
* This property is defined in [classes/ObjectModel.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L64)


### <a name="property-$get_shop_from_context"></a>$get_shop_from_context

    protected boolean $get_shop_from_context = true





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L67)


### <a name="property-$fieldsRequiredDatabase"></a>$fieldsRequiredDatabase

    protected array $fieldsRequiredDatabase = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/ObjectModel.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L70)


### <a name="property-$table"></a>$table

    protected string $table





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L76)


### <a name="property-$identifier"></a>$identifier

    protected string $identifier





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L82)


### <a name="property-$fieldsRequired"></a>$fieldsRequired

    protected array $fieldsRequired = array()





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L88)


### <a name="property-$fieldsSize"></a>$fieldsSize

    protected array $fieldsSize = array()





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L94)


### <a name="property-$fieldsValidate"></a>$fieldsValidate

    protected array $fieldsValidate = array()





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L100)


### <a name="property-$fieldsRequiredLang"></a>$fieldsRequiredLang

    protected array $fieldsRequiredLang = array()





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L106)


### <a name="property-$fieldsSizeLang"></a>$fieldsSizeLang

    protected array $fieldsSizeLang = array()





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L112)


### <a name="property-$fieldsValidateLang"></a>$fieldsValidateLang

    protected array $fieldsValidateLang = array()





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L118)


### <a name="property-$tables"></a>$tables

    protected array $tables = array()





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L124)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected array $webserviceParameters = array()





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L127)


### <a name="property-$image_dir"></a>$image_dir

    protected string $image_dir = null





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L130)


### <a name="property-$image_format"></a>$image_format

    protected String $image_format = 'jpg'





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L133)


### <a name="property-$definition"></a>$definition

    public array $definition = array()





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/ObjectModel.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L139)


### <a name="property-$loaded_classes"></a>$loaded_classes

    protected array $loaded_classes = array()

Holds compiled definitions of each ObjectModel class.

Values are assigned during object initialization.

* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/ObjectModel.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L147)


### <a name="property-$def"></a>$def

    protected array $def





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L150)


### <a name="property-$update_fields"></a>$update_fields

    protected array $update_fields = null





* Visibility: **protected**
* This property is defined in [classes/ObjectModel.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L153)


### <a name="property-$db"></a>$db

    protected \Db $db = false





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/ObjectModel.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L156)


### <a name="property-$force_id"></a>$force_id

    public boolean $force_id = false





* Visibility: **public**
* This property is defined in [classes/ObjectModel.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L159)


### <a name="property-$cache_objects"></a>$cache_objects

    protected boolean $cache_objects = true





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/ObjectModel.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L164)


Methods
-------


### <a name="method-getRepositoryClassName"></a>getRepositoryClassName

    string Core_Foundation_Database_EntityInterface::getRepositoryClassName()

Returns the name of the repository class for this entity.

If unspecified, a generic repository will be used for the entity.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)
* This method is defined in [classes/ObjectModel.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L35)




### <a name="method-getValidationRules"></a>getValidationRules

    array ObjectModelCore::getValidationRules(string $class)

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ObjectModel.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L178)


#### Arguments
* $class **string** - &lt;p&gt;Child class name for static use (optional)&lt;/p&gt;



### <a name="method-__construct"></a>__construct

    mixed ObjectModelCore::__construct(integer|null $id, integer|null $id_lang, integer|null $id_shop)

Builds the object



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L201)


#### Arguments
* $id **integer|null** - &lt;p&gt;If specified, loads and existing object from DB (optional).&lt;/p&gt;
* $id_lang **integer|null** - &lt;p&gt;Required if object is multilingual (optional).&lt;/p&gt;
* $id_shop **integer|null** - &lt;p&gt;ID shop for objects with multishop tables.&lt;/p&gt;



### <a name="method-getFields"></a>getFields

    array ObjectModelCore::getFields()

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval, .

..)

* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L244)




### <a name="method-getFieldsShop"></a>getFieldsShop

    array ObjectModelCore::getFieldsShop()

Prepare fields for multishop
Fields are not validated here, we consider they are already validated in getFields() method,
this is not the best solution but this is the only one possible for retro compatibility.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L270)




### <a name="method-getFieldsLang"></a>getFieldsLang

    array ObjectModelCore::getFieldsLang()

Prepare multilang fields



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L288)




### <a name="method-formatFields"></a>formatFields

    array ObjectModelCore::formatFields(integer $type, integer $id_lang)

Formats values of each fields.



* Visibility: **protected**
* This method is defined in [classes/ObjectModel.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L327)


#### Arguments
* $type **integer** - &lt;p&gt;FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;If this parameter is given, only take lang fields&lt;/p&gt;



### <a name="method-formatValue"></a>formatValue

    mixed ObjectModelCore::formatValue(mixed $value, integer $type, boolean $with_quotes, boolean $purify, boolean $allow_null)

Formats a value



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ObjectModel.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L381)


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **boolean**
* $purify **boolean**
* $allow_null **boolean**



### <a name="method-save"></a>save

    mixed Core_Foundation_Database_EntityInterface::save()





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)
* This method is defined in [classes/ObjectModel.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L37)




### <a name="method-add"></a>add

    boolean ObjectModelCore::add(boolean $auto_date, boolean $null_values)

Adds current object to the database



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 458](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L458)


#### Arguments
* $auto_date **boolean**
* $null_values **boolean**



### <a name="method-duplicateObject"></a>duplicateObject

    \ObjectModel|false ObjectModelCore::duplicateObject()

Takes current object ID, gets its values from database,
saves them in a new row and loads newly saved values as a new object.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L549)




### <a name="method-update"></a>update

    boolean ObjectModelCore::update(boolean $null_values)

Updates the current object in the database



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 619](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L619)


#### Arguments
* $null_values **boolean**



### <a name="method-delete"></a>delete

    mixed Core_Foundation_Database_EntityInterface::delete()





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)
* This method is defined in [classes/ObjectModel.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L39)




### <a name="method-deleteSelection"></a>deleteSelection

    boolean ObjectModelCore::deleteSelection(array $ids)

Deletes multiple objects from the database at once



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 790](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L790)


#### Arguments
* $ids **array** - &lt;p&gt;Array of objects IDs.&lt;/p&gt;



### <a name="method-toggleStatus"></a>toggleStatus

    boolean ObjectModelCore::toggleStatus()

Toggles object status in database



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 807](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L807)




### <a name="method-getTranslationsFields"></a>getTranslationsFields

    array ObjectModelCore::getTranslationsFields(array $fields_array)





* Visibility: **protected**
* This method is defined in [classes/ObjectModel.php line 831](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L831)


#### Arguments
* $fields_array **array**



### <a name="method-makeTranslationFields"></a>makeTranslationFields

    mixed ObjectModelCore::makeTranslationFields(array $fields, array $fields_array, integer $id_language)





* Visibility: **protected**
* This method is defined in [classes/ObjectModel.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L854)


#### Arguments
* $fields **array**
* $fields_array **array**
* $id_language **integer**



### <a name="method-validateFields"></a>validateFields

    boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)

Checks if object field values are valid before database interaction



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L895)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateFieldsLang"></a>validateFieldsLang

    boolean|string ObjectModelCore::validateFieldsLang(boolean $die, boolean $error_return)

Checks if multilingual object field values are valid before database interaction.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L927)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### <a name="method-validateField"></a>validateField

    true|string ObjectModelCore::validateField(string $field, mixed $value, integer|null $id_lang, array $skip, boolean $human_errors)

Validate a single field



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L977)


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;
* $value **mixed** - &lt;p&gt;Field value&lt;/p&gt;
* $id_lang **integer|null** - &lt;p&gt;Language ID&lt;/p&gt;
* $skip **array** - &lt;p&gt;Array of fields to skip.&lt;/p&gt;
* $human_errors **boolean** - &lt;p&gt;If true, uses more descriptive, translatable error strings.&lt;/p&gt;



### <a name="method-displayFieldName"></a>displayFieldName

    string ObjectModelCore::displayFieldName(string $field, string $class, boolean $htmlentities, \Context|null $context)

Returns field name translation



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ObjectModel.php line 1083](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1083)


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;
* $class **string** - &lt;p&gt;ObjectModel class name&lt;/p&gt;
* $htmlentities **boolean** - &lt;p&gt;If true, applies htmlentities() to result string&lt;/p&gt;
* $context **[Context](ContextCore)|null** - &lt;p&gt;Context object&lt;/p&gt;



### <a name="method-validateControler"></a>validateControler

    array ObjectModelCore::validateControler(boolean $htmlentities)





* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1105)


#### Arguments
* $htmlentities **boolean**



### <a name="method-validateController"></a>validateController

    array ObjectModelCore::validateController(boolean $htmlentities)

Validates submitted values and returns an array of errors, if any.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1118)


#### Arguments
* $htmlentities **boolean** - &lt;p&gt;If true, uses htmlentities() for field name translations in errors.&lt;/p&gt;



### <a name="method-getWebserviceParameters"></a>getWebserviceParameters

    array ObjectModelCore::getWebserviceParameters(string|null $ws_params_attribute_name)

Returns webservice parameters of this object.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1176)


#### Arguments
* $ws_params_attribute_name **string|null**



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

    array|null ObjectModelCore::getWebserviceObjectList(string $sql_join, string $sql_filter, string $sql_sort, string $sql_limit)

Returns webservice object list.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1279)


#### Arguments
* $sql_join **string**
* $sql_filter **string**
* $sql_sort **string**
* $sql_limit **string**



### <a name="method-validateFieldsRequiredDatabase"></a>validateFieldsRequiredDatabase

    array ObjectModelCore::validateFieldsRequiredDatabase(boolean $htmlentities)

Validate required fields.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1322](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1322)


#### Arguments
* $htmlentities **boolean**



### <a name="method-getFieldsRequiredDatabase"></a>getFieldsRequiredDatabase

    array|null ObjectModelCore::getFieldsRequiredDatabase(boolean $all)

Returns an array of required fields



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1355](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1355)


#### Arguments
* $all **boolean** - &lt;p&gt;If true, returns required fields of all object classes.&lt;/p&gt;



### <a name="method-cacheFieldsRequiredDatabase"></a>cacheFieldsRequiredDatabase

    mixed ObjectModelCore::cacheFieldsRequiredDatabase(boolean $all)

Caches data about required objects fields in memory



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1368](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1368)


#### Arguments
* $all **boolean** - &lt;p&gt;If true, caches required fields of all object classes.&lt;/p&gt;



### <a name="method-addFieldsRequiredDatabase"></a>addFieldsRequiredDatabase

    boolean ObjectModelCore::addFieldsRequiredDatabase(array $fields)

Sets required field for this class in the database.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1390)


#### Arguments
* $fields **array**



### <a name="method-clearCache"></a>clearCache

    mixed ObjectModelCore::clearCache(boolean $all)

Clears cache entries that have this object's ID.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1414)


#### Arguments
* $all **boolean** - &lt;p&gt;If true, clears cache for all objects&lt;/p&gt;



### <a name="method-isAssociatedToShop"></a>isAssociatedToShop

    boolean ObjectModelCore::isAssociatedToShop(integer|null $id_shop)

Checks if current object is associated to a shop.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1430)


#### Arguments
* $id_shop **integer|null**



### <a name="method-associateTo"></a>associateTo

    boolean|void ObjectModelCore::associateTo(integer|array $id_shops)

This function associate an item to its context



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1464)


#### Arguments
* $id_shops **integer|array**



### <a name="method-getAssociatedShops"></a>getAssociatedShops

    array ObjectModelCore::getAssociatedShops()

Gets the list of associated shop IDs



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1499](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1499)




### <a name="method-duplicateShops"></a>duplicateShops

    boolean|void ObjectModelCore::duplicateShops($id)

Copies shop association data from object with specified ID.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1523)


#### Arguments
* $id **mixed**



### <a name="method-hasMultishopEntries"></a>hasMultishopEntries

    boolean ObjectModelCore::hasMultishopEntries()

Checks if there is more than one entry in associated shop table for current object.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1550)




### <a name="method-isMultishop"></a>isMultishop

    boolean ObjectModelCore::isMultishop()

Checks if object is multi-shop object.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1564](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1564)




### <a name="method-isMultiShopField"></a>isMultiShopField

    boolean ObjectModelCore::isMultiShopField(string $field)

Checks if a field is a multi-shop field.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1576](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1576)


#### Arguments
* $field **string**



### <a name="method-isLangMultishop"></a>isLangMultishop

    boolean ObjectModelCore::isLangMultishop()

Checks if the object is both multi-language and multi-shop.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1586)




### <a name="method-updateMultishopTable"></a>updateMultishopTable

    boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)

Updates a table and splits the common datas and the shop datas.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ObjectModel.php line 1602](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1602)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - &lt;p&gt;Only executed for common table&lt;/p&gt;



### <a name="method-deleteImage"></a>deleteImage

    boolean ObjectModelCore::deleteImage(boolean $force_delete)

Delete images associated with the object



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1643](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1643)


#### Arguments
* $force_delete **boolean**



### <a name="method-existsInDatabase"></a>existsInDatabase

    boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)

Checks if an object exists in database.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ObjectModel.php line 1686](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1686)


#### Arguments
* $id_entity **integer**
* $table **string**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

    boolean ObjectModelCore::isCurrentlyUsed(string|null $table, boolean $has_active_column)

Checks if an object type exists in the database.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ObjectModel.php line 1706](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1706)


#### Arguments
* $table **string|null** - &lt;p&gt;Name of table linked to entity&lt;/p&gt;
* $has_active_column **boolean** - &lt;p&gt;True if the table has an active column&lt;/p&gt;



### <a name="method-hydrate"></a>hydrate

    mixed Core_Foundation_Database_EntityInterface::hydrate(array $keyValueData)





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)
* This method is defined in [classes/ObjectModel.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L41)


#### Arguments
* $keyValueData **array**



### <a name="method-hydrateCollection"></a>hydrateCollection

    array ObjectModelCore::hydrateCollection(string $class, array $datas, integer|null $id_lang)

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ObjectModel.php line 1755](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1755)


#### Arguments
* $class **string** - &lt;p&gt;Class of objects to hydrate&lt;/p&gt;
* $datas **array** - &lt;p&gt;List of data (multi-dimensional array)&lt;/p&gt;
* $id_lang **integer|null**



### <a name="method-getDefinition"></a>getDefinition

    array ObjectModelCore::getDefinition(string $class, string|null $field)

Returns object definition



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ObjectModel.php line 1809](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1809)


#### Arguments
* $class **string** - &lt;p&gt;Name of object&lt;/p&gt;
* $field **string|null** - &lt;p&gt;Name of field if we want the definition of one field only&lt;/p&gt;



### <a name="method-setDefinitionRetrocompatibility"></a>setDefinitionRetrocompatibility

    mixed ObjectModelCore::setDefinitionRetrocompatibility()

Retrocompatibility for classes without $definition static



* Visibility: **protected**
* This method is defined in [classes/ObjectModel.php line 1855](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1855)




### <a name="method-getFieldByLang"></a>getFieldByLang

    mixed ObjectModelCore::getFieldByLang(string $field_name, integer|null $id_lang)

Return the field value for the specified language if the field is multilang,
else the field value.



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1927)


#### Arguments
* $field_name **string**
* $id_lang **integer|null**



### <a name="method-setFieldsToUpdate"></a>setFieldsToUpdate

    mixed ObjectModelCore::setFieldsToUpdate(array $fields)

Set a list of specific fields to update
array(field1 => true, field2 => false,
langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined in [classes/ObjectModel.php line 1953](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1953)


#### Arguments
* $fields **array**



### <a name="method-enableCache"></a>enableCache

    mixed ObjectModelCore::enableCache()

Enables object caching



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ObjectModel.php line 1961](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1961)




### <a name="method-disableCache"></a>disableCache

    mixed ObjectModelCore::disableCache()

Disables object caching



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ObjectModel.php line 1969](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ObjectModel.php#L1969)



