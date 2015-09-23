Class CurrencyCore
=====================





* Class name: CurrencyCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Currency.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L27)


Contents
--------


### Properties

* [$active](#property-$active)
* [$blank](#property-$blank)
* [$conversion_rate](#property-$conversion_rate)
* [$countActiveCurrencies](#property-$countActiveCurrencies)
* [$currencies](#property-$currencies)
* [$decimals](#property-$decimals)
* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$format](#property-$format)
* [$id](#property-$id)
* [$iso_code](#property-$iso_code)
* [$iso_code_num](#property-$iso_code_num)
* [$name](#property-$name)
* [$prefix](#property-$prefix)
* [$sign](#property-$sign)
* [$suffix](#property-$suffix)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [__construct](#method-__construct)
* [add](#method-add)
* [checkPaymentCurrencies](#method-checkPaymentCurrencies)
* [countActiveCurrencies](#method-countActiveCurrencies)
* [delete](#method-delete)
* [deleteSelection](#method-deleteSelection)
* [exists](#method-exists)
* [getConversationRate](#method-getConversationRate)
* [getCurrencies](#method-getCurrencies)
* [getCurrenciesByIdShop](#method-getCurrenciesByIdShop)
* [getCurrency](#method-getCurrency)
* [getCurrencyInstance](#method-getCurrencyInstance)
* [getCurrent](#method-getCurrent)
* [getDefaultCurrency](#method-getDefaultCurrency)
* [getIdByIsoCode](#method-getIdByIsoCode)
* [getIdByIsoCodeNum](#method-getIdByIsoCodeNum)
* [getIdByQuery](#method-getIdByQuery)
* [getPaymentCurrencies](#method-getPaymentCurrencies)
* [getPaymentCurrenciesSpecial](#method-getPaymentCurrenciesSpecial)
* [getSign](#method-getSign)
* [isMultiCurrencyActivated](#method-isMultiCurrencyActivated)
* [refreshCurrencies](#method-refreshCurrencies)
* [refreshCurrency](#method-refreshCurrency)
* [update](#method-update)




Properties
----------


### <a name="property-$active"></a>$active

```php
public integer $active
```





* Visibility: **public**
* Source: [classes/Currency.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L59).


### <a name="property-$blank"></a>$blank

```php
public integer $blank
```





* Visibility: **public**
* Source: [classes/Currency.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L44).


### <a name="property-$conversion_rate"></a>$conversion_rate

```php
public string $conversion_rate
```





* Visibility: **public**
* Source: [classes/Currency.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L47).


### <a name="property-$countActiveCurrencies"></a>$countActiveCurrencies

```php
protected mixed $countActiveCurrencies = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Currency.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L84).


### <a name="property-$currencies"></a>$currencies

```php
protected array $currencies = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Currency.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L83).


### <a name="property-$decimals"></a>$decimals

```php
public integer $decimals
```





* Visibility: **public**
* Source: [classes/Currency.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L56).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'currency', 'primary' => 'id_currency', 'multilang_shop' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageIsoCode', 'required' => true, 'size' => 3), 'iso_code_num' => array('type' => self::TYPE_STRING, 'validate' => 'isNumericIsoCode', 'size' => 3), 'blank' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'sign' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 8), 'format' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'decimals' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true, 'shop' => true), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/Currency.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L64).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/Currency.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L50).


### <a name="property-$format"></a>$format

```php
public integer $format
```





* Visibility: **public**
* Source: [classes/Currency.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L53).


### <a name="property-$id"></a>$id

```php
public mixed $id
```





* Visibility: **public**
* Source: [classes/Currency.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L29).


### <a name="property-$iso_code"></a>$iso_code

```php
public string $iso_code
```





* Visibility: **public**
* Source: [classes/Currency.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L35).


### <a name="property-$iso_code_num"></a>$iso_code_num

```php
public string $iso_code_num
```





* Visibility: **public**
* Source: [classes/Currency.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L38).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/Currency.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L32).


### <a name="property-$prefix"></a>$prefix

```php
public string $prefix = null
```

contains the sign to display before price, according to its format



* Visibility: **public**
* Source: [classes/Currency.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L94).


### <a name="property-$sign"></a>$sign

```php
public string $sign
```





* Visibility: **public**
* Source: [classes/Currency.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L41).


### <a name="property-$suffix"></a>$suffix

```php
public string $suffix = null
```

contains the sign to display after price, according to its format



* Visibility: **public**
* Source: [classes/Currency.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L99).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'currencies')
```





* Visibility: **protected**
* Source: [classes/Currency.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L86).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CurrencyCore::__construct($id, $id_lang, $id_shop)
```





* Visibility: **public**
* Source: [classes/Currency.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L101)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-add"></a>add

```php
mixed CurrencyCore::add($autodate, $nullValues)
```

Overriding check if currency rate is not empty and if currency with the same iso code already exists.

If it's true, currency is not added.

* Visibility: **public**
* Source: [classes/Currency.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L117)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-checkPaymentCurrencies"></a>checkPaymentCurrencies

```php
mixed CurrencyCore::checkPaymentCurrencies($id_module, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L268)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-countActiveCurrencies"></a>countActiveCurrencies

```php
mixed CurrencyCore::countActiveCurrencies($id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 444](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L444)


#### Arguments
* $id_shop **mixed**



### <a name="method-delete"></a>delete

```php
mixed CurrencyCore::delete()
```





* Visibility: **public**
* Source: [classes/Currency.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L168)




### <a name="method-deleteSelection"></a>deleteSelection

```php
mixed CurrencyCore::deleteSelection($selection)
```





* Visibility: **public**
* Source: [classes/Currency.php line 150](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L150)


#### Arguments
* $selection **mixed**



### <a name="method-exists"></a>exists

```php
boolean CurrencyCore::exists(integer|string $iso_code, $iso_code_num, $id_shop)
```

Check if a curency already exists.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 137](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L137)


#### Arguments
* $iso_code **integer|string** - int for iso code number string for iso code
* $iso_code_num **mixed**
* $id_shop **mixed**



### <a name="method-getConversationRate"></a>getConversationRate

```php
mixed CurrencyCore::getConversationRate()
```





* Visibility: **public**
* Source: [classes/Currency.php line 439](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L439)




### <a name="method-getCurrencies"></a>getCurrencies

```php
array CurrencyCore::getCurrencies($object, $active, $group_by)
```

Return available currencies



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L213)


#### Arguments
* $object **mixed**
* $active **mixed**
* $group_by **mixed**



### <a name="method-getCurrenciesByIdShop"></a>getCurrenciesByIdShop

```php
mixed CurrencyCore::getCurrenciesByIdShop($id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L229)


#### Arguments
* $id_shop **mixed**



### <a name="method-getCurrency"></a>getCurrency

```php
mixed CurrencyCore::getCurrency($id_currency)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L283)


#### Arguments
* $id_currency **mixed**



### <a name="method-getCurrencyInstance"></a>getCurrencyInstance

```php
mixed CurrencyCore::getCurrencyInstance($id)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 432](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L432)


#### Arguments
* $id **mixed**



### <a name="method-getCurrent"></a>getCurrent

```php
\Currency CurrencyCore::getCurrent()
```

Get current currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 426](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L426)




### <a name="method-getDefaultCurrency"></a>getDefaultCurrency

```php
mixed CurrencyCore::getDefaultCurrency()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 393](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L393)




### <a name="method-getIdByIsoCode"></a>getIdByIsoCode

```php
integer CurrencyCore::getIdByIsoCode($iso_code, integer $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L298)


#### Arguments
* $iso_code **mixed**
* $id_shop **integer**



### <a name="method-getIdByIsoCodeNum"></a>getIdByIsoCodeNum

```php
integer CurrencyCore::getIdByIsoCodeNum($iso_code_num, integer $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L318)


#### Arguments
* $iso_code_num **mixed**
* $id_shop **integer**



### <a name="method-getIdByQuery"></a>getIdByQuery

```php
\DbQuery CurrencyCore::getIdByQuery(integer $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L331)


#### Arguments
* $id_shop **integer**



### <a name="method-getPaymentCurrencies"></a>getPaymentCurrencies

```php
mixed CurrencyCore::getPaymentCurrencies($id_module, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 252](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L252)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-getPaymentCurrenciesSpecial"></a>getPaymentCurrenciesSpecial

```php
mixed CurrencyCore::getPaymentCurrenciesSpecial($id_module, $id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L240)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-getSign"></a>getSign

```php
string CurrencyCore::getSign(string $side)
```

Return formated sign



* Visibility: **public**
* Source: [classes/Currency.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L187)


#### Arguments
* $side **string** - left or right



### <a name="method-isMultiCurrencyActivated"></a>isMultiCurrencyActivated

```php
mixed CurrencyCore::isMultiCurrencyActivated($id_shop)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 458](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L458)


#### Arguments
* $id_shop **mixed**



### <a name="method-refreshCurrencies"></a>refreshCurrencies

```php
mixed CurrencyCore::refreshCurrencies()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 402](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L402)




### <a name="method-refreshCurrency"></a>refreshCurrency

```php
mixed CurrencyCore::refreshCurrency($data, $isoCodeSource, $defaultCurrency)
```

Refresh the currency exchange rate
The XML file define exchange rate for each from a default currency ($isoCodeSource).



* Visibility: **public**
* Source: [classes/Currency.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L354)


#### Arguments
* $data **mixed** - XML content which contains all the exchange rates
* $isoCodeSource **mixed** - The default currency used in the XML file
* $defaultCurrency **mixed** - The default currency object



### <a name="method-update"></a>update

```php
mixed CurrencyCore::update($autodate, $nullValues)
```





* Visibility: **public**
* Source: [classes/Currency.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/Currency.php#L124)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**


