Class ManufacturerCore
=====================





* Class name: ManufacturerCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Manufacturer.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L27)


Contents
--------


### Properties

* [$active](#property-$active)
* [$cacheName](#property-$cacheName)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$description](#property-$description)
* [$id](#property-$id)
* [$id_address](#property-$id_address)
* [$id_manufacturer](#property-$id_manufacturer)
* [$link_rewrite](#property-$link_rewrite)
* [$meta_description](#property-$meta_description)
* [$meta_keywords](#property-$meta_keywords)
* [$meta_title](#property-$meta_title)
* [$name](#property-$name)
* [$short_description](#property-$short_description)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [delete](#method-delete)
* [deleteSelection](#method-deleteSelection)
* [getAddresses](#method-getAddresses)
* [getIdByName](#method-getIdByName)
* [getLink](#method-getLink)
* [getManufacturerAddress](#method-getManufacturerAddress)
* [getManufacturers](#method-getManufacturers)
* [getNameById](#method-getNameById)
* [getProducts](#method-getProducts)
* [getProductsLite](#method-getProductsLite)
* [getWsAddresses](#method-getWsAddresses)
* [manufacturerExists](#method-manufacturerExists)
* [setWsAddresses](#method-setWsAddresses)




Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L65).


### <a name="property-$cacheName"></a>$cacheName

```php
protected mixed $cacheName = array()
```

Return name from id



* Visibility: **protected**
* This property is **static**.
* Source: [classes/Manufacturer.php line 221](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L221).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L47).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L50).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'manufacturer', 'primary' => 'id_manufacturer', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isCatalogName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL), 'date_add' => array('type' => self::TYPE_DATE), 'date_upd' => array('type' => self::TYPE_DATE), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'short_description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Manufacturer.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L70).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L38).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L29).


### <a name="property-$id_address"></a>$id_address

```php
public integer $id_address
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L44).


### <a name="property-$id_manufacturer"></a>$id_manufacturer

```php
public integer $id_manufacturer
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L32).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public string $link_rewrite
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L53).


### <a name="property-$meta_description"></a>$meta_description

```php
public string $meta_description
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L62).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public string $meta_keywords
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L59).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L56).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L35).


### <a name="property-$short_description"></a>$short_description

```php
public string $short_description
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L41).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('active' => array(), 'link_rewrite' => array('getter' => 'getLink', 'setter' => false)), 'associations' => array('addresses' => array('resource' => 'address', 'setter' => false, 'fields' => array('id' => array('xlink_resource' => 'addresses')))))
```





* Visibility: **protected**
* Source: [classes/Manufacturer.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L89).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed ManufacturerCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L101)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-delete"></a>delete

```php
mixed ManufacturerCore::delete()
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L109)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed ManufacturerCore::deleteSelection($selection)
```

Delete several objects from database

return boolean Deletion result

* Visibility: **public**
* Source: [classes/Manufacturer.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L128)


#### Arguments
* $selection **mixed**



### <a name="method-getAddresses"></a>getAddresses

```php
mixed ManufacturerCore::getAddresses($id_lang)
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 405](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L405)


#### Arguments
* $id_lang **mixed**



### <a name="method-getIdByName"></a>getIdByName

```php
mixed ManufacturerCore::getIdByName($name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Manufacturer.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L235)


#### Arguments
* $name **mixed**



### <a name="method-getLink"></a>getLink

```php
mixed ManufacturerCore::getLink()
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 249](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L249)




### <a name="method-getManufacturerAddress"></a>getManufacturerAddress

```php
mixed ManufacturerCore::getManufacturerAddress()
```





* Visibility: **protected**
* Source: [classes/Manufacturer.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L144)




### <a name="method-getManufacturers"></a>getManufacturers

```php
array ManufacturerCore::getManufacturers(boolean $get_nb_products, integer $id_lang, boolean $active, integer $p, integer $n, boolean $all_group)
```

Return manufacturers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Manufacturer.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L163)


#### Arguments
* $get_nb_products **boolean** - [optional] return products numbers for each
* $id_lang **integer**
* $active **boolean**
* $p **integer**
* $n **integer**
* $all_group **boolean**



### <a name="method-getNameById"></a>getNameById

```php
mixed ManufacturerCore::getNameById($id_manufacturer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Manufacturer.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L222)


#### Arguments
* $id_manufacturer **mixed**



### <a name="method-getProducts"></a>getProducts

```php
mixed ManufacturerCore::getProducts($id_manufacturer, $id_lang, $p, $n, $order_by, $order_way, $get_total, $active, $active_category, \Context $context)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Manufacturer.php line 254](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L254)


#### Arguments
* $id_manufacturer **mixed**
* $id_lang **mixed**
* $p **mixed**
* $n **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $get_total **mixed**
* $active **mixed**
* $active_category **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getProductsLite"></a>getProductsLite

```php
mixed ManufacturerCore::getProductsLite($id_lang)
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L369)


#### Arguments
* $id_lang **mixed**



### <a name="method-getWsAddresses"></a>getWsAddresses

```php
mixed ManufacturerCore::getWsAddresses()
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 420](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L420)




### <a name="method-manufacturerExists"></a>manufacturerExists

```php
mixed ManufacturerCore::manufacturerExists($id_manufacturer)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Manufacturer.php line 394](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L394)


#### Arguments
* $id_manufacturer **mixed**



### <a name="method-setWsAddresses"></a>setWsAddresses

```php
mixed ManufacturerCore::setWsAddresses($id_addresses)
```





* Visibility: **public**
* Source: [classes/Manufacturer.php line 431](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/Manufacturer.php#L431)


#### Arguments
* $id_addresses **mixed**


