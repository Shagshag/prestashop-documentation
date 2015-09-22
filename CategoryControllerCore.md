CategoryControllerCore
===============






* Class name: CategoryControllerCore
* Namespace: 
* Parent class: [FrontController](FrontControllerCore)
* This class is defined in controllers\front\CategoryController.php line 27





Properties
----------


### $php_self

    public mixed $php_self = 'category'

string Internal controller name



* Visibility: **public**
* This property is defined in controllers\front\CategoryController.php line 30


### $category

    protected \Category $category





* Visibility: **protected**
* This property is defined in controllers\front\CategoryController.php line 33


### $customer_access

    public boolean $customer_access = true





* Visibility: **public**
* This property is defined in controllers\front\CategoryController.php line 36


### $nbProducts

    protected integer $nbProducts





* Visibility: **protected**
* This property is defined in controllers\front\CategoryController.php line 39


### $cat_products

    protected array $cat_products





* Visibility: **protected**
* This property is defined in controllers\front\CategoryController.php line 42


Methods
-------


### setMedia

    mixed CategoryControllerCore::setMedia()

Sets default medias for this controller



* Visibility: **public**
* This method is defined in controllers\front\CategoryController.php line 47




### canonicalRedirection

    mixed CategoryControllerCore::canonicalRedirection(string $canonical_url)

Redirects to canonical or "Not Found" URL



* Visibility: **public**
* This method is defined in controllers\front\CategoryController.php line 74


#### Arguments
* $canonical_url **string**



### init

    mixed CategoryControllerCore::init()

Initializes controller



* Visibility: **public**
* This method is defined in controllers\front\CategoryController.php line 96




### initContent

    mixed CategoryControllerCore::initContent()

Initializes page content variables



* Visibility: **public**
* This method is defined in controllers\front\CategoryController.php line 127




### assignScenes

    mixed CategoryControllerCore::assignScenes()

Assigns scenes template variables



* Visibility: **protected**
* This method is defined in controllers\front\CategoryController.php line 171




### assignSubcategories

    mixed CategoryControllerCore::assignSubcategories()

Assigns subcategory templates variables



* Visibility: **protected**
* This method is defined in controllers\front\CategoryController.php line 197




### assignProductList

    mixed CategoryControllerCore::assignProductList()

Assigns product list template variables



* Visibility: **public**
* This method is defined in controllers\front\CategoryController.php line 211




### getCategory

    \Category CategoryControllerCore::getCategory()

Returns an instance of the current category



* Visibility: **public**
* This method is defined in controllers\front\CategoryController.php line 254



