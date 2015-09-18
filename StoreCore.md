StoreCore
===============






* Class name: StoreCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_country

    public integer $id_country





* Visibility: **public**


### $id_state

    public integer $id_state





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $address1

    public string $address1





* Visibility: **public**


### $address2

    public string $address2





* Visibility: **public**


### $postcode

    public string $postcode





* Visibility: **public**


### $city

    public string $city





* Visibility: **public**


### $latitude

    public float $latitude





* Visibility: **public**


### $longitude

    public float $longitude





* Visibility: **public**


### $hours

    public string $hours





* Visibility: **public**


### $phone

    public string $phone





* Visibility: **public**


### $fax

    public string $fax





* Visibility: **public**


### $note

    public string $note





* Visibility: **public**


### $email

    public string $email





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $active

    public boolean $active = true





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'store', 'primary' => 'id_store', 'fields' => array('id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isNullOrUnsignedId'), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 128), 'address1' => array('type' => self::TYPE_STRING, 'validate' => 'isAddress', 'required' => true, 'size' => 128), 'address2' => array('type' => self::TYPE_STRING, 'validate' => 'isAddress', 'size' => 128), 'postcode' => array('type' => self::TYPE_STRING, 'size' => 12), 'city' => array('type' => self::TYPE_STRING, 'validate' => 'isCityName', 'required' => true, 'size' => 64), 'latitude' => array('type' => self::TYPE_FLOAT, 'validate' => 'isCoordinate', 'size' => 13), 'longitude' => array('type' => self::TYPE_FLOAT, 'validate' => 'isCoordinate', 'size' => 13), 'hours' => array('type' => self::TYPE_STRING, 'validate' => 'isSerializedArray', 'size' => 65000), 'phone' => array('type' => self::TYPE_STRING, 'validate' => 'isPhoneNumber', 'size' => 16), 'fax' => array('type' => self::TYPE_STRING, 'validate' => 'isPhoneNumber', 'size' => 16), 'note' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'size' => 65000), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'size' => 128), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_country' => array('xlink_resource' => 'countries'), 'id_state' => array('xlink_resource' => 'states'), 'hours' => array('getter' => 'getWsHours', 'setter' => 'setWsHours')))





* Visibility: **protected**


Methods
-------


### __construct

    mixed StoreCore::__construct($id_store, $id_lang)





* Visibility: **public**


#### Arguments
* $id_store **mixed**
* $id_lang **mixed**



### getWsHours

    mixed StoreCore::getWsHours()





* Visibility: **public**




### setWsHours

    mixed StoreCore::setWsHours($hours)





* Visibility: **public**


#### Arguments
* $hours **mixed**


