CustomizationFieldCore
===============






* Class name: CustomizationFieldCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_product

    public integer $id_product





* Visibility: **public**


### $type

    public integer $type





* Visibility: **public**


### $required

    public boolean $required





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'customization_field', 'primary' => 'id_customization_field', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'type' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'required' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'required' => true, 'size' => 255)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_product' => array('xlink_resource' => array('resourceName' => 'products'))))





* Visibility: **protected**



