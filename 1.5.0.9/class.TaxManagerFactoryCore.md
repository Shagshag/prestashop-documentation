Class TaxManagerFactoryCore
=====================





* Class name: TaxManagerFactoryCore
* Source: [classes/tax/TaxManagerFactory.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/tax/TaxManagerFactory.php#L31)


Contents
--------


### Properties

* [$cache_tax_manager](#property-$cache_tax_manager)

### Methods

* [execHookTaxManagerFactory](#method-execHookTaxManagerFactory)
* [getCacheKey](#method-getCacheKey)
* [getManager](#method-getManager)




Properties
----------


### <a name="property-$cache_tax_manager"></a>$cache_tax_manager

```php
protected mixed $cache_tax_manager
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/tax/TaxManagerFactory.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/tax/TaxManagerFactory.php#L33).


Methods
-------


### <a name="method-execHookTaxManagerFactory"></a>execHookTaxManagerFactory

```php
\TaxManager TaxManagerFactoryCore::execHookTaxManagerFactory(\Address $address, string $type)
```

Check for a tax manager able to handle this type of address in the module list



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxManagerFactory.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/tax/TaxManagerFactory.php#L66)


#### Arguments
* $address **[Address](class.AddressCore.md)**
* $type **string**



### <a name="method-getCacheKey"></a>getCacheKey

```php
mixed TaxManagerFactoryCore::getCacheKey(\Address $address)
```

Create a unique identifier for the address



* Visibility: **protected**
* This method is **static**.
* Source: [classes/tax/TaxManagerFactory.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/tax/TaxManagerFactory.php#L94)


#### Arguments
* $address **[Address](class.AddressCore.md)**



### <a name="method-getManager"></a>getManager

```php
\TaxManager TaxManagerFactoryCore::getManager(\Address $address, string $type)
```

Returns a tax manager able to handle this address



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxManagerFactory.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/classes/tax/TaxManagerFactory.php#L43)


#### Arguments
* $address **[Address](class.AddressCore.md)**
* $type **string**


