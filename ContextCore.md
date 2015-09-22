ContextCore
===============

Class ContextCore




* Class name: ContextCore
* Namespace: 
* This class is defined in classes\Context.php line 32



Constants
----------


### DEVICE_COMPUTER

    const DEVICE_COMPUTER = 1



* This constant is defined in classes\Context.php line 99


### DEVICE_TABLET

    const DEVICE_TABLET = 2



* This constant is defined in classes\Context.php line 102


### DEVICE_MOBILE

    const DEVICE_MOBILE = 4



* This constant is defined in classes\Context.php line 105


### MODE_STD

    const MODE_STD = 1



* This constant is defined in classes\Context.php line 108


### MODE_STD_CONTRIB

    const MODE_STD_CONTRIB = 2



* This constant is defined in classes\Context.php line 111


### MODE_HOST_CONTRIB

    const MODE_HOST_CONTRIB = 4



* This constant is defined in classes\Context.php line 114


### MODE_HOST

    const MODE_HOST = 8



* This constant is defined in classes\Context.php line 117


Properties
----------


### $instance

    protected mixed $instance





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\Context.php line 35


### $cart

    public \Cart $cart





* Visibility: **public**
* This property is defined in classes\Context.php line 38


### $customer

    public \Customer $customer





* Visibility: **public**
* This property is defined in classes\Context.php line 41


### $cookie

    public \Cookie $cookie





* Visibility: **public**
* This property is defined in classes\Context.php line 44


### $link

    public \Link $link





* Visibility: **public**
* This property is defined in classes\Context.php line 47


### $country

    public \Country $country





* Visibility: **public**
* This property is defined in classes\Context.php line 50


### $employee

    public \Employee $employee





* Visibility: **public**
* This property is defined in classes\Context.php line 53


### $controller

    public \AdminController $controller





* Visibility: **public**
* This property is defined in classes\Context.php line 56


### $override_controller_name_for_translations

    public string $override_controller_name_for_translations





* Visibility: **public**
* This property is defined in classes\Context.php line 59


### $language

    public \Language $language





* Visibility: **public**
* This property is defined in classes\Context.php line 62


### $currency

    public \Currency $currency





* Visibility: **public**
* This property is defined in classes\Context.php line 65


### $tab

    public \AdminTab $tab





* Visibility: **public**
* This property is defined in classes\Context.php line 68


### $shop

    public \Shop $shop





* Visibility: **public**
* This property is defined in classes\Context.php line 71


### $theme

    public \Theme $theme





* Visibility: **public**
* This property is defined in classes\Context.php line 74


### $smarty

    public \Smarty $smarty





* Visibility: **public**
* This property is defined in classes\Context.php line 77


### $mobile_detect

    public \Mobile_Detect $mobile_detect





* Visibility: **public**
* This property is defined in classes\Context.php line 80


### $mode

    public integer $mode





* Visibility: **public**
* This property is defined in classes\Context.php line 83


### $mobile_device

    protected boolean $mobile_device = null

Mobile device of the customer



* Visibility: **protected**
* This property is defined in classes\Context.php line 90


### $is_mobile

    protected boolean $is_mobile = null





* Visibility: **protected**
* This property is defined in classes\Context.php line 93


### $is_tablet

    protected boolean $is_tablet = null





* Visibility: **protected**
* This property is defined in classes\Context.php line 96


Methods
-------


### getMobileDetect

    \Mobile_Detect ContextCore::getMobileDetect()

Sets Mobile_Detect tool object



* Visibility: **public**
* This method is defined in classes\Context.php line 124




### isMobile

    boolean ContextCore::isMobile()

Checks if visitor's device is a mobile device



* Visibility: **public**
* This method is defined in classes\Context.php line 138




### isTablet

    boolean ContextCore::isTablet()

Checks if visitor's device is a tablet device



* Visibility: **public**
* This method is defined in classes\Context.php line 152




### getMobileDevice

    boolean ContextCore::getMobileDevice()

Sets mobile_device context variable



* Visibility: **public**
* This method is defined in classes\Context.php line 166




### getDevice

    integer ContextCore::getDevice()

Returns mobile device type



* Visibility: **public**
* This method is defined in classes\Context.php line 202




### checkMobileContext

    boolean ContextCore::checkMobileContext()

Checks if mobile context is possible



* Visibility: **protected**
* This method is defined in classes\Context.php line 225




### getContext

    \Context ContextCore::getContext()

Get a singleton instance of Context object



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Context.php line 256




### setInstanceForTesting

    mixed ContextCore::setInstanceForTesting($test_instance)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Context.php line 269


#### Arguments
* $test_instance **mixed** - &lt;p&gt;Context
Unit testing purpose only&lt;/p&gt;



### deleteTestingInstance

    mixed ContextCore::deleteTestingInstance()

Unit testing purpose only



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Context.php line 277




### cloneContext

    \Context ContextCore::cloneContext()

Clone current context object



* Visibility: **public**
* This method is defined in classes\Context.php line 287



