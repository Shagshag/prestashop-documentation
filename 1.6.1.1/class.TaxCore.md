Class TaxCore
=====================





* Class name: TaxCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/tax/Tax.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L28)



Properties
----------

* [$_product_country_tax](#property-$_product_country_tax)
* [$_product_tax_via_rules](#property-$_product_tax_via_rules)
* [$active](#property-$active)
* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$name](#property-$name)
* [$rate](#property-$rate)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [_onStatusChange](#method-_onStatusChange)
* [delete](#method-delete)
* [excludeTaxeOption](#method-excludeTaxeOption)
* [getCarrierTaxRate](#method-getCarrierTaxRate)
* [getProductEcotaxRate](#method-getProductEcotaxRate)
* [getProductTaxRate](#method-getProductTaxRate)
* [getProductTaxRateViaRules](#method-getProductTaxRateViaRules)
* [getTaxIdByName](#method-getTaxIdByName)
* [getTaxes](#method-getTaxes)
* [historize](#method-historize)
* [isUsed](#method-isUsed)
* [toggleStatus](#method-toggleStatus)
* [update](#method-update)




Properties
----------


### <a name="property-$_product_country_tax"></a>$_product_country_tax

    protected mixed $_product_country_tax = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/tax/Tax.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L59).


### <a name="property-$_product_tax_via_rules"></a>$_product_tax_via_rules

    protected mixed $_product_tax_via_rules = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/tax/Tax.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L60).


### <a name="property-$active"></a>$active

    public boolean $active





* Visibility: **public**
* Source: [classes/tax/Tax.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L37).


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'tax', 'primary' => 'id_tax', 'multilang' => true, 'fields' => array('rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'active' => array('type' => self::TYPE_BOOL), 'deleted' => array('type' => self::TYPE_BOOL), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/tax/Tax.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L45).


### <a name="property-$deleted"></a>$deleted

    public boolean $deleted





* Visibility: **public**
* Source: [classes/tax/Tax.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L40).


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* Source: [classes/tax/Tax.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L31).


### <a name="property-$rate"></a>$rate

    public float $rate





* Visibility: **public**
* Source: [classes/tax/Tax.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L34).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'taxes')





* Visibility: **protected**
* Source: [classes/tax/Tax.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L62).


Methods
-------


### <a name="method-_onStatusChange"></a>_onStatusChange

    mixed TaxCore::_onStatusChange()





* Visibility: **protected**
* Source: [classes/tax/Tax.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L118)




### <a name="method-delete"></a>delete

    mixed TaxCore::delete()





* Visibility: **public**
* Source: [classes/tax/Tax.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L66)




### <a name="method-excludeTaxeOption"></a>excludeTaxeOption

    mixed TaxCore::excludeTaxeOption()





* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/Tax.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L166)




### <a name="method-getCarrierTaxRate"></a>getCarrierTaxRate

    float TaxCore::getCarrierTaxRate($id_carrier, $id_address)

Returns the carrier tax rate



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/Tax.php line 211](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L211)


#### Arguments
* $id_carrier **mixed**
* $id_address **mixed**



### <a name="method-getProductEcotaxRate"></a>getProductEcotaxRate

    float TaxCore::getProductEcotaxRate($id_address)

Returns the ecotax tax rate



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/Tax.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L195)


#### Arguments
* $id_address **mixed**



### <a name="method-getProductTaxRate"></a>getProductTaxRate

    \Tax TaxCore::getProductTaxRate(integer $id_product, $id_address, \Context $context)

Returns the product tax



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/Tax.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L250)


#### Arguments
* $id_product **integer**
* $id_address **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-getProductTaxRateViaRules"></a>getProductTaxRateViaRules

    \Tax TaxCore::getProductTaxRateViaRules(integer $id_product, integer $id_country, $id_state, $zipcode)

Return the product tax rate using the tax rules system



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/Tax.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L231)


#### Arguments
* $id_product **integer**
* $id_country **integer**
* $id_state **mixed**
* $zipcode **mixed**



### <a name="method-getTaxIdByName"></a>getTaxIdByName

    mixed TaxCore::getTaxIdByName(string $tax_name, boolean $active)

Return the tax id associated to the specified name



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/Tax.php line 177](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L177)


#### Arguments
* $tax_name **string**
* $active **boolean** - (true by default)



### <a name="method-getTaxes"></a>getTaxes

    array TaxCore::getTaxes($id_lang, $active_only)

Get all available taxes



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/Tax.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L146)


#### Arguments
* $id_lang **mixed**
* $active_only **mixed**



### <a name="method-historize"></a>historize

    mixed TaxCore::historize()

Save the object with the field deleted to true

@return bool

* Visibility: **public**
* Source: [classes/tax/Tax.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L83)




### <a name="method-isUsed"></a>isUsed

    boolean TaxCore::isUsed()

Returns true if the tax is used in an order details



* Visibility: **public**
* Source: [classes/tax/Tax.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L132)




### <a name="method-toggleStatus"></a>toggleStatus

    mixed TaxCore::toggleStatus()





* Visibility: **public**
* Source: [classes/tax/Tax.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L89)




### <a name="method-update"></a>update

    mixed TaxCore::update($null_values)





* Visibility: **public**
* Source: [classes/tax/Tax.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/Tax.php#L98)


#### Arguments
* $null_values **mixed**


