CartControllerCore
===============






* Class name: CartControllerCore
* Namespace: 
* Parent class: [FrontController](FrontControllerCore)

* This class is defined in [controllers/front/CartController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#27)





Properties
----------


### $php_self

    public mixed $php_self = 'cart'





* Visibility: **public**
* This property is defined in [controllers/front/CartController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#29)


### $id_product

    protected mixed $id_product





* Visibility: **protected**
* This property is defined in [controllers/front/CartController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#31)


### $id_product_attribute

    protected mixed $id_product_attribute





* Visibility: **protected**
* This property is defined in [controllers/front/CartController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#32)


### $id_address_delivery

    protected mixed $id_address_delivery





* Visibility: **protected**
* This property is defined in [controllers/front/CartController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#33)


### $customization_id

    protected mixed $customization_id





* Visibility: **protected**
* This property is defined in [controllers/front/CartController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#34)


### $qty

    protected mixed $qty





* Visibility: **protected**
* This property is defined in [controllers/front/CartController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#35)


### $ssl

    public mixed $ssl = true





* Visibility: **public**
* This property is defined in [controllers/front/CartController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#36)


### $ajax_refresh

    protected mixed $ajax_refresh = false





* Visibility: **protected**
* This property is defined in [controllers/front/CartController.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#38)


Methods
-------


### canonicalRedirection

    mixed CartControllerCore::canonicalRedirection(string $canonicalURL)

This is not a public page, so the canonical redirection is disabled



* Visibility: **public**
* This method is defined in [controllers/front/CartController.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#45)


#### Arguments
* $canonicalURL **string**



### init

    mixed CartControllerCore::init()

Initialize cart controller



* Visibility: **public**
* This method is defined in [controllers/front/CartController.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#53)




### postProcess

    mixed CartControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/front/CartController.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#68)




### processDeleteProductInCart

    mixed CartControllerCore::processDeleteProductInCart()

This process delete a product from the cart



* Visibility: **protected**
* This method is defined in [controllers/front/CartController.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#108)




### processChangeProductAddressDelivery

    mixed CartControllerCore::processChangeProductAddressDelivery()





* Visibility: **protected**
* This method is defined in [controllers/front/CartController.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#157)




### processAllowSeperatedPackage

    mixed CartControllerCore::processAllowSeperatedPackage()





* Visibility: **protected**
* This method is defined in [controllers/front/CartController.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#180)




### processDuplicateProduct

    mixed CartControllerCore::processDuplicateProduct()





* Visibility: **protected**
* This method is defined in [controllers/front/CartController.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#195)




### processChangeProductInCart

    mixed CartControllerCore::processChangeProductInCart()

This process add or update a product in the cart



* Visibility: **protected**
* This method is defined in [controllers/front/CartController.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#216)




### processRemoveDiscounts

    mixed CartControllerCore::processRemoveDiscounts()

Remove discounts on cart



* Visibility: **protected**
* This method is defined in [controllers/front/CartController.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#331)




### initContent

    mixed CartControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/front/CartController.php line 340](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#340)




### displayAjax

    mixed CartControllerCore::displayAjax()

Display ajax content (this function is called instead of classic display, in ajax mode)



* Visibility: **public**
* This method is defined in [controllers/front/CartController.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CartController.php#351)



