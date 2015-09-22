SceneCore
===============






* Class name: SceneCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\Scene.php line 27





Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in classes\Scene.php line 30


### $active

    public boolean $active = true





* Visibility: **public**
* This property is defined in classes\Scene.php line 33


### $zones

    public array $zones = array()





* Visibility: **public**
* This property is defined in classes\Scene.php line 36


### $categories

    public array $categories = array()





* Visibility: **public**
* This property is defined in classes\Scene.php line 39


### $products

    public array $products





* Visibility: **public**
* This property is defined in classes\Scene.php line 42


### $definition

    public mixed $definition = array('table' => 'scene', 'primary' => 'id_scene', 'multilang' => true, 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 100)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Scene.php line 47


### $feature_active

    protected mixed $feature_active = null





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\Scene.php line 59


Methods
-------


### __construct

    mixed SceneCore::__construct($id, $id_lang, $lite_result, $hide_scene_position)





* Visibility: **public**
* This method is defined in classes\Scene.php line 61


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $lite_result **mixed**
* $hide_scene_position **mixed**



### update

    mixed SceneCore::update($null_values)





* Visibility: **public**
* This method is defined in classes\Scene.php line 74


#### Arguments
* $null_values **mixed**



### add

    mixed SceneCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in classes\Scene.php line 91


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### delete

    mixed SceneCore::delete()





* Visibility: **public**
* This method is defined in classes\Scene.php line 110




### deleteImage

    mixed SceneCore::deleteImage($force_delete)





* Visibility: **public**
* This method is defined in classes\Scene.php line 121


#### Arguments
* $force_delete **mixed**



### addCategories

    mixed SceneCore::addCategories($categories)





* Visibility: **public**
* This method is defined in classes\Scene.php line 133


#### Arguments
* $categories **mixed**



### deleteCategories

    mixed SceneCore::deleteCategories()





* Visibility: **public**
* This method is defined in classes\Scene.php line 145




### updateCategories

    mixed SceneCore::updateCategories()





* Visibility: **public**
* This method is defined in classes\Scene.php line 152




### addZoneProducts

    mixed SceneCore::addZoneProducts($zones)





* Visibility: **public**
* This method is defined in classes\Scene.php line 163


#### Arguments
* $zones **mixed**



### deleteZoneProducts

    mixed SceneCore::deleteZoneProducts()





* Visibility: **public**
* This method is defined in classes\Scene.php line 180




### updateZoneProducts

    mixed SceneCore::updateZoneProducts()





* Visibility: **public**
* This method is defined in classes\Scene.php line 187




### getScenes

    array SceneCore::getScenes($id_category, $id_lang, $only_active, $lite_result, $hide_scene_position, \Context $context)

Get all scenes of a category



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Scene.php line 203


#### Arguments
* $id_category **mixed**
* $id_lang **mixed**
* $only_active **mixed**
* $lite_result **mixed**
* $hide_scene_position **mixed**
* $context **[Context](ContextCore)**



### getProducts

    array SceneCore::getProducts($only_active, $id_lang, $lite_result, \Context $context)

Get all products of this scene



* Visibility: **public**
* This method is defined in classes\Scene.php line 245


#### Arguments
* $only_active **mixed**
* $id_lang **mixed**
* $lite_result **mixed**
* $context **[Context](ContextCore)**



### getIndexedCategories

    array SceneCore::getIndexedCategories(integer $id_scene)

Get categories where scene is indexed



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Scene.php line 289


#### Arguments
* $id_scene **integer** - &lt;p&gt;Scene id&lt;/p&gt;



### hideScenePosition

    string SceneCore::hideScenePosition(string $name)

Hide scene prefix used for position



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Scene.php line 303


#### Arguments
* $name **string** - &lt;p&gt;Scene name&lt;/p&gt;



### isFeatureActive

    boolean SceneCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Scene.php line 313



