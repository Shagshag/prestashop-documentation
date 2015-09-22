Interface TaxManagerInterface
=========================

A TaxManager define a way to retrieve tax.



* Interface name: TaxManagerInterface
* This is an **interface**
* Source: [classes/tax/TaxManagerInterface.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxManagerInterface.php#L31)

Contents
--------



### Methods

* [getTaxCalculator](#method-getTaxCalculator)
* [isAvailableForThisAddress](#method-isAvailableForThisAddress)






Methods
-------


### <a name="method-getTaxCalculator"></a>getTaxCalculator

```php
\TaxCalculator TaxManagerInterface::getTaxCalculator()
```

Return the tax calculator associated to this address



* Visibility: **public**
* Source: [classes/tax/TaxManagerInterface.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxManagerInterface.php#L47)




### <a name="method-isAvailableForThisAddress"></a>isAvailableForThisAddress

```php
boolean TaxManagerInterface::isAvailableForThisAddress(\Address $address)
```

This method determine if the tax manager is available for the specified address.



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxManagerInterface.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/tax/TaxManagerInterface.php#L40)


#### Arguments
* $address **[Address](class.AddressCore.md)**


