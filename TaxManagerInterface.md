TaxManagerInterface
===============

A TaxManager define a way to retrieve tax.




* Interface name: TaxManagerInterface
* Namespace: 
* This is an **interface**






Methods
-------


### isAvailableForThisAddress

    boolean TaxManagerInterface::isAvailableForThisAddress(\Address $address)

This method determine if the tax manager is available for the specified address.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $address **Address**



### getTaxCalculator

    \TaxCalculator TaxManagerInterface::getTaxCalculator()

Return the tax calculator associated to this address



* Visibility: **public**



