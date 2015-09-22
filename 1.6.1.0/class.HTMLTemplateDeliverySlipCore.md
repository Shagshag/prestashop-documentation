Class HTMLTemplateDeliverySlipCore
=====================





* Class name: HTMLTemplateDeliverySlipCore
* Parent class: [HTMLTemplate](class.HTMLTemplateCore.md)
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateDeliverySlip.php#L30)


Contents
--------


### Properties

* [$order](#property-$order)

### Methods

* [__construct](#method-__construct)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getHeader](#method-getHeader)




Properties
----------


### <a name="property-$order"></a>$order

```php
public mixed $order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateDeliverySlip.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateDeliverySlipCore::__construct(\OrderInvoice $order_invoice, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateDeliverySlip.php#L39)


#### Arguments
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**
* $smarty **mixed**



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateDeliverySlipCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateDeliverySlip.php#L139)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateDeliverySlipCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateDeliverySlip.php#L74)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateDeliverySlipCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateDeliverySlip.php#L149)




### <a name="method-getHeader"></a>getHeader

```php
string HTMLTemplateDeliverySlipCore::getHeader()
```

Returns the template's HTML header



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateDeliverySlip.php#L59)



