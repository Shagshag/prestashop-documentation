StoresControllerCore
===============






* Class name: StoresControllerCore
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in [controllers/front/StoresController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StoresController.php#L27)





Properties
----------

* [$php_self](#property-$php_self)

Methods
-------
* [init](#method-init)
* [processStoreAddress](#method-processStoreAddress)
* [assignStoresSimplified](#method-assignStoresSimplified)
* [renderStoreWorkingHours](#method-renderStoreWorkingHours)
* [getStores](#method-getStores)
* [assignStores](#method-assignStores)
* [displayAjax](#method-displayAjax)
* [initContent](#method-initContent)
* [setMedia](#method-setMedia)




Properties
----------


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'stores'





* Visibility: **public**
* This property is defined in [controllers/front/StoresController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StoresController.php#L29)


Methods
-------


### <a name="method-init"></a>init

    mixed StoresControllerCore::init()

Initialize stores controller



* Visibility: **public**
* This method is defined in [controllers/front/StoresController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StoresController.php#L35)




### <a name="method-processStoreAddress"></a>processStoreAddress

    string StoresControllerCore::processStoreAddress(array $store)

Get formatted string address



* Visibility: **protected**
* This method is defined in [controllers/front/StoresController.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StoresController.php#L52)


#### Arguments
* $store **array**



### <a name="method-assignStoresSimplified"></a>assignStoresSimplified

    mixed StoresControllerCore::assignStoresSimplified()

Assign template vars for simplified stores



* Visibility: **protected**
* This method is defined in [controllers/front/StoresController.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StoresController.php#L89)




### <a name="method-renderStoreWorkingHours"></a>renderStoreWorkingHours

    mixed StoresControllerCore::renderStoreWorkingHours($store)





* Visibility: **public**
* This method is defined in [controllers/front/StoresController.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StoresController.php#L124)


#### Arguments
* $store **mixed**



### <a name="method-getStores"></a>getStores

    mixed StoresControllerCore::getStores()





* Visibility: **public**
* This method is defined in [controllers/front/StoresController.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StoresController.php#L162)




### <a name="method-assignStores"></a>assignStores

    mixed StoresControllerCore::assignStores()

Assign template vars for classical stores



* Visibility: **protected**
* This method is defined in [controllers/front/StoresController.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StoresController.php#L209)




### <a name="method-displayAjax"></a>displayAjax

    mixed StoresControllerCore::displayAjax()

Display the Xml for showing the nodes in the google map



* Visibility: **protected**
* This method is defined in [controllers/front/StoresController.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StoresController.php#L228)




### <a name="method-initContent"></a>initContent

    mixed StoresControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* This method is defined in [controllers/front/StoresController.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StoresController.php#L261)




### <a name="method-setMedia"></a>setMedia

    mixed StoresControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/front/StoresController.php line 282](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/StoresController.php#L282)



