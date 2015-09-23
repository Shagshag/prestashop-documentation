Class FeatureCore
=====================





* Class name: FeatureCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Feature.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L27)


Contents
--------


### Properties

* [$definition](#property-$definition)
* [$name](#property-$name)
* [$position](#property-$position)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [add](#method-add)
* [addFeatureImport](#method-addFeatureImport)
* [cleanPositions](#method-cleanPositions)
* [delete](#method-delete)
* [deleteSelection](#method-deleteSelection)
* [getFeature](#method-getFeature)
* [getFeatures](#method-getFeatures)
* [getFeaturesForComparison](#method-getFeaturesForComparison)
* [getHigherPosition](#method-getHigherPosition)
* [isFeatureActive](#method-isFeatureActive)
* [nbFeatures](#method-nbFeatures)
* [update](#method-update)
* [updatePosition](#method-updatePosition)




Properties
----------


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'feature', 'primary' => 'id_feature', 'multilang' => true, 'fields' => array('position' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Feature.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L36).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Feature.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L30).


### <a name="property-$position"></a>$position

```php
public mixed $position
```





* Visibility: **public**
* Source: [classes/Feature.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L31).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'product_features', 'objectNodeName' => 'product_feature', 'fields' => array())
```





* Visibility: **protected**
* Source: [classes/Feature.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L49).


Methods
-------


### <a name="method-add"></a>add

```php
mixed FeatureCore::add($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/Feature.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L109)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-addFeatureImport"></a>addFeatureImport

```php
mixed FeatureCore::addFeatureImport($name, $position)
```

Create a feature from import



* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 197](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L197)


#### Arguments
* $name **mixed**
* $position **mixed**



### <a name="method-cleanPositions"></a>cleanPositions

```php
boolean FeatureCore::cleanPositions()
```

Reorder feature position
Call it after deleting a feature.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L313)




### <a name="method-delete"></a>delete

```php
mixed FeatureCore::delete()
```





* Visibility: **public**
* Source: [classes/Feature.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L119)




### <a name="method-deleteSelection"></a>deleteSelection

```php
boolean FeatureCore::deleteSelection(array $selection)
```

Delete several objects from database



* Visibility: **public**
* Source: [classes/Feature.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L97)


#### Arguments
* $selection **array** - Array with items to delete



### <a name="method-getFeature"></a>getFeature

```php
array FeatureCore::getFeature(integer $id_lang, integer $id_feature)
```

Get a feature data for a given id_feature and id_lang



* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L63)


#### Arguments
* $id_lang **integer** - Language id
* $id_feature **integer** - Feature id



### <a name="method-getFeatures"></a>getFeatures

```php
array FeatureCore::getFeatures(integer $id_lang, $with_shop)
```

Get all features for a given language



* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L81)


#### Arguments
* $id_lang **integer** - Language id
* $with_shop **mixed**



### <a name="method-getFeaturesForComparison"></a>getFeaturesForComparison

```php
mixed FeatureCore::getFeaturesForComparison($list_ids_product, $id_lang)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L231)


#### Arguments
* $list_ids_product **mixed**
* $id_lang **mixed**



### <a name="method-getHigherPosition"></a>getHigherPosition

```php
integer FeatureCore::getHigherPosition()
```

getHigherPosition

Get the higher feature position

* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 355](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L355)




### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean FeatureCore::isFeatureActive()
```

This metohd is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L264)




### <a name="method-nbFeatures"></a>nbFeatures

```php
integer FeatureCore::nbFeatures(integer $id_lang)
```

Count number of features for a given language



* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L180)


#### Arguments
* $id_lang **integer** - Language id



### <a name="method-update"></a>update

```php
mixed FeatureCore::update($nullValues)
```





* Visibility: **public**
* Source: [classes/Feature.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L146)


#### Arguments
* $nullValues **mixed**



### <a name="method-updatePosition"></a>updatePosition

```php
boolean FeatureCore::updatePosition(boolean $way, integer $position, $id_feature)
```

Move a feature



* Visibility: **public**
* Source: [classes/Feature.php line 275](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.5/classes/Feature.php#L275)


#### Arguments
* $way **boolean** - Up (1)  or Down (0)
* $position **integer**
* $id_feature **mixed**


