TaxManagerFactoryCore
===============






* Class name: TaxManagerFactoryCore
* Namespace: 





Properties
----------


### $cache_tax_manager

    protected mixed $cache_tax_manager





* Visibility: **protected**
* This property is **static**.


Methods
-------


### getManager

    \TaxManagerInterface TaxManagerFactoryCore::getManager(\Address $address, string $type)

Returns a tax manager able to handle this address



* Visibility: **public**
* This method is **static**.


#### Arguments
* $address **Address**
* $type **string**



### execHookTaxManagerFactory

    \TaxManagerInterface|false TaxManagerFactoryCore::execHookTaxManagerFactory(\Address $address, string $type)

Check for a tax manager able to handle this type of address in the module list



* Visibility: **public**
* This method is **static**.


#### Arguments
* $address **Address**
* $type **string**



### getCacheKey

    mixed TaxManagerFactoryCore::getCacheKey(\Address $address)

Create a unique identifier for the address



* Visibility: **protected**
* This method is **static**.


#### Arguments
* $address **Address**


