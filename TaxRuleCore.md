TaxRuleCore
===============






* Class name: TaxRuleCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/tax/TaxRule.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L27)





Properties
----------

* [$id_tax_rules_group](#property-$id_tax_rules_group)
* [$id_country](#property-$id_country)
* [$id_state](#property-$id_state)
* [$zipcode_from](#property-$zipcode_from)
* [$zipcode_to](#property-$zipcode_to)
* [$id_tax](#property-$id_tax)
* [$behavior](#property-$behavior)
* [$description](#property-$description)
* [$definition](#property-$definition)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [deleteByGroupId](#method-deleteByGroupId)
* [retrieveById](#method-retrieveById)
* [getTaxRulesByGroupId](#method-getTaxRulesByGroupId)
* [deleteTaxRuleByIdTax](#method-deleteTaxRuleByIdTax)
* [deleteTaxRuleByIdCounty](#method-deleteTaxRuleByIdCounty)
* [isTaxInUse](#method-isTaxInUse)
* [breakDownZipCode](#method-breakDownZipCode)
* [swapTaxId](#method-swapTaxId)




Properties
----------


### <a name="property-$id_tax_rules_group"></a>$id_tax_rules_group

    public mixed $id_tax_rules_group





* Visibility: **public**
* This property is defined in [classes/tax/TaxRule.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L29)


### <a name="property-$id_country"></a>$id_country

    public mixed $id_country





* Visibility: **public**
* This property is defined in [classes/tax/TaxRule.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L30)


### <a name="property-$id_state"></a>$id_state

    public mixed $id_state





* Visibility: **public**
* This property is defined in [classes/tax/TaxRule.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L31)


### <a name="property-$zipcode_from"></a>$zipcode_from

    public mixed $zipcode_from





* Visibility: **public**
* This property is defined in [classes/tax/TaxRule.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L32)


### <a name="property-$zipcode_to"></a>$zipcode_to

    public mixed $zipcode_to





* Visibility: **public**
* This property is defined in [classes/tax/TaxRule.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L33)


### <a name="property-$id_tax"></a>$id_tax

    public mixed $id_tax





* Visibility: **public**
* This property is defined in [classes/tax/TaxRule.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L34)


### <a name="property-$behavior"></a>$behavior

    public mixed $behavior





* Visibility: **public**
* This property is defined in [classes/tax/TaxRule.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L35)


### <a name="property-$description"></a>$description

    public mixed $description





* Visibility: **public**
* This property is defined in [classes/tax/TaxRule.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L36)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'tax_rule', 'primary' => 'id_tax_rule', 'fields' => array('id_tax_rules_group' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_country' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'id_state' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId'), 'zipcode_from' => array('type' => self::TYPE_STRING, 'validate' => 'isPostCode'), 'zipcode_to' => array('type' => self::TYPE_STRING, 'validate' => 'isPostCode'), 'id_tax' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'behavior' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'description' => array('type' => self::TYPE_STRING, 'validate' => 'isString')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/tax/TaxRule.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L41)


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('fields' => array('id_tax_rules_group' => array('xlink_resource' => 'tax_rule_groups'), 'id_state' => array('xlink_resource' => 'states'), 'id_country' => array('xlink_resource' => 'countries')))





* Visibility: **protected**
* This property is defined in [classes/tax/TaxRule.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L56)


Methods
-------


### <a name="method-deleteByGroupId"></a>deleteByGroupId

    mixed TaxRuleCore::deleteByGroupId($id_group)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRule.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L64)


#### Arguments
* $id_group **mixed**



### <a name="method-retrieveById"></a>retrieveById

    mixed TaxRuleCore::retrieveById($id_tax_rule)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRule.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L76)


#### Arguments
* $id_tax_rule **mixed**



### <a name="method-getTaxRulesByGroupId"></a>getTaxRulesByGroupId

    mixed TaxRuleCore::getTaxRulesByGroupId($id_lang, $id_group)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRule.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L83)


#### Arguments
* $id_lang **mixed**
* $id_group **mixed**



### <a name="method-deleteTaxRuleByIdTax"></a>deleteTaxRuleByIdTax

    mixed TaxRuleCore::deleteTaxRuleByIdTax($id_tax)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRule.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L104)


#### Arguments
* $id_tax **mixed**



### <a name="method-deleteTaxRuleByIdCounty"></a>deleteTaxRuleByIdCounty

    mixed TaxRuleCore::deleteTaxRuleByIdCounty($id_county)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRule.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L115)


#### Arguments
* $id_county **mixed**



### <a name="method-isTaxInUse"></a>isTaxInUse

    boolean TaxRuleCore::isTaxInUse(integer $id_tax)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRule.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L125)


#### Arguments
* $id_tax **integer**



### <a name="method-breakDownZipCode"></a>breakDownZipCode

    array TaxRuleCore::breakDownZipCode($zip_codes)





* Visibility: **public**
* This method is defined in [classes/tax/TaxRule.php line 141](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L141)


#### Arguments
* $zip_codes **mixed**



### <a name="method-swapTaxId"></a>swapTaxId

    mixed TaxRuleCore::swapTaxId(integer $old_id, integer $new_id)

Replace a tax_rule id by an other one in the tax_rule table



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxRule.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRule.php#L171)


#### Arguments
* $old_id **integer**
* $new_id **integer**


