GroupCore
===============






* Class name: GroupCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/Group.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#27)





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/Group.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#29)


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Group.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#32)


### $reduction

    public string $reduction





* Visibility: **public**
* This property is defined in [classes/Group.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#35)


### $price_display_method

    public integer $price_display_method





* Visibility: **public**
* This property is defined in [classes/Group.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#38)


### $show_prices

    public boolean $show_prices = 1





* Visibility: **public**
* This property is defined in [classes/Group.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#41)


### $date_add

    public string $date_add





* Visibility: **public**
* This property is defined in [classes/Group.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#44)


### $date_upd

    public string $date_upd





* Visibility: **public**
* This property is defined in [classes/Group.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#47)


### $definition

    public mixed $definition = array('table' => 'group', 'primary' => 'id_group', 'multilang' => true, 'fields' => array('reduction' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'price_display_method' => array('type' => self::TYPE_INT, 'validate' => 'isPriceDisplayMethod', 'required' => true), 'show_prices' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Group.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#52)


### $cache_reduction

    protected mixed $cache_reduction = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Group.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#68)


### $group_price_display_method

    protected mixed $group_price_display_method = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Group.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#69)


### $webserviceParameters

    protected mixed $webserviceParameters = array()





* Visibility: **protected**
* This property is defined in [classes/Group.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#71)


Methods
-------


### __construct

    mixed GroupCore::__construct($id, $id_lang, $id_shop)





* Visibility: **public**
* This method is defined in [classes/Group.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#73)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### getGroups

    mixed GroupCore::getGroups($id_lang, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Group.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#81)


#### Arguments
* $id_lang **mixed**
* $id_shop **mixed**



### getCustomers

    mixed GroupCore::getCustomers($count, $start, $limit, $shop_filtering)





* Visibility: **public**
* This method is defined in [classes/Group.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#96)


#### Arguments
* $count **mixed**
* $start **mixed**
* $limit **mixed**
* $shop_filtering **mixed**



### getReduction

    mixed GroupCore::getReduction($id_customer)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Group.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#118)


#### Arguments
* $id_customer **mixed**



### getReductionByIdGroup

    mixed GroupCore::getReductionByIdGroup($id_group)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Group.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#127)


#### Arguments
* $id_group **mixed**



### getPriceDisplayMethod

    mixed GroupCore::getPriceDisplayMethod($id_group)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Group.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#138)


#### Arguments
* $id_group **mixed**



### getDefaultPriceDisplayMethod

    mixed GroupCore::getDefaultPriceDisplayMethod()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Group.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#149)




### add

    mixed GroupCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Group.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#154)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed GroupCore::update($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Group.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#165)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### delete

    mixed GroupCore::delete()





* Visibility: **public**
* This method is defined in [classes/Group.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#173)




### isFeatureActive

    boolean GroupCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Group.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#213)




### isCurrentlyUsed

    boolean GroupCore::isCurrentlyUsed($table, $has_active_column)

This method is allow to know if there are other groups than the default ones



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Group.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#229)


#### Arguments
* $table **mixed**
* $has_active_column **mixed**



### truncateModulesRestrictions

    boolean GroupCore::truncateModulesRestrictions(integer $id_group)

Truncate all modules restrictions for the group



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Group.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#240)


#### Arguments
* $id_group **integer**



### truncateRestrictionsByModule

    boolean GroupCore::truncateRestrictionsByModule(integer $id_module)

Truncate all restrictions by module



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Group.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#253)


#### Arguments
* $id_module **integer**



### addModulesRestrictions

    boolean GroupCore::addModulesRestrictions($id_group, $modules, array $shops)

Adding restrictions modules to the group with id $id_group



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Group.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#267)


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
* This method is defined in [classes/Group.php line 295](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#295)


#### Arguments
* $id_module **integer**
* $shops **array**



### getCurrent

    \Group GroupCore::getCurrent()

Return current group object
Use context



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Group.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#316)




### searchByName

    array GroupCore::searchByName(string $query)

Light back office search for Group



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Group.php line 357](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#357)


#### Arguments
* $query **string** - &lt;p&gt;Searched string&lt;/p&gt;


