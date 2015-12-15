Class HTMLTemplateDeliverySlipCore
=====================





* Class name: HTMLTemplateDeliverySlipCore
* Parent class: [HTMLTemplate](class.HTMLTemplateCore.md)
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateDeliverySlip.php#L30)


Contents
--------


### Properties

* [$order](#property-$order)
* [$available_in_your_account](#property-$available_in_your_account)
* [$date](#property-$date)
* [$shop](#property-$shop)
* [$smarty](#property-$smarty)
* [$title](#property-$title)

### Methods

* [__construct](#method-__construct)
* [assignCommonHeaderData](#method-assignCommonHeaderData)
* [assignHookData](#method-assignHookData)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getFooter](#method-getFooter)
* [getHeader](#method-getHeader)
* [getLogo](#method-getLogo)
* [getShopAddress](#method-getShopAddress)
* [getTemplate](#method-getTemplate)
* [l](#method-l)
* [setShopId](#method-setShopId)




Properties
----------


### <a name="property-$order"></a>$order

```php
public mixed $order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateDeliverySlip.php#L32).


### <a name="property-$available_in_your_account"></a>$available_in_your_account

```php
public mixed $available_in_your_account = true
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L34).


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
mixed HTMLTemplateDeliverySlipCore::__construct(\OrderInvoice $order_invoice, $smarty, $bulk_mode)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateDeliverySlip.php#L39)


#### Arguments
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**
* $smarty **mixed**
* $bulk_mode **mixed**



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



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateDeliverySlipCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateDeliverySlip.php#L146)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateDeliverySlipCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateDeliverySlip.php#L82)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateDeliverySlipCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateDeliverySlip.php#L156)




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
string HTMLTemplateDeliverySlipCore::getHeader()
```

Returns the template's HTML header



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateDeliverySlip.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplateDeliverySlip.php#L69)




### <a name="method-getLogo"></a>getLogo

```php
mixed HTMLTemplateCore::getLogo()
```

Returns the invoice logo



* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L97)




### <a name="method-getShopAddress"></a>getShopAddress

```php
string HTMLTemplateCore::getShopAddress()
```

Returns the shop address



* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.3/classes/pdf/HTMLTemplate.php#L82)




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



