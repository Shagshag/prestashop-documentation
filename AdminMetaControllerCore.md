AdminMetaControllerCore
===============






* Class name: AdminMetaControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminMetaController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L30)





Properties
----------

* [$table](#property-$table)
* [$className](#property-$className)
* [$lang](#property-$lang)
* [$url](#property-$url)
* [$toolbar_scroll](#property-$toolbar_scroll)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initProcess](#method-initProcess)
* [setMedia](#method-setMedia)
* [addFieldRoute](#method-addFieldRoute)
* [renderForm](#method-renderForm)
* [postProcess](#method-postProcess)
* [generateRobotsFile](#method-generateRobotsFile)
* [getList](#method-getList)
* [renderList](#method-renderList)
* [checkAndUpdateRoute](#method-checkAndUpdateRoute)
* [updateOptionPsRewritingSettings](#method-updateOptionPsRewritingSettings)
* [updateOptionPsRouteProductRule](#method-updateOptionPsRouteProductRule)
* [updateOptionPsRouteCategoryRule](#method-updateOptionPsRouteCategoryRule)
* [updateOptionPsRouteLayeredRule](#method-updateOptionPsRouteLayeredRule)
* [updateOptionPsRouteSupplierRule](#method-updateOptionPsRouteSupplierRule)
* [updateOptionPsRouteManufacturerRule](#method-updateOptionPsRouteManufacturerRule)
* [updateOptionPsRouteCmsRule](#method-updateOptionPsRouteCmsRule)
* [updateOptionPsRouteCmsCategoryRule](#method-updateOptionPsRouteCmsCategoryRule)
* [updateOptionDomain](#method-updateOptionDomain)
* [updateOptionDomainSsl](#method-updateOptionDomainSsl)
* [updateOptionUri](#method-updateOptionUri)
* [renderOptions](#method-renderOptions)
* [addAllRouteFields](#method-addAllRouteFields)
* [checkConfiguration](#method-checkConfiguration)
* [getRobotsContent](#method-getRobotsContent)




Properties
----------


### <a name="property-$table"></a>$table

    public mixed $table = 'meta'





* Visibility: **public**
* This property is defined in [controllers/admin/AdminMetaController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L32)


### <a name="property-$className"></a>$className

    public mixed $className = 'Meta'





* Visibility: **public**
* This property is defined in [controllers/admin/AdminMetaController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L33)


### <a name="property-$lang"></a>$lang

    public mixed $lang = true





* Visibility: **public**
* This property is defined in [controllers/admin/AdminMetaController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L34)


### <a name="property-$url"></a>$url

    protected \ShopUrl $url = false





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminMetaController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L37)


### <a name="property-$toolbar_scroll"></a>$toolbar_scroll

    protected mixed $toolbar_scroll = false





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminMetaController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L38)


### <a name="property-$object"></a>$object

    public \Meta $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminMetaController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminMetaControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L40)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminMetaControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L229)




### <a name="method-initProcess"></a>initProcess

    mixed AdminMetaControllerCore::initProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 242](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L242)




### <a name="method-setMedia"></a>setMedia

    mixed AdminMetaControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L251)




### <a name="method-addFieldRoute"></a>addFieldRoute

    mixed AdminMetaControllerCore::addFieldRoute($route_id, $title)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L258)


#### Arguments
* $route_id **mixed**
* $title **mixed**



### <a name="method-renderForm"></a>renderForm

    mixed AdminMetaControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L275)




### <a name="method-postProcess"></a>postProcess

    mixed AdminMetaControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 388](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L388)




### <a name="method-generateRobotsFile"></a>generateRobotsFile

    mixed AdminMetaControllerCore::generateRobotsFile()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 460](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L460)




### <a name="method-getList"></a>getList

    mixed AdminMetaControllerCore::getList($id_lang, $orderBy, $orderWay, $start, $limit, $id_lang_shop)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 540](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L540)


#### Arguments
* $id_lang **mixed**
* $orderBy **mixed**
* $orderWay **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-renderList"></a>renderList

    mixed AdminMetaControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 545](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L545)




### <a name="method-checkAndUpdateRoute"></a>checkAndUpdateRoute

    mixed AdminMetaControllerCore::checkAndUpdateRoute(string $route_id)

Validate route syntax and save it in configuration



* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L559)


#### Arguments
* $route_id **string**



### <a name="method-updateOptionPsRewritingSettings"></a>updateOptionPsRewritingSettings

    mixed AdminMetaControllerCore::updateOptionPsRewritingSettings()

Called when PS_REWRITING_SETTINGS option is saved



* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 589](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L589)




### <a name="method-updateOptionPsRouteProductRule"></a>updateOptionPsRouteProductRule

    mixed AdminMetaControllerCore::updateOptionPsRouteProductRule()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 614](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L614)




### <a name="method-updateOptionPsRouteCategoryRule"></a>updateOptionPsRouteCategoryRule

    mixed AdminMetaControllerCore::updateOptionPsRouteCategoryRule()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 619](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L619)




### <a name="method-updateOptionPsRouteLayeredRule"></a>updateOptionPsRouteLayeredRule

    mixed AdminMetaControllerCore::updateOptionPsRouteLayeredRule()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 624](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L624)




### <a name="method-updateOptionPsRouteSupplierRule"></a>updateOptionPsRouteSupplierRule

    mixed AdminMetaControllerCore::updateOptionPsRouteSupplierRule()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 629](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L629)




### <a name="method-updateOptionPsRouteManufacturerRule"></a>updateOptionPsRouteManufacturerRule

    mixed AdminMetaControllerCore::updateOptionPsRouteManufacturerRule()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 634](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L634)




### <a name="method-updateOptionPsRouteCmsRule"></a>updateOptionPsRouteCmsRule

    mixed AdminMetaControllerCore::updateOptionPsRouteCmsRule()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 639](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L639)




### <a name="method-updateOptionPsRouteCmsCategoryRule"></a>updateOptionPsRouteCmsCategoryRule

    mixed AdminMetaControllerCore::updateOptionPsRouteCmsCategoryRule()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 644](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L644)




### <a name="method-updateOptionDomain"></a>updateOptionDomain

    mixed AdminMetaControllerCore::updateOptionDomain(string $value)

Update shop domain (for mono shop)



* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L656)


#### Arguments
* $value **string**



### <a name="method-updateOptionDomainSsl"></a>updateOptionDomainSsl

    mixed AdminMetaControllerCore::updateOptionDomainSsl(string $value)

Update shop SSL domain (for mono shop)



* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 676](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L676)


#### Arguments
* $value **string**



### <a name="method-updateOptionUri"></a>updateOptionUri

    mixed AdminMetaControllerCore::updateOptionUri(string $value)

Update shop physical uri for mono shop)



* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 696](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L696)


#### Arguments
* $value **string**



### <a name="method-renderOptions"></a>renderOptions

    mixed AdminMetaControllerCore::renderOptions()

Function used to render the options for this controller



* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 707](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L707)




### <a name="method-addAllRouteFields"></a>addAllRouteFields

    mixed AdminMetaControllerCore::addAllRouteFields()

Add all custom route fields to the options form



* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 735](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L735)




### <a name="method-checkConfiguration"></a>checkConfiguration

    boolean AdminMetaControllerCore::checkConfiguration(string $file)

Check if a file is writable



* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L753)


#### Arguments
* $file **string**



### <a name="method-getRobotsContent"></a>getRobotsContent

    mixed AdminMetaControllerCore::getRobotsContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminMetaController.php line 761](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminMetaController.php#L761)



