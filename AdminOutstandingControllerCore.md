AdminOutstandingControllerCore
===============






* Class name: AdminOutstandingControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminOutstandingController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOutstandingController.php#L30)





Properties
----------

* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [initToolbar](#method-initToolbar)
* [printPDFIcons](#method-printPDFIcons)
* [printOutstandingCalculation](#method-printOutstandingCalculation)
* [renderView](#method-renderView)




Properties
----------


### <a name="property-$object"></a>$object

    public \OrderInvoice $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminOutstandingController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOutstandingController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminOutstandingControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOutstandingController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOutstandingController.php#L32)




### <a name="method-initToolbar"></a>initToolbar

    boolean AdminOutstandingControllerCore::initToolbar()

Toolbar initialisation



* Visibility: **public**
* This method is defined in [controllers/admin/AdminOutstandingController.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOutstandingController.php#L119)




### <a name="method-printPDFIcons"></a>printPDFIcons

    string AdminOutstandingControllerCore::printPDFIcons($id_invoice, $tr)

Column callback for print PDF incon



* Visibility: **public**
* This method is defined in [controllers/admin/AdminOutstandingController.php line 130](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOutstandingController.php#L130)


#### Arguments
* $id_invoice **mixed** - &lt;p&gt;integer Invoice ID&lt;/p&gt;
* $tr **mixed** - &lt;p&gt;array Row data&lt;/p&gt;



### <a name="method-printOutstandingCalculation"></a>printOutstandingCalculation

    mixed AdminOutstandingControllerCore::printOutstandingCalculation($id_invoice, $tr)





* Visibility: **public**
* This method is defined in [controllers/admin/AdminOutstandingController.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOutstandingController.php#L139)


#### Arguments
* $id_invoice **mixed**
* $tr **mixed**



### <a name="method-renderView"></a>renderView

    mixed AdminOutstandingControllerCore::renderView()

View render



* Visibility: **public**
* This method is defined in [controllers/admin/AdminOutstandingController.php line 161](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminOutstandingController.php#L161)



