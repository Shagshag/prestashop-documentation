AdminCarrierWizardControllerCore
===============






* Class name: AdminCarrierWizardControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminCarrierWizardController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#L30)





Properties
----------


### $wizard_access

    protected mixed $wizard_access





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminCarrierWizardController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#32)


### $object

    public \Carrier $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminCarrierWizardController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#30)


Methods
-------


### __construct

    mixed AdminCarrierWizardControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#34)




### setMedia

    mixed AdminCarrierWizardControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#59)




### initWizard

    mixed AdminCarrierWizardControllerCore::initWizard()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#67)




### renderView

    mixed AdminCarrierWizardControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#97)




### initBreadcrumbs

    mixed AdminCarrierWizardControllerCore::initBreadcrumbs($tab_id, $tabs)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#150)


#### Arguments
* $tab_id **mixed**
* $tabs **mixed**



### initPageHeaderToolbar

    mixed AdminCarrierWizardControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#163)




### renderStepOne

    mixed AdminCarrierWizardControllerCore::renderStepOne($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#173)


#### Arguments
* $carrier **mixed**



### renderStepTwo

    mixed AdminCarrierWizardControllerCore::renderStepTwo($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#227)


#### Arguments
* $carrier **mixed**



### renderStepThree

    mixed AdminCarrierWizardControllerCore::renderStepThree($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 246](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#246)


#### Arguments
* $carrier **mixed**



### renderStepFour

    string AdminCarrierWizardControllerCore::renderStepFour(\Carrier $carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 376](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#376)


#### Arguments
* $carrier **[Carrier](CarrierCore)**



### renderStepFive

    mixed AdminCarrierWizardControllerCore::renderStepFive($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#440)


#### Arguments
* $carrier **mixed**



### getTplRangesVarsAndValues

    mixed AdminCarrierWizardControllerCore::getTplRangesVarsAndValues(\Carrier $carrier, array $tpl_vars, array $fields_value)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 486](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#486)


#### Arguments
* $carrier **[Carrier](CarrierCore)**
* $tpl_vars **array**
* $fields_value **array**



### renderGenericForm

    mixed AdminCarrierWizardControllerCore::renderGenericForm($fields_form, $fields_value, $tpl_vars)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 532](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#532)


#### Arguments
* $fields_form **mixed**
* $fields_value **mixed**
* $tpl_vars **mixed**



### getStepOneFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepOneFieldsValues($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 553](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#553)


#### Arguments
* $carrier **mixed**



### getStepTwoFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepTwoFieldsValues($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 564](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#564)


#### Arguments
* $carrier **mixed**



### getStepThreeFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepThreeFieldsValues($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 569](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#569)


#### Arguments
* $carrier **mixed**



### getStepFourFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepFourFieldsValues($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 585](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#585)


#### Arguments
* $carrier **mixed**



### getStepFiveFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepFiveFieldsValues($carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 597](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#597)


#### Arguments
* $carrier **mixed**



### ajaxProcessChangeRanges

    mixed AdminCarrierWizardControllerCore::ajaxProcessChangeRanges()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 602](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#602)




### validateForm

    mixed AdminCarrierWizardControllerCore::validateForm($die)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 633](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#633)


#### Arguments
* $die **mixed**



### ajaxProcessValidateStep

    mixed AdminCarrierWizardControllerCore::ajaxProcessValidateStep()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 661](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#661)




### processRanges

    mixed AdminCarrierWizardControllerCore::processRanges($id_carrier)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 666](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#666)


#### Arguments
* $id_carrier **mixed**



### ajaxProcessUploadLogo

    mixed AdminCarrierWizardControllerCore::ajaxProcessUploadLogo()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 739](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#739)




### ajaxProcessFinishStep

    mixed AdminCarrierWizardControllerCore::ajaxProcessFinishStep()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 767](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#767)




### changeGroups

    mixed AdminCarrierWizardControllerCore::changeGroups($id_carrier, $delete)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 873](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#873)


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### changeZones

    mixed AdminCarrierWizardControllerCore::changeZones($id)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 883](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#883)


#### Arguments
* $id **mixed**



### getValidationRules

    mixed AdminCarrierWizardControllerCore::getValidationRules()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 904](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#904)




### displayFieldName

    mixed AdminCarrierWizardControllerCore::displayFieldName($field)





* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 937](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#937)


#### Arguments
* $field **mixed**



### duplicateLogo

    mixed AdminCarrierWizardControllerCore::duplicateLogo($new_id, $old_id)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 942](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#942)


#### Arguments
* $new_id **mixed**
* $old_id **mixed**



### getActualCurrency

    mixed AdminCarrierWizardControllerCore::getActualCurrency()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminCarrierWizardController.php line 958](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCarrierWizardController.php#958)



