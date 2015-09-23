Class DispatcherCore
=====================





* Class name: DispatcherCore
* Source: [classes/Dispatcher.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L30)


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
* [$multilang_activated](#property-$multilang_activated)
* [$request_uri](#property-$request_uri)
* [$routes](#property-$routes)
* [$use_default_controller](#property-$use_default_controller)
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
* [getModuleControllers](#method-getModuleControllers)
* [hasKeyword](#method-hasKeyword)
* [hasRoute](#method-hasRoute)
* [loadRoutes](#method-loadRoutes)
* [setRequestUri](#method-setRequestUri)
* [useDefaultController](#method-useDefaultController)
* [validateRoute](#method-validateRoute)


Constants
----------


### <a name="constant-FC_ADMIN"></a>FC_ADMIN

```php
const FC_ADMIN = 2
```





* Source: [classes/Dispatcher.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L36).


### <a name="constant-FC_FRONT"></a>FC_FRONT

```php
const FC_FRONT = 1
```

List of available front controllers types



* Source: [classes/Dispatcher.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L35).


### <a name="constant-FC_MODULE"></a>FC_MODULE

```php
const FC_MODULE = 3
```





* Source: [classes/Dispatcher.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L37).


Properties
----------


### <a name="property-$controller"></a>$controller

```php
protected string $controller
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L157).


### <a name="property-$controller_not_found"></a>$controller_not_found

```php
protected string $controller_not_found = 'pagenotfound'
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L178).


### <a name="property-$default_controller"></a>$default_controller

```php
protected string $default_controller
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L172).


### <a name="property-$default_routes"></a>$default_routes

```php
public array $default_routes = array('category_rule' => array('controller' => 'category', 'rule' => '{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_category'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'))), 'supplier_rule' => array('controller' => 'supplier', 'rule' => '{id}__{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_supplier'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'))), 'manufacturer_rule' => array('controller' => 'manufacturer', 'rule' => '{id}_{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_manufacturer'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'))), 'cms_rule' => array('controller' => 'cms', 'rule' => 'content/{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_cms'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'))), 'cms_category_rule' => array('controller' => 'cms', 'rule' => 'content/category/{id}-{rewrite}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_cms_category'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'))), 'module' => array('controller' => null, 'rule' => 'module/{module}{/:controller}', 'keywords' => array('module' => array('regexp' => '[_a-zA-Z0-9_-]+', 'param' => 'module'), 'controller' => array('regexp' => '[_a-zA-Z0-9_-]+', 'param' => 'controller')), 'params' => array('fc' => 'module')), 'product_rule' => array('controller' => 'product', 'rule' => '{category:/}{id}-{rewrite}{-:ean13}.html', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_product'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'ean13' => array('regexp' => '[0-9\pL]*'), 'category' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'categories' => array('regexp' => '[/_a-zA-Z0-9-\pL]*'), 'reference' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'manufacturer' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'supplier' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'price' => array('regexp' => '[0-9\.,]*'), 'tags' => array('regexp' => '[a-zA-Z0-9-\pL]*'))), 'layered_rule' => array('controller' => 'category', 'rule' => '{id}-{rewrite}{/:selected_filters}', 'keywords' => array('id' => array('regexp' => '[0-9]+', 'param' => 'id_category'), 'selected_filters' => array('regexp' => '.*', 'param' => 'selected_filters'), 'rewrite' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_keywords' => array('regexp' => '[_a-zA-Z0-9-\pL]*'), 'meta_title' => array('regexp' => '[_a-zA-Z0-9-\pL]*'))))
```





* Visibility: **public**
* Source: [classes/Dispatcher.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L47).


### <a name="property-$empty_route"></a>$empty_route

```php
protected array $empty_route
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 167](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L167).


### <a name="property-$front_controller"></a>$front_controller

```php
protected string $front_controller = self::FC_FRONT
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L183).


### <a name="property-$instance"></a>$instance

```php
public \Dispatcher $instance = null
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Dispatcher.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L42).


### <a name="property-$multilang_activated"></a>$multilang_activated

```php
protected mixed $multilang_activated = false
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L147).


### <a name="property-$request_uri"></a>$request_uri

```php
protected string $request_uri
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L162).


### <a name="property-$routes"></a>$routes

```php
protected array $routes = array()
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L152).


### <a name="property-$use_default_controller"></a>$use_default_controller

```php
protected mixed $use_default_controller = false
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L173).


### <a name="property-$use_routes"></a>$use_routes

```php
protected boolean $use_routes = false
```





* Visibility: **protected**
* Source: [classes/Dispatcher.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L145).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed DispatcherCore::__construct()
```

Need to be instancied from getInstance() method



* Visibility: **protected**
* Source: [classes/Dispatcher.php line 200](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L200)




### <a name="method-addRoute"></a>addRoute

```php
mixed DispatcherCore::addRoute(string $route_id, string $rule, string $controller, integer $id_lang, array $keywords, array $params, integer $id_shop)
```





* Visibility: **public**
* Source: [classes/Dispatcher.php line 504](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L504)


#### Arguments
* $route_id **string** - Name of the route (need to be uniq, a second route with same name will override the first)
* $rule **string** - Url rule
* $controller **string** - Controller to call if request uri match the rule
* $id_lang **integer**
* $keywords **array**
* $params **array**
* $id_shop **integer**



### <a name="method-createUrl"></a>createUrl

```php
mixed DispatcherCore::createUrl(string $route_id, integer $id_lang, array $params, $force_routes, string $anchor, $id_shop)
```

Create an url from



* Visibility: **public**
* Source: [classes/Dispatcher.php line 629](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L629)


#### Arguments
* $route_id **string** - Name the route
* $id_lang **integer**
* $params **array**
* $force_routes **mixed**
* $anchor **string** - Optional anchor to add at the end of this url
* $id_shop **mixed**



### <a name="method-dispatch"></a>dispatch

```php
mixed DispatcherCore::dispatch()
```

Find the controller and instantiate it



* Visibility: **public**
* Source: [classes/Dispatcher.php line 255](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L255)




### <a name="method-getController"></a>getController

```php
string DispatcherCore::getController($id_shop)
```

Retrieve the controller from url or request uri if routes are activated



* Visibility: **public**
* Source: [classes/Dispatcher.php line 711](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L711)


#### Arguments
* $id_shop **mixed**



### <a name="method-getControllers"></a>getControllers

```php
array DispatcherCore::getControllers($dirs)
```

Get list of all available FO controllers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 795](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L795)


#### Arguments
* $dirs **mixed**



### <a name="method-getControllersInDirectory"></a>getControllersInDirectory

```php
array DispatcherCore::getControllersInDirectory($dir)
```

Get list of available controllers from the specified dir



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 852](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L852)


#### Arguments
* $dir **mixed**



### <a name="method-getInstance"></a>getInstance

```php
\Dispatcher DispatcherCore::getInstance()
```

Get current instance of dispatcher (singleton)



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 190](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L190)




### <a name="method-getModuleControllers"></a>getModuleControllers

```php
array DispatcherCore::getModuleControllers($type, $module)
```

Get list of all available Module Front controllers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Dispatcher.php line 811](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L811)


#### Arguments
* $type **mixed**
* $module **mixed**



### <a name="method-hasKeyword"></a>hasKeyword

```php
boolean DispatcherCore::hasKeyword(string $route_id, integer $id_lang, string $keyword, integer $id_shop)
```

Check if a keyword is written in a route rule



* Visibility: **public**
* Source: [classes/Dispatcher.php line 586](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L586)


#### Arguments
* $route_id **string**
* $id_lang **integer**
* $keyword **string**
* $id_shop **integer**



### <a name="method-hasRoute"></a>hasRoute

```php
boolean DispatcherCore::hasRoute(string $route_id, integer $id_lang, integer $id_shop)
```

Check if a route exists



* Visibility: **public**
* Source: [classes/Dispatcher.php line 567](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L567)


#### Arguments
* $route_id **string**
* $id_lang **integer**
* $id_shop **integer**



### <a name="method-loadRoutes"></a>loadRoutes

```php
mixed DispatcherCore::loadRoutes($id_shop)
```

Load default routes group by languages



* Visibility: **protected**
* Source: [classes/Dispatcher.php line 408](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L408)


#### Arguments
* $id_shop **mixed**



### <a name="method-setRequestUri"></a>setRequestUri

```php
mixed DispatcherCore::setRequestUri()
```

Set request uri and iso lang



* Visibility: **protected**
* Source: [classes/Dispatcher.php line 384](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L384)




### <a name="method-useDefaultController"></a>useDefaultController

```php
mixed DispatcherCore::useDefaultController()
```





* Visibility: **public**
* Source: [classes/Dispatcher.php line 233](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L233)




### <a name="method-validateRoute"></a>validateRoute

```php
mixed DispatcherCore::validateRoute(string $route_id, string $rule, array $errors)
```

Check if a route rule contain all required keywords of default route definition



* Visibility: **public**
* Source: [classes/Dispatcher.php line 607](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/Dispatcher.php#L607)


#### Arguments
* $route_id **string**
* $rule **string** - Rule to verify
* $errors **array** - List of missing keywords


