GuestCore
===============






* Class name: GuestCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/Guest.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#27)





Properties
----------


### $id_operating_system

    public mixed $id_operating_system





* Visibility: **public**
* This property is defined in [classes/Guest.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#29)


### $id_web_browser

    public mixed $id_web_browser





* Visibility: **public**
* This property is defined in [classes/Guest.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#30)


### $id_customer

    public mixed $id_customer





* Visibility: **public**
* This property is defined in [classes/Guest.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#31)


### $javascript

    public mixed $javascript





* Visibility: **public**
* This property is defined in [classes/Guest.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#32)


### $screen_resolution_x

    public mixed $screen_resolution_x





* Visibility: **public**
* This property is defined in [classes/Guest.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#33)


### $screen_resolution_y

    public mixed $screen_resolution_y





* Visibility: **public**
* This property is defined in [classes/Guest.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#34)


### $screen_color

    public mixed $screen_color





* Visibility: **public**
* This property is defined in [classes/Guest.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#35)


### $sun_java

    public mixed $sun_java





* Visibility: **public**
* This property is defined in [classes/Guest.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#36)


### $adobe_flash

    public mixed $adobe_flash





* Visibility: **public**
* This property is defined in [classes/Guest.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#37)


### $adobe_director

    public mixed $adobe_director





* Visibility: **public**
* This property is defined in [classes/Guest.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#38)


### $apple_quicktime

    public mixed $apple_quicktime





* Visibility: **public**
* This property is defined in [classes/Guest.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#39)


### $real_player

    public mixed $real_player





* Visibility: **public**
* This property is defined in [classes/Guest.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#40)


### $windows_media

    public mixed $windows_media





* Visibility: **public**
* This property is defined in [classes/Guest.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#41)


### $accept_language

    public mixed $accept_language





* Visibility: **public**
* This property is defined in [classes/Guest.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#42)


### $mobile_theme

    public mixed $mobile_theme





* Visibility: **public**
* This property is defined in [classes/Guest.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#43)


### $definition

    public mixed $definition = array('table' => 'guest', 'primary' => 'id_guest', 'fields' => array('id_operating_system' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_web_browser' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'javascript' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'screen_resolution_x' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'screen_resolution_y' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'screen_color' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'sun_java' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'adobe_flash' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'adobe_director' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'apple_quicktime' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'real_player' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'windows_media' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'accept_language' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 8), 'mobile_theme' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Guest.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#48)


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_customer' => array('xlink_resource' => 'customers')))





* Visibility: **protected**
* This property is defined in [classes/Guest.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#70)


Methods
-------


### userAgent

    mixed GuestCore::userAgent()





* Visibility: **public**
* This method is defined in [classes/Guest.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#76)




### getLanguage

    mixed GuestCore::getLanguage($acceptLanguage)





* Visibility: **protected**
* This method is defined in [classes/Guest.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#86)


#### Arguments
* $acceptLanguage **mixed**



### getBrowser

    mixed GuestCore::getBrowser($userAgent)





* Visibility: **protected**
* This method is defined in [classes/Guest.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#105)


#### Arguments
* $userAgent **mixed**



### getOs

    mixed GuestCore::getOs($userAgent)





* Visibility: **protected**
* This method is defined in [classes/Guest.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#133)


#### Arguments
* $userAgent **mixed**



### getFromCustomer

    mixed GuestCore::getFromCustomer($id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Guest.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#158)


#### Arguments
* $id_customer **mixed**



### mergeWithCustomer

    mixed GuestCore::mergeWithCustomer($id_guest, $id_customer)





* Visibility: **public**
* This method is defined in [classes/Guest.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#170)


#### Arguments
* $id_guest **mixed**
* $id_customer **mixed**



### setNewGuest

    mixed GuestCore::setNewGuest($cookie)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Guest.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#189)


#### Arguments
* $cookie **mixed**


