Class HTMLTemplateOrderSlipCore
=====================





* Class name: HTMLTemplateOrderSlipCore
* Parent class: [HTMLTemplateInvoice](class.HTMLTemplateInvoiceCore)
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L30)



Properties
----------

* [$order](#property-$order)
* [$order_slip](#property-$order_slip)

Methods
-------
* [__construct](#method-__construct)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getHeader](#method-getHeader)
* [getProductTaxesBreakdown](#method-getProductTaxesBreakdown)
* [getShippingTaxesBreakdown](#method-getShippingTaxesBreakdown)
* [getTaxBreakdown](#method-getTaxBreakdown)
* [getTaxTabContent](#method-getTaxTabContent)




Properties
----------


### <a name="property-$order"></a>$order

    public mixed $order





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L32)


### <a name="property-$order_slip"></a>$order_slip

    public mixed $order_slip





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L33)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HTMLTemplateOrderSlipCore::__construct(\OrderSlip $order_slip, $smarty)





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L40)


#### Arguments
* $order_slip **[OrderSlip](class.OrderSlipCore)**
* $smarty **mixed**



### <a name="method-getBulkFilename"></a>getBulkFilename

    string HTMLTemplateOrderSlipCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L189)




### <a name="method-getContent"></a>getContent

    string HTMLTemplateOrderSlipCore::getContent()

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L80)




### <a name="method-getFilename"></a>getFilename

    string HTMLTemplateOrderSlipCore::getFilename()

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L199)




### <a name="method-getHeader"></a>getHeader

    string HTMLTemplateOrderSlipCore::getHeader()

Returns the template's HTML header



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L65)




### <a name="method-getProductTaxesBreakdown"></a>getProductTaxesBreakdown

    mixed HTMLTemplateOrderSlipCore::getProductTaxesBreakdown()





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L269)




### <a name="method-getShippingTaxesBreakdown"></a>getShippingTaxesBreakdown

    Array HTMLTemplateOrderSlipCore::getShippingTaxesBreakdown()

Returns Shipping tax breakdown elements



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 308](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L308)




### <a name="method-getTaxBreakdown"></a>getTaxBreakdown

    Array HTMLTemplateOrderSlipCore::getTaxBreakdown()

Returns different tax breakdown elements



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L235)




### <a name="method-getTaxTabContent"></a>getTaxTabContent

    String HTMLTemplateOrderSlipCore::getTaxTabContent()

Returns the tax tab content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L209)



