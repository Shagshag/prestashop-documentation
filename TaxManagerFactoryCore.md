TaxManagerFactoryCore
===============






* Class name: TaxManagerFactoryCore
* This class is defined in [classes/tax/TaxManagerFactory.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxManagerFactory.php#L30)





Properties
----------


### $cache_tax_manager

    protected mixed $cache_tax_manager





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/tax/TaxManagerFactory.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxManagerFactory.php#32)


Methods
-------


### getManager

    \TaxManagerInterface TaxManagerFactoryCore::getManager(\Address $address, string $type)

Returns a tax manager able to handle this address



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxManagerFactory.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxManagerFactory.php#42)


#### Arguments
* $address **[Address](AddressCore)**
* $type **string**



### execHookTaxManagerFactory

    \TaxManagerInterface|false TaxManagerFactoryCore::execHookTaxManagerFactory(\Address $address, string $type)

Check for a tax manager able to handle this type of address in the module list



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/tax/TaxManagerFactory.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxManagerFactory.php#65)


#### Arguments
* $address **[Address](AddressCore)**
* $type **string**



### getCacheKey

    mixed TaxManagerFactoryCore::getCacheKey(\Address $address)

Create a unique identifier for the address



* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/tax/TaxManagerFactory.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxManagerFactory.php#92)


#### Arguments
* $address **[Address](AddressCore)**


