TaxCalculatorCore
===============






* Class name: TaxCalculatorCore
* Namespace: 
* This class is defined in classes\tax\TaxCalculator.php line 32



Constants
----------


### COMBINE_METHOD

    const COMBINE_METHOD = 1



* This constant is defined in classes\tax\TaxCalculator.php line 38


### ONE_AFTER_ANOTHER_METHOD

    const ONE_AFTER_ANOTHER_METHOD = 2



* This constant is defined in classes\tax\TaxCalculator.php line 44


Properties
----------


### $taxes

    public array $taxes





* Visibility: **public**
* This property is defined in classes\tax\TaxCalculator.php line 49


### $computation_method

    public integer $computation_method





* Visibility: **public**
* This property is defined in classes\tax\TaxCalculator.php line 54


Methods
-------


### __construct

    mixed TaxCalculatorCore::__construct(array $taxes, integer $computation_method)





* Visibility: **public**
* This method is defined in classes\tax\TaxCalculator.php line 61


#### Arguments
* $taxes **array**
* $computation_method **integer** - &lt;p&gt;(COMBINE_METHOD | ONE_AFTER_ANOTHER_METHOD)&lt;/p&gt;



### addTaxes

    float TaxCalculatorCore::addTaxes(float $price_te)

Compute and add the taxes to the specified price



* Visibility: **public**
* This method is defined in classes\tax\TaxCalculator.php line 80


#### Arguments
* $price_te **float** - &lt;p&gt;price tax excluded&lt;/p&gt;



### removeTaxes

    float TaxCalculatorCore::removeTaxes(float $price_ti)

Compute and remove the taxes to the specified price



* Visibility: **public**
* This method is defined in classes\tax\TaxCalculator.php line 92


#### Arguments
* $price_ti **float** - &lt;p&gt;price tax inclusive&lt;/p&gt;



### getTotalRate

    float TaxCalculatorCore::getTotalRate()





* Visibility: **public**
* This method is defined in classes\tax\TaxCalculator.php line 100




### getTaxesName

    mixed TaxCalculatorCore::getTaxesName()





* Visibility: **public**
* This method is defined in classes\tax\TaxCalculator.php line 120




### getTaxesAmount

    array TaxCalculatorCore::getTaxesAmount(float $price_te)

Return the tax amount associated to each taxes of the TaxCalculator



* Visibility: **public**
* This method is defined in classes\tax\TaxCalculator.php line 138


#### Arguments
* $price_te **float**



### getTaxesTotalAmount

    float TaxCalculatorCore::getTaxesTotalAmount(float $price_te)

Return the total taxes amount



* Visibility: **public**
* This method is defined in classes\tax\TaxCalculator.php line 160


#### Arguments
* $price_te **float**


