Class MessageCore
=====================





* Class name: MessageCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Message.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L27)


Contents
--------


### Properties

* [$date_add](#property-$date_add)
* [$definition](#property-$definition)
* [$id](#property-$id)
* [$id_cart](#property-$id_cart)
* [$id_customer](#property-$id_customer)
* [$id_employee](#property-$id_employee)
* [$id_order](#property-$id_order)
* [$message](#property-$message)
* [$private](#property-$private)

### Methods

* [getMessageByCartId](#method-getMessageByCartId)
* [getMessagesByCartId](#method-getMessagesByCartId)
* [getMessagesByOrderId](#method-getMessagesByOrderId)
* [markAsReaded](#method-markAsReaded)




Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Message.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L50).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'message', 'primary' => 'id_message', 'fields' => array('message' => array('type' => self::TYPE_STRING, 'validate' => 'isCleanHtml', 'required' => true, 'size' => 1600), 'id_cart' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_order' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_customer' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'id_employee' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'private' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Message.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L55).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Message.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L29).


### <a name="property-$id_cart"></a>$id_cart

```php
public integer $id_cart
```





* Visibility: **public**
* Source: [classes/Message.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L35).


### <a name="property-$id_customer"></a>$id_customer

```php
public integer $id_customer
```





* Visibility: **public**
* Source: [classes/Message.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L41).


### <a name="property-$id_employee"></a>$id_employee

```php
public integer $id_employee
```





* Visibility: **public**
* Source: [classes/Message.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L44).


### <a name="property-$id_order"></a>$id_order

```php
public integer $id_order
```





* Visibility: **public**
* Source: [classes/Message.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L38).


### <a name="property-$message"></a>$message

```php
public string $message
```





* Visibility: **public**
* Source: [classes/Message.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L32).


### <a name="property-$private"></a>$private

```php
public boolean $private
```





* Visibility: **public**
* Source: [classes/Message.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L47).


Methods
-------


### <a name="method-getMessageByCartId"></a>getMessageByCartId

```php
array MessageCore::getMessageByCartId(integer $id_cart)
```

Return the last message from cart



* Visibility: **public**
* This method is **static**.
* Source: [classes/Message.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L75)


#### Arguments
* $id_cart **integer** - Cart ID



### <a name="method-getMessagesByCartId"></a>getMessagesByCartId

```php
array MessageCore::getMessagesByCartId($id_cart, boolean $private, \Context $context)
```

Return messages from Cart ID



* Visibility: **public**
* This method is **static**.
* Source: [classes/Message.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L122)


#### Arguments
* $id_cart **mixed**
* $private **boolean** - return WITH private messages
* $context **[Context](class.ContextCore.md)**



### <a name="method-getMessagesByOrderId"></a>getMessagesByOrderId

```php
array MessageCore::getMessagesByOrderId(integer $id_order, boolean $private, \Context $context)
```

Return messages from Order ID



* Visibility: **public**
* This method is **static**.
* Source: [classes/Message.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L91)


#### Arguments
* $id_order **integer** - Order ID
* $private **boolean** - return WITH private messages
* $context **[Context](class.ContextCore.md)**



### <a name="method-markAsReaded"></a>markAsReaded

```php
mixed MessageCore::markAsReaded(integer $id_message, $id_employee)
```

Registered a message 'readed'



* Visibility: **public**
* This method is **static**.
* Source: [classes/Message.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/Message.php#L150)


#### Arguments
* $id_message **integer** - Message ID
* $id_employee **mixed**


