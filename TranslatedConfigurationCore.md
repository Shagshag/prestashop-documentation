TranslatedConfigurationCore
===============






* Class name: TranslatedConfigurationCore
* Namespace: 
* Parent class: [Configuration](ConfigurationCore)

* This class is defined in [classes/TranslatedConfiguration.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#27)





Properties
----------


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectNodeName' => 'translated_configuration', 'objectsNodeName' => 'translated_configurations', 'fields' => array('value' => array(), 'date_add' => array(), 'date_upd' => array()))





* Visibility: **protected**
* This property is defined in [classes/TranslatedConfiguration.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#29)


### $definition

    public mixed $definition = array('table' => 'configuration', 'primary' => 'id_configuration', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isConfigName', 'required' => true, 'size' => 32), 'id_shop_group' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'value' => array('type' => self::TYPE_STRING, 'lang' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/TranslatedConfiguration.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#39)


Methods
-------


### __construct

    mixed TranslatedConfigurationCore::__construct($id, $id_lang)





* Visibility: **public**
* This method is defined in [classes/TranslatedConfiguration.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#53)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### add

    mixed TranslatedConfigurationCore::add($autodate, $nullValues)





* Visibility: **public**
* This method is defined in [classes/TranslatedConfiguration.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#71)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### update

    mixed TranslatedConfigurationCore::update($nullValues)





* Visibility: **public**
* This method is defined in [classes/TranslatedConfiguration.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#76)


#### Arguments
* $nullValues **mixed**



### getWebserviceObjectList

    mixed TranslatedConfigurationCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)





* Visibility: **public**
* This method is defined in [classes/TranslatedConfiguration.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#98)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**


