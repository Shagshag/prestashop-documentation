ProductControllerCore
===============






* Class name: ProductControllerCore
* Namespace: 
* Parent class: FrontController





Properties
----------


### $php_self

    public mixed $php_self = 'product'





* Visibility: **public**


### $product

    protected \Product $product





* Visibility: **protected**


### $category

    protected \Category $category





* Visibility: **protected**


Methods
-------


### setMedia

    mixed ProductControllerCore::setMedia()





* Visibility: **public**




### canonicalRedirection

    mixed ProductControllerCore::canonicalRedirection($canonical_url)





* Visibility: **public**


#### Arguments
* $canonical_url **mixed**



### init

    mixed ProductControllerCore::init()

Initialize product controller



* Visibility: **public**




### initContent

    mixed ProductControllerCore::initContent()

Assign template vars related to page content



* Visibility: **public**




### assignPriceAndTax

    mixed ProductControllerCore::assignPriceAndTax()

Assign price and tax to the template



* Visibility: **protected**




### assignImages

    mixed ProductControllerCore::assignImages()

Assign template vars related to images



* Visibility: **protected**




### assignAttributesGroups

    mixed ProductControllerCore::assignAttributesGroups()

Assign template vars related to attribute groups and colors



* Visibility: **protected**




### assignAttributesCombinations

    mixed ProductControllerCore::assignAttributesCombinations()

Get and assign attributes combinations informations



* Visibility: **protected**




### assignCategory

    mixed ProductControllerCore::assignCategory()

Assign template vars related to category



* Visibility: **protected**




### transformDescriptionWithImg

    mixed ProductControllerCore::transformDescriptionWithImg($desc)





* Visibility: **protected**


#### Arguments
* $desc **mixed**



### pictureUpload

    mixed ProductControllerCore::pictureUpload()





* Visibility: **protected**




### textRecord

    mixed ProductControllerCore::textRecord()





* Visibility: **protected**




### formTargetFormat

    mixed ProductControllerCore::formTargetFormat()





* Visibility: **protected**




### formatQuantityDiscounts

    mixed ProductControllerCore::formatQuantityDiscounts($specific_prices, $price, $tax_rate, $ecotax_amount)





* Visibility: **protected**


#### Arguments
* $specific_prices **mixed**
* $price **mixed**
* $tax_rate **mixed**
* $ecotax_amount **mixed**



### getProduct

    mixed ProductControllerCore::getProduct()





* Visibility: **public**




### getCategory

    mixed ProductControllerCore::getCategory()





* Visibility: **public**



