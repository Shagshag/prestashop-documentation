Class HTMLTemplateCore
=====================





* Class name: HTMLTemplateCore
* This is an **abstract** class
* Source: [classes/pdf/HTMLTemplate.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L30)



Properties
----------

* [$available_in_your_account](#property-$available_in_your_account)
* [$date](#property-$date)
* [$shop](#property-$shop)
* [$smarty](#property-$smarty)
* [$title](#property-$title)

Methods
-------
* [assignCommonHeaderData](#method-assignCommonHeaderData)
* [assignHookData](#method-assignHookData)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getFooter](#method-getFooter)
* [getHeader](#method-getHeader)
* [getLogo](#method-getLogo)
* [getShopAddress](#method-getShopAddress)
* [getTemplate](#method-getTemplate)
* [l](#method-l)
* [setShopId](#method-setShopId)




Properties
----------


### <a name="property-$available_in_your_account"></a>$available_in_your_account

    public mixed $available_in_your_account = true





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L34).


### <a name="property-$date"></a>$date

    public mixed $date





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L33).


### <a name="property-$shop"></a>$shop

    public \Shop $shop





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L40).


### <a name="property-$smarty"></a>$smarty

    public \Smarty $smarty





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L37).


### <a name="property-$title"></a>$title

    public mixed $title





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L32).


Methods
-------


### <a name="method-assignCommonHeaderData"></a>assignCommonHeaderData

    mixed HTMLTemplateCore::assignCommonHeaderData()

Assign common header data to smarty variables



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L115)




### <a name="method-assignHookData"></a>assignHookData

    mixed HTMLTemplateCore::assignHookData(\ObjectModel $object)

Assign hook data



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L155)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)** - generally the object used in the constructor



### <a name="method-getBulkFilename"></a>getBulkFilename

    string HTMLTemplateCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/pdf/HTMLTemplate.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L185)




### <a name="method-getContent"></a>getContent

    string HTMLTemplateCore::getContent()

Returns the template's HTML content



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/pdf/HTMLTemplate.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L170)




### <a name="method-getFilename"></a>getFilename

    string HTMLTemplateCore::getFilename()

Returns the template filename



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/pdf/HTMLTemplate.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L178)




### <a name="method-getFooter"></a>getFooter

    string HTMLTemplateCore::getFooter()

Returns the template's HTML footer



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L59)




### <a name="method-getHeader"></a>getHeader

    string HTMLTemplateCore::getHeader()

Returns the template's HTML header



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L47)




### <a name="method-getLogo"></a>getLogo

    mixed HTMLTemplateCore::getLogo()

Returns the invoice logo



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplate.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L97)




### <a name="method-getShopAddress"></a>getShopAddress

    string HTMLTemplateCore::getShopAddress()

Returns the shop address



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplate.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L82)




### <a name="method-getTemplate"></a>getTemplate

    string HTMLTemplateCore::getTemplate($template_name)

If the template is not present in the theme directory, it will return the default template
in _PS_PDF_DIR_ directory



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplate.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L195)


#### Arguments
* $template_name **mixed**



### <a name="method-l"></a>l

    string HTMLTemplateCore::l(string $string)

Translation method



* Visibility: **protected**
* This method is **static**.
* Source: [classes/pdf/HTMLTemplate.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L217)


#### Arguments
* $string **string**



### <a name="method-setShopId"></a>setShopId

    mixed HTMLTemplateCore::setShopId()





* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplate.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplate.php#L222)



