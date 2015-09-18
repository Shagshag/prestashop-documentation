RiskCore
===============






* Class name: RiskCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_risk

    public mixed $id_risk





* Visibility: **public**


### $name

    public mixed $name





* Visibility: **public**


### $color

    public mixed $color





* Visibility: **public**


### $percent

    public mixed $percent





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'risk', 'primary' => 'id_risk', 'multilang' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isString', 'required' => true, 'size' => 20), 'color' => array('type' => self::TYPE_STRING, 'validate' => 'isColor', 'size' => 32), 'percent' => array('type' => self::TYPE_INT, 'validate' => 'isPercentage')))





* Visibility: **public**
* This property is **static**.


Methods
-------


### getFields

    mixed RiskCore::getFields()





* Visibility: **public**




### getTranslationsFieldsChild

    array RiskCore::getTranslationsFieldsChild()

Check then return multilingual fields for database interaction



* Visibility: **public**




### getRisks

    mixed RiskCore::getRisks($id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**


