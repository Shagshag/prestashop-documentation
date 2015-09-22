ImageTypeCore
===============






* Class name: ImageTypeCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/ImageType.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#27)





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/ImageType.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#29)


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/ImageType.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#32)


### $width

    public integer $width





* Visibility: **public**
* This property is defined in [classes/ImageType.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#35)


### $height

    public integer $height





* Visibility: **public**
* This property is defined in [classes/ImageType.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#38)


### $products

    public boolean $products





* Visibility: **public**
* This property is defined in [classes/ImageType.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#41)


### $categories

    public integer $categories





* Visibility: **public**
* This property is defined in [classes/ImageType.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#44)


### $manufacturers

    public integer $manufacturers





* Visibility: **public**
* This property is defined in [classes/ImageType.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#47)


### $suppliers

    public integer $suppliers





* Visibility: **public**
* This property is defined in [classes/ImageType.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#50)


### $scenes

    public integer $scenes





* Visibility: **public**
* This property is defined in [classes/ImageType.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#53)


### $stores

    public integer $stores





* Visibility: **public**
* This property is defined in [classes/ImageType.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#56)


### $definition

    public mixed $definition = array('table' => 'image_type', 'primary' => 'id_image_type', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isImageTypeName', 'required' => true, 'size' => 64), 'width' => array('type' => self::TYPE_INT, 'validate' => 'isImageSize', 'required' => true), 'height' => array('type' => self::TYPE_INT, 'validate' => 'isImageSize', 'required' => true), 'categories' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'products' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'manufacturers' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'suppliers' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'scenes' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'stores' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/ImageType.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#61)


### $images_types_cache

    protected array $images_types_cache = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/ImageType.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#80)


### $images_types_name_cache

    protected mixed $images_types_name_cache = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/ImageType.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#82)


### $webserviceParameters

    protected mixed $webserviceParameters = array()





* Visibility: **protected**
* This property is defined in [classes/ImageType.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#84)


Methods
-------


### getImagesTypes

    array ImageTypeCore::getImagesTypes($type, boolean $order_by_size)

Returns image type definitions



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageType.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#94)


#### Arguments
* $type **mixed**
* $order_by_size **boolean**



### typeAlreadyExists

    integer ImageTypeCore::typeAlreadyExists($type_name)

Check if type already is already registered in database



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageType.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#119)


#### Arguments
* $type_name **mixed**



### getByNameNType

    mixed ImageTypeCore::getByNameNType(string $name, string $type, $order)

Finds image type definition by name and type



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageType.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#138)


#### Arguments
* $name **string**
* $type **string**
* $order **mixed**



### getFormatedName

    mixed ImageTypeCore::getFormatedName($name)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/ImageType.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#166)


#### Arguments
* $name **mixed**


