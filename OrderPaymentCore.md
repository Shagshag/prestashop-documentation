OrderPaymentCore
===============






* Class name: OrderPaymentCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $order_reference

    public mixed $order_reference





* Visibility: **public**


### $id_currency

    public mixed $id_currency





* Visibility: **public**


### $amount

    public mixed $amount





* Visibility: **public**


### $payment_method

    public mixed $payment_method





* Visibility: **public**


### $conversion_rate

    public mixed $conversion_rate





* Visibility: **public**


### $transaction_id

    public mixed $transaction_id





* Visibility: **public**


### $card_number

    public mixed $card_number





* Visibility: **public**


### $card_brand

    public mixed $card_brand





* Visibility: **public**


### $card_expiration

    public mixed $card_expiration





* Visibility: **public**


### $card_holder

    public mixed $card_holder





* Visibility: **public**


### $date_add

    public mixed $date_add





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'order_payment', 'primary' => 'id_order_payment', 'fields' => array('order_reference' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 9), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'amount' => array('type' => self::TYPE_FLOAT, 'validate' => 'isNegativePrice', 'required' => true), 'payment_method' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName'), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'transaction_id' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'card_number' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'card_brand' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'card_expiration' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'card_holder' => array('type' => self::TYPE_STRING, 'validate' => 'isAnything', 'size' => 254), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


Methods
-------


### add

    mixed OrderPaymentCore::add($autodate, $nullValues)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### getByOrderId

    array OrderPaymentCore::getByOrderId(integer $id_order)

Get the detailed payment of an order



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order **integer**



### getByOrderReference

    array OrderPaymentCore::getByOrderReference(integer $order_reference)

Get the detailed payment of an order



* Visibility: **public**
* This method is **static**.


#### Arguments
* $order_reference **integer**



### getByInvoiceId

    \PrestaShopCollection OrderPaymentCore::getByInvoiceId(integer $id_invoice)

Get Order Payments By Invoice ID



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_invoice **integer** - &lt;p&gt;Invoice ID&lt;/p&gt;



### getOrderInvoice

    mixed OrderPaymentCore::getOrderInvoice(integer $id_order)

Return order invoice object linked to the payment



* Visibility: **public**


#### Arguments
* $id_order **integer** - &lt;p&gt;Order Id&lt;/p&gt;


