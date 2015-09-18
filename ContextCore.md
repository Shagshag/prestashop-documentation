ContextCore
===============

Class ContextCore




* Class name: ContextCore
* Namespace: 



Constants
----------


### DEVICE_COMPUTER

    const DEVICE_COMPUTER = 1





### DEVICE_TABLET

    const DEVICE_TABLET = 2





### DEVICE_MOBILE

    const DEVICE_MOBILE = 4





### MODE_STD

    const MODE_STD = 1





### MODE_STD_CONTRIB

    const MODE_STD_CONTRIB = 2





### MODE_HOST_CONTRIB

    const MODE_HOST_CONTRIB = 4





### MODE_HOST

    const MODE_HOST = 8





Properties
----------


### $instance

    protected mixed $instance





* Visibility: **protected**
* This property is **static**.


### $cart

    public \Cart $cart





* Visibility: **public**


### $customer

    public \Customer $customer





* Visibility: **public**


### $cookie

    public \Cookie $cookie





* Visibility: **public**


### $link

    public \Link $link





* Visibility: **public**


### $country

    public \Country $country





* Visibility: **public**


### $employee

    public \Employee $employee





* Visibility: **public**


### $controller

    public \AdminController $controller





* Visibility: **public**


### $override_controller_name_for_translations

    public string $override_controller_name_for_translations





* Visibility: **public**


### $language

    public \Language $language





* Visibility: **public**


### $currency

    public \Currency $currency





* Visibility: **public**


### $tab

    public \AdminTab $tab





* Visibility: **public**


### $shop

    public \Shop $shop





* Visibility: **public**


### $theme

    public \Theme $theme





* Visibility: **public**


### $smarty

    public \Smarty $smarty





* Visibility: **public**


### $mobile_detect

    public \Mobile_Detect $mobile_detect





* Visibility: **public**


### $mode

    public integer $mode





* Visibility: **public**


### $mobile_device

    protected boolean $mobile_device = null

Mobile device of the customer



* Visibility: **protected**


### $is_mobile

    protected boolean $is_mobile = null





* Visibility: **protected**


### $is_tablet

    protected boolean $is_tablet = null





* Visibility: **protected**


Methods
-------


### getMobileDetect

    \Mobile_Detect ContextCore::getMobileDetect()

Sets Mobile_Detect tool object



* Visibility: **public**




### isMobile

    boolean ContextCore::isMobile()

Checks if visitor's device is a mobile device



* Visibility: **public**




### isTablet

    boolean ContextCore::isTablet()

Checks if visitor's device is a tablet device



* Visibility: **public**




### getMobileDevice

    boolean ContextCore::getMobileDevice()

Sets mobile_device context variable



* Visibility: **public**




### getDevice

    integer ContextCore::getDevice()

Returns mobile device type



* Visibility: **public**




### checkMobileContext

    boolean ContextCore::checkMobileContext()

Checks if mobile context is possible



* Visibility: **protected**




### getContext

    \Context ContextCore::getContext()

Get a singleton instance of Context object



* Visibility: **public**
* This method is **static**.




### setInstanceForTesting

    mixed ContextCore::setInstanceForTesting($test_instance)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $test_instance **mixed** - &lt;p&gt;Context
Unit testing purpose only&lt;/p&gt;



### deleteTestingInstance

    mixed ContextCore::deleteTestingInstance()

Unit testing purpose only



* Visibility: **public**
* This method is **static**.




### cloneContext

    \Context ContextCore::cloneContext()

Clone current context object



* Visibility: **public**



