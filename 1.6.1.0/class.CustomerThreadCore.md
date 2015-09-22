Class CustomerThreadCore
=====================





* Class name: CustomerThreadCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/CustomerThread.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L27)


Contents
--------


### Properties

* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$email](#property-$email)
* [$id](#property-$id)
* [$id_contact](#property-$id_contact)
* [$id_customer](#property-$id_customer)
* [$id_lang](#property-$id_lang)
* [$id_order](#property-$id_order)
* [$id_product](#property-$id_product)
* [$id_shop](#property-$id_shop)
* [$status](#property-$status)
* [$token](#property-$token)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [delete](#method-delete)
* [getContacts](#method-getContacts)
* [getCustomerMessages](#method-getCustomerMessages)
* [getIdCustomerThreadByEmailAndIdOrder](#method-getIdCustomerThreadByEmailAndIdOrder)
* [getMessageCustomerThreads](#method-getMessageCustomerThreads)
* [getNextThread](#method-getNextThread)
* [getTotalCustomerThreads](#method-getTotalCustomerThreads)
* [getWsCustomerMessages](#method-getWsCustomerMessages)




Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public mixed $date_add
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L39).


### <a name="property-$date_upd"></a>$date_upd

```php
public mixed $date_upd
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L40).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'customer_thread', 'primary' => 'id_customer_thread', 'fields' => array('id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_contact' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'email' => array('type' => self::TYPE_STRING, 'validate' => 'isEmail', 'size' => 254), 'token' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'status' => array('type' => self::TYPE_STRING), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/CustomerThread.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L45).


### <a name="property-$email"></a>$email

```php
public mixed $email
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L37).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L29).


### <a name="property-$id_contact"></a>$id_contact

```php
public mixed $id_contact
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L32).


### <a name="property-$id_customer"></a>$id_customer

```php
public mixed $id_customer
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L33).


### <a name="property-$id_lang"></a>$id_lang

```php
public mixed $id_lang
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L31).


### <a name="property-$id_order"></a>$id_order

```php
public mixed $id_order
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L34).


### <a name="property-$id_product"></a>$id_product

```php
public mixed $id_product
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L35).


### <a name="property-$id_shop"></a>$id_shop

```php
public mixed $id_shop
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L30).


### <a name="property-$status"></a>$status

```php
public mixed $status
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L36).


### <a name="property-$token"></a>$token

```php
public mixed $token
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L38).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_lang' => array('xlink_resource' => 'languages'), 'id_shop' => array('xlink_resource' => 'shops'), 'id_customer' => array('xlink_resource' => 'customers'), 'id_order' => array('xlink_resource' => 'orders'), 'id_product' => array('xlink_resource' => 'products')), 'associations' => array('customer_messages' => array('resource' => 'customer_message', 'id' => array('required' => true))))
```





* Visibility: **protected**
* Source: [classes/CustomerThread.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L63).


Methods
-------


### <a name="method-delete"></a>delete

```php
mixed CustomerThreadCore::delete()
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L96)




### <a name="method-getContacts"></a>getContacts

```php
mixed CustomerThreadCore::getContacts()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CustomerThread.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L150)




### <a name="method-getCustomerMessages"></a>getCustomerMessages

```php
mixed CustomerThreadCore::getCustomerMessages($id_customer, $read, $id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CustomerThread.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L123)


#### Arguments
* $id_customer **mixed**
* $read **mixed**
* $id_order **mixed**



### <a name="method-getIdCustomerThreadByEmailAndIdOrder"></a>getIdCustomerThreadByEmailAndIdOrder

```php
mixed CustomerThreadCore::getIdCustomerThreadByEmailAndIdOrder($email, $id_order)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CustomerThread.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L139)


#### Arguments
* $email **mixed**
* $id_order **mixed**



### <a name="method-getMessageCustomerThreads"></a>getMessageCustomerThreads

```php
mixed CustomerThreadCore::getMessageCustomerThreads($id_customer_thread)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CustomerThread.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L188)


#### Arguments
* $id_customer_thread **mixed**



### <a name="method-getNextThread"></a>getNextThread

```php
mixed CustomerThreadCore::getNextThread($id_customer_thread)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CustomerThread.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L207)


#### Arguments
* $id_customer_thread **mixed**



### <a name="method-getTotalCustomerThreads"></a>getTotalCustomerThreads

```php
mixed CustomerThreadCore::getTotalCustomerThreads($where)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/CustomerThread.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L172)


#### Arguments
* $where **mixed**



### <a name="method-getWsCustomerMessages"></a>getWsCustomerMessages

```php
mixed CustomerThreadCore::getWsCustomerMessages()
```





* Visibility: **public**
* Source: [classes/CustomerThread.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/CustomerThread.php#L88)



