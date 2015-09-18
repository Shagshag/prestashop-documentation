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
* Namespace: 
* This is an **abstract** class
* This class implements: [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface.md)


Constants
----------


### TYPE_INT

    const TYPE_INT = 1





### TYPE_BOOL

    const TYPE_BOOL = 2





### TYPE_STRING

    const TYPE_STRING = 3





### TYPE_FLOAT

    const TYPE_FLOAT = 4





### TYPE_DATE

    const TYPE_DATE = 5





### TYPE_HTML

    const TYPE_HTML = 6





### TYPE_NOTHING

    const TYPE_NOTHING = 7





### TYPE_SQL

    const TYPE_SQL = 8





### FORMAT_COMMON

    const FORMAT_COMMON = 1





### FORMAT_LANG

    const FORMAT_LANG = 2





### FORMAT_SHOP

    const FORMAT_SHOP = 3





### HAS_ONE

    const HAS_ONE = 1





### HAS_MANY

    const HAS_MANY = 2





Properties
----------


### $id

    public integer $id





* Visibility: **public**


### $id_lang

    protected integer $id_lang = null





* Visibility: **protected**


### $id_shop

    protected integer $id_shop = null





* Visibility: **protected**


### $id_shop_list

    public array $id_shop_list = null





* Visibility: **public**


### $get_shop_from_context

    protected boolean $get_shop_from_context = true





* Visibility: **protected**


### $fieldsRequiredDatabase

    protected array $fieldsRequiredDatabase = null





* Visibility: **protected**
* This property is **static**.


### $table

    protected string $table





* Visibility: **protected**


### $identifier

    protected string $identifier





* Visibility: **protected**


### $fieldsRequired

    protected array $fieldsRequired = array()





* Visibility: **protected**


### $fieldsSize

    protected array $fieldsSize = array()





* Visibility: **protected**


### $fieldsValidate

    protected array $fieldsValidate = array()





* Visibility: **protected**


### $fieldsRequiredLang

    protected array $fieldsRequiredLang = array()





* Visibility: **protected**


### $fieldsSizeLang

    protected array $fieldsSizeLang = array()





* Visibility: **protected**


### $fieldsValidateLang

    protected array $fieldsValidateLang = array()





* Visibility: **protected**


### $tables

    protected array $tables = array()





* Visibility: **protected**


### $webserviceParameters

    protected array $webserviceParameters = array()





* Visibility: **protected**


### $image_dir

    protected string $image_dir = null





* Visibility: **protected**


### $image_format

    protected String $image_format = 'jpg'





* Visibility: **protected**


### $definition

    public array $definition = array()





* Visibility: **public**
* This property is **static**.


### $loaded_classes

    protected array $loaded_classes = array()

Holds compiled definitions of each ObjectModel class.

Values are assigned during object initialization.

* Visibility: **protected**
* This property is **static**.


### $def

    protected array $def





* Visibility: **protected**


### $update_fields

    protected array $update_fields = null





* Visibility: **protected**


### $db

    protected \Db $db = false





* Visibility: **protected**
* This property is **static**.


### $force_id

    public boolean $force_id = false





* Visibility: **public**


### $cache_objects

    protected boolean $cache_objects = true





* Visibility: **protected**
* This property is **static**.


Methods
-------


### getRepositoryClassName

    string Core_Foundation_Database_EntityInterface::getRepositoryClassName()

Returns the name of the repository class for this entity.

If unspecified, a generic repository will be used for the entity.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface.md)




### getValidationRules

    array ObjectModelCore::getValidationRules(string $class)

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $class **string** - &lt;p&gt;Child class name for static use (optional)&lt;/p&gt;



### __construct

    mixed ObjectModelCore::__construct(integer|null $id, integer|null $id_lang, integer|null $id_shop)

Builds the object



* Visibility: **public**


#### Arguments
* $id **integer|null** - &lt;p&gt;If specified, loads and existing object from DB (optional).&lt;/p&gt;
* $id_lang **integer|null** - &lt;p&gt;Required if object is multilingual (optional).&lt;/p&gt;
* $id_shop **integer|null** - &lt;p&gt;ID shop for objects with multishop tables.&lt;/p&gt;



### getFields

    array ObjectModelCore::getFields()

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval, .

..)

* Visibility: **public**




### getFieldsShop

    array ObjectModelCore::getFieldsShop()

Prepare fields for multishop
Fields are not validated here, we consider they are already validated in getFields() method,
this is not the best solution but this is the only one possible for retro compatibility.



* Visibility: **public**




### getFieldsLang

    array ObjectModelCore::getFieldsLang()

Prepare multilang fields



* Visibility: **public**




### formatFields

    array ObjectModelCore::formatFields(integer $type, integer $id_lang)

Formats values of each fields.



* Visibility: **protected**


#### Arguments
* $type **integer** - &lt;p&gt;FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;If this parameter is given, only take lang fields&lt;/p&gt;



