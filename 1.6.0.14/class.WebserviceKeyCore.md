Class WebserviceKeyCore
=====================





* Class name: WebserviceKeyCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/webservice/WebserviceKey.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceKey.php#L27)


Contents
--------


### Properties

* [$active](#property-$active)
* [$definition](#property-$definition)
* [$description](#property-$description)
* [$key](#property-$key)

### Methods

* [add](#method-add)
* [delete](#method-delete)
* [deleteAssociations](#method-deleteAssociations)
* [getClassFromKey](#method-getClassFromKey)
* [getPermissionForAccount](#method-getPermissionForAccount)
* [isKeyActive](#method-isKeyActive)
* [keyExists](#method-keyExists)
* [setPermissionForAccount](#method-setPermissionForAccount)




Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceKey.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceKey.php#L33).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'webservice_account', 'primary' => 'id_webservice_account', 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'key' => array('type' => self::TYPE_STRING, 'required' => true, 'size' => 32), 'description' => array('type' => self::TYPE_STRING)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/webservice/WebserviceKey.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceKey.php#L41).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceKey.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceKey.php#L36).


### <a name="property-$key"></a>$key

```php
public string $key
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceKey.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceKey.php#L30).


Methods
-------


### <a name="method-add"></a>add

```php
mixed WebserviceKeyCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceKey.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceKey.php#L51)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-delete"></a>delete

```php
mixed WebserviceKeyCore::delete()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceKey.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceKey.php#L66)




### <a name="method-deleteAssociations"></a>deleteAssociations

```php
mixed WebserviceKeyCore::deleteAssociations()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceKey.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceKey.php#L71)




### <a name="method-getClassFromKey"></a>getClassFromKey

```php
mixed WebserviceKeyCore::getClassFromKey($auth_key)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/webservice/WebserviceKey.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceKey.php#L107)


#### Arguments
* $auth_key **mixed**



### <a name="method-getPermissionForAccount"></a>getPermissionForAccount

```php
mixed WebserviceKeyCore::getPermissionForAccount($auth_key)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/webservice/WebserviceKey.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceKey.php#L84)


#### Arguments
* $auth_key **mixed**



### <a name="method-isKeyActive"></a>isKeyActive

```php
mixed WebserviceKeyCore::isKeyActive($auth_key)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/webservice/WebserviceKey.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceKey.php#L99)


#### Arguments
* $auth_key **mixed**



### <a name="method-keyExists"></a>keyExists

```php
mixed WebserviceKeyCore::keyExists($key)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/webservice/WebserviceKey.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceKey.php#L58)


#### Arguments
* $key **mixed**



### <a name="method-setPermissionForAccount"></a>setPermissionForAccount

```php
mixed WebserviceKeyCore::setPermissionForAccount($id_account, $permissions_to_set)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/webservice/WebserviceKey.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.14/classes/webservice/WebserviceKey.php#L115)


#### Arguments
* $id_account **mixed**
* $permissions_to_set **mixed**


