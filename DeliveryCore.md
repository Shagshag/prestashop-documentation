DeliveryCore
===============






* Class name: DeliveryCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_delivery

    public integer $id_delivery





* Visibility: **public**


### $id_shop

    public integer $id_shop





* Visibility: **public**


### $id_shop_group

    public integer $id_shop_group





* Visibility: **public**


### $id_carrier

    public integer $id_carrier





* Visibility: **public**


### $id_range_price

    public integer $id_range_price





* Visibility: **public**


### $id_range_weight

    public integer $id_range_weight





* Visibility: **public**


### $id_zone

    public integer $id_zone





* Visibility: **public**


### $price

    public float $price





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'delivery', 'primary' => 'id_delivery', 'fields' => array('id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_range_price' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_range_weight' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_zone' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT), 'id_shop_group' => array('type' => self::TYPE_INT), 'price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'deliveries', 'fields' => array('id_carrier' => array('xlink_resource' => 'carriers'), 'id_range_price' => array('xlink_resource' => 'price_ranges'), 'id_range_weight' => array('xlink_resource' => 'weight_ranges'), 'id_zone' => array('xlink_resource' => 'zones')))





* Visibility: **protected**


Methods
-------


### getFields

    mixed DeliveryCore::getFields()





* Visibility: **public**



