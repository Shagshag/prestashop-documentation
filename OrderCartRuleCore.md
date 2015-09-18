OrderCartRuleCore
===============






* Class name: OrderCartRuleCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_order_cart_rule

    public integer $id_order_cart_rule





* Visibility: **public**


### $id_order

    public integer $id_order





* Visibility: **public**


### $id_cart_rule

    public integer $id_cart_rule





* Visibility: **public**


### $id_order_invoice

    public integer $id_order_invoice





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $value

    public float $value





* Visibility: **public**


### $value_tax_excl

    public float $value_tax_excl





* Visibility: **public**


### $free_shipping

    public boolean $free_shipping





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'order_cart_rule', 'primary' => 'id_order_cart_rule', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_cart_rule' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'required' => true), 'value' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'value_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'free_shipping' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_order' => array('xlink_resource' => 'orders')))





* Visibility: **protected**



