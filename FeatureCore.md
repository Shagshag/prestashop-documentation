FeatureCore
===============






* Class name: FeatureCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Feature.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L27)





Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Feature.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#30)


### $position

    public mixed $position





* Visibility: **public**
* This property is defined in [classes/Feature.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#31)


### $definition

    public mixed $definition = array('table' => 'feature', 'primary' => 'id_feature', 'multilang' => true, 'fields' => array('position' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Feature.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#36)


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'product_features', 'objectNodeName' => 'product_feature', 'fields' => array())





* Visibility: **protected**
* This property is defined in [classes/Feature.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#49)


Methods
-------


### getFeature

    array FeatureCore::getFeature(integer $id_lang, integer $id_feature)

Get a feature data for a given id_feature and id_lang



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Feature.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#62)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $id_feature **integer** - &lt;p&gt;Feature id&lt;/p&gt;



### getFeatures

    array FeatureCore::getFeatures(integer $id_lang, $with_shop)

Get all features for a given language



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Feature.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#79)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $with_shop **mixed**



### deleteSelection

    boolean FeatureCore::deleteSelection(array $selection)

Delete several objects from database



* Visibility: **public**
* This method is defined in [classes/Feature.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#95)


#### Arguments
* $selection **array** - &lt;p&gt;Array with items to delete&lt;/p&gt;



### add

    mixed FeatureCore::add($autodate, $nullValues)





* Visibility: **public**
* This method is defined in [classes/Feature.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#107)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### delete

    mixed FeatureCore::delete()





* Visibility: **public**
* This method is defined in [classes/Feature.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#118)




### update

    mixed FeatureCore::update($nullValues)





* Visibility: **public**
* This method is defined in [classes/Feature.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#152)


#### Arguments
* $nullValues **mixed**



### nbFeatures

    integer FeatureCore::nbFeatures(integer $id_lang)

Count number of features for a given language



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Feature.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#186)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;



### addFeatureImport

    mixed FeatureCore::addFeatureImport($name, $position)

Create a feature from import



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Feature.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#203)


#### Arguments
* $name **mixed**
* $position **mixed**



### getFeaturesForComparison

    mixed FeatureCore::getFeaturesForComparison($list_ids_product, $id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Feature.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#234)


#### Arguments
* $list_ids_product **mixed**
* $id_lang **mixed**



### isFeatureActive

    boolean FeatureCore::isFeatureActive()

This metohd is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Feature.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#270)




### updatePosition

    boolean FeatureCore::updatePosition(boolean $way, integer $position, $id_feature)

Move a feature



* Visibility: **public**
* This method is defined in [classes/Feature.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#281)


#### Arguments
* $way **boolean** - &lt;p&gt;Up (1)  or Down (0)&lt;/p&gt;
* $position **integer**
* $id_feature **mixed**



### cleanPositions

    boolean FeatureCore::cleanPositions()

Reorder feature position
Call it after deleting a feature.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Feature.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#323)




### getHigherPosition

    integer FeatureCore::getHigherPosition()

getHigherPosition

Get the higher feature position

* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Feature.php line 337](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#337)



