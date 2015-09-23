Class AdminPdfControllerCore
=====================





* Class name: AdminPdfControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminPdfController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L27)


Contents
--------



### Methods

* [generateDeliverySlipPDFByIdOrder](#method-generateDeliverySlipPDFByIdOrder)
* [generateDeliverySlipPDFByIdOrderInvoice](#method-generateDeliverySlipPDFByIdOrderInvoice)
* [generateInvoicePDFByIdOrder](#method-generateInvoicePDFByIdOrder)
* [generateInvoicePDFByIdOrderInvoice](#method-generateInvoicePDFByIdOrderInvoice)
* [generatePDF](#method-generatePDF)
* [initProcess](#method-initProcess)
* [postProcess](#method-postProcess)
* [processGenerateDeliverySlipPDF](#method-processGenerateDeliverySlipPDF)
* [processGenerateDeliverySlipsPDF](#method-processGenerateDeliverySlipsPDF)
* [processGenerateInvoicePdf](#method-processGenerateInvoicePdf)
* [processGenerateInvoicesPDF](#method-processGenerateInvoicesPDF)
* [processGenerateInvoicesPDF2](#method-processGenerateInvoicesPDF2)
* [processGenerateOrderSlipPDF](#method-processGenerateOrderSlipPDF)
* [processGenerateOrderSlipsPDF](#method-processGenerateOrderSlipsPDF)
* [processGenerateSupplyOrderFormPDF](#method-processGenerateSupplyOrderFormPDF)






Methods
-------


### <a name="method-generateDeliverySlipPDFByIdOrder"></a>generateDeliverySlipPDFByIdOrder

```php
mixed AdminPdfControllerCore::generateDeliverySlipPDFByIdOrder($id_order)
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L143)


#### Arguments
* $id_order **mixed**



### <a name="method-generateDeliverySlipPDFByIdOrderInvoice"></a>generateDeliverySlipPDFByIdOrderInvoice

```php
mixed AdminPdfControllerCore::generateDeliverySlipPDFByIdOrderInvoice($id_order_invoice)
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L153)


#### Arguments
* $id_order_invoice **mixed**



### <a name="method-generateInvoicePDFByIdOrder"></a>generateInvoicePDFByIdOrder

```php
mixed AdminPdfControllerCore::generateInvoicePDFByIdOrder($id_order)
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L162)


#### Arguments
* $id_order **mixed**



### <a name="method-generateInvoicePDFByIdOrderInvoice"></a>generateInvoicePDFByIdOrderInvoice

```php
mixed AdminPdfControllerCore::generateInvoicePDFByIdOrderInvoice($id_order_invoice)
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L173)


#### Arguments
* $id_order_invoice **mixed**



### <a name="method-generatePDF"></a>generatePDF

```php
mixed AdminPdfControllerCore::generatePDF($object, $template)
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 183](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L183)


#### Arguments
* $object **mixed**
* $template **mixed**



### <a name="method-initProcess"></a>initProcess

```php
mixed AdminPdfControllerCore::initProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L37)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminPdfControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L29)




### <a name="method-processGenerateDeliverySlipPDF"></a>processGenerateDeliverySlipPDF

```php
mixed AdminPdfControllerCore::processGenerateDeliverySlipPDF()
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L68)




### <a name="method-processGenerateDeliverySlipsPDF"></a>processGenerateDeliverySlipsPDF

```php
mixed AdminPdfControllerCore::processGenerateDeliverySlipsPDF()
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 119](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L119)




### <a name="method-processGenerateInvoicePdf"></a>processGenerateInvoicePdf

```php
mixed AdminPdfControllerCore::processGenerateInvoicePdf()
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L47)




### <a name="method-processGenerateInvoicesPDF"></a>processGenerateInvoicesPDF

```php
mixed AdminPdfControllerCore::processGenerateInvoicesPDF()
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L83)




### <a name="method-processGenerateInvoicesPDF2"></a>processGenerateInvoicesPDF2

```php
mixed AdminPdfControllerCore::processGenerateInvoicesPDF2()
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L93)




### <a name="method-processGenerateOrderSlipPDF"></a>processGenerateOrderSlipPDF

```php
mixed AdminPdfControllerCore::processGenerateOrderSlipPDF()
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L57)




### <a name="method-processGenerateOrderSlipsPDF"></a>processGenerateOrderSlipsPDF

```php
mixed AdminPdfControllerCore::processGenerateOrderSlipsPDF()
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L106)




### <a name="method-processGenerateSupplyOrderFormPDF"></a>processGenerateSupplyOrderFormPDF

```php
mixed AdminPdfControllerCore::processGenerateSupplyOrderFormPDF()
```





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.2/controllers/admin/AdminPdfController.php#L129)



