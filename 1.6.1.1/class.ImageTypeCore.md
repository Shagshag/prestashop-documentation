Class ImageTypeCore
=====================





* Class name: ImageTypeCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/ImageType.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L27)


Contents
--------


### Properties

* [$categories](#property-$categories)
* [$definition](#property-$definition)
* [$height](#property-$height)
* [$id](#property-$id)
* [$images_types_cache](#property-$images_types_cache)
* [$images_types_name_cache](#property-$images_types_name_cache)
* [$manufacturers](#property-$manufacturers)
* [$name](#property-$name)
* [$products](#property-$products)
* [$scenes](#property-$scenes)
* [$stores](#property-$stores)
* [$suppliers](#property-$suppliers)
* [$webserviceParameters](#property-$webserviceParameters)
* [$width](#property-$width)

### Methods

* [getByNameNType](#method-getByNameNType)
* [getFormatedName](#method-getFormatedName)
* [getImagesTypes](#method-getImagesTypes)
* [typeAlreadyExists](#method-typeAlreadyExists)




Properties
----------


### <a name="property-$categories"></a>$categories

```php
public integer $categories
```





* Visibility: **public**
* Source: [classes/ImageType.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L44).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'image_type', 'primary' => 'id_image_type', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isImageTypeName', 'required' => true, 'size' => 64), 'width' => array('type' => self::TYPE_INT, 'validate' => 'isImageSize', 'required' => true), 'height' => array('type' => self::TYPE_INT, 'validate' => 'isImageSize', 'required' => true), 'categories' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'products' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'manufacturers' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'suppliers' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'scenes' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'stores' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/ImageType.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L61).


### <a name="property-$height"></a>$height

```php
public integer $height
```





* Visibility: **public**
* Source: [classes/ImageType.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L38).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/ImageType.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L29).


### <a name="property-$images_types_cache"></a>$images_types_cache

```php
protected array $images_types_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/ImageType.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L80).


### <a name="property-$images_types_name_cache"></a>$images_types_name_cache

```php
protected mixed $images_types_name_cache = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/ImageType.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L82).


### <a name="property-$manufacturers"></a>$manufacturers

```php
public integer $manufacturers
```





* Visibility: **public**
* Source: [classes/ImageType.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L47).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/ImageType.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L32).


### <a name="property-$products"></a>$products

```php
public boolean $products
```





* Visibility: **public**
* Source: [classes/ImageType.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L41).


### <a name="property-$scenes"></a>$scenes

```php
public integer $scenes
```





* Visibility: **public**
* Source: [classes/ImageType.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L53).


### <a name="property-$stores"></a>$stores

```php
public integer $stores
```





* Visibility: **public**
* Source: [classes/ImageType.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L56).


### <a name="property-$suppliers"></a>$suppliers

```php
public integer $suppliers
```





* Visibility: **public**
* Source: [classes/ImageType.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L50).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array()
```





* Visibility: **protected**
* Source: [classes/ImageType.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L84).


### <a name="property-$width"></a>$width

```php
public integer $width
```





* Visibility: **public**
* Source: [classes/ImageType.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L35).


Methods
-------


### <a name="method-getByNameNType"></a>getByNameNType

```php
mixed ImageTypeCore::getByNameNType(string $name, string $type, $order)
```

Finds image type definition by name and type



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageType.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L138)


#### Arguments
* $name **string**
* $type **string**
* $order **mixed**



### <a name="method-getFormatedName"></a>getFormatedName

```php
mixed ImageTypeCore::getFormatedName($name)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageType.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L166)


#### Arguments
* $name **mixed**



### <a name="method-getImagesTypes"></a>getImagesTypes

```php
array ImageTypeCore::getImagesTypes($type, boolean $order_by_size)
```

Returns image type definitions



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageType.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L94)


#### Arguments
* $type **mixed**
* $order_by_size **boolean**



### <a name="method-typeAlreadyExists"></a>typeAlreadyExists

```php
integer ImageTypeCore::typeAlreadyExists($type_name)
```

Check if type already is already registered in database



* Visibility: **public**
* This method is **static**.
* Source: [classes/ImageType.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/ImageType.php#L119)


#### Arguments
* $type_name **mixed**


