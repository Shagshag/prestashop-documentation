PaymentCCCore
===============






* Class name: PaymentCCCore
* Namespace: 
* Parent class: OrderPayment
* **Warning:** this class is **deprecated**. This means that this class will likely be removed in a future version.





Properties
----------


### $id_order

    public mixed $id_order





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $id_currency

    public mixed $id_currency





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $amount

    public mixed $amount





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $transaction_id

    public mixed $transaction_id





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $card_number

    public mixed $card_number





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $card_brand

    public mixed $card_brand





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $card_expiration

    public mixed $card_expiration





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $card_holder

    public mixed $card_holder





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $date_add

    public mixed $date_add





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $fieldsRequired

    protected mixed $fieldsRequired = array('id_currency', 'amount')





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $fieldsSize

    protected mixed $fieldsSize = array('transaction_id' => 254, 'card_number' => 254, 'card_brand' => 254, 'card_expiration' => 254, 'card_holder' => 254)





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $fieldsValidate

    protected mixed $fieldsValidate = array('id_order' => 'isUnsignedId', 'id_currency' => 'isUnsignedId', 'amount' => 'isPrice', 'transaction_id' => 'isAnything', 'card_number' => 'isAnything', 'card_brand' => 'isAnything', 'card_expiration' => 'isAnything', 'card_holder' => 'isAnything')





* Visibility: **protected**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.


### $definition

    public mixed $definition = array('table' => 'payment_cc', 'primary' => 'id_payment_cc')





* Visibility: **public**
* **Warning:** this property is **deprecated**. This means that this property will likely be removed in a future version.
* This property is **static**.


Methods
-------


### add

    mixed PaymentCCCore::add($autodate, $nullValues)





* Visibility: **public**
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### getByOrderId

    array PaymentCCCore::getByOrderId(integer $id_order)

Get the detailed payment of an order



* Visibility: **public**
* This method is **static**.
* **Warning:** this method is **deprecated**. This means that this method will likely be removed in a future version.


#### Arguments
* $id_order **integer**


