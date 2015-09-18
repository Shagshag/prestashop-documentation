AliasCore
===============






* Class name: AliasCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $alias

    public mixed $alias





* Visibility: **public**


### $search

    public mixed $search





* Visibility: **public**


### $active

    public mixed $active = true





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'alias', 'primary' => 'id_alias', 'fields' => array('search' => array('type' => self::TYPE_STRING, 'validate' => 'isValidSearch', 'required' => true, 'size' => 255), 'alias' => array('type' => self::TYPE_STRING, 'validate' => 'isValidSearch', 'required' => true, 'size' => 255), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.


Methods
-------


### __construct

    mixed AliasCore::__construct($id, $alias, $search, $id_lang)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $alias **mixed**
* $search **mixed**
* $id_lang **mixed**



### add

    mixed AliasCore::add($autodate, $nullValues)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### delete

    mixed AliasCore::delete()





* Visibility: **public**




### getAliases

    mixed AliasCore::getAliases()





* Visibility: **public**




### isFeatureActive

    boolean AliasCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.




### aliasExists

    boolean AliasCore::aliasExists($id_alias)

This method is allow to know if a alias exist for AdminImportController



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_alias **mixed**


