HTMLTemplateOrderSlipCore
===============






* Class name: HTMLTemplateOrderSlipCore
* Parent class: [HTMLTemplateInvoice](HTMLTemplateInvoiceCore)
* This class is defined in [classes/pdf/HTMLTemplateOrderSlip.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L30)





Properties
----------

* [$order](#property-$order)
* [$order_slip](#property-$order_slip)

Methods
-------
* [__construct](#method-__construct)
* [getHeader](#method-getHeader)
* [getContent](#method-getContent)
* [getBulkFilename](#method-getBulkFilename)
* [getFilename](#method-getFilename)
* [getTaxTabContent](#method-getTaxTabContent)
* [getTaxBreakdown](#method-getTaxBreakdown)
* [getProductTaxesBreakdown](#method-getProductTaxesBreakdown)
* [getShippingTaxesBreakdown](#method-getShippingTaxesBreakdown)




Properties
----------


### <a name="property-$order"></a>$order

    public mixed $order





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateOrderSlip.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L32)


### <a name="property-$order_slip"></a>$order_slip

    public mixed $order_slip





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateOrderSlip.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L33)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HTMLTemplateOrderSlipCore::__construct(\OrderSlip $order_slip, $smarty)





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateOrderSlip.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L40)


#### Arguments
* $order_slip **[OrderSlip](OrderSlipCore)**
* $smarty **mixed**



### <a name="method-getHeader"></a>getHeader

    string HTMLTemplateOrderSlipCore::getHeader()

Returns the template's HTML header



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateOrderSlip.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L65)




### <a name="method-getContent"></a>getContent

    string HTMLTemplateOrderSlipCore::getContent()

Returns the template's HTML content



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateOrderSlip.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L80)




### <a name="method-getBulkFilename"></a>getBulkFilename

    string HTMLTemplateOrderSlipCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateOrderSlip.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L189)




### <a name="method-getFilename"></a>getFilename

    string HTMLTemplateOrderSlipCore::getFilename()

Returns the template filename



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateOrderSlip.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L199)




### <a name="method-getTaxTabContent"></a>getTaxTabContent

    String HTMLTemplateOrderSlipCore::getTaxTabContent()

Returns the tax tab content



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateOrderSlip.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L209)




### <a name="method-getTaxBreakdown"></a>getTaxBreakdown

    Array HTMLTemplateOrderSlipCore::getTaxBreakdown()

Returns different tax breakdown elements



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplateOrderSlip.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L235)




### <a name="method-getProductTaxesBreakdown"></a>getProductTaxesBreakdown

    mixed HTMLTemplateOrderSlipCore::getProductTaxesBreakdown()





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateOrderSlip.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L269)




### <a name="method-getShippingTaxesBreakdown"></a>getShippingTaxesBreakdown

    Array HTMLTemplateOrderSlipCore::getShippingTaxesBreakdown()

Returns Shipping tax breakdown elements



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateOrderSlip.php line 308](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderSlip.php#L308)



