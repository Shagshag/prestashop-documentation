AdminBackupControllerCore
===============






* Class name: AdminBackupControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminBackupController.php line 30





Properties
----------


### $sort_by

    protected string $sort_by = 'date'





* Visibility: **protected**
* This property is defined in controllers\admin\AdminBackupController.php line 33


### $object

    public \PrestaShopBackup $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminBackupController.php line 30


Methods
-------


### __construct

    mixed AdminBackupControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminBackupController.php line 35




### renderList

    mixed AdminBackupControllerCore::renderList()





* Visibility: **public**
* This method is defined in controllers\admin\AdminBackupController.php line 82




### renderView

    mixed AdminBackupControllerCore::renderView()





* Visibility: **public**
* This method is defined in controllers\admin\AdminBackupController.php line 90




### initViewDownload

    mixed AdminBackupControllerCore::initViewDownload()





* Visibility: **public**
* This method is defined in controllers\admin\AdminBackupController.php line 106




### initToolbar

    mixed AdminBackupControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminBackupController.php line 113




### initContent

    mixed AdminBackupControllerCore::initContent()





* Visibility: **public**
* This method is defined in controllers\admin\AdminBackupController.php line 133




### loadObject

    object AdminBackupControllerCore::loadObject(boolean $opt)

Load class object using identifier in $_GET (if possible)
otherwise return an empty object
This method overrides the one in AdminTab because AdminTab assumes the id is a UnsignedInt
"Backups" Directory in admin directory must be writeable (CHMOD 777)



* Visibility: **protected**
* This method is defined in controllers\admin\AdminBackupController.php line 150


#### Arguments
* $opt **boolean** - &lt;p&gt;Return an empty object if load fail&lt;/p&gt;



### postProcess

    mixed AdminBackupControllerCore::postProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminBackupController.php line 162




### getList

    mixed AdminBackupControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)





* Visibility: **public**
* This method is defined in controllers\admin\AdminBackupController.php line 191


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### intSort

    mixed AdminBackupControllerCore::intSort($a, $b)





* Visibility: **public**
* This method is defined in controllers\admin\AdminBackupController.php line 301


#### Arguments
* $a **mixed**
* $b **mixed**



### strSort

    mixed AdminBackupControllerCore::strSort($a, $b)





* Visibility: **public**
* This method is defined in controllers\admin\AdminBackupController.php line 307


#### Arguments
* $a **mixed**
* $b **mixed**