### formatValue

    mixed ObjectModelCore::formatValue(mixed $value, integer $type, boolean $with_quotes, boolean $purify, boolean $allow_null)

Formats a value



* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **boolean**
* $purify **boolean**
* $allow_null **boolean**



### save

    mixed Core_Foundation_Database_EntityInterface::save()





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface.md)




### add

    boolean ObjectModelCore::add(boolean $auto_date, boolean $null_values)

Adds current object to the database



* Visibility: **public**


#### Arguments
* $auto_date **boolean**
* $null_values **boolean**



### duplicateObject

    \ObjectModel|false ObjectModelCore::duplicateObject()

Takes current object ID, gets its values from database,
saves them in a new row and loads newly saved values as a new object.



* Visibility: **public**




### update

    boolean ObjectModelCore::update(boolean $null_values)

Updates the current object in the database



* Visibility: **public**


#### Arguments
* $null_values **boolean**



### delete

    mixed Core_Foundation_Database_EntityInterface::delete()





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface.md)




### deleteSelection

    boolean ObjectModelCore::deleteSelection(array $ids)

Deletes multiple objects from the database at once



* Visibility: **public**


#### Arguments
* $ids **array** - &lt;p&gt;Array of objects IDs.&lt;/p&gt;



### toggleStatus

    boolean ObjectModelCore::toggleStatus()

Toggles object status in database



* Visibility: **public**




### getTranslationsFields

    array ObjectModelCore::getTranslationsFields(array $fields_array)





* Visibility: **protected**


#### Arguments
* $fields_array **array**



### makeTranslationFields

    mixed ObjectModelCore::makeTranslationFields(array $fields, array $fields_array, integer $id_language)





* Visibility: **protected**


#### Arguments
* $fields **array**
* $fields_array **array**
* $id_language **integer**



### validateFields

    boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)

Checks if object field values are valid before database interaction



* Visibility: **public**


#### Arguments
* $die **boolean**
* $error_return **boolean**



### validateFieldsLang

    boolean|string ObjectModelCore::validateFieldsLang(boolean $die, boolean $error_return)

Checks if multilingual object field values are valid before database interaction.



* Visibility: **public**


#### Arguments
* $die **boolean**
* $error_return **boolean**



### validateField

    true|string ObjectModelCore::validateField(string $field, mixed $value, integer|null $id_lang, array $skip, boolean $human_errors)

Validate a single field



* Visibility: **public**


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;
* $value **mixed** - &lt;p&gt;Field value&lt;/p&gt;
* $id_lang **integer|null** - &lt;p&gt;Language ID&lt;/p&gt;
* $skip **array** - &lt;p&gt;Array of fields to skip.&lt;/p&gt;
* $human_errors **boolean** - &lt;p&gt;If true, uses more descriptive, translatable error strings.&lt;/p&gt;



### displayFieldName

    string ObjectModelCore::displayFieldName(string $field, string $class, boolean $htmlentities, \Context|null $context)

Returns field name translation



* Visibility: **public**
* This method is **static**.


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;
* $class **string** - &lt;p&gt;ObjectModel class name&lt;/p&gt;
* $htmlentities **boolean** - &lt;p&gt;If true, applies htmlentities() to result string&lt;/p&gt;
* $context **Context|null** - &lt;p&gt;Context object&lt;/p&gt;



### validateControler

    array ObjectModelCore::validateControler(boolean $htmlentities)





* Visibility: **public**


#### Arguments
* $htmlentities **boolean**



### validateController

    array ObjectModelCore::validateController(boolean $htmlentities)

Validates submitted values and returns an array of errors, if any.



* Visibility: **public**


#### Arguments
* $htmlentities **boolean** - &lt;p&gt;If true, uses htmlentities() for field name translations in errors.&lt;/p&gt;



### getWebserviceParameters

    array ObjectModelCore::getWebserviceParameters(string|null $ws_params_attribute_name)

Returns webservice parameters of this object.



* Visibility: **public**


#### Arguments
* $ws_params_attribute_name **string|null**



### getWebserviceObjectList

    array|null ObjectModelCore::getWebserviceObjectList(string $sql_join, string $sql_filter, string $sql_sort, string $sql_limit)

Returns webservice object list.



* Visibility: **public**


#### Arguments
* $sql_join **string**
* $sql_filter **string**
* $sql_sort **string**
* $sql_limit **string**



### validateFieldsRequiredDatabase

    array ObjectModelCore::validateFieldsRequiredDatabase(boolean $htmlentities)

Validate required fields.



* Visibility: **public**


#### Arguments
* $htmlentities **boolean**



### getFieldsRequiredDatabase

    array|null ObjectModelCore::getFieldsRequiredDatabase(boolean $all)

Returns an array of required fields



* Visibility: **public**


#### Arguments
* $all **boolean** - &lt;p&gt;If true, returns required fields of all object classes.&lt;/p&gt;



