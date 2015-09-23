Class HTMLTemplateOrderSlipCore
=====================





* Class name: HTMLTemplateOrderSlipCore
* Parent class: [HTMLTemplateInvoice](class.HTMLTemplateInvoiceCore.md)
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplateOrderSlip.php#L31)


Contents
--------


### Properties

* [$order](#property-$order)
* [$order_slip](#property-$order_slip)
* [$available_in_your_account](#property-$available_in_your_account)
* [$date](#property-$date)
* [$shop](#property-$shop)
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
* [getShopAddress](#method-getShopAddress)
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
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplateOrderSlip.php#L33).


### <a name="property-$order_slip"></a>$order_slip

```php
public mixed $order_slip
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplateOrderSlip.php#L34).


### <a name="property-$available_in_your_account"></a>$available_in_your_account

```php
public mixed $available_in_your_account = false
```





* Visibility: **public**
* This property is defined by [HTMLTemplateInvoiceCore](class.HTMLTemplateInvoiceCore.md).
* Source: [classes/pdf/HTMLTemplateInvoice.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplateInvoice.php#L34).


### <a name="property-$date"></a>$date

```php
public mixed $date
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplate.php#L35).


### <a name="property-$shop"></a>$shop

```php
public mixed $shop
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplate.php#L38).


### <a name="property-$smarty"></a>$smarty

```php
public mixed $smarty
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplate.php#L37).


### <a name="property-$title"></a>$title

```php
public mixed $title
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplate.php#L34).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateOrderSlipCore::__construct(\OrderSlip $order_slip, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplateOrderSlip.php#L36)


#### Arguments
* $order_slip **[OrderSlip](class.OrderSlipCore.md)**
* $smarty **mixed**



### <a name="method-assignHookData"></a>assignHookData

```php
mixed HTMLTemplateCore::assignHookData($object)
```

Assign hook data



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplate.php#L120)


#### Arguments
* $object **mixed** - generally the object used in the constructor



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateOrderSlipCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplateOrderSlip.php#L120)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateOrderSlipCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplateOrderSlip.php#L60)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateOrderSlipCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderSlip.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplateOrderSlip.php#L129)




### <a name="method-getFooter"></a>getFooter

```php
string HTMLTemplateCore::getFooter()
```

Returns the template's HTML footer



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 66](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplate.php#L66)




### <a name="method-getHeader"></a>getHeader

```php
string HTMLTemplateCore::getHeader()
```

Returns the template's HTML header



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplate.php#L44)




### <a name="method-getLogo"></a>getLogo

```php
mixed HTMLTemplateCore::getLogo()
```

Returns the invoice logo



* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplate.php#L103)




### <a name="method-getShopAddress"></a>getShopAddress

```php
string HTMLTemplateCore::getShopAddress()
```

Returns the shop address



* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplate.php#L86)




### <a name="method-getTaxTabContent"></a>getTaxTabContent

```php
mixed HTMLTemplateInvoiceCore::getTaxTabContent()
```

Returns the tax tab content



* Visibility: **public**
* This method is defined by [HTMLTemplateInvoiceCore](class.HTMLTemplateInvoiceCore.md).
* Source: [classes/pdf/HTMLTemplateInvoice.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplateInvoice.php#L86)




### <a name="method-getTemplate"></a>getTemplate

```php
mixed HTMLTemplateInvoiceCore::getTemplate(string $iso_country)
```

Returns the invoice template associated to the country iso_code



* Visibility: **protected**
* This method is defined by [HTMLTemplateInvoiceCore](class.HTMLTemplateInvoiceCore.md).
* Source: [classes/pdf/HTMLTemplateInvoice.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplateInvoice.php#L110)


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
* Source: [classes/pdf/HTMLTemplate.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.5/classes/pdf/HTMLTemplate.php#L154)


#### Arguments
* $string **string**


