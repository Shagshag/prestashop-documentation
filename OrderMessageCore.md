OrderMessageCore
===============






* Class name: OrderMessageCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $name

    public string $name





* Visibility: **public**


### $message

    public string $message





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'order_message', 'primary' => 'id_order_message', 'multilang' => true, 'fields' => array('date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128), 'message' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isMessage', 'required' => true, 'size' => 1200)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id' => array('sqlId' => 'id_discount_type', 'xlink_resource' => 'order_message_lang'), 'date_add' => array('sqlId' => 'date_add')))





* Visibility: **protected**


Methods
-------


### getOrderMessages

    mixed OrderMessageCore::getOrderMessages($id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**


