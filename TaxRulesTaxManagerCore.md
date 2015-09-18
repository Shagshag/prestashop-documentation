TaxRulesTaxManagerCore
===============






* Class name: TaxRulesTaxManagerCore
* Namespace: 
* This class implements: [TaxManagerInterface](TaxManagerInterface.md)




Properties
----------


### $address

    public mixed $address





* Visibility: **public**


### $type

    public mixed $type





* Visibility: **public**


### $tax_calculator

    public mixed $tax_calculator





* Visibility: **public**


### $configurationManager

    private \Core_Business_ConfigurationInterface $configurationManager





* Visibility: **private**


Methods
-------


### __construct

    mixed TaxRulesTaxManagerCore::__construct(\Address $address, mixed $type, \Core_Business_ConfigurationInterface $configurationManager)





* Visibility: **public**


#### Arguments
* $address **Address**
* $type **mixed** - &lt;p&gt;An additional parameter for the tax manager (ex: tax rules id for TaxRuleTaxManager)&lt;/p&gt;
* $configurationManager **[Core_Business_ConfigurationInterface](Core_Business_ConfigurationInterface.md)**



### isAvailableForThisAddress

    boolean TaxManagerInterface::isAvailableForThisAddress(\Address $address)

This method determine if the tax manager is available for the specified address.



* Visibility: **public**
* This method is **static**.
* This method is defined by [TaxManagerInterface](TaxManagerInterface.md)


#### Arguments
* $address **Address**



### getTaxCalculator

    \TaxCalculator TaxManagerInterface::getTaxCalculator()

Return the tax calculator associated to this address



* Visibility: **public**
* This method is defined by [TaxManagerInterface](TaxManagerInterface.md)



