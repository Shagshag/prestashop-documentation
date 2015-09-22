AdminImportControllerCore
===============






* Class name: AdminImportControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)

* This class is defined in [controllers/admin/AdminImportController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#40)





Properties
----------


### $column_mask

    public mixed $column_mask





* Visibility: **public**
* This property is **static**.
* This property is defined in [controllers/admin/AdminImportController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#42)


### $entities

    public mixed $entities = array()





* Visibility: **public**
* This property is defined in [controllers/admin/AdminImportController.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#44)


### $available_fields

    public mixed $available_fields = array()





* Visibility: **public**
* This property is defined in [controllers/admin/AdminImportController.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#46)


### $required_fields

    public mixed $required_fields = array()





* Visibility: **public**
* This property is defined in [controllers/admin/AdminImportController.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#48)


### $cache_image_deleted

    public mixed $cache_image_deleted = array()





* Visibility: **public**
* This property is defined in [controllers/admin/AdminImportController.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#50)


### $default_values

    public mixed $default_values = array()





* Visibility: **public**
* This property is **static**.
* This property is defined in [controllers/admin/AdminImportController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#52)


### $validators

    public mixed $validators = array('active' => array('AdminImportController', 'getBoolean'), 'tax_rate' => array('AdminImportController', 'getPrice'), 'price_tex' => array('AdminImportController', 'getPrice'), 'price_tin' => array('AdminImportController', 'getPrice'), 'reduction_price' => array('AdminImportController', 'getPrice'), 'reduction_percent' => array('AdminImportController', 'getPrice'), 'wholesale_price' => array('AdminImportController', 'getPrice'), 'ecotax' => array('AdminImportController', 'getPrice'), 'name' => array('AdminImportController', 'createMultiLangField'), 'description' => array('AdminImportController', 'createMultiLangField'), 'description_short' => array('AdminImportController', 'createMultiLangField'), 'meta_title' => array('AdminImportController', 'createMultiLangField'), 'meta_keywords' => array('AdminImportController', 'createMultiLangField'), 'meta_description' => array('AdminImportController', 'createMultiLangField'), 'link_rewrite' => array('AdminImportController', 'createMultiLangField'), 'available_now' => array('AdminImportController', 'createMultiLangField'), 'available_later' => array('AdminImportController', 'createMultiLangField'), 'category' => array('AdminImportController', 'split'), 'online_only' => array('AdminImportController', 'getBoolean'))





* Visibility: **public**
* This property is **static**.
* This property is defined in [controllers/admin/AdminImportController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#54)


### $separator

    public mixed $separator





* Visibility: **public**
* This property is defined in [controllers/admin/AdminImportController.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#78)


### $multiple_value_separator

    public mixed $multiple_value_separator





* Visibility: **public**
* This property is defined in [controllers/admin/AdminImportController.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#79)


Methods
-------


### __construct

    mixed AdminImportControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#81)




### setMedia

    mixed AdminImportControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 509](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#509)




### renderForm

    mixed AdminImportControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 530](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#530)




### ajaxProcessuploadCsv

    mixed AdminImportControllerCore::ajaxProcessuploadCsv()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 631](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#631)




### renderView

    mixed AdminImportControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 670](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#670)




### initToolbar

    mixed AdminImportControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 720](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#720)




### generateContentTable

    mixed AdminImportControllerCore::generateContentTable($current_table, $nb_column, $handle, $glue)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImportController.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#743)


#### Arguments
* $current_table **mixed**
* $nb_column **mixed**
* $handle **mixed**
* $glue **mixed**



### init

    mixed AdminImportControllerCore::init()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 779](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#779)




### initContent

    mixed AdminImportControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 787](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#787)




### rewindBomAware

    mixed AdminImportControllerCore::rewindBomAware($handle)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImportController.php line 813](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#813)


#### Arguments
* $handle **mixed**



### getBoolean

    mixed AdminImportControllerCore::getBoolean($field)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImportController.php line 825](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#825)


#### Arguments
* $field **mixed**



### getPrice

    mixed AdminImportControllerCore::getPrice($field)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImportController.php line 830](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#830)


#### Arguments
* $field **mixed**



### split

    mixed AdminImportControllerCore::split($field)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImportController.php line 837](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#837)


#### Arguments
* $field **mixed**



### createMultiLangField

    mixed AdminImportControllerCore::createMultiLangField($field)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImportController.php line 868](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#868)


#### Arguments
* $field **mixed**



### getTypeValuesOptions

    mixed AdminImportControllerCore::getTypeValuesOptions($nb_c)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImportController.php line 878](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#878)


#### Arguments
* $nb_c **mixed**



### getAvailableFields

    mixed AdminImportControllerCore::getAvailableFields($in_array)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 904](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#904)


#### Arguments
* $in_array **mixed**



### receiveTab

    mixed AdminImportControllerCore::receiveTab()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImportController.php line 933](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#933)




### getMaskedRow

    mixed AdminImportControllerCore::getMaskedRow($row)





* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImportController.php line 943](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#943)


#### Arguments
* $row **mixed**



### setDefaultValues

    mixed AdminImportControllerCore::setDefaultValues($info)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImportController.php line 955](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#955)


#### Arguments
* $info **mixed**



### setEntityDefaultValues

    mixed AdminImportControllerCore::setEntityDefaultValues($entity)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImportController.php line 964](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#964)


#### Arguments
* $entity **mixed**



### fillInfo

    mixed AdminImportControllerCore::fillInfo($infos, $key, $entity)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImportController.php line 974](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#974)


#### Arguments
* $infos **mixed**
* $key **mixed**
* $entity **mixed**



### arrayWalk

    boolean AdminImportControllerCore::arrayWalk($array, $funcname, mixed $user_data)





* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImportController.php line 998](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#998)


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
* This method is defined in [controllers/admin/AdminImportController.php line 1024](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#1024)


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
* This method is defined in [controllers/admin/AdminImportController.php line 1115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#1115)


#### Arguments
* $tgt_width **mixed**
* $tgt_height **mixed**
* $path_infos **mixed**



### categoryImport

    mixed AdminImportControllerCore::categoryImport()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 1128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#1128)




### productImport

    mixed AdminImportControllerCore::productImport()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 1324](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#1324)




### productImportCreateCat

    mixed AdminImportControllerCore::productImportCreateCat($default_language_id, $category_name, $id_parent_category)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 1968](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#1968)


#### Arguments
* $default_language_id **mixed**
* $category_name **mixed**
* $id_parent_category **mixed**



### attributeImport

    mixed AdminImportControllerCore::attributeImport()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 2001](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#2001)




### customerImport

    mixed AdminImportControllerCore::customerImport()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 2433](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#2433)




### addressImport

    mixed AdminImportControllerCore::addressImport()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 2642](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#2642)




### manufacturerImport

    mixed AdminImportControllerCore::manufacturerImport()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 2839](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#2839)




### supplierImport

    mixed AdminImportControllerCore::supplierImport()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 2925](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#2925)




### aliasImport

    mixed AdminImportControllerCore::aliasImport()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 3009](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3009)




### supplyOrdersImport

    mixed AdminImportControllerCore::supplyOrdersImport()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 3067](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3067)




### supplyOrdersDetailsImport

    mixed AdminImportControllerCore::supplyOrdersDetailsImport()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 3180](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3180)




### utf8EncodeArray

    mixed AdminImportControllerCore::utf8EncodeArray($array)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 3300](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3300)


#### Arguments
* $array **mixed**



### getNbrColumn

    mixed AdminImportControllerCore::getNbrColumn($handle, $glue)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImportController.php line 3305](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3305)


#### Arguments
* $handle **mixed**
* $glue **mixed**



### usortFiles

    mixed AdminImportControllerCore::usortFiles($a, $b)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImportController.php line 3315](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3315)


#### Arguments
* $a **mixed**
* $b **mixed**



### openCsvFile

    mixed AdminImportControllerCore::openCsvFile()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImportController.php line 3323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3323)




### closeCsvFile

    mixed AdminImportControllerCore::closeCsvFile($handle)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImportController.php line 3343](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3343)


#### Arguments
* $handle **mixed**



### truncateTables

    mixed AdminImportControllerCore::truncateTables($case)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImportController.php line 3348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3348)


#### Arguments
* $case **mixed**



### clearSmartyCache

    mixed AdminImportControllerCore::clearSmartyCache()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 3462](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3462)




### postProcess

    mixed AdminImportControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 3469](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3469)




### setLocale

    mixed AdminImportControllerCore::setLocale()





* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImportController.php line 3586](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3586)




### addProductWarning

    mixed AdminImportControllerCore::addProductWarning($product_name, $product_id, $message)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImportController.php line 3593](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3593)


#### Arguments
* $product_name **mixed**
* $product_id **mixed**
* $message **mixed**



### ajaxProcessSaveImportMatchs

    mixed AdminImportControllerCore::ajaxProcessSaveImportMatchs()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 3599](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3599)




### ajaxProcessLoadImportMatchs

    mixed AdminImportControllerCore::ajaxProcessLoadImportMatchs()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 3620](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3620)




### ajaxProcessDeleteImportMatchs

    mixed AdminImportControllerCore::ajaxProcessDeleteImportMatchs()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImportController.php line 3630](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3630)




### getPath

    mixed AdminImportControllerCore::getPath($file)





* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImportController.php line 3639](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImportController.php#3639)


#### Arguments
* $file **mixed**


