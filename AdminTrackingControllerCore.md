AdminTrackingControllerCore
===============






* Class name: AdminTrackingControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $bootstrap

    public mixed $bootstrap = true





* Visibility: **public**


### $_helper_list

    protected \HelperList $_helper_list





* Visibility: **protected**


### $object

    public \Product|\Category $object





* Visibility: **public**


Methods
-------


### postprocess

    mixed AdminTrackingControllerCore::postprocess()





* Visibility: **public**




### initContent

    mixed AdminTrackingControllerCore::initContent()





* Visibility: **public**




### getCustomListCategoriesEmpty

    mixed AdminTrackingControllerCore::getCustomListCategoriesEmpty()





* Visibility: **public**




### getCustomListProductsAttributesNoStock

    mixed AdminTrackingControllerCore::getCustomListProductsAttributesNoStock()





* Visibility: **public**




### getCustomListProductsNoStock

    mixed AdminTrackingControllerCore::getCustomListProductsNoStock()





* Visibility: **public**




### getCustomListProductsDisabled

    mixed AdminTrackingControllerCore::getCustomListProductsDisabled()





* Visibility: **public**




### renderList

    mixed AdminTrackingControllerCore::renderList()





* Visibility: **public**




### displayEnableLink

    mixed AdminTrackingControllerCore::displayEnableLink($token, $id, $value, $active, $id_category, $id_product)





* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **mixed**
* $value **mixed**
* $active **mixed**
* $id_category **mixed**
* $id_product **mixed**



### displayDeleteLink

    mixed AdminTrackingControllerCore::displayDeleteLink($token, $id, $name)





* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### displayEditLink

    mixed AdminTrackingControllerCore::displayEditLink($token, $id, $name)





* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### clearFilters

    mixed AdminTrackingControllerCore::clearFilters()





* Visibility: **protected**




### clearListOptions

    mixed AdminTrackingControllerCore::clearListOptions()





* Visibility: **public**




### getList

    mixed AdminTrackingControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### getDescriptionClean

    mixed AdminTrackingControllerCore::getDescriptionClean($description)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $description **mixed**


