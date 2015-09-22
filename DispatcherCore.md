DispatcherCore
===============






* Class name: DispatcherCore
* Namespace: 
* This class is defined in classes\Dispatcher.php line 30



Constants
----------


### FC_FRONT

    const FC_FRONT = 1



* This constant is defined in classes\Dispatcher.php line 35


### FC_ADMIN

    const FC_ADMIN = 2



* This constant is defined in classes\Dispatcher.php line 36


### FC_MODULE

    const FC_MODULE = 3



* This constant is defined in classes\Dispatcher.php line 37


Properties
----------


### $instance

    public \Dispatcher $instance = null





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Dispatcher.php line 42


### $default_routes

    public array $default_routes = array('category_rule' => array('controller' => 'category', 'rule' => '{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_category'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9\pL\pS-]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'))), 'supplier_rule' => array('controller' => 'supplier', 'rule' => '{id}__{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_supplier'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9\pL\pS-]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'))), 'manufacturer_rule' => array('controller' => 'manufacturer', 'rule' => '{id}_{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_manufacturer'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9\pL\pS-]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'))), 'cms_rule' => array('controller' => 'cms', 'rule' => 'content/{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_cms'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9\pL\pS-]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'))), 'cms_category_rule' => array('controller' => 'cms', 'rule' => 'content/category/{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_cms_category'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9\pL\pS-]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'))), 'module' => array('controller' => null, 'rule' => 'module/{module}{/:controller}', 'keywords' => array('module' => array('regexp' => '[_a-zA-Z0-9_-]+', 'param' => 'module'), 'controller' => array('regexp' => '[_a-zA-Z0-9_-]+', 'param' => 'controller')), 'params' => array('fc' => 'module')), 'product_rule' => array('controller' => 'product', 'rule' => '{category:/}{id}-{rewrite}{-:ean13}.html', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_product'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9\pL\pS-]*'), 'ean13' => array('regexp' => '[0-9\pL]*'), 'category' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'categories' => array('regexp' => '[/_a-zA-Z0-9-\pL]*'), 'reference' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'manufacturer' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'supplier' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'price' => array('regexp' => '[0-9\.,]*'), 'tags' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'layered_rule' => array('controller' => 'category', 'rule' => '{id}-{rewrite}{/:selected_filters}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_category'), 'selected_filters' => array('regexp' => '.*', 'param' => 'selected_filters'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9\pL\pS-]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'))))





* Visibility: **public**
* This property is defined in classes\Dispatcher.php line 47


### $use_routes

    protected boolean $use_routes = false





* Visibility: **protected**
* This property is defined in classes\Dispatcher.php line 145


### $multilang_activated

    protected mixed $multilang_activated = false





* Visibility: **protected**
* This property is defined in classes\Dispatcher.php line 147


### $routes

    protected array $routes = array()





* Visibility: **protected**
* This property is defined in classes\Dispatcher.php line 152


### $controller

    protected string $controller





* Visibility: **protected**
* This property is defined in classes\Dispatcher.php line 157


### $request_uri

    protected string $request_uri





* Visibility: **protected**
* This property is defined in classes\Dispatcher.php line 162


### $empty_route

    protected array $empty_route





* Visibility: **protected**
* This property is defined in classes\Dispatcher.php line 167


### $default_controller

    protected string $default_controller





* Visibility: **protected**
* This property is defined in classes\Dispatcher.php line 172


### $use_default_controller

    protected mixed $use_default_controller = false





* Visibility: **protected**
* This property is defined in classes\Dispatcher.php line 173


### $controller_not_found

    protected string $controller_not_found = 'pagenotfound'





* Visibility: **protected**
* This property is defined in classes\Dispatcher.php line 178


### $front_controller

    protected string $front_controller = self::FC_FRONT





* Visibility: **protected**
* This property is defined in classes\Dispatcher.php line 183


Methods
-------


### getInstance

    \Dispatcher DispatcherCore::getInstance()

Get current instance of dispatcher (singleton)



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Dispatcher.php line 190




### __construct

    mixed DispatcherCore::__construct()

Need to be instancied from getInstance() method



