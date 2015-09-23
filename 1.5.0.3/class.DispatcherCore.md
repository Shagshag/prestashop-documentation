Class DispatcherCore
=====================





* Class name: DispatcherCore
* Source: [classes/Dispatcher.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L31)


Contents
--------


### Properties

* [$controller](#property-$controller)
* [$controller_directories](#property-$controller_directories)
* [$controller_not_found](#property-$controller_not_found)
* [$default_controller](#property-$default_controller)
* [$default_routes](#property-$default_routes)
* [$empty_route](#property-$empty_route)
* [$instance](#property-$instance)
* [$request_uri](#property-$request_uri)
* [$routes](#property-$routes)
* [$use_routes](#property-$use_routes)

### Methods

* [__construct](#method-__construct)
* [addRoute](#method-addRoute)
* [createUrl](#method-createUrl)
* [dispatch](#method-dispatch)
* [getAdminController](#method-getAdminController)
* [getController](#method-getController)
* [getControllers](#method-getControllers)
* [getControllersInDirectory](#method-getControllersInDirectory)
* [getInstance](#method-getInstance)
* [hasKeyword](#method-hasKeyword)
* [includeModuleClass](#method-includeModuleClass)
* [loadRoutes](#method-loadRoutes)
* [setControllerDirectories](#method-setControllerDirectories)
* [setControllerNotFound](#method-setControllerNotFound)
* [setDefaultController](#method-setDefaultController)
* [validateRoute](#method-validateRoute)




Properties
----------


### <a name="property-$controller"></a>$controller

```php
protected string $controller
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L132).


### <a name="property-$controller_directories"></a>$controller_directories

```php
protected array $controller_directories = array()
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L157).


### <a name="property-$controller_not_found"></a>$controller_not_found

```php
protected string $controller_not_found = 'pagenotfound'
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L152).


### <a name="property-$default_controller"></a>$default_controller

```php
protected string $default_controller = 'Index'
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L147).


### <a name="property-$default_routes"></a>$default_routes

```php
public array $default_routes = array('product_rule' => array('controller' => 'product', 'rule' => '{category:/}{id}-{rewrite}{-:ean13}.html', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_product'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'ean13' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'category' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'reference' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'manufacturer' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'supplier' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'price' => array('regexp' => '[0-9\.,]*'), 'tags' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'category_rule' => array('controller' => 'category', 'rule' => '{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_category'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'supplier_rule' => array('controller' => 'supplier', 'rule' => '{id}__{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_supplier'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'manufacturer_rule' => array('controller' => 'manufacturer', 'rule' => '{id}_{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_manufacturer'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'cms_rule' => array('controller' => 'cms', 'rule' => 'content/{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_cms'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'cms_category_rule' => array('controller' => 'cms', 'rule' => 'content/category/{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_cms_category'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'module' => array('controller' => 'module', 'rule' => 'module/{module}/{process}', 'keywords' => array('module' => array('regexp' => '[a-zA-Z0-9_-]+', 'param' => 'module'), 'process' => array('regexp' => '[a-zA-Z0-9_-]+', 'param' => 'process'))))
```





* Visibility: **public**
* Source: [classes/Dispatcher.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L41).


### <a name="property-$empty_route"></a>$empty_route

```php
protected array $empty_route
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L142).


### <a name="property-$instance"></a>$instance

```php
public \Dispatcher $instance = null
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Dispatcher.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L36).


### <a name="property-$request_uri"></a>$request_uri

```php
protected string $request_uri
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L137).


### <a name="property-$routes"></a>$routes

```php
protected array $routes = array()
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L127).


### <a name="property-$use_routes"></a>$use_routes

```php
protected boolean $use_routes = false
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L122).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed DispatcherCore::__construct()
```

Need to be instancied from getInstance() method



* Visibility: **protected**
* Source: [classes/Dispatcher.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L174)




### <a name="method-addRoute"></a>addRoute

```php
mixed DispatcherCore::addRoute($route_id, string $rule, string $controller, $keywords)
```





* Visibility: **public**
* Source: [classes/Dispatcher.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L393)


#### Arguments
* $route_id **mixed**
* $rule **string** - Url rule
* $controller **string** - Controller to call if request uri match the rule
* $keywords **mixed**



### <a name="method-createUrl"></a>createUrl

```php
mixed DispatcherCore::createUrl(string $route_id, array $params, boolean $use_routes, string $anchor)
```

Create an url from



* Visibility: **public**
* Source: [classes/Dispatcher.php line 472](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L472)


#### Arguments
* $route_id **string** - Name the route
* $params **array**
* $use_routes **boolean** - If false, don&#039;t use to create this url
* $anchor **string** - Optional anchor to add at the end of this url



### <a name="method-dispatch"></a>dispatch

```php
mixed DispatcherCore::dispatch()
```

Find the controller and instantiate it



* Visibility: **public**
* Source: [classes/Dispatcher.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L264)




### <a name="method-getAdminController"></a>getAdminController

```php
mixed DispatcherCore::getAdminController(string $name)
```

Get the controller row in db



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 226](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L226)


#### Arguments
* $name **string**



### <a name="method-getController"></a>getController

```php
string DispatcherCore::getController()
```

Retrieve the controller from url or request uri if routes are activated



* Visibility: **public**
* Source: [classes/Dispatcher.php line 533](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L533)




### <a name="method-getControllers"></a>getControllers

```php
array DispatcherCore::getControllers($dirs)
```

Get list of all available FO controllers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 590](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L590)


#### Arguments
* $dirs **mixed**



### <a name="method-getControllersInDirectory"></a>getControllersInDirectory

```php
array DispatcherCore::getControllersInDirectory($dir)
```

Get list of available controllers from the specified dir



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 615](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L615)


#### Arguments
* $dir **mixed**



### <a name="method-getInstance"></a>getInstance

```php
\Dispatcher DispatcherCore::getInstance()
```

Get current instance of dispatcher (singleton)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L164)




### <a name="method-hasKeyword"></a>hasKeyword

```php
boolean DispatcherCore::hasKeyword(string $route_id, string $keyword)
```

Check if a keyword is written in a route rule



* Visibility: **public**
* Source: [classes/Dispatcher.php line 436](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L436)


#### Arguments
* $route_id **string**
* $keyword **string**



### <a name="method-includeModuleClass"></a>includeModuleClass

```php
string|boolean DispatcherCore::includeModuleClass(string $module, string $name)
```

Include the file containing a controller or tab from a mdodule



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L245)


#### Arguments
* $module **string**
* $name **string** - controller name



### <a name="method-loadRoutes"></a>loadRoutes

```php
mixed DispatcherCore::loadRoutes()
```

Load default routes



* Visibility: **protected**
* Source: [classes/Dispatcher.php line 353](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L353)




### <a name="method-setControllerDirectories"></a>setControllerDirectories

```php
mixed DispatcherCore::setControllerDirectories($dir)
```

Set list of controllers where are stored controllers



* Visibility: **public**
* Source: [classes/Dispatcher.php line 214](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L214)


#### Arguments
* $dir **mixed**



### <a name="method-setControllerNotFound"></a>setControllerNotFound

```php
mixed DispatcherCore::setControllerNotFound($controller)
```

Controller to use if found controller doesn't exist



* Visibility: **public**
* Source: [classes/Dispatcher.php line 204](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L204)


#### Arguments
* $controller **mixed**



### <a name="method-setDefaultController"></a>setDefaultController

```php
mixed DispatcherCore::setDefaultController(string $controller)
```

Set default controller, which will be used if http parameter 'controller' is empty



* Visibility: **public**
* Source: [classes/Dispatcher.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L194)


#### Arguments
* $controller **string**



### <a name="method-validateRoute"></a>validateRoute

```php
mixed DispatcherCore::validateRoute(string $route_id, string $rule, array $errors)
```

Check if a route rule contain all required keywords of default route definition



* Visibility: **public**
* Source: [classes/Dispatcher.php line 451](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/Dispatcher.php#L451)


#### Arguments
* $route_id **string**
* $rule **string** - Rule to verify
* $errors **array** - List of missing keywords


