CustomizationFieldCore
===============






* Class name: CustomizationFieldCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/CustomizationField.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#L27)





Properties
----------

* [$id_product](#property-$id_product)
* [$type](#property-$type)
* [$required](#property-$required)
* [$name](#property-$name)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)





Properties
----------


### <a name="property-$id_product"></a>$id_product

    public integer $id_product





* Visibility: **public**
* This property is defined in [classes/CustomizationField.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#L30)


### <a name="property-$type"></a>$type

    public integer $type





* Visibility: **public**
* This property is defined in [classes/CustomizationField.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#L32)


### <a name="property-$required"></a>$required

    public boolean $required





* Visibility: **public**
* This property is defined in [classes/CustomizationField.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#L34)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* This property is defined in [classes/CustomizationField.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#L36)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'customization_field', 'primary' => 'id_customization_field', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'type' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'required' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'required' => true, 'size' => 255)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/CustomizationField.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#L41)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_product' => array('xlink_resource' => array('resourceName' => 'products'))))





* Visibility: **protected**
* This property is defined in [classes/CustomizationField.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#L56)



