RiskCore
===============






* Class name: RiskCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Risk.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#L30)





Properties
----------

* [$id_risk](#property-$id_risk)
* [$name](#property-$name)
* [$color](#property-$color)
* [$percent](#property-$percent)
* [$definition](#property-$definition)

Methods
-------
* [getFields](#method-getFields)
* [getTranslationsFieldsChild](#method-getTranslationsFieldsChild)
* [getRisks](#method-getRisks)




Properties
----------


### <a name="property-$id_risk"></a>$id_risk

    public mixed $id_risk





* Visibility: **public**
* This property is defined in [classes/Risk.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#L32)


### <a name="property-$name"></a>$name

    public mixed $name





* Visibility: **public**
* This property is defined in [classes/Risk.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#L33)


### <a name="property-$color"></a>$color

    public mixed $color





* Visibility: **public**
* This property is defined in [classes/Risk.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#L34)


### <a name="property-$percent"></a>$percent

    public mixed $percent





* Visibility: **public**
* This property is defined in [classes/Risk.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#L35)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'risk', 'primary' => 'id_risk', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isString', 'required' => true, 'size' => 20), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor', 'size' => 32), 'percent' => array('type' => self::TYPE_INT, 'validate' => 'isPercentage')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Risk.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#L37)


Methods
-------


### <a name="method-getFields"></a>getFields

    mixed RiskCore::getFields()





* Visibility: **public**
* This method is defined in [classes/Risk.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#L48)




### <a name="method-getTranslationsFieldsChild"></a>getTranslationsFieldsChild

    array RiskCore::getTranslationsFieldsChild()

Check then return multilingual fields for database interaction



* Visibility: **public**
* This method is defined in [classes/Risk.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#L62)




### <a name="method-getRisks"></a>getRisks

    mixed RiskCore::getRisks($id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Risk.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#L68)


#### Arguments
* $id_lang **mixed**


