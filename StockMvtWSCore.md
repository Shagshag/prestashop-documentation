StockMvtWSCore
===============

Webservice entity for stock movements

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


* Class name: StockMvtWSCore
* Namespace: 
* Parent class: [ObjectModelCore](ObjectModelCore)

* This class is defined in [classes/stock/StockMvtWS.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#31)



Constants
----------


### TYPE_INT

    const TYPE_INT = 1



* This constant is defined in [classes/stock/StockMvtWS.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#32)


### TYPE_BOOL

    const TYPE_BOOL = 2



* This constant is defined in [classes/stock/StockMvtWS.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#33)


### TYPE_STRING

    const TYPE_STRING = 3



* This constant is defined in [classes/stock/StockMvtWS.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#34)


### TYPE_FLOAT

    const TYPE_FLOAT = 4



* This constant is defined in [classes/stock/StockMvtWS.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#35)


### TYPE_DATE

    const TYPE_DATE = 5



* This constant is defined in [classes/stock/StockMvtWS.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#36)


### TYPE_HTML

    const TYPE_HTML = 6



* This constant is defined in [classes/stock/StockMvtWS.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#37)


### TYPE_NOTHING

    const TYPE_NOTHING = 7



* This constant is defined in [classes/stock/StockMvtWS.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#38)


### TYPE_SQL

    const TYPE_SQL = 8



* This constant is defined in [classes/stock/StockMvtWS.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#39)


### FORMAT_COMMON

    const FORMAT_COMMON = 1



* This constant is defined in [classes/stock/StockMvtWS.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#44)


### FORMAT_LANG

    const FORMAT_LANG = 2



* This constant is defined in [classes/stock/StockMvtWS.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#45)


### FORMAT_SHOP

    const FORMAT_SHOP = 3



* This constant is defined in [classes/stock/StockMvtWS.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#46)


### HAS_ONE

    const HAS_ONE = 1



* This constant is defined in [classes/stock/StockMvtWS.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#51)


### HAS_MANY

    const HAS_MANY = 2



* This constant is defined in [classes/stock/StockMvtWS.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#52)


Properties
----------


### $id

    public integer $id





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#55)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#38)


### $id_employee

    public integer $id_employee





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#43)


### $employee_firstname

    public string $employee_firstname





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#48)


### $employee_lastname

    public string $employee_lastname





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#53)


### $id_stock

    public integer $id_stock





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#58)


### $physical_quantity

    public integer $physical_quantity





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#63)


### $id_stock_mvt_reason

    public integer $id_stock_mvt_reason





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#68)


### $id_order

    public integer $id_order = null





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#73)


### $sign

    public integer $sign





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#78)


### $id_supply_order

    public integer $id_supply_order = null





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#83)


### $last_wa

    public float $last_wa = null





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#88)


### $current_wa

    public float $current_wa = null





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#93)


### $price_te

    public float $price_te





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#98)


### $referer

    public integer $referer





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#103)


### $id_product

    public integer $id_product





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#108)


### $id_product_attribute

    public integer $id_product_attribute





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#113)


### $id_warehouse

    public integer $id_warehouse





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#118)


### $id_currency

    public integer $id_currency





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#123)


### $management_type

    public string $management_type





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#128)


### $product_name

    public mixed $product_name





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#133)


### $ean13

    public string $ean13





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#138)


### $upc

    public string $upc





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#143)


### $reference

    public string $reference





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#148)


### $definition

    public array $definition = array()





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/stock/StockMvtWS.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#139)


### $webserviceParameters

    protected array $webserviceParameters = array()





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#127)


### $tables_assoc

    protected Array $tables_assoc = array('id_product' => array('table' => 's'), 'id_product_attribute' => array('table' => 's'), 'id_warehouse' => array('table' => 's'), 'id_currency' => array('table' => 's'), 'management_type' => array('table' => 'w'), 'ean13' => array('table' => 's'), 'upc' => array('table' => 's'), 'reference' => array('table' => 's'))

Associations tables for attributes that require different tables than stated in ObjectModel::definition



* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 205](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#205)


### $id_lang

    protected integer $id_lang = null





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#58)


### $id_shop

    protected integer $id_shop = null





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#61)


### $id_shop_list

    public array $id_shop_list = null





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#64)


### $get_shop_from_context

    protected boolean $get_shop_from_context = true





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#67)


### $fieldsRequiredDatabase

    protected array $fieldsRequiredDatabase = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/stock/StockMvtWS.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#70)


### $table

    protected string $table





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#76)


### $identifier

    protected string $identifier





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#82)


### $fieldsRequired

    protected array $fieldsRequired = array()





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#88)


### $fieldsSize

    protected array $fieldsSize = array()





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#94)


### $fieldsValidate

    protected array $fieldsValidate = array()





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#100)


### $fieldsRequiredLang

    protected array $fieldsRequiredLang = array()





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#106)


### $fieldsSizeLang

    protected array $fieldsSizeLang = array()





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#112)


### $fieldsValidateLang

    protected array $fieldsValidateLang = array()





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#118)


### $tables

    protected array $tables = array()





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#124)


### $image_dir

    protected string $image_dir = null





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#130)


### $image_format

    protected String $image_format = 'jpg'





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#133)


### $loaded_classes

    protected array $loaded_classes = array()

Holds compiled definitions of each ObjectModel class.

Values are assigned during object initialization.

* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/stock/StockMvtWS.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#147)


### $def

    protected array $def





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#150)


### $update_fields

    protected array $update_fields = null





* Visibility: **protected**
* This property is defined in [classes/stock/StockMvtWS.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#153)


### $db

    protected \Db $db = false





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/stock/StockMvtWS.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#156)


### $force_id

    public boolean $force_id = false





* Visibility: **public**
* This property is defined in [classes/stock/StockMvtWS.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#159)


### $cache_objects

    protected boolean $cache_objects = true





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/stock/StockMvtWS.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#164)


Methods
-------


### __construct

    mixed ObjectModelCore::__construct(integer|null $id, integer|null $id_lang, integer|null $id_shop)

Builds the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#201)


#### Arguments
* $id **integer|null** - &lt;p&gt;If specified, loads and existing object from DB (optional).&lt;/p&gt;
* $id_lang **integer|null** - &lt;p&gt;Required if object is multilingual (optional).&lt;/p&gt;
* $id_shop **integer|null** - &lt;p&gt;ID shop for objects with multishop tables.&lt;/p&gt;



### getWebserviceObjectList

    array|null ObjectModelCore::getWebserviceObjectList(string $sql_join, string $sql_filter, string $sql_sort, string $sql_limit)

Returns webservice object list.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1279)


#### Arguments
* $sql_join **string**
* $sql_filter **string**
* $sql_sort **string**
* $sql_limit **string**



### getWSProductName

    mixed StockMvtWSCore::getWSProductName()

Webservice : getter for the product name



* Visibility: **public**
* This method is defined in [classes/stock/StockMvtWS.php line 286](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#286)




### getRepositoryClassName

    string Core_Foundation_Database_EntityInterface::getRepositoryClassName()

Returns the name of the repository class for this entity.

If unspecified, a generic repository will be used for the entity.

* Visibility: **public**
* This method is **static**.
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)
* This method is defined in [classes/stock/StockMvtWS.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#35)




### getValidationRules

    array ObjectModelCore::getValidationRules(string $class)

Returns object validation rules (fields validity)



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#178)


#### Arguments
* $class **string** - &lt;p&gt;Child class name for static use (optional)&lt;/p&gt;



### getFields

    array ObjectModelCore::getFields()

Prepare fields for ObjectModel class (add, update)
All fields are verified (pSQL, intval, .

..)

* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 244](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#244)




### getFieldsShop

    array ObjectModelCore::getFieldsShop()

Prepare fields for multishop
Fields are not validated here, we consider they are already validated in getFields() method,
this is not the best solution but this is the only one possible for retro compatibility.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#270)




### getFieldsLang

    array ObjectModelCore::getFieldsLang()

Prepare multilang fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 288](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#288)




### formatFields

    array ObjectModelCore::formatFields(integer $type, integer $id_lang)

Formats values of each fields.



* Visibility: **protected**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 327](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#327)


#### Arguments
* $type **integer** - &lt;p&gt;FORMAT_COMMON or FORMAT_LANG or FORMAT_SHOP&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;If this parameter is given, only take lang fields&lt;/p&gt;



### formatValue

    mixed ObjectModelCore::formatValue(mixed $value, integer $type, boolean $with_quotes, boolean $purify, boolean $allow_null)

Formats a value



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#381)


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
* This method is defined in [classes/stock/StockMvtWS.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#37)




### add

    boolean ObjectModelCore::add(boolean $auto_date, boolean $null_values)

Adds current object to the database



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 458](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#458)


#### Arguments
* $auto_date **boolean**
* $null_values **boolean**



### duplicateObject

    \ObjectModel|false ObjectModelCore::duplicateObject()

Takes current object ID, gets its values from database,
saves them in a new row and loads newly saved values as a new object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#549)




### update

    boolean ObjectModelCore::update(boolean $null_values)

Updates the current object in the database



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 619](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#619)


#### Arguments
* $null_values **boolean**



### delete

    mixed Core_Foundation_Database_EntityInterface::delete()





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)
* This method is defined in [classes/stock/StockMvtWS.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#39)




### deleteSelection

    boolean ObjectModelCore::deleteSelection(array $ids)

Deletes multiple objects from the database at once



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 790](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#790)


#### Arguments
* $ids **array** - &lt;p&gt;Array of objects IDs.&lt;/p&gt;



### toggleStatus

    boolean ObjectModelCore::toggleStatus()

Toggles object status in database



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 807](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#807)




### getTranslationsFields

    array ObjectModelCore::getTranslationsFields(array $fields_array)





* Visibility: **protected**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 831](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#831)


#### Arguments
* $fields_array **array**



### makeTranslationFields

    mixed ObjectModelCore::makeTranslationFields(array $fields, array $fields_array, integer $id_language)





* Visibility: **protected**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#854)


#### Arguments
* $fields **array**
* $fields_array **array**
* $id_language **integer**



### validateFields

    boolean|string ObjectModelCore::validateFields(boolean $die, boolean $error_return)

Checks if object field values are valid before database interaction



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 895](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#895)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### validateFieldsLang

    boolean|string ObjectModelCore::validateFieldsLang(boolean $die, boolean $error_return)

Checks if multilingual object field values are valid before database interaction.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#927)


#### Arguments
* $die **boolean**
* $error_return **boolean**



### validateField

    true|string ObjectModelCore::validateField(string $field, mixed $value, integer|null $id_lang, array $skip, boolean $human_errors)

Validate a single field



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 977](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#977)


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
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1083](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1083)


#### Arguments
* $field **string** - &lt;p&gt;Field name&lt;/p&gt;
* $class **string** - &lt;p&gt;ObjectModel class name&lt;/p&gt;
* $htmlentities **boolean** - &lt;p&gt;If true, applies htmlentities() to result string&lt;/p&gt;
* $context **[Context](ContextCore)|null** - &lt;p&gt;Context object&lt;/p&gt;



### validateControler

    array ObjectModelCore::validateControler(boolean $htmlentities)





* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1105)


#### Arguments
* $htmlentities **boolean**



### validateController

    array ObjectModelCore::validateController(boolean $htmlentities)

Validates submitted values and returns an array of errors, if any.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1118)


#### Arguments
* $htmlentities **boolean** - &lt;p&gt;If true, uses htmlentities() for field name translations in errors.&lt;/p&gt;



### getWebserviceParameters

    array ObjectModelCore::getWebserviceParameters(string|null $ws_params_attribute_name)

Returns webservice parameters of this object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1176](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1176)


#### Arguments
* $ws_params_attribute_name **string|null**



### validateFieldsRequiredDatabase

    array ObjectModelCore::validateFieldsRequiredDatabase(boolean $htmlentities)

Validate required fields.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1322](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1322)


#### Arguments
* $htmlentities **boolean**



### getFieldsRequiredDatabase

    array|null ObjectModelCore::getFieldsRequiredDatabase(boolean $all)

Returns an array of required fields



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1355](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1355)


#### Arguments
* $all **boolean** - &lt;p&gt;If true, returns required fields of all object classes.&lt;/p&gt;



### cacheFieldsRequiredDatabase

    mixed ObjectModelCore::cacheFieldsRequiredDatabase(boolean $all)

Caches data about required objects fields in memory



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1368](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1368)


#### Arguments
* $all **boolean** - &lt;p&gt;If true, caches required fields of all object classes.&lt;/p&gt;



### addFieldsRequiredDatabase

    boolean ObjectModelCore::addFieldsRequiredDatabase(array $fields)

Sets required field for this class in the database.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1390](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1390)


#### Arguments
* $fields **array**



### clearCache

    mixed ObjectModelCore::clearCache(boolean $all)

Clears cache entries that have this object's ID.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1414](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1414)


#### Arguments
* $all **boolean** - &lt;p&gt;If true, clears cache for all objects&lt;/p&gt;



### isAssociatedToShop

    boolean ObjectModelCore::isAssociatedToShop(integer|null $id_shop)

Checks if current object is associated to a shop.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1430](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1430)


#### Arguments
* $id_shop **integer|null**



### associateTo

    boolean|void ObjectModelCore::associateTo(integer|array $id_shops)

This function associate an item to its context



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1464)


#### Arguments
* $id_shops **integer|array**



### getAssociatedShops

    array ObjectModelCore::getAssociatedShops()

Gets the list of associated shop IDs



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1499](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1499)




### duplicateShops

    boolean|void ObjectModelCore::duplicateShops($id)

Copies shop association data from object with specified ID.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1523)


#### Arguments
* $id **mixed**



### hasMultishopEntries

    boolean ObjectModelCore::hasMultishopEntries()

Checks if there is more than one entry in associated shop table for current object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1550](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1550)




### isMultishop

    boolean ObjectModelCore::isMultishop()

Checks if object is multi-shop object.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1564](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1564)




### isMultiShopField

    boolean ObjectModelCore::isMultiShopField(string $field)

Checks if a field is a multi-shop field.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1576](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1576)


#### Arguments
* $field **string**



### isLangMultishop

    boolean ObjectModelCore::isLangMultishop()

Checks if the object is both multi-language and multi-shop.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1586)




### updateMultishopTable

    boolean ObjectModelCore::updateMultishopTable(string $classname, array $data, string $where, string $specific_where)

Updates a table and splits the common datas and the shop datas.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1602](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1602)


