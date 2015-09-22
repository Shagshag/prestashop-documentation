OrderPaymentCore
===============






* Class name: OrderPaymentCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\order\OrderPayment.php line 27





Properties
----------


### $order_reference

    public mixed $order_reference





* Visibility: **public**
* This property is defined in classes\order\OrderPayment.php line 29


### $id_currency

    public mixed $id_currency





* Visibility: **public**
* This property is defined in classes\order\OrderPayment.php line 30


### $amount

    public mixed $amount





* Visibility: **public**
* This property is defined in classes\order\OrderPayment.php line 31


### $payment_method

    public mixed $payment_method





* Visibility: **public**
* This property is defined in classes\order\OrderPayment.php line 32


### $conversion_rate

    public mixed $conversion_rate





* Visibility: **public**
* This property is defined in classes\order\OrderPayment.php line 33


### $transaction_id

    public mixed $transaction_id





* Visibility: **public**
* This property is defined in classes\order\OrderPayment.php line 34


### $card_number

    public mixed $card_number





* Visibility: **public**
* This property is defined in classes\order\OrderPayment.php line 35


### $card_brand

    public mixed $card_brand





* Visibility: **public**
* This property is defined in classes\order\OrderPayment.php line 36


### $card_expiration

    public mixed $card_expiration





* Visibility: **public**
* This property is defined in classes\order\OrderPayment.php line 37


### $card_holder

    public mixed $card_holder





* Visibility: **public**
* This property is defined in classes\order\OrderPayment.php line 38


### $date_add

    public mixed $date_add





* Visibility: **public**
* This property is defined in classes\order\OrderPayment.php line 39


### $definition

    public mixed $definition = array('table' => 'order_payment', 'primary' => 'id_order_payment', 'fields' => array('order_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 9), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isNegativePrice', 'required' => true), 'payment_method' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'transaction_id' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'card_number' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'card_brand' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'card_expiration' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'card_holder' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\order\OrderPayment.php line 44


Methods
-------


### add

    mixed OrderPaymentCore::add($autodate, $nullValues)





* Visibility: **public**
* This method is defined in classes\order\OrderPayment.php line 62


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### getByOrderId

    array OrderPaymentCore::getByOrderId(integer $id_order)

Get the detailed payment of an order



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\order\OrderPayment.php line 78


#### Arguments
* $id_order **integer**



### getByOrderReference

    array OrderPaymentCore::getByOrderReference(integer $order_reference)

Get the detailed payment of an order



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\order\OrderPayment.php line 91


#### Arguments
* $order_reference **integer**



### getByInvoiceId

    \PrestaShopCollection OrderPaymentCore::getByInvoiceId(integer $id_invoice)

Get Order Payments By Invoice ID



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\order\OrderPayment.php line 107


#### Arguments
* $id_invoice **integer** - &lt;p&gt;Invoice ID&lt;/p&gt;



### getOrderInvoice

    mixed OrderPaymentCore::getOrderInvoice(integer $id_order)

Return order invoice object linked to the payment



* Visibility: **public**
* This method is defined in classes\order\OrderPayment.php line 131


#### Arguments
* $id_order **integer** - &lt;p&gt;Order Id&lt;/p&gt;


