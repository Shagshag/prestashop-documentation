AverageTaxOfProductsTaxCalculator
===============






* Class name: AverageTaxOfProductsTaxCalculator
* Namespace: 





Properties
----------


### $id_order

    private mixed $id_order





* Visibility: **private**


### $configuration

    private mixed $configuration





* Visibility: **private**


### $db

    private mixed $db





* Visibility: **private**


### $computation_method

    public mixed $computation_method = 'average_tax_of_products'





* Visibility: **public**


Methods
-------


### __construct

    mixed AverageTaxOfProductsTaxCalculator::__construct(\Core_Foundation_Database_DatabaseInterface $db, \Core_Business_ConfigurationInterface $configuration)





* Visibility: **public**


#### Arguments
* $db **[Core_Foundation_Database_DatabaseInterface](Core_Foundation_Database_DatabaseInterface.md)**
* $configuration **[Core_Business_ConfigurationInterface](Core_Business_ConfigurationInterface.md)**



### getProductTaxes

    mixed AverageTaxOfProductsTaxCalculator::getProductTaxes()





* Visibility: **private**




### setIdOrder

    mixed AverageTaxOfProductsTaxCalculator::setIdOrder($id_order)





* Visibility: **public**


#### Arguments
* $id_order **mixed**



### getTaxesAmount

    mixed AverageTaxOfProductsTaxCalculator::getTaxesAmount($price_before_tax, $price_after_tax, $round_precision, $round_mode)





* Visibility: **public**


#### Arguments
* $price_before_tax **mixed**
* $price_after_tax **mixed**
* $round_precision **mixed**
* $round_mode **mixed**


