ManufacturerCore
===============






* Class name: ManufacturerCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Manufacturer.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#L27)





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/Manufacturer.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#29)


### $id_manufacturer

    public integer $id_manufacturer





* Visibility: **public**
* This property is defined in [classes/Manufacturer.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#32)


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Manufacturer.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#35)


### $description

    public string $description





* Visibility: **public**
* This property is defined in [classes/Manufacturer.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#38)


### $short_description

    public string $short_description





* Visibility: **public**
* This property is defined in [classes/Manufacturer.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#41)


### $id_address

    public integer $id_address





* Visibility: **public**
* This property is defined in [classes/Manufacturer.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#44)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/Manufacturer.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#47)


### $date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/Manufacturer.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#50)


### $link_rewrite

    public string $link_rewrite





* Visibility: **public**
* This property is defined in [classes/Manufacturer.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#53)


### $meta_title

    public string $meta_title





* Visibility: **public**
* This property is defined in [classes/Manufacturer.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#56)


### $meta_keywords

    public string $meta_keywords





* Visibility: **public**
* This property is defined in [classes/Manufacturer.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#59)


### $meta_description

    public string $meta_description





* Visibility: **public**
* This property is defined in [classes/Manufacturer.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#62)


### $active

    public boolean $active





* Visibility: **public**
* This property is defined in [classes/Manufacturer.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#65)


### $definition

    public mixed $definition = array('table' => 'manufacturer', 'primary' => 'id_manufacturer', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isCatalogName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL), 'date_add' => array('type' => self::TYPE_DATE), 'date_upd' => array('type' => self::TYPE_DATE), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'short_description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Manufacturer.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#70)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('active' => array(), 'link_rewrite' => array('getter' => 'getLink', 'setter' => false)), 'associations' => array('addresses' => array('resource' => 'address', 'setter' => false, 'fields' => array('id' => array('xlink_resource' => 'addresses')))))





* Visibility: **protected**
* This property is defined in [classes/Manufacturer.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#89)


### $cacheName

    protected mixed $cacheName = array()

Return name from id



* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Manufacturer.php line 239](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#239)


Methods
-------


### __construct

    mixed ManufacturerCore::__construct($id, $id_lang)





* Visibility: **public**
* This method is defined in [classes/Manufacturer.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#101)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### delete

    mixed ManufacturerCore::delete()





* Visibility: **public**
* This method is defined in [classes/Manufacturer.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#109)




### deleteSelection

    mixed ManufacturerCore::deleteSelection($selection)

Delete several objects from database

return boolean Deletion result

* Visibility: **public**
* This method is defined in [classes/Manufacturer.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#128)


#### Arguments
* $selection **mixed**



### getManufacturerAddress

    mixed ManufacturerCore::getManufacturerAddress()





* Visibility: **protected**
* This method is defined in [classes/Manufacturer.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#144)




### getManufacturers

    array ManufacturerCore::getManufacturers(boolean $get_nb_products, integer $id_lang, boolean $active, integer $p, integer $n, boolean $all_group, $group_by)

Return manufacturers



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Manufacturer.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#164)


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
* This method is defined in [classes/Manufacturer.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#240)


#### Arguments
* $id_manufacturer **mixed**



### getIdByName

    mixed ManufacturerCore::getIdByName($name)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Manufacturer.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#254)


#### Arguments
* $name **mixed**



### getLink

    mixed ManufacturerCore::getLink()





* Visibility: **public**
* This method is defined in [classes/Manufacturer.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#269)




### getProducts

    mixed ManufacturerCore::getProducts($id_manufacturer, $id_lang, $p, $n, $order_by, $order_way, $get_total, $active, $active_category, \Context $context)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Manufacturer.php line 274](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#274)


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
* $context **[Context](ContextCore)**



### getProductsLite

    mixed ManufacturerCore::getProductsLite($id_lang)





* Visibility: **public**
* This method is defined in [classes/Manufacturer.php line 399](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#399)


#### Arguments
* $id_lang **mixed**



### manufacturerExists

    mixed ManufacturerCore::manufacturerExists($id_manufacturer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Manufacturer.php line 425](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#425)


#### Arguments
* $id_manufacturer **mixed**



### getAddresses

    mixed ManufacturerCore::getAddresses($id_lang)





* Visibility: **public**
* This method is defined in [classes/Manufacturer.php line 436](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#436)


#### Arguments
* $id_lang **mixed**



### getWsAddresses

    mixed ManufacturerCore::getWsAddresses()





* Visibility: **public**
* This method is defined in [classes/Manufacturer.php line 451](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#451)




### setWsAddresses

    mixed ManufacturerCore::setWsAddresses($id_addresses)





* Visibility: **public**
* This method is defined in [classes/Manufacturer.php line 462](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Manufacturer.php#462)


#### Arguments
* $id_addresses **mixed**


