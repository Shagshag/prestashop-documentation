AdminRequestSqlControllerCore
===============






* Class name: AdminRequestSqlControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminRequestSqlController.php line 30





Properties
----------


### $encoding_file

    public array $encoding_file = array(array('value' => 1, 'name' => 'utf-8'), array('value' => 2, 'name' => 'iso-8859-1'))





* Visibility: **public**
* This property is **static**.
* This property is defined in controllers\admin\AdminRequestSqlController.php line 35


### $object

    public \RequestSql $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminRequestSqlController.php line 30


Methods
-------


### __construct

    mixed AdminRequestSqlControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 40




### renderOptions

    mixed AdminRequestSqlControllerCore::renderOptions()





* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 84




### initToolbar

    mixed AdminRequestSqlControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 95




### renderList

    mixed AdminRequestSqlControllerCore::renderList()





* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 111




### renderForm

    mixed AdminRequestSqlControllerCore::renderForm()





* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 135




### postProcess

    mixed AdminRequestSqlControllerCore::postProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 171




### ajaxProcess

    mixed AdminRequestSqlControllerCore::ajaxProcess()

method call when ajax request is made with the details row action



* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 185




### renderView

    mixed AdminRequestSqlControllerCore::renderView()





* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 204




### _childValidation

    mixed AdminRequestSqlControllerCore::_childValidation()





* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 235




### displayExportLink

    string AdminRequestSqlControllerCore::displayExportLink($token, integer $id)

Display export action link



* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 258


#### Arguments
* $token **mixed**
* $id **integer**



### initProcess

    mixed AdminRequestSqlControllerCore::initProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 270




### initContent

    mixed AdminRequestSqlControllerCore::initContent()





* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 279




### initPageHeaderToolbar

    mixed AdminRequestSqlControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 313




### generateExport

    mixed AdminRequestSqlControllerCore::generateExport()

Genrating a export file



* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 329




### displayError

    mixed AdminRequestSqlControllerCore::displayError($e)

Display all errors



* Visibility: **public**
* This method is defined in controllers\admin\AdminRequestSqlController.php line 381


#### Arguments
* $e **mixed** - &lt;p&gt;: array of errors&lt;/p&gt;


