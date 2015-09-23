Class CustomerMessageCore
=====================





* Class name: CustomerMessageCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/CustomerMessage.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L27)


Contents
--------


### Properties

* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$file_name](#property-$file_name)
* [$id](#property-$id)
* [$id_customer_thread](#property-$id_customer_thread)
* [$id_employee](#property-$id_employee)
* [$ip_address](#property-$ip_address)
* [$message](#property-$message)
* [$private](#property-$private)
* [$read](#property-$read)
* [$user_agent](#property-$user_agent)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [delete](#method-delete)
* [getMessagesByOrderId](#method-getMessagesByOrderId)
* [getTotalCustomerMessages](#method-getTotalCustomerMessages)




Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public mixed $date_add
```





* Visibility: **public**
* Source: [classes/CustomerMessage.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L37).


### <a name="property-$date_upd"></a>$date_upd

```php
public mixed $date_upd
```





* Visibility: **public**
* Source: [classes/CustomerMessage.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L38).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'customer_message', 'primary' => 'id_customer_message', 'fields' => array('id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer_thread' => array('type' => self::TYPE_INT), 'ip_address' => array('type' => self::TYPE_STRING, 'validate' => 'isIp2Long', 'size' => 15), 'message' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 65000), 'file_name' => array('type' => self::TYPE_STRING), 'user_agent' => array('type' => self::TYPE_STRING), 'private' => array('type' => self::TYPE_INT), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'read' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/CustomerMessage.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L44).


### <a name="property-$file_name"></a>$file_name

```php
public mixed $file_name
```





* Visibility: **public**
* Source: [classes/CustomerMessage.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L33).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/CustomerMessage.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L29).


### <a name="property-$id_customer_thread"></a>$id_customer_thread

```php
public mixed $id_customer_thread
```





* Visibility: **public**
* Source: [classes/CustomerMessage.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L30).


### <a name="property-$id_employee"></a>$id_employee

```php
public mixed $id_employee
```





* Visibility: **public**
* Source: [classes/CustomerMessage.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L31).


### <a name="property-$ip_address"></a>$ip_address

```php
public mixed $ip_address
```





* Visibility: **public**
* Source: [classes/CustomerMessage.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L34).


### <a name="property-$message"></a>$message

```php
public mixed $message
```





* Visibility: **public**
* Source: [classes/CustomerMessage.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L32).


### <a name="property-$private"></a>$private

```php
public mixed $private
```





* Visibility: **public**
* Source: [classes/CustomerMessage.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L36).


### <a name="property-$read"></a>$read

```php
public mixed $read
```





* Visibility: **public**
* Source: [classes/CustomerMessage.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L39).


### <a name="property-$user_agent"></a>$user_agent

```php
public mixed $user_agent
```





* Visibility: **public**
* Source: [classes/CustomerMessage.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L35).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_employee' => array('xlink_resource' => 'employees'), 'id_customer_thread' => array('xlink_resource' => 'customer_threads')))
```





* Visibility: **protected**
* Source: [classes/CustomerMessage.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L61).


Methods
-------


### <a name="method-delete"></a>delete

```php
mixed CustomerMessageCore::delete()
```





* Visibility: **public**
* Source: [classes/CustomerMessage.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L110)




### <a name="method-getMessagesByOrderId"></a>getMessagesByOrderId

```php
mixed CustomerMessageCore::getMessagesByOrderId($id_order, $private)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CustomerMessage.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L72)


#### Arguments
* $id_order **mixed**
* $private **mixed**



### <a name="method-getTotalCustomerMessages"></a>getTotalCustomerMessages

```php
mixed CustomerMessageCore::getTotalCustomerMessages($where)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CustomerMessage.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/CustomerMessage.php#L95)


#### Arguments
* $where **mixed**


