Class HTMLTemplateOrderSlipCore
=====================





* Class name: HTMLTemplateOrderSlipCore
* Parent class: [HTMLTemplateInvoice](class.HTMLTemplateInvoiceCore.md)
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateOrderSlip.php#L31)


Contents
--------


### Properties

* [$order](#property-$order)
* [$order_slip](#property-$order_slip)
* [$available_in_your_account](#property-$available_in_your_account)
* [$address](#property-$address)
* [$date](#property-$date)
* [$smarty](#property-$smarty)
* [$title](#property-$title)

### Methods

* [__construct](#method-__construct)
* [assignHookData](#method-assignHookData)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getFooter](#method-getFooter)
* [getHeader](#method-getHeader)
* [getLogo](#method-getLogo)
* [getTaxTabContent](#method-getTaxTabContent)
* [getTemplate](#method-getTemplate)
* [l](#method-l)




Properties
----------


### <a name="property-$order"></a>$order

```php
public mixed $order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateOrderSlip.php#L33).


### <a name="property-$order_slip"></a>$order_slip

```php
public mixed $order_slip
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateOrderSlip.php#L34).


### <a name="property-$available_in_your_account"></a>$available_in_your_account

```php
public mixed $available_in_your_account = false
```





* Visibility: **public**
* This property is defined by [HTMLTemplateInvoiceCore](class.HTMLTemplateInvoiceCore.md).
* Source: [classes/pdf/HTMLTemplateInvoice.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateInvoice.php#L35).


### <a name="property-$address"></a>$address

```php
public mixed $address
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplate.php#L36).


### <a name="property-$date"></a>$date

```php
public mixed $date
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplate.php#L35).


### <a name="property-$smarty"></a>$smarty

```php
public mixed $smarty
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplate.php#L38).


### <a name="property-$title"></a>$title

```php
public mixed $title
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplate.php#L34).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateOrderSlipCore::__construct(\OrderSlip $order_slip, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateOrderSlip.php#L36)


#### Arguments
* $order_slip **[OrderSlip](class.OrderSlipCore.md)**
* $smarty **mixed**



### <a name="method-assignHookData"></a>assignHookData

```php
mixed HTMLTemplateCore::assignHookData()
```

Returns the HTML content of the template's footer



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplate.php#L99)




### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateOrderSlipCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateOrderSlip.php#L92)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateOrderSlipCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateOrderSlip.php#L61)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateOrderSlipCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateOrderSlip.php#L101)




### <a name="method-getFooter"></a>getFooter

```php
string HTMLTemplateCore::getFooter()
```

Returns the template's HTML footer



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplate.php#L64)




### <a name="method-getHeader"></a>getHeader

```php
string HTMLTemplateCore::getHeader()
```

Returns the template's HTML header



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplate.php#L44)




### <a name="method-getLogo"></a>getLogo

```php
mixed HTMLTemplateCore::getLogo()
```

Returns the invoice logo



* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplate.php#L84)




### <a name="method-getTaxTabContent"></a>getTaxTabContent

```php
mixed HTMLTemplateInvoiceCore::getTaxTabContent()
```

Returns the tax tab content



* Visibility: **public**
* This method is defined by [HTMLTemplateInvoiceCore](class.HTMLTemplateInvoiceCore.md).
* Source: [classes/pdf/HTMLTemplateInvoice.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateInvoice.php#L86)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed HTMLTemplateInvoiceCore::getTemplate(string $iso_country)
```

Returns the invoice template associated to the country iso_code



* Visibility: **protected**
* This method is defined by [HTMLTemplateInvoiceCore](class.HTMLTemplateInvoiceCore.md).
* Source: [classes/pdf/HTMLTemplateInvoice.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateInvoice.php#L110)


#### Arguments
* $iso_country **string**



### <a name="method-l"></a>l

```php
string HTMLTemplateCore::l(string $string)
```

Translatation method



* Visibility: **protected**
* This method is **static**.
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplate.php#L133)


#### Arguments
* $string **string**


