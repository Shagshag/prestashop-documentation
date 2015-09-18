HTMLTemplateInvoiceCore
===============






* Class name: HTMLTemplateInvoiceCore
* Namespace: 
* Parent class: HTMLTemplate





Properties
----------


### $order

    public mixed $order





* Visibility: **public**


### $order_invoice

    public mixed $order_invoice





* Visibility: **public**


### $available_in_your_account

    public mixed $available_in_your_account = false





* Visibility: **public**


Methods
-------


### __construct

    mixed HTMLTemplateInvoiceCore::__construct(\OrderInvoice $order_invoice, $smarty, $bulk_mode)





* Visibility: **public**


#### Arguments
* $order_invoice **OrderInvoice**
* $smarty **mixed**
* $bulk_mode **mixed**



### getHeader

    string HTMLTemplateInvoiceCore::getHeader()

Returns the template's HTML header



* Visibility: **public**




### computeLayout

    Array HTMLTemplateInvoiceCore::computeLayout($params)

Compute layout elements size



* Visibility: **private**


#### Arguments
* $params **mixed** - &lt;p&gt;Array Layout elements&lt;/p&gt;



### getContent

    string HTMLTemplateInvoiceCore::getContent()

Returns the template's HTML content



* Visibility: **public**




### getTaxTabContent

    String HTMLTemplateInvoiceCore::getTaxTabContent()

Returns the tax tab content



* Visibility: **public**




### getTaxBreakdown

    Array HTMLTemplateInvoiceCore::getTaxBreakdown()

Returns different tax breakdown elements



* Visibility: **protected**




### getTemplateByCountry

    mixed HTMLTemplateInvoiceCore::getTemplateByCountry(string $iso_country)

Returns the invoice template associated to the country iso_code



* Visibility: **protected**


#### Arguments
* $iso_country **string**



### getBulkFilename

    string HTMLTemplateInvoiceCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**




### getFilename

    string HTMLTemplateInvoiceCore::getFilename()

Returns the template filename



* Visibility: **public**



