TaxRulesTaxManagerCore
===============






* Class name: TaxRulesTaxManagerCore
* This class is defined in [classes/tax/TaxRulesTaxManager.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L30)
* This class implements: [TaxManagerInterface](TaxManagerInterface)




Properties
----------

* [$address](#property-$address)
* [$type](#property-$type)
* [$tax_calculator](#property-$tax_calculator)
* [$configurationManager](#property-$configurationManager)

Methods
-------
* [__construct](#method-__construct)
* [isAvailableForThisAddress](#method-isAvailableForThisAddress)
* [getTaxCalculator](#method-getTaxCalculator)




Properties
----------


### <a name="property-$address"></a>$address

    public mixed $address





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesTaxManager.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L32)


### <a name="property-$type"></a>$type

    public mixed $type





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesTaxManager.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L33)


### <a name="property-$tax_calculator"></a>$tax_calculator

    public mixed $tax_calculator





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesTaxManager.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L34)


### <a name="property-$configurationManager"></a>$configurationManager

    private \Core_Business_ConfigurationInterface $configurationManager





* Visibility: **private**
* This property is defined in [classes/tax/TaxRulesTaxManager.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L39)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed TaxRulesTaxManagerCore::__construct(\Address $address, mixed $type, \Core_Business_ConfigurationInterface $configurationManager)





* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesTaxManager.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L46)


#### Arguments
* $address **[Address](AddressCore)**
* $type **mixed** - &lt;p&gt;An additional parameter for the tax manager (ex: tax rules id for TaxRuleTaxManager)&lt;/p&gt;
* $configurationManager **[Core_Business_ConfigurationInterface](Core_Business_ConfigurationInterface)**



### <a name="method-isAvailableForThisAddress"></a>isAvailableForThisAddress

    boolean TaxManagerInterface::isAvailableForThisAddress(\Address $address)

This method determine if the tax manager is available for the specified address.



* Visibility: **public**
* This method is **static**.
* This method is defined by [TaxManagerInterface](TaxManagerInterface)
* This method is defined in [classes/tax/TaxRulesTaxManager.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L40)


#### Arguments
* $address **[Address](AddressCore)**



### <a name="method-getTaxCalculator"></a>getTaxCalculator

    \TaxCalculator TaxManagerInterface::getTaxCalculator()

Return the tax calculator associated to this address



* Visibility: **public**
* This method is defined by [TaxManagerInterface](TaxManagerInterface)
* This method is defined in [classes/tax/TaxRulesTaxManager.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L47)



