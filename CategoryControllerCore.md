CategoryControllerCore
===============






* Class name: CategoryControllerCore
* Namespace: 
* Parent class: FrontController





Properties
----------


### $php_self

    public mixed $php_self = 'category'

string Internal controller name



* Visibility: **public**


### $category

    protected \Category $category





* Visibility: **protected**


### $customer_access

    public boolean $customer_access = true





* Visibility: **public**


### $nbProducts

    protected integer $nbProducts





* Visibility: **protected**


### $cat_products

    protected array $cat_products





* Visibility: **protected**


Methods
-------


### setMedia

    mixed CategoryControllerCore::setMedia()

Sets default medias for this controller



* Visibility: **public**




### canonicalRedirection

    mixed CategoryControllerCore::canonicalRedirection(string $canonical_url)

Redirects to canonical or "Not Found" URL



* Visibility: **public**


#### Arguments
* $canonical_url **string**



### init

    mixed CategoryControllerCore::init()

Initializes controller



* Visibility: **public**




### initContent

    mixed CategoryControllerCore::initContent()

Initializes page content variables



* Visibility: **public**




### assignScenes

    mixed CategoryControllerCore::assignScenes()

Assigns scenes template variables



* Visibility: **protected**




### assignSubcategories

    mixed CategoryControllerCore::assignSubcategories()

Assigns subcategory templates variables



* Visibility: **protected**




### assignProductList

    mixed CategoryControllerCore::assignProductList()

Assigns product list template variables



* Visibility: **public**




### getCategory

    \Category CategoryControllerCore::getCategory()

Returns an instance of the current category



* Visibility: **public**



