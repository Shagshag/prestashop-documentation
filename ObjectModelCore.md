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
* This class implements: [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)* This class is defined in classes\ObjectModel.php line 27



Constants
----------


### TYPE_INT

    const TYPE_INT = 1



* This constant is defined in classes\ObjectModel.php line 32


### TYPE_BOOL

    const TYPE_BOOL = 2



* This constant is defined in classes\ObjectModel.php line 33


### TYPE_STRING

    const TYPE_STRING = 3



* This constant is defined in classes\ObjectModel.php line 34


### TYPE_FLOAT

    const TYPE_FLOAT = 4



* This constant is defined in classes\ObjectModel.php line 35


### TYPE_DATE

    const TYPE_DATE = 5



* This constant is defined in classes\ObjectModel.php line 36


### TYPE_HTML

    const TYPE_HTML = 6



* This constant is defined in classes\ObjectModel.php line 37


### TYPE_NOTHING

    const TYPE_NOTHING = 7



* This constant is defined in classes\ObjectModel.php line 38


### TYPE_SQL

    const TYPE_SQL = 8



* This constant is defined in classes\ObjectModel.php line 39


### FORMAT_COMMON

    const FORMAT_COMMON = 1



* This constant is defined in classes\ObjectModel.php line 44


### FORMAT_LANG

    const FORMAT_LANG = 2



* This constant is defined in classes\ObjectModel.php line 45


### FORMAT_SHOP

    const FORMAT_SHOP = 3



* This constant is defined in classes\ObjectModel.php line 46


### HAS_ONE

    const HAS_ONE = 1



* This constant is defined in classes\ObjectModel.php line 51


### HAS_MANY

    const HAS_MANY = 2



* This constant is defined in classes\ObjectModel.php line 52


Properties
----------


### $id

    public integer $id





* Visibility: **public**
* This property is defined in classes\ObjectModel.php line 55


### $id_lang

    protected integer $id_lang = null





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 58


### $id_shop

    protected integer $id_shop = null





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 61


### $id_shop_list

    public array $id_shop_list = null





* Visibility: **public**
* This property is defined in classes\ObjectModel.php line 64


### $get_shop_from_context

    protected boolean $get_shop_from_context = true





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 67


### $fieldsRequiredDatabase

    protected array $fieldsRequiredDatabase = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\ObjectModel.php line 70


### $table

    protected string $table





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 76


### $identifier

    protected string $identifier





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 82


### $fieldsRequired

    protected array $fieldsRequired = array()





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 88


### $fieldsSize

    protected array $fieldsSize = array()





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 94


### $fieldsValidate

    protected array $fieldsValidate = array()





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 100


### $fieldsRequiredLang

    protected array $fieldsRequiredLang = array()





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 106


### $fieldsSizeLang

    protected array $fieldsSizeLang = array()





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 112


### $fieldsValidateLang

    protected array $fieldsValidateLang = array()





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 118


### $tables

    protected array $tables = array()





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 124


### $webserviceParameters

    protected array $webserviceParameters = array()





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 127


### $image_dir

    protected string $image_dir = null





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 130


### $image_format

    protected String $image_format = 'jpg'





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 133


### $definition

    public array $definition = array()





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\ObjectModel.php line 139


### $loaded_classes

    protected array $loaded_classes = array()

Holds compiled definitions of each ObjectModel class.

Values are assigned during object initialization.

* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\ObjectModel.php line 147


### $def

    protected array $def





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 150


### $update_fields

    protected array $update_fields = null





* Visibility: **protected**
* This property is defined in classes\ObjectModel.php line 153


### $db

    protected \Db $db = false





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\ObjectModel.php line 156


### $force_id

    public boolean $force_id = false





* Visibility: **public**
* This property is defined in classes\ObjectModel.php line 159


### $cache_objects

    protected boolean $cache_objects = true





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\ObjectModel.php line 164


Methods
-------


### getRepositoryClassName

    string Core_Foundation_Database_EntityInterface::getRepositoryClassName()

Returns the name of the repository class for this entity.

If unspecified, a generic repository will be used for the entity.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)
* This method is defined in classes\ObjectModel.php line 35




### getValidationRules

    array ObjectModelCore::getValidationRules(string $class)

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ObjectModel.php line 178


#### Arguments
* $class **string** - &lt;p&gt;Child class name for static use (optional)&lt;/p&gt;



### __construct

    mixed ObjectModelCore::__construct(integer|null $id, integer|null $id_lang, integer|null $id_shop)

Builds the object



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 201


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
* This method is defined in classes\ObjectModel.php line 244




### getFieldsShop

    array ObjectModelCore::getFieldsShop()

Prepare fields for multishop
Fields are not validated here, we consider they are already validated in getFields() method,
this is not the best solution but this is the only one possible for retro compatibility.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 270




### getFieldsLang

    array ObjectModelCore::getFieldsLang()

