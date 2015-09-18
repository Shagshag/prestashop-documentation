ManufacturerCore
===============






* Class name: ManufacturerCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $id_manufacturer

    public integer $id_manufacturer





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $description

    public string $description





* Visibility: **public**


### $short_description

    public string $short_description





* Visibility: **public**


### $id_address

    public integer $id_address





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

    public mixed $definition = array('table' => 'manufacturer', 'primary' => 'id_manufacturer', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isCatalogName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL), 'date_add' => array('type' => self::TYPE_DATE), 'date_upd' => array('type' => self::TYPE_DATE), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'short_description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('active' => array(), 'link_rewrite' => array('getter' => 'getLink', 'setter' => false)), 'associations' => array('addresses' => array('resource' => 'address', 'setter' => false, 'fields' => array('id' => array('xlink_resource' => 'addresses')))))





* Visibility: **protected**


### $cacheName

    protected mixed $cacheName = array()

Return name from id



* Visibility: **protected**
* This property is **static**.


Methods
-------


### __construct

    mixed ManufacturerCore::__construct($id, $id_lang)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### delete

    mixed ManufacturerCore::delete()





* Visibility: **public**




### deleteSelection

    mixed ManufacturerCore::deleteSelection($selection)

Delete several objects from database

return boolean Deletion result

* Visibility: **public**


#### Arguments
* $selection **mixed**



### getManufacturerAddress

    mixed ManufacturerCore::getManufacturerAddress()





* Visibility: **protected**




### getManufacturers

    array ManufacturerCore::getManufacturers(boolean $get_nb_products, integer $id_lang, boolean $active, integer $p, integer $n, boolean $all_group, $group_by)

Return manufacturers



* Visibility: **public**
* This method is **static**.


#### Arguments
* $get_nb_products **boolean** - &lt;p&gt;[optional] return products numbers for each&lt;/p&gt;
* $id_lang **integer**
* $active **boolean**
* $p **integer**
* $n **integer**
* $all_group **boolean**
* $group_by **mixed**



### getNameById

    mixed ManufacturerCore::getNameById($id_manufacturer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_manufacturer **mixed**



### getIdByName

    mixed ManufacturerCore::getIdByName($name)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **mixed**



### getLink

    mixed ManufacturerCore::getLink()





* Visibility: **public**




### getProducts

    mixed ManufacturerCore::getProducts($id_manufacturer, $id_lang, $p, $n, $order_by, $order_way, $get_total, $active, $active_category, \Context $context)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_manufacturer **mixed**
* $id_lang **mixed**
* $p **mixed**
* $n **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $get_total **mixed**
* $active **mixed**
* $active_category **mixed**
* $context **Context**



### getProductsLite

    mixed ManufacturerCore::getProductsLite($id_lang)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**



### manufacturerExists

    mixed ManufacturerCore::manufacturerExists($id_manufacturer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_manufacturer **mixed**



### getAddresses

    mixed ManufacturerCore::getAddresses($id_lang)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**



### getWsAddresses

    mixed ManufacturerCore::getWsAddresses()





* Visibility: **public**




### setWsAddresses

    mixed ManufacturerCore::setWsAddresses($id_addresses)





* Visibility: **public**


#### Arguments
* $id_addresses **mixed**


