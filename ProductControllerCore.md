ProductControllerCore
===============






* Class name: ProductControllerCore
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in [controllers/front/ProductController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#L27)





Properties
----------


### $php_self

    public mixed $php_self = 'product'





* Visibility: **public**
* This property is defined in [controllers/front/ProductController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#29)


### $product

    protected \Product $product





* Visibility: **protected**
* This property is defined in [controllers/front/ProductController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#32)


### $category

    protected \Category $category





* Visibility: **protected**
* This property is defined in [controllers/front/ProductController.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#35)


Methods
-------


### setMedia

    mixed ProductControllerCore::setMedia()





* Visibility: **public**
* This method is defined in [controllers/front/ProductController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#37)




### canonicalRedirection

    mixed ProductControllerCore::canonicalRedirection($canonical_url)





* Visibility: **public**
* This method is defined in [controllers/front/ProductController.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#66)


#### Arguments
* $canonical_url **mixed**



### init

    mixed ProductControllerCore::init()

Initialize product controller



* Visibility: **public**
* This method is defined in [controllers/front/ProductController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#80)




### initContent

    mixed ProductControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* This method is defined in [controllers/front/ProductController.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#170)




### assignPriceAndTax

    mixed ProductControllerCore::assignPriceAndTax()

Assign price and tax to the template



* Visibility: **protected**
* This method is defined in [controllers/front/ProductController.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#302)




### assignImages

    mixed ProductControllerCore::assignImages()

Assign template vars related to images



* Visibility: **protected**
* This method is defined in [controllers/front/ProductController.php line 367](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#367)




### assignAttributesGroups

    mixed ProductControllerCore::assignAttributesGroups()

Assign template vars related to attribute groups and colors



* Visibility: **protected**
* This method is defined in [controllers/front/ProductController.php line 416](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#416)




### assignAttributesCombinations

    mixed ProductControllerCore::assignAttributesCombinations()

Get and assign attributes combinations informations



* Visibility: **protected**
* This method is defined in [controllers/front/ProductController.php line 560](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#560)




### assignCategory

    mixed ProductControllerCore::assignCategory()

Assign template vars related to category



* Visibility: **protected**
* This method is defined in [controllers/front/ProductController.php line 582](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#582)




### transformDescriptionWithImg

    mixed ProductControllerCore::transformDescriptionWithImg($desc)





* Visibility: **protected**
* This method is defined in [controllers/front/ProductController.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#615)


#### Arguments
* $desc **mixed**



### pictureUpload

    mixed ProductControllerCore::pictureUpload()





* Visibility: **protected**
* This method is defined in [controllers/front/ProductController.php line 627](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#627)




### textRecord

    mixed ProductControllerCore::textRecord()





* Visibility: **protected**
* This method is defined in [controllers/front/ProductController.php line 670](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#670)




### formTargetFormat

    mixed ProductControllerCore::formTargetFormat()





* Visibility: **protected**
* This method is defined in [controllers/front/ProductController.php line 697](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#697)




### formatQuantityDiscounts

    mixed ProductControllerCore::formatQuantityDiscounts($specific_prices, $price, $tax_rate, $ecotax_amount)





* Visibility: **protected**
* This method is defined in [controllers/front/ProductController.php line 711](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#711)


#### Arguments
* $specific_prices **mixed**
* $price **mixed**
* $tax_rate **mixed**
* $ecotax_amount **mixed**



### getProduct

    mixed ProductControllerCore::getProduct()





* Visibility: **public**
* This method is defined in [controllers/front/ProductController.php line 745](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#745)




### getCategory

    mixed ProductControllerCore::getCategory()





* Visibility: **public**
* This method is defined in [controllers/front/ProductController.php line 750](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/ProductController.php#750)



