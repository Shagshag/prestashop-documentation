HTMLTemplateOrderSlipCore
===============






* Class name: HTMLTemplateOrderSlipCore
* Namespace: 
* Parent class: [HTMLTemplateInvoice](HTMLTemplateInvoiceCore)
* This class is defined in classes\pdf\HTMLTemplateOrderSlip.php line 30





Properties
----------


### $order

    public mixed $order





* Visibility: **public**
* This property is defined in classes\pdf\HTMLTemplateOrderSlip.php line 32


### $order_slip

    public mixed $order_slip





* Visibility: **public**
* This property is defined in classes\pdf\HTMLTemplateOrderSlip.php line 33


Methods
-------


### __construct

    mixed HTMLTemplateOrderSlipCore::__construct(\OrderSlip $order_slip, $smarty)





* Visibility: **public**
* This method is defined in classes\pdf\HTMLTemplateOrderSlip.php line 40


#### Arguments
* $order_slip **[OrderSlip](OrderSlipCore)**
* $smarty **mixed**



### getHeader

    string HTMLTemplateOrderSlipCore::getHeader()

Returns the template's HTML header



* Visibility: **public**
* This method is defined in classes\pdf\HTMLTemplateOrderSlip.php line 65




### getContent

    string HTMLTemplateOrderSlipCore::getContent()

Returns the template's HTML content



* Visibility: **public**
* This method is defined in classes\pdf\HTMLTemplateOrderSlip.php line 80




### getBulkFilename

    string HTMLTemplateOrderSlipCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**
* This method is defined in classes\pdf\HTMLTemplateOrderSlip.php line 189




### getFilename

    string HTMLTemplateOrderSlipCore::getFilename()

Returns the template filename



* Visibility: **public**
* This method is defined in classes\pdf\HTMLTemplateOrderSlip.php line 199




### getTaxTabContent

    String HTMLTemplateOrderSlipCore::getTaxTabContent()

Returns the tax tab content



* Visibility: **public**
* This method is defined in classes\pdf\HTMLTemplateOrderSlip.php line 209




### getTaxBreakdown

    Array HTMLTemplateOrderSlipCore::getTaxBreakdown()

Returns different tax breakdown elements



* Visibility: **protected**
* This method is defined in classes\pdf\HTMLTemplateOrderSlip.php line 235




### getProductTaxesBreakdown

    mixed HTMLTemplateOrderSlipCore::getProductTaxesBreakdown()





* Visibility: **public**
* This method is defined in classes\pdf\HTMLTemplateOrderSlip.php line 269




### getShippingTaxesBreakdown

    Array HTMLTemplateOrderSlipCore::getShippingTaxesBreakdown()

Returns Shipping tax breakdown elements



* Visibility: **public**
* This method is defined in classes\pdf\HTMLTemplateOrderSlip.php line 308



