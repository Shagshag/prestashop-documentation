Class TagCore
=====================





* Class name: TagCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Tag.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Tag.php#L27)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$id_lang](#property-$id_lang)
* [$name](#property-$name)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addTags](#method-addTags)
* [deleteTagsForProduct](#method-deleteTagsForProduct)
* [getMainTags](#method-getMainTags)
* [getProductTags](#method-getProductTags)
* [getProducts](#method-getProducts)
* [setProducts](#method-setProducts)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'tag', 'primary' => 'id_tag', 'fields' => array('id_lang' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Tag.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Tag.php#L38).


### <a name="property-$id_lang"></a>$id_lang

```php
public integer $id_lang
```





* Visibility: **public**
* Source: [classes/Tag.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Tag.php#L30).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Tag.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Tag.php#L33).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_lang' => array('xlink_resource' => 'languages')))
```





* Visibility: **protected**
* Source: [classes/Tag.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Tag.php#L48).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed TagCore::__construct($id, $name, $id_lang)
```





* Visibility: **public**
* Source: [classes/Tag.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Tag.php#L54)


#### Arguments
* $id **mixed**
* $name **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

```php
mixed TagCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Tag.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Tag.php#L77)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addTags"></a>addTags

```php
boolean TagCore::addTags(integer $id_lang, integer $id_product, string|array $tag_list, $separator)
```

Add several tags in database and link it to a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Tag.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Tag.php#L94)


#### Arguments
* $id_lang **integer** - Language id
* $id_product **integer** - Product id to link tags with
* $tag_list **string|array** - List of tags, as array or as a string with comas
* $separator **mixed**



### <a name="method-deleteTagsForProduct"></a>deleteTagsForProduct

```php
mixed TagCore::deleteTagsForProduct($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tag.php line 216](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Tag.php#L216)


#### Arguments
* $id_product **mixed**



### <a name="method-getMainTags"></a>getMainTags

```php
mixed TagCore::getMainTags($id_lang, $nb)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tag.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Tag.php#L131)


#### Arguments
* $id_lang **mixed**
* $nb **mixed**



### <a name="method-getProductTags"></a>getProductTags

```php
mixed TagCore::getProductTags($id_product)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Tag.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Tag.php#L160)


#### Arguments
* $id_product **mixed**



### <a name="method-getProducts"></a>getProducts

```php
mixed TagCore::getProducts($associated, \Context $context)
```





* Visibility: **public**
* Source: [classes/Tag.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Tag.php#L174)


#### Arguments
* $associated **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-setProducts"></a>setProducts

```php
mixed TagCore::setProducts($array)
```





* Visibility: **public**
* Source: [classes/Tag.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/Tag.php#L195)


#### Arguments
* $array **mixed**


