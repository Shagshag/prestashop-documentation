PDFCore
===============






* Class name: PDFCore
* Namespace: 



Constants
----------


### TEMPLATE_INVOICE

    const TEMPLATE_INVOICE = 'Invoice'





### TEMPLATE_ORDER_RETURN

    const TEMPLATE_ORDER_RETURN = 'OrderReturn'





### TEMPLATE_ORDER_SLIP

    const TEMPLATE_ORDER_SLIP = 'OrderSlip'





### TEMPLATE_DELIVERY_SLIP

    const TEMPLATE_DELIVERY_SLIP = 'DeliverySlip'





### TEMPLATE_SUPPLY_ORDER_FORM

    const TEMPLATE_SUPPLY_ORDER_FORM = 'SupplyOrderForm'





Properties
----------


### $filename

    public mixed $filename





* Visibility: **public**


### $pdf_renderer

    public mixed $pdf_renderer





* Visibility: **public**


### $objects

    public mixed $objects





* Visibility: **public**


### $template

    public mixed $template





* Visibility: **public**


### $send_bulk_flag

    public mixed $send_bulk_flag = false





* Visibility: **public**


Methods
-------


### __construct

    mixed PDFCore::__construct($objects, $template, $smarty, string $orientation)





* Visibility: **public**


#### Arguments
* $objects **mixed**
* $template **mixed**
* $smarty **mixed**
* $orientation **string**



### render

    mixed PDFCore::render(boolean $display)

Render PDF



* Visibility: **public**


#### Arguments
* $display **boolean**



### getTemplateObject

    \HTMLTemplate|false PDFCore::getTemplateObject(mixed $object)

Get correct PDF template classes



* Visibility: **public**


#### Arguments
* $object **mixed**


