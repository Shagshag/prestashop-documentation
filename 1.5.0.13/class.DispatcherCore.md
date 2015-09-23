Class DispatcherCore
=====================





* Class name: DispatcherCore
* Source: [classes/Dispatcher.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L31)


Contents
--------

### Constants

* [FC_ADMIN](#constant-FC_ADMIN)
* [FC_FRONT](#constant-FC_FRONT)
* [FC_MODULE](#constant-FC_MODULE)

### Properties

* [$controller](#property-$controller)
* [$controller_not_found](#property-$controller_not_found)
* [$default_controller](#property-$default_controller)
* [$default_routes](#property-$default_routes)
* [$empty_route](#property-$empty_route)
* [$front_controller](#property-$front_controller)
* [$instance](#property-$instance)
* [$request_uri](#property-$request_uri)
* [$routes](#property-$routes)
* [$use_routes](#property-$use_routes)

### Methods

* [__construct](#method-__construct)
* [addRoute](#method-addRoute)
* [createUrl](#method-createUrl)
* [dispatch](#method-dispatch)
* [getController](#method-getController)
* [getControllers](#method-getControllers)
* [getControllersInDirectory](#method-getControllersInDirectory)
* [getInstance](#method-getInstance)
* [hasKeyword](#method-hasKeyword)
* [hasRoute](#method-hasRoute)
* [loadRoutes](#method-loadRoutes)
* [validateRoute](#method-validateRoute)


Constants
----------


### <a name="constant-FC_ADMIN"></a>FC_ADMIN

```php
const FC_ADMIN = 2
```





* Source: [classes/Dispatcher.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L37).


### <a name="constant-FC_FRONT"></a>FC_FRONT

```php
const FC_FRONT = 1
```

List of available front controllers types



* Source: [classes/Dispatcher.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L36).


### <a name="constant-FC_MODULE"></a>FC_MODULE

```php
const FC_MODULE = 3
```





* Source: [classes/Dispatcher.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L38).


Properties
----------


### <a name="property-$controller"></a>$controller

```php
protected string $controller
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L155).


### <a name="property-$controller_not_found"></a>$controller_not_found

```php
protected string $controller_not_found = 'pagenotfound'
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L175).


### <a name="property-$default_controller"></a>$default_controller

```php
protected string $default_controller = 'index'
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L170).


### <a name="property-$default_routes"></a>$default_routes

```php
public array $default_routes = array('product_rule' => array('controller' => 'product', 'rule' => '{category:/}{id}-{rewrite}{-:ean13}.html', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_product'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'ean13' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'category' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'categories' => array('regexp' => '[/a-zA-Z0-9-\pL]*'), 'reference' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'manufacturer' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'supplier' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'price' => array('regexp' => '[0-9\.,]*'), 'tags' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'layered_rule' => array('controller' => 'category', 'rule' => '{id}-{rewrite}{/:selected_filters}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_category'), 'selected_filters' => array('regexp' => '.*', 'param' => 'selected_filters'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'category_rule' => array('controller' => 'category', 'rule' => '{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_category'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'supplier_rule' => array('controller' => 'supplier', 'rule' => '{id}__{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_supplier'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'manufacturer_rule' => array('controller' => 'manufacturer', 'rule' => '{id}_{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_manufacturer'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'cms_rule' => array('controller' => 'cms', 'rule' => 'content/{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_cms'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'cms_category_rule' => array('controller' => 'cms', 'rule' => 'content/category/{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_cms_category'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'module' => array('controller' => null, 'rule' => 'module/{module}{/:controller}', 'keywords' => array('module' => array('regexp' => '[a-zA-Z0-9_-]+', 'param' => 'module'), 'controller' => array('regexp' => '[a-zA-Z0-9_-]+', 'param' => 'controller')), 'params' => array('fc' => 'module')))
```





* Visibility: **public**
* Source: [classes/Dispatcher.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L48).


### <a name="property-$empty_route"></a>$empty_route

```php
protected array $empty_route
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L165).


### <a name="property-$front_controller"></a>$front_controller

```php
protected string $front_controller = self::FC_FRONT
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L180).


### <a name="property-$instance"></a>$instance

```php
public \Dispatcher $instance = null
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Dispatcher.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L43).


### <a name="property-$request_uri"></a>$request_uri

```php
protected string $request_uri
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L160).


### <a name="property-$routes"></a>$routes

```php
protected array $routes = array()
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L150).


### <a name="property-$use_routes"></a>$use_routes

```php
protected boolean $use_routes = false
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L145).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed DispatcherCore::__construct()
```

Need to be instancied from getInstance() method



* Visibility: **protected**
* Source: [classes/Dispatcher.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L197)




### <a name="method-addRoute"></a>addRoute

```php
mixed DispatcherCore::addRoute($route_id, string $rule, string $controller, array $keywords, array $params)
```





* Visibility: **public**
* Source: [classes/Dispatcher.php line 424](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L424)


#### Arguments
* $route_id **mixed**
* $rule **string** - Url rule
* $controller **string** - Controller to call if request uri match the rule
* $keywords **array**
* $params **array**



### <a name="method-createUrl"></a>createUrl

```php
mixed DispatcherCore::createUrl(string $route_id, array $params, $force_routes, string $anchor)
```

Create an url from



* Visibility: **public**
* Source: [classes/Dispatcher.php line 522](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L522)


#### Arguments
* $route_id **string** - Name the route
* $params **array**
* $force_routes **mixed**
* $anchor **string** - Optional anchor to add at the end of this url



### <a name="method-dispatch"></a>dispatch

```php
mixed DispatcherCore::dispatch()
```

Find the controller and instantiate it



* Visibility: **public**
* Source: [classes/Dispatcher.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L235)




### <a name="method-getController"></a>getController

```php
string DispatcherCore::getController()
```

Retrieve the controller from url or request uri if routes are activated



* Visibility: **public**
* Source: [classes/Dispatcher.php line 589](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L589)




### <a name="method-getControllers"></a>getControllers

```php
array DispatcherCore::getControllers($dirs)
```

Get list of all available FO controllers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 664](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L664)


#### Arguments
* $dirs **mixed**



### <a name="method-getControllersInDirectory"></a>getControllersInDirectory

```php
array DispatcherCore::getControllersInDirectory($dir)
```

Get list of available controllers from the specified dir



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 681](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L681)


#### Arguments
* $dir **mixed**



### <a name="method-getInstance"></a>getInstance

```php
\Dispatcher DispatcherCore::getInstance()
```

Get current instance of dispatcher (singleton)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L187)




### <a name="method-hasKeyword"></a>hasKeyword

```php
boolean DispatcherCore::hasKeyword(string $route_id, string $keyword)
```

Check if a keyword is written in a route rule



* Visibility: **public**
* Source: [classes/Dispatcher.php line 486](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L486)


#### Arguments
* $route_id **string**
* $keyword **string**



### <a name="method-hasRoute"></a>hasRoute

```php
boolean DispatcherCore::hasRoute(string $route_id)
```

Check if a route exists



* Visibility: **public**
* Source: [classes/Dispatcher.php line 474](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L474)


#### Arguments
* $route_id **string**



### <a name="method-loadRoutes"></a>loadRoutes

```php
mixed DispatcherCore::loadRoutes()
```

Load default routes



* Visibility: **protected**
* Source: [classes/Dispatcher.php line 364](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L364)




### <a name="method-validateRoute"></a>validateRoute

```php
mixed DispatcherCore::validateRoute(string $route_id, string $rule, array $errors)
```

Check if a route rule contain all required keywords of default route definition



* Visibility: **public**
* Source: [classes/Dispatcher.php line 501](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.13/classes/Dispatcher.php#L501)


#### Arguments
* $route_id **string**
* $rule **string** - Rule to verify
* $errors **array** - List of missing keywords


