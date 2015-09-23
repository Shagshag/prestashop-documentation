Class HTMLTemplateSupplyOrderForm
=====================





* Class name: HTMLTemplateSupplyOrderForm
* Parent class: [HTMLTemplate](class.HTMLTemplateCore.md)
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L31)


Contents
--------


### Properties

* [$address_warehouse](#property-$address_warehouse)
* [$context](#property-$context)
* [$supply_order](#property-$supply_order)
* [$warehouse](#property-$warehouse)
* [$address](#property-$address)
* [$available_in_your_account](#property-$available_in_your_account)
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
* [getTaxOrderSummary](#method-getTaxOrderSummary)
* [l](#method-l)
* [roundSupplyOrder](#method-roundSupplyOrder)
* [roundSupplyOrderDetails](#method-roundSupplyOrderDetails)




Properties
----------


### <a name="property-$address_warehouse"></a>$address_warehouse

```php
public mixed $address_warehouse
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L35).


### <a name="property-$context"></a>$context

```php
public mixed $context
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L36).


### <a name="property-$supply_order"></a>$supply_order

```php
public mixed $supply_order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L33).


### <a name="property-$warehouse"></a>$warehouse

```php
public mixed $warehouse
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L34).


### <a name="property-$address"></a>$address

```php
public mixed $address
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplate.php#L36).


### <a name="property-$available_in_your_account"></a>$available_in_your_account

```php
public mixed $available_in_your_account = true
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplate.php#L37).


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
mixed HTMLTemplateSupplyOrderForm::__construct(\SupplyOrder $supply_order, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L38)


#### Arguments
* $supply_order **[SupplyOrder](class.SupplyOrderCore.md)**
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
mixed HTMLTemplateSupplyOrderForm::getBulkFilename()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L78)




### <a name="method-getContent"></a>getContent

```php
mixed HTMLTemplateSupplyOrderForm::getContent()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L54)




### <a name="method-getFilename"></a>getFilename

```php
mixed HTMLTemplateSupplyOrderForm::getFilename()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L86)




### <a name="method-getFooter"></a>getFooter

```php
mixed HTMLTemplateSupplyOrderForm::getFooter()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 118](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L118)




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




### <a name="method-getTaxOrderSummary"></a>getTaxOrderSummary

```php
mixed HTMLTemplateSupplyOrderForm::getTaxOrderSummary()
```





* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L91)




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



### <a name="method-roundSupplyOrder"></a>roundSupplyOrder

```php
mixed HTMLTemplateSupplyOrderForm::roundSupplyOrder(\SupplyOrder $supply_order)
```

Rounds values of a SupplyOrder object



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L159)


#### Arguments
* $supply_order **[SupplyOrder](class.SupplyOrderCore.md)**



### <a name="method-roundSupplyOrderDetails"></a>roundSupplyOrderDetails

```php
mixed HTMLTemplateSupplyOrderForm::roundSupplyOrderDetails(array $collection)
```

Rounds values of a SupplyOrderDetail object



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L142)


#### Arguments
* $collection **array**


