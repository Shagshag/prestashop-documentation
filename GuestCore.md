GuestCore
===============






* Class name: GuestCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_operating_system

    public mixed $id_operating_system





* Visibility: **public**


### $id_web_browser

    public mixed $id_web_browser





* Visibility: **public**


### $id_customer

    public mixed $id_customer





* Visibility: **public**


### $javascript

    public mixed $javascript





* Visibility: **public**


### $screen_resolution_x

    public mixed $screen_resolution_x





* Visibility: **public**


### $screen_resolution_y

    public mixed $screen_resolution_y





* Visibility: **public**


### $screen_color

    public mixed $screen_color





* Visibility: **public**


### $sun_java

    public mixed $sun_java





* Visibility: **public**


### $adobe_flash

    public mixed $adobe_flash





* Visibility: **public**


### $adobe_director

    public mixed $adobe_director





* Visibility: **public**


### $apple_quicktime

    public mixed $apple_quicktime





* Visibility: **public**


### $real_player

    public mixed $real_player





* Visibility: **public**


### $windows_media

    public mixed $windows_media





* Visibility: **public**


### $accept_language

    public mixed $accept_language





* Visibility: **public**


### $mobile_theme

    public mixed $mobile_theme





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'guest', 'primary' => 'id_guest', 'fields' => array('id_operating_system' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_web_browser' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'javascript' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'screen_resolution_x' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'screen_resolution_y' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'screen_color' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'sun_java' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'adobe_flash' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'adobe_director' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'apple_quicktime' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'real_player' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'windows_media' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'accept_language' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 8), 'mobile_theme' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_customer' => array('xlink_resource' => 'customers')))





* Visibility: **protected**


Methods
-------


### userAgent

    mixed GuestCore::userAgent()





* Visibility: **public**




### getLanguage

    mixed GuestCore::getLanguage($acceptLanguage)





* Visibility: **protected**


#### Arguments
* $acceptLanguage **mixed**



### getBrowser

    mixed GuestCore::getBrowser($userAgent)





* Visibility: **protected**


#### Arguments
* $userAgent **mixed**



### getOs

    mixed GuestCore::getOs($userAgent)





* Visibility: **protected**


#### Arguments
* $userAgent **mixed**



### getFromCustomer

    mixed GuestCore::getFromCustomer($id_customer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**



### mergeWithCustomer

    mixed GuestCore::mergeWithCustomer($id_guest, $id_customer)





* Visibility: **public**


#### Arguments
* $id_guest **mixed**
* $id_customer **mixed**



### setNewGuest

    mixed GuestCore::setNewGuest($cookie)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $cookie **mixed**


