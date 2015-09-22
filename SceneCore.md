SceneCore
===============






* Class name: SceneCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Scene.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L27)





Properties
----------

* [$name](#property-$name)
* [$active](#property-$active)
* [$zones](#property-$zones)
* [$categories](#property-$categories)
* [$products](#property-$products)
* [$definition](#property-$definition)
* [$feature_active](#property-$feature_active)

Methods
-------
* [__construct](#method-__construct)
* [update](#method-update)
* [add](#method-add)
* [delete](#method-delete)
* [deleteImage](#method-deleteImage)
* [addCategories](#method-addCategories)
* [deleteCategories](#method-deleteCategories)
* [updateCategories](#method-updateCategories)
* [addZoneProducts](#method-addZoneProducts)
* [deleteZoneProducts](#method-deleteZoneProducts)
* [updateZoneProducts](#method-updateZoneProducts)
* [getScenes](#method-getScenes)
* [getProducts](#method-getProducts)
* [getIndexedCategories](#method-getIndexedCategories)
* [hideScenePosition](#method-hideScenePosition)
* [isFeatureActive](#method-isFeatureActive)




Properties
----------


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Scene.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L30)


### <a name="property-$active"></a>$active

    public boolean $active = true





* Visibility: **public**
* This property is defined in [classes/Scene.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L33)


### <a name="property-$zones"></a>$zones

    public array $zones = array()





* Visibility: **public**
* This property is defined in [classes/Scene.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L36)


### <a name="property-$categories"></a>$categories

    public array $categories = array()





* Visibility: **public**
* This property is defined in [classes/Scene.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L39)


### <a name="property-$products"></a>$products

    public array $products





* Visibility: **public**
* This property is defined in [classes/Scene.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L42)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'scene', 'primary' => 'id_scene', 'multilang' => true, 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 100)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Scene.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L47)


### <a name="property-$feature_active"></a>$feature_active

    protected mixed $feature_active = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Scene.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L59)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed SceneCore::__construct($id, $id_lang, $lite_result, $hide_scene_position)





* Visibility: **public**
* This method is defined in [classes/Scene.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L61)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $lite_result **mixed**
* $hide_scene_position **mixed**



### <a name="method-update"></a>update

    mixed SceneCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/Scene.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L74)


#### Arguments
* $null_values **mixed**



### <a name="method-add"></a>add

    mixed SceneCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Scene.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L91)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-delete"></a>delete

    mixed SceneCore::delete()





* Visibility: **public**
* This method is defined in [classes/Scene.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L110)




### <a name="method-deleteImage"></a>deleteImage

    mixed SceneCore::deleteImage($force_delete)





* Visibility: **public**
* This method is defined in [classes/Scene.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L121)


#### Arguments
* $force_delete **mixed**



### <a name="method-addCategories"></a>addCategories

    mixed SceneCore::addCategories($categories)





* Visibility: **public**
* This method is defined in [classes/Scene.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L133)


#### Arguments
* $categories **mixed**



### <a name="method-deleteCategories"></a>deleteCategories

    mixed SceneCore::deleteCategories()





* Visibility: **public**
* This method is defined in [classes/Scene.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L145)




### <a name="method-updateCategories"></a>updateCategories

    mixed SceneCore::updateCategories()





* Visibility: **public**
* This method is defined in [classes/Scene.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L152)




### <a name="method-addZoneProducts"></a>addZoneProducts

    mixed SceneCore::addZoneProducts($zones)





* Visibility: **public**
* This method is defined in [classes/Scene.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L163)


#### Arguments
* $zones **mixed**



### <a name="method-deleteZoneProducts"></a>deleteZoneProducts

    mixed SceneCore::deleteZoneProducts()





* Visibility: **public**
* This method is defined in [classes/Scene.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L180)




### <a name="method-updateZoneProducts"></a>updateZoneProducts

    mixed SceneCore::updateZoneProducts()





* Visibility: **public**
* This method is defined in [classes/Scene.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L187)




### <a name="method-getScenes"></a>getScenes

    array SceneCore::getScenes($id_category, $id_lang, $only_active, $lite_result, $hide_scene_position, \Context $context)

Get all scenes of a category



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Scene.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L203)


#### Arguments
* $id_category **mixed**
* $id_lang **mixed**
* $only_active **mixed**
* $lite_result **mixed**
* $hide_scene_position **mixed**
* $context **[Context](ContextCore)**



### <a name="method-getProducts"></a>getProducts

    array SceneCore::getProducts($only_active, $id_lang, $lite_result, \Context $context)

Get all products of this scene



* Visibility: **public**
* This method is defined in [classes/Scene.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L245)


#### Arguments
* $only_active **mixed**
* $id_lang **mixed**
* $lite_result **mixed**
* $context **[Context](ContextCore)**



### <a name="method-getIndexedCategories"></a>getIndexedCategories

    array SceneCore::getIndexedCategories(integer $id_scene)

Get categories where scene is indexed



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Scene.php line 289](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L289)


#### Arguments
* $id_scene **integer** - &lt;p&gt;Scene id&lt;/p&gt;



### <a name="method-hideScenePosition"></a>hideScenePosition

    string SceneCore::hideScenePosition(string $name)

Hide scene prefix used for position



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Scene.php line 303](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L303)


#### Arguments
* $name **string** - &lt;p&gt;Scene name&lt;/p&gt;



### <a name="method-isFeatureActive"></a>isFeatureActive

    boolean SceneCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Scene.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Scene.php#L313)



