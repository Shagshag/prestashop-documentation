AdminMetaControllerCore
===============






* Class name: AdminMetaControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $table

    public mixed $table = 'meta'





* Visibility: **public**


### $className

    public mixed $className = 'Meta'





* Visibility: **public**


### $lang

    public mixed $lang = true





* Visibility: **public**


### $url

    protected \ShopUrl $url = false





* Visibility: **protected**


### $toolbar_scroll

    protected mixed $toolbar_scroll = false





* Visibility: **protected**


### $object

    public \Meta $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminMetaControllerCore::__construct()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminMetaControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### initProcess

    mixed AdminMetaControllerCore::initProcess()





* Visibility: **public**




### setMedia

    mixed AdminMetaControllerCore::setMedia()





* Visibility: **public**




### addFieldRoute

    mixed AdminMetaControllerCore::addFieldRoute($route_id, $title)





* Visibility: **public**


#### Arguments
* $route_id **mixed**
* $title **mixed**



### renderForm

    mixed AdminMetaControllerCore::renderForm()





* Visibility: **public**




### postProcess

    mixed AdminMetaControllerCore::postProcess()





* Visibility: **public**




### generateRobotsFile

    mixed AdminMetaControllerCore::generateRobotsFile()





* Visibility: **public**




### getList

    mixed AdminMetaControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)





* Visibility: **public**


#### Arguments
* $id_lang **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### renderList

    mixed AdminMetaControllerCore::renderList()





* Visibility: **public**




### checkAndUpdateRoute

    mixed AdminMetaControllerCore::checkAndUpdateRoute(string $route_id)

Validate route syntax and save it in configuration



* Visibility: **public**


#### Arguments
* $route_id **string**



### updateOptionPsRewritingSettings

    mixed AdminMetaControllerCore::updateOptionPsRewritingSettings()

Called when PS_REWRITING_SETTINGS option is saved



* Visibility: **public**




### updateOptionPsRouteProductRule

    mixed AdminMetaControllerCore::updateOptionPsRouteProductRule()





* Visibility: **public**




### updateOptionPsRouteCategoryRule

    mixed AdminMetaControllerCore::updateOptionPsRouteCategoryRule()





* Visibility: **public**




### updateOptionPsRouteLayeredRule

    mixed AdminMetaControllerCore::updateOptionPsRouteLayeredRule()





* Visibility: **public**




### updateOptionPsRouteSupplierRule

    mixed AdminMetaControllerCore::updateOptionPsRouteSupplierRule()





* Visibility: **public**




### updateOptionPsRouteManufacturerRule

    mixed AdminMetaControllerCore::updateOptionPsRouteManufacturerRule()





* Visibility: **public**




### updateOptionPsRouteCmsRule

    mixed AdminMetaControllerCore::updateOptionPsRouteCmsRule()





* Visibility: **public**




### updateOptionPsRouteCmsCategoryRule

    mixed AdminMetaControllerCore::updateOptionPsRouteCmsCategoryRule()





* Visibility: **public**




### updateOptionDomain

    mixed AdminMetaControllerCore::updateOptionDomain(string $value)

Update shop domain (for mono shop)



* Visibility: **public**


#### Arguments
* $value **string**



### updateOptionDomainSsl

    mixed AdminMetaControllerCore::updateOptionDomainSsl(string $value)

Update shop SSL domain (for mono shop)



* Visibility: **public**


#### Arguments
* $value **string**



### updateOptionUri

    mixed AdminMetaControllerCore::updateOptionUri(string $value)

Update shop physical uri for mono shop)



* Visibility: **public**


#### Arguments
* $value **string**



### renderOptions

    mixed AdminMetaControllerCore::renderOptions()

Function used to render the options for this controller



* Visibility: **public**




### addAllRouteFields

    mixed AdminMetaControllerCore::addAllRouteFields()

Add all custom route fields to the options form



* Visibility: **public**




### checkConfiguration

    boolean AdminMetaControllerCore::checkConfiguration(string $file)

Check if a file is writable



* Visibility: **public**


#### Arguments
* $file **string**



### getRobotsContent

    mixed AdminMetaControllerCore::getRobotsContent()





* Visibility: **public**



