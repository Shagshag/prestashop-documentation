CustomerMessageCore
===============






* Class name: CustomerMessageCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $id_customer_thread

    public mixed $id_customer_thread





* Visibility: **public**


### $id_employee

    public mixed $id_employee





* Visibility: **public**


### $message

    public mixed $message





* Visibility: **public**


### $file_name

    public mixed $file_name





* Visibility: **public**


### $ip_address

    public mixed $ip_address





* Visibility: **public**


### $user_agent

    public mixed $user_agent





* Visibility: **public**


### $private

    public mixed $private





* Visibility: **public**


### $date_add

    public mixed $date_add





* Visibility: **public**


### $date_upd

    public mixed $date_upd





* Visibility: **public**


### $read

    public mixed $read





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'customer_message', 'primary' => 'id_customer_message', 'fields' => array('id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer_thread' => array('type' => self::TYPE_INT), 'ip_address' => array('type' => self::TYPE_STRING, 'validate' => 'isIp2Long', 'size' => 15), 'message' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 16777216), 'file_name' => array('type' => self::TYPE_STRING), 'user_agent' => array('type' => self::TYPE_STRING), 'private' => array('type' => self::TYPE_INT), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'read' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_employee' => array('xlink_resource' => 'employees'), 'id_customer_thread' => array('xlink_resource' => 'customer_threads')))





* Visibility: **protected**


Methods
-------


### getMessagesByOrderId

    mixed CustomerMessageCore::getMessagesByOrderId($id_order, $private)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_order **mixed**
* $private **mixed**



### getTotalCustomerMessages

    mixed CustomerMessageCore::getTotalCustomerMessages($where)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $where **mixed**



### delete

    mixed CustomerMessageCore::delete()





* Visibility: **public**



