Class CartControllerCore
=====================





* Class name: CartControllerCore
* Parent class: [FrontController](class.FrontControllerCore)
* Source: [controllers/front/CartController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L27)



Properties
----------

* [$ajax_refresh](#property-$ajax_refresh)
* [$customization_id](#property-$customization_id)
* [$id_address_delivery](#property-$id_address_delivery)
* [$id_product](#property-$id_product)
* [$id_product_attribute](#property-$id_product_attribute)
* [$php_self](#property-$php_self)
* [$qty](#property-$qty)
* [$ssl](#property-$ssl)

Methods
-------
* [canonicalRedirection](#method-canonicalRedirection)
* [displayAjax](#method-displayAjax)
* [init](#method-init)
* [initContent](#method-initContent)
* [postProcess](#method-postProcess)
* [processAllowSeperatedPackage](#method-processAllowSeperatedPackage)
* [processChangeProductAddressDelivery](#method-processChangeProductAddressDelivery)
* [processChangeProductInCart](#method-processChangeProductInCart)
* [processDeleteProductInCart](#method-processDeleteProductInCart)
* [processDuplicateProduct](#method-processDuplicateProduct)
* [processRemoveDiscounts](#method-processRemoveDiscounts)




Properties
----------


### <a name="property-$ajax_refresh"></a>$ajax_refresh

    protected mixed $ajax_refresh = false





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L38)


### <a name="property-$customization_id"></a>$customization_id

    protected mixed $customization_id





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L34)


### <a name="property-$id_address_delivery"></a>$id_address_delivery

    protected mixed $id_address_delivery





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L33)


### <a name="property-$id_product"></a>$id_product

    protected mixed $id_product





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L31)


### <a name="property-$id_product_attribute"></a>$id_product_attribute

    protected mixed $id_product_attribute





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L32)


### <a name="property-$php_self"></a>$php_self

    public mixed $php_self = 'cart'





* Visibility: **public**
* Source: [controllers/front/CartController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L29)


### <a name="property-$qty"></a>$qty

    protected mixed $qty





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L35)


### <a name="property-$ssl"></a>$ssl

    public mixed $ssl = true





* Visibility: **public**
* Source: [controllers/front/CartController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L36)


Methods
-------


### <a name="method-canonicalRedirection"></a>canonicalRedirection

    mixed CartControllerCore::canonicalRedirection(string $canonicalURL)

This is not a public page, so the canonical redirection is disabled



* Visibility: **public**
* Source: [controllers/front/CartController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L45)


#### Arguments
* $canonicalURL **string**



### <a name="method-displayAjax"></a>displayAjax

    mixed CartControllerCore::displayAjax()

Display ajax content (this function is called instead of classic display, in ajax mode)



* Visibility: **public**
* Source: [controllers/front/CartController.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L351)




### <a name="method-init"></a>init

    mixed CartControllerCore::init()

Initialize cart controller



* Visibility: **public**
* Source: [controllers/front/CartController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L53)




### <a name="method-initContent"></a>initContent

    mixed CartControllerCore::initContent()





* Visibility: **public**
* Source: [controllers/front/CartController.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L340)




### <a name="method-postProcess"></a>postProcess

    mixed CartControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/front/CartController.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L68)




### <a name="method-processAllowSeperatedPackage"></a>processAllowSeperatedPackage

    mixed CartControllerCore::processAllowSeperatedPackage()





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L180)




### <a name="method-processChangeProductAddressDelivery"></a>processChangeProductAddressDelivery

    mixed CartControllerCore::processChangeProductAddressDelivery()





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L157)




### <a name="method-processChangeProductInCart"></a>processChangeProductInCart

    mixed CartControllerCore::processChangeProductInCart()

This process add or update a product in the cart



* Visibility: **protected**
* Source: [controllers/front/CartController.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L216)




### <a name="method-processDeleteProductInCart"></a>processDeleteProductInCart

    mixed CartControllerCore::processDeleteProductInCart()

This process delete a product from the cart



* Visibility: **protected**
* Source: [controllers/front/CartController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L108)




### <a name="method-processDuplicateProduct"></a>processDuplicateProduct

    mixed CartControllerCore::processDuplicateProduct()





* Visibility: **protected**
* Source: [controllers/front/CartController.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L195)




### <a name="method-processRemoveDiscounts"></a>processRemoveDiscounts

    mixed CartControllerCore::processRemoveDiscounts()

Remove discounts on cart



* Visibility: **protected**
* Source: [controllers/front/CartController.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#L331)