* Visibility: **protected**
* This method is defined in classes\Dispatcher.php line 201




### useDefaultController

    mixed DispatcherCore::useDefaultController()





* Visibility: **public**
* This method is defined in classes\Dispatcher.php line 231




### dispatch

    mixed DispatcherCore::dispatch()

Find the controller and instantiate it



* Visibility: **public**
* This method is defined in classes\Dispatcher.php line 254




### setRequestUri

    mixed DispatcherCore::setRequestUri()

Set request uri and iso lang



* Visibility: **protected**
* This method is defined in classes\Dispatcher.php line 376




### loadRoutes

    mixed DispatcherCore::loadRoutes($id_shop)

Load default routes group by languages



* Visibility: **protected**
* This method is defined in classes\Dispatcher.php line 402


#### Arguments
* $id_shop **mixed**



### addRoute

    mixed DispatcherCore::addRoute(string $route_id, string $rule, string $controller, integer $id_lang, array $keywords, array $params, integer $id_shop)





* Visibility: **public**
* This method is defined in classes\Dispatcher.php line 500


#### Arguments
* $route_id **string** - &lt;p&gt;Name of the route (need to be uniq, a second route with same name will override the first)&lt;/p&gt;
* $rule **string** - &lt;p&gt;Url rule&lt;/p&gt;
* $controller **string** - &lt;p&gt;Controller to call if request uri match the rule&lt;/p&gt;
* $id_lang **integer**
* $keywords **array**
* $params **array**
* $id_shop **integer**



### hasRoute

    boolean DispatcherCore::hasRoute(string $route_id, integer $id_lang, integer $id_shop)

Check if a route exists



* Visibility: **public**
* This method is defined in classes\Dispatcher.php line 564


#### Arguments
* $route_id **string**
* $id_lang **integer**
* $id_shop **integer**



### hasKeyword

    boolean DispatcherCore::hasKeyword(string $route_id, integer $id_lang, string $keyword, integer $id_shop)

Check if a keyword is written in a route rule



* Visibility: **public**
* This method is defined in classes\Dispatcher.php line 585


#### Arguments
* $route_id **string**
* $id_lang **integer**
* $keyword **string**
* $id_shop **integer**



### validateRoute

    mixed DispatcherCore::validateRoute(string $route_id, string $rule, array $errors)

Check if a route rule contain all required keywords of default route definition



* Visibility: **public**
* This method is defined in classes\Dispatcher.php line 609


#### Arguments
* $route_id **string**
* $rule **string** - &lt;p&gt;Rule to verify&lt;/p&gt;
* $errors **array** - &lt;p&gt;List of missing keywords&lt;/p&gt;



### createUrl

    mixed DispatcherCore::createUrl(string $route_id, integer $id_lang, array $params, $force_routes, string $anchor, $id_shop)

Create an url from



* Visibility: **public**
* This method is defined in classes\Dispatcher.php line 634


#### Arguments
* $route_id **string** - &lt;p&gt;Name the route&lt;/p&gt;
* $id_lang **integer**
* $params **array**
* $force_routes **mixed**
* $anchor **string** - &lt;p&gt;Optional anchor to add at the end of this url&lt;/p&gt;
* $id_shop **mixed**



### getController

    string DispatcherCore::getController($id_shop)

Retrieve the controller from url or request uri if routes are activated



* Visibility: **public**
* This method is defined in classes\Dispatcher.php line 719


#### Arguments
* $id_shop **mixed**



### getControllers

    array DispatcherCore::getControllers($dirs)

Get list of all available FO controllers



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Dispatcher.php line 814


#### Arguments
* $dirs **mixed**



### getModuleControllers

    array DispatcherCore::getModuleControllers($type, $module)

Get list of all available Module Front controllers



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Dispatcher.php line 832


#### Arguments
* $type **mixed**
* $module **mixed**



### getControllersInDirectory

    array DispatcherCore::getControllersInDirectory(string $dir)

Get list of available controllers from the specified dir



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Dispatcher.php line 870


#### Arguments
* $dir **string** - &lt;p&gt;Directory to scan (recursively)&lt;/p&gt;


