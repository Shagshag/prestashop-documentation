AdminRequestSqlControllerCore
===============






* Class name: AdminRequestSqlControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminRequestSqlController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L30)





Properties
----------

* [$encoding_file](#property-$encoding_file)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [renderOptions](#method-renderOptions)
* [initToolbar](#method-initToolbar)
* [renderList](#method-renderList)
* [renderForm](#method-renderForm)
* [postProcess](#method-postProcess)
* [ajaxProcess](#method-ajaxProcess)
* [renderView](#method-renderView)
* [_childValidation](#method-_childValidation)
* [displayExportLink](#method-displayExportLink)
* [initProcess](#method-initProcess)
* [initContent](#method-initContent)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [generateExport](#method-generateExport)
* [displayError](#method-displayError)




Properties
----------


### <a name="property-$encoding_file"></a>$encoding_file

    public array $encoding_file = array(array('value' => 1, 'name' => 'utf-8'), array('value' => 2, 'name' => 'iso-8859-1'))





* Visibility: **public**
* This property is **static**.
* This property is defined in [controllers/admin/AdminRequestSqlController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L35)


### <a name="property-$object"></a>$object

    public \RequestSql $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminRequestSqlController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminRequestSqlControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L40)




### <a name="method-renderOptions"></a>renderOptions

    mixed AdminRequestSqlControllerCore::renderOptions()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L84)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminRequestSqlControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L95)




### <a name="method-renderList"></a>renderList

    mixed AdminRequestSqlControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 111](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L111)




### <a name="method-renderForm"></a>renderForm

    mixed AdminRequestSqlControllerCore::renderForm()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L135)




### <a name="method-postProcess"></a>postProcess

    mixed AdminRequestSqlControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L171)




### <a name="method-ajaxProcess"></a>ajaxProcess

    mixed AdminRequestSqlControllerCore::ajaxProcess()

method call when ajax request is made with the details row action



* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L185)




### <a name="method-renderView"></a>renderView

    mixed AdminRequestSqlControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L204)




### <a name="method-_childValidation"></a>_childValidation

    mixed AdminRequestSqlControllerCore::_childValidation()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L235)




### <a name="method-displayExportLink"></a>displayExportLink

    string AdminRequestSqlControllerCore::displayExportLink($token, integer $id)

Display export action link



* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L258)


#### Arguments
* $token **mixed**
* $id **integer**



### <a name="method-initProcess"></a>initProcess

    mixed AdminRequestSqlControllerCore::initProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L270)




### <a name="method-initContent"></a>initContent

    mixed AdminRequestSqlControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 279](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L279)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminRequestSqlControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L313)




### <a name="method-generateExport"></a>generateExport

    mixed AdminRequestSqlControllerCore::generateExport()

Genrating a export file



* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 329](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L329)




### <a name="method-displayError"></a>displayError

    mixed AdminRequestSqlControllerCore::displayError($e)

Display all errors



* Visibility: **public**
* This method is defined in [controllers/admin/AdminRequestSqlController.php line 381](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminRequestSqlController.php#L381)


#### Arguments
* $e **mixed** - &lt;p&gt;: array of errors&lt;/p&gt;


