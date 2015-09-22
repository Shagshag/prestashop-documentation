Class PDFCore
=====================





* Class name: PDFCore
* Source: [classes/pdf/PDF.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L30)

Constants
----------

* [TEMPLATE_DELIVERY_SLIP](#constant-TEMPLATE_DELIVERY_SLIP)
* [TEMPLATE_INVOICE](#constant-TEMPLATE_INVOICE)
* [TEMPLATE_ORDER_RETURN](#constant-TEMPLATE_ORDER_RETURN)
* [TEMPLATE_ORDER_SLIP](#constant-TEMPLATE_ORDER_SLIP)
* [TEMPLATE_SUPPLY_ORDER_FORM](#constant-TEMPLATE_SUPPLY_ORDER_FORM)

Properties
----------

* [$filename](#property-$filename)
* [$objects](#property-$objects)
* [$pdf_renderer](#property-$pdf_renderer)
* [$send_bulk_flag](#property-$send_bulk_flag)
* [$template](#property-$template)

Methods
-------
* [__construct](#method-__construct)
* [getTemplateObject](#method-getTemplateObject)
* [render](#method-render)


Constants
----------


### <a name="constant-TEMPLATE_DELIVERY_SLIP"></a>TEMPLATE_DELIVERY_SLIP

    const TEMPLATE_DELIVERY_SLIP = 'DeliverySlip'



* Source: [classes/pdf/PDF.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L41)


### <a name="constant-TEMPLATE_INVOICE"></a>TEMPLATE_INVOICE

    const TEMPLATE_INVOICE = 'Invoice'



* Source: [classes/pdf/PDF.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L38)


### <a name="constant-TEMPLATE_ORDER_RETURN"></a>TEMPLATE_ORDER_RETURN

    const TEMPLATE_ORDER_RETURN = 'OrderReturn'



* Source: [classes/pdf/PDF.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L39)


### <a name="constant-TEMPLATE_ORDER_SLIP"></a>TEMPLATE_ORDER_SLIP

    const TEMPLATE_ORDER_SLIP = 'OrderSlip'



* Source: [classes/pdf/PDF.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L40)


### <a name="constant-TEMPLATE_SUPPLY_ORDER_FORM"></a>TEMPLATE_SUPPLY_ORDER_FORM

    const TEMPLATE_SUPPLY_ORDER_FORM = 'SupplyOrderForm'



* Source: [classes/pdf/PDF.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L42)


Properties
----------


### <a name="property-$filename"></a>$filename

    public mixed $filename





* Visibility: **public**
* Source: [classes/pdf/PDF.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L32)


### <a name="property-$objects"></a>$objects

    public mixed $objects





* Visibility: **public**
* Source: [classes/pdf/PDF.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L34)


### <a name="property-$pdf_renderer"></a>$pdf_renderer

    public mixed $pdf_renderer





* Visibility: **public**
* Source: [classes/pdf/PDF.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L33)


### <a name="property-$send_bulk_flag"></a>$send_bulk_flag

    public mixed $send_bulk_flag = false





* Visibility: **public**
* Source: [classes/pdf/PDF.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L36)


### <a name="property-$template"></a>$template

    public mixed $template





* Visibility: **public**
* Source: [classes/pdf/PDF.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L35)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed PDFCore::__construct($objects, $template, $smarty, string $orientation)





* Visibility: **public**
* Source: [classes/pdf/PDF.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L50)


#### Arguments
* $objects **mixed**
* $template **mixed**
* $smarty **mixed**
* $orientation **string**



### <a name="method-getTemplateObject"></a>getTemplateObject

    \HTMLTemplate|false PDFCore::getTemplateObject(mixed $object)

Get correct PDF template classes



* Visibility: **public**
* Source: [classes/pdf/PDF.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L117)


#### Arguments
* $object **mixed**



### <a name="method-render"></a>render

    mixed PDFCore::render(boolean $display)

Render PDF



* Visibility: **public**
* Source: [classes/pdf/PDF.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L73)


#### Arguments
* $display **boolean**


