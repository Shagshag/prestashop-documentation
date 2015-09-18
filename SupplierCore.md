SupplierCore
===============






* Class name: SupplierCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $id_supplier

    public integer $id_supplier





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $description

    public string $description





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $link_rewrite

    public string $link_rewrite





* Visibility: **public**


### $meta_title

    public string $meta_title





* Visibility: **public**


### $meta_keywords

    public string $meta_keywords





* Visibility: **public**


### $meta_description

    public string $meta_description





* Visibility: **public**


### $active

    public boolean $active





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'supplier', 'primary' => 'id_supplier', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isCatalogName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('link_rewrite' => array('sqlId' => 'link_rewrite')))





* Visibility: **protected**


### $cache_name

    protected mixed $cache_name = array()

Return name from id



* Visibility: **protected**
* This property is **static**.


Methods
-------


### __construct

    mixed SupplierCore::__construct($id, $id_lang)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### getLink

    mixed SupplierCore::getLink()





* Visibility: **public**




### getSuppliers

    array SupplierCore::getSuppliers($get_nb_products, $id_lang, $active, $p, $n, $all_groups)

Return suppliers



* Visibility: **public**
* This method is **static**.


#### Arguments
* $get_nb_products **mixed**
* $id_lang **mixed**
* $active **mixed**
* $p **mixed**
* $n **mixed**
* $all_groups **mixed**



### getNameById

    mixed SupplierCore::getNameById($id_supplier)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_supplier **mixed**



### getIdByName

    mixed SupplierCore::getIdByName($name)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **mixed**



### getProducts

    mixed SupplierCore::getProducts($id_supplier, $id_lang, $p, $n, $order_by, $order_way, $get_total, $active, $active_category)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_supplier **mixed**
* $id_lang **mixed**
* $p **mixed**
* $n **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $get_total **mixed**
* $active **mixed**
* $active_category **mixed**



### getProductsLite

    mixed SupplierCore::getProductsLite($id_lang)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**



### supplierExists

    mixed SupplierCore::supplierExists($id_supplier)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_supplier **mixed**



### delete

    mixed SupplierCore::delete()





* Visibility: **public**




### getProductInformationsBySupplier

    array SupplierCore::getProductInformationsBySupplier(integer $id_supplier, integer $id_product, integer $id_product_attribute)

Gets product informations



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_supplier **integer**
* $id_product **integer**
* $id_product_attribute **integer**


