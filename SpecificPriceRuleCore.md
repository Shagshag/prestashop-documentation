SpecificPriceRuleCore
===============






* Class name: SpecificPriceRuleCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\SpecificPriceRule.php line 27





Properties
----------


### $name

    public mixed $name





* Visibility: **public**
* This property is defined in classes\SpecificPriceRule.php line 29


### $id_shop

    public mixed $id_shop





* Visibility: **public**
* This property is defined in classes\SpecificPriceRule.php line 30


### $id_currency

    public mixed $id_currency





* Visibility: **public**
* This property is defined in classes\SpecificPriceRule.php line 31


### $id_country

    public mixed $id_country





* Visibility: **public**
* This property is defined in classes\SpecificPriceRule.php line 32


### $id_group

    public mixed $id_group





* Visibility: **public**
* This property is defined in classes\SpecificPriceRule.php line 33


### $from_quantity

    public mixed $from_quantity





* Visibility: **public**
* This property is defined in classes\SpecificPriceRule.php line 34


### $price

    public mixed $price





* Visibility: **public**
* This property is defined in classes\SpecificPriceRule.php line 35


### $reduction

    public mixed $reduction





* Visibility: **public**
* This property is defined in classes\SpecificPriceRule.php line 36


### $reduction_tax

    public mixed $reduction_tax





* Visibility: **public**
* This property is defined in classes\SpecificPriceRule.php line 37


### $reduction_type

    public mixed $reduction_type





* Visibility: **public**
* This property is defined in classes\SpecificPriceRule.php line 38


### $from

    public mixed $from





* Visibility: **public**
* This property is defined in classes\SpecificPriceRule.php line 39


### $to

    public mixed $to





* Visibility: **public**
* This property is defined in classes\SpecificPriceRule.php line 40


### $rules_application_enable

    protected mixed $rules_application_enable = true





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\SpecificPriceRule.php line 42


### $definition

    public mixed $definition = array('table' => 'specific_price_rule', 'primary' => 'id_specific_price_rule', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true), 'id_shop' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_currency' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'from_quantity' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt', 'required' => true), 'price' => array('type' => self::TYPE_FLOAT, 'validate' => 'isNegativePrice', 'required' => true), 'reduction' => array('type' => self::TYPE_FLOAT, 'validate' => 'isPrice', 'required' => true), 'reduction_tax' => array('type' => self::TYPE_INT, 'validate' => 'isBool', 'required' => true), 'reduction_type' => array('type' => self::TYPE_STRING, 'validate' => 'isReductionType', 'required' => true), 'from' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat', 'required' => false), 'to' => array('type' => self::TYPE_DATE, 'validate' => 'isDateFormat', 'required' => false)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\SpecificPriceRule.php line 47


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'specific_price_rules', 'objectNodeName' => 'specific_price_rule', 'fields' => array('id_shop' => array('xlink_resource' => 'shops', 'required' => true), 'id_country' => array('xlink_resource' => 'countries', 'required' => true), 'id_currency' => array('xlink_resource' => 'currencies', 'required' => true), 'id_group' => array('xlink_resource' => 'groups', 'required' => true)))





* Visibility: **protected**
* This property is defined in classes\SpecificPriceRule.php line 66


Methods
-------


### delete

    mixed SpecificPriceRuleCore::delete()





* Visibility: **public**
* This method is defined in classes\SpecificPriceRule.php line 77




### deleteConditions

    mixed SpecificPriceRuleCore::deleteConditions()





* Visibility: **public**
* This method is defined in classes\SpecificPriceRule.php line 84




### disableAnyApplication

    mixed SpecificPriceRuleCore::disableAnyApplication()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\SpecificPriceRule.php line 97




### enableAnyApplication

    mixed SpecificPriceRuleCore::enableAnyApplication()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\SpecificPriceRule.php line 102




### addConditions

    mixed SpecificPriceRuleCore::addConditions($conditions)





* Visibility: **public**
* This method is defined in classes\SpecificPriceRule.php line 107


#### Arguments
* $conditions **mixed**



### apply

    mixed SpecificPriceRuleCore::apply($products)





* Visibility: **public**
* This method is defined in classes\SpecificPriceRule.php line 133


#### Arguments
* $products **mixed**



### resetApplication

    mixed SpecificPriceRuleCore::resetApplication($products)





* Visibility: **public**
* This method is defined in classes\SpecificPriceRule.php line 146


#### Arguments
* $products **mixed**



### applyAllRules

    mixed SpecificPriceRuleCore::applyAllRules(array|boolean $products)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\SpecificPriceRule.php line 158


#### Arguments
* $products **array|boolean**



### getConditions

    mixed SpecificPriceRuleCore::getConditions()





* Visibility: **public**
* This method is defined in classes\SpecificPriceRule.php line 171




### getAffectedProducts

    array SpecificPriceRuleCore::getAffectedProducts(boolean|array $products)

Return the product list affected by this specific rule.



* Visibility: **public**
* This method is defined in classes\SpecificPriceRule.php line 205


#### Arguments
* $products **boolean|array** - &lt;p&gt;Products list limitation.&lt;/p&gt;



### applyRuleToProduct

    mixed SpecificPriceRuleCore::applyRuleToProduct($id_rule, $id_product, $id_product_attribute)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\SpecificPriceRule.php line 288


#### Arguments
* $id_rule **mixed**
* $id_product **mixed**
* $id_product_attribute **mixed**


