SceneCore
===============






* Class name: SceneCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $name

    public string $name





* Visibility: **public**


### $active

    public boolean $active = true





* Visibility: **public**


### $zones

    public array $zones = array()





* Visibility: **public**


### $categories

    public array $categories = array()





* Visibility: **public**


### $products

    public array $products





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'scene', 'primary' => 'id_scene', 'multilang' => true, 'fields' => array('active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 100)))





* Visibility: **public**
* This property is **static**.


### $feature_active

    protected mixed $feature_active = null





* Visibility: **protected**
* This property is **static**.


Methods
-------


### __construct

    mixed SceneCore::__construct($id, $id_lang, $lite_result, $hide_scene_position)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $lite_result **mixed**
* $hide_scene_position **mixed**



### update

    mixed SceneCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### add

    mixed SceneCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### delete

    mixed SceneCore::delete()





* Visibility: **public**




### deleteImage

    mixed SceneCore::deleteImage($force_delete)





* Visibility: **public**


#### Arguments
* $force_delete **mixed**



### addCategories

    mixed SceneCore::addCategories($categories)





* Visibility: **public**


#### Arguments
* $categories **mixed**



### deleteCategories

    mixed SceneCore::deleteCategories()





* Visibility: **public**




### updateCategories

    mixed SceneCore::updateCategories()





* Visibility: **public**




### addZoneProducts

    mixed SceneCore::addZoneProducts($zones)





* Visibility: **public**


#### Arguments
* $zones **mixed**



### deleteZoneProducts

    mixed SceneCore::deleteZoneProducts()





* Visibility: **public**




### updateZoneProducts

    mixed SceneCore::updateZoneProducts()





* Visibility: **public**




### getScenes

    array SceneCore::getScenes($id_category, $id_lang, $only_active, $lite_result, $hide_scene_position, \Context $context)

Get all scenes of a category



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_category **mixed**
* $id_lang **mixed**
* $only_active **mixed**
* $lite_result **mixed**
* $hide_scene_position **mixed**
* $context **Context**



### getProducts

    array SceneCore::getProducts($only_active, $id_lang, $lite_result, \Context $context)

Get all products of this scene



* Visibility: **public**


#### Arguments
* $only_active **mixed**
* $id_lang **mixed**
* $lite_result **mixed**
* $context **Context**



### getIndexedCategories

    array SceneCore::getIndexedCategories(integer $id_scene)

Get categories where scene is indexed



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_scene **integer** - &lt;p&gt;Scene id&lt;/p&gt;



### hideScenePosition

    string SceneCore::hideScenePosition(string $name)

Hide scene prefix used for position



* Visibility: **public**
* This method is **static**.


#### Arguments
* $name **string** - &lt;p&gt;Scene name&lt;/p&gt;



### isFeatureActive

    boolean SceneCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.



