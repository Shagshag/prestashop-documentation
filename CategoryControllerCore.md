CategoryControllerCore
===============






* Class name: CategoryControllerCore
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in [controllers/front/CategoryController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#L27)





Properties
----------


### $php_self

    public mixed $php_self = 'category'

string Internal controller name



* Visibility: **public**
* This property is defined in [controllers/front/CategoryController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#30)


### $category

    protected \Category $category





* Visibility: **protected**
* This property is defined in [controllers/front/CategoryController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#33)


### $customer_access

    public boolean $customer_access = true





* Visibility: **public**
* This property is defined in [controllers/front/CategoryController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#36)


### $nbProducts

    protected integer $nbProducts





* Visibility: **protected**
* This property is defined in [controllers/front/CategoryController.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#39)


### $cat_products

    protected array $cat_products





* Visibility: **protected**
* This property is defined in [controllers/front/CategoryController.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#42)


Methods
-------


### setMedia

    mixed CategoryControllerCore::setMedia()

Sets default medias for this controller



* Visibility: **public**
* This method is defined in [controllers/front/CategoryController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#47)




### canonicalRedirection

    mixed CategoryControllerCore::canonicalRedirection(string $canonical_url)

Redirects to canonical or "Not Found" URL



* Visibility: **public**
* This method is defined in [controllers/front/CategoryController.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#74)


#### Arguments
* $canonical_url **string**



### init

    mixed CategoryControllerCore::init()

Initializes controller



* Visibility: **public**
* This method is defined in [controllers/front/CategoryController.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#96)




### initContent

    mixed CategoryControllerCore::initContent()

Initializes page content variables



* Visibility: **public**
* This method is defined in [controllers/front/CategoryController.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#127)




### assignScenes

    mixed CategoryControllerCore::assignScenes()

Assigns scenes template variables



* Visibility: **protected**
* This method is defined in [controllers/front/CategoryController.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#171)




### assignSubcategories

    mixed CategoryControllerCore::assignSubcategories()

Assigns subcategory templates variables



* Visibility: **protected**
* This method is defined in [controllers/front/CategoryController.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#197)




### assignProductList

    mixed CategoryControllerCore::assignProductList()

Assigns product list template variables



* Visibility: **public**
* This method is defined in [controllers/front/CategoryController.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#211)




### getCategory

    \Category CategoryControllerCore::getCategory()

Returns an instance of the current category



* Visibility: **public**
* This method is defined in [controllers/front/CategoryController.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/front/CategoryController.php#254)



