TaxManagerInterface
===============

A TaxManager define a way to retrieve tax.




* Interface name: TaxManagerInterface
* Namespace: 
* This is an **interface**
* This interface is defined in classes\tax\TaxManagerInterface.php line 31






Methods
-------


### isAvailableForThisAddress

    boolean TaxManagerInterface::isAvailableForThisAddress(\Address $address)

This method determine if the tax manager is available for the specified address.



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\tax\TaxManagerInterface.php line 40


#### Arguments
* $address **[Address](AddressCore)**



### getTaxCalculator

    \TaxCalculator TaxManagerInterface::getTaxCalculator()

Return the tax calculator associated to this address



* Visibility: **public**
* This method is defined in classes\tax\TaxManagerInterface.php line 47



