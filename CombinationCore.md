CombinationCore
===============






* Class name: CombinationCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\Combination.php line 27





Properties
----------


### $id_product

    public mixed $id_product





* Visibility: **public**
* This property is defined in classes\Combination.php line 29


### $reference

    public mixed $reference





* Visibility: **public**
* This property is defined in classes\Combination.php line 31


### $supplier_reference

    public mixed $supplier_reference





* Visibility: **public**
* This property is defined in classes\Combination.php line 33


### $location

    public mixed $location





* Visibility: **public**
* This property is defined in classes\Combination.php line 35


### $ean13

    public mixed $ean13





* Visibility: **public**
* This property is defined in classes\Combination.php line 37


### $upc

    public mixed $upc





* Visibility: **public**
* This property is defined in classes\Combination.php line 39


### $wholesale_price

    public mixed $wholesale_price





* Visibility: **public**
* This property is defined in classes\Combination.php line 41


### $price

    public mixed $price





* Visibility: **public**
* This property is defined in classes\Combination.php line 43


### $unit_price_impact

    public mixed $unit_price_impact





* Visibility: **public**
* This property is defined in classes\Combination.php line 45


### $ecotax

    public mixed $ecotax





* Visibility: **public**
* This property is defined in classes\Combination.php line 47


### $minimal_quantity

    public mixed $minimal_quantity = 1





* Visibility: **public**
* This property is defined in classes\Combination.php line 49


### $quantity

    public mixed $quantity





* Visibility: **public**
* This property is defined in classes\Combination.php line 51


### $weight

    public mixed $weight





* Visibility: **public**
* This property is defined in classes\Combination.php line 53


### $default_on

    public mixed $default_on





* Visibility: **public**
* This property is defined in classes\Combination.php line 55


### $available_date

    public mixed $available_date = '0000-00-00'





* Visibility: **public**
* This property is defined in classes\Combination.php line 57


### $definition

    public mixed $definition = array('table' => 'product_attribute', 'primary' => 'id_product_attribute', 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'shop' => 'both', 'validate' => 'isUnsignedId', 'required' => true), 'location' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 64), 'ean13' => array('type' => self::TYPE_STRING, 'validate' => 'isEan13', 'size' => 13), 'upc' => array('type' => self::TYPE_STRING, 'validate' => 'isUpc', 'size' => 12), 'quantity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'size' => 10), 'reference' => array('type' => self::TYPE_STRING, 'size' => 32), 'supplier_reference' => array('type' => self::TYPE_STRING, 'size' => 32), 'wholesale_price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice', 'size' => 27), 'price' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isNegativePrice', 'size' => 20), 'ecotax' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isPrice', 'size' => 20), 'weight' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isFloat'), 'unit_price_impact' => array('type' => self::TYPE_FLOAT, 'shop' => true, 'validate' => 'isNegativePrice', 'size' => 20), 'minimal_quantity' => array('type' => self::TYPE_INT, 'shop' => true, 'validate' => 'isUnsignedId', 'required' => true), 'default_on' => array('type' => self::TYPE_BOOL, 'allow_null' => true, 'shop' => true, 'validate' => 'isBool'), 'available_date' => array('type' => self::TYPE_DATE, 'shop' => true, 'validate' => 'isDateFormat')))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Combination.php line 62


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectNodeName' => 'combination', 'objectsNodeName' => 'combinations', 'fields' => array('id_product' => array('required' => true, 'xlink_resource' => 'products')), 'associations' => array('product_option_values' => array('resource' => 'product_option_value'), 'images' => array('resource' => 'image', 'api' => 'images/products')))





* Visibility: **protected**
* This property is defined in classes\Combination.php line 86


Methods
-------


### delete

    mixed CombinationCore::delete()





* Visibility: **public**
* This method is defined in classes\Combination.php line 98




### deleteFromSupplier

    mixed CombinationCore::deleteFromSupplier($id_product)





* Visibility: **public**
* This method is defined in classes\Combination.php line 124


#### Arguments
* $id_product **mixed**



### add

    mixed CombinationCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in classes\Combination.php line 130


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed CombinationCore::update($null_values)





* Visibility: **public**
* This method is defined in classes\Combination.php line 156


#### Arguments
* $null_values **mixed**



### deleteAssociations

    mixed CombinationCore::deleteAssociations()





* Visibility: **public**
* This method is defined in classes\Combination.php line 170




### setAttributes

    mixed CombinationCore::setAttributes($ids_attribute)





* Visibility: **public**
* This method is defined in classes\Combination.php line 179


#### Arguments
* $ids_attribute **mixed**



### setWsProductOptionValues

    mixed CombinationCore::setWsProductOptionValues($values)





* Visibility: **public**
* This method is defined in classes\Combination.php line 196


#### Arguments
* $values **mixed**



### getWsProductOptionValues

    mixed CombinationCore::getWsProductOptionValues()





* Visibility: **public**
* This method is defined in classes\Combination.php line 205




### getWsImages

    mixed CombinationCore::getWsImages()





* Visibility: **public**
* This method is defined in classes\Combination.php line 216




### setImages

    mixed CombinationCore::setImages($ids_image)





* Visibility: **public**
* This method is defined in classes\Combination.php line 226


#### Arguments
* $ids_image **mixed**



### setWsImages

    mixed CombinationCore::setWsImages($values)





* Visibility: **public**
* This method is defined in classes\Combination.php line 251


#### Arguments
* $values **mixed**



### getAttributesName

    mixed CombinationCore::getAttributesName($id_lang)





* Visibility: **public**
* This method is defined in classes\Combination.php line 260


#### Arguments
* $id_lang **mixed**



### isFeatureActive

    boolean CombinationCore::isFeatureActive()

This method is allow to know if a feature is active



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Combination.php line 274




### isCurrentlyUsed

    boolean CombinationCore::isCurrentlyUsed($table, $has_active_column)

This method is allow to know if a Combination entity is currently used



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Combination.php line 291


#### Arguments
* $table **mixed**
* $has_active_column **mixed**



### getIdByReference

    integer CombinationCore::getIdByReference(integer $id_product, string $reference)

For a given product_attribute reference, returns the corresponding id



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Combination.php line 303


#### Arguments
* $id_product **integer**
* $reference **string**



### getColorsAttributes

    mixed CombinationCore::getColorsAttributes()





* Visibility: **public**
* This method is defined in classes\Combination.php line 318




### getPrice

    float CombinationCore::getPrice(integer $id_product_attribute)

Retrive the price of combination



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Combination.php line 336


#### Arguments
* $id_product_attribute **integer**


