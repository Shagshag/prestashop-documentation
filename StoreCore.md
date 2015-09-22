StoreCore
===============






* Class name: StoreCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Store.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#L27)





Properties
----------


### $id_country

    public integer $id_country





* Visibility: **public**
* This property is defined in [classes/Store.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#30)


### $id_state

    public integer $id_state





* Visibility: **public**
* This property is defined in [classes/Store.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#33)


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Store.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#36)


### $address1

    public string $address1





* Visibility: **public**
* This property is defined in [classes/Store.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#39)


### $address2

    public string $address2





* Visibility: **public**
* This property is defined in [classes/Store.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#42)


### $postcode

    public string $postcode





* Visibility: **public**
* This property is defined in [classes/Store.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#45)


### $city

    public string $city





* Visibility: **public**
* This property is defined in [classes/Store.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#48)


### $latitude

    public float $latitude





* Visibility: **public**
* This property is defined in [classes/Store.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#51)


### $longitude

    public float $longitude





* Visibility: **public**
* This property is defined in [classes/Store.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#54)


### $hours

    public string $hours





* Visibility: **public**
* This property is defined in [classes/Store.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#57)


### $phone

    public string $phone





* Visibility: **public**
* This property is defined in [classes/Store.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#60)


### $fax

    public string $fax





* Visibility: **public**
* This property is defined in [classes/Store.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#63)


### $note

    public string $note





* Visibility: **public**
* This property is defined in [classes/Store.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#66)


### $email

    public string $email





* Visibility: **public**
* This property is defined in [classes/Store.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#69)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/Store.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#72)


### $date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/Store.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#75)


### $active

    public boolean $active = true





* Visibility: **public**
* This property is defined in [classes/Store.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#78)


### $definition

    public mixed $definition = array('table' => 'store', 'primary' => 'id_store', 'fields' => array('id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId'), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 128), 'address1' => array('type' => self::TYPE_STRING, 'validate' => 'isAddress', 'required' => true, 'size' => 128), 'address2' => array('type' => self::TYPE_STRING, 'validate' => 'isAddress', 'size' => 128), 'postcode' => array('type' => self::TYPE_STRING, 'size' => 12), 'city' => array('type' => self::TYPE_STRING, 'validate' => 'isCityName', 'required' => true, 'size' => 64), 'latitude' => array('type' => self::TYPE_FLOAT, 'validate' => 'isCoordinate', 'size' => 13), 'longitude' => array('type' => self::TYPE_FLOAT, 'validate' => 'isCoordinate', 'size' => 13), 'hours' => array('type' => self::TYPE_STRING, 'validate' => 'isSerializedArray', 'size' => 65000), 'phone' => array('type' => self::TYPE_STRING, 'validate' => 'isPhoneNumber', 'size' => 16), 'fax' => array('type' => self::TYPE_STRING, 'validate' => 'isPhoneNumber', 'size' => 16), 'note' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 65000), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'size' => 128), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Store.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#83)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_country' => array('xlink_resource' => 'countries'), 'id_state' => array('xlink_resource' => 'states'), 'hours' => array('getter' => 'getWsHours', 'setter' => 'setWsHours')))





* Visibility: **protected**
* This property is defined in [classes/Store.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#107)


Methods
-------


### __construct

    mixed StoreCore::__construct($id_store, $id_lang)





* Visibility: **public**
* This method is defined in [classes/Store.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#115)


#### Arguments
* $id_store **mixed**
* $id_lang **mixed**



### getWsHours

    mixed StoreCore::getWsHours()





* Visibility: **public**
* This method is defined in [classes/Store.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#122)




### setWsHours

    mixed StoreCore::setWsHours($hours)





* Visibility: **public**
* This method is defined in [classes/Store.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Store.php#127)


#### Arguments
* $hours **mixed**


