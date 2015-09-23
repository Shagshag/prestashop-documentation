Class HTMLTemplateSupplyOrderFormCore
=====================





* Class name: HTMLTemplateSupplyOrderFormCore
* Parent class: [HTMLTemplate](class.HTMLTemplateCore.md)
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L30)


Contents
--------


### Properties

* [$address_supplier](#property-$address_supplier)
* [$address_warehouse](#property-$address_warehouse)
* [$context](#property-$context)
* [$supply_order](#property-$supply_order)
* [$warehouse](#property-$warehouse)

### Methods

* [__construct](#method-__construct)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getFooter](#method-getFooter)
* [getHeader](#method-getHeader)
* [getTaxOrderSummary](#method-getTaxOrderSummary)
* [roundSupplyOrder](#method-roundSupplyOrder)
* [roundSupplyOrderDetails](#method-roundSupplyOrderDetails)




Properties
----------


### <a name="property-$address_supplier"></a>$address_supplier

```php
public mixed $address_supplier
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L35).


### <a name="property-$address_warehouse"></a>$address_warehouse

```php
public mixed $address_warehouse
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L34).


### <a name="property-$context"></a>$context

```php
public mixed $context
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L36).


### <a name="property-$supply_order"></a>$supply_order

```php
public mixed $supply_order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L32).


### <a name="property-$warehouse"></a>$warehouse

```php
public mixed $warehouse
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L33).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateSupplyOrderFormCore::__construct(\SupplyOrder $supply_order, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L38)


#### Arguments
* $supply_order **[SupplyOrder](class.SupplyOrderCore.md)**
* $smarty **mixed**



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
mixed HTMLTemplateSupplyOrderFormCore::getBulkFilename()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L81)




### <a name="method-getContent"></a>getContent

```php
mixed HTMLTemplateSupplyOrderFormCore::getContent()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L55)




### <a name="method-getFilename"></a>getFilename

```php
mixed HTMLTemplateSupplyOrderFormCore::getFilename()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L89)




### <a name="method-getFooter"></a>getFooter

```php
mixed HTMLTemplateSupplyOrderFormCore::getFooter()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L149)




### <a name="method-getHeader"></a>getHeader

```php
mixed HTMLTemplateSupplyOrderFormCore::getHeader()
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 122](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L122)




### <a name="method-getTaxOrderSummary"></a>getTaxOrderSummary

```php
mixed HTMLTemplateSupplyOrderFormCore::getTaxOrderSummary()
```





* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L94)




### <a name="method-roundSupplyOrder"></a>roundSupplyOrder

```php
mixed HTMLTemplateSupplyOrderFormCore::roundSupplyOrder(\SupplyOrder $supply_order)
```

Rounds values of a SupplyOrder object



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L187)


#### Arguments
* $supply_order **[SupplyOrder](class.SupplyOrderCore.md)**



### <a name="method-roundSupplyOrderDetails"></a>roundSupplyOrderDetails

```php
mixed HTMLTemplateSupplyOrderFormCore::roundSupplyOrderDetails(array $collection)
```

Rounds values of a SupplyOrderDetail object



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/classes/pdf/HTMLTemplateSupplyOrderForm.php#L170)


#### Arguments
* $collection **array**


