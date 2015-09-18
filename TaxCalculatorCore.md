TaxCalculatorCore
===============






* Class name: TaxCalculatorCore
* Namespace: 



Constants
----------


### COMBINE_METHOD

    const COMBINE_METHOD = 1





### ONE_AFTER_ANOTHER_METHOD

    const ONE_AFTER_ANOTHER_METHOD = 2





Properties
----------


### $taxes

    public array $taxes





* Visibility: **public**


### $computation_method

    public integer $computation_method





* Visibility: **public**


Methods
-------


### __construct

    mixed TaxCalculatorCore::__construct(array $taxes, integer $computation_method)





* Visibility: **public**


#### Arguments
* $taxes **array**
* $computation_method **integer** - &lt;p&gt;(COMBINE_METHOD | ONE_AFTER_ANOTHER_METHOD)&lt;/p&gt;



### addTaxes

    float TaxCalculatorCore::addTaxes(float $price_te)

Compute and add the taxes to the specified price



* Visibility: **public**


#### Arguments
* $price_te **float** - &lt;p&gt;price tax excluded&lt;/p&gt;



### removeTaxes

    float TaxCalculatorCore::removeTaxes(float $price_ti)

Compute and remove the taxes to the specified price



* Visibility: **public**


#### Arguments
* $price_ti **float** - &lt;p&gt;price tax inclusive&lt;/p&gt;



### getTotalRate

    float TaxCalculatorCore::getTotalRate()





* Visibility: **public**




### getTaxesName

    mixed TaxCalculatorCore::getTaxesName()





* Visibility: **public**




### getTaxesAmount

    array TaxCalculatorCore::getTaxesAmount(float $price_te)

Return the tax amount associated to each taxes of the TaxCalculator



* Visibility: **public**


#### Arguments
* $price_te **float**



### getTaxesTotalAmount

    float TaxCalculatorCore::getTaxesTotalAmount(float $price_te)

Return the total taxes amount



* Visibility: **public**


#### Arguments
* $price_te **float**


