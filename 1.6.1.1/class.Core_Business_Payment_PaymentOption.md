Class Core_Business_Payment_PaymentOption
=====================

2007-2015 PrestaShop

NOTICE OF LICENSE

This source file is subject to the Open Software License (OSL 3.0)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
http://opensource.org/licenses/osl-3.0.php
If you did not receive a copy of the license and are unable to
obtain it through the world-wide-web, please send an email
to license@prestashop.com so we can send you a copy immediately.

DISCLAIMER

Do not edit or add to this file if you wish to upgrade PrestaShop to newer
versions in the future. If you wish to customize PrestaShop for your
needs please refer to http://www.prestashop.com for more information.

* Class name: Core_Business_Payment_PaymentOption
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L27)



Properties
----------

* [$action](#property-$action)
* [$callToActionText](#property-$callToActionText)
* [$form](#property-$form)
* [$inputs](#property-$inputs)
* [$logo](#property-$logo)
* [$method](#property-$method)
* [$moduleName](#property-$moduleName)

Methods
-------
* [convertLegacyOption](#method-convertLegacyOption)
* [getAction](#method-getAction)
* [getCallToActionText](#method-getCallToActionText)
* [getForm](#method-getForm)
* [getInputs](#method-getInputs)
* [getLogo](#method-getLogo)
* [getMethod](#method-getMethod)
* [getModuleName](#method-getModuleName)
* [setAction](#method-setAction)
* [setCallToActionText](#method-setCallToActionText)
* [setForm](#method-setForm)
* [setInputs](#method-setInputs)
* [setLogo](#method-setLogo)
* [setMethod](#method-setMethod)
* [setModuleName](#method-setModuleName)




Properties
----------


### <a name="property-$action"></a>$action

    private mixed $action





* Visibility: **private**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L31).


### <a name="property-$callToActionText"></a>$callToActionText

    private mixed $callToActionText





* Visibility: **private**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L29).


### <a name="property-$form"></a>$form

    private mixed $form





* Visibility: **private**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L34).


### <a name="property-$inputs"></a>$inputs

    private mixed $inputs





* Visibility: **private**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L33).


### <a name="property-$logo"></a>$logo

    private mixed $logo





* Visibility: **private**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L30).


### <a name="property-$method"></a>$method

    private mixed $method





* Visibility: **private**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L32).


### <a name="property-$moduleName"></a>$moduleName

    private mixed $moduleName





* Visibility: **private**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L35).


Methods
-------


### <a name="method-convertLegacyOption"></a>convertLegacyOption

    mixed Core_Business_Payment_PaymentOption::convertLegacyOption(array $legacyOption)

Legacy options were specified this way:
- either an array with a top level property 'cta_text'
	and then the other properties
- or a numerically indexed array or arrays as described above
Since this was a mess, this method is provided to convert them.

It takes as input a legacy option (in either form) and always
returns an array of instances of Core_Business_Payment_PaymentOption

* Visibility: **public**
* This method is **static**.
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L178)


#### Arguments
* $legacyOption **array**



### <a name="method-getAction"></a>getAction

    string Core_Business_Payment_PaymentOption::getAction()

Return action to perform (POST/GET)



* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L81)




### <a name="method-getCallToActionText"></a>getCallToActionText

    string Core_Business_Payment_PaymentOption::getCallToActionText()

Return Call to Action Text



* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L41)




### <a name="method-getForm"></a>getForm

    mixed Core_Business_Payment_PaymentOption::getForm()

Get payment option form



* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L133)




### <a name="method-getInputs"></a>getInputs

    mixed Core_Business_Payment_PaymentOption::getInputs()

Return inputs contained in this payment option



* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L113)




### <a name="method-getLogo"></a>getLogo

    string Core_Business_Payment_PaymentOption::getLogo()

Return logo path



* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L61)




### <a name="method-getMethod"></a>getMethod

    mixed Core_Business_Payment_PaymentOption::getMethod()





* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L98)




### <a name="method-getModuleName"></a>getModuleName

    string Core_Business_Payment_PaymentOption::getModuleName()

Get related module name to this payment option



* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L153)




### <a name="method-setAction"></a>setAction

    \Core_Business_Payment_PaymentOption Core_Business_Payment_PaymentOption::setAction($action)

Set action to be performed by this option



* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L92)


#### Arguments
* $action **mixed**



### <a name="method-setCallToActionText"></a>setCallToActionText

    \Core_Business_Payment_PaymentOption Core_Business_Payment_PaymentOption::setCallToActionText($callToActionText)

Set Call To Action Text



* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L51)


#### Arguments
* $callToActionText **mixed**



### <a name="method-setForm"></a>setForm

    \Core_Business_Payment_PaymentOption Core_Business_Payment_PaymentOption::setForm($form)

Set payment option form



* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L143)


#### Arguments
* $form **mixed**



### <a name="method-setInputs"></a>setInputs

    \Core_Business_Payment_PaymentOption Core_Business_Payment_PaymentOption::setInputs($inputs)

Set inputs for this payment option



* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L123)


#### Arguments
* $inputs **mixed**



### <a name="method-setLogo"></a>setLogo

    \Core_Business_Payment_PaymentOption Core_Business_Payment_PaymentOption::setLogo($logo)

Set logo path



* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L71)


#### Arguments
* $logo **mixed**



### <a name="method-setMethod"></a>setMethod

    mixed Core_Business_Payment_PaymentOption::setMethod($method)





* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L103)


#### Arguments
* $method **mixed**



### <a name="method-setModuleName"></a>setModuleName

    \Core_Business_Payment_PaymentOption Core_Business_Payment_PaymentOption::setModuleName($moduleName)

Set related module name to this payment option



* Visibility: **public**
* Source: [Core/Business/Payment/Core_Business_Payment_PaymentOption.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Business/Payment/Core_Business_Payment_PaymentOption.php#L163)


#### Arguments
* $moduleName **mixed**


