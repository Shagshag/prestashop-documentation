Class ConnectionsSourceCore
=====================





* Class name: ConnectionsSourceCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/ConnectionsSource.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ConnectionsSource.php#L27)


Contents
--------


### Properties

* [$date_add](#property-$date_add)
* [$definition](#property-$definition)
* [$http_referer](#property-$http_referer)
* [$id_connections](#property-$id_connections)
* [$keywords](#property-$keywords)
* [$request_uri](#property-$request_uri)
* [$uri_max_size](#property-$uri_max_size)

### Methods

* [add](#method-add)
* [getOrderSources](#method-getOrderSources)
* [logHttpReferer](#method-logHttpReferer)




Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public mixed $date_add
```





* Visibility: **public**
* Source: [classes/ConnectionsSource.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ConnectionsSource.php#L33).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'connections_source', 'primary' => 'id_connections_source', 'fields' => array('id_connections' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'http_referer' => array('type' => self::TYPE_STRING, 'validate' => 'isAbsoluteUrl'), 'request_uri' => array('type' => self::TYPE_STRING, 'validate' => 'isUrl'), 'keywords' => array('type' => self::TYPE_STRING, 'validate' => 'isMessage'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate', 'required' => true)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/ConnectionsSource.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ConnectionsSource.php#L39).


### <a name="property-$http_referer"></a>$http_referer

```php
public mixed $http_referer
```





* Visibility: **public**
* Source: [classes/ConnectionsSource.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ConnectionsSource.php#L30).


### <a name="property-$id_connections"></a>$id_connections

```php
public mixed $id_connections
```





* Visibility: **public**
* Source: [classes/ConnectionsSource.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ConnectionsSource.php#L29).


### <a name="property-$keywords"></a>$keywords

```php
public mixed $keywords
```





* Visibility: **public**
* Source: [classes/ConnectionsSource.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ConnectionsSource.php#L32).


### <a name="property-$request_uri"></a>$request_uri

```php
public mixed $request_uri
```





* Visibility: **public**
* Source: [classes/ConnectionsSource.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ConnectionsSource.php#L31).


### <a name="property-$uri_max_size"></a>$uri_max_size

```php
public mixed $uri_max_size = 255
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/ConnectionsSource.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ConnectionsSource.php#L34).


Methods
-------


### <a name="method-add"></a>add

```php
mixed ConnectionsSourceCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/ConnectionsSource.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ConnectionsSource.php#L51)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-getOrderSources"></a>getOrderSources

```php
mixed ConnectionsSourceCore::getOrderSources($id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConnectionsSource.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ConnectionsSource.php#L101)


#### Arguments
* $id_order **mixed**



### <a name="method-logHttpReferer"></a>logHttpReferer

```php
mixed ConnectionsSourceCore::logHttpReferer(\Cookie $cookie)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ConnectionsSource.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/ConnectionsSource.php#L58)


#### Arguments
* $cookie **[Cookie](class.CookieCore.md)**


