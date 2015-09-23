Class TaxCalculatorCore
=====================





* Class name: TaxCalculatorCore
* Source: [classes/tax/TaxCalculator.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/tax/TaxCalculator.php#L32)


Contents
--------

### Constants

* [COMBINE_METHOD](#constant-COMBINE_METHOD)
* [ONE_AFTER_ANOTHER_METHOD](#constant-ONE_AFTER_ANOTHER_METHOD)

### Properties

* [$computation_method](#property-$computation_method)
* [$taxes](#property-$taxes)

### Methods

* [__construct](#method-__construct)
* [addTaxes](#method-addTaxes)
* [getTaxesAmount](#method-getTaxesAmount)
* [getTaxesName](#method-getTaxesName)
* [getTotalRate](#method-getTotalRate)
* [removeTaxes](#method-removeTaxes)


Constants
----------


### <a name="constant-COMBINE_METHOD"></a>COMBINE_METHOD

```php
const COMBINE_METHOD = 1
```

COMBINE_METHOD sum taxes
eg: 100€ * (10% + 15%)



* Source: [classes/tax/TaxCalculator.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/tax/TaxCalculator.php#L38).


### <a name="constant-ONE_AFTER_ANOTHER_METHOD"></a>ONE_AFTER_ANOTHER_METHOD

```php
const ONE_AFTER_ANOTHER_METHOD = 2
```

ONE_AFTER_ANOTHER_METHOD apply taxes one after another
eg: (100€ * 10%) * 15%



* Source: [classes/tax/TaxCalculator.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/tax/TaxCalculator.php#L44).


Properties
----------


### <a name="property-$computation_method"></a>$computation_method

```php
public integer $computation_method
```





* Visibility: **public**
* Source: [classes/tax/TaxCalculator.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/tax/TaxCalculator.php#L54).


### <a name="property-$taxes"></a>$taxes

```php
public array $taxes
```





* Visibility: **public**
* Source: [classes/tax/TaxCalculator.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/tax/TaxCalculator.php#L49).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed TaxCalculatorCore::__construct(array $taxes, integer $computation_method)
```





* Visibility: **public**
* Source: [classes/tax/TaxCalculator.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/tax/TaxCalculator.php#L61)


#### Arguments
* $taxes **array**
* $computation_method **integer** - (COMBINE_METHOD | ONE_AFTER_ANOTHER_METHOD)



### <a name="method-addTaxes"></a>addTaxes

```php
float TaxCalculatorCore::addTaxes($price_te)
```

Compute and add the taxes to the specified price



* Visibility: **public**
* Source: [classes/tax/TaxCalculator.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/tax/TaxCalculator.php#L78)


#### Arguments
* $price_te **mixed**



### <a name="method-getTaxesAmount"></a>getTaxesAmount

```php
array TaxCalculatorCore::getTaxesAmount(float $price_te)
```

Return the tax amount associated to each taxes of the TaxCalculator



* Visibility: **public**
* Source: [classes/tax/TaxCalculator.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/tax/TaxCalculator.php#L136)


#### Arguments
* $price_te **float**



### <a name="method-getTaxesName"></a>getTaxesName

```php
mixed TaxCalculatorCore::getTaxesName()
```





* Visibility: **public**
* Source: [classes/tax/TaxCalculator.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/tax/TaxCalculator.php#L119)




### <a name="method-getTotalRate"></a>getTotalRate

```php
float TaxCalculatorCore::getTotalRate()
```





* Visibility: **public**
* Source: [classes/tax/TaxCalculator.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/tax/TaxCalculator.php#L98)




### <a name="method-removeTaxes"></a>removeTaxes

```php
\price TaxCalculatorCore::removeTaxes($price_ti)
```

Compute and remove the taxes to the specified price



* Visibility: **public**
* Source: [classes/tax/TaxCalculator.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.1/classes/tax/TaxCalculator.php#L90)


#### Arguments
* $price_ti **mixed**


