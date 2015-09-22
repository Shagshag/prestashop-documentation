Class OrderCartRuleCore
=====================





* Class name: OrderCartRuleCore
* Parent class: [ObjectModel](class.ObjectModelCore)
* Source: [classes/order/OrderCartRule.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#L27)



Properties
----------

* [$definition](#property-$definition)
* [$free_shipping](#property-$free_shipping)
* [$id_cart_rule](#property-$id_cart_rule)
* [$id_order](#property-$id_order)
* [$id_order_cart_rule](#property-$id_order_cart_rule)
* [$id_order_invoice](#property-$id_order_invoice)
* [$name](#property-$name)
* [$value](#property-$value)
* [$value_tax_excl](#property-$value_tax_excl)
* [$webserviceParameters](#property-$webserviceParameters)





Properties
----------


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'order_cart_rule', 'primary' => 'id_order_cart_rule', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_cart_rule' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'required' => true), 'value' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'value_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'free_shipping' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* Source: [classes/order/OrderCartRule.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#L56)


### <a name="property-$free_shipping"></a>$free_shipping

    public boolean $free_shipping





* Visibility: **public**
* Source: [classes/order/OrderCartRule.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#L51)


### <a name="property-$id_cart_rule"></a>$id_cart_rule

    public integer $id_cart_rule





* Visibility: **public**
* Source: [classes/order/OrderCartRule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#L36)


### <a name="property-$id_order"></a>$id_order

    public integer $id_order





* Visibility: **public**
* Source: [classes/order/OrderCartRule.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#L33)


### <a name="property-$id_order_cart_rule"></a>$id_order_cart_rule

    public integer $id_order_cart_rule





* Visibility: **public**
* Source: [classes/order/OrderCartRule.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#L30)


### <a name="property-$id_order_invoice"></a>$id_order_invoice

    public integer $id_order_invoice





* Visibility: **public**
* Source: [classes/order/OrderCartRule.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#L39)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* Source: [classes/order/OrderCartRule.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#L42)


### <a name="property-$value"></a>$value

    public float $value





* Visibility: **public**
* Source: [classes/order/OrderCartRule.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#L45)


### <a name="property-$value_tax_excl"></a>$value_tax_excl

    public float $value_tax_excl





* Visibility: **public**
* Source: [classes/order/OrderCartRule.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#L48)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_order' => array('xlink_resource' => 'orders')))





* Visibility: **protected**
* Source: [classes/order/OrderCartRule.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCartRule.php#L70)



