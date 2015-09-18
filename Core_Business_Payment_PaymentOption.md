Core_Business_Payment_PaymentOption
===============

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
* Namespace: 





Properties
----------


### $callToActionText

    private mixed $callToActionText





* Visibility: **private**


### $logo

    private mixed $logo





* Visibility: **private**


### $action

    private mixed $action





* Visibility: **private**


### $method

    private mixed $method





* Visibility: **private**


### $inputs

    private mixed $inputs





* Visibility: **private**


### $form

    private mixed $form





* Visibility: **private**


### $moduleName

    private mixed $moduleName





* Visibility: **private**


Methods
-------


### getCallToActionText

    string Core_Business_Payment_PaymentOption::getCallToActionText()

Return Call to Action Text



* Visibility: **public**




### setCallToActionText

    \Core_Business_Payment_PaymentOption Core_Business_Payment_PaymentOption::setCallToActionText($callToActionText)

Set Call To Action Text



* Visibility: **public**


#### Arguments
* $callToActionText **mixed**



### getLogo

    string Core_Business_Payment_PaymentOption::getLogo()

Return logo path



* Visibility: **public**




### setLogo

    \Core_Business_Payment_PaymentOption Core_Business_Payment_PaymentOption::setLogo($logo)

Set logo path



* Visibility: **public**


#### Arguments
* $logo **mixed**



### getAction

    string Core_Business_Payment_PaymentOption::getAction()

Return action to perform (POST/GET)



* Visibility: **public**




### setAction

    \Core_Business_Payment_PaymentOption Core_Business_Payment_PaymentOption::setAction($action)

Set action to be performed by this option



* Visibility: **public**


#### Arguments
* $action **mixed**



### getMethod

    mixed Core_Business_Payment_PaymentOption::getMethod()





* Visibility: **public**




### setMethod

    mixed Core_Business_Payment_PaymentOption::setMethod($method)





* Visibility: **public**


#### Arguments
* $method **mixed**



### getInputs

    mixed Core_Business_Payment_PaymentOption::getInputs()

Return inputs contained in this payment option



* Visibility: **public**




### setInputs

    \Core_Business_Payment_PaymentOption Core_Business_Payment_PaymentOption::setInputs($inputs)

Set inputs for this payment option



* Visibility: **public**


#### Arguments
* $inputs **mixed**



### getForm

    mixed Core_Business_Payment_PaymentOption::getForm()

Get payment option form



* Visibility: **public**




### setForm

    \Core_Business_Payment_PaymentOption Core_Business_Payment_PaymentOption::setForm($form)

Set payment option form



* Visibility: **public**


#### Arguments
* $form **mixed**



### getModuleName

    string Core_Business_Payment_PaymentOption::getModuleName()

Get related module name to this payment option



* Visibility: **public**




### setModuleName

    \Core_Business_Payment_PaymentOption Core_Business_Payment_PaymentOption::setModuleName($moduleName)

Set related module name to this payment option



* Visibility: **public**


#### Arguments
* $moduleName **mixed**



### convertLegacyOption

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


#### Arguments
* $legacyOption **array**


