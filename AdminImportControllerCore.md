AdminImportControllerCore
===============






* Class name: AdminImportControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $column_mask

    public mixed $column_mask





* Visibility: **public**
* This property is **static**.


### $entities

    public mixed $entities = array()





* Visibility: **public**


### $available_fields

    public mixed $available_fields = array()





* Visibility: **public**


### $required_fields

    public mixed $required_fields = array()





* Visibility: **public**


### $cache_image_deleted

    public mixed $cache_image_deleted = array()





* Visibility: **public**


### $default_values

    public mixed $default_values = array()





* Visibility: **public**
* This property is **static**.


### $validators

    public mixed $validators = array('active' => array('AdminImportController', 'getBoolean'), 'tax_rate' => array('AdminImportController', 'getPrice'), 'price_tex' => array('AdminImportController', 'getPrice'), 'price_tin' => array('AdminImportController', 'getPrice'), 'reduction_price' => array('AdminImportController', 'getPrice'), 'reduction_percent' => array('AdminImportController', 'getPrice'), 'wholesale_price' => array('AdminImportController', 'getPrice'), 'ecotax' => array('AdminImportController', 'getPrice'), 'name' => array('AdminImportController', 'createMultiLangField'), 'description' => array('AdminImportController', 'createMultiLangField'), 'description_short' => array('AdminImportController', 'createMultiLangField'), 'meta_title' => array('AdminImportController', 'createMultiLangField'), 'meta_keywords' => array('AdminImportController', 'createMultiLangField'), 'meta_description' => array('AdminImportController', 'createMultiLangField'), 'link_rewrite' => array('AdminImportController', 'createMultiLangField'), 'available_now' => array('AdminImportController', 'createMultiLangField'), 'available_later' => array('AdminImportController', 'createMultiLangField'), 'category' => array('AdminImportController', 'split'), 'online_only' => array('AdminImportController', 'getBoolean'))





* Visibility: **public**
* This property is **static**.


### $separator

    public mixed $separator





* Visibility: **public**


### $multiple_value_separator

    public mixed $multiple_value_separator





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminImportControllerCore::__construct()





* Visibility: **public**




### setMedia

    mixed AdminImportControllerCore::setMedia()





* Visibility: **public**




### renderForm

    mixed AdminImportControllerCore::renderForm()





* Visibility: **public**




### ajaxProcessuploadCsv

    mixed AdminImportControllerCore::ajaxProcessuploadCsv()





* Visibility: **public**




### renderView

    mixed AdminImportControllerCore::renderView()





* Visibility: **public**




### initToolbar

    mixed AdminImportControllerCore::initToolbar()





* Visibility: **public**




### generateContentTable

    mixed AdminImportControllerCore::generateContentTable($current_table, $nb_column, $handle, $glue)





* Visibility: **protected**


#### Arguments
* $current_table **mixed**
* $nb_column **mixed**
* $handle **mixed**
* $glue **mixed**



### init

    mixed AdminImportControllerCore::init()





* Visibility: **public**




### initContent

    mixed AdminImportControllerCore::initContent()





* Visibility: **public**




### rewindBomAware

    mixed AdminImportControllerCore::rewindBomAware($handle)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $handle **mixed**



### getBoolean

    mixed AdminImportControllerCore::getBoolean($field)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $field **mixed**



### getPrice

    mixed AdminImportControllerCore::getPrice($field)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $field **mixed**



### split

    mixed AdminImportControllerCore::split($field)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $field **mixed**



### createMultiLangField

    mixed AdminImportControllerCore::createMultiLangField($field)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $field **mixed**



### getTypeValuesOptions

    mixed AdminImportControllerCore::getTypeValuesOptions($nb_c)





* Visibility: **protected**


#### Arguments
* $nb_c **mixed**



### getAvailableFields

    mixed AdminImportControllerCore::getAvailableFields($in_array)





* Visibility: **public**


#### Arguments
* $in_array **mixed**



### receiveTab

    mixed AdminImportControllerCore::receiveTab()





* Visibility: **protected**




### getMaskedRow

    mixed AdminImportControllerCore::getMaskedRow($row)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $row **mixed**



### setDefaultValues

    mixed AdminImportControllerCore::setDefaultValues($info)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $info **mixed**



### setEntityDefaultValues

    mixed AdminImportControllerCore::setEntityDefaultValues($entity)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $entity **mixed**



### fillInfo

    mixed AdminImportControllerCore::fillInfo($infos, $key, $entity)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $infos **mixed**
* $key **mixed**
* $entity **mixed**



