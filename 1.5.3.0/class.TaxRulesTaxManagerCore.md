Class TaxRulesTaxManagerCore
=====================





* Class name: TaxRulesTaxManagerCore
* Source: [classes/tax/TaxRulesTaxManager.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/tax/TaxRulesTaxManager.php#L30)
* This class implements: [TaxManagerInterface](interface.TaxManagerInterface.md)

Contents
--------


### Properties

* [$address](#property-$address)
* [$cache_tax_calculator](#property-$cache_tax_calculator)
* [$tax_calculator](#property-$tax_calculator)
* [$type](#property-$type)

### Methods

* [__construct](#method-__construct)
* [getTaxCalculator](#method-getTaxCalculator)
* [isAvailableForThisAddress](#method-isAvailableForThisAddress)




Properties
----------


### <a name="property-$address"></a>$address

```php
public mixed $address
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/tax/TaxRulesTaxManager.php#L32).


### <a name="property-$cache_tax_calculator"></a>$cache_tax_calculator

```php
protected mixed $cache_tax_calculator
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/tax/TaxRulesTaxManager.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/tax/TaxRulesTaxManager.php#L36).


### <a name="property-$tax_calculator"></a>$tax_calculator

```php
public mixed $tax_calculator
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/tax/TaxRulesTaxManager.php#L34).


### <a name="property-$type"></a>$type

```php
public mixed $type
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/tax/TaxRulesTaxManager.php#L33).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed TaxRulesTaxManagerCore::__construct(\Address $address, $type)
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/tax/TaxRulesTaxManager.php#L44)


#### Arguments
* $address **[Address](class.AddressCore.md)**
* $type **mixed**



### <a name="method-getTaxCalculator"></a>getTaxCalculator

```php
\TaxCalculator TaxRulesTaxManagerCore::getTaxCalculator()
```

Return the tax calculator associated to this address



* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/tax/TaxRulesTaxManager.php#L65)




### <a name="method-isAvailableForThisAddress"></a>isAvailableForThisAddress

```php
boolean TaxRulesTaxManagerCore::isAvailableForThisAddress(\Address $address)
```

Returns true if this tax manager is available for this address



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesTaxManager.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/tax/TaxRulesTaxManager.php#L55)


#### Arguments
* $address **[Address](class.AddressCore.md)**