Prepare multilang fields



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 288




### formatFields

    array ObjectModelCore::formatFields(integer $type, integer $id_lang)

Formats values of each fields.



* Visibility: **protected**
* This method is defined in classes\ObjectModel.php line 327


#### Arguments
* $type **integer** - &lt;p&gt;FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;If this parameter is given, only take lang fields&lt;/p&gt;



### formatValue

    mixed ObjectModelCore::formatValue(mixed $value, integer $type, boolean $with_quotes, boolean $purify, boolean $allow_null)

Formats a value



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ObjectModel.php line 381


#### Arguments
* $value **mixed**
* $type **integer**
* $with_quotes **boolean**
* $purify **boolean**
* $allow_null **boolean**



### save

    mixed Core_Foundation_Database_EntityInterface::save()





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)
* This method is defined in classes\ObjectModel.php line 37




### add

    boolean ObjectModelCore::add(boolean $auto_date, boolean $null_values)

Adds current object to the database



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 458


#### Arguments
* $auto_date **boolean**
* $null_values **boolean**



### duplicateObject

    \ObjectModel|false ObjectModelCore::duplicateObject()

Takes current object ID, gets its values from database,
saves them in a new row and loads newly saved values as a new object.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 549




### update

    boolean ObjectModelCore::update(boolean $null_values)

Updates the current object in the database



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 619


#### Arguments
* $null_values **boolean**



### delete

    mixed Core_Foundation_Database_EntityInterface::delete()





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)
* This method is defined in classes\ObjectModel.php line 39




### deleteSelection

    boolean ObjectModelCore::deleteSelection(array $ids)

Deletes multiple objects from the database at once



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 790


#### Arguments
* $ids **array** - &lt;p&gt;Array of objects IDs.&lt;/p&gt;



### toggleStatus

    boolean ObjectModelCore::toggleStatus()

Toggles object status in database



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 807




### getTranslationsFields

    array ObjectModelCore::getTranslationsFields(array $fields_array)





* Visibility: **protected**
* This method is defined in classes\ObjectModel.php line 831


#### Arguments
* $fields_array **array**



### makeTranslationFields

    mixed ObjectModelCore::makeTranslationFields(array $fields, array $fields_array, integer $id_language)





* Visibility: **protected**
* This method is defined in classes\ObjectModel.php line 854


#### Arguments
* $fields **array**
* $fields_array **array**
* $id_language **integer**



### validateFields

    boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)

Checks if object field values are valid before database interaction



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 895


#### Arguments
* $die **boolean**
* $error_return **boolean**



### validateFieldsLang

    boolean|string ObjectModelCore::validateFieldsLang(boolean $die, boolean $error_return)

Checks if multilingual object field values are valid before database interaction.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 927


#### Arguments
* $die **boolean**
* $error_return **boolean**



### validateField

    true|string ObjectModelCore::validateField(string $field, mixed $value, integer|null $id_lang, array $skip, boolean $human_errors)

Validate a single field



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 977


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
* This method is defined in classes\ObjectModel.php line 1083


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;
* $class **string** - &lt;p&gt;ObjectModel class name&lt;/p&gt;
* $htmlentities **boolean** - &lt;p&gt;If true, applies htmlentities() to result string&lt;/p&gt;
* $context **[Context](ContextCore)|null** - &lt;p&gt;Context object&lt;/p&gt;



### validateControler

    array ObjectModelCore::validateControler(boolean $htmlentities)





* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1105


#### Arguments
* $htmlentities **boolean**



### validateController

    array ObjectModelCore::validateController(boolean $htmlentities)

Validates submitted values and returns an array of errors, if any.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1118


#### Arguments
* $htmlentities **boolean** - &lt;p&gt;If true, uses htmlentities() for field name translations in errors.&lt;/p&gt;



### getWebserviceParameters

    array ObjectModelCore::getWebserviceParameters(string|null $ws_params_attribute_name)

Returns webservice parameters of this object.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1176


#### Arguments
* $ws_params_attribute_name **string|null**



### getWebserviceObjectList

    array|null ObjectModelCore::getWebserviceObjectList(string $sql_join, string $sql_filter, string $sql_sort, string $sql_limit)

Returns webservice object list.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1279


#### Arguments
* $sql_join **string**
* $sql_filter **string**
* $sql_sort **string**
* $sql_limit **string**



### validateFieldsRequiredDatabase

    array ObjectModelCore::validateFieldsRequiredDatabase(boolean $htmlentities)

Validate required fields.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1322


#### Arguments
* $htmlentities **boolean**



### getFieldsRequiredDatabase

    array|null ObjectModelCore::getFieldsRequiredDatabase(boolean $all)

Returns an array of required fields



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1355


#### Arguments
* $all **boolean** - &lt;p&gt;If true, returns required fields of all object classes.&lt;/p&gt;



