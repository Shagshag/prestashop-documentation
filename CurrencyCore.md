CurrencyCore
===============






* Class name: CurrencyCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/Currency.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#27)





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/Currency.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#29)


### $name

    public string $name





* Visibility: **public**
* This property is defined in [classes/Currency.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#32)


### $iso_code

    public string $iso_code





* Visibility: **public**
* This property is defined in [classes/Currency.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#35)


### $iso_code_num

    public string $iso_code_num





* Visibility: **public**
* This property is defined in [classes/Currency.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#38)


### $sign

    public string $sign





* Visibility: **public**
* This property is defined in [classes/Currency.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#41)


### $blank

    public integer $blank





* Visibility: **public**
* This property is defined in [classes/Currency.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#44)


### $conversion_rate

    public string $conversion_rate





* Visibility: **public**
* This property is defined in [classes/Currency.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#47)


### $deleted

    public boolean $deleted





* Visibility: **public**
* This property is defined in [classes/Currency.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#50)


### $format

    public integer $format





* Visibility: **public**
* This property is defined in [classes/Currency.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#53)


### $decimals

    public integer $decimals





* Visibility: **public**
* This property is defined in [classes/Currency.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#56)


### $active

    public integer $active





* Visibility: **public**
* This property is defined in [classes/Currency.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#59)


### $definition

    public mixed $definition = array('table' => 'currency', 'primary' => 'id_currency', 'multilang_shop' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageIsoCode', 'required' => true, 'size' => 3), 'iso_code_num' => array('type' => self::TYPE_STRING, 'validate' => 'isNumericIsoCode', 'size' => 3), 'blank' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'sign' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 8), 'format' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'decimals' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true, 'shop' => true), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Currency.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#64)


### $currencies

    protected array $currencies = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Currency.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#83)


### $countActiveCurrencies

    protected mixed $countActiveCurrencies = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Currency.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#84)


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'currencies')





* Visibility: **protected**
* This property is defined in [classes/Currency.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#86)


### $prefix

    public string $prefix = null

contains the sign to display before price, according to its format



* Visibility: **public**
* This property is defined in [classes/Currency.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#94)


### $suffix

    public string $suffix = null

contains the sign to display after price, according to its format



* Visibility: **public**
* This property is defined in [classes/Currency.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#99)


Methods
-------


### __construct

    mixed CurrencyCore::__construct($id, $id_lang, $id_shop)





* Visibility: **public**
* This method is defined in [classes/Currency.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#101)


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### add

    mixed CurrencyCore::add($autodate, $nullValues)

Overriding check if currency rate is not empty and if currency with the same iso code already exists.

If it's true, currency is not added.

* Visibility: **public**
* This method is defined in [classes/Currency.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#118)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### update

    mixed CurrencyCore::update($autodate, $nullValues)





* Visibility: **public**
* This method is defined in [classes/Currency.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#126)


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### exists

    boolean CurrencyCore::exists(integer|string $iso_code, $iso_code_num, $id_shop)

Check if a curency already exists.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#140)


#### Arguments
* $iso_code **integer|string** - &lt;p&gt;int for iso code number string for iso code&lt;/p&gt;
* $iso_code_num **mixed**
* $id_shop **mixed**



### deleteSelection

    mixed CurrencyCore::deleteSelection($selection)





* Visibility: **public**
* This method is defined in [classes/Currency.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#155)


#### Arguments
* $selection **mixed**



### delete

    mixed CurrencyCore::delete()





* Visibility: **public**
* This method is defined in [classes/Currency.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#175)




### getSign

    string CurrencyCore::getSign(string $side)

Return formated sign



* Visibility: **public**
* This method is defined in [classes/Currency.php line 194](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#194)


#### Arguments
* $side **string** - &lt;p&gt;left or right&lt;/p&gt;



### getCurrencies

    array CurrencyCore::getCurrencies($object, $active, $group_by)

Return available currencies



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#222)


#### Arguments
* $object **mixed**
* $active **mixed**
* $group_by **mixed**



### getCurrenciesByIdShop

    mixed CurrencyCore::getCurrenciesByIdShop($id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#240)


#### Arguments
* $id_shop **mixed**



### getPaymentCurrenciesSpecial

    mixed CurrencyCore::getPaymentCurrenciesSpecial($id_module, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 251](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#251)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### getPaymentCurrencies

    mixed CurrencyCore::getPaymentCurrencies($id_module, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#264)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### checkPaymentCurrencies

    mixed CurrencyCore::checkPaymentCurrencies($id_module, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 281](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#281)


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### getCurrency

    mixed CurrencyCore::getCurrency($id_currency)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 298](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#298)


#### Arguments
* $id_currency **mixed**



### getIdByIsoCode

    integer CurrencyCore::getIdByIsoCode($iso_code, integer $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 312](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#312)


#### Arguments
* $iso_code **mixed**
* $id_shop **integer**



### getIdByIsoCodeNum

    integer CurrencyCore::getIdByIsoCodeNum($iso_code_num, integer $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 331](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#331)


#### Arguments
* $iso_code_num **mixed**
* $id_shop **integer**



### getIdByQuery

    \DbQuery CurrencyCore::getIdByQuery(integer $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 343](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#343)


#### Arguments
* $id_shop **integer**



### refreshCurrency

    mixed CurrencyCore::refreshCurrency(\SimpleXMLElement $data, string $isoCodeSource, \Currency $defaultCurrency)

Refresh the currency exchange rate
The XML file define exchange rate for each from a default currency ($isoCodeSource).



* Visibility: **public**
* This method is defined in [classes/Currency.php line 365](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#365)


#### Arguments
* $data **SimpleXMLElement** - &lt;p&gt;XML content which contains all the exchange rates&lt;/p&gt;
* $isoCodeSource **string** - &lt;p&gt;The default currency used in the XML file&lt;/p&gt;
* $defaultCurrency **[Currency](CurrencyCore)** - &lt;p&gt;The default currency object&lt;/p&gt;



### getDefaultCurrency

    mixed CurrencyCore::getDefaultCurrency()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 403](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#403)




### refreshCurrencies

    mixed CurrencyCore::refreshCurrencies()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 413](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#413)




### getCurrent

    \Currency CurrencyCore::getCurrent()

Get current currency



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 442](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#442)




### getCurrencyInstance

    mixed CurrencyCore::getCurrencyInstance($id)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 448](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#448)


#### Arguments
* $id **mixed**



### getConversationRate

    mixed CurrencyCore::getConversationRate()





* Visibility: **public**
* This method is defined in [classes/Currency.php line 456](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#456)




### countActiveCurrencies

    mixed CurrencyCore::countActiveCurrencies($id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#461)


#### Arguments
* $id_shop **mixed**



### isMultiCurrencyActivated

    mixed CurrencyCore::isMultiCurrencyActivated($id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Currency.php line 477](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Currency.php#477)


#### Arguments
* $id_shop **mixed**


