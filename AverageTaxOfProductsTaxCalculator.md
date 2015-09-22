AverageTaxOfProductsTaxCalculator
===============






* Class name: AverageTaxOfProductsTaxCalculator
* This class is defined in [classes/tax/AverageTaxOfProductsTaxCalculator.php line 3](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/AverageTaxOfProductsTaxCalculator.php#L3)





Properties
----------

* [$id_order](#property-$id_order)
* [$configuration](#property-$configuration)
* [$db](#property-$db)
* [$computation_method](#property-$computation_method)

Methods
-------
* [__construct](#method-__construct)
* [getProductTaxes](#method-getProductTaxes)
* [setIdOrder](#method-setIdOrder)
* [getTaxesAmount](#method-getTaxesAmount)




Properties
----------


### <a name="property-$id_order"></a>$id_order

    private mixed $id_order





* Visibility: **private**
* This property is defined in [classes/tax/AverageTaxOfProductsTaxCalculator.php line 5](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/AverageTaxOfProductsTaxCalculator.php#L5)


### <a name="property-$configuration"></a>$configuration

    private mixed $configuration





* Visibility: **private**
* This property is defined in [classes/tax/AverageTaxOfProductsTaxCalculator.php line 6](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/AverageTaxOfProductsTaxCalculator.php#L6)


### <a name="property-$db"></a>$db

    private mixed $db





* Visibility: **private**
* This property is defined in [classes/tax/AverageTaxOfProductsTaxCalculator.php line 7](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/AverageTaxOfProductsTaxCalculator.php#L7)


### <a name="property-$computation_method"></a>$computation_method

    public mixed $computation_method = 'average_tax_of_products'





* Visibility: **public**
* This property is defined in [classes/tax/AverageTaxOfProductsTaxCalculator.php line 9](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/AverageTaxOfProductsTaxCalculator.php#L9)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AverageTaxOfProductsTaxCalculator::__construct(\Core_Foundation_Database_DatabaseInterface $db, \Core_Business_ConfigurationInterface $configuration)





* Visibility: **public**
* This method is defined in [classes/tax/AverageTaxOfProductsTaxCalculator.php line 11](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/AverageTaxOfProductsTaxCalculator.php#L11)


#### Arguments
* $db **[Core_Foundation_Database_DatabaseInterface](Core_Foundation_Database_DatabaseInterface)**
* $configuration **[Core_Business_ConfigurationInterface](Core_Business_ConfigurationInterface)**



### <a name="method-getProductTaxes"></a>getProductTaxes

    mixed AverageTaxOfProductsTaxCalculator::getProductTaxes()





* Visibility: **private**
* This method is defined in [classes/tax/AverageTaxOfProductsTaxCalculator.php line 17](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/AverageTaxOfProductsTaxCalculator.php#L17)




### <a name="method-setIdOrder"></a>setIdOrder

    mixed AverageTaxOfProductsTaxCalculator::setIdOrder($id_order)





* Visibility: **public**
* This method is defined in [classes/tax/AverageTaxOfProductsTaxCalculator.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/AverageTaxOfProductsTaxCalculator.php#L30)


#### Arguments
* $id_order **mixed**



### <a name="method-getTaxesAmount"></a>getTaxesAmount

    mixed AverageTaxOfProductsTaxCalculator::getTaxesAmount($price_before_tax, $price_after_tax, $round_precision, $round_mode)





* Visibility: **public**
* This method is defined in [classes/tax/AverageTaxOfProductsTaxCalculator.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/AverageTaxOfProductsTaxCalculator.php#L36)


#### Arguments
* $price_before_tax **mixed**
* $price_after_tax **mixed**
* $round_precision **mixed**
* $round_mode **mixed**


