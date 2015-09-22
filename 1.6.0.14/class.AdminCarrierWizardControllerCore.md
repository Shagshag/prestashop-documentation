Class AdminCarrierWizardControllerCore
=====================





* Class name: AdminCarrierWizardControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCarrierWizardController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L27)


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
* Source: [controllers/admin/AdminCarrierWizardController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminCarrierWizardControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L31)




### <a name="method-ajaxProcessChangeRanges"></a>ajaxProcessChangeRanges

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessChangeRanges()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 581](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L581)




### <a name="method-ajaxProcessFinishStep"></a>ajaxProcessFinishStep

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessFinishStep()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 754](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L754)




### <a name="method-ajaxProcessUploadLogo"></a>ajaxProcessUploadLogo

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessUploadLogo()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 728](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L728)




### <a name="method-ajaxProcessValidateStep"></a>ajaxProcessValidateStep

```php
mixed AdminCarrierWizardControllerCore::ajaxProcessValidateStep()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 644](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L644)




### <a name="method-changeGroups"></a>changeGroups

```php
mixed AdminCarrierWizardControllerCore::changeGroups($id_carrier, $delete)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 871](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L871)


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### <a name="method-changeZones"></a>changeZones

```php
mixed AdminCarrierWizardControllerCore::changeZones($id)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 880](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L880)


#### Arguments
* $id **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

```php
mixed AdminCarrierWizardControllerCore::displayFieldName($field)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminCarrierWizardController.php line 930](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L930)


#### Arguments
* $field **mixed**



### <a name="method-duplicateLogo"></a>duplicateLogo

```php
mixed AdminCarrierWizardControllerCore::duplicateLogo($new_id, $old_id)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 935](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L935)


#### Arguments
* $new_id **mixed**
* $old_id **mixed**



### <a name="method-getActualCurrency"></a>getActualCurrency

```php
mixed AdminCarrierWizardControllerCore::getActualCurrency()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 950](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L950)




### <a name="method-getStepFiveFieldsValues"></a>getStepFiveFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepFiveFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 576](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L576)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepFourFieldsValues"></a>getStepFourFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepFourFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 564](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L564)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepOneFieldsValues"></a>getStepOneFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepOneFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 531](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L531)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepThreeFieldsValues"></a>getStepThreeFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepThreeFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 548](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L548)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepTwoFieldsValues"></a>getStepTwoFieldsValues

```php
mixed AdminCarrierWizardControllerCore::getStepTwoFieldsValues($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 542](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L542)


#### Arguments
* $carrier **mixed**



### <a name="method-getTplRangesVarsAndValues"></a>getTplRangesVarsAndValues

```php
mixed AdminCarrierWizardControllerCore::getTplRangesVarsAndValues($carrier, $tpl_vars, $fields_value)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 465](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L465)


#### Arguments
* $carrier **mixed**
* $tpl_vars **mixed**
* $fields_value **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

```php
mixed AdminCarrierWizardControllerCore::getValidationRules()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 900](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L900)




### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

```php
mixed AdminCarrierWizardControllerCore::initBreadcrumbs($tab_id, $tabs)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L147)


#### Arguments
* $tab_id **mixed**
* $tabs **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminCarrierWizardControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L159)




### <a name="method-initWizard"></a>initWizard

```php
mixed AdminCarrierWizardControllerCore::initWizard()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L64)




### <a name="method-processRanges"></a>processRanges

```php
mixed AdminCarrierWizardControllerCore::processRanges($id_carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L649)


#### Arguments
* $id_carrier **mixed**



### <a name="method-renderGenericForm"></a>renderGenericForm

```php
mixed AdminCarrierWizardControllerCore::renderGenericForm($fields_form, $fields_value, $tpl_vars)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 509](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L509)


#### Arguments
* $fields_form **mixed**
* $fields_value **mixed**
* $tpl_vars **mixed**



### <a name="method-renderStepFive"></a>renderStepFive

```php
mixed AdminCarrierWizardControllerCore::renderStepFive($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 424](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L424)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepFour"></a>renderStepFour

```php
mixed AdminCarrierWizardControllerCore::renderStepFour($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 363](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L363)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepOne"></a>renderStepOne

```php
mixed AdminCarrierWizardControllerCore::renderStepOne($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L169)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepThree"></a>renderStepThree

```php
mixed AdminCarrierWizardControllerCore::renderStepThree($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L242)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepTwo"></a>renderStepTwo

```php
mixed AdminCarrierWizardControllerCore::renderStepTwo($carrier)
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L223)


#### Arguments
* $carrier **mixed**



### <a name="method-renderView"></a>renderView

```php
mixed AdminCarrierWizardControllerCore::renderView()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L95)




### <a name="method-setMedia"></a>setMedia

```php
mixed AdminCarrierWizardControllerCore::setMedia()
```





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L56)




### <a name="method-validateForm"></a>validateForm

```php
mixed AdminCarrierWizardControllerCore::validateForm($die)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 612](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/controllers/admin/AdminCarrierWizardController.php#L612)


#### Arguments
* $die **mixed**


