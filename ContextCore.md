ContextCore
===============

Class ContextCore




* Class name: ContextCore
* This class is defined in [classes/Context.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L32)



Constants
----------

* [DEVICE_COMPUTER](#constant-DEVICE_COMPUTER)
* [DEVICE_TABLET](#constant-DEVICE_TABLET)
* [DEVICE_MOBILE](#constant-DEVICE_MOBILE)
* [MODE_STD](#constant-MODE_STD)
* [MODE_STD_CONTRIB](#constant-MODE_STD_CONTRIB)
* [MODE_HOST_CONTRIB](#constant-MODE_HOST_CONTRIB)
* [MODE_HOST](#constant-MODE_HOST)

Properties
----------

* [$instance](#property-$instance)
* [$cart](#property-$cart)
* [$customer](#property-$customer)
* [$cookie](#property-$cookie)
* [$link](#property-$link)
* [$country](#property-$country)
* [$employee](#property-$employee)
* [$controller](#property-$controller)
* [$override_controller_name_for_translations](#property-$override_controller_name_for_translations)
* [$language](#property-$language)
* [$currency](#property-$currency)
* [$tab](#property-$tab)
* [$shop](#property-$shop)
* [$theme](#property-$theme)
* [$smarty](#property-$smarty)
* [$mobile_detect](#property-$mobile_detect)
* [$mode](#property-$mode)
* [$mobile_device](#property-$mobile_device)
* [$is_mobile](#property-$is_mobile)
* [$is_tablet](#property-$is_tablet)

Methods
-------
* [getMobileDetect](#method-getMobileDetect)
* [isMobile](#method-isMobile)
* [isTablet](#method-isTablet)
* [getMobileDevice](#method-getMobileDevice)
* [getDevice](#method-getDevice)
* [checkMobileContext](#method-checkMobileContext)
* [getContext](#method-getContext)
* [setInstanceForTesting](#method-setInstanceForTesting)
* [deleteTestingInstance](#method-deleteTestingInstance)
* [cloneContext](#method-cloneContext)


Constants
----------


### <a name="constant-DEVICE_COMPUTER"></a>DEVICE_COMPUTER

    const DEVICE_COMPUTER = 1



* This constant is defined in [classes/Context.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L99)


### <a name="constant-DEVICE_TABLET"></a>DEVICE_TABLET

    const DEVICE_TABLET = 2



* This constant is defined in [classes/Context.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L102)


### <a name="constant-DEVICE_MOBILE"></a>DEVICE_MOBILE

    const DEVICE_MOBILE = 4



* This constant is defined in [classes/Context.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L105)


### <a name="constant-MODE_STD"></a>MODE_STD

    const MODE_STD = 1



* This constant is defined in [classes/Context.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L108)


### <a name="constant-MODE_STD_CONTRIB"></a>MODE_STD_CONTRIB

    const MODE_STD_CONTRIB = 2



* This constant is defined in [classes/Context.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L111)


### <a name="constant-MODE_HOST_CONTRIB"></a>MODE_HOST_CONTRIB

    const MODE_HOST_CONTRIB = 4



* This constant is defined in [classes/Context.php line 114](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L114)


### <a name="constant-MODE_HOST"></a>MODE_HOST

    const MODE_HOST = 8



* This constant is defined in [classes/Context.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L117)


Properties
----------


### <a name="property-$instance"></a>$instance

    protected mixed $instance





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Context.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L35)


### <a name="property-$cart"></a>$cart

    public \Cart $cart





* Visibility: **public**
* This property is defined in [classes/Context.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L38)


### <a name="property-$customer"></a>$customer

    public \Customer $customer





* Visibility: **public**
* This property is defined in [classes/Context.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L41)


### <a name="property-$cookie"></a>$cookie

    public \Cookie $cookie





* Visibility: **public**
* This property is defined in [classes/Context.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L44)


### <a name="property-$link"></a>$link

    public \Link $link





* Visibility: **public**
* This property is defined in [classes/Context.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L47)


### <a name="property-$country"></a>$country

    public \Country $country





* Visibility: **public**
* This property is defined in [classes/Context.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L50)


### <a name="property-$employee"></a>$employee

    public \Employee $employee





* Visibility: **public**
* This property is defined in [classes/Context.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L53)


### <a name="property-$controller"></a>$controller

    public \AdminController $controller





* Visibility: **public**
* This property is defined in [classes/Context.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L56)


### <a name="property-$override_controller_name_for_translations"></a>$override_controller_name_for_translations

    public string $override_controller_name_for_translations





* Visibility: **public**
* This property is defined in [classes/Context.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L59)


### <a name="property-$language"></a>$language

    public \Language $language





* Visibility: **public**
* This property is defined in [classes/Context.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L62)


### <a name="property-$currency"></a>$currency

    public \Currency $currency





* Visibility: **public**
* This property is defined in [classes/Context.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L65)


### <a name="property-$tab"></a>$tab

    public \AdminTab $tab





* Visibility: **public**
* This property is defined in [classes/Context.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L68)


### <a name="property-$shop"></a>$shop

    public \Shop $shop





* Visibility: **public**
* This property is defined in [classes/Context.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L71)


### <a name="property-$theme"></a>$theme

    public \Theme $theme





* Visibility: **public**
* This property is defined in [classes/Context.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L74)


### <a name="property-$smarty"></a>$smarty

    public \Smarty $smarty





* Visibility: **public**
* This property is defined in [classes/Context.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L77)


### <a name="property-$mobile_detect"></a>$mobile_detect

    public \Mobile_Detect $mobile_detect





* Visibility: **public**
* This property is defined in [classes/Context.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L80)


### <a name="property-$mode"></a>$mode

    public integer $mode





* Visibility: **public**
* This property is defined in [classes/Context.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L83)


### <a name="property-$mobile_device"></a>$mobile_device

    protected boolean $mobile_device = null

Mobile device of the customer



* Visibility: **protected**
* This property is defined in [classes/Context.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L90)


### <a name="property-$is_mobile"></a>$is_mobile

    protected boolean $is_mobile = null





* Visibility: **protected**
* This property is defined in [classes/Context.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L93)


### <a name="property-$is_tablet"></a>$is_tablet

    protected boolean $is_tablet = null





* Visibility: **protected**
* This property is defined in [classes/Context.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L96)


Methods
-------


### <a name="method-getMobileDetect"></a>getMobileDetect

    \Mobile_Detect ContextCore::getMobileDetect()

Sets Mobile_Detect tool object



* Visibility: **public**
* This method is defined in [classes/Context.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L124)




### <a name="method-isMobile"></a>isMobile

    boolean ContextCore::isMobile()

Checks if visitor's device is a mobile device



* Visibility: **public**
* This method is defined in [classes/Context.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L138)




### <a name="method-isTablet"></a>isTablet

    boolean ContextCore::isTablet()

Checks if visitor's device is a tablet device



* Visibility: **public**
* This method is defined in [classes/Context.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L152)




### <a name="method-getMobileDevice"></a>getMobileDevice

    boolean ContextCore::getMobileDevice()

Sets mobile_device context variable



* Visibility: **public**
* This method is defined in [classes/Context.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L166)




### <a name="method-getDevice"></a>getDevice

    integer ContextCore::getDevice()

Returns mobile device type



* Visibility: **public**
* This method is defined in [classes/Context.php line 202](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L202)




### <a name="method-checkMobileContext"></a>checkMobileContext

    boolean ContextCore::checkMobileContext()

Checks if mobile context is possible



* Visibility: **protected**
* This method is defined in [classes/Context.php line 225](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L225)




### <a name="method-getContext"></a>getContext

    \Context ContextCore::getContext()

Get a singleton instance of Context object



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Context.php line 256](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L256)




### <a name="method-setInstanceForTesting"></a>setInstanceForTesting

    mixed ContextCore::setInstanceForTesting($test_instance)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Context.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L269)


#### Arguments
* $test_instance **mixed** - &lt;p&gt;Context
Unit testing purpose only&lt;/p&gt;



### <a name="method-deleteTestingInstance"></a>deleteTestingInstance

    mixed ContextCore::deleteTestingInstance()

Unit testing purpose only



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Context.php line 277](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L277)




### <a name="method-cloneContext"></a>cloneContext

    \Context ContextCore::cloneContext()

Clone current context object



* Visibility: **public**
* This method is defined in [classes/Context.php line 287](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Context.php#L287)



