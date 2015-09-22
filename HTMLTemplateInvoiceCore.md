HTMLTemplateInvoiceCore
===============






* Class name: HTMLTemplateInvoiceCore
* Namespace: 
* Parent class: [HTMLTemplate](HTMLTemplateCore)

* This class is defined in [classes/pdf/HTMLTemplateInvoice.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#30)





Properties
----------


### $order

    public mixed $order





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateInvoice.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#32)


### $order_invoice

    public mixed $order_invoice





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateInvoice.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#33)


### $available_in_your_account

    public mixed $available_in_your_account = false





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateInvoice.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#34)


Methods
-------


### __construct

    mixed HTMLTemplateInvoiceCore::__construct(\OrderInvoice $order_invoice, $smarty, $bulk_mode)





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#41)


#### Arguments
* $order_invoice **[OrderInvoice](OrderInvoiceCore)**
* $smarty **mixed**
* $bulk_mode **mixed**



### getHeader

    string HTMLTemplateInvoiceCore::getHeader()

Returns the template's HTML header



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#71)




### computeLayout

    Array HTMLTemplateInvoiceCore::computeLayout($params)

Compute layout elements size



* Visibility: **private**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#86)


#### Arguments
* $params **mixed** - &lt;p&gt;Array Layout elements&lt;/p&gt;



### getContent

    string HTMLTemplateInvoiceCore::getContent()

Returns the template's HTML content



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#143)




### getTaxTabContent

    String HTMLTemplateInvoiceCore::getTaxTabContent()

Returns the tax tab content



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 362](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#362)




### getTaxBreakdown

    Array HTMLTemplateInvoiceCore::getTaxBreakdown()

Returns different tax breakdown elements



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 402](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#402)




### getTemplateByCountry

    mixed HTMLTemplateInvoiceCore::getTemplateByCountry(string $iso_country)

Returns the invoice template associated to the country iso_code



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 464](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#464)


#### Arguments
* $iso_country **string**



### getBulkFilename

    string HTMLTemplateInvoiceCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 484](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#484)




### getFilename

    string HTMLTemplateInvoiceCore::getFilename()

Returns the template filename



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateInvoice.php line 494](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateInvoice.php#494)



