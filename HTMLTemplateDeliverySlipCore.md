HTMLTemplateDeliverySlipCore
===============






* Class name: HTMLTemplateDeliverySlipCore
* Namespace: 
* Parent class: [HTMLTemplate](HTMLTemplateCore)
* This class is defined in classes\pdf\HTMLTemplateDeliverySlip.php line 30





Properties
----------


### $order

    public mixed $order





* Visibility: **public**
* This property is defined in classes\pdf\HTMLTemplateDeliverySlip.php line 32


Methods
-------


### __construct

    mixed HTMLTemplateDeliverySlipCore::__construct(\OrderInvoice $order_invoice, $smarty, $bulk_mode)





* Visibility: **public**
* This method is defined in classes\pdf\HTMLTemplateDeliverySlip.php line 39


#### Arguments
* $order_invoice **[OrderInvoice](OrderInvoiceCore)**
* $smarty **mixed**
* $bulk_mode **mixed**



### getHeader

    string HTMLTemplateDeliverySlipCore::getHeader()

Returns the template's HTML header



* Visibility: **public**
* This method is defined in classes\pdf\HTMLTemplateDeliverySlip.php line 69




### getContent

    string HTMLTemplateDeliverySlipCore::getContent()

Returns the template's HTML content



* Visibility: **public**
* This method is defined in classes\pdf\HTMLTemplateDeliverySlip.php line 82




### getBulkFilename

    string HTMLTemplateDeliverySlipCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**
* This method is defined in classes\pdf\HTMLTemplateDeliverySlip.php line 146




### getFilename

    string HTMLTemplateDeliverySlipCore::getFilename()

Returns the template filename



* Visibility: **public**
* This method is defined in classes\pdf\HTMLTemplateDeliverySlip.php line 156



