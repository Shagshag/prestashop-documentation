ProductControllerCore
===============






* Class name: ProductControllerCore
* Namespace: 
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in controllers\front\ProductController.php line 27





Properties
----------


### $php_self

    public mixed $php_self = 'product'





* Visibility: **public**
* This property is defined in controllers\front\ProductController.php line 29


### $product

    protected \Product $product





* Visibility: **protected**
* This property is defined in controllers\front\ProductController.php line 32


### $category

    protected \Category $category





* Visibility: **protected**
* This property is defined in controllers\front\ProductController.php line 35


Methods
-------


### setMedia

    mixed ProductControllerCore::setMedia()





* Visibility: **public**
* This method is defined in controllers\front\ProductController.php line 37




### canonicalRedirection

    mixed ProductControllerCore::canonicalRedirection($canonical_url)





* Visibility: **public**
* This method is defined in controllers\front\ProductController.php line 66


#### Arguments
* $canonical_url **mixed**



### init

    mixed ProductControllerCore::init()

Initialize product controller



* Visibility: **public**
* This method is defined in controllers\front\ProductController.php line 80




### initContent

    mixed ProductControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**
* This method is defined in controllers\front\ProductController.php line 170




### assignPriceAndTax

    mixed ProductControllerCore::assignPriceAndTax()

Assign price and tax to the template



* Visibility: **protected**
* This method is defined in controllers\front\ProductController.php line 302




### assignImages

    mixed ProductControllerCore::assignImages()

Assign template vars related to images



* Visibility: **protected**
* This method is defined in controllers\front\ProductController.php line 367




### assignAttributesGroups

    mixed ProductControllerCore::assignAttributesGroups()

Assign template vars related to attribute groups and colors



* Visibility: **protected**
* This method is defined in controllers\front\ProductController.php line 416




### assignAttributesCombinations

    mixed ProductControllerCore::assignAttributesCombinations()

Get and assign attributes combinations informations



* Visibility: **protected**
* This method is defined in controllers\front\ProductController.php line 560




### assignCategory

    mixed ProductControllerCore::assignCategory()

Assign template vars related to category



* Visibility: **protected**
* This method is defined in controllers\front\ProductController.php line 582




### transformDescriptionWithImg

    mixed ProductControllerCore::transformDescriptionWithImg($desc)





* Visibility: **protected**
* This method is defined in controllers\front\ProductController.php line 615


#### Arguments
* $desc **mixed**



### pictureUpload

    mixed ProductControllerCore::pictureUpload()





* Visibility: **protected**
* This method is defined in controllers\front\ProductController.php line 627




### textRecord

    mixed ProductControllerCore::textRecord()





* Visibility: **protected**
* This method is defined in controllers\front\ProductController.php line 670




### formTargetFormat

    mixed ProductControllerCore::formTargetFormat()





* Visibility: **protected**
* This method is defined in controllers\front\ProductController.php line 697




### formatQuantityDiscounts

    mixed ProductControllerCore::formatQuantityDiscounts($specific_prices, $price, $tax_rate, $ecotax_amount)





* Visibility: **protected**
* This method is defined in controllers\front\ProductController.php line 711


#### Arguments
* $specific_prices **mixed**
* $price **mixed**
* $tax_rate **mixed**
* $ecotax_amount **mixed**



### getProduct

    mixed ProductControllerCore::getProduct()





* Visibility: **public**
* This method is defined in controllers\front\ProductController.php line 745




### getCategory

    mixed ProductControllerCore::getCategory()





* Visibility: **public**
* This method is defined in controllers\front\ProductController.php line 750



