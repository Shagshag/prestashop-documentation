Class AdminCarrierWizardControllerCore
=====================





* Class name: AdminCarrierWizardControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminCarrierWizardController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L30)



Properties
----------

* [$object](#property-$object)
* [$wizard_access](#property-$wizard_access)

Methods
-------
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

    public \Carrier $object





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L30).


### <a name="property-$wizard_access"></a>$wizard_access

    protected mixed $wizard_access





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminCarrierWizardControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L34)




### <a name="method-ajaxProcessChangeRanges"></a>ajaxProcessChangeRanges

    mixed AdminCarrierWizardControllerCore::ajaxProcessChangeRanges()





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 602](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L602)




### <a name="method-ajaxProcessFinishStep"></a>ajaxProcessFinishStep

    mixed AdminCarrierWizardControllerCore::ajaxProcessFinishStep()





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 767](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L767)




### <a name="method-ajaxProcessUploadLogo"></a>ajaxProcessUploadLogo

    mixed AdminCarrierWizardControllerCore::ajaxProcessUploadLogo()





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 739](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L739)




### <a name="method-ajaxProcessValidateStep"></a>ajaxProcessValidateStep

    mixed AdminCarrierWizardControllerCore::ajaxProcessValidateStep()





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L661)




### <a name="method-changeGroups"></a>changeGroups

    mixed AdminCarrierWizardControllerCore::changeGroups($id_carrier, $delete)





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 873](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L873)


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### <a name="method-changeZones"></a>changeZones

    mixed AdminCarrierWizardControllerCore::changeZones($id)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 883](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L883)


#### Arguments
* $id **mixed**



### <a name="method-displayFieldName"></a>displayFieldName

    mixed AdminCarrierWizardControllerCore::displayFieldName($field)





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminCarrierWizardController.php line 937](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L937)


#### Arguments
* $field **mixed**



### <a name="method-duplicateLogo"></a>duplicateLogo

    mixed AdminCarrierWizardControllerCore::duplicateLogo($new_id, $old_id)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 942](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L942)


#### Arguments
* $new_id **mixed**
* $old_id **mixed**



### <a name="method-getActualCurrency"></a>getActualCurrency

    mixed AdminCarrierWizardControllerCore::getActualCurrency()





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 958](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L958)




### <a name="method-getStepFiveFieldsValues"></a>getStepFiveFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepFiveFieldsValues($carrier)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 597](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L597)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepFourFieldsValues"></a>getStepFourFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepFourFieldsValues($carrier)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 585](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L585)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepOneFieldsValues"></a>getStepOneFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepOneFieldsValues($carrier)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 553](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L553)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepThreeFieldsValues"></a>getStepThreeFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepThreeFieldsValues($carrier)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L569)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepTwoFieldsValues"></a>getStepTwoFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepTwoFieldsValues($carrier)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 564](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L564)


#### Arguments
* $carrier **mixed**



### <a name="method-getTplRangesVarsAndValues"></a>getTplRangesVarsAndValues

    mixed AdminCarrierWizardControllerCore::getTplRangesVarsAndValues(\Carrier $carrier, array $tpl_vars, array $fields_value)





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 486](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L486)


#### Arguments
* $carrier **[Carrier](class.CarrierCore.md)**
* $tpl_vars **array**
* $fields_value **array**



### <a name="method-getValidationRules"></a>getValidationRules

    mixed AdminCarrierWizardControllerCore::getValidationRules()





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 904](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L904)




### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

    mixed AdminCarrierWizardControllerCore::initBreadcrumbs($tab_id, $tabs)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L150)


#### Arguments
* $tab_id **mixed**
* $tabs **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminCarrierWizardControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L163)




### <a name="method-initWizard"></a>initWizard

    mixed AdminCarrierWizardControllerCore::initWizard()





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L67)




### <a name="method-processRanges"></a>processRanges

    mixed AdminCarrierWizardControllerCore::processRanges($id_carrier)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 666](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L666)


#### Arguments
* $id_carrier **mixed**



### <a name="method-renderGenericForm"></a>renderGenericForm

    mixed AdminCarrierWizardControllerCore::renderGenericForm($fields_form, $fields_value, $tpl_vars)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 532](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L532)


#### Arguments
* $fields_form **mixed**
* $fields_value **mixed**
* $tpl_vars **mixed**



### <a name="method-renderStepFive"></a>renderStepFive

    mixed AdminCarrierWizardControllerCore::renderStepFive($carrier)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L440)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepFour"></a>renderStepFour

    string AdminCarrierWizardControllerCore::renderStepFour(\Carrier $carrier)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 376](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L376)


#### Arguments
* $carrier **[Carrier](class.CarrierCore.md)**



### <a name="method-renderStepOne"></a>renderStepOne

    mixed AdminCarrierWizardControllerCore::renderStepOne($carrier)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L173)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepThree"></a>renderStepThree

    mixed AdminCarrierWizardControllerCore::renderStepThree($carrier)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L246)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepTwo"></a>renderStepTwo

    mixed AdminCarrierWizardControllerCore::renderStepTwo($carrier)





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L227)


#### Arguments
* $carrier **mixed**



### <a name="method-renderView"></a>renderView

    mixed AdminCarrierWizardControllerCore::renderView()





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L97)




### <a name="method-setMedia"></a>setMedia

    mixed AdminCarrierWizardControllerCore::setMedia()





* Visibility: **public**
* Source: [controllers/admin/AdminCarrierWizardController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L59)




### <a name="method-validateForm"></a>validateForm

    mixed AdminCarrierWizardControllerCore::validateForm($die)





* Visibility: **protected**
* Source: [controllers/admin/AdminCarrierWizardController.php line 633](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L633)


#### Arguments
* $die **mixed**