### cacheFieldsRequiredDatabase

    mixed ObjectModelCore::cacheFieldsRequiredDatabase(boolean $all)

Caches data about required objects fields in memory



* Visibility: **public**


#### Arguments
* $all **boolean** - &lt;p&gt;If true, caches required fields of all object classes.&lt;/p&gt;



### addFieldsRequiredDatabase

    boolean ObjectModelCore::addFieldsRequiredDatabase(array $fields)

Sets required field for this class in the database.



* Visibility: **public**


#### Arguments
* $fields **array**



### clearCache

    mixed ObjectModelCore::clearCache(boolean $all)

Clears cache entries that have this object's ID.



* Visibility: **public**


#### Arguments
* $all **boolean** - &lt;p&gt;If true, clears cache for all objects&lt;/p&gt;



### isAssociatedToShop

    boolean ObjectModelCore::isAssociatedToShop(integer|null $id_shop)

Checks if current object is associated to a shop.



* Visibility: **public**


#### Arguments
* $id_shop **integer|null**



### associateTo

    boolean|void ObjectModelCore::associateTo(integer|array $id_shops)

This function associate an item to its context



* Visibility: **public**


#### Arguments
* $id_shops **integer|array**



### getAssociatedShops

    array ObjectModelCore::getAssociatedShops()

Gets the list of associated shop IDs



* Visibility: **public**




### duplicateShops

    boolean|void ObjectModelCore::duplicateShops($id)

Copies shop association data from object with specified ID.



* Visibility: **public**


#### Arguments
* $id **mixed**



### hasMultishopEntries

    boolean ObjectModelCore::hasMultishopEntries()

Checks if there is more than one entry in associated shop table for current object.



* Visibility: **public**




### isMultishop

    boolean ObjectModelCore::isMultishop()

Checks if object is multi-shop object.



* Visibility: **public**




### isMultiShopField

    boolean ObjectModelCore::isMultiShopField(string $field)

Checks if a field is a multi-shop field.



* Visibility: **public**


#### Arguments
* $field **string**



### isLangMultishop

    boolean ObjectModelCore::isLangMultishop()

Checks if the object is both multi-language and multi-shop.



* Visibility: **public**




### updateMultishopTable

    boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)

Updates a table and splits the common datas and the shop datas.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - &lt;p&gt;Only executed for common table&lt;/p&gt;



### deleteImage

    boolean ObjectModelCore::deleteImage(boolean $force_delete)

Delete images associated with the object



* Visibility: **public**


#### Arguments
* $force_delete **boolean**



### existsInDatabase

    boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)

Checks if an object exists in database.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_entity **integer**
* $table **string**



### isCurrentlyUsed

    boolean ObjectModelCore::isCurrentlyUsed(string|null $table, boolean $has_active_column)

Checks if an object type exists in the database.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $table **string|null** - &lt;p&gt;Name of table linked to entity&lt;/p&gt;
* $has_active_column **boolean** - &lt;p&gt;True if the table has an active column&lt;/p&gt;



### hydrate

    mixed Core_Foundation_Database_EntityInterface::hydrate(array $keyValueData)





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface.md)


#### Arguments
* $keyValueData **array**



### hydrateCollection

    array ObjectModelCore::hydrateCollection(string $class, array $datas, integer|null $id_lang)

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.


#### Arguments
* $class **string** - &lt;p&gt;Class of objects to hydrate&lt;/p&gt;
* $datas **array** - &lt;p&gt;List of data (multi-dimensional array)&lt;/p&gt;
* $id_lang **integer|null**



### getDefinition

    array ObjectModelCore::getDefinition(string $class, string|null $field)

Returns object definition



* Visibility: **public**
* This method is **static**.


#### Arguments
* $class **string** - &lt;p&gt;Name of object&lt;/p&gt;
* $field **string|null** - &lt;p&gt;Name of field if we want the definition of one field only&lt;/p&gt;



### setDefinitionRetrocompatibility

    mixed ObjectModelCore::setDefinitionRetrocompatibility()

Retrocompatibility for classes without $definition static



* Visibility: **protected**




### getFieldByLang

    mixed ObjectModelCore::getFieldByLang(string $field_name, integer|null $id_lang)

Return the field value for the specified language if the field is multilang,
else the field value.



* Visibility: **public**


#### Arguments
* $field_name **string**
* $id_lang **integer|null**



### setFieldsToUpdate

    mixed ObjectModelCore::setFieldsToUpdate(array $fields)

Set a list of specific fields to update
array(field1 => true, field2 => false,
langfield1 => array(1 => true, 2 => false))



* Visibility: **public**


#### Arguments
* $fields **array**



### enableCache

    mixed ObjectModelCore::enableCache()

Enables object caching



* Visibility: **public**
* This method is **static**.




### disableCache

    mixed ObjectModelCore::disableCache()

Disables object caching



* Visibility: **public**
* This method is **static**.



