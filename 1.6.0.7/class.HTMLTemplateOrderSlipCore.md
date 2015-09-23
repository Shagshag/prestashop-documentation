Class HTMLTemplateOrderSlipCore
=====================





* Class name: HTMLTemplateOrderSlipCore
* Parent class: [HTMLTemplateInvoice](class.HTMLTemplateInvoiceCore.md)
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/pdf/HTMLTemplateOrderSlip.php#L30)


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
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/pdf/HTMLTemplateOrderSlip.php#L32).


### <a name="property-$order_slip"></a>$order_slip

```php
public mixed $order_slip
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/pdf/HTMLTemplateOrderSlip.php#L33).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateOrderSlipCore::__construct(\OrderSlip $order_slip, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/pdf/HTMLTemplateOrderSlip.php#L35)


#### Arguments
* $order_slip **[OrderSlip](class.OrderSlipCore.md)**
* $smarty **mixed**



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateOrderSlipCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/pdf/HTMLTemplateOrderSlip.php#L126)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateOrderSlipCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/pdf/HTMLTemplateOrderSlip.php#L59)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateOrderSlipCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/pdf/HTMLTemplateOrderSlip.php#L135)




### <a name="method-getProductTaxesBreakdown"></a>getProductTaxesBreakdown

```php
mixed HTMLTemplateOrderSlipCore::getProductTaxesBreakdown()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 164](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/pdf/HTMLTemplateOrderSlip.php#L164)




### <a name="method-getShippingTaxesBreakdown"></a>getShippingTaxesBreakdown

```php
mixed HTMLTemplateOrderSlipCore::getShippingTaxesBreakdown()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/pdf/HTMLTemplateOrderSlip.php#L223)




### <a name="method-getTaxTabContent"></a>getTaxTabContent

```php
mixed HTMLTemplateOrderSlipCore::getTaxTabContent()
```

Returns the tax tab content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.7/classes/pdf/HTMLTemplateOrderSlip.php#L143)



