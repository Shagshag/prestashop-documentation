OrderCarrierCore
===============






* Class name: OrderCarrierCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_order_carrier

    public integer $id_order_carrier





* Visibility: **public**


### $id_order

    public integer $id_order





* Visibility: **public**


### $id_carrier

    public integer $id_carrier





* Visibility: **public**


### $id_order_invoice

    public integer $id_order_invoice





* Visibility: **public**


### $weight

    public float $weight





* Visibility: **public**


### $shipping_cost_tax_excl

    public float $shipping_cost_tax_excl





* Visibility: **public**


### $shipping_cost_tax_incl

    public float $shipping_cost_tax_incl





* Visibility: **public**


### $tracking_number

    public integer $tracking_number





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'order_carrier', 'primary' => 'id_order_carrier', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'shipping_cost_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'shipping_cost_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'tracking_number' => array('type' => self::TYPE_STRING, 'validate' => 'isTrackingNumber'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_order' => array('xlink_resource' => 'orders'), 'id_carrier' => array('xlink_resource' => 'carriers')))





* Visibility: **protected**



