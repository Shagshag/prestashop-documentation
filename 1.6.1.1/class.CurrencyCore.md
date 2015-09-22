Class CurrencyCore
=====================





* Class name: CurrencyCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/Currency.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L27)



Properties
----------

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

Methods
-------
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

    public integer $active





* Visibility: **public**
* Source: [classes/Currency.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L59).


### <a name="property-$blank"></a>$blank

    public integer $blank





* Visibility: **public**
* Source: [classes/Currency.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L44).


### <a name="property-$conversion_rate"></a>$conversion_rate

    public string $conversion_rate





* Visibility: **public**
* Source: [classes/Currency.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L47).


### <a name="property-$countActiveCurrencies"></a>$countActiveCurrencies

    protected mixed $countActiveCurrencies = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Currency.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L84).


### <a name="property-$currencies"></a>$currencies

    protected array $currencies = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Currency.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L83).


### <a name="property-$decimals"></a>$decimals

    public integer $decimals





* Visibility: **public**
* Source: [classes/Currency.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L56).


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'currency', 'primary' => 'id_currency', 'multilang_shop' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageIsoCode', 'required' => true, 'size' => 3), 'iso_code_num' => array('type' => self::TYPE_STRING, 'validate' => 'isNumericIsoCode', 'size' => 3), 'blank' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'sign' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 8), 'format' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'decimals' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true, 'shop' => true), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* Source: [classes/Currency.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L64).


### <a name="property-$deleted"></a>$deleted

    public boolean $deleted





* Visibility: **public**
* Source: [classes/Currency.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L50).


### <a name="property-$format"></a>$format

    public integer $format





* Visibility: **public**
* Source: [classes/Currency.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L53).


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* Source: [classes/Currency.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L29).


### <a name="property-$iso_code"></a>$iso_code

    public string $iso_code





* Visibility: **public**
* Source: [classes/Currency.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L35).


### <a name="property-$iso_code_num"></a>$iso_code_num

    public string $iso_code_num





* Visibility: **public**
* Source: [classes/Currency.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L38).


### <a name="property-$name"></a>$name

    public string $name





* Visibility: **public**
* Source: [classes/Currency.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L32).


### <a name="property-$prefix"></a>$prefix

    public string $prefix = null

contains the sign to display before price, according to its format



* Visibility: **public**
* Source: [classes/Currency.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L94).


### <a name="property-$sign"></a>$sign

    public string $sign





* Visibility: **public**
* Source: [classes/Currency.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L41).


### <a name="property-$suffix"></a>$suffix

    public string $suffix = null

contains the sign to display after price, according to its format



* Visibility: **public**
* Source: [classes/Currency.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L99).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'currencies')





* Visibility: **protected**
* Source: [classes/Currency.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L86).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed CurrencyCore::__construct($id, $id_lang, $id_shop)





* Visibility: **public**
* Source: [classes/Currency.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L101)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-add"></a>add

    mixed CurrencyCore::add($autodate, $nullValues)

Overriding check if currency rate is not empty and if currency with the same iso code already exists.

If it's true, currency is not added.

* Visibility: **public**
* Source: [classes/Currency.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L118)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### <a name="method-checkPaymentCurrencies"></a>checkPaymentCurrencies

    mixed CurrencyCore::checkPaymentCurrencies($id_module, $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L281)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-countActiveCurrencies"></a>countActiveCurrencies

    mixed CurrencyCore::countActiveCurrencies($id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L461)


#### Arguments
* $id_shop **mixed**



### <a name="method-delete"></a>delete

    mixed CurrencyCore::delete()





* Visibility: **public**
* Source: [classes/Currency.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L175)




### <a name="method-deleteSelection"></a>deleteSelection

    mixed CurrencyCore::deleteSelection($selection)





* Visibility: **public**
* Source: [classes/Currency.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L155)


#### Arguments
* $selection **mixed**



### <a name="method-exists"></a>exists

    boolean CurrencyCore::exists(integer|string $iso_code, $iso_code_num, $id_shop)

Check if a curency already exists.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L140)


