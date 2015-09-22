Class GroupCore
=====================





* Class name: GroupCore
* Parent class: [ObjectModel](class.ObjectModelCore)
* Source: [classes/Group.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L27)



Properties
----------

* [$cache_reduction](#property-$cache_reduction)
* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$group_price_display_method](#property-$group_price_display_method)
* [$id](#property-$id)
* [$name](#property-$name)
* [$price_display_method](#property-$price_display_method)
* [$reduction](#property-$reduction)
* [$show_prices](#property-$show_prices)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [__construct](#method-__construct)
* [add](#method-add)
* [addModulesRestrictions](#method-addModulesRestrictions)
* [addRestrictionsForModule](#method-addRestrictionsForModule)
* [delete](#method-delete)
* [getCurrent](#method-getCurrent)
* [getCustomers](#method-getCustomers)
* [getDefaultPriceDisplayMethod](#method-getDefaultPriceDisplayMethod)
* [getGroups](#method-getGroups)
* [getPriceDisplayMethod](#method-getPriceDisplayMethod)
* [getReduction](#method-getReduction)
* [getReductionByIdGroup](#method-getReductionByIdGroup)
* [isCurrentlyUsed](#method-isCurrentlyUsed)
* [isFeatureActive](#method-isFeatureActive)
* [searchByName](#method-searchByName)
* [truncateModulesRestrictions](#method-truncateModulesRestrictions)
* [truncateRestrictionsByModule](#method-truncateRestrictionsByModule)
* [update](#method-update)




Properties
----------


### <a name="property-$cache_reduction"></a>$cache_reduction

    protected mixed $cache_reduction = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Group.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L68)


### <a name="property-$date_add"></a>$date_add

    public string $date_add





* Visibility: **public**
* Source: [classes/Group.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L44)


### <a name="property-$date_upd"></a>$date_upd

    public string $date_upd





* Visibility: **public**
* Source: [classes/Group.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L47)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'group', 'primary' => 'id_group', 'multilang' => true, 'fields' => array('reduction' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat'), 'price_display_method' => array('type' => self::TYPE_INT, 'validate' => 'isPriceDisplayMethod', 'required' => true), 'show_prices' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/Group.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L52)


### <a name="property-$group_price_display_method"></a>$group_price_display_method

    protected mixed $group_price_display_method = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Group.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L69)


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* Source: [classes/Group.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L29)


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* Source: [classes/Group.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L32)


### <a name="property-$price_display_method"></a>$price_display_method

    public integer $price_display_method





* Visibility: **public**
* Source: [classes/Group.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L38)


### <a name="property-$reduction"></a>$reduction

    public string $reduction





* Visibility: **public**
* Source: [classes/Group.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L35)


### <a name="property-$show_prices"></a>$show_prices

    public boolean $show_prices = 1





* Visibility: **public**
* Source: [classes/Group.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L41)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array()





* Visibility: **protected**
* Source: [classes/Group.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L71)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed GroupCore::__construct($id, $id_lang, $id_shop)





* Visibility: **public**
* Source: [classes/Group.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L73)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-add"></a>add

    mixed GroupCore::add($autodate, $null_values)





* Visibility: **public**
* Source: [classes/Group.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L154)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-addModulesRestrictions"></a>addModulesRestrictions

    boolean GroupCore::addModulesRestrictions($id_group, $modules, array $shops)

Adding restrictions modules to the group with id $id_group



* Visibility: **public**
* This method is **static**.
* Source: [classes/Group.php line 267](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L267)


#### Arguments
* $id_group **mixed**
* $modules **mixed**
* $shops **array**



### <a name="method-addRestrictionsForModule"></a>addRestrictionsForModule

    boolean GroupCore::addRestrictionsForModule(integer $id_module, array $shops)

Add restrictions for a new module.

We authorize every groups to the new module

* Visibility: **public**
* This method is **static**.
* Source: [classes/Group.php line 295](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L295)


#### Arguments
* $id_module **integer**
* $shops **array**



### <a name="method-delete"></a>delete

    mixed GroupCore::delete()





* Visibility: **public**
* Source: [classes/Group.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L173)




### <a name="method-getCurrent"></a>getCurrent

    \Group GroupCore::getCurrent()

Return current group object
Use context



* Visibility: **public**
* This method is **static**.
* Source: [classes/Group.php line 316](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L316)




### <a name="method-getCustomers"></a>getCustomers

    mixed GroupCore::getCustomers($count, $start, $limit, $shop_filtering)





* Visibility: **public**
* Source: [classes/Group.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L96)


#### Arguments
* $count **mixed**
* $start **mixed**
* $limit **mixed**
* $shop_filtering **mixed**



### <a name="method-getDefaultPriceDisplayMethod"></a>getDefaultPriceDisplayMethod

    mixed GroupCore::getDefaultPriceDisplayMethod()





* Visibility: **public**
* This method is **static**.
* Source: [classes/Group.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L149)




### <a name="method-getGroups"></a>getGroups

    mixed GroupCore::getGroups($id_lang, $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Group.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L81)


#### Arguments
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-getPriceDisplayMethod"></a>getPriceDisplayMethod

    mixed GroupCore::getPriceDisplayMethod($id_group)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Group.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L138)


#### Arguments
* $id_group **mixed**



### <a name="method-getReduction"></a>getReduction

    mixed GroupCore::getReduction($id_customer)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Group.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L118)


#### Arguments
* $id_customer **mixed**



### <a name="method-getReductionByIdGroup"></a>getReductionByIdGroup

    mixed GroupCore::getReductionByIdGroup($id_group)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Group.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L127)


#### Arguments
* $id_group **mixed**



### <a name="method-isCurrentlyUsed"></a>isCurrentlyUsed

    boolean GroupCore::isCurrentlyUsed($table, $has_active_column)

This method is allow to know if there are other groups than the default ones



* Visibility: **public**
* This method is **static**.
* Source: [classes/Group.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L229)


#### Arguments
* $table **mixed**
* $has_active_column **mixed**



### <a name="method-isFeatureActive"></a>isFeatureActive

    boolean GroupCore::isFeatureActive()

This method is allow to know if a feature is used or active



* Visibility: **public**
* This method is **static**.
* Source: [classes/Group.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L213)




### <a name="method-searchByName"></a>searchByName

    array GroupCore::searchByName(string $query)

Light back office search for Group



* Visibility: **public**
* This method is **static**.
* Source: [classes/Group.php line 357](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L357)


#### Arguments
* $query **string** - Searched string



### <a name="method-truncateModulesRestrictions"></a>truncateModulesRestrictions

    boolean GroupCore::truncateModulesRestrictions(integer $id_group)

Truncate all modules restrictions for the group



* Visibility: **public**
* This method is **static**.
* Source: [classes/Group.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L240)


#### Arguments
* $id_group **integer**



### <a name="method-truncateRestrictionsByModule"></a>truncateRestrictionsByModule

    boolean GroupCore::truncateRestrictionsByModule(integer $id_module)

Truncate all restrictions by module



* Visibility: **public**
* This method is **static**.
* Source: [classes/Group.php line 253](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L253)


#### Arguments
* $id_module **integer**



### <a name="method-update"></a>update

    mixed GroupCore::update($autodate, $null_values)





* Visibility: **public**
* Source: [classes/Group.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Group.php#L165)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**


