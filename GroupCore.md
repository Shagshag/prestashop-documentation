GroupCore
===============






* Class name: GroupCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $reduction

    public string $reduction





* Visibility: **public**


### $price_display_method

    public integer $price_display_method





* Visibility: **public**


### $show_prices

    public boolean $show_prices = 1





* Visibility: **public**


### $date_add

    public string $date_add





* Visibility: **public**


### $date_upd

    public string $date_upd





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'group', 'primary' => 'id_group', 'multilang' => true, 'fields' => array('reduction' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'price_display_method' => array('type' => self::TYPE_INT, 'validate' => 'isPriceDisplayMethod', 'required' => true), 'show_prices' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32)))





* Visibility: **public**
* This property is **static**.


### $cache_reduction

    protected mixed $cache_reduction = array()





* Visibility: **protected**
* This property is **static**.


### $group_price_display_method

    protected mixed $group_price_display_method = array()





* Visibility: **protected**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array()





* Visibility: **protected**


Methods
-------


### __construct

    mixed GroupCore::__construct($id, $id_lang, $id_shop)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### getGroups

    mixed GroupCore::getGroups($id_lang, $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $id_shop **mixed**



### getCustomers

    mixed GroupCore::getCustomers($count, $start, $limit, $shop_filtering)





* Visibility: **public**


#### Arguments
* $count **mixed**
* $start **mixed**
* $limit **mixed**
* $shop_filtering **mixed**



### getReduction

    mixed GroupCore::getReduction($id_customer)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_customer **mixed**



### getReductionByIdGroup

    mixed GroupCore::getReductionByIdGroup($id_group)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_group **mixed**



### getPriceDisplayMethod

    mixed GroupCore::getPriceDisplayMethod($id_group)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_group **mixed**



### getDefaultPriceDisplayMethod

    mixed GroupCore::getDefaultPriceDisplayMethod()





* Visibility: **public**
* This method is **static**.




### add

    mixed GroupCore::add($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed GroupCore::update($autodate, $null_values)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### delete

    mixed GroupCore::delete()





* Visibility: **public**




### isFeatureActive

    boolean GroupCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.




### isCurrentlyUsed

    boolean GroupCore::isCurrentlyUsed($table, $has_active_column)

This method is allow to know if there are other groups than the default ones



* Visibility: **public**
* This method is **static**.


#### Arguments
* $table **mixed**
* $has_active_column **mixed**



### truncateModulesRestrictions

    boolean GroupCore::truncateModulesRestrictions(integer $id_group)

Truncate all modules restrictions for the group



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_group **integer**



### truncateRestrictionsByModule

    boolean GroupCore::truncateRestrictionsByModule(integer $id_module)

Truncate all restrictions by module



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_module **integer**



### addModulesRestrictions

    boolean GroupCore::addModulesRestrictions($id_group, $modules, array $shops)

Adding restrictions modules to the group with id $id_group



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_group **mixed**
* $modules **mixed**
* $shops **array**



### addRestrictionsForModule

    boolean GroupCore::addRestrictionsForModule(integer $id_module, array $shops)

Add restrictions for a new module.

We authorize every groups to the new module

* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_module **integer**
* $shops **array**



### getCurrent

    \Group GroupCore::getCurrent()

Return current group object
Use context



* Visibility: **public**
* This method is **static**.




### searchByName

    array GroupCore::searchByName(string $query)

Light back office search for Group



* Visibility: **public**
* This method is **static**.


#### Arguments
* $query **string** - &lt;p&gt;Searched string&lt;/p&gt;


