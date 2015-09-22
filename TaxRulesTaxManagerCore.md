TaxRulesTaxManagerCore
===============






* Class name: TaxRulesTaxManagerCore
* Namespace: 
* This class implements: [TaxManagerInterface](TaxManagerInterface)
* This class is defined in [classes/tax/TaxRulesTaxManager.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#30)





Properties
----------


### $address

    public mixed $address





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesTaxManager.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#32)


### $type

    public mixed $type





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesTaxManager.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#33)


### $tax_calculator

    public mixed $tax_calculator





* Visibility: **public**
* This property is defined in [classes/tax/TaxRulesTaxManager.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#34)


### $configurationManager

    private \Core_Business_ConfigurationInterface $configurationManager





* Visibility: **private**
* This property is defined in [classes/tax/TaxRulesTaxManager.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#39)


Methods
-------


### __construct

    mixed TaxRulesTaxManagerCore::__construct(\Address $address, mixed $type, \Core_Business_ConfigurationInterface $configurationManager)





* Visibility: **public**
* This method is defined in [classes/tax/TaxRulesTaxManager.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#46)


#### Arguments
* $address **[Address](AddressCore)**
* $type **mixed** - &lt;p&gt;An additional parameter for the tax manager (ex: tax rules id for TaxRuleTaxManager)&lt;/p&gt;
* $configurationManager **[Core_Business_ConfigurationInterface](Core_Business_ConfigurationInterface)**



### isAvailableForThisAddress

    boolean TaxManagerInterface::isAvailableForThisAddress(\Address $address)

This method determine if the tax manager is available for the specified address.



* Visibility: **public**
* This method is **static**.
* This method is defined by [TaxManagerInterface](TaxManagerInterface)
* This method is defined in [classes/tax/TaxRulesTaxManager.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#40)


#### Arguments
* $address **[Address](AddressCore)**



### getTaxCalculator

    \TaxCalculator TaxManagerInterface::getTaxCalculator()

Return the tax calculator associated to this address



* Visibility: **public**
* This method is defined by [TaxManagerInterface](TaxManagerInterface)
* This method is defined in [classes/tax/TaxRulesTaxManager.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxRulesTaxManager.php#47)



