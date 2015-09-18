TaxCore
===============






* Class name: TaxCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $name

    public string $name





* Visibility: **public**


### $rate

    public float $rate





* Visibility: **public**


### $active

    public boolean $active





* Visibility: **public**


### $deleted

    public boolean $deleted





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'tax', 'primary' => 'id_tax', 'multilang' => true, 'fields' => array('rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isFloat', 'required' => true), 'active' => array('type' => self::TYPE_BOOL), 'deleted' => array('type' => self::TYPE_BOOL), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 32)))





* Visibility: **public**
* This property is **static**.


### $_product_country_tax

    protected mixed $_product_country_tax = array()





* Visibility: **protected**
* This property is **static**.


### $_product_tax_via_rules

    protected mixed $_product_tax_via_rules = array()





* Visibility: **protected**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'taxes')





* Visibility: **protected**


Methods
-------


### delete

    mixed TaxCore::delete()





* Visibility: **public**




### historize

    mixed TaxCore::historize()

Save the object with the field deleted to true

@return bool

* Visibility: **public**




### toggleStatus

    mixed TaxCore::toggleStatus()





* Visibility: **public**




### update

    mixed TaxCore::update($null_values)





* Visibility: **public**


#### Arguments
* $null_values **mixed**



### _onStatusChange

    mixed TaxCore::_onStatusChange()





* Visibility: **protected**




### isUsed

    boolean TaxCore::isUsed()

Returns true if the tax is used in an order details



* Visibility: **public**




### getTaxes

    array TaxCore::getTaxes($id_lang, $active_only)

Get all available taxes



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_lang **mixed**
* $active_only **mixed**



### excludeTaxeOption

    mixed TaxCore::excludeTaxeOption()





* Visibility: **public**
* This method is **static**.




### getTaxIdByName

    mixed TaxCore::getTaxIdByName(string $tax_name, boolean $active)

Return the tax id associated to the specified name



* Visibility: **public**
* This method is **static**.


#### Arguments
* $tax_name **string**
* $active **boolean** - &lt;p&gt;(true by default)&lt;/p&gt;



### getProductEcotaxRate

    float TaxCore::getProductEcotaxRate($id_address)

Returns the ecotax tax rate



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_address **mixed**



### getCarrierTaxRate

    float TaxCore::getCarrierTaxRate($id_carrier, $id_address)

Returns the carrier tax rate



* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_carrier **mixed**
* $id_address **mixed**



### getProductTaxRateViaRules

    \Tax TaxCore::getProductTaxRateViaRules(integer $id_product, integer $id_country, $id_state, $zipcode)

Return the product tax rate using the tax rules system



* Visibility: **public**
* This method is **static**.


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


#### Arguments
* $id_product **integer**
* $id_address **mixed**
* $context **Context**


