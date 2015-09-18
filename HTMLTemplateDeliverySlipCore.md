HTMLTemplateDeliverySlipCore
===============






* Class name: HTMLTemplateDeliverySlipCore
* Namespace: 
* Parent class: HTMLTemplate





Properties
----------


### $order

    public mixed $order





* Visibility: **public**


Methods
-------


### __construct

    mixed HTMLTemplateDeliverySlipCore::__construct(\OrderInvoice $order_invoice, $smarty, $bulk_mode)





* Visibility: **public**


#### Arguments
* $order_invoice **OrderInvoice**
* $smarty **mixed**
* $bulk_mode **mixed**



### getHeader

    string HTMLTemplateDeliverySlipCore::getHeader()

Returns the template's HTML header



* Visibility: **public**




### getContent

    string HTMLTemplateDeliverySlipCore::getContent()

Returns the template's HTML content



* Visibility: **public**




### getBulkFilename

    string HTMLTemplateDeliverySlipCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**




### getFilename

    string HTMLTemplateDeliverySlipCore::getFilename()

Returns the template filename



* Visibility: **public**



