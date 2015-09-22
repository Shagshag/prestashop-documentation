AdminBackupControllerCore
===============






* Class name: AdminBackupControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminBackupController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L30)





Properties
----------

* [$sort_by](#property-$sort_by)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [initViewDownload](#method-initViewDownload)
* [initToolbar](#method-initToolbar)
* [initContent](#method-initContent)
* [loadObject](#method-loadObject)
* [postProcess](#method-postProcess)
* [getList](#method-getList)
* [intSort](#method-intSort)
* [strSort](#method-strSort)




Properties
----------


### <a name="property-$sort_by"></a>$sort_by

    protected string $sort_by = 'date'





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminBackupController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L33)


### <a name="property-$object"></a>$object

    public \PrestaShopBackup $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminBackupController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminBackupControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminBackupController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L35)




### <a name="method-renderList"></a>renderList

    mixed AdminBackupControllerCore::renderList()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminBackupController.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L82)




### <a name="method-renderView"></a>renderView

    mixed AdminBackupControllerCore::renderView()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminBackupController.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L90)




### <a name="method-initViewDownload"></a>initViewDownload

    mixed AdminBackupControllerCore::initViewDownload()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminBackupController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L106)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminBackupControllerCore::initToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminBackupController.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L113)




### <a name="method-initContent"></a>initContent

    mixed AdminBackupControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminBackupController.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L133)




### <a name="method-loadObject"></a>loadObject

    object AdminBackupControllerCore::loadObject(boolean $opt)

Load class object using identifier in $_GET (if possible)
otherwise return an empty object
This method overrides the one in AdminTab because AdminTab assumes the id is a UnsignedInt
"Backups" Directory in admin directory must be writeable (CHMOD 777)



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminBackupController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L150)


#### Arguments
* $opt **boolean** - &lt;p&gt;Return an empty object if load fail&lt;/p&gt;



### <a name="method-postProcess"></a>postProcess

    mixed AdminBackupControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminBackupController.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L162)




### <a name="method-getList"></a>getList

    mixed AdminBackupControllerCore::getList($id_lang, $order_by, $order_way, $start, $limit, $id_lang_shop)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminBackupController.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L191)


#### Arguments
* $id_lang **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $start **mixed**
* $limit **mixed**
* $id_lang_shop **mixed**



### <a name="method-intSort"></a>intSort

    mixed AdminBackupControllerCore::intSort($a, $b)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminBackupController.php line 301](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L301)


#### Arguments
* $a **mixed**
* $b **mixed**



### <a name="method-strSort"></a>strSort

    mixed AdminBackupControllerCore::strSort($a, $b)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminBackupController.php line 307](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminBackupController.php#L307)


#### Arguments
* $a **mixed**
* $b **mixed**


