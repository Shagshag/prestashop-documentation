Class SupplierCore
=====================





* Class name: SupplierCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Supplier.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L27)


Contents
--------


### Properties

* [$active](#property-$active)
* [$cache_name](#property-$cache_name)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$description](#property-$description)
* [$id](#property-$id)
* [$id_supplier](#property-$id_supplier)
* [$link_rewrite](#property-$link_rewrite)
* [$meta_description](#property-$meta_description)
* [$meta_keywords](#property-$meta_keywords)
* [$meta_title](#property-$meta_title)
* [$name](#property-$name)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [delete](#method-delete)
* [getIdByName](#method-getIdByName)
* [getLink](#method-getLink)
* [getNameById](#method-getNameById)
* [getProductInformationsBySupplier](#method-getProductInformationsBySupplier)
* [getProducts](#method-getProducts)
* [getProductsLite](#method-getProductsLite)
* [getSuppliers](#method-getSuppliers)
* [supplierExists](#method-supplierExists)




Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active
```





* Visibility: **public**
* Source: [classes/Supplier.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L59).


### <a name="property-$cache_name"></a>$cache_name

```php
protected mixed $cache_name = array()
```

Return name from id



* Visibility: **protected**
* This property is **static**.
* Source: [classes/Supplier.php line 172](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L172).


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/Supplier.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L41).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/Supplier.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L44).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'supplier', 'primary' => 'id_supplier', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isCatalogName', 'required' => true, 'size' => 64), 'active' => array('type' => self::TYPE_BOOL), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'description' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml'), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Supplier.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L64).


### <a name="property-$description"></a>$description

```php
public string $description
```





* Visibility: **public**
* Source: [classes/Supplier.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L38).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Supplier.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L29).


### <a name="property-$id_supplier"></a>$id_supplier

```php
public integer $id_supplier
```





* Visibility: **public**
* Source: [classes/Supplier.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L32).


### <a name="property-$link_rewrite"></a>$link_rewrite

```php
public string $link_rewrite
```





* Visibility: **public**
* Source: [classes/Supplier.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L47).


### <a name="property-$meta_description"></a>$meta_description

```php
public string $meta_description
```





* Visibility: **public**
* Source: [classes/Supplier.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L56).


### <a name="property-$meta_keywords"></a>$meta_keywords

```php
public string $meta_keywords
```





* Visibility: **public**
* Source: [classes/Supplier.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L53).


### <a name="property-$meta_title"></a>$meta_title

```php
public string $meta_title
```





* Visibility: **public**
* Source: [classes/Supplier.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L50).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Supplier.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L35).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('link_rewrite' => array('sqlId' => 'link_rewrite')))
```





* Visibility: **protected**
* Source: [classes/Supplier.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L82).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed SupplierCore::__construct($id, $id_lang)
```





* Visibility: **public**
* Source: [classes/Supplier.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L88)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-delete"></a>delete

```php
mixed SupplierCore::delete()
```





* Visibility: **public**
* Source: [classes/Supplier.php line 352](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L352)




### <a name="method-getIdByName"></a>getIdByName

```php
mixed SupplierCore::getIdByName($name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Supplier.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L181)


#### Arguments
* $name **mixed**



### <a name="method-getLink"></a>getLink

```php
mixed SupplierCore::getLink()
```





* Visibility: **public**
* Source: [classes/Supplier.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L96)




### <a name="method-getNameById"></a>getNameById

```php
mixed SupplierCore::getNameById($id_supplier)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Supplier.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L173)


#### Arguments
* $id_supplier **mixed**



### <a name="method-getProductInformationsBySupplier"></a>getProductInformationsBySupplier

```php
array SupplierCore::getProductInformationsBySupplier(integer $id_supplier, integer $id_product, integer $id_product_attribute)
```

Gets product informations



* Visibility: **public**
* This method is **static**.
* Source: [classes/Supplier.php line 370](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L370)


#### Arguments
* $id_supplier **integer**
* $id_product **integer**
* $id_product_attribute **integer**



### <a name="method-getProducts"></a>getProducts

```php
mixed SupplierCore::getProducts($id_supplier, $id_lang, $p, $n, $order_by, $order_way, $get_total, $active, $active_category)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Supplier.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L194)


#### Arguments
* $id_supplier **mixed**
* $id_lang **mixed**
* $p **mixed**
* $n **mixed**
* $order_by **mixed**
* $order_way **mixed**
* $get_total **mixed**
* $active **mixed**
* $active_category **mixed**



### <a name="method-getProductsLite"></a>getProductsLite

```php
mixed SupplierCore::getProductsLite($id_lang)
```





* Visibility: **public**
* Source: [classes/Supplier.php line 305](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L305)


#### Arguments
* $id_lang **mixed**



### <a name="method-getSuppliers"></a>getSuppliers

```php
array SupplierCore::getSuppliers($get_nb_products, $id_lang, $active, $p, $n, $all_groups)
```

Return suppliers



* Visibility: **public**
* This method is **static**.
* Source: [classes/Supplier.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L106)


#### Arguments
* $get_nb_products **mixed**
* $id_lang **mixed**
* $active **mixed**
* $p **mixed**
* $n **mixed**
* $all_groups **mixed**



### <a name="method-supplierExists"></a>supplierExists

```php
mixed SupplierCore::supplierExists($id_supplier)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Supplier.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/Supplier.php#L338)


#### Arguments
* $id_supplier **mixed**


