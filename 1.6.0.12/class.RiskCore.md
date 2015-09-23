Class RiskCore
=====================





* Class name: RiskCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Risk.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Risk.php#L30)


Contents
--------


### Properties

* [$color](#property-$color)
* [$definition](#property-$definition)
* [$id_risk](#property-$id_risk)
* [$name](#property-$name)
* [$percent](#property-$percent)

### Methods

* [getFields](#method-getFields)
* [getRisks](#method-getRisks)
* [getTranslationsFieldsChild](#method-getTranslationsFieldsChild)




Properties
----------


### <a name="property-$color"></a>$color

```php
public mixed $color
```





* Visibility: **public**
* Source: [classes/Risk.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Risk.php#L34).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'risk', 'primary' => 'id_risk', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isString', 'required' => true, 'size' => 20), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor', 'size' => 32), 'percent' => array('type' => self::TYPE_INT, 'validate' => 'isPercentage')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Risk.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Risk.php#L37).


### <a name="property-$id_risk"></a>$id_risk

```php
public mixed $id_risk
```





* Visibility: **public**
* Source: [classes/Risk.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Risk.php#L32).


### <a name="property-$name"></a>$name

```php
public mixed $name
```





* Visibility: **public**
* Source: [classes/Risk.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Risk.php#L33).


### <a name="property-$percent"></a>$percent

```php
public mixed $percent
```





* Visibility: **public**
* Source: [classes/Risk.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Risk.php#L35).


Methods
-------


### <a name="method-getFields"></a>getFields

```php
mixed RiskCore::getFields()
```





* Visibility: **public**
* Source: [classes/Risk.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Risk.php#L48)




### <a name="method-getRisks"></a>getRisks

```php
mixed RiskCore::getRisks($id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Risk.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Risk.php#L68)


#### Arguments
* $id_lang **mixed**



### <a name="method-getTranslationsFieldsChild"></a>getTranslationsFieldsChild

```php
array RiskCore::getTranslationsFieldsChild()
```

Check then return multilingual fields for database interaction



* Visibility: **public**
* Source: [classes/Risk.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Risk.php#L62)



