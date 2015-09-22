ManufacturerControllerCore
===============






* Class name: ManufacturerControllerCore
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in [controllers/front/ManufacturerController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ManufacturerController.php#L27)





Properties
----------

* [$php_self](#property-$php_self)
* [$manufacturer](#property-$manufacturer)

Methods
-------
* [setMedia](#method-setMedia)
* [canonicalRedirection](#method-canonicalRedirection)
* [init](#method-init)
* [initContent](#method-initContent)
* [assignOne](#method-assignOne)
* [assignAll](#method-assignAll)
* [getManufacturer](#method-getManufacturer)




Properties
----------


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'manufacturer'





* Visibility: **public**
* This property is defined in [controllers/front/ManufacturerController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ManufacturerController.php#L29)


### <a name="property-$manufacturer"></a>$manufacturer

    protected \Manufacturer $manufacturer





* Visibility: **protected**
* This property is defined in [controllers/front/ManufacturerController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ManufacturerController.php#L32)


Methods
-------


### <a name="method-setMedia"></a>setMedia

    mixed ManufacturerControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/front/ManufacturerController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ManufacturerController.php#L34)




### <a name="method-canonicalRedirection"></a>canonicalRedirection

    mixed ManufacturerControllerCore::canonicalRedirection($canonicalURL)





* Visibility: **public**
* This method is defined in [controllers/front/ManufacturerController.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ManufacturerController.php#L40)


#### Arguments
* $canonicalURL **mixed**



### <a name="method-init"></a>init

    mixed ManufacturerControllerCore::init()

Initialize manufaturer controller



* Visibility: **public**
* This method is defined in [controllers/front/ManufacturerController.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ManufacturerController.php#L54)




### <a name="method-initContent"></a>initContent

    mixed ManufacturerControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* This method is defined in [controllers/front/ManufacturerController.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ManufacturerController.php#L74)




### <a name="method-assignOne"></a>assignOne

    mixed ManufacturerControllerCore::assignOne()

Assign template vars if displaying one manufacturer



* Visibility: **protected**
* This method is defined in [controllers/front/ManufacturerController.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ManufacturerController.php#L91)




### <a name="method-assignAll"></a>assignAll

    mixed ManufacturerControllerCore::assignAll()

Assign template vars if displaying the manufacturer list



* Visibility: **protected**
* This method is defined in [controllers/front/ManufacturerController.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ManufacturerController.php#L113)




### <a name="method-getManufacturer"></a>getManufacturer

    mixed ManufacturerControllerCore::getManufacturer()

Get instance of current manufacturer



* Visibility: **public**
* This method is defined in [controllers/front/ManufacturerController.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ManufacturerController.php#L142)



