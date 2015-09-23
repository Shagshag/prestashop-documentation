Class SceneCore
=====================





* Class name: SceneCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Scene.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L27)


Contents
--------


### Properties

* [$active](#property-$active)
* [$categories](#property-$categories)
* [$definition](#property-$definition)
* [$feature_active](#property-$feature_active)
* [$name](#property-$name)
* [$products](#property-$products)
* [$zones](#property-$zones)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [addCategories](#method-addCategories)
* [addZoneProducts](#method-addZoneProducts)
* [delete](#method-delete)
* [deleteCategories](#method-deleteCategories)
* [deleteImage](#method-deleteImage)
* [deleteZoneProducts](#method-deleteZoneProducts)
* [getIndexedCategories](#method-getIndexedCategories)
* [getProducts](#method-getProducts)
* [getScenes](#method-getScenes)
* [hideScenePosition](#method-hideScenePosition)
* [isFeatureActive](#method-isFeatureActive)
* [update](#method-update)
* [updateCategories](#method-updateCategories)
* [updateZoneProducts](#method-updateZoneProducts)




Properties
----------


### <a name="property-$active"></a>$active

```php
public boolean $active = true
```





* Visibility: **public**
* Source: [classes/Scene.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L33).


### <a name="property-$categories"></a>$categories

```php
public array $categories = array()
```





* Visibility: **public**
* Source: [classes/Scene.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L39).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'scene', 'primary' => 'id_scene', 'multilang' => true, 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 100)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Scene.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L47).


### <a name="property-$feature_active"></a>$feature_active

```php
protected mixed $feature_active = null
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Scene.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L59).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Scene.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L30).


### <a name="property-$products"></a>$products

```php
public array $products
```





* Visibility: **public**
* Source: [classes/Scene.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L42).


### <a name="property-$zones"></a>$zones

```php
public array $zones = array()
```





* Visibility: **public**
* Source: [classes/Scene.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L36).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed SceneCore::__construct($id, $id_lang, $lite_result, $hide_scene_position)
```





* Visibility: **public**
* Source: [classes/Scene.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L61)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $lite_result **mixed**
* $hide_scene_position **mixed**



### <a name="method-add"></a>add

```php
mixed SceneCore::add($autodate, $null_values)
```





* Visibility: **public**
* Source: [classes/Scene.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L89)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addCategories"></a>addCategories

```php
mixed SceneCore::addCategories($categories)
```





* Visibility: **public**
* Source: [classes/Scene.php line 128](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L128)


#### Arguments
* $categories **mixed**



### <a name="method-addZoneProducts"></a>addZoneProducts

```php
mixed SceneCore::addZoneProducts($zones)
```





* Visibility: **public**
* Source: [classes/Scene.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L157)


#### Arguments
* $zones **mixed**



### <a name="method-delete"></a>delete

```php
mixed SceneCore::delete()
```





* Visibility: **public**
* Source: [classes/Scene.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L106)




### <a name="method-deleteCategories"></a>deleteCategories

```php
mixed SceneCore::deleteCategories()
```





* Visibility: **public**
* Source: [classes/Scene.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L141)




### <a name="method-deleteImage"></a>deleteImage

```php
mixed SceneCore::deleteImage($force_delete)
```





* Visibility: **public**
* Source: [classes/Scene.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L118)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteZoneProducts"></a>deleteZoneProducts

```php
mixed SceneCore::deleteZoneProducts()
```





* Visibility: **public**
* Source: [classes/Scene.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L175)




### <a name="method-getIndexedCategories"></a>getIndexedCategories

```php
array SceneCore::getIndexedCategories(integer $id_scene)
```

Get categories where scene is indexed



* Visibility: **public**
* This method is **static**.
* Source: [classes/Scene.php line 266](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L266)


#### Arguments
* $id_scene **integer** - Scene id



### <a name="method-getProducts"></a>getProducts

```php
array SceneCore::getProducts($only_active, $id_lang, $lite_result, \Context $context)
```

Get all products of this scene



* Visibility: **public**
* Source: [classes/Scene.php line 227](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L227)


#### Arguments
* $only_active **mixed**
* $id_lang **mixed**
* $lite_result **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getScenes"></a>getScenes

```php
array SceneCore::getScenes($id_category, $id_lang, $only_active, $lite_result, $hide_scene_position, \Context $context)
```

Get all scenes of a category



* Visibility: **public**
* This method is **static**.
* Source: [classes/Scene.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L196)


#### Arguments
* $id_category **mixed**
* $id_lang **mixed**
* $only_active **mixed**
* $lite_result **mixed**
* $hide_scene_position **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-hideScenePosition"></a>hideScenePosition

```php
string SceneCore::hideScenePosition(string $name)
```

Hide scene prefix used for position



* Visibility: **public**
* This method is **static**.
* Source: [classes/Scene.php line 280](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L280)


#### Arguments
* $name **string** - Scene name



### <a name="method-isFeatureActive"></a>isFeatureActive

```php
boolean SceneCore::isFeatureActive()
```

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Scene.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L290)




### <a name="method-update"></a>update

```php
mixed SceneCore::update($null_values)
```





* Visibility: **public**
* Source: [classes/Scene.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L72)


#### Arguments
* $null_values **mixed**



### <a name="method-updateCategories"></a>updateCategories

```php
mixed SceneCore::updateCategories()
```





* Visibility: **public**
* Source: [classes/Scene.php line 148](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L148)




### <a name="method-updateZoneProducts"></a>updateZoneProducts

```php
mixed SceneCore::updateZoneProducts()
```





* Visibility: **public**
* Source: [classes/Scene.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.1/classes/Scene.php#L182)



