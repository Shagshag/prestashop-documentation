Class AdminCarrierWizardControllerCore
=====================





* Class name: AdminCarrierWizardControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCarrierWizardController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L27)


Contents
--------


### Properties

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
* [getStepFiveFieldsValues](#method-getStepFiveFieldsValues)
* [getStepFourFieldsValues](#method-getStepFourFieldsValues)
* [getStepOneFieldsValues](#method-getStepOneFieldsValues)
* [getStepThreeFieldsValues](#method-getStepThreeFieldsValues)
* [getStepTwoFieldsValues](#method-getStepTwoFieldsValues)
* [getTplRangesVarsAndValues](#method-getTplRangesVarsAndValues)
* [getValidationRules](#method-getValidationRules)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initToolbarTitle](#method-initToolbarTitle)
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




Properties
----------


### <a name="property-$wizard_access"></a>$wizard_access

```php
protected mixed $wizard_access
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCarrierWizardControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L31)




### <a name="method-ajaxProcessChangeRanges"></a>ajaxProcessChangeRanges

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessChangeRanges()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 566](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L566)




### <a name="method-ajaxProcessFinishStep"></a>ajaxProcessFinishStep

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessFinishStep()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 728](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L728)




### <a name="method-ajaxProcessUploadLogo"></a>ajaxProcessUploadLogo

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessUploadLogo()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 702](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L702)




### <a name="method-ajaxProcessValidateStep"></a>ajaxProcessValidateStep

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessValidateStep()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 596](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L596)




### <a name="method-changeGroups"></a>changeGroups

```php
mixed AdminCarrierWizardControllerCore::changeGroups($id_carrier, $delete)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 845](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L845)


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### <a name="method-changeZones"></a>changeZones

```php
mixed AdminCarrierWizardControllerCore::changeZones($id)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 854](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L854)


#### Arguments
* $id **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed AdminCarrierWizardControllerCore::displayFieldName($field)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminCarrierWizardController.php line 902](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L902)


#### Arguments
* $field **mixed**



### <a name="method-duplicateLogo"></a>duplicateLogo

```php
mixed AdminCarrierWizardControllerCore::duplicateLogo($new_id, $old_id)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 907](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L907)


#### Arguments
* $new_id **mixed**
* $old_id **mixed**



### <a name="method-getStepFiveFieldsValues"></a>getStepFiveFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepFiveFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 561](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L561)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepFourFieldsValues"></a>getStepFourFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepFourFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 549](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L549)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepOneFieldsValues"></a>getStepOneFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepOneFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 516](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L516)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepThreeFieldsValues"></a>getStepThreeFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepThreeFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 533](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L533)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepTwoFieldsValues"></a>getStepTwoFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepTwoFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 527](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L527)


#### Arguments
* $carrier **mixed**



### <a name="method-getTplRangesVarsAndValues"></a>getTplRangesVarsAndValues

```php
mixed AdminCarrierWizardControllerCore::getTplRangesVarsAndValues($carrier, $tpl_vars, $fields_value)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 451](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L451)


#### Arguments
* $carrier **mixed**
* $tpl_vars **mixed**
* $fields_value **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
mixed AdminCarrierWizardControllerCore::getValidationRules()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 874](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L874)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCarrierWizardControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L152)




### <a name="method-initToolbarTitle"></a>initToolbarTitle

```php
mixed AdminCarrierWizardControllerCore::initToolbarTitle()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L140)




### <a name="method-initWizard"></a>initWizard

```php
mixed AdminCarrierWizardControllerCore::initWizard()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L63)




### <a name="method-processRanges"></a>processRanges

```php
mixed AdminCarrierWizardControllerCore::processRanges($id_carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 625](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L625)


#### Arguments
* $id_carrier **mixed**



### <a name="method-renderGenericForm"></a>renderGenericForm

```php
mixed AdminCarrierWizardControllerCore::renderGenericForm($fields_form, $fields_value, $tpl_vars)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 495](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L495)


#### Arguments
* $fields_form **mixed**
* $fields_value **mixed**
* $tpl_vars **mixed**



### <a name="method-renderStepFive"></a>renderStepFive

```php
mixed AdminCarrierWizardControllerCore::renderStepFive($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L408)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepFour"></a>renderStepFour

```php
mixed AdminCarrierWizardControllerCore::renderStepFour($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 347](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L347)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepOne"></a>renderStepOne

```php
mixed AdminCarrierWizardControllerCore::renderStepOne($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L158)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepThree"></a>renderStepThree

```php
mixed AdminCarrierWizardControllerCore::renderStepThree($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L228)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepTwo"></a>renderStepTwo

```php
mixed AdminCarrierWizardControllerCore::renderStepTwo($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L211)


#### Arguments
* $carrier **mixed**



### <a name="method-renderView"></a>renderView

```php
mixed AdminCarrierWizardControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L94)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminCarrierWizardControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/controllers/admin/AdminCarrierWizardController.php#L55)



