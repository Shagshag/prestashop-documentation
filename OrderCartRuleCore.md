OrderCartRuleCore
===============






* Class name: OrderCartRuleCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/order/OrderCartRule.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#L27)





Properties
----------


### $id_order_cart_rule

    public integer $id_order_cart_rule





* Visibility: **public**
* This property is defined in [classes/order/OrderCartRule.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#30)


### $id_order

    public integer $id_order





* Visibility: **public**
* This property is defined in [classes/order/OrderCartRule.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#33)


### $id_cart_rule

    public integer $id_cart_rule





* Visibility: **public**
* This property is defined in [classes/order/OrderCartRule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#36)


### $id_order_invoice

    public integer $id_order_invoice





* Visibility: **public**
* This property is defined in [classes/order/OrderCartRule.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#39)


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/order/OrderCartRule.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#42)


### $value

    public float $value





* Visibility: **public**
* This property is defined in [classes/order/OrderCartRule.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#45)


### $value_tax_excl

    public float $value_tax_excl





* Visibility: **public**
* This property is defined in [classes/order/OrderCartRule.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#48)


### $free_shipping

    public boolean $free_shipping





* Visibility: **public**
* This property is defined in [classes/order/OrderCartRule.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#51)


### $definition

    public mixed $definition = array('table' => 'order_cart_rule', 'primary' => 'id_order_cart_rule', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_cart_rule' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'required' => true), 'value' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'value_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'free_shipping' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/order/OrderCartRule.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#56)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_order' => array('xlink_resource' => 'orders')))





* Visibility: **protected**
* This property is defined in [classes/order/OrderCartRule.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#70)



