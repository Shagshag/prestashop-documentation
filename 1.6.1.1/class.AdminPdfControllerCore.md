Class AdminPdfControllerCore
=====================





* Class name: AdminPdfControllerCore
* Parent class: [AdminController](class.AdminControllerCore)
* Source: [controllers/admin/AdminPdfController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L27)





Methods
-------
* [checkCacheFolder](#method-checkCacheFolder)
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


### <a name="method-checkCacheFolder"></a>checkCacheFolder

    mixed AdminPdfControllerCore::checkCacheFolder()





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L49)




### <a name="method-generateDeliverySlipPDFByIdOrder"></a>generateDeliverySlipPDFByIdOrder

    mixed AdminPdfControllerCore::generateDeliverySlipPDFByIdOrder($id_order)





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L163)


#### Arguments
* $id_order **mixed**



### <a name="method-generateDeliverySlipPDFByIdOrderInvoice"></a>generateDeliverySlipPDFByIdOrderInvoice

    mixed AdminPdfControllerCore::generateDeliverySlipPDFByIdOrderInvoice($id_order_invoice)





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L174)


#### Arguments
* $id_order_invoice **mixed**



### <a name="method-generateInvoicePDFByIdOrder"></a>generateInvoicePDFByIdOrder

    mixed AdminPdfControllerCore::generateInvoicePDFByIdOrder($id_order)





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L184)


#### Arguments
* $id_order **mixed**



### <a name="method-generateInvoicePDFByIdOrderInvoice"></a>generateInvoicePDFByIdOrderInvoice

    mixed AdminPdfControllerCore::generateInvoicePDFByIdOrderInvoice($id_order_invoice)





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 196](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L196)


#### Arguments
* $id_order_invoice **mixed**



### <a name="method-generatePDF"></a>generatePDF

    mixed AdminPdfControllerCore::generatePDF($object, $template)





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 207](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L207)


#### Arguments
* $object **mixed**
* $template **mixed**



### <a name="method-initProcess"></a>initProcess

    mixed AdminPdfControllerCore::initProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L37)




### <a name="method-postProcess"></a>postProcess

    mixed AdminPdfControllerCore::postProcess()





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L29)




### <a name="method-processGenerateDeliverySlipPDF"></a>processGenerateDeliverySlipPDF

    mixed AdminPdfControllerCore::processGenerateDeliverySlipPDF()





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L80)




### <a name="method-processGenerateDeliverySlipsPDF"></a>processGenerateDeliverySlipsPDF

    mixed AdminPdfControllerCore::processGenerateDeliverySlipsPDF()





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 136](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L136)




### <a name="method-processGenerateInvoicePdf"></a>processGenerateInvoicePdf

    mixed AdminPdfControllerCore::processGenerateInvoicePdf()





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L56)




### <a name="method-processGenerateInvoicesPDF"></a>processGenerateInvoicesPDF

    mixed AdminPdfControllerCore::processGenerateInvoicesPDF()





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 94](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L94)




### <a name="method-processGenerateInvoicesPDF2"></a>processGenerateInvoicesPDF2

    mixed AdminPdfControllerCore::processGenerateInvoicesPDF2()





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L105)




### <a name="method-processGenerateOrderSlipPDF"></a>processGenerateOrderSlipPDF

    mixed AdminPdfControllerCore::processGenerateOrderSlipPDF()





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L67)




### <a name="method-processGenerateOrderSlipsPDF"></a>processGenerateOrderSlipsPDF

    mixed AdminPdfControllerCore::processGenerateOrderSlipsPDF()





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L121)




### <a name="method-processGenerateSupplyOrderFormPDF"></a>processGenerateSupplyOrderFormPDF

    mixed AdminPdfControllerCore::processGenerateSupplyOrderFormPDF()





* Visibility: **public**
* Source: [controllers/admin/AdminPdfController.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminPdfController.php#L147)



