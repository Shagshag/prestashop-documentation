AdminRequestSqlControllerCore
===============






* Class name: AdminRequestSqlControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $encoding_file

    public array $encoding_file = array(array('value' => 1, 'name' => 'utf-8'), array('value' => 2, 'name' => 'iso-8859-1'))





* Visibility: **public**
* This property is **static**.


### $object

    public \RequestSql $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminRequestSqlControllerCore::__construct()





* Visibility: **public**




### renderOptions

    mixed AdminRequestSqlControllerCore::renderOptions()





* Visibility: **public**




### initToolbar

    mixed AdminRequestSqlControllerCore::initToolbar()





* Visibility: **public**




### renderList

    mixed AdminRequestSqlControllerCore::renderList()





* Visibility: **public**




### renderForm

    mixed AdminRequestSqlControllerCore::renderForm()





* Visibility: **public**




### postProcess

    mixed AdminRequestSqlControllerCore::postProcess()





* Visibility: **public**




### ajaxProcess

    mixed AdminRequestSqlControllerCore::ajaxProcess()

method call when ajax request is made with the details row action



* Visibility: **public**




### renderView

    mixed AdminRequestSqlControllerCore::renderView()





* Visibility: **public**




### _childValidation

    mixed AdminRequestSqlControllerCore::_childValidation()





* Visibility: **public**




### displayExportLink

    string AdminRequestSqlControllerCore::displayExportLink($token, integer $id)

Display export action link



* Visibility: **public**


#### Arguments
* $token **mixed**
* $id **integer**



### initProcess

    mixed AdminRequestSqlControllerCore::initProcess()





* Visibility: **public**




### initContent

    mixed AdminRequestSqlControllerCore::initContent()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminRequestSqlControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### generateExport

    mixed AdminRequestSqlControllerCore::generateExport()

Genrating a export file



* Visibility: **public**




### displayError

    mixed AdminRequestSqlControllerCore::displayError($e)

Display all errors



* Visibility: **public**


#### Arguments
* $e **mixed** - &lt;p&gt;: array of errors&lt;/p&gt;


