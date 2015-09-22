PaymentCCCore
===============






* Class name: PaymentCCCore
* Parent class: [OrderPayment](OrderPaymentCore)
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.
* This class is defined in [classes/PaymentCC.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#L33)





Properties
----------


### $id_order

    public mixed $id_order





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/PaymentCC.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#35)


### $id_currency

    public mixed $id_currency





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/PaymentCC.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#36)


### $amount

    public mixed $amount





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/PaymentCC.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#37)


### $transaction_id

    public mixed $transaction_id





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/PaymentCC.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#38)


### $card_number

    public mixed $card_number





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/PaymentCC.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#39)


### $card_brand

    public mixed $card_brand





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/PaymentCC.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#40)


### $card_expiration

    public mixed $card_expiration





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/PaymentCC.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#41)


### $card_holder

    public mixed $card_holder





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/PaymentCC.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#42)


### $date_add

    public mixed $date_add





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/PaymentCC.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#43)


### $fieldsRequired

    protected mixed $fieldsRequired = array('id_currency', 'amount')





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/PaymentCC.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#45)


### $fieldsSize

    protected mixed $fieldsSize = array('transaction_id' => 254, 'card_number' => 254, 'card_brand' => 254, 'card_expiration' => 254, 'card_holder' => 254)





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/PaymentCC.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#46)


### $fieldsValidate

    protected mixed $fieldsValidate = array('id_order' => 'isUnsignedId', 'id_currency' => 'isUnsignedId', 'amount' => 'isPrice', 'transaction_id' => 'isAnything', 'card_number' => 'isAnything', 'card_brand' => 'isAnything', 'card_expiration' => 'isAnything', 'card_holder' => 'isAnything')





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is defined in [classes/PaymentCC.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#47)


### $definition

    public mixed $definition = array('table' => 'payment_cc', 'primary' => 'id_payment_cc')





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.
* This property is defined in [classes/PaymentCC.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#51)


Methods
-------


### add

    mixed PaymentCCCore::add($autodate, $nullValues)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/PaymentCC.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#61)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### getByOrderId

    array PaymentCCCore::getByOrderId(integer $id_order)

Get the detailed payment of an order



* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.
* This method is defined in [classes/PaymentCC.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PaymentCC.php#74)


#### Arguments
* $id_order **integer**