#### Arguments
* $classname **string**
* $data **array**
* $where **string**
* $specific_where **string** - &lt;p&gt;Only executed for common table&lt;/p&gt;



### deleteImage

    boolean ObjectModelCore::deleteImage(boolean $force_delete)

Delete images associated with the object



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1643](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1643)


#### Arguments
* $force_delete **boolean**



### existsInDatabase

    boolean ObjectModelCore::existsInDatabase(integer $id_entity, string $table)

Checks if an object exists in database.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1686](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1686)


#### Arguments
* $id_entity **integer**
* $table **string**



### isCurrentlyUsed

    boolean ObjectModelCore::isCurrentlyUsed(string|null $table, boolean $has_active_column)

Checks if an object type exists in the database.



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1706](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1706)


#### Arguments
* $table **string|null** - &lt;p&gt;Name of table linked to entity&lt;/p&gt;
* $has_active_column **boolean** - &lt;p&gt;True if the table has an active column&lt;/p&gt;



### hydrate

    mixed Core_Foundation_Database_EntityInterface::hydrate(array $keyValueData)





* Visibility: **public**
* This method is defined by [Core_Foundation_Database_EntityInterface](Core_Foundation_Database_EntityInterface)
* This method is defined in [classes/stock/StockMvtWS.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#41)


#### Arguments
* $keyValueData **array**



### hydrateCollection

    array ObjectModelCore::hydrateCollection(string $class, array $datas, integer|null $id_lang)

Fill (hydrate) a list of objects in order to get a collection of these objects



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1755](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1755)


