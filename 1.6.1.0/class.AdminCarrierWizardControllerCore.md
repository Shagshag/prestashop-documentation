Class AdminCarrierWizardControllerCore
=====================





* Class name: AdminCarrierWizardControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCarrierWizardController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L30)


Contents
--------


### Properties

* [$object](#property-$object)
* [$wizard_access](#property-$wizard_access)

### Methods

* [__construct](#method-__construct)
* [ajaxProcessChangeRanges](#method-ajaxProcessChangeRanges)
* [ajaxProcessFinishStep](#method-ajaxProcessFinishStep)
* [ajaxProcessUploadLogo](#method-ajaxProcessUploadLogo)
* [ajaxProcessValidateStep](#method-ajaxProcessValidateStep)
* [changeGroups](#method-changeGroups)
* [changeZones](#method-changeZones)
* [displayFieldName](#method-displayFieldName)
* [duplicateLogo](#method-duplicateLogo)
* [getActualCurrency](#method-getActualCurrency)
* [getStepFiveFieldsValues](#method-getStepFiveFieldsValues)
* [getStepFourFieldsValues](#method-getStepFourFieldsValues)
* [getStepOneFieldsValues](#method-getStepOneFieldsValues)
* [getStepThreeFieldsValues](#method-getStepThreeFieldsValues)
* [getStepTwoFieldsValues](#method-getStepTwoFieldsValues)
* [getTplRangesVarsAndValues](#method-getTplRangesVarsAndValues)
* [getValidationRules](#method-getValidationRules)
* [initBreadcrumbs](#method-initBreadcrumbs)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initWizard](#method-initWizard)
* [processRanges](#method-processRanges)
* [renderGenericForm](#method-renderGenericForm)
* [renderStepFive](#method-renderStepFive)
* [renderStepFour](#method-renderStepFour)
* [renderStepOne](#method-renderStepOne)
* [renderStepThree](#method-renderStepThree)
* [renderStepTwo](#method-renderStepTwo)
* [renderView](#method-renderView)
* [setMedia](#method-setMedia)
* [validateForm](#method-validateForm)




Properties
----------


### <a name="property-$object"></a>$object

```php
public \Carrier $object
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L30).


### <a name="property-$wizard_access"></a>$wizard_access

```php
protected mixed $wizard_access
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCarrierWizardControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L34)




### <a name="method-ajaxProcessChangeRanges"></a>ajaxProcessChangeRanges

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessChangeRanges()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 599](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L599)




### <a name="method-ajaxProcessFinishStep"></a>ajaxProcessFinishStep

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessFinishStep()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 772](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L772)




### <a name="method-ajaxProcessUploadLogo"></a>ajaxProcessUploadLogo

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessUploadLogo()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 746](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L746)




### <a name="method-ajaxProcessValidateStep"></a>ajaxProcessValidateStep

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessValidateStep()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 662](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L662)




### <a name="method-changeGroups"></a>changeGroups

```php
mixed AdminCarrierWizardControllerCore::changeGroups($id_carrier, $delete)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 892](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L892)


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### <a name="method-changeZones"></a>changeZones

```php
mixed AdminCarrierWizardControllerCore::changeZones($id)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 901](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L901)


#### Arguments
* $id **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed AdminCarrierWizardControllerCore::displayFieldName($field)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminCarrierWizardController.php line 951](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L951)


#### Arguments
* $field **mixed**



### <a name="method-duplicateLogo"></a>duplicateLogo

```php
mixed AdminCarrierWizardControllerCore::duplicateLogo($new_id, $old_id)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 956](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L956)


#### Arguments
* $new_id **mixed**
* $old_id **mixed**



### <a name="method-getActualCurrency"></a>getActualCurrency

```php
mixed AdminCarrierWizardControllerCore::getActualCurrency()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 971](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L971)




### <a name="method-getStepFiveFieldsValues"></a>getStepFiveFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepFiveFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 594](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L594)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepFourFieldsValues"></a>getStepFourFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepFourFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 582](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L582)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepOneFieldsValues"></a>getStepOneFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepOneFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L549)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepThreeFieldsValues"></a>getStepThreeFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepThreeFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 566](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L566)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepTwoFieldsValues"></a>getStepTwoFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepTwoFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 560](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L560)


#### Arguments
* $carrier **mixed**



### <a name="method-getTplRangesVarsAndValues"></a>getTplRangesVarsAndValues

```php
mixed AdminCarrierWizardControllerCore::getTplRangesVarsAndValues(\Carrier $carrier, array $tpl_vars, array $fields_value)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 483](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L483)


#### Arguments
* $carrier **[Carrier](class.CarrierCore.md)**
* $tpl_vars **array**
* $fields_value **array**



### <a name="method-getValidationRules"></a>getValidationRules

```php
mixed AdminCarrierWizardControllerCore::getValidationRules()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 921](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L921)




### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

```php
mixed AdminCarrierWizardControllerCore::initBreadcrumbs($tab_id, $tabs)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L150)


#### Arguments
* $tab_id **mixed**
* $tabs **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCarrierWizardControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L162)




### <a name="method-initWizard"></a>initWizard

```php
mixed AdminCarrierWizardControllerCore::initWizard()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L67)




### <a name="method-processRanges"></a>processRanges

```php
mixed AdminCarrierWizardControllerCore::processRanges($id_carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 667](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L667)


#### Arguments
* $id_carrier **mixed**



### <a name="method-renderGenericForm"></a>renderGenericForm

```php
mixed AdminCarrierWizardControllerCore::renderGenericForm($fields_form, $fields_value, $tpl_vars)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L527)


#### Arguments
* $fields_form **mixed**
* $fields_value **mixed**
* $tpl_vars **mixed**



### <a name="method-renderStepFive"></a>renderStepFive

```php
mixed AdminCarrierWizardControllerCore::renderStepFive($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L437)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepFour"></a>renderStepFour

```php
string AdminCarrierWizardControllerCore::renderStepFour(\Carrier $carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 376](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L376)


#### Arguments
* $carrier **[Carrier](class.CarrierCore.md)**



### <a name="method-renderStepOne"></a>renderStepOne

```php
mixed AdminCarrierWizardControllerCore::renderStepOne($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L172)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepThree"></a>renderStepThree

```php
mixed AdminCarrierWizardControllerCore::renderStepThree($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L245)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepTwo"></a>renderStepTwo

```php
mixed AdminCarrierWizardControllerCore::renderStepTwo($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L226)


#### Arguments
* $carrier **mixed**



### <a name="method-renderView"></a>renderView

```php
mixed AdminCarrierWizardControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L98)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminCarrierWizardControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L59)




### <a name="method-validateForm"></a>validateForm

```php
mixed AdminCarrierWizardControllerCore::validateForm($die)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 630](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/controllers/admin/AdminCarrierWizardController.php#L630)


#### Arguments
* $die **mixed**


