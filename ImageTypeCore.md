ImageTypeCore
===============






* Class name: ImageTypeCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $width

    public integer $width





* Visibility: **public**


### $height

    public integer $height





* Visibility: **public**


### $products

    public boolean $products





* Visibility: **public**


### $categories

    public integer $categories





* Visibility: **public**


### $manufacturers

    public integer $manufacturers





* Visibility: **public**


### $suppliers

    public integer $suppliers





* Visibility: **public**


### $scenes

    public integer $scenes





* Visibility: **public**


### $stores

    public integer $stores





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'image_type', 'primary' => 'id_image_type', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isImageTypeName', 'required' => true, 'size' => 64), 'width' => array('type' => self::TYPE_INT, 'validate' => 'isImageSize', 'required' => true), 'height' => array('type' => self::TYPE_INT, 'validate' => 'isImageSize', 'required' => true), 'categories' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'products' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'manufacturers' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'suppliers' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'scenes' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'stores' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.


### $images_types_cache

    protected array $images_types_cache = array()





* Visibility: **protected**
* This property is **static**.


### $images_types_name_cache

    protected mixed $images_types_name_cache = array()





* Visibility: **protected**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array()





* Visibility: **protected**


Methods
-------


### getImagesTypes

    array ImageTypeCore::getImagesTypes($type, boolean $order_by_size)

Returns image type definitions



* Visibility: **public**
* This method is **static**.


#### Arguments
* $type **mixed**
* $order_by_size **boolean**



### typeAlreadyExists

    integer ImageTypeCore::typeAlreadyExists($type_name)

Check if type already is already registered in database



* Visibility: **public**
* This method is **static**.


#### Arguments
* $type_name **mixed**



### getByNameNType

    mixed ImageTypeCore::getByNameNType(string $name, string $type, $order)

Finds image type definition by name and type



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string**
* $type **string**
* $order **mixed**



### getFormatedName

    mixed ImageTypeCore::getFormatedName($name)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **mixed**


