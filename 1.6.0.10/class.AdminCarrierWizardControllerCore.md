Class AdminCarrierWizardControllerCore
=====================





* Class name: AdminCarrierWizardControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCarrierWizardController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L27)


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


### <a name="property-$wizard_access"></a>$wizard_access

```php
protected mixed $wizard_access
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCarrierWizardControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L31)




### <a name="method-ajaxProcessChangeRanges"></a>ajaxProcessChangeRanges

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessChangeRanges()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 572](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L572)




### <a name="method-ajaxProcessFinishStep"></a>ajaxProcessFinishStep

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessFinishStep()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 744](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L744)




### <a name="method-ajaxProcessUploadLogo"></a>ajaxProcessUploadLogo

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessUploadLogo()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 718](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L718)




### <a name="method-ajaxProcessValidateStep"></a>ajaxProcessValidateStep

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessValidateStep()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 634](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L634)




### <a name="method-changeGroups"></a>changeGroups

```php
mixed AdminCarrierWizardControllerCore::changeGroups($id_carrier, $delete)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 861](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L861)


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### <a name="method-changeZones"></a>changeZones

```php
mixed AdminCarrierWizardControllerCore::changeZones($id)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 870](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L870)


#### Arguments
* $id **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed AdminCarrierWizardControllerCore::displayFieldName($field)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminCarrierWizardController.php line 920](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L920)


#### Arguments
* $field **mixed**



### <a name="method-duplicateLogo"></a>duplicateLogo

```php
mixed AdminCarrierWizardControllerCore::duplicateLogo($new_id, $old_id)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 925](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L925)


#### Arguments
* $new_id **mixed**
* $old_id **mixed**



### <a name="method-getStepFiveFieldsValues"></a>getStepFiveFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepFiveFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 567](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L567)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepFourFieldsValues"></a>getStepFourFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepFourFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 555](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L555)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepOneFieldsValues"></a>getStepOneFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepOneFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 522](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L522)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepThreeFieldsValues"></a>getStepThreeFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepThreeFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 539](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L539)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepTwoFieldsValues"></a>getStepTwoFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepTwoFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 533](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L533)


#### Arguments
* $carrier **mixed**



### <a name="method-getTplRangesVarsAndValues"></a>getTplRangesVarsAndValues

```php
mixed AdminCarrierWizardControllerCore::getTplRangesVarsAndValues($carrier, $tpl_vars, $fields_value)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 457](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L457)


#### Arguments
* $carrier **mixed**
* $tpl_vars **mixed**
* $fields_value **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
mixed AdminCarrierWizardControllerCore::getValidationRules()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 890](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L890)




### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

```php
mixed AdminCarrierWizardControllerCore::initBreadcrumbs($tab_id, $tabs)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L144)


#### Arguments
* $tab_id **mixed**
* $tabs **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCarrierWizardControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L156)




### <a name="method-initWizard"></a>initWizard

```php
mixed AdminCarrierWizardControllerCore::initWizard()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L63)




### <a name="method-processRanges"></a>processRanges

```php
mixed AdminCarrierWizardControllerCore::processRanges($id_carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 639](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L639)


#### Arguments
* $id_carrier **mixed**



### <a name="method-renderGenericForm"></a>renderGenericForm

```php
mixed AdminCarrierWizardControllerCore::renderGenericForm($fields_form, $fields_value, $tpl_vars)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 501](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L501)


#### Arguments
* $fields_form **mixed**
* $fields_value **mixed**
* $tpl_vars **mixed**



### <a name="method-renderStepFive"></a>renderStepFive

```php
mixed AdminCarrierWizardControllerCore::renderStepFive($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 416](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L416)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepFour"></a>renderStepFour

```php
mixed AdminCarrierWizardControllerCore::renderStepFour($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L355)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepOne"></a>renderStepOne

```php
mixed AdminCarrierWizardControllerCore::renderStepOne($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L166)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepThree"></a>renderStepThree

```php
mixed AdminCarrierWizardControllerCore::renderStepThree($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 236](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L236)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepTwo"></a>renderStepTwo

```php
mixed AdminCarrierWizardControllerCore::renderStepTwo($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 219](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L219)


#### Arguments
* $carrier **mixed**



### <a name="method-renderView"></a>renderView

```php
mixed AdminCarrierWizardControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L94)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminCarrierWizardControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L55)




### <a name="method-validateForm"></a>validateForm

```php
mixed AdminCarrierWizardControllerCore::validateForm($die)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 602](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/controllers/admin/AdminCarrierWizardController.php#L602)


#### Arguments
* $die **mixed**


