SupplierCore
===============






* Class name: SupplierCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/Supplier.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#27)





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/Supplier.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#29)


### $id_supplier

    public integer $id_supplier





* Visibility: **public**
* This property is defined in [classes/Supplier.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#32)


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Supplier.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#35)


### $description

    public string $description





* Visibility: **public**
* This property is defined in [classes/Supplier.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#38)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/Supplier.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#41)


### $date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/Supplier.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#44)


### $link_rewrite

    public string $link_rewrite





* Visibility: **public**
* This property is defined in [classes/Supplier.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#47)


### $meta_title

    public string $meta_title





* Visibility: **public**
* This property is defined in [classes/Supplier.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#50)


### $meta_keywords

    public string $meta_keywords





* Visibility: **public**
* This property is defined in [classes/Supplier.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#53)


### $meta_description

    public string $meta_description





* Visibility: **public**
* This property is defined in [classes/Supplier.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#56)


### $active

    public boolean $active





* Visibility: **public**
* This property is defined in [classes/Supplier.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#59)


### $definition

    public mixed $definition = array('table' => 'supplier', 'primary' => 'id_supplier', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isCatalogName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Supplier.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#64)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('link_rewrite' => array('sqlId' => 'link_rewrite')))





* Visibility: **protected**
* This property is defined in [classes/Supplier.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#82)


### $cache_name

    protected mixed $cache_name = array()

Return name from id



* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Supplier.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#187)


Methods
-------


### __construct

    mixed SupplierCore::__construct($id, $id_lang)





* Visibility: **public**
* This method is defined in [classes/Supplier.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#88)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### getLink

    mixed SupplierCore::getLink()





* Visibility: **public**
* This method is defined in [classes/Supplier.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#96)




### getSuppliers

    array SupplierCore::getSuppliers($get_nb_products, $id_lang, $active, $p, $n, $all_groups)

Return suppliers



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Supplier.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#106)


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
* This method is defined in [classes/Supplier.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#188)


#### Arguments
* $id_supplier **mixed**



### getIdByName

    mixed SupplierCore::getIdByName($name)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Supplier.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#197)


#### Arguments
* $name **mixed**



### getProducts

    mixed SupplierCore::getProducts($id_supplier, $id_lang, $p, $n, $order_by, $order_way, $get_total, $active, $active_category)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Supplier.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#211)


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
* This method is defined in [classes/Supplier.php line 337](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#337)


#### Arguments
* $id_lang **mixed**



### supplierExists

    mixed SupplierCore::supplierExists($id_supplier)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Supplier.php line 371](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#371)


#### Arguments
* $id_supplier **mixed**



### delete

    mixed SupplierCore::delete()





* Visibility: **public**
* This method is defined in [classes/Supplier.php line 385](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#385)




### getProductInformationsBySupplier

    array SupplierCore::getProductInformationsBySupplier(integer $id_supplier, integer $id_product, integer $id_product_attribute)

Gets product informations



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Supplier.php line 402](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Supplier.php#402)


#### Arguments
* $id_supplier **integer**
* $id_product **integer**
* $id_product_attribute **integer**


