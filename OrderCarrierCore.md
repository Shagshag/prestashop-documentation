OrderCarrierCore
===============






* Class name: OrderCarrierCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/order/OrderCarrier.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCarrier.php#L27)





Properties
----------

* [$id_order_carrier](#property-$id_order_carrier)
* [$id_order](#property-$id_order)
* [$id_carrier](#property-$id_carrier)
* [$id_order_invoice](#property-$id_order_invoice)
* [$weight](#property-$weight)
* [$shipping_cost_tax_excl](#property-$shipping_cost_tax_excl)
* [$shipping_cost_tax_incl](#property-$shipping_cost_tax_incl)
* [$tracking_number](#property-$tracking_number)
* [$date_add](#property-$date_add)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)





Properties
----------


### <a name="property-$id_order_carrier"></a>$id_order_carrier

    public integer $id_order_carrier





* Visibility: **public**
* This property is defined in [classes/order/OrderCarrier.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCarrier.php#L30)


### <a name="property-$id_order"></a>$id_order

    public integer $id_order





* Visibility: **public**
* This property is defined in [classes/order/OrderCarrier.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCarrier.php#L33)


### <a name="property-$id_carrier"></a>$id_carrier

    public integer $id_carrier





* Visibility: **public**
* This property is defined in [classes/order/OrderCarrier.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCarrier.php#L36)


### <a name="property-$id_order_invoice"></a>$id_order_invoice

    public integer $id_order_invoice





* Visibility: **public**
* This property is defined in [classes/order/OrderCarrier.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCarrier.php#L39)


### <a name="property-$weight"></a>$weight

    public float $weight





* Visibility: **public**
* This property is defined in [classes/order/OrderCarrier.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCarrier.php#L42)


### <a name="property-$shipping_cost_tax_excl"></a>$shipping_cost_tax_excl

    public float $shipping_cost_tax_excl





* Visibility: **public**
* This property is defined in [classes/order/OrderCarrier.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCarrier.php#L45)


### <a name="property-$shipping_cost_tax_incl"></a>$shipping_cost_tax_incl

    public float $shipping_cost_tax_incl





* Visibility: **public**
* This property is defined in [classes/order/OrderCarrier.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCarrier.php#L48)


### <a name="property-$tracking_number"></a>$tracking_number

    public integer $tracking_number





* Visibility: **public**
* This property is defined in [classes/order/OrderCarrier.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCarrier.php#L51)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/order/OrderCarrier.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCarrier.php#L54)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'order_carrier', 'primary' => 'id_order_carrier', 'fields' => array('id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_carrier' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_order_invoice' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'weight' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'shipping_cost_tax_excl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'shipping_cost_tax_incl' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'tracking_number' => array('type' => self::TYPE_STRING, 'validate' => 'isTrackingNumber'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/order/OrderCarrier.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCarrier.php#L59)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_order' => array('xlink_resource' => 'orders'), 'id_carrier' => array('xlink_resource' => 'carriers')))





* Visibility: **protected**
* This property is defined in [classes/order/OrderCarrier.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderCarrier.php#L74)



