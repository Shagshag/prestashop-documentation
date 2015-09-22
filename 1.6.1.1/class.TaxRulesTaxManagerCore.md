Class TaxRulesTaxManagerCore
=====================





* Class name: TaxRulesTaxManagerCore
* Source: [classes/tax/TaxRulesTaxManager.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L30)
* This class implements: [TaxManagerInterface](interface.TaxManagerInterface.md)


Properties
----------

* [$address](#property-$address)
* [$configurationManager](#property-$configurationManager)
* [$tax_calculator](#property-$tax_calculator)
* [$type](#property-$type)

Methods
-------
* [__construct](#method-__construct)
* [getTaxCalculator](#method-getTaxCalculator)
* [isAvailableForThisAddress](#method-isAvailableForThisAddress)




Properties
----------


### <a name="property-$address"></a>$address

    public mixed $address





* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L32)


### <a name="property-$configurationManager"></a>$configurationManager

    private \Core_Business_ConfigurationInterface $configurationManager





* Visibility: **private**
* Source: [classes/tax/TaxRulesTaxManager.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L39)


### <a name="property-$tax_calculator"></a>$tax_calculator

    public mixed $tax_calculator





* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L34)


### <a name="property-$type"></a>$type

    public mixed $type





* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L33)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed TaxRulesTaxManagerCore::__construct(\Address $address, mixed $type, \Core_Business_ConfigurationInterface $configurationManager)





* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L46)


#### Arguments
* $address **[Address](class.AddressCore.md)**
* $type **mixed** - An additional parameter for the tax manager (ex: tax rules id for TaxRuleTaxManager)
* $configurationManager **Core_Business_ConfigurationInterface**



### <a name="method-getTaxCalculator"></a>getTaxCalculator

    \TaxCalculator TaxRulesTaxManagerCore::getTaxCalculator()

Return the tax calculator associated to this address



* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L73)




### <a name="method-isAvailableForThisAddress"></a>isAvailableForThisAddress

    boolean TaxRulesTaxManagerCore::isAvailableForThisAddress(\Address $address)

Returns true if this tax manager is available for this address



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesTaxManager.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#L63)


#### Arguments
* $address **[Address](class.AddressCore.md)**


