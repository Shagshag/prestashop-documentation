Class ConnectionCore
=====================





* Class name: ConnectionCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Connection.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L27)


Contents
--------


### Properties

* [$date_add](#property-$date_add)
* [$definition](#property-$definition)
* [$http_referer](#property-$http_referer)
* [$id_guest](#property-$id_guest)
* [$id_page](#property-$id_page)
* [$id_shop](#property-$id_shop)
* [$id_shop_group](#property-$id_shop_group)
* [$ip_address](#property-$ip_address)

### Methods

* [cleanConnectionsPages](#method-cleanConnectionsPages)
* [getFields](#method-getFields)
* [setNewConnection](#method-setNewConnection)
* [setPageConnection](#method-setPageConnection)
* [setPageTime](#method-setPageTime)




Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Connection.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L48).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'connections', 'primary' => 'id_connections', 'fields' => array('id_guest' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_page' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'ip_address' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'http_referer' => array('type' => self::TYPE_STRING, 'validate' => 'isAbsoluteUrl'), 'id_shop' => array('type' => self::TYPE_INT, 'required' => true), 'id_shop_group' => array('type' => self::TYPE_INT, 'required' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Connection.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L53).


### <a name="property-$http_referer"></a>$http_referer

```php
public string $http_referer
```





* Visibility: **public**
* Source: [classes/Connection.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L39).


### <a name="property-$id_guest"></a>$id_guest

```php
public integer $id_guest
```





* Visibility: **public**
* Source: [classes/Connection.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L30).


### <a name="property-$id_page"></a>$id_page

```php
public integer $id_page
```





* Visibility: **public**
* Source: [classes/Connection.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L33).


### <a name="property-$id_shop"></a>$id_shop

```php
public integer $id_shop
```





* Visibility: **public**
* Source: [classes/Connection.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L42).


### <a name="property-$id_shop_group"></a>$id_shop_group

```php
public integer $id_shop_group
```





* Visibility: **public**
* Source: [classes/Connection.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L45).


### <a name="property-$ip_address"></a>$ip_address

```php
public string $ip_address
```





* Visibility: **public**
* Source: [classes/Connection.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L36).


Methods
-------


### <a name="method-cleanConnectionsPages"></a>cleanConnectionsPages

```php
mixed ConnectionCore::cleanConnectionsPages()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Connection.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L178)




### <a name="method-getFields"></a>getFields

```php
array ConnectionCore::getFields()
```





* Visibility: **public**
* Source: [classes/Connection.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L71)




### <a name="method-setNewConnection"></a>setNewConnection

```php
mixed ConnectionCore::setNewConnection($cookie)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Connection.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L110)


#### Arguments
* $cookie **mixed**



### <a name="method-setPageConnection"></a>setPageConnection

```php
mixed ConnectionCore::setPageConnection($cookie, $full)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Connection.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L80)


#### Arguments
* $cookie **mixed**
* $full **mixed**



### <a name="method-setPageTime"></a>setPageTime

```php
mixed ConnectionCore::setPageTime($id_connections, $id_page, $time_start, $time)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Connection.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Connection.php#L160)


#### Arguments
* $id_connections **mixed**
* $id_page **mixed**
* $time_start **mixed**
* $time **mixed**


