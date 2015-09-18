HTMLTemplateOrderSlipCore
===============






* Class name: HTMLTemplateOrderSlipCore
* Namespace: 
* Parent class: HTMLTemplateInvoice





Properties
----------


### $order

    public mixed $order





* Visibility: **public**


### $order_slip

    public mixed $order_slip





* Visibility: **public**


Methods
-------


### __construct

    mixed HTMLTemplateOrderSlipCore::__construct(\OrderSlip $order_slip, $smarty)





* Visibility: **public**


#### Arguments
* $order_slip **OrderSlip**
* $smarty **mixed**



### getHeader

    string HTMLTemplateOrderSlipCore::getHeader()

Returns the template's HTML header



* Visibility: **public**




### getContent

    string HTMLTemplateOrderSlipCore::getContent()

Returns the template's HTML content



* Visibility: **public**




### getBulkFilename

    string HTMLTemplateOrderSlipCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**




### getFilename

    string HTMLTemplateOrderSlipCore::getFilename()

Returns the template filename



* Visibility: **public**




### getTaxTabContent

    String HTMLTemplateOrderSlipCore::getTaxTabContent()

Returns the tax tab content



* Visibility: **public**




### getTaxBreakdown

    Array HTMLTemplateOrderSlipCore::getTaxBreakdown()

Returns different tax breakdown elements



* Visibility: **protected**




### getProductTaxesBreakdown

    mixed HTMLTemplateOrderSlipCore::getProductTaxesBreakdown()





* Visibility: **public**




### getShippingTaxesBreakdown

    Array HTMLTemplateOrderSlipCore::getShippingTaxesBreakdown()

Returns Shipping tax breakdown elements



* Visibility: **public**



