Class TaxRulesTaxManagerCore
=====================





* Class name: TaxRulesTaxManagerCore
* Source: [classes/tax/TaxRulesTaxManager.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/tax/TaxRulesTaxManager.php#L30)
* This class implements: [TaxManagerInterface](interface.TaxManagerInterface.md)

Contents
--------


### Properties

* [$address](#property-$address)
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
* Source: [classes/tax/TaxRulesTaxManager.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/tax/TaxRulesTaxManager.php#L32).


### <a name="property-$tax_calculator"></a>$tax_calculator

```php
public mixed $tax_calculator
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/tax/TaxRulesTaxManager.php#L34).


### <a name="property-$type"></a>$type

```php
public mixed $type
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/tax/TaxRulesTaxManager.php#L33).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed TaxRulesTaxManagerCore::__construct(\Address $address, $type)
```





* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/tax/TaxRulesTaxManager.php#L41)


#### Arguments
* $address **[Address](class.AddressCore.md)**
* $type **mixed**



### <a name="method-getTaxCalculator"></a>getTaxCalculator

```php
\TaxCalculator TaxRulesTaxManagerCore::getTaxCalculator()
```

Return the tax calculator associated to this address



* Visibility: **public**
* Source: [classes/tax/TaxRulesTaxManager.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/tax/TaxRulesTaxManager.php#L62)




### <a name="method-isAvailableForThisAddress"></a>isAvailableForThisAddress

```php
boolean TaxRulesTaxManagerCore::isAvailableForThisAddress(\Address $address)
```

Returns true if this tax manager is available for this address



* Visibility: **public**
* This method is **static**.
* Source: [classes/tax/TaxRulesTaxManager.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.4/classes/tax/TaxRulesTaxManager.php#L52)


#### Arguments
* $address **[Address](class.AddressCore.md)**