#### Arguments
* $iso_code **integer|string** - int for iso code number string for iso code
* $iso_code_num **mixed**
* $id_shop **mixed**



### <a name="method-getConversationRate"></a>getConversationRate

    mixed CurrencyCore::getConversationRate()





* Visibility: **public**
* Source: [classes/Currency.php line 456](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L456)




### <a name="method-getCurrencies"></a>getCurrencies

    array CurrencyCore::getCurrencies($object, $active, $group_by)

Return available currencies



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L222)


#### Arguments
* $object **mixed**
* $active **mixed**
* $group_by **mixed**



### <a name="method-getCurrenciesByIdShop"></a>getCurrenciesByIdShop

    mixed CurrencyCore::getCurrenciesByIdShop($id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L240)


#### Arguments
* $id_shop **mixed**



### <a name="method-getCurrency"></a>getCurrency

    mixed CurrencyCore::getCurrency($id_currency)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L298)


#### Arguments
* $id_currency **mixed**



### <a name="method-getCurrencyInstance"></a>getCurrencyInstance

    mixed CurrencyCore::getCurrencyInstance($id)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 448](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L448)


#### Arguments
* $id **mixed**



### <a name="method-getCurrent"></a>getCurrent

    \Currency CurrencyCore::getCurrent()

Get current currency



* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 442](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L442)




### <a name="method-getDefaultCurrency"></a>getDefaultCurrency

    mixed CurrencyCore::getDefaultCurrency()





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 403](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L403)




### <a name="method-getIdByIsoCode"></a>getIdByIsoCode

    integer CurrencyCore::getIdByIsoCode($iso_code, integer $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L312)


#### Arguments
* $iso_code **mixed**
* $id_shop **integer**



### <a name="method-getIdByIsoCodeNum"></a>getIdByIsoCodeNum

    integer CurrencyCore::getIdByIsoCodeNum($iso_code_num, integer $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L331)


#### Arguments
* $iso_code_num **mixed**
* $id_shop **integer**



### <a name="method-getIdByQuery"></a>getIdByQuery

    \DbQuery CurrencyCore::getIdByQuery(integer $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 343](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L343)


#### Arguments
* $id_shop **integer**



### <a name="method-getPaymentCurrencies"></a>getPaymentCurrencies

    mixed CurrencyCore::getPaymentCurrencies($id_module, $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L264)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-getPaymentCurrenciesSpecial"></a>getPaymentCurrenciesSpecial

    mixed CurrencyCore::getPaymentCurrenciesSpecial($id_module, $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L251)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### <a name="method-getSign"></a>getSign

    string CurrencyCore::getSign(string $side)

Return formated sign



* Visibility: **public**
* Source: [classes/Currency.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L194)


#### Arguments
* $side **string** - left or right



### <a name="method-isMultiCurrencyActivated"></a>isMultiCurrencyActivated

    mixed CurrencyCore::isMultiCurrencyActivated($id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 477](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L477)


#### Arguments
* $id_shop **mixed**



### <a name="method-refreshCurrencies"></a>refreshCurrencies

    mixed CurrencyCore::refreshCurrencies()





* Visibility: **public**
* This method is **static**.
* Source: [classes/Currency.php line 413](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L413)




### <a name="method-refreshCurrency"></a>refreshCurrency

    mixed CurrencyCore::refreshCurrency(\SimpleXMLElement $data, string $isoCodeSource, \Currency $defaultCurrency)

Refresh the currency exchange rate
The XML file define exchange rate for each from a default currency ($isoCodeSource).



* Visibility: **public**
* Source: [classes/Currency.php line 365](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L365)


#### Arguments
* $data **SimpleXMLElement** - XML content which contains all the exchange rates
* $isoCodeSource **string** - The default currency used in the XML file
* $defaultCurrency **[Currency](class.CurrencyCore.md)** - The default currency object



### <a name="method-update"></a>update

    mixed CurrencyCore::update($autodate, $nullValues)





* Visibility: **public**
* Source: [classes/Currency.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#L126)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**


