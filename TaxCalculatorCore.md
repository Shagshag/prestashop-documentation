TaxCalculatorCore
===============






* Class name: TaxCalculatorCore
* This class is defined in [classes/tax/TaxCalculator.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxCalculator.php#L32)



Constants
----------

* [COMBINE_METHOD](#constant-COMBINE_METHOD)
* [ONE_AFTER_ANOTHER_METHOD](#constant-ONE_AFTER_ANOTHER_METHOD)

Properties
----------

* [$taxes](#property-$taxes)
* [$computation_method](#property-$computation_method)

Methods
-------
* [__construct](#method-__construct)
* [addTaxes](#method-addTaxes)
* [removeTaxes](#method-removeTaxes)
* [getTotalRate](#method-getTotalRate)
* [getTaxesName](#method-getTaxesName)
* [getTaxesAmount](#method-getTaxesAmount)
* [getTaxesTotalAmount](#method-getTaxesTotalAmount)


Constants
----------


### <a name="constant-COMBINE_METHOD"></a>COMBINE_METHOD

    const COMBINE_METHOD = 1



* This constant is defined in [classes/tax/TaxCalculator.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxCalculator.php#L38)


### <a name="constant-ONE_AFTER_ANOTHER_METHOD"></a>ONE_AFTER_ANOTHER_METHOD

    const ONE_AFTER_ANOTHER_METHOD = 2



* This constant is defined in [classes/tax/TaxCalculator.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxCalculator.php#L44)


Properties
----------


### <a name="property-$taxes"></a>$taxes

    public array $taxes





* Visibility: **public**
* This property is defined in [classes/tax/TaxCalculator.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxCalculator.php#L49)


### <a name="property-$computation_method"></a>$computation_method

    public integer $computation_method





* Visibility: **public**
* This property is defined in [classes/tax/TaxCalculator.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxCalculator.php#L54)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed TaxCalculatorCore::__construct(array $taxes, integer $computation_method)





* Visibility: **public**
* This method is defined in [classes/tax/TaxCalculator.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxCalculator.php#L61)


#### Arguments
* $taxes **array**
* $computation_method **integer** - &lt;p&gt;(COMBINE_METHOD | ONE_AFTER_ANOTHER_METHOD)&lt;/p&gt;



### <a name="method-addTaxes"></a>addTaxes

    float TaxCalculatorCore::addTaxes(float $price_te)

Compute and add the taxes to the specified price



* Visibility: **public**
* This method is defined in [classes/tax/TaxCalculator.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxCalculator.php#L80)


#### Arguments
* $price_te **float** - &lt;p&gt;price tax excluded&lt;/p&gt;



### <a name="method-removeTaxes"></a>removeTaxes

    float TaxCalculatorCore::removeTaxes(float $price_ti)

Compute and remove the taxes to the specified price



* Visibility: **public**
* This method is defined in [classes/tax/TaxCalculator.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxCalculator.php#L92)


#### Arguments
* $price_ti **float** - &lt;p&gt;price tax inclusive&lt;/p&gt;



### <a name="method-getTotalRate"></a>getTotalRate

    float TaxCalculatorCore::getTotalRate()





* Visibility: **public**
* This method is defined in [classes/tax/TaxCalculator.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxCalculator.php#L100)




### <a name="method-getTaxesName"></a>getTaxesName

    mixed TaxCalculatorCore::getTaxesName()





* Visibility: **public**
* This method is defined in [classes/tax/TaxCalculator.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxCalculator.php#L120)




### <a name="method-getTaxesAmount"></a>getTaxesAmount

    array TaxCalculatorCore::getTaxesAmount(float $price_te)

Return the tax amount associated to each taxes of the TaxCalculator



* Visibility: **public**
* This method is defined in [classes/tax/TaxCalculator.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxCalculator.php#L138)


#### Arguments
* $price_te **float**



### <a name="method-getTaxesTotalAmount"></a>getTaxesTotalAmount

    float TaxCalculatorCore::getTaxesTotalAmount(float $price_te)

Return the total taxes amount



* Visibility: **public**
* This method is defined in [classes/tax/TaxCalculator.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxCalculator.php#L160)


#### Arguments
* $price_te **float**


