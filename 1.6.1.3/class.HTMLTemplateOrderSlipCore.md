Class HTMLTemplateOrderSlipCore
=====================





* Class name: HTMLTemplateOrderSlipCore
* Parent class: [HTMLTemplateInvoice](class.HTMLTemplateInvoiceCore.md)
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateOrderSlip.php#L30)


Contents
--------


### Properties

* [$order](#property-$order)
* [$order_slip](#property-$order_slip)
* [$available_in_your_account](#property-$available_in_your_account)
* [$order_invoice](#property-$order_invoice)
* [$date](#property-$date)
* [$shop](#property-$shop)
* [$smarty](#property-$smarty)
* [$title](#property-$title)

### Methods

* [__construct](#method-__construct)
* [assignCommonHeaderData](#method-assignCommonHeaderData)
* [assignHookData](#method-assignHookData)
* [computeLayout](#method-computeLayout)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getFooter](#method-getFooter)
* [getHeader](#method-getHeader)
* [getLogo](#method-getLogo)
* [getProductTaxesBreakdown](#method-getProductTaxesBreakdown)
* [getShippingTaxesBreakdown](#method-getShippingTaxesBreakdown)
* [getShopAddress](#method-getShopAddress)
* [getTaxBreakdown](#method-getTaxBreakdown)
* [getTaxTabContent](#method-getTaxTabContent)
* [getTemplate](#method-getTemplate)
* [getTemplateByCountry](#method-getTemplateByCountry)
* [l](#method-l)
* [setShopId](#method-setShopId)




Properties
----------


### <a name="property-$order"></a>$order

```php
public mixed $order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateOrderSlip.php#L32).


### <a name="property-$order_slip"></a>$order_slip

```php
public mixed $order_slip
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateOrderSlip.php#L33).


### <a name="property-$available_in_your_account"></a>$available_in_your_account

```php
public mixed $available_in_your_account = false
```





* Visibility: **public**
* This property is defined by [HTMLTemplateInvoiceCore](class.HTMLTemplateInvoiceCore.md).
* Source: [classes/pdf/HTMLTemplateInvoice.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateInvoice.php#L34).


### <a name="property-$order_invoice"></a>$order_invoice

```php
public mixed $order_invoice
```





* Visibility: **public**
* This property is defined by [HTMLTemplateInvoiceCore](class.HTMLTemplateInvoiceCore.md).
* Source: [classes/pdf/HTMLTemplateInvoice.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateInvoice.php#L33).


### <a name="property-$date"></a>$date

```php
public mixed $date
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L33).


### <a name="property-$shop"></a>$shop

```php
public \Shop $shop
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L40).


### <a name="property-$smarty"></a>$smarty

```php
public \Smarty $smarty
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L37).


### <a name="property-$title"></a>$title

```php
public mixed $title
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateOrderSlipCore::__construct(\OrderSlip $order_slip, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateOrderSlip.php#L40)


#### Arguments
* $order_slip **[OrderSlip](class.OrderSlipCore.md)**
* $smarty **mixed**



### <a name="method-assignCommonHeaderData"></a>assignCommonHeaderData

```php
mixed HTMLTemplateCore::assignCommonHeaderData()
```

Assign common header data to smarty variables



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L115)




### <a name="method-assignHookData"></a>assignHookData

```php
mixed HTMLTemplateCore::assignHookData(\ObjectModel $object)
```

Assign hook data



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L155)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)** - generally the object used in the constructor



### <a name="method-computeLayout"></a>computeLayout

```php
Array HTMLTemplateInvoiceCore::computeLayout($params)
```

Compute layout elements size



* Visibility: **protected**
* This method is defined by [HTMLTemplateInvoiceCore](class.HTMLTemplateInvoiceCore.md).
* Source: [classes/pdf/HTMLTemplateInvoice.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateInvoice.php#L86)


#### Arguments
* $params **mixed** - Array Layout elements



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateOrderSlipCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 189](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateOrderSlip.php#L189)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateOrderSlipCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateOrderSlip.php#L80)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateOrderSlipCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateOrderSlip.php#L199)




### <a name="method-getFooter"></a>getFooter

```php
string HTMLTemplateCore::getFooter()
```

Returns the template's HTML footer



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L59)




### <a name="method-getHeader"></a>getHeader

```php
string HTMLTemplateOrderSlipCore::getHeader()
```

Returns the template's HTML header



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateOrderSlip.php#L65)




### <a name="method-getLogo"></a>getLogo

```php
mixed HTMLTemplateCore::getLogo()
```

Returns the invoice logo



* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L97)




### <a name="method-getProductTaxesBreakdown"></a>getProductTaxesBreakdown

```php
mixed HTMLTemplateOrderSlipCore::getProductTaxesBreakdown()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 269](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateOrderSlip.php#L269)




### <a name="method-getShippingTaxesBreakdown"></a>getShippingTaxesBreakdown

```php
Array HTMLTemplateOrderSlipCore::getShippingTaxesBreakdown()
```

Returns Shipping tax breakdown elements



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 308](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateOrderSlip.php#L308)




### <a name="method-getShopAddress"></a>getShopAddress

```php
string HTMLTemplateCore::getShopAddress()
```

Returns the shop address



* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L82)




### <a name="method-getTaxBreakdown"></a>getTaxBreakdown

```php
Array HTMLTemplateOrderSlipCore::getTaxBreakdown()
```

Returns different tax breakdown elements



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 235](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateOrderSlip.php#L235)




### <a name="method-getTaxTabContent"></a>getTaxTabContent

```php
String HTMLTemplateOrderSlipCore::getTaxTabContent()
```

Returns the tax tab content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 209](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateOrderSlip.php#L209)




### <a name="method-getTemplate"></a>getTemplate

```php
string HTMLTemplateCore::getTemplate($template_name)
```

If the template is not present in the theme directory, it will return the default template
in _PS_PDF_DIR_ directory



* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L195)


#### Arguments
* $template_name **mixed**



### <a name="method-getTemplateByCountry"></a>getTemplateByCountry

```php
mixed HTMLTemplateInvoiceCore::getTemplateByCountry(string $iso_country)
```

Returns the invoice template associated to the country iso_code



* Visibility: **protected**
* This method is defined by [HTMLTemplateInvoiceCore](class.HTMLTemplateInvoiceCore.md).
* Source: [classes/pdf/HTMLTemplateInvoice.php line 464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateInvoice.php#L464)


#### Arguments
* $iso_country **string**



### <a name="method-l"></a>l

```php
string HTMLTemplateCore::l(string $string)
```

Translation method



* Visibility: **protected**
* This method is **static**.
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L217)


#### Arguments
* $string **string**



### <a name="method-setShopId"></a>setShopId

```php
mixed HTMLTemplateCore::setShopId()
```





* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L222)