### cacheFieldsRequiredDatabase

    mixed ObjectModelCore::cacheFieldsRequiredDatabase(boolean $all)

Caches data about required objects fields in memory



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1368


#### Arguments
* $all **boolean** - &lt;p&gt;If true, caches required fields of all object classes.&lt;/p&gt;



### addFieldsRequiredDatabase

    boolean ObjectModelCore::addFieldsRequiredDatabase(array $fields)

Sets required field for this class in the database.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1390


#### Arguments
* $fields **array**



### clearCache

    mixed ObjectModelCore::clearCache(boolean $all)

Clears cache entries that have this object's ID.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1414


#### Arguments
* $all **boolean** - &lt;p&gt;If true, clears cache for all objects&lt;/p&gt;



### isAssociatedToShop

    boolean ObjectModelCore::isAssociatedToShop(integer|null $id_shop)

Checks if current object is associated to a shop.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1430


#### Arguments
* $id_shop **integer|null**



### associateTo

    boolean|void ObjectModelCore::associateTo(integer|array $id_shops)

This function associate an item to its context



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1464


#### Arguments
* $id_shops **integer|array**



### getAssociatedShops

    array ObjectModelCore::getAssociatedShops()

Gets the list of associated shop IDs



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1499




### duplicateShops

    boolean|void ObjectModelCore::duplicateShops($id)

Copies shop association data from object with specified ID.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1523


#### Arguments
* $id **mixed**



### hasMultishopEntries

    boolean ObjectModelCore::hasMultishopEntries()

Checks if there is more than one entry in associated shop table for current object.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1550




### isMultishop

    boolean ObjectModelCore::isMultishop()

Checks if object is multi-shop object.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1564




### isMultiShopField

    boolean ObjectModelCore::isMultiShopField(string $field)

Checks if a field is a multi-shop field.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1576


#### Arguments
* $field **string**



### isLangMultishop

    boolean ObjectModelCore::isLangMultishop()

Checks if the object is both multi-language and multi-shop.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1586




### updateMultishopTable

    boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)

Updates a table and splits the common datas and the shop datas.



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ObjectModel.php line 1602


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - &lt;p&gt;Only executed for common table&lt;/p&gt;



### deleteImage

    boolean ObjectModelCore::deleteImage(boolean $force_delete)

Delete images associated with the object



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1643


#### Arguments
* $force_delete **boolean**



### existsInDatabase

    boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)

Checks if an object exists in database.



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ObjectModel.php line 1686


#### Arguments
* $id_entity **integer**
* $table **string**



### isCurrentlyUsed

    boolean ObjectModelCore::isCurrentlyUsed(string|null $table, boolean $has_active_column)

Checks if an object type exists in the database.



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ObjectModel.php line 1706


#### Arguments
* $table **string|null** - &lt;p&gt;Name of table linked to entity&lt;/p&gt;
* $has_active_column **boolean** - &lt;p&gt;True if the table has an active column&lt;/p&gt;



### hydrate

    mixed Core_Foundation_Database_EntityInterface::hydrate(array $keyValueData)





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)
* This method is defined in classes\ObjectModel.php line 41


#### Arguments
* $keyValueData **array**



### hydrateCollection

    array ObjectModelCore::hydrateCollection(string $class, array $datas, integer|null $id_lang)

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ObjectModel.php line 1755


#### Arguments
* $class **string** - &lt;p&gt;Class of objects to hydrate&lt;/p&gt;
* $datas **array** - &lt;p&gt;List of data (multi-dimensional array)&lt;/p&gt;
* $id_lang **integer|null**



### getDefinition

    array ObjectModelCore::getDefinition(string $class, string|null $field)

Returns object definition



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ObjectModel.php line 1809


#### Arguments
* $class **string** - &lt;p&gt;Name of object&lt;/p&gt;
* $field **string|null** - &lt;p&gt;Name of field if we want the definition of one field only&lt;/p&gt;



### setDefinitionRetrocompatibility

    mixed ObjectModelCore::setDefinitionRetrocompatibility()

Retrocompatibility for classes without $definition static



* Visibility: **protected**
* This method is defined in classes\ObjectModel.php line 1855




### getFieldByLang

    mixed ObjectModelCore::getFieldByLang(string $field_name, integer|null $id_lang)

Return the field value for the specified language if the field is multilang,
else the field value.



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1927


#### Arguments
* $field_name **string**
* $id_lang **integer|null**



### setFieldsToUpdate

    mixed ObjectModelCore::setFieldsToUpdate(array $fields)

Set a list of specific fields to update
array(field1 => true, field2 => false,
langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined in classes\ObjectModel.php line 1953


#### Arguments
* $fields **array**



### enableCache

    mixed ObjectModelCore::enableCache()

Enables object caching



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ObjectModel.php line 1961




### disableCache

    mixed ObjectModelCore::disableCache()

Disables object caching



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\ObjectModel.php line 1969



