Class DispatcherCore
=====================





* Class name: DispatcherCore
* Source: [classes/Dispatcher.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L31)


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
* [loadRoutes](#method-loadRoutes)
* [validateRoute](#method-validateRoute)


Constants
----------


### <a name="constant-FC_ADMIN"></a>FC_ADMIN

```php
const FC_ADMIN = 2
```





* Source: [classes/Dispatcher.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L37).


### <a name="constant-FC_FRONT"></a>FC_FRONT

```php
const FC_FRONT = 1
```

List of available front controllers types



* Source: [classes/Dispatcher.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L36).


### <a name="constant-FC_MODULE"></a>FC_MODULE

```php
const FC_MODULE = 3
```





* Source: [classes/Dispatcher.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L38).


Properties
----------


### <a name="property-$controller"></a>$controller

```php
protected string $controller
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L143).


### <a name="property-$controller_not_found"></a>$controller_not_found

```php
protected string $controller_not_found = 'pagenotfound'
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L163).


### <a name="property-$default_controller"></a>$default_controller

```php
protected string $default_controller = 'index'
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 158](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L158).


### <a name="property-$default_routes"></a>$default_routes

```php
public array $default_routes = array('product_rule' => array('controller' => 'product', 'rule' => '{category:/}{id}-{rewrite}{-:ean13}.html', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_product'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'ean13' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'category' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'categories' => array('regexp' => '[/a-zA-Z0-9-\pL]*'), 'reference' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'manufacturer' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'supplier' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'price' => array('regexp' => '[0-9\.,]*'), 'tags' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'category_rule' => array('controller' => 'category', 'rule' => '{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_category'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'supplier_rule' => array('controller' => 'supplier', 'rule' => '{id}__{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_supplier'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'manufacturer_rule' => array('controller' => 'manufacturer', 'rule' => '{id}_{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_manufacturer'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'cms_rule' => array('controller' => 'cms', 'rule' => 'content/{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_cms'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'cms_category_rule' => array('controller' => 'cms', 'rule' => 'content/category/{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_cms_category'), 'rewrite' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'module' => array('controller' => null, 'rule' => 'module/{module}{/:controller}', 'keywords' => array('module' => array('regexp' => '[a-zA-Z0-9_-]+', 'param' => 'module'), 'controller' => array('regexp' => '[a-zA-Z0-9_-]+', 'param' => 'controller')), 'params' => array('fc' => 'module')))
```





* Visibility: **public**
* Source: [classes/Dispatcher.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L48).


### <a name="property-$empty_route"></a>$empty_route

```php
protected array $empty_route
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L153).


### <a name="property-$front_controller"></a>$front_controller

```php
protected string $front_controller = self::FC_FRONT
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L168).


### <a name="property-$instance"></a>$instance

```php
public \Dispatcher $instance = null
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Dispatcher.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L43).


### <a name="property-$request_uri"></a>$request_uri

```php
protected string $request_uri
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L148).


### <a name="property-$routes"></a>$routes

```php
protected array $routes = array()
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L138).


### <a name="property-$use_routes"></a>$use_routes

```php
protected boolean $use_routes = false
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L133).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed DispatcherCore::__construct()
```

Need to be instancied from getInstance() method



* Visibility: **protected**
* Source: [classes/Dispatcher.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L185)




### <a name="method-addRoute"></a>addRoute

```php
mixed DispatcherCore::addRoute($route_id, string $rule, string $controller, array $keywords, array $params)
```





* Visibility: **public**
* Source: [classes/Dispatcher.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L391)


#### Arguments
* $route_id **mixed**
* $rule **string** - Url rule
* $controller **string** - Controller to call if request uri match the rule
* $keywords **array**
* $params **array**



### <a name="method-createUrl"></a>createUrl

```php
mixed DispatcherCore::createUrl(string $route_id, array $params, boolean $use_routes, string $anchor)
```

Create an url from



* Visibility: **public**
* Source: [classes/Dispatcher.php line 471](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L471)


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
* Source: [classes/Dispatcher.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L223)




### <a name="method-getController"></a>getController

```php
string DispatcherCore::getController()
```

Retrieve the controller from url or request uri if routes are activated



* Visibility: **public**
* Source: [classes/Dispatcher.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L538)




### <a name="method-getControllers"></a>getControllers

```php
array DispatcherCore::getControllers($dirs)
```

Get list of all available FO controllers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 605](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L605)


#### Arguments
* $dirs **mixed**



### <a name="method-getControllersInDirectory"></a>getControllersInDirectory

```php
array DispatcherCore::getControllersInDirectory($dir)
```

Get list of available controllers from the specified dir



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 622](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L622)


#### Arguments
* $dir **mixed**



### <a name="method-getInstance"></a>getInstance

```php
\Dispatcher DispatcherCore::getInstance()
```

Get current instance of dispatcher (singleton)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L175)




### <a name="method-hasKeyword"></a>hasKeyword

```php
boolean DispatcherCore::hasKeyword(string $route_id, string $keyword)
```

Check if a keyword is written in a route rule



* Visibility: **public**
* Source: [classes/Dispatcher.php line 435](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L435)


#### Arguments
* $route_id **string**
* $keyword **string**



### <a name="method-loadRoutes"></a>loadRoutes

```php
mixed DispatcherCore::loadRoutes()
```

Load default routes



* Visibility: **protected**
* Source: [classes/Dispatcher.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L339)




### <a name="method-validateRoute"></a>validateRoute

```php
mixed DispatcherCore::validateRoute(string $route_id, string $rule, array $errors)
```

Check if a route rule contain all required keywords of default route definition



* Visibility: **public**
* Source: [classes/Dispatcher.php line 450](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/Dispatcher.php#L450)


#### Arguments
* $route_id **string**
* $rule **string** - Rule to verify
* $errors **array** - List of missing keywords


