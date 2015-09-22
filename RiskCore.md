RiskCore
===============






* Class name: RiskCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/Risk.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#30)





Properties
----------


### $id_risk

    public mixed $id_risk





* Visibility: **public**
* This property is defined in [classes/Risk.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#32)


### $name

    public mixed $name





* Visibility: **public**
* This property is defined in [classes/Risk.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#33)


### $color

    public mixed $color





* Visibility: **public**
* This property is defined in [classes/Risk.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#34)


### $percent

    public mixed $percent





* Visibility: **public**
* This property is defined in [classes/Risk.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#35)


### $definition

    public mixed $definition = array('table' => 'risk', 'primary' => 'id_risk', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isString', 'required' => true, 'size' => 20), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor', 'size' => 32), 'percent' => array('type' => self::TYPE_INT, 'validate' => 'isPercentage')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Risk.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#37)


Methods
-------


### getFields

    mixed RiskCore::getFields()





* Visibility: **public**
* This method is defined in [classes/Risk.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#48)




### getTranslationsFieldsChild

    array RiskCore::getTranslationsFieldsChild()

Check then return multilingual fields for database interaction



* Visibility: **public**
* This method is defined in [classes/Risk.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#62)




### getRisks

    mixed RiskCore::getRisks($id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Risk.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Risk.php#68)


#### Arguments
* $id_lang **mixed**


