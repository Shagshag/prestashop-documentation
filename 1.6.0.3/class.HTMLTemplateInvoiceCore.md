Class HTMLTemplateInvoiceCore
=====================





* Class name: HTMLTemplateInvoiceCore
* Parent class: [HTMLTemplate](class.HTMLTemplateCore.md)
* Source: [classes/pdf/HTMLTemplateInvoice.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/pdf/HTMLTemplateInvoice.php#L30)


Contents
--------


### Properties

* [$available_in_your_account](#property-$available_in_your_account)
* [$order](#property-$order)

### Methods

* [__construct](#method-__construct)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getTaxTabContent](#method-getTaxTabContent)
* [getTemplateByCountry](#method-getTemplateByCountry)




Properties
----------


### <a name="property-$available_in_your_account"></a>$available_in_your_account

```php
public mixed $available_in_your_account = false
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/pdf/HTMLTemplateInvoice.php#L33).


### <a name="property-$order"></a>$order

```php
public mixed $order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/pdf/HTMLTemplateInvoice.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateInvoiceCore::__construct(\OrderInvoice $order_invoice, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/pdf/HTMLTemplateInvoice.php#L35)


#### Arguments
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**
* $smarty **mixed**



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateInvoiceCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/pdf/HTMLTemplateInvoice.php#L131)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateInvoiceCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/pdf/HTMLTemplateInvoice.php#L54)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateInvoiceCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/pdf/HTMLTemplateInvoice.php#L140)




### <a name="method-getTaxTabContent"></a>getTaxTabContent

```php
mixed HTMLTemplateInvoiceCore::getTaxTabContent()
```

Returns the tax tab content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/pdf/HTMLTemplateInvoice.php#L86)




### <a name="method-getTemplateByCountry"></a>getTemplateByCountry

```php
mixed HTMLTemplateInvoiceCore::getTemplateByCountry(string $iso_country)
```

Returns the invoice template associated to the country iso_code



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.3/classes/pdf/HTMLTemplateInvoice.php#L113)


#### Arguments
* $iso_country **string**


