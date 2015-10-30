Class HTMLTemplateSupplyOrderFormCore
=====================





* Class name: HTMLTemplateSupplyOrderFormCore
* Parent class: [HTMLTemplate](class.HTMLTemplateCore.md)
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L30)


Contents
--------


### Properties

* [$address_supplier](#property-$address_supplier)
* [$address_warehouse](#property-$address_warehouse)
* [$context](#property-$context)
* [$supply_order](#property-$supply_order)
* [$warehouse](#property-$warehouse)
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
* [getTaxOrderSummary](#method-getTaxOrderSummary)
* [getTemplate](#method-getTemplate)
* [l](#method-l)
* [roundSupplyOrder](#method-roundSupplyOrder)
* [roundSupplyOrderDetails](#method-roundSupplyOrderDetails)
* [setShopId](#method-setShopId)




Properties
----------


### <a name="property-$address_supplier"></a>$address_supplier

```php
public mixed $address_supplier
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L35).


### <a name="property-$address_warehouse"></a>$address_warehouse

```php
public mixed $address_warehouse
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L34).


### <a name="property-$context"></a>$context

```php
public mixed $context
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L36).


### <a name="property-$supply_order"></a>$supply_order

```php
public mixed $supply_order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L32).


### <a name="property-$warehouse"></a>$warehouse

```php
public mixed $warehouse
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L33).


### <a name="property-$available_in_your_account"></a>$available_in_your_account

```php
public mixed $available_in_your_account = true
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplate.php#L34).


### <a name="property-$date"></a>$date

```php
public mixed $date
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplate.php#L33).


### <a name="property-$shop"></a>$shop

```php
public \Shop $shop
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplate.php#L40).


### <a name="property-$smarty"></a>$smarty

```php
public \Smarty $smarty
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplate.php#L37).


### <a name="property-$title"></a>$title

```php
public mixed $title
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplate.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateSupplyOrderFormCore::__construct(\SupplyOrder $supply_order, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L43)


#### Arguments
* $supply_order **[SupplyOrder](class.SupplyOrderCore.md)**
* $smarty **mixed**



### <a name="method-assignCommonHeaderData"></a>assignCommonHeaderData

```php
mixed HTMLTemplateCore::assignCommonHeaderData()
```

Assign common header data to smarty variables



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplate.php#L115)




### <a name="method-assignHookData"></a>assignHookData

```php
mixed HTMLTemplateCore::assignHookData(\ObjectModel $object)
```

Assign hook data



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplate.php#L155)


#### Arguments
* $object **[ObjectModel](class.ObjectModelCore.md)** - generally the object used in the constructor



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
mixed HTMLTemplateSupplyOrderFormCore::getBulkFilename()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L115)




### <a name="method-getContent"></a>getContent

```php
mixed HTMLTemplateSupplyOrderFormCore::getContent()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L62)




### <a name="method-getFilename"></a>getFilename

```php
mixed HTMLTemplateSupplyOrderFormCore::getFilename()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L123)




### <a name="method-getFooter"></a>getFooter

```php
mixed HTMLTemplateSupplyOrderFormCore::getFooter()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L191)




### <a name="method-getHeader"></a>getHeader

```php
mixed HTMLTemplateSupplyOrderFormCore::getHeader()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L163)




### <a name="method-getLogo"></a>getLogo

```php
String HTMLTemplateSupplyOrderFormCore::getLogo()
```

Returns the invoice logo



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L99)




### <a name="method-getShopAddress"></a>getShopAddress

```php
string HTMLTemplateCore::getShopAddress()
```

Returns the shop address



* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplate.php#L82)




### <a name="method-getTaxOrderSummary"></a>getTaxOrderSummary

```php
array|false|\mysqli_result|null|\PDOStatement|resource HTMLTemplateSupplyOrderFormCore::getTaxOrderSummary()
```

Get order taxes summary



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L135)




### <a name="method-getTemplate"></a>getTemplate

```php
string HTMLTemplateCore::getTemplate($template_name)
```

If the template is not present in the theme directory, it will return the default template
in _PS_PDF_DIR_ directory



* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 195](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplate.php#L195)


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
* Source: [classes/pdf/HTMLTemplate.php line 217](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplate.php#L217)


#### Arguments
* $string **string**



### <a name="method-roundSupplyOrder"></a>roundSupplyOrder

```php
mixed HTMLTemplateSupplyOrderFormCore::roundSupplyOrder(\SupplyOrder $supply_order)
```

Rounds values of a SupplyOrder object



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L231)


#### Arguments
* $supply_order **[SupplyOrder](class.SupplyOrderCore.md)**



### <a name="method-roundSupplyOrderDetails"></a>roundSupplyOrderDetails

```php
mixed HTMLTemplateSupplyOrderFormCore::roundSupplyOrderDetails(array|\PrestaShopCollection $collection)
```

Rounds values of a SupplyOrderDetail object



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L213)


#### Arguments
* $collection **array|[array](class.PrestaShopCollectionCore.md)**



### <a name="method-setShopId"></a>setShopId

```php
mixed HTMLTemplateCore::setShopId()
```





* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 222](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/pdf/HTMLTemplate.php#L222)



