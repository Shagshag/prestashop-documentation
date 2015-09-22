TaxRuleCore
===============






* Class name: TaxRuleCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\tax\TaxRule.php line 27





Properties
----------


### $id_tax_rules_group

    public mixed $id_tax_rules_group





* Visibility: **public**
* This property is defined in classes\tax\TaxRule.php line 29


### $id_country

    public mixed $id_country





* Visibility: **public**
* This property is defined in classes\tax\TaxRule.php line 30


### $id_state

    public mixed $id_state





* Visibility: **public**
* This property is defined in classes\tax\TaxRule.php line 31


### $zipcode_from

    public mixed $zipcode_from





* Visibility: **public**
* This property is defined in classes\tax\TaxRule.php line 32


### $zipcode_to

    public mixed $zipcode_to





* Visibility: **public**
* This property is defined in classes\tax\TaxRule.php line 33


### $id_tax

    public mixed $id_tax





* Visibility: **public**
* This property is defined in classes\tax\TaxRule.php line 34


### $behavior

    public mixed $behavior





* Visibility: **public**
* This property is defined in classes\tax\TaxRule.php line 35


### $description

    public mixed $description





* Visibility: **public**
* This property is defined in classes\tax\TaxRule.php line 36


### $definition

    public mixed $definition = array('table' => 'tax_rule', 'primary' => 'id_tax_rule', 'fields' => array('id_tax_rules_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'zipcode_from' => array('type' => self::TYPE_STRING, 'validate' => 'isPostCode'), 'zipcode_to' => array('type' => self::TYPE_STRING, 'validate' => 'isPostCode'), 'id_tax' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'behavior' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'description' => array('type' => self::TYPE_STRING, 'validate' => 'isString')))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\tax\TaxRule.php line 41


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_tax_rules_group' => array('xlink_resource' => 'tax_rule_groups'), 'id_state' => array('xlink_resource' => 'states'), 'id_country' => array('xlink_resource' => 'countries')))





* Visibility: **protected**
* This property is defined in classes\tax\TaxRule.php line 56


Methods
-------


### deleteByGroupId

    mixed TaxRuleCore::deleteByGroupId($id_group)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\TaxRule.php line 64


#### Arguments
* $id_group **mixed**



### retrieveById

    mixed TaxRuleCore::retrieveById($id_tax_rule)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\TaxRule.php line 76


#### Arguments
* $id_tax_rule **mixed**



### getTaxRulesByGroupId

    mixed TaxRuleCore::getTaxRulesByGroupId($id_lang, $id_group)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\TaxRule.php line 83


#### Arguments
* $id_lang **mixed**
* $id_group **mixed**



### deleteTaxRuleByIdTax

    mixed TaxRuleCore::deleteTaxRuleByIdTax($id_tax)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\TaxRule.php line 104


#### Arguments
* $id_tax **mixed**



### deleteTaxRuleByIdCounty

    mixed TaxRuleCore::deleteTaxRuleByIdCounty($id_county)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\TaxRule.php line 115


#### Arguments
* $id_county **mixed**



### isTaxInUse

    boolean TaxRuleCore::isTaxInUse(integer $id_tax)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\TaxRule.php line 125


#### Arguments
* $id_tax **integer**



### breakDownZipCode

    array TaxRuleCore::breakDownZipCode($zip_codes)





* Visibility: **public**
* This method is defined in classes\tax\TaxRule.php line 141


#### Arguments
* $zip_codes **mixed**



### swapTaxId

    mixed TaxRuleCore::swapTaxId(integer $old_id, integer $new_id)

Replace a tax_rule id by an other one in the tax_rule table



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\TaxRule.php line 171


#### Arguments
* $old_id **integer**
* $new_id **integer**


