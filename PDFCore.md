PDFCore
===============






* Class name: PDFCore
* This class is defined in [classes/pdf/PDF.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#L30)



Constants
----------


### TEMPLATE_INVOICE

    const TEMPLATE_INVOICE = 'Invoice'



* This constant is defined in [classes/pdf/PDF.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#38)


### TEMPLATE_ORDER_RETURN

    const TEMPLATE_ORDER_RETURN = 'OrderReturn'



* This constant is defined in [classes/pdf/PDF.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#39)


### TEMPLATE_ORDER_SLIP

    const TEMPLATE_ORDER_SLIP = 'OrderSlip'



* This constant is defined in [classes/pdf/PDF.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#40)


### TEMPLATE_DELIVERY_SLIP

    const TEMPLATE_DELIVERY_SLIP = 'DeliverySlip'



* This constant is defined in [classes/pdf/PDF.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#41)


### TEMPLATE_SUPPLY_ORDER_FORM

    const TEMPLATE_SUPPLY_ORDER_FORM = 'SupplyOrderForm'



* This constant is defined in [classes/pdf/PDF.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#42)


Properties
----------


### $filename

    public mixed $filename





* Visibility: **public**
* This property is defined in [classes/pdf/PDF.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#32)


### $pdf_renderer

    public mixed $pdf_renderer





* Visibility: **public**
* This property is defined in [classes/pdf/PDF.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#33)


### $objects

    public mixed $objects





* Visibility: **public**
* This property is defined in [classes/pdf/PDF.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#34)


### $template

    public mixed $template





* Visibility: **public**
* This property is defined in [classes/pdf/PDF.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#35)


### $send_bulk_flag

    public mixed $send_bulk_flag = false





* Visibility: **public**
* This property is defined in [classes/pdf/PDF.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#36)


Methods
-------


### __construct

    mixed PDFCore::__construct($objects, $template, $smarty, string $orientation)





* Visibility: **public**
* This method is defined in [classes/pdf/PDF.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#50)


#### Arguments
* $objects **mixed**
* $template **mixed**
* $smarty **mixed**
* $orientation **string**



### render

    mixed PDFCore::render(boolean $display)

Render PDF



* Visibility: **public**
* This method is defined in [classes/pdf/PDF.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#73)


#### Arguments
* $display **boolean**



### getTemplateObject

    \HTMLTemplate|false PDFCore::getTemplateObject(mixed $object)

Get correct PDF template classes



* Visibility: **public**
* This method is defined in [classes/pdf/PDF.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDF.php#117)


#### Arguments
* $object **mixed**


