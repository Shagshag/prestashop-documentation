OrderMessageCore
===============






* Class name: OrderMessageCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/order/OrderMessage.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderMessage.php#27)





Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/order/OrderMessage.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderMessage.php#30)


### $message

    public string $message





* Visibility: **public**
* This property is defined in [classes/order/OrderMessage.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderMessage.php#33)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/order/OrderMessage.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderMessage.php#36)


### $definition

    public mixed $definition = array('table' => 'order_message', 'primary' => 'id_order_message', 'multilang' => true, 'fields' => array('date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128), 'message' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isMessage', 'required' => true, 'size' => 1200)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/order/OrderMessage.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderMessage.php#41)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id' => array('sqlId' => 'id_discount_type', 'xlink_resource' => 'order_message_lang'), 'date_add' => array('sqlId' => 'date_add')))





* Visibility: **protected**
* This property is defined in [classes/order/OrderMessage.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderMessage.php#54)


Methods
-------


### getOrderMessages

    mixed OrderMessageCore::getOrderMessages($id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/order/OrderMessage.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/order/OrderMessage.php#61)


#### Arguments
* $id_lang **mixed**


