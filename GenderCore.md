GenderCore
===============






* Class name: GenderCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_gender

    public mixed $id_gender





* Visibility: **public**


### $name

    public mixed $name





* Visibility: **public**


### $type

    public mixed $type





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'gender', 'primary' => 'id_gender', 'multilang' => true, 'fields' => array('type' => array('type' => self::TYPE_INT, 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isString', 'required' => true, 'size' => 20)))





* Visibility: **public**
* This property is **static**.


Methods
-------


### __construct

    mixed GenderCore::__construct($id, $id_lang, $id_shop)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### getGenders

    mixed GenderCore::getGenders($id_lang)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**



### getImage

    mixed GenderCore::getImage($use_unknown)





* Visibility: **public**


#### Arguments
* $use_unknown **mixed**


