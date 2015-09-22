PDFCore
===============






* Class name: PDFCore
* This class is defined in [classes/pdf/PDF.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L30)



Constants
----------

* [TEMPLATE_INVOICE](#constant-TEMPLATE_INVOICE)
* [TEMPLATE_ORDER_RETURN](#constant-TEMPLATE_ORDER_RETURN)
* [TEMPLATE_ORDER_SLIP](#constant-TEMPLATE_ORDER_SLIP)
* [TEMPLATE_DELIVERY_SLIP](#constant-TEMPLATE_DELIVERY_SLIP)
* [TEMPLATE_SUPPLY_ORDER_FORM](#constant-TEMPLATE_SUPPLY_ORDER_FORM)

Properties
----------

* [$filename](#property-$filename)
* [$pdf_renderer](#property-$pdf_renderer)
* [$objects](#property-$objects)
* [$template](#property-$template)
* [$send_bulk_flag](#property-$send_bulk_flag)

Methods
-------
* [__construct](#method-__construct)
* [render](#method-render)
* [getTemplateObject](#method-getTemplateObject)


Constants
----------


### <a name="constant-TEMPLATE_INVOICE"></a>TEMPLATE_INVOICE

    const TEMPLATE_INVOICE = 'Invoice'



* This constant is defined in [classes/pdf/PDF.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L38)


### <a name="constant-TEMPLATE_ORDER_RETURN"></a>TEMPLATE_ORDER_RETURN

    const TEMPLATE_ORDER_RETURN = 'OrderReturn'



* This constant is defined in [classes/pdf/PDF.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L39)


### <a name="constant-TEMPLATE_ORDER_SLIP"></a>TEMPLATE_ORDER_SLIP

    const TEMPLATE_ORDER_SLIP = 'OrderSlip'



* This constant is defined in [classes/pdf/PDF.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L40)


### <a name="constant-TEMPLATE_DELIVERY_SLIP"></a>TEMPLATE_DELIVERY_SLIP

    const TEMPLATE_DELIVERY_SLIP = 'DeliverySlip'



* This constant is defined in [classes/pdf/PDF.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L41)


### <a name="constant-TEMPLATE_SUPPLY_ORDER_FORM"></a>TEMPLATE_SUPPLY_ORDER_FORM

    const TEMPLATE_SUPPLY_ORDER_FORM = 'SupplyOrderForm'



* This constant is defined in [classes/pdf/PDF.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L42)


Properties
----------


### <a name="property-$filename"></a>$filename

    public mixed $filename





* Visibility: **public**
* This property is defined in [classes/pdf/PDF.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L32)


### <a name="property-$pdf_renderer"></a>$pdf_renderer

    public mixed $pdf_renderer





* Visibility: **public**
* This property is defined in [classes/pdf/PDF.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L33)


### <a name="property-$objects"></a>$objects

    public mixed $objects





* Visibility: **public**
* This property is defined in [classes/pdf/PDF.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L34)


### <a name="property-$template"></a>$template

    public mixed $template





* Visibility: **public**
* This property is defined in [classes/pdf/PDF.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L35)


### <a name="property-$send_bulk_flag"></a>$send_bulk_flag

    public mixed $send_bulk_flag = false





* Visibility: **public**
* This property is defined in [classes/pdf/PDF.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L36)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed PDFCore::__construct($objects, $template, $smarty, string $orientation)





* Visibility: **public**
* This method is defined in [classes/pdf/PDF.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L50)


#### Arguments
* $objects **mixed**
* $template **mixed**
* $smarty **mixed**
* $orientation **string**



### <a name="method-render"></a>render

    mixed PDFCore::render(boolean $display)

Render PDF



* Visibility: **public**
* This method is defined in [classes/pdf/PDF.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L73)


#### Arguments
* $display **boolean**



### <a name="method-getTemplateObject"></a>getTemplateObject

    \HTMLTemplate|false PDFCore::getTemplateObject(mixed $object)

Get correct PDF template classes



* Visibility: **public**
* This method is defined in [classes/pdf/PDF.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L117)


#### Arguments
* $object **mixed**


