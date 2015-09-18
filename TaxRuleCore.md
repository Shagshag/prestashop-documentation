TaxRuleCore
===============






* Class name: TaxRuleCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id_tax_rules_group

    public mixed $id_tax_rules_group





* Visibility: **public**


### $id_country

    public mixed $id_country





* Visibility: **public**


### $id_state

    public mixed $id_state





* Visibility: **public**


### $zipcode_from

    public mixed $zipcode_from





* Visibility: **public**


### $zipcode_to

    public mixed $zipcode_to





* Visibility: **public**


### $id_tax

    public mixed $id_tax





* Visibility: **public**


### $behavior

    public mixed $behavior





* Visibility: **public**


### $description

    public mixed $description





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'tax_rule', 'primary' => 'id_tax_rule', 'fields' => array('id_tax_rules_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'zipcode_from' => array('type' => self::TYPE_STRING, 'validate' => 'isPostCode'), 'zipcode_to' => array('type' => self::TYPE_STRING, 'validate' => 'isPostCode'), 'id_tax' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'behavior' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'description' => array('type' => self::TYPE_STRING, 'validate' => 'isString')))





* Visibility: **public**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_tax_rules_group' => array('xlink_resource' => 'tax_rule_groups'), 'id_state' => array('xlink_resource' => 'states'), 'id_country' => array('xlink_resource' => 'countries')))





* Visibility: **protected**


Methods
-------


### deleteByGroupId

    mixed TaxRuleCore::deleteByGroupId($id_group)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_group **mixed**



### retrieveById

    mixed TaxRuleCore::retrieveById($id_tax_rule)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_tax_rule **mixed**



### getTaxRulesByGroupId

    mixed TaxRuleCore::getTaxRulesByGroupId($id_lang, $id_group)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $id_group **mixed**



### deleteTaxRuleByIdTax

    mixed TaxRuleCore::deleteTaxRuleByIdTax($id_tax)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_tax **mixed**



### deleteTaxRuleByIdCounty

    mixed TaxRuleCore::deleteTaxRuleByIdCounty($id_county)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_county **mixed**



### isTaxInUse

    boolean TaxRuleCore::isTaxInUse(integer $id_tax)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_tax **integer**



### breakDownZipCode

    array TaxRuleCore::breakDownZipCode($zip_codes)





* Visibility: **public**


#### Arguments
* $zip_codes **mixed**



### swapTaxId

    mixed TaxRuleCore::swapTaxId(integer $old_id, integer $new_id)

Replace a tax_rule id by an other one in the tax_rule table



* Visibility: **public**
* This method is **static**.


#### Arguments
* $old_id **integer**
* $new_id **integer**


