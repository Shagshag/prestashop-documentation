Class PDFCore
=====================





* Class name: PDFCore
* Source: [classes/pdf/PDF.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/pdf/PDF.php#L30)


Contents
--------

### Constants

* [TEMPLATE_DELIVERY_SLIP](#constant-TEMPLATE_DELIVERY_SLIP)
* [TEMPLATE_INVOICE](#constant-TEMPLATE_INVOICE)
* [TEMPLATE_ORDER_RETURN](#constant-TEMPLATE_ORDER_RETURN)
* [TEMPLATE_ORDER_SLIP](#constant-TEMPLATE_ORDER_SLIP)
* [TEMPLATE_SUPPLY_ORDER_FORM](#constant-TEMPLATE_SUPPLY_ORDER_FORM)

### Properties

* [$filename](#property-$filename)
* [$objects](#property-$objects)
* [$pdf_renderer](#property-$pdf_renderer)
* [$template](#property-$template)

### Methods

* [__construct](#method-__construct)
* [getTemplateObject](#method-getTemplateObject)
* [render](#method-render)


Constants
----------


### <a name="constant-TEMPLATE_DELIVERY_SLIP"></a>TEMPLATE_DELIVERY_SLIP

```php
const TEMPLATE_DELIVERY_SLIP = 'DeliverySlip'
```





* Source: [classes/pdf/PDF.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/pdf/PDF.php#L40).


### <a name="constant-TEMPLATE_INVOICE"></a>TEMPLATE_INVOICE

```php
const TEMPLATE_INVOICE = 'Invoice'
```





* Source: [classes/pdf/PDF.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/pdf/PDF.php#L37).


### <a name="constant-TEMPLATE_ORDER_RETURN"></a>TEMPLATE_ORDER_RETURN

```php
const TEMPLATE_ORDER_RETURN = 'OrderReturn'
```





* Source: [classes/pdf/PDF.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/pdf/PDF.php#L38).


### <a name="constant-TEMPLATE_ORDER_SLIP"></a>TEMPLATE_ORDER_SLIP

```php
const TEMPLATE_ORDER_SLIP = 'OrderSlip'
```





* Source: [classes/pdf/PDF.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/pdf/PDF.php#L39).


### <a name="constant-TEMPLATE_SUPPLY_ORDER_FORM"></a>TEMPLATE_SUPPLY_ORDER_FORM

```php
const TEMPLATE_SUPPLY_ORDER_FORM = 'SupplyOrderForm'
```





* Source: [classes/pdf/PDF.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/pdf/PDF.php#L41).


Properties
----------


### <a name="property-$filename"></a>$filename

```php
public mixed $filename
```





* Visibility: **public**
* Source: [classes/pdf/PDF.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/pdf/PDF.php#L32).


### <a name="property-$objects"></a>$objects

```php
public mixed $objects
```





* Visibility: **public**
* Source: [classes/pdf/PDF.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/pdf/PDF.php#L34).


### <a name="property-$pdf_renderer"></a>$pdf_renderer

```php
public mixed $pdf_renderer
```





* Visibility: **public**
* Source: [classes/pdf/PDF.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/pdf/PDF.php#L33).


### <a name="property-$template"></a>$template

```php
public mixed $template
```





* Visibility: **public**
* Source: [classes/pdf/PDF.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/pdf/PDF.php#L35).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed PDFCore::__construct($objects, $template, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/PDF.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/pdf/PDF.php#L43)


#### Arguments
* $objects **mixed**
* $template **mixed**
* $smarty **mixed**



### <a name="method-getTemplateObject"></a>getTemplateObject

```php
mixed PDFCore::getTemplateObject($object)
```





* Visibility: **public**
* Source: [classes/pdf/PDF.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/pdf/PDF.php#L91)


#### Arguments
* $object **mixed**



### <a name="method-render"></a>render

```php
mixed PDFCore::render($display)
```





* Visibility: **public**
* Source: [classes/pdf/PDF.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/pdf/PDF.php#L54)


#### Arguments
* $display **mixed**