#### Arguments
* $class **string** - &lt;p&gt;Class of objects to hydrate&lt;/p&gt;
* $datas **array** - &lt;p&gt;List of data (multi-dimensional array)&lt;/p&gt;
* $id_lang **integer|null**



### getDefinition

    array ObjectModelCore::getDefinition(string $class, string|null $field)

Returns object definition



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1809](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1809)


#### Arguments
* $class **string** - &lt;p&gt;Name of object&lt;/p&gt;
* $field **string|null** - &lt;p&gt;Name of field if we want the definition of one field only&lt;/p&gt;



### setDefinitionRetrocompatibility

    mixed ObjectModelCore::setDefinitionRetrocompatibility()

Retrocompatibility for classes without $definition static



* Visibility: **protected**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1855](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1855)




### getFieldByLang

    mixed ObjectModelCore::getFieldByLang(string $field_name, integer|null $id_lang)

Return the field value for the specified language if the field is multilang,
else the field value.



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1927](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1927)


#### Arguments
* $field_name **string**
* $id_lang **integer|null**



### setFieldsToUpdate

    mixed ObjectModelCore::setFieldsToUpdate(array $fields)

Set a list of specific fields to update
array(field1 => true, field2 => false,
langfield1 => array(1 => true, 2 => false))



* Visibility: **public**
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1953](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1953)


#### Arguments
* $fields **array**



### enableCache

    mixed ObjectModelCore::enableCache()

Enables object caching



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1961](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1961)




### disableCache

    mixed ObjectModelCore::disableCache()

Disables object caching



* Visibility: **public**
* This method is **static**.
* This method is defined by [ObjectModelCore](ObjectModelCore)
* This method is defined in [classes/stock/StockMvtWS.php line 1969](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockMvtWS.php#1969)



