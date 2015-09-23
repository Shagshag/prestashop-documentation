Class GenderCore
=====================





* Class name: GenderCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Gender.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Gender.php#L30)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$id_gender](#property-$id_gender)
* [$name](#property-$name)
* [$type](#property-$type)

### Methods

* [__construct](#method-__construct)
* [getGenders](#method-getGenders)
* [getImage](#method-getImage)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'gender', 'primary' => 'id_gender', 'multilang' => true, 'fields' => array('type' => array('type' => self::TYPE_INT, 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isString', 'required' => true, 'size' => 20)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Gender.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Gender.php#L39).


### <a name="property-$id_gender"></a>$id_gender

```php
public mixed $id_gender
```





* Visibility: **public**
* Source: [classes/Gender.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Gender.php#L32).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/Gender.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Gender.php#L33).


### <a name="property-$type"></a>$type

```php
public mixed $type
```





* Visibility: **public**
* Source: [classes/Gender.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Gender.php#L34).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed GenderCore::__construct($id, $id_lang, $id_shop)
```





* Visibility: **public**
* Source: [classes/Gender.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Gender.php#L51)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-getGenders"></a>getGenders

```php
mixed GenderCore::getGenders($id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Gender.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Gender.php#L58)


#### Arguments
* $id_lang **mixed**



### <a name="method-getImage"></a>getImage

```php
mixed GenderCore::getImage($use_unknown)
```





* Visibility: **public**
* Source: [classes/Gender.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/Gender.php#L67)


#### Arguments
* $use_unknown **mixed**


