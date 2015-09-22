Class TaxManagerFactoryCore
=====================





* Class name: TaxManagerFactoryCore
* Source: [classes/tax/TaxManagerFactory.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxManagerFactory.php#L30)


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
* Source: [classes/tax/TaxManagerFactory.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxManagerFactory.php#L32).


Methods
-------


### <a name="method-execHookTaxManagerFactory"></a>execHookTaxManagerFactory

```php
\TaxManagerInterface|false TaxManagerFactoryCore::execHookTaxManagerFactory(\Address $address, string $type)
```

Check for a tax manager able to handle this type of address in the module list



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxManagerFactory.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxManagerFactory.php#L65)


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
* Source: [classes/tax/TaxManagerFactory.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxManagerFactory.php#L93)


#### Arguments
* $address **[Address](class.AddressCore.md)**



### <a name="method-getManager"></a>getManager

```php
\TaxManagerInterface TaxManagerFactoryCore::getManager(\Address $address, string $type)
```

Returns a tax manager able to handle this address



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxManagerFactory.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/tax/TaxManagerFactory.php#L42)


#### Arguments
* $address **[Address](class.AddressCore.md)**
* $type **string**


