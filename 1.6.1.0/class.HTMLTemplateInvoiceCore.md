Class HTMLTemplateInvoiceCore
=====================





* Class name: HTMLTemplateInvoiceCore
* Parent class: [HTMLTemplate](class.HTMLTemplateCore.md)
* Source: [classes/pdf/HTMLTemplateInvoice.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateInvoice.php#L30)


Contents
--------


### Properties

* [$available_in_your_account](#property-$available_in_your_account)
* [$order](#property-$order)

### Methods

* [__construct](#method-__construct)
* [computeLayout](#method-computeLayout)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getHeader](#method-getHeader)
* [getTaxBreakdown](#method-getTaxBreakdown)
* [getTaxTabContent](#method-getTaxTabContent)
* [getTemplateByCountry](#method-getTemplateByCountry)




Properties
----------


### <a name="property-$available_in_your_account"></a>$available_in_your_account

```php
public mixed $available_in_your_account = false
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateInvoice.php#L33).


### <a name="property-$order"></a>$order

```php
public mixed $order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateInvoice.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateInvoiceCore::__construct(\OrderInvoice $order_invoice, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateInvoice.php#L40)


#### Arguments
* $order_invoice **[OrderInvoice](class.OrderInvoiceCore.md)**
* $smarty **mixed**



### <a name="method-computeLayout"></a>computeLayout

```php
Array HTMLTemplateInvoiceCore::computeLayout($params)
```

Compute layout elements size



* Visibility: **private**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateInvoice.php#L78)


#### Arguments
* $params **mixed**



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateInvoiceCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 480](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateInvoice.php#L480)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateInvoiceCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateInvoice.php#L134)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateInvoiceCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 490](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateInvoice.php#L490)




### <a name="method-getHeader"></a>getHeader

```php
string HTMLTemplateInvoiceCore::getHeader()
```

Returns the template's HTML header



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateInvoice.php#L60)




### <a name="method-getTaxBreakdown"></a>getTaxBreakdown

```php
Array HTMLTemplateInvoiceCore::getTaxBreakdown()
```

Returns different tax breakdown elements



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 400](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateInvoice.php#L400)




### <a name="method-getTaxTabContent"></a>getTaxTabContent

```php
String HTMLTemplateInvoiceCore::getTaxTabContent()
```

Returns the tax tab content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 361](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateInvoice.php#L361)




### <a name="method-getTemplateByCountry"></a>getTemplateByCountry

```php
mixed HTMLTemplateInvoiceCore::getTemplateByCountry(string $iso_country)
```

Returns the invoice template associated to the country iso_code



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateInvoice.php line 461](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.0/classes/pdf/HTMLTemplateInvoice.php#L461)


#### Arguments
* $iso_country **string**


