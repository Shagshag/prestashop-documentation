GenderCore
===============






* Class name: GenderCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Gender.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Gender.php#L30)





Properties
----------


### $id_gender

    public mixed $id_gender





* Visibility: **public**
* This property is defined in [classes/Gender.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Gender.php#32)


### $name

    public mixed $name





* Visibility: **public**
* This property is defined in [classes/Gender.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Gender.php#33)


### $type

    public mixed $type





* Visibility: **public**
* This property is defined in [classes/Gender.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Gender.php#34)


### $definition

    public mixed $definition = array('table' => 'gender', 'primary' => 'id_gender', 'multilang' => true, 'fields' => array('type' => array('type' => self::TYPE_INT, 'required' => true), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isString', 'required' => true, 'size' => 20)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Gender.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Gender.php#39)


Methods
-------


### __construct

    mixed GenderCore::__construct($id, $id_lang, $id_shop)





* Visibility: **public**
* This method is defined in [classes/Gender.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Gender.php#51)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### getGenders

    mixed GenderCore::getGenders($id_lang)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Gender.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Gender.php#58)


#### Arguments
* $id_lang **mixed**



### getImage

    mixed GenderCore::getImage($use_unknown)





* Visibility: **public**
* This method is defined in [classes/Gender.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Gender.php#68)


#### Arguments
* $use_unknown **mixed**


