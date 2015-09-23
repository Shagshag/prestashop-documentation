Class AdminImportControllerCore
=====================





* Class name: AdminImportControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminImportController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L40)


Contents
--------


### Properties

* [$available_fields](#property-$available_fields)
* [$cache_image_deleted](#property-$cache_image_deleted)
* [$column_mask](#property-$column_mask)
* [$default_values](#property-$default_values)
* [$entities](#property-$entities)
* [$multiple_value_separator](#property-$multiple_value_separator)
* [$required_fields](#property-$required_fields)
* [$separator](#property-$separator)
* [$validators](#property-$validators)

### Methods

* [__construct](#method-__construct)
* [addProductWarning](#method-addProductWarning)
* [addressImport](#method-addressImport)
* [ajaxProcessDeleteImportMatchs](#method-ajaxProcessDeleteImportMatchs)
* [ajaxProcessLoadImportMatchs](#method-ajaxProcessLoadImportMatchs)
* [ajaxProcessSaveImportMatchs](#method-ajaxProcessSaveImportMatchs)
* [ajaxProcessuploadCsv](#method-ajaxProcessuploadCsv)
* [aliasImport](#method-aliasImport)
* [arrayWalk](#method-arrayWalk)
* [attributeImport](#method-attributeImport)
* [categoryImport](#method-categoryImport)
* [clearSmartyCache](#method-clearSmartyCache)
* [closeCsvFile](#method-closeCsvFile)
* [copyImg](#method-copyImg)
* [createMultiLangField](#method-createMultiLangField)
* [customerImport](#method-customerImport)
* [fillInfo](#method-fillInfo)
* [generateContentTable](#method-generateContentTable)
* [getAvailableFields](#method-getAvailableFields)
* [getBoolean](#method-getBoolean)
* [getMaskedRow](#method-getMaskedRow)
* [getNbrColumn](#method-getNbrColumn)
* [getPath](#method-getPath)
* [getPrice](#method-getPrice)
* [getTypeValuesOptions](#method-getTypeValuesOptions)
* [init](#method-init)
* [initContent](#method-initContent)
* [initToolbar](#method-initToolbar)
* [manufacturerImport](#method-manufacturerImport)
* [openCsvFile](#method-openCsvFile)
* [postProcess](#method-postProcess)
* [productImport](#method-productImport)
* [productImportCreateCat](#method-productImportCreateCat)
* [receiveTab](#method-receiveTab)
* [renderForm](#method-renderForm)
* [renderView](#method-renderView)
* [rewindBomAware](#method-rewindBomAware)
* [setDefaultValues](#method-setDefaultValues)
* [setEntityDefaultValues](#method-setEntityDefaultValues)
* [setLocale](#method-setLocale)
* [setMedia](#method-setMedia)
* [split](#method-split)
* [supplierImport](#method-supplierImport)
* [supplyOrdersDetailsImport](#method-supplyOrdersDetailsImport)
* [supplyOrdersImport](#method-supplyOrdersImport)
* [truncateTables](#method-truncateTables)
* [usortFiles](#method-usortFiles)
* [utf8EncodeArray](#method-utf8EncodeArray)




Properties
----------


### <a name="property-$available_fields"></a>$available_fields

```php
public mixed $available_fields = array()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L46).


### <a name="property-$cache_image_deleted"></a>$cache_image_deleted

```php
public mixed $cache_image_deleted = array()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L50).


### <a name="property-$column_mask"></a>$column_mask

```php
public mixed $column_mask
```





* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminImportController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L42).


### <a name="property-$default_values"></a>$default_values

```php
public mixed $default_values = array()
```





* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminImportController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L52).


### <a name="property-$entities"></a>$entities

```php
public mixed $entities = array()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L44).


### <a name="property-$multiple_value_separator"></a>$multiple_value_separator

```php
public mixed $multiple_value_separator
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L79).


### <a name="property-$required_fields"></a>$required_fields

```php
public mixed $required_fields = array()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L48).


### <a name="property-$separator"></a>$separator

```php
public mixed $separator
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L78).


### <a name="property-$validators"></a>$validators

```php
public mixed $validators = array('active' => array('AdminImportController', 'getBoolean'), 'tax_rate' => array('AdminImportController', 'getPrice'), 'price_tex' => array('AdminImportController', 'getPrice'), 'price_tin' => array('AdminImportController', 'getPrice'), 'reduction_price' => array('AdminImportController', 'getPrice'), 'reduction_percent' => array('AdminImportController', 'getPrice'), 'wholesale_price' => array('AdminImportController', 'getPrice'), 'ecotax' => array('AdminImportController', 'getPrice'), 'name' => array('AdminImportController', 'createMultiLangField'), 'description' => array('AdminImportController', 'createMultiLangField'), 'description_short' => array('AdminImportController', 'createMultiLangField'), 'meta_title' => array('AdminImportController', 'createMultiLangField'), 'meta_keywords' => array('AdminImportController', 'createMultiLangField'), 'meta_description' => array('AdminImportController', 'createMultiLangField'), 'link_rewrite' => array('AdminImportController', 'createMultiLangField'), 'available_now' => array('AdminImportController', 'createMultiLangField'), 'available_later' => array('AdminImportController', 'createMultiLangField'), 'category' => array('AdminImportController', 'split'), 'online_only' => array('AdminImportController', 'getBoolean'))
```





* Visibility: **public**
* This property is **static**.
* Source: [controllers/admin/AdminImportController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L54).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminImportControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L81)




### <a name="method-addProductWarning"></a>addProductWarning

```php
mixed AdminImportControllerCore::addProductWarning($product_name, $product_id, $message)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 3441](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3441)


#### Arguments
* $product_name **mixed**
* $product_id **mixed**
* $message **mixed**



### <a name="method-addressImport"></a>addressImport

```php
mixed AdminImportControllerCore::addressImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 2524](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L2524)




### <a name="method-ajaxProcessDeleteImportMatchs"></a>ajaxProcessDeleteImportMatchs

```php
mixed AdminImportControllerCore::ajaxProcessDeleteImportMatchs()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 3480](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3480)




### <a name="method-ajaxProcessLoadImportMatchs"></a>ajaxProcessLoadImportMatchs

```php
mixed AdminImportControllerCore::ajaxProcessLoadImportMatchs()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 3469](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3469)




### <a name="method-ajaxProcessSaveImportMatchs"></a>ajaxProcessSaveImportMatchs

```php
mixed AdminImportControllerCore::ajaxProcessSaveImportMatchs()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 3447](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3447)




### <a name="method-ajaxProcessuploadCsv"></a>ajaxProcessuploadCsv

```php
mixed AdminImportControllerCore::ajaxProcessuploadCsv()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 624](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L624)




### <a name="method-aliasImport"></a>aliasImport

```php
mixed AdminImportControllerCore::aliasImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 2895](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L2895)




### <a name="method-arrayWalk"></a>arrayWalk

```php
boolean AdminImportControllerCore::arrayWalk($array, $funcname, mixed $user_data)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 975](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L975)


#### Arguments
* $array **mixed**
* $funcname **mixed**
* $user_data **mixed**



### <a name="method-attributeImport"></a>attributeImport

```php
mixed AdminImportControllerCore::attributeImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 1895](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L1895)




### <a name="method-categoryImport"></a>categoryImport

```php
mixed AdminImportControllerCore::categoryImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 1073](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L1073)




### <a name="method-clearSmartyCache"></a>clearSmartyCache

```php
mixed AdminImportControllerCore::clearSmartyCache()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 3312](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3312)




### <a name="method-closeCsvFile"></a>closeCsvFile

```php
mixed AdminImportControllerCore::closeCsvFile($handle)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 3200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3200)


#### Arguments
* $handle **mixed**



### <a name="method-copyImg"></a>copyImg

```php
boolean AdminImportControllerCore::copyImg(integer $id_entity, integer $id_image, string $url, $entity, $regenerate)
```

copyImg copy an image located in $url and save it in a path
according to $entity->$id_entity .

$id_image is used if we need to add a watermark

* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 996](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L996)


#### Arguments
* $id_entity **integer** - id of product or category (set in entity)
* $id_image **integer** - (default null) id of the image if watermark enabled.
* $url **string** - path or url to use
* $entity **mixed**
* $regenerate **mixed**



### <a name="method-createMultiLangField"></a>createMultiLangField

```php
mixed AdminImportControllerCore::createMultiLangField($field)
```





* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 855](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L855)


#### Arguments
* $field **mixed**



### <a name="method-customerImport"></a>customerImport

```php
mixed AdminImportControllerCore::customerImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 2327](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L2327)




### <a name="method-fillInfo"></a>fillInfo

```php
mixed AdminImportControllerCore::fillInfo($infos, $key, $entity)
```





* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 951](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L951)


#### Arguments
* $infos **mixed**
* $key **mixed**
* $entity **mixed**



### <a name="method-generateContentTable"></a>generateContentTable

```php
mixed AdminImportControllerCore::generateContentTable($current_table, $nb_column, $handle, $glue)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L738)


#### Arguments
* $current_table **mixed**
* $nb_column **mixed**
* $handle **mixed**
* $glue **mixed**



### <a name="method-getAvailableFields"></a>getAvailableFields

```php
mixed AdminImportControllerCore::getAvailableFields($in_array)
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 889](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L889)


#### Arguments
* $in_array **mixed**



### <a name="method-getBoolean"></a>getBoolean

```php
mixed AdminImportControllerCore::getBoolean($field)
```





* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 815](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L815)


#### Arguments
* $field **mixed**



### <a name="method-getMaskedRow"></a>getMaskedRow

```php
mixed AdminImportControllerCore::getMaskedRow($row)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 926](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L926)


#### Arguments
* $row **mixed**



### <a name="method-getNbrColumn"></a>getNbrColumn

```php
mixed AdminImportControllerCore::getNbrColumn($handle, $glue)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 3167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3167)


#### Arguments
* $handle **mixed**
* $glue **mixed**



### <a name="method-getPath"></a>getPath

```php
mixed AdminImportControllerCore::getPath($file)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 3490](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3490)


#### Arguments
* $file **mixed**



### <a name="method-getPrice"></a>getPrice

```php
mixed AdminImportControllerCore::getPrice($field)
```





* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 820](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L820)


#### Arguments
* $field **mixed**



### <a name="method-getTypeValuesOptions"></a>getTypeValuesOptions

```php
mixed AdminImportControllerCore::getTypeValuesOptions($nb_c)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 864](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L864)


#### Arguments
* $nb_c **mixed**



### <a name="method-init"></a>init

```php
mixed AdminImportControllerCore::init()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 770](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L770)




### <a name="method-initContent"></a>initContent

```php
mixed AdminImportControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 777](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L777)




### <a name="method-initToolbar"></a>initToolbar

```php
mixed AdminImportControllerCore::initToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 715](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L715)




### <a name="method-manufacturerImport"></a>manufacturerImport

```php
mixed AdminImportControllerCore::manufacturerImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 2738](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L2738)




### <a name="method-openCsvFile"></a>openCsvFile

```php
mixed AdminImportControllerCore::openCsvFile()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 3183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3183)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminImportControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 3319](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3319)




### <a name="method-productImport"></a>productImport

```php
mixed AdminImportControllerCore::productImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 1264](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L1264)




### <a name="method-productImportCreateCat"></a>productImportCreateCat

```php
mixed AdminImportControllerCore::productImportCreateCat($default_language_id, $category_name, $id_parent_category)
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 1868](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L1868)


#### Arguments
* $default_language_id **mixed**
* $category_name **mixed**
* $id_parent_category **mixed**



### <a name="method-receiveTab"></a>receiveTab

```php
mixed AdminImportControllerCore::receiveTab()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 918](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L918)




### <a name="method-renderForm"></a>renderForm

```php
mixed AdminImportControllerCore::renderForm()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 530](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L530)




### <a name="method-renderView"></a>renderView

```php
mixed AdminImportControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 667](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L667)




### <a name="method-rewindBomAware"></a>rewindBomAware

```php
mixed AdminImportControllerCore::rewindBomAware($handle)
```





* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 805](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L805)


#### Arguments
* $handle **mixed**



### <a name="method-setDefaultValues"></a>setDefaultValues

```php
mixed AdminImportControllerCore::setDefaultValues($info)
```





* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 936](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L936)


#### Arguments
* $info **mixed**



### <a name="method-setEntityDefaultValues"></a>setEntityDefaultValues

```php
mixed AdminImportControllerCore::setEntityDefaultValues($entity)
```





* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 943](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L943)


#### Arguments
* $entity **mixed**



### <a name="method-setLocale"></a>setLocale

```php
mixed AdminImportControllerCore::setLocale()
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 3434](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3434)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminImportControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 510](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L510)




### <a name="method-split"></a>split

```php
mixed AdminImportControllerCore::split($field)
```





* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 827](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L827)


#### Arguments
* $field **mixed**



### <a name="method-supplierImport"></a>supplierImport

```php
mixed AdminImportControllerCore::supplierImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 2817](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L2817)




### <a name="method-supplyOrdersDetailsImport"></a>supplyOrdersDetailsImport

```php
mixed AdminImportControllerCore::supplyOrdersDetailsImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 3050](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3050)




### <a name="method-supplyOrdersImport"></a>supplyOrdersImport

```php
mixed AdminImportControllerCore::supplyOrdersImport()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 2949](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L2949)




### <a name="method-truncateTables"></a>truncateTables

```php
mixed AdminImportControllerCore::truncateTables($case)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImportController.php line 3205](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3205)


#### Arguments
* $case **mixed**



### <a name="method-usortFiles"></a>usortFiles

```php
mixed AdminImportControllerCore::usortFiles($a, $b)
```





* Visibility: **protected**
* This method is **static**.
* Source: [controllers/admin/AdminImportController.php line 3176](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3176)


#### Arguments
* $a **mixed**
* $b **mixed**



### <a name="method-utf8EncodeArray"></a>utf8EncodeArray

```php
mixed AdminImportControllerCore::utf8EncodeArray($array)
```





* Visibility: **public**
* Source: [controllers/admin/AdminImportController.php line 3162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImportController.php#L3162)


#### Arguments
* $array **mixed**


