Class TranslatedConfigurationCore
=====================





* Class name: TranslatedConfigurationCore
* Parent class: [Configuration](class.ConfigurationCore.md)
* Source: [classes/TranslatedConfiguration.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#L27)



Properties
----------

* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [__construct](#method-__construct)
* [add](#method-add)
* [getWebserviceObjectList](#method-getWebserviceObjectList)
* [update](#method-update)




Properties
----------


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'configuration', 'primary' => 'id_configuration', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isConfigName', 'required' => true, 'size' => 32), 'id_shop_group' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'id_shop' => array('type' => self::TYPE_NOTHING, 'validate' => 'isUnsignedId'), 'value' => array('type' => self::TYPE_STRING, 'lang' => true), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate')))





* Visibility: **public**
* This property is **static**.
* Source: [classes/TranslatedConfiguration.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#L39).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectNodeName' => 'translated_configuration', 'objectsNodeName' => 'translated_configurations', 'fields' => array('value' => array(), 'date_add' => array(), 'date_upd' => array()))





* Visibility: **protected**
* Source: [classes/TranslatedConfiguration.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed TranslatedConfigurationCore::__construct($id, $id_lang)





* Visibility: **public**
* Source: [classes/TranslatedConfiguration.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#L53)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

    mixed TranslatedConfigurationCore::add($autodate, $nullValues)





* Visibility: **public**
* Source: [classes/TranslatedConfiguration.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#L71)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-getWebserviceObjectList"></a>getWebserviceObjectList

    mixed TranslatedConfigurationCore::getWebserviceObjectList($sql_join, $sql_filter, $sql_sort, $sql_limit)





* Visibility: **public**
* Source: [classes/TranslatedConfiguration.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#L98)


#### Arguments
* $sql_join **mixed**
* $sql_filter **mixed**
* $sql_sort **mixed**
* $sql_limit **mixed**



### <a name="method-update"></a>update

    mixed TranslatedConfigurationCore::update($nullValues)





* Visibility: **public**
* Source: [classes/TranslatedConfiguration.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/TranslatedConfiguration.php#L76)


#### Arguments
* $nullValues **mixed**


