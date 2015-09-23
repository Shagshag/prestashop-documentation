Class HTMLTemplateOrderSlipCore
=====================





* Class name: HTMLTemplateOrderSlipCore
* Parent class: [HTMLTemplateInvoice](class.HTMLTemplateInvoiceCore.md)
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/pdf/HTMLTemplateOrderSlip.php#L30)


Contents
--------


### Properties

* [$order](#property-$order)
* [$order_slip](#property-$order_slip)

### Methods

* [__construct](#method-__construct)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getProductTaxesBreakdown](#method-getProductTaxesBreakdown)
* [getShippingTaxesBreakdown](#method-getShippingTaxesBreakdown)
* [getTaxTabContent](#method-getTaxTabContent)




Properties
----------


### <a name="property-$order"></a>$order

```php
public mixed $order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/pdf/HTMLTemplateOrderSlip.php#L32).


### <a name="property-$order_slip"></a>$order_slip

```php
public mixed $order_slip
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/pdf/HTMLTemplateOrderSlip.php#L33).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateOrderSlipCore::__construct(\OrderSlip $order_slip, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/pdf/HTMLTemplateOrderSlip.php#L35)


#### Arguments
* $order_slip **[OrderSlip](class.OrderSlipCore.md)**
* $smarty **mixed**



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateOrderSlipCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/pdf/HTMLTemplateOrderSlip.php#L146)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateOrderSlipCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/pdf/HTMLTemplateOrderSlip.php#L60)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateOrderSlipCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/pdf/HTMLTemplateOrderSlip.php#L155)




### <a name="method-getProductTaxesBreakdown"></a>getProductTaxesBreakdown

```php
mixed HTMLTemplateOrderSlipCore::getProductTaxesBreakdown()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/pdf/HTMLTemplateOrderSlip.php#L184)




### <a name="method-getShippingTaxesBreakdown"></a>getShippingTaxesBreakdown

```php
mixed HTMLTemplateOrderSlipCore::getShippingTaxesBreakdown()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 250](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/pdf/HTMLTemplateOrderSlip.php#L250)




### <a name="method-getTaxTabContent"></a>getTaxTabContent

```php
mixed HTMLTemplateOrderSlipCore::getTaxTabContent()
```

Returns the tax tab content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/pdf/HTMLTemplateOrderSlip.php#L163)



