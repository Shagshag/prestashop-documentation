GuestCore
===============






* Class name: GuestCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Guest.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L27)





Properties
----------

* [$id_operating_system](#property-$id_operating_system)
* [$id_web_browser](#property-$id_web_browser)
* [$id_customer](#property-$id_customer)
* [$javascript](#property-$javascript)
* [$screen_resolution_x](#property-$screen_resolution_x)
* [$screen_resolution_y](#property-$screen_resolution_y)
* [$screen_color](#property-$screen_color)
* [$sun_java](#property-$sun_java)
* [$adobe_flash](#property-$adobe_flash)
* [$adobe_director](#property-$adobe_director)
* [$apple_quicktime](#property-$apple_quicktime)
* [$real_player](#property-$real_player)
* [$windows_media](#property-$windows_media)
* [$accept_language](#property-$accept_language)
* [$mobile_theme](#property-$mobile_theme)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [userAgent](#method-userAgent)
* [getLanguage](#method-getLanguage)
* [getBrowser](#method-getBrowser)
* [getOs](#method-getOs)
* [getFromCustomer](#method-getFromCustomer)
* [mergeWithCustomer](#method-mergeWithCustomer)
* [setNewGuest](#method-setNewGuest)




Properties
----------


### <a name="property-$id_operating_system"></a>$id_operating_system

    public mixed $id_operating_system





* Visibility: **public**
* This property is defined in [classes/Guest.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L29)


### <a name="property-$id_web_browser"></a>$id_web_browser

    public mixed $id_web_browser





* Visibility: **public**
* This property is defined in [classes/Guest.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L30)


### <a name="property-$id_customer"></a>$id_customer

    public mixed $id_customer





* Visibility: **public**
* This property is defined in [classes/Guest.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L31)


### <a name="property-$javascript"></a>$javascript

    public mixed $javascript





* Visibility: **public**
* This property is defined in [classes/Guest.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L32)


### <a name="property-$screen_resolution_x"></a>$screen_resolution_x

    public mixed $screen_resolution_x





* Visibility: **public**
* This property is defined in [classes/Guest.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L33)


### <a name="property-$screen_resolution_y"></a>$screen_resolution_y

    public mixed $screen_resolution_y





* Visibility: **public**
* This property is defined in [classes/Guest.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L34)


### <a name="property-$screen_color"></a>$screen_color

    public mixed $screen_color





* Visibility: **public**
* This property is defined in [classes/Guest.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L35)


### <a name="property-$sun_java"></a>$sun_java

    public mixed $sun_java





* Visibility: **public**
* This property is defined in [classes/Guest.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L36)


### <a name="property-$adobe_flash"></a>$adobe_flash

    public mixed $adobe_flash





* Visibility: **public**
* This property is defined in [classes/Guest.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L37)


### <a name="property-$adobe_director"></a>$adobe_director

    public mixed $adobe_director





* Visibility: **public**
* This property is defined in [classes/Guest.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L38)


### <a name="property-$apple_quicktime"></a>$apple_quicktime

    public mixed $apple_quicktime





* Visibility: **public**
* This property is defined in [classes/Guest.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L39)


### <a name="property-$real_player"></a>$real_player

    public mixed $real_player





* Visibility: **public**
* This property is defined in [classes/Guest.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L40)


### <a name="property-$windows_media"></a>$windows_media

    public mixed $windows_media





* Visibility: **public**
* This property is defined in [classes/Guest.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L41)


### <a name="property-$accept_language"></a>$accept_language

    public mixed $accept_language





* Visibility: **public**
* This property is defined in [classes/Guest.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L42)


### <a name="property-$mobile_theme"></a>$mobile_theme

    public mixed $mobile_theme





* Visibility: **public**
* This property is defined in [classes/Guest.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L43)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'guest', 'primary' => 'id_guest', 'fields' => array('id_operating_system' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_web_browser' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'javascript' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'screen_resolution_x' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'screen_resolution_y' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'screen_color' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'sun_java' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'adobe_flash' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'adobe_director' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'apple_quicktime' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'real_player' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'windows_media' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'accept_language' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 8), 'mobile_theme' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Guest.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L48)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_customer' => array('xlink_resource' => 'customers')))





* Visibility: **protected**
* This property is defined in [classes/Guest.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L70)


Methods
-------


### <a name="method-userAgent"></a>userAgent

    mixed GuestCore::userAgent()





* Visibility: **public**
* This method is defined in [classes/Guest.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L76)




### <a name="method-getLanguage"></a>getLanguage

    mixed GuestCore::getLanguage($acceptLanguage)





* Visibility: **protected**
* This method is defined in [classes/Guest.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L86)


#### Arguments
* $acceptLanguage **mixed**



### <a name="method-getBrowser"></a>getBrowser

    mixed GuestCore::getBrowser($userAgent)





* Visibility: **protected**
* This method is defined in [classes/Guest.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L105)


#### Arguments
* $userAgent **mixed**



### <a name="method-getOs"></a>getOs

    mixed GuestCore::getOs($userAgent)





* Visibility: **protected**
* This method is defined in [classes/Guest.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L133)


#### Arguments
* $userAgent **mixed**



### <a name="method-getFromCustomer"></a>getFromCustomer

    mixed GuestCore::getFromCustomer($id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Guest.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L158)


#### Arguments
* $id_customer **mixed**



### <a name="method-mergeWithCustomer"></a>mergeWithCustomer

    mixed GuestCore::mergeWithCustomer($id_guest, $id_customer)





* Visibility: **public**
* This method is defined in [classes/Guest.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L170)


#### Arguments
* $id_guest **mixed**
* $id_customer **mixed**



### <a name="method-setNewGuest"></a>setNewGuest

    mixed GuestCore::setNewGuest($cookie)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Guest.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Guest.php#L189)


#### Arguments
* $cookie **mixed**


