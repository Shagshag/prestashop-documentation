Class HTMLTemplateDeliverySlipCore
=====================





* Class name: HTMLTemplateDeliverySlipCore
* Parent class: [HTMLTemplate](class.HTMLTemplateCore.md)
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/pdf/HTMLTemplateDeliverySlip.php#L30)


Contents
--------


### Properties

* [$order](#property-$order)

### Methods

* [__construct](#method-__construct)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)




Properties
----------


### <a name="property-$order"></a>$order

```php
public mixed $order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/pdf/HTMLTemplateDeliverySlip.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateDeliverySlipCore::__construct(\OrderInvoice $order_invoice, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/pdf/HTMLTemplateDeliverySlip.php#L34)


#### Arguments
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**
* $smarty **mixed**



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateDeliverySlipCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/pdf/HTMLTemplateDeliverySlip.php#L82)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateDeliverySlipCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 52](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/pdf/HTMLTemplateDeliverySlip.php#L52)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateDeliverySlipCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/pdf/HTMLTemplateDeliverySlip.php#L91)



