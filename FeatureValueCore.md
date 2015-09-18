FeatureValueCore
===============






* Class name: FeatureValueCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_feature

    public integer $id_feature





* Visibility: **public**


### $value

    public string $value





* Visibility: **public**


### $custom

    public boolean $custom





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'feature_value', 'primary' => 'id_feature_value', 'multilang' => true, 'fields' => array('id_feature' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'custom' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'value' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 255)))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'product_feature_values', 'objectNodeName' => 'product_feature_value', 'fields' => array('id_feature' => array('xlink_resource' => 'product_features')))





* Visibility: **protected**


Methods
-------


### getFeatureValues

    array FeatureValueCore::getFeatureValues(boolean $id_feature)

Get all values for a given feature



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_feature **boolean** - &lt;p&gt;Feature id&lt;/p&gt;



### getFeatureValuesWithLang

    array FeatureValueCore::getFeatureValuesWithLang(integer $id_lang, boolean $id_feature, $custom)

Get all values for a given feature and language



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;
* $id_feature **boolean** - &lt;p&gt;Feature id&lt;/p&gt;
* $custom **mixed**



### getFeatureValueLang

    array FeatureValueCore::getFeatureValueLang(boolean $id_feature_value)

Get all language for a given value



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_feature_value **boolean** - &lt;p&gt;Feature value id&lt;/p&gt;



### selectLang

    string FeatureValueCore::selectLang(array $lang, integer $id_lang)

Select the good lang in tab



* Visibility: **public**
* This method is **static**.


#### Arguments
* $lang **array** - &lt;p&gt;Array with all language&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Language id&lt;/p&gt;



### addFeatureValueImport

    mixed FeatureValueCore::addFeatureValueImport($id_feature, $value, $id_product, $id_lang, $custom)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_feature **mixed**
* $value **mixed**
* $id_product **mixed**
* $id_lang **mixed**
* $custom **mixed**



### add

    mixed FeatureValueCore::add($autodate, $nullValues)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### delete

    mixed FeatureValueCore::delete()





* Visibility: **public**




### update

    mixed FeatureValueCore::update($nullValues)





* Visibility: **public**


#### Arguments
* $nullValues **mixed**


