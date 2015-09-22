Class FeatureCore
=====================





* Class name: FeatureCore
* Parent class: [ObjectModel](class.ObjectModelCore)
* Source: [classes/Feature.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L27)



Properties
----------

* [$definition](#property-$definition)
* [$name](#property-$name)
* [$position](#property-$position)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
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

    public mixed $definition = array('table' => 'feature', 'primary' => 'id_feature', 'multilang' => true, 'fields' => array('position' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/Feature.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L36)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* Source: [classes/Feature.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L30)


### <a name="property-$position"></a>$position

    public mixed $position





* Visibility: **public**
* Source: [classes/Feature.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L31)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'product_features', 'objectNodeName' => 'product_feature', 'fields' => array())





* Visibility: **protected**
* Source: [classes/Feature.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L49)


Methods
-------


### <a name="method-add"></a>add

    mixed FeatureCore::add($autodate, $nullValues)





* Visibility: **public**
* Source: [classes/Feature.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L107)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-addFeatureImport"></a>addFeatureImport

    mixed FeatureCore::addFeatureImport($name, $position)

Create a feature from import



* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 203](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L203)


#### Arguments
* $name **mixed**
* $position **mixed**



### <a name="method-cleanPositions"></a>cleanPositions

    boolean FeatureCore::cleanPositions()

Reorder feature position
Call it after deleting a feature.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 323](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L323)




### <a name="method-delete"></a>delete

    mixed FeatureCore::delete()





* Visibility: **public**
* Source: [classes/Feature.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L118)




### <a name="method-deleteSelection"></a>deleteSelection

    boolean FeatureCore::deleteSelection(array $selection)

Delete several objects from database



* Visibility: **public**
* Source: [classes/Feature.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L95)


#### Arguments
* $selection **array** - Array with items to delete



### <a name="method-getFeature"></a>getFeature

    array FeatureCore::getFeature(integer $id_lang, integer $id_feature)

Get a feature data for a given id_feature and id_lang



* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L62)


#### Arguments
* $id_lang **integer** - Language id
* $id_feature **integer** - Feature id



### <a name="method-getFeatures"></a>getFeatures

    array FeatureCore::getFeatures(integer $id_lang, $with_shop)

Get all features for a given language



* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L79)


#### Arguments
* $id_lang **integer** - Language id
* $with_shop **mixed**



### <a name="method-getFeaturesForComparison"></a>getFeaturesForComparison

    mixed FeatureCore::getFeaturesForComparison($list_ids_product, $id_lang)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L234)


#### Arguments
* $list_ids_product **mixed**
* $id_lang **mixed**



### <a name="method-getHigherPosition"></a>getHigherPosition

    integer FeatureCore::getHigherPosition()

getHigherPosition

Get the higher feature position

* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 337](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L337)




### <a name="method-isFeatureActive"></a>isFeatureActive

    boolean FeatureCore::isFeatureActive()

This metohd is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 270](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L270)




### <a name="method-nbFeatures"></a>nbFeatures

    integer FeatureCore::nbFeatures(integer $id_lang)

Count number of features for a given language



* Visibility: **public**
* This method is **static**.
* Source: [classes/Feature.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L186)


#### Arguments
* $id_lang **integer** - Language id



### <a name="method-update"></a>update

    mixed FeatureCore::update($nullValues)





* Visibility: **public**
* Source: [classes/Feature.php line 152](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L152)


#### Arguments
* $nullValues **mixed**



### <a name="method-updatePosition"></a>updatePosition

    boolean FeatureCore::updatePosition(boolean $way, integer $position, $id_feature)

Move a feature



* Visibility: **public**
* Source: [classes/Feature.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Feature.php#L281)


#### Arguments
* $way **boolean** - Up (1)  or Down (0)
* $position **integer**
* $id_feature **mixed**


