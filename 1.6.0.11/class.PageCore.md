Class PageCore
=====================





* Class name: PageCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Page.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Page.php#L27)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$id_object](#property-$id_object)
* [$id_page_type](#property-$id_page_type)
* [$name](#property-$name)

### Methods

* [getCurrentId](#method-getCurrentId)
* [getPageTypeByName](#method-getPageTypeByName)
* [setPageViewed](#method-setPageViewed)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'page', 'primary' => 'id_page', 'fields' => array('id_page_type' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_object' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Page.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Page.php#L37).


### <a name="property-$id_object"></a>$id_object

```php
public mixed $id_object
```





* Visibility: **public**
* Source: [classes/Page.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Page.php#L30).


### <a name="property-$id_page_type"></a>$id_page_type

```php
public mixed $id_page_type
```





* Visibility: **public**
* Source: [classes/Page.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Page.php#L29).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/Page.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Page.php#L32).


Methods
-------


### <a name="method-getCurrentId"></a>getCurrentId

```php
integer PageCore::getCurrentId()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Page.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Page.php#L49)




### <a name="method-getPageTypeByName"></a>getPageTypeByName

```php
mixed PageCore::getPageTypeByName(string $name)
```

Return page type ID from page name



* Visibility: **public**
* This method is **static**.
* Source: [classes/Page.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Page.php#L91)


#### Arguments
* $name **string** - Page name (E.g. product.php)



### <a name="method-setPageViewed"></a>setPageViewed

```php
mixed PageCore::setPageViewed($id_page)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Page.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/Page.php#L106)


#### Arguments
* $id_page **mixed**


