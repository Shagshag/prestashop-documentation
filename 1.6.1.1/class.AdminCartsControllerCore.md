Class AdminCartsControllerCore
=====================





* Class name: AdminCartsControllerCore
* Parent class: [AdminController](class.AdminControllerCore)
* Source: [controllers/admin/AdminCartsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L30)



Properties
----------

* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [ajaxPreProcess](#method-ajaxPreProcess)
* [ajaxProcessAddVoucher](#method-ajaxProcessAddVoucher)
* [ajaxProcessDeleteProduct](#method-ajaxProcessDeleteProduct)
* [ajaxProcessDeleteVoucher](#method-ajaxProcessDeleteVoucher)
* [ajaxProcessDuplicateOrder](#method-ajaxProcessDuplicateOrder)
* [ajaxProcessUpdateAddress](#method-ajaxProcessUpdateAddress)
* [ajaxProcessUpdateAddresses](#method-ajaxProcessUpdateAddresses)
* [ajaxProcessUpdateCurrency](#method-ajaxProcessUpdateCurrency)
* [ajaxProcessUpdateCustomizationFields](#method-ajaxProcessUpdateCustomizationFields)
* [ajaxProcessUpdateDeliveryOption](#method-ajaxProcessUpdateDeliveryOption)
* [ajaxProcessUpdateLang](#method-ajaxProcessUpdateLang)
* [ajaxProcessUpdateOrderMessage](#method-ajaxProcessUpdateOrderMessage)
* [ajaxProcessUpdateProductPrice](#method-ajaxProcessUpdateProductPrice)
* [ajaxProcessUpdateQty](#method-ajaxProcessUpdateQty)
* [ajaxProcessupdateFreeShipping](#method-ajaxProcessupdateFreeShipping)
* [ajaxReturnVars](#method-ajaxReturnVars)
* [displayAjaxGetSummary](#method-displayAjaxGetSummary)
* [displayAjaxSearchCarts](#method-displayAjaxSearchCarts)
* [displayDeleteLink](#method-displayDeleteLink)
* [getCartSummary](#method-getCartSummary)
* [getDeliveryOptionList](#method-getDeliveryOptionList)
* [getOrderTotalUsingTaxCalculationMethod](#method-getOrderTotalUsingTaxCalculationMethod)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initToolbar](#method-initToolbar)
* [renderKpis](#method-renderKpis)
* [renderList](#method-renderList)
* [renderView](#method-renderView)
* [replaceZeroByShopName](#method-replaceZeroByShopName)




Properties
----------


### <a name="property-$object"></a>$object

    public \Cart $object





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminCartsControllerCore::__construct()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L32)




### <a name="method-ajaxPreProcess"></a>ajaxPreProcess

    mixed AdminCartsControllerCore::ajaxPreProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 296](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L296)




### <a name="method-ajaxProcessAddVoucher"></a>ajaxProcessAddVoucher

    mixed AdminCartsControllerCore::ajaxProcessAddVoucher()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 611](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L611)




### <a name="method-ajaxProcessDeleteProduct"></a>ajaxProcessDeleteProduct

    mixed AdminCartsControllerCore::ajaxProcessDeleteProduct()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 353](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L353)




### <a name="method-ajaxProcessDeleteVoucher"></a>ajaxProcessDeleteVoucher

    mixed AdminCartsControllerCore::ajaxProcessDeleteVoucher()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 572](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L572)




### <a name="method-ajaxProcessDuplicateOrder"></a>ajaxProcessDuplicateOrder

    mixed AdminCartsControllerCore::ajaxProcessDuplicateOrder()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L552)




### <a name="method-ajaxProcessUpdateAddress"></a>ajaxProcessUpdateAddress

    mixed AdminCartsControllerCore::ajaxProcessUpdateAddress()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 629](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L629)




### <a name="method-ajaxProcessUpdateAddresses"></a>ajaxProcessUpdateAddresses

    mixed AdminCartsControllerCore::ajaxProcessUpdateAddresses()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 636](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L636)




### <a name="method-ajaxProcessUpdateCurrency"></a>ajaxProcessUpdateCurrency

    mixed AdminCartsControllerCore::ajaxProcessUpdateCurrency()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 528](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L528)




### <a name="method-ajaxProcessUpdateCustomizationFields"></a>ajaxProcessUpdateCustomizationFields

    mixed AdminCartsControllerCore::ajaxProcessUpdateCustomizationFields()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 372](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L372)




### <a name="method-ajaxProcessUpdateDeliveryOption"></a>ajaxProcessUpdateDeliveryOption

    mixed AdminCartsControllerCore::ajaxProcessUpdateDeliveryOption()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 485](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L485)




### <a name="method-ajaxProcessUpdateLang"></a>ajaxProcessUpdateLang

    mixed AdminCartsControllerCore::ajaxProcessUpdateLang()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 540](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L540)




### <a name="method-ajaxProcessUpdateOrderMessage"></a>ajaxProcessUpdateOrderMessage

    mixed AdminCartsControllerCore::ajaxProcessUpdateOrderMessage()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 506](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L506)




### <a name="method-ajaxProcessUpdateProductPrice"></a>ajaxProcessUpdateProductPrice

    mixed AdminCartsControllerCore::ajaxProcessUpdateProductPrice()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 823](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L823)




### <a name="method-ajaxProcessUpdateQty"></a>ajaxProcessUpdateQty

    mixed AdminCartsControllerCore::ajaxProcessUpdateQty()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 433](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L433)




### <a name="method-ajaxProcessupdateFreeShipping"></a>ajaxProcessupdateFreeShipping

    mixed AdminCartsControllerCore::ajaxProcessupdateFreeShipping()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 581](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L581)




### <a name="method-ajaxReturnVars"></a>ajaxReturnVars

    mixed AdminCartsControllerCore::ajaxReturnVars()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 769](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L769)




### <a name="method-displayAjaxGetSummary"></a>displayAjaxGetSummary

    mixed AdminCartsControllerCore::displayAjaxGetSummary()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 818](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L818)




### <a name="method-displayAjaxSearchCarts"></a>displayAjaxSearchCarts

    mixed AdminCartsControllerCore::displayAjaxSearchCarts()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 735](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L735)




### <a name="method-displayDeleteLink"></a>displayDeleteLink

    mixed AdminCartsControllerCore::displayDeleteLink($token, $id, $name)





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 862](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L862)


#### Arguments
* $token **mixed**
* $id **mixed**
* $name **mixed**



### <a name="method-getCartSummary"></a>getCartSummary

    mixed AdminCartsControllerCore::getCartSummary()





* Visibility: **protected**
* Source: [controllers/admin/AdminCartsController.php line 656](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L656)




### <a name="method-getDeliveryOptionList"></a>getDeliveryOptionList

    mixed AdminCartsControllerCore::getDeliveryOptionList()





* Visibility: **protected**
* Source: [controllers/admin/AdminCartsController.php line 692](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L692)




### <a name="method-getOrderTotalUsingTaxCalculationMethod"></a>getOrderTotalUsingTaxCalculationMethod

    mixed AdminCartsControllerCore::getOrderTotalUsingTaxCalculationMethod($id_cart)





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminCartsController.php line 848](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L848)


#### Arguments
* $id_cart **mixed**



### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminCartsControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L118)




### <a name="method-initToolbar"></a>initToolbar

    mixed AdminCartsControllerCore::initToolbar()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 812](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L812)




### <a name="method-renderKpis"></a>renderKpis

    mixed AdminCartsControllerCore::renderKpis()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L131)




### <a name="method-renderList"></a>renderList

    mixed AdminCartsControllerCore::renderList()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 874](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L874)




### <a name="method-renderView"></a>renderView

    mixed AdminCartsControllerCore::renderView()





* Visibility: **public**
* Source: [controllers/admin/AdminCartsController.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L203)




### <a name="method-replaceZeroByShopName"></a>replaceZeroByShopName

    mixed AdminCartsControllerCore::replaceZeroByShopName($echo, $tr)





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminCartsController.php line 857](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminCartsController.php#L857)


#### Arguments
* $echo **mixed**
* $tr **mixed**


