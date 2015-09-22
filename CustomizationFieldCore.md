CustomizationFieldCore
===============






* Class name: CustomizationFieldCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/CustomizationField.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#27)





Properties
----------


### $id_product

    public integer $id_product





* Visibility: **public**
* This property is defined in [classes/CustomizationField.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#30)


### $type

    public integer $type





* Visibility: **public**
* This property is defined in [classes/CustomizationField.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#32)


### $required

    public boolean $required





* Visibility: **public**
* This property is defined in [classes/CustomizationField.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#34)


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/CustomizationField.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#36)


### $definition

    public mixed $definition = array('table' => 'customization_field', 'primary' => 'id_customization_field', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'type' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'required' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'required' => true, 'size' => 255)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/CustomizationField.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#41)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_product' => array('xlink_resource' => array('resourceName' => 'products'))))





* Visibility: **protected**
* This property is defined in [classes/CustomizationField.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CustomizationField.php#56)