### arrayWalk

    boolean AdminImportControllerCore::arrayWalk($array, $funcname, mixed $user_data)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $array **mixed**
* $funcname **mixed**
* $user_data **mixed**



### copyImg

    boolean AdminImportControllerCore::copyImg(integer $id_entity, integer $id_image, string $url, string $entity, boolean $regenerate)

copyImg copy an image located in $url and save it in a path
according to $entity->$id_entity .

$id_image is used if we need to add a watermark

* Visibility: **protected**
* This method is **static**.


#### Arguments
* $id_entity **integer** - &lt;p&gt;id of product or category (set in entity)&lt;/p&gt;
* $id_image **integer** - &lt;p&gt;(default null) id of the image if watermark enabled.&lt;/p&gt;
* $url **string** - &lt;p&gt;path or url to use&lt;/p&gt;
* $entity **string** - &lt;p&gt;&#039;products&#039; or &#039;categories&#039;&lt;/p&gt;
* $regenerate **boolean**



### get_best_path

    mixed AdminImportControllerCore::get_best_path($tgt_width, $tgt_height, $path_infos)





* Visibility: **private**
* This method is **static**.


#### Arguments
* $tgt_width **mixed**
* $tgt_height **mixed**
* $path_infos **mixed**



### categoryImport

    mixed AdminImportControllerCore::categoryImport()





* Visibility: **public**




### productImport

    mixed AdminImportControllerCore::productImport()





* Visibility: **public**




### productImportCreateCat

    mixed AdminImportControllerCore::productImportCreateCat($default_language_id, $category_name, $id_parent_category)





* Visibility: **public**


#### Arguments
* $default_language_id **mixed**
* $category_name **mixed**
* $id_parent_category **mixed**



### attributeImport

    mixed AdminImportControllerCore::attributeImport()





* Visibility: **public**




### customerImport

    mixed AdminImportControllerCore::customerImport()





* Visibility: **public**




### addressImport

    mixed AdminImportControllerCore::addressImport()





* Visibility: **public**




### manufacturerImport

    mixed AdminImportControllerCore::manufacturerImport()





* Visibility: **public**




### supplierImport

    mixed AdminImportControllerCore::supplierImport()





* Visibility: **public**




### aliasImport

    mixed AdminImportControllerCore::aliasImport()





* Visibility: **public**




### supplyOrdersImport

    mixed AdminImportControllerCore::supplyOrdersImport()





* Visibility: **public**




### supplyOrdersDetailsImport

    mixed AdminImportControllerCore::supplyOrdersDetailsImport()





* Visibility: **public**




### utf8EncodeArray

    mixed AdminImportControllerCore::utf8EncodeArray($array)





* Visibility: **public**


#### Arguments
* $array **mixed**



### getNbrColumn

    mixed AdminImportControllerCore::getNbrColumn($handle, $glue)





* Visibility: **protected**


#### Arguments
* $handle **mixed**
* $glue **mixed**



### usortFiles

    mixed AdminImportControllerCore::usortFiles($a, $b)





* Visibility: **protected**
* This method is **static**.


#### Arguments
* $a **mixed**
* $b **mixed**



### openCsvFile

    mixed AdminImportControllerCore::openCsvFile()





* Visibility: **protected**




### closeCsvFile

    mixed AdminImportControllerCore::closeCsvFile($handle)





* Visibility: **protected**


#### Arguments
* $handle **mixed**



### truncateTables

    mixed AdminImportControllerCore::truncateTables($case)





* Visibility: **protected**


#### Arguments
* $case **mixed**



### clearSmartyCache

    mixed AdminImportControllerCore::clearSmartyCache()





* Visibility: **public**




### postProcess

    mixed AdminImportControllerCore::postProcess()





* Visibility: **public**




### setLocale

    mixed AdminImportControllerCore::setLocale()





* Visibility: **public**
* This method is **static**.




### addProductWarning

    mixed AdminImportControllerCore::addProductWarning($product_name, $product_id, $message)





* Visibility: **protected**


#### Arguments
* $product_name **mixed**
* $product_id **mixed**
* $message **mixed**



### ajaxProcessSaveImportMatchs

    mixed AdminImportControllerCore::ajaxProcessSaveImportMatchs()





* Visibility: **public**




### ajaxProcessLoadImportMatchs

    mixed AdminImportControllerCore::ajaxProcessLoadImportMatchs()





* Visibility: **public**




### ajaxProcessDeleteImportMatchs

    mixed AdminImportControllerCore::ajaxProcessDeleteImportMatchs()





* Visibility: **public**




### getPath

    mixed AdminImportControllerCore::getPath($file)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $file **mixed**


