Class HTMLTemplateDeliverySlipCore
=====================





* Class name: HTMLTemplateDeliverySlipCore
* Parent class: [HTMLTemplate](class.HTMLTemplateCore.md)
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateDeliverySlip.php#L30)



Properties
----------

* [$order](#property-$order)

Methods
-------
* [__construct](#method-__construct)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getHeader](#method-getHeader)




Properties
----------


### <a name="property-$order"></a>$order

    public mixed $order





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateDeliverySlip.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HTMLTemplateDeliverySlipCore::__construct(\OrderInvoice $order_invoice, $smarty, $bulk_mode)





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateDeliverySlip.php#L39)


#### Arguments
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**
* $smarty **mixed**
* $bulk_mode **mixed**



### <a name="method-getBulkFilename"></a>getBulkFilename

    string HTMLTemplateDeliverySlipCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateDeliverySlip.php#L146)




### <a name="method-getContent"></a>getContent

    string HTMLTemplateDeliverySlipCore::getContent()

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateDeliverySlip.php#L82)




### <a name="method-getFilename"></a>getFilename

    string HTMLTemplateDeliverySlipCore::getFilename()

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateDeliverySlip.php#L156)




### <a name="method-getHeader"></a>getHeader

    string HTMLTemplateDeliverySlipCore::getHeader()

Returns the template's HTML header



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateDeliverySlip.php#L69)



