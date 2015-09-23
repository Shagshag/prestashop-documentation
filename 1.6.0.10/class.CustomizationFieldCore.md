Class CustomizationFieldCore
=====================





* Class name: CustomizationFieldCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/CustomizationField.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CustomizationField.php#L27)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$id_product](#property-$id_product)
* [$name](#property-$name)
* [$required](#property-$required)
* [$type](#property-$type)
* [$webserviceParameters](#property-$webserviceParameters)





Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'customization_field', 'primary' => 'id_customization_field', 'multilang' => true, 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'type' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'required' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'required' => true, 'size' => 255)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/CustomizationField.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CustomizationField.php#L41).


### <a name="property-$id_product"></a>$id_product

```php
public integer $id_product
```





* Visibility: **public**
* Source: [classes/CustomizationField.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CustomizationField.php#L30).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/CustomizationField.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CustomizationField.php#L36).


### <a name="property-$required"></a>$required

```php
public boolean $required
```





* Visibility: **public**
* Source: [classes/CustomizationField.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CustomizationField.php#L34).


### <a name="property-$type"></a>$type

```php
public integer $type
```





* Visibility: **public**
* Source: [classes/CustomizationField.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CustomizationField.php#L32).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('fields' => array('id_product' => array('xlink_resource' => array('resourceName' => 'products'))))
```





* Visibility: **protected**
* Source: [classes/CustomizationField.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/CustomizationField.php#L55).



