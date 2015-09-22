AdminMetaControllerCore
===============






* Class name: AdminMetaControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminMetaController.php line 30





Properties
----------


### $table

    public mixed $table = 'meta'





* Visibility: **public**
* This property is defined in controllers\admin\AdminMetaController.php line 32


### $className

    public mixed $className = 'Meta'





* Visibility: **public**
* This property is defined in controllers\admin\AdminMetaController.php line 33


### $lang

    public mixed $lang = true





* Visibility: **public**
* This property is defined in controllers\admin\AdminMetaController.php line 34


### $url

    protected \ShopUrl $url = false





* Visibility: **protected**
* This property is defined in controllers\admin\AdminMetaController.php line 37


### $toolbar_scroll

    protected mixed $toolbar_scroll = false





* Visibility: **protected**
* This property is defined in controllers\admin\AdminMetaController.php line 38


### $object

    public \Meta $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminMetaController.php line 30


Methods
-------


### __construct

    mixed AdminMetaControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 40




### initPageHeaderToolbar

    mixed AdminMetaControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 229




### initProcess

    mixed AdminMetaControllerCore::initProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 242




### setMedia

    mixed AdminMetaControllerCore::setMedia()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 251




### addFieldRoute

    mixed AdminMetaControllerCore::addFieldRoute($route_id, $title)





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 258


#### Arguments
* $route_id **mixed**
* $title **mixed**



### renderForm

    mixed AdminMetaControllerCore::renderForm()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 275




### postProcess

    mixed AdminMetaControllerCore::postProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 388




### generateRobotsFile

    mixed AdminMetaControllerCore::generateRobotsFile()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 460




### getList

    mixed AdminMetaControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 540


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
* This method is defined in controllers\admin\AdminMetaController.php line 545




### checkAndUpdateRoute

    mixed AdminMetaControllerCore::checkAndUpdateRoute(string $route_id)

Validate route syntax and save it in configuration



* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 559


#### Arguments
* $route_id **string**



### updateOptionPsRewritingSettings

    mixed AdminMetaControllerCore::updateOptionPsRewritingSettings()

Called when PS_REWRITING_SETTINGS option is saved



* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 589




### updateOptionPsRouteProductRule

    mixed AdminMetaControllerCore::updateOptionPsRouteProductRule()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 614




### updateOptionPsRouteCategoryRule

    mixed AdminMetaControllerCore::updateOptionPsRouteCategoryRule()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 619




### updateOptionPsRouteLayeredRule

    mixed AdminMetaControllerCore::updateOptionPsRouteLayeredRule()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 624




### updateOptionPsRouteSupplierRule

    mixed AdminMetaControllerCore::updateOptionPsRouteSupplierRule()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 629




### updateOptionPsRouteManufacturerRule

    mixed AdminMetaControllerCore::updateOptionPsRouteManufacturerRule()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 634




### updateOptionPsRouteCmsRule

    mixed AdminMetaControllerCore::updateOptionPsRouteCmsRule()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 639




### updateOptionPsRouteCmsCategoryRule

    mixed AdminMetaControllerCore::updateOptionPsRouteCmsCategoryRule()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 644




### updateOptionDomain

    mixed AdminMetaControllerCore::updateOptionDomain(string $value)

Update shop domain (for mono shop)



* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 656


#### Arguments
* $value **string**



### updateOptionDomainSsl

    mixed AdminMetaControllerCore::updateOptionDomainSsl(string $value)

Update shop SSL domain (for mono shop)



* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 676


#### Arguments
* $value **string**



### updateOptionUri

    mixed AdminMetaControllerCore::updateOptionUri(string $value)

Update shop physical uri for mono shop)



* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 696


#### Arguments
* $value **string**



### renderOptions

    mixed AdminMetaControllerCore::renderOptions()

Function used to render the options for this controller



* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 707




### addAllRouteFields

    mixed AdminMetaControllerCore::addAllRouteFields()

Add all custom route fields to the options form



* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 735




### checkConfiguration

    boolean AdminMetaControllerCore::checkConfiguration(string $file)

Check if a file is writable



* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 753


#### Arguments
* $file **string**



### getRobotsContent

    mixed AdminMetaControllerCore::getRobotsContent()





* Visibility: **public**
* This method is defined in controllers\admin\AdminMetaController.php line 761



