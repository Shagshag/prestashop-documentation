CurrencyCore
===============






* Class name: CurrencyCore
* Namespace: 
* Parent class: ObjectModel





Properties
----------


### $id

    public mixed $id





* Visibility: **public**


### $name

    public string $name





* Visibility: **public**


### $iso_code

    public string $iso_code





* Visibility: **public**


### $iso_code_num

    public string $iso_code_num





* Visibility: **public**


### $sign

    public string $sign





* Visibility: **public**


### $blank

    public integer $blank





* Visibility: **public**


### $conversion_rate

    public string $conversion_rate





* Visibility: **public**


### $deleted

    public boolean $deleted





* Visibility: **public**


### $format

    public integer $format





* Visibility: **public**


### $decimals

    public integer $decimals





* Visibility: **public**


### $active

    public integer $active





* Visibility: **public**


### $definition

    public mixed $definition = array('table' => 'currency', 'primary' => 'id_currency', 'multilang_shop' => true, 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 32), 'iso_code' => array('type' => self::TYPE_STRING, 'validate' => 'isLanguageIsoCode', 'required' => true, 'size' => 3), 'iso_code_num' => array('type' => self::TYPE_STRING, 'validate' => 'isNumericIsoCode', 'size' => 3), 'blank' => array('type' => self::TYPE_INT, 'validate' => 'isInt'), 'sign' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'required' => true, 'size' => 8), 'format' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedId', 'required' => true), 'decimals' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool', 'required' => true), 'conversion_rate' => array('type' => self::TYPE_FLOAT, 'validate' => 'isUnsignedFloat', 'required' => true, 'shop' => true), 'deleted' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'active' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool')))





* Visibility: **public**
* This property is **static**.


### $currencies

    protected array $currencies = array()





* Visibility: **protected**
* This property is **static**.


### $countActiveCurrencies

    protected mixed $countActiveCurrencies = array()





* Visibility: **protected**
* This property is **static**.


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectsNodeName' => 'currencies')





* Visibility: **protected**


### $prefix

    public string $prefix = null

contains the sign to display before price, according to its format



* Visibility: **public**


### $suffix

    public string $suffix = null

contains the sign to display after price, according to its format



* Visibility: **public**


Methods
-------


### __construct

    mixed CurrencyCore::__construct($id, $id_lang, $id_shop)





* Visibility: **public**


#### Arguments
* $id **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### add

    mixed CurrencyCore::add($autodate, $nullValues)

Overriding check if currency rate is not empty and if currency with the same iso code already exists.

If it's true, currency is not added.

* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### update

    mixed CurrencyCore::update($autodate, $nullValues)





* Visibility: **public**


#### Arguments
* $autodate **mixed**
* $nullValues **mixed**



### exists

    boolean CurrencyCore::exists(integer|string $iso_code, $iso_code_num, $id_shop)

Check if a curency already exists.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code **integer|string** - &lt;p&gt;int for iso code number string for iso code&lt;/p&gt;
* $iso_code_num **mixed**
* $id_shop **mixed**



### deleteSelection

    mixed CurrencyCore::deleteSelection($selection)





* Visibility: **public**


#### Arguments
* $selection **mixed**



### delete

    mixed CurrencyCore::delete()





* Visibility: **public**




### getSign

    string CurrencyCore::getSign(string $side)

Return formated sign



* Visibility: **public**


#### Arguments
* $side **string** - &lt;p&gt;left or right&lt;/p&gt;



### getCurrencies

    array CurrencyCore::getCurrencies($object, $active, $group_by)

Return available currencies



* Visibility: **public**
* This method is **static**.


#### Arguments
* $object **mixed**
* $active **mixed**
* $group_by **mixed**



### getCurrenciesByIdShop

    mixed CurrencyCore::getCurrenciesByIdShop($id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop **mixed**



### getPaymentCurrenciesSpecial

    mixed CurrencyCore::getPaymentCurrenciesSpecial($id_module, $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### getPaymentCurrencies

    mixed CurrencyCore::getPaymentCurrencies($id_module, $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### checkPaymentCurrencies

    mixed CurrencyCore::checkPaymentCurrencies($id_module, $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_module **mixed**
* $id_shop **mixed**



### getCurrency

    mixed CurrencyCore::getCurrency($id_currency)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_currency **mixed**



### getIdByIsoCode

    integer CurrencyCore::getIdByIsoCode($iso_code, integer $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code **mixed**
* $id_shop **integer**



### getIdByIsoCodeNum

    integer CurrencyCore::getIdByIsoCodeNum($iso_code_num, integer $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $iso_code_num **mixed**
* $id_shop **integer**



### getIdByQuery

    \DbQuery CurrencyCore::getIdByQuery(integer $id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop **integer**



### refreshCurrency

    mixed CurrencyCore::refreshCurrency(\SimpleXMLElement $data, string $isoCodeSource, \Currency $defaultCurrency)

Refresh the currency exchange rate
The XML file define exchange rate for each from a default currency ($isoCodeSource).



* Visibility: **public**


#### Arguments
* $data **SimpleXMLElement** - &lt;p&gt;XML content which contains all the exchange rates&lt;/p&gt;
* $isoCodeSource **string** - &lt;p&gt;The default currency used in the XML file&lt;/p&gt;
* $defaultCurrency **Currency** - &lt;p&gt;The default currency object&lt;/p&gt;



### getDefaultCurrency

    mixed CurrencyCore::getDefaultCurrency()





* Visibility: **public**
* This method is **static**.




### refreshCurrencies

    mixed CurrencyCore::refreshCurrencies()





* Visibility: **public**
* This method is **static**.




### getCurrent

    \Currency CurrencyCore::getCurrent()

Get current currency



* Visibility: **public**
* This method is **static**.




### getCurrencyInstance

    mixed CurrencyCore::getCurrencyInstance($id)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id **mixed**



### getConversationRate

    mixed CurrencyCore::getConversationRate()





* Visibility: **public**




### countActiveCurrencies

    mixed CurrencyCore::countActiveCurrencies($id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop **mixed**



### isMultiCurrencyActivated

    mixed CurrencyCore::isMultiCurrencyActivated($id_shop)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_shop **mixed**


