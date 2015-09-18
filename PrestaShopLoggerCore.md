PrestaShopLoggerCore
===============






* Class name: PrestaShopLoggerCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_log

    public integer $id_log





* Visibility: **public**


### $severity

    public integer $severity





* Visibility: **public**


### $error_code

    public integer $error_code





* Visibility: **public**


### $message

    public string $message





* Visibility: **public**


### $object_type

    public string $object_type





* Visibility: **public**


### $object_id

    public integer $object_id





* Visibility: **public**


### $id_employee

    public integer $id_employee





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'log', 'primary' => 'id_log', 'fields' => array('severity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'error_code' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'message' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true), 'object_id' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'object_type' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


### $is_present

    protected mixed $is_present = array()





* Visibility: **protected**
* This property is **static**.


Methods
-------


### sendByMail

    mixed PrestaShopLoggerCore::sendByMail(\PrestaShopLogger $log)

Send e-mail to the shop owner only if the minimal severity level has been reached



* Visibility: **public**
* This method is **static**.


#### Arguments
* $log **PrestaShopLogger**



### addLog

    boolean PrestaShopLoggerCore::addLog(string $message, integer $severity, integer $error_code, string $object_type, integer $object_id, boolean $allow_duplicate, $id_employee)

add a log item to the database and send a mail if configured for this $severity



* Visibility: **public**
* This method is **static**.


#### Arguments
* $message **string** - &lt;p&gt;the log message&lt;/p&gt;
* $severity **integer**
* $error_code **integer**
* $object_type **string**
* $object_id **integer**
* $allow_duplicate **boolean** - &lt;p&gt;if set to true, can log several time the same information (not recommended)&lt;/p&gt;
* $id_employee **mixed**



### getHash

    string PrestaShopLoggerCore::getHash()

this function md5($this->message.$this->severity.$this->error_code.$this->object_type.$this->object_id)



* Visibility: **public**




### eraseAllLogs

    mixed PrestaShopLoggerCore::eraseAllLogs()





* Visibility: **public**
* This method is **static**.




### _isPresent

    true PrestaShopLoggerCore::_isPresent()

check if this log message already exists in database.



* Visibility: **protected**



