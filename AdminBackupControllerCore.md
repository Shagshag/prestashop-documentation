AdminBackupControllerCore
===============






* Class name: AdminBackupControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $sort_by

    protected string $sort_by = 'date'





* Visibility: **protected**


### $object

    public \PrestaShopBackup $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminBackupControllerCore::__construct()





* Visibility: **public**




### renderList

    mixed AdminBackupControllerCore::renderList()





* Visibility: **public**




### renderView

    mixed AdminBackupControllerCore::renderView()





* Visibility: **public**




### initViewDownload

    mixed AdminBackupControllerCore::initViewDownload()





* Visibility: **public**




### initToolbar

    mixed AdminBackupControllerCore::initToolbar()





* Visibility: **public**




### initContent

    mixed AdminBackupControllerCore::initContent()





* Visibility: **public**




### loadObject

    object AdminBackupControllerCore::loadObject(boolean $opt)

Load class object using identifier in $_GET (if possible)
otherwise return an empty object
This method overrides the one in AdminTab because AdminTab assumes the id is a UnsignedInt
"Backups" Directory in admin directory must be writeable (CHMOD 777)



* Visibility: **protected**


#### Arguments
* $opt **boolean** - &lt;p&gt;Return an empty object if load fail&lt;/p&gt;



### postProcess

    mixed AdminBackupControllerCore::postProcess()





* Visibility: **public**




### getList

    mixed AdminBackupControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)





* Visibility: **public**


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


#### Arguments
* $a **mixed**
* $b **mixed**



### strSort

    mixed AdminBackupControllerCore::strSort($a, $b)





* Visibility: **public**


#### Arguments
* $a **mixed**
* $b **mixed**


