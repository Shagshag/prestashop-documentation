PrestaShopLoggerCore
===============






* Class name: PrestaShopLoggerCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/PrestaShopLogger.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#L27)





Properties
----------


### $id_log

    public integer $id_log





* Visibility: **public**
* This property is defined in [classes/PrestaShopLogger.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#30)


### $severity

    public integer $severity





* Visibility: **public**
* This property is defined in [classes/PrestaShopLogger.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#33)


### $error_code

    public integer $error_code





* Visibility: **public**
* This property is defined in [classes/PrestaShopLogger.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#36)


### $message

    public string $message





* Visibility: **public**
* This property is defined in [classes/PrestaShopLogger.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#39)


### $object_type

    public string $object_type





* Visibility: **public**
* This property is defined in [classes/PrestaShopLogger.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#42)


### $object_id

    public integer $object_id





* Visibility: **public**
* This property is defined in [classes/PrestaShopLogger.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#45)


### $id_employee

    public integer $id_employee





* Visibility: **public**
* This property is defined in [classes/PrestaShopLogger.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#48)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/PrestaShopLogger.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#51)


### $date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/PrestaShopLogger.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#54)


### $definition

    public mixed $definition = array('table' => 'log', 'primary' => 'id_log', 'fields' => array('severity' => array('type' => self::TYPE_INT, 'validate' => 'isInt', 'required' => true), 'error_code' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'message' => array('type' => self::TYPE_STRING, 'validate' => 'isString', 'required' => true), 'object_id' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'object_type' => array('type' => self::TYPE_STRING, 'validate' => 'isName'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/PrestaShopLogger.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#59)


### $is_present

    protected mixed $is_present = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/PrestaShopLogger.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#74)


Methods
-------


### sendByMail

    mixed PrestaShopLoggerCore::sendByMail(\PrestaShopLogger $log)

Send e-mail to the shop owner only if the minimal severity level has been reached



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/PrestaShopLogger.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#82)


#### Arguments
* $log **[PrestaShopLogger](PrestaShopLoggerCore)**



### addLog

    boolean PrestaShopLoggerCore::addLog(string $message, integer $severity, integer $error_code, string $object_type, integer $object_id, boolean $allow_duplicate, $id_employee)

add a log item to the database and send a mail if configured for this $severity



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/PrestaShopLogger.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#106)


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
* This method is defined in [classes/PrestaShopLogger.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#147)




### eraseAllLogs

    mixed PrestaShopLoggerCore::eraseAllLogs()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/PrestaShopLogger.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#156)




### _isPresent

    true PrestaShopLoggerCore::_isPresent()

check if this log message already exists in database.



* Visibility: **protected**
* This method is defined in [classes/PrestaShopLogger.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/PrestaShopLogger.php#166)



