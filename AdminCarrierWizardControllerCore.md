AdminCarrierWizardControllerCore
===============






* Class name: AdminCarrierWizardControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminCarrierWizardController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L30)





Properties
----------

* [$wizard_access](#property-$wizard_access)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [setMedia](#method-setMedia)
* [initWizard](#method-initWizard)
* [renderView](#method-renderView)
* [initBreadcrumbs](#method-initBreadcrumbs)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [renderStepOne](#method-renderStepOne)
* [renderStepTwo](#method-renderStepTwo)
* [renderStepThree](#method-renderStepThree)
* [renderStepFour](#method-renderStepFour)
* [renderStepFive](#method-renderStepFive)
* [getTplRangesVarsAndValues](#method-getTplRangesVarsAndValues)
* [renderGenericForm](#method-renderGenericForm)
* [getStepOneFieldsValues](#method-getStepOneFieldsValues)
* [getStepTwoFieldsValues](#method-getStepTwoFieldsValues)
* [getStepThreeFieldsValues](#method-getStepThreeFieldsValues)
* [getStepFourFieldsValues](#method-getStepFourFieldsValues)
* [getStepFiveFieldsValues](#method-getStepFiveFieldsValues)
* [ajaxProcessChangeRanges](#method-ajaxProcessChangeRanges)
* [validateForm](#method-validateForm)
* [ajaxProcessValidateStep](#method-ajaxProcessValidateStep)
* [processRanges](#method-processRanges)
* [ajaxProcessUploadLogo](#method-ajaxProcessUploadLogo)
* [ajaxProcessFinishStep](#method-ajaxProcessFinishStep)
* [changeGroups](#method-changeGroups)
* [changeZones](#method-changeZones)
* [getValidationRules](#method-getValidationRules)
* [displayFieldName](#method-displayFieldName)
* [duplicateLogo](#method-duplicateLogo)
* [getActualCurrency](#method-getActualCurrency)




Properties
----------


### <a name="property-$wizard_access"></a>$wizard_access

    protected mixed $wizard_access





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminCarrierWizardController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L32)


### <a name="property-$object"></a>$object

    public \Carrier $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminCarrierWizardController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminCarrierWizardControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L34)




### <a name="method-setMedia"></a>setMedia

    mixed AdminCarrierWizardControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L59)




### <a name="method-initWizard"></a>initWizard

    mixed AdminCarrierWizardControllerCore::initWizard()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L67)




### <a name="method-renderView"></a>renderView

    mixed AdminCarrierWizardControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L97)




### <a name="method-initBreadcrumbs"></a>initBreadcrumbs

    mixed AdminCarrierWizardControllerCore::initBreadcrumbs($tab_id, $tabs)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L150)


#### Arguments
* $tab_id **mixed**
* $tabs **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminCarrierWizardControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L163)




### <a name="method-renderStepOne"></a>renderStepOne

    mixed AdminCarrierWizardControllerCore::renderStepOne($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L173)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepTwo"></a>renderStepTwo

    mixed AdminCarrierWizardControllerCore::renderStepTwo($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L227)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepThree"></a>renderStepThree

    mixed AdminCarrierWizardControllerCore::renderStepThree($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L246)


#### Arguments
* $carrier **mixed**



### <a name="method-renderStepFour"></a>renderStepFour

    string AdminCarrierWizardControllerCore::renderStepFour(\Carrier $carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 376](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L376)


#### Arguments
* $carrier **[Carrier](CarrierCore)**



### <a name="method-renderStepFive"></a>renderStepFive

    mixed AdminCarrierWizardControllerCore::renderStepFive($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L440)


#### Arguments
* $carrier **mixed**



### <a name="method-getTplRangesVarsAndValues"></a>getTplRangesVarsAndValues

    mixed AdminCarrierWizardControllerCore::getTplRangesVarsAndValues(\Carrier $carrier, array $tpl_vars, array $fields_value)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 486](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L486)


#### Arguments
* $carrier **[Carrier](CarrierCore)**
* $tpl_vars **array**
* $fields_value **array**



### <a name="method-renderGenericForm"></a>renderGenericForm

    mixed AdminCarrierWizardControllerCore::renderGenericForm($fields_form, $fields_value, $tpl_vars)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 532](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L532)


#### Arguments
* $fields_form **mixed**
* $fields_value **mixed**
* $tpl_vars **mixed**



### <a name="method-getStepOneFieldsValues"></a>getStepOneFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepOneFieldsValues($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 553](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L553)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepTwoFieldsValues"></a>getStepTwoFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepTwoFieldsValues($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 564](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L564)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepThreeFieldsValues"></a>getStepThreeFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepThreeFieldsValues($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L569)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepFourFieldsValues"></a>getStepFourFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepFourFieldsValues($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 585](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L585)


#### Arguments
* $carrier **mixed**



### <a name="method-getStepFiveFieldsValues"></a>getStepFiveFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepFiveFieldsValues($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 597](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L597)


#### Arguments
* $carrier **mixed**



### <a name="method-ajaxProcessChangeRanges"></a>ajaxProcessChangeRanges

    mixed AdminCarrierWizardControllerCore::ajaxProcessChangeRanges()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 602](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L602)




### <a name="method-validateForm"></a>validateForm

    mixed AdminCarrierWizardControllerCore::validateForm($die)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 633](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L633)


#### Arguments
* $die **mixed**



### <a name="method-ajaxProcessValidateStep"></a>ajaxProcessValidateStep

    mixed AdminCarrierWizardControllerCore::ajaxProcessValidateStep()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L661)




### <a name="method-processRanges"></a>processRanges

    mixed AdminCarrierWizardControllerCore::processRanges($id_carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 666](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L666)


#### Arguments
* $id_carrier **mixed**



### <a name="method-ajaxProcessUploadLogo"></a>ajaxProcessUploadLogo

    mixed AdminCarrierWizardControllerCore::ajaxProcessUploadLogo()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 739](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L739)




### <a name="method-ajaxProcessFinishStep"></a>ajaxProcessFinishStep

    mixed AdminCarrierWizardControllerCore::ajaxProcessFinishStep()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 767](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L767)




### <a name="method-changeGroups"></a>changeGroups

    mixed AdminCarrierWizardControllerCore::changeGroups($id_carrier, $delete)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 873](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L873)


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### <a name="method-changeZones"></a>changeZones

    mixed AdminCarrierWizardControllerCore::changeZones($id)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 883](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L883)


#### Arguments
* $id **mixed**



### <a name="method-getValidationRules"></a>getValidationRules

    mixed AdminCarrierWizardControllerCore::getValidationRules()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 904](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L904)




### <a name="method-displayFieldName"></a>displayFieldName

    mixed AdminCarrierWizardControllerCore::displayFieldName($field)





* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 937](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L937)


#### Arguments
* $field **mixed**



### <a name="method-duplicateLogo"></a>duplicateLogo

    mixed AdminCarrierWizardControllerCore::duplicateLogo($new_id, $old_id)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 942](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L942)


#### Arguments
* $new_id **mixed**
* $old_id **mixed**



### <a name="method-getActualCurrency"></a>getActualCurrency

    mixed AdminCarrierWizardControllerCore::getActualCurrency()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 958](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L958)



