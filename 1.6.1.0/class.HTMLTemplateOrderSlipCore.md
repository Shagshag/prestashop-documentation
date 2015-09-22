Class HTMLTemplateOrderSlipCore
=====================





* Class name: HTMLTemplateOrderSlipCore
* Parent class: [HTMLTemplateInvoice](class.HTMLTemplateInvoiceCore.md)
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateOrderSlip.php#L30)


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
* [getHeader](#method-getHeader)
* [getProductTaxesBreakdown](#method-getProductTaxesBreakdown)
* [getShippingTaxesBreakdown](#method-getShippingTaxesBreakdown)
* [getTaxBreakdown](#method-getTaxBreakdown)
* [getTaxTabContent](#method-getTaxTabContent)
* [useOneAfterAnotherTaxComputationMethod](#method-useOneAfterAnotherTaxComputationMethod)




Properties
----------


### <a name="property-$order"></a>$order

```php
public mixed $order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateOrderSlip.php#L32).


### <a name="property-$order_slip"></a>$order_slip

```php
public mixed $order_slip
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateOrderSlip.php#L33).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateOrderSlipCore::__construct(\OrderSlip $order_slip, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateOrderSlip.php#L40)


#### Arguments
* $order_slip **[OrderSlip](class.OrderSlipCore.md)**
* $smarty **mixed**



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateOrderSlipCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 178](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateOrderSlip.php#L178)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateOrderSlipCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateOrderSlip.php#L80)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateOrderSlipCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 188](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateOrderSlip.php#L188)




### <a name="method-getHeader"></a>getHeader

```php
string HTMLTemplateOrderSlipCore::getHeader()
```

Returns the template's HTML header



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateOrderSlip.php#L65)




### <a name="method-getProductTaxesBreakdown"></a>getProductTaxesBreakdown

```php
mixed HTMLTemplateOrderSlipCore::getProductTaxesBreakdown()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateOrderSlip.php#L259)




### <a name="method-getShippingTaxesBreakdown"></a>getShippingTaxesBreakdown

```php
Array HTMLTemplateOrderSlipCore::getShippingTaxesBreakdown()
```

Returns Shipping tax breakdown elements



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateOrderSlip.php#L339)




### <a name="method-getTaxBreakdown"></a>getTaxBreakdown

```php
Array HTMLTemplateOrderSlipCore::getTaxBreakdown()
```

Returns different tax breakdown elements



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 224](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateOrderSlip.php#L224)




### <a name="method-getTaxTabContent"></a>getTaxTabContent

```php
String HTMLTemplateOrderSlipCore::getTaxTabContent()
```

Returns the tax tab content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateOrderSlip.php#L198)




### <a name="method-useOneAfterAnotherTaxComputationMethod"></a>useOneAfterAnotherTaxComputationMethod

```php
mixed HTMLTemplateOrderSlipCore::useOneAfterAnotherTaxComputationMethod()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 321](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateOrderSlip.php#L321)



