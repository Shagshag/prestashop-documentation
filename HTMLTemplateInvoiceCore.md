HTMLTemplateInvoiceCore
===============






* Class name: HTMLTemplateInvoiceCore
* Parent class: [HTMLTemplate](HTMLTemplateCore)
* This class is defined in [classes/pdf/HTMLTemplateInvoice.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#L30)





Properties
----------

* [$order](#property-$order)
* [$order_invoice](#property-$order_invoice)
* [$available_in_your_account](#property-$available_in_your_account)

Methods
-------
* [__construct](#method-__construct)
* [getHeader](#method-getHeader)
* [computeLayout](#method-computeLayout)
* [getContent](#method-getContent)
* [getTaxTabContent](#method-getTaxTabContent)
* [getTaxBreakdown](#method-getTaxBreakdown)
* [getTemplateByCountry](#method-getTemplateByCountry)
* [getBulkFilename](#method-getBulkFilename)
* [getFilename](#method-getFilename)




Properties
----------


### <a name="property-$order"></a>$order

    public mixed $order





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateInvoice.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#L32)


### <a name="property-$order_invoice"></a>$order_invoice

    public mixed $order_invoice





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateInvoice.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#L33)


### <a name="property-$available_in_your_account"></a>$available_in_your_account

    public mixed $available_in_your_account = false





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateInvoice.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#L34)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HTMLTemplateInvoiceCore::__construct(\OrderInvoice $order_invoice, $smarty, $bulk_mode)





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#L41)


#### Arguments
* $order_invoice **[OrderInvoice](OrderInvoiceCore)**
* $smarty **mixed**
* $bulk_mode **mixed**



### <a name="method-getHeader"></a>getHeader

    string HTMLTemplateInvoiceCore::getHeader()

Returns the template's HTML header



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#L71)




### <a name="method-computeLayout"></a>computeLayout

    Array HTMLTemplateInvoiceCore::computeLayout($params)

Compute layout elements size



* Visibility: **private**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#L86)


#### Arguments
* $params **mixed** - &lt;p&gt;Array Layout elements&lt;/p&gt;



### <a name="method-getContent"></a>getContent

    string HTMLTemplateInvoiceCore::getContent()

Returns the template's HTML content



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#L143)




### <a name="method-getTaxTabContent"></a>getTaxTabContent

    String HTMLTemplateInvoiceCore::getTaxTabContent()

Returns the tax tab content



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#L362)




### <a name="method-getTaxBreakdown"></a>getTaxBreakdown

    Array HTMLTemplateInvoiceCore::getTaxBreakdown()

Returns different tax breakdown elements



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 402](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#L402)




### <a name="method-getTemplateByCountry"></a>getTemplateByCountry

    mixed HTMLTemplateInvoiceCore::getTemplateByCountry(string $iso_country)

Returns the invoice template associated to the country iso_code



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#L464)


#### Arguments
* $iso_country **string**



### <a name="method-getBulkFilename"></a>getBulkFilename

    string HTMLTemplateInvoiceCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 484](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#L484)




### <a name="method-getFilename"></a>getFilename

    string HTMLTemplateInvoiceCore::getFilename()

Returns the template filename



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 494](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#L494)



