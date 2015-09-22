SupplierControllerCore
===============






* Class name: SupplierControllerCore
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in [controllers/front/SupplierController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/SupplierController.php#L27)





Properties
----------

* [$php_self](#property-$php_self)
* [$supplier](#property-$supplier)

Methods
-------
* [setMedia](#method-setMedia)
* [canonicalRedirection](#method-canonicalRedirection)
* [init](#method-init)
* [initContent](#method-initContent)
* [assignOne](#method-assignOne)
* [assignAll](#method-assignAll)
* [getSupplier](#method-getSupplier)




Properties
----------


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'supplier'





* Visibility: **public**
* This property is defined in [controllers/front/SupplierController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/SupplierController.php#L29)


### <a name="property-$supplier"></a>$supplier

    protected \Supplier $supplier





* Visibility: **protected**
* This property is defined in [controllers/front/SupplierController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/SupplierController.php#L32)


Methods
-------


### <a name="method-setMedia"></a>setMedia

    mixed SupplierControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/front/SupplierController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/SupplierController.php#L34)




### <a name="method-canonicalRedirection"></a>canonicalRedirection

    mixed SupplierControllerCore::canonicalRedirection($canonicalURL)





* Visibility: **public**
* This method is defined in [controllers/front/SupplierController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/SupplierController.php#L40)


#### Arguments
* $canonicalURL **mixed**



### <a name="method-init"></a>init

    mixed SupplierControllerCore::init()

Initialize supplier controller



* Visibility: **public**
* This method is defined in [controllers/front/SupplierController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/SupplierController.php#L54)




### <a name="method-initContent"></a>initContent

    mixed SupplierControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* This method is defined in [controllers/front/SupplierController.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/SupplierController.php#L75)




### <a name="method-assignOne"></a>assignOne

    mixed SupplierControllerCore::assignOne()

Assign template vars if displaying one supplier



* Visibility: **protected**
* This method is defined in [controllers/front/SupplierController.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/SupplierController.php#L92)




### <a name="method-assignAll"></a>assignAll

    mixed SupplierControllerCore::assignAll()

Assign template vars if displaying the supplier list



* Visibility: **protected**
* This method is defined in [controllers/front/SupplierController.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/SupplierController.php#L123)




### <a name="method-getSupplier"></a>getSupplier

    mixed SupplierControllerCore::getSupplier()

Get instance of current supplier



* Visibility: **public**
* This method is defined in [controllers/front/SupplierController.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/SupplierController.php#L150)



