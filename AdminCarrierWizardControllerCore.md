AdminCarrierWizardControllerCore
===============






* Class name: AdminCarrierWizardControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $wizard_access

    protected mixed $wizard_access





* Visibility: **protected**


### $object

    public \Carrier $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminCarrierWizardControllerCore::__construct()





* Visibility: **public**




### setMedia

    mixed AdminCarrierWizardControllerCore::setMedia()





* Visibility: **public**




### initWizard

    mixed AdminCarrierWizardControllerCore::initWizard()





* Visibility: **public**




### renderView

    mixed AdminCarrierWizardControllerCore::renderView()





* Visibility: **public**




### initBreadcrumbs

    mixed AdminCarrierWizardControllerCore::initBreadcrumbs($tab_id, $tabs)





* Visibility: **public**


#### Arguments
* $tab_id **mixed**
* $tabs **mixed**



### initPageHeaderToolbar

    mixed AdminCarrierWizardControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### renderStepOne

    mixed AdminCarrierWizardControllerCore::renderStepOne($carrier)





* Visibility: **public**


#### Arguments
* $carrier **mixed**



### renderStepTwo

    mixed AdminCarrierWizardControllerCore::renderStepTwo($carrier)





* Visibility: **public**


#### Arguments
* $carrier **mixed**



### renderStepThree

    mixed AdminCarrierWizardControllerCore::renderStepThree($carrier)





* Visibility: **public**


#### Arguments
* $carrier **mixed**



### renderStepFour

    string AdminCarrierWizardControllerCore::renderStepFour(\Carrier $carrier)





* Visibility: **public**


#### Arguments
* $carrier **Carrier**



### renderStepFive

    mixed AdminCarrierWizardControllerCore::renderStepFive($carrier)





* Visibility: **public**


#### Arguments
* $carrier **mixed**



### getTplRangesVarsAndValues

    mixed AdminCarrierWizardControllerCore::getTplRangesVarsAndValues(\Carrier $carrier, array $tpl_vars, array $fields_value)





* Visibility: **protected**


#### Arguments
* $carrier **Carrier**
* $tpl_vars **array**
* $fields_value **array**



### renderGenericForm

    mixed AdminCarrierWizardControllerCore::renderGenericForm($fields_form, $fields_value, $tpl_vars)





* Visibility: **public**


#### Arguments
* $fields_form **mixed**
* $fields_value **mixed**
* $tpl_vars **mixed**



### getStepOneFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepOneFieldsValues($carrier)





* Visibility: **public**


#### Arguments
* $carrier **mixed**



### getStepTwoFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepTwoFieldsValues($carrier)





* Visibility: **public**


#### Arguments
* $carrier **mixed**



### getStepThreeFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepThreeFieldsValues($carrier)





* Visibility: **public**


#### Arguments
* $carrier **mixed**



### getStepFourFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepFourFieldsValues($carrier)





* Visibility: **public**


#### Arguments
* $carrier **mixed**



### getStepFiveFieldsValues

    mixed AdminCarrierWizardControllerCore::getStepFiveFieldsValues($carrier)





* Visibility: **public**


#### Arguments
* $carrier **mixed**



### ajaxProcessChangeRanges

    mixed AdminCarrierWizardControllerCore::ajaxProcessChangeRanges()





* Visibility: **public**




### validateForm

    mixed AdminCarrierWizardControllerCore::validateForm($die)





* Visibility: **protected**


#### Arguments
* $die **mixed**



### ajaxProcessValidateStep

    mixed AdminCarrierWizardControllerCore::ajaxProcessValidateStep()





* Visibility: **public**




### processRanges

    mixed AdminCarrierWizardControllerCore::processRanges($id_carrier)





* Visibility: **public**


#### Arguments
* $id_carrier **mixed**



### ajaxProcessUploadLogo

    mixed AdminCarrierWizardControllerCore::ajaxProcessUploadLogo()





* Visibility: **public**




### ajaxProcessFinishStep

    mixed AdminCarrierWizardControllerCore::ajaxProcessFinishStep()





* Visibility: **public**




### changeGroups

    mixed AdminCarrierWizardControllerCore::changeGroups($id_carrier, $delete)





* Visibility: **protected**


#### Arguments
* $id_carrier **mixed**
* $delete **mixed**



### changeZones

    mixed AdminCarrierWizardControllerCore::changeZones($id)





* Visibility: **public**


#### Arguments
* $id **mixed**



### getValidationRules

    mixed AdminCarrierWizardControllerCore::getValidationRules()





* Visibility: **public**




### displayFieldName

    mixed AdminCarrierWizardControllerCore::displayFieldName($field)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $field **mixed**



### duplicateLogo

    mixed AdminCarrierWizardControllerCore::duplicateLogo($new_id, $old_id)





* Visibility: **public**


#### Arguments
* $new_id **mixed**
* $old_id **mixed**



### getActualCurrency

    mixed AdminCarrierWizardControllerCore::getActualCurrency()





* Visibility: **public**



