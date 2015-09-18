CartControllerCore
===============






* Class name: CartControllerCore
* Namespace: 
* Parent class: FrontController





Properties
----------


### $php_self

    public mixed $php_self = 'cart'





* Visibility: **public**


### $id_product

    protected mixed $id_product





* Visibility: **protected**


### $id_product_attribute

    protected mixed $id_product_attribute





* Visibility: **protected**


### $id_address_delivery

    protected mixed $id_address_delivery





* Visibility: **protected**


### $customization_id

    protected mixed $customization_id





* Visibility: **protected**


### $qty

    protected mixed $qty





* Visibility: **protected**


### $ssl

    public mixed $ssl = true





* Visibility: **public**


### $ajax_refresh

    protected mixed $ajax_refresh = false





* Visibility: **protected**


Methods
-------


### canonicalRedirection

    mixed CartControllerCore::canonicalRedirection(string $canonicalURL)

This is not a public page, so the canonical redirection is disabled



* Visibility: **public**


#### Arguments
* $canonicalURL **string**



### init

    mixed CartControllerCore::init()

Initialize cart controller



* Visibility: **public**




### postProcess

    mixed CartControllerCore::postProcess()





* Visibility: **public**




### processDeleteProductInCart

    mixed CartControllerCore::processDeleteProductInCart()

This process delete a product from the cart



* Visibility: **protected**




### processChangeProductAddressDelivery

    mixed CartControllerCore::processChangeProductAddressDelivery()





* Visibility: **protected**




### processAllowSeperatedPackage

    mixed CartControllerCore::processAllowSeperatedPackage()





* Visibility: **protected**




### processDuplicateProduct

    mixed CartControllerCore::processDuplicateProduct()





* Visibility: **protected**




### processChangeProductInCart

    mixed CartControllerCore::processChangeProductInCart()

This process add or update a product in the cart



* Visibility: **protected**




### processRemoveDiscounts

    mixed CartControllerCore::processRemoveDiscounts()

Remove discounts on cart



* Visibility: **protected**




### initContent

    mixed CartControllerCore::initContent()





* Visibility: **public**




### displayAjax

    mixed CartControllerCore::displayAjax()

Display ajax content (this function is called instead of classic display, in ajax mode)



* Visibility: **public**



