TaxCore
===============






* Class name: TaxCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\tax\Tax.php line 28





Properties
----------


### $name

    public string $name





* Visibility: **public**
* This property is defined in classes\tax\Tax.php line 31


### $rate

    public float $rate





* Visibility: **public**
* This property is defined in classes\tax\Tax.php line 34


### $active

    public boolean $active





* Visibility: **public**
* This property is defined in classes\tax\Tax.php line 37


### $deleted

    public boolean $deleted





* Visibility: **public**
* This property is defined in classes\tax\Tax.php line 40


### $definition

    public mixed $definition = array('table' => 'tax', 'primary' => 'id_tax', 'multilang' => true, 'fields' => array('rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'active' => array('type' => self::TYPE_BOOL), 'deleted' => array('type' => self::TYPE_BOOL), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32)))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\tax\Tax.php line 45


### $_product_country_tax

    protected mixed $_product_country_tax = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\tax\Tax.php line 59


### $_product_tax_via_rules

    protected mixed $_product_tax_via_rules = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in classes\tax\Tax.php line 60


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'taxes')





* Visibility: **protected**
* This property is defined in classes\tax\Tax.php line 62


Methods
-------


### delete

    mixed TaxCore::delete()





* Visibility: **public**
* This method is defined in classes\tax\Tax.php line 66




### historize

    mixed TaxCore::historize()

Save the object with the field deleted to true

@return bool

* Visibility: **public**
* This method is defined in classes\tax\Tax.php line 83




### toggleStatus

    mixed TaxCore::toggleStatus()





* Visibility: **public**
* This method is defined in classes\tax\Tax.php line 89




### update

    mixed TaxCore::update($null_values)





* Visibility: **public**
* This method is defined in classes\tax\Tax.php line 98


#### Arguments
* $null_values **mixed**



### _onStatusChange

    mixed TaxCore::_onStatusChange()





* Visibility: **protected**
* This method is defined in classes\tax\Tax.php line 118




### isUsed

    boolean TaxCore::isUsed()

Returns true if the tax is used in an order details



* Visibility: **public**
* This method is defined in classes\tax\Tax.php line 132




### getTaxes

    array TaxCore::getTaxes($id_lang, $active_only)

Get all available taxes



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\Tax.php line 146


#### Arguments
* $id_lang **mixed**
* $active_only **mixed**



### excludeTaxeOption

    mixed TaxCore::excludeTaxeOption()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\Tax.php line 166




### getTaxIdByName

    mixed TaxCore::getTaxIdByName(string $tax_name, boolean $active)

Return the tax id associated to the specified name



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\Tax.php line 177


#### Arguments
* $tax_name **string**
* $active **boolean** - &lt;p&gt;(true by default)&lt;/p&gt;



### getProductEcotaxRate

    float TaxCore::getProductEcotaxRate($id_address)

Returns the ecotax tax rate



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\Tax.php line 195


#### Arguments
* $id_address **mixed**



### getCarrierTaxRate

    float TaxCore::getCarrierTaxRate($id_carrier, $id_address)

Returns the carrier tax rate



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\Tax.php line 211


#### Arguments
* $id_carrier **mixed**
* $id_address **mixed**



### getProductTaxRateViaRules

    \Tax TaxCore::getProductTaxRateViaRules(integer $id_product, integer $id_country, $id_state, $zipcode)

Return the product tax rate using the tax rules system



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\Tax.php line 231


#### Arguments
* $id_product **integer**
* $id_country **integer**
* $id_state **mixed**
* $zipcode **mixed**



### getProductTaxRate

    \Tax TaxCore::getProductTaxRate(integer $id_product, $id_address, \Context $context)

Returns the product tax



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\Tax.php line 250


#### Arguments
* $id_product **integer**
* $id_address **mixed**
* $context **[Context](ContextCore)**


