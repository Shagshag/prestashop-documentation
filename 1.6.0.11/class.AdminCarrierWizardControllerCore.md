Class AdminCarrierWizardControllerCore
=====================





* Class name: AdminCarrierWizardControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCarrierWizardController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L27)


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


### <a name="property-$wizard_access"></a>$wizard_access

```php
protected mixed $wizard_access
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCarrierWizardControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L31)




### <a name="method-ajaxProcessChangeRanges"></a>ajaxProcessChangeRanges

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessChangeRanges()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 580](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L580)




### <a name="method-ajaxProcessFinishStep"></a>ajaxProcessFinishStep

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessFinishStep()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L753)




### <a name="method-ajaxProcessUploadLogo"></a>ajaxProcessUploadLogo

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessUploadLogo()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 727](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L727)




### <a name="method-ajaxProcessValidateStep"></a>ajaxProcessValidateStep

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessValidateStep()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L643)




### <a name="method-changeGroups"></a>changeGroups

```php
mixed AdminCarrierWizardControllerCore::changeGroups($id_carrier, $delete)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 870](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L870)


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### <a name="method-changeZones"></a>changeZones

```php
mixed AdminCarrierWizardControllerCore::changeZones($id)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 879](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L879)


#### Arguments
* $id **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed AdminCarrierWizardControllerCore::displayFieldName($field)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminCarrierWizardController.php line 929](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L929)


#### Arguments
* $field **mixed**



### <a name="method-duplicateLogo"></a>duplicateLogo

```php
mixed AdminCarrierWizardControllerCore::duplicateLogo($new_id, $old_id)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 934](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L934)


#### Arguments
* $new_id **mixed**
* $old_id **mixed**



### <a name="method-getActualCurrency"></a>getActualCurrency

```php
mixed AdminCarrierWizardControllerCore::getActualCurrency()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 949](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L949)




### <a name="method-getStepFiveFieldsValues"></a>getStepFiveFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepFiveFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 575](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L575)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepFourFieldsValues"></a>getStepFourFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepFourFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 563](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L563)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepOneFieldsValues"></a>getStepOneFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepOneFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 530](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L530)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepThreeFieldsValues"></a>getStepThreeFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepThreeFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 547](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L547)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepTwoFieldsValues"></a>getStepTwoFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepTwoFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 541](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L541)


#### Arguments
* $carrier **mixed**



### <a name="method-getTplRangesVarsAndValues"></a>getTplRangesVarsAndValues

```php
mixed AdminCarrierWizardControllerCore::getTplRangesVarsAndValues($carrier, $tpl_vars, $fields_value)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 464](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L464)


#### Arguments
* $carrier **mixed**
* $tpl_vars **mixed**
* $fields_value **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
mixed AdminCarrierWizardControllerCore::getValidationRules()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 899](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L899)




### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

```php
mixed AdminCarrierWizardControllerCore::initBreadcrumbs($tab_id, $tabs)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L147)


#### Arguments
* $tab_id **mixed**
* $tabs **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCarrierWizardControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L159)




### <a name="method-initWizard"></a>initWizard

```php
mixed AdminCarrierWizardControllerCore::initWizard()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L64)




### <a name="method-processRanges"></a>processRanges

```php
mixed AdminCarrierWizardControllerCore::processRanges($id_carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 648](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L648)


#### Arguments
* $id_carrier **mixed**



### <a name="method-renderGenericForm"></a>renderGenericForm

```php
mixed AdminCarrierWizardControllerCore::renderGenericForm($fields_form, $fields_value, $tpl_vars)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 508](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L508)


#### Arguments
* $fields_form **mixed**
* $fields_value **mixed**
* $tpl_vars **mixed**



### <a name="method-renderStepFive"></a>renderStepFive

```php
mixed AdminCarrierWizardControllerCore::renderStepFive($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 423](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L423)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepFour"></a>renderStepFour

```php
mixed AdminCarrierWizardControllerCore::renderStepFour($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L362)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepOne"></a>renderStepOne

```php
mixed AdminCarrierWizardControllerCore::renderStepOne($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L169)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepThree"></a>renderStepThree

```php
mixed AdminCarrierWizardControllerCore::renderStepThree($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 241](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L241)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepTwo"></a>renderStepTwo

```php
mixed AdminCarrierWizardControllerCore::renderStepTwo($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L222)


#### Arguments
* $carrier **mixed**



### <a name="method-renderView"></a>renderView

```php
mixed AdminCarrierWizardControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L95)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminCarrierWizardControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L56)




### <a name="method-validateForm"></a>validateForm

```php
mixed AdminCarrierWizardControllerCore::validateForm($die)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminCarrierWizardController.php#L611)


#### Arguments
* $die **mixed**


