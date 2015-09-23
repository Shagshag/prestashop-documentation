Class PDFCore
=====================





* Class name: PDFCore
* Parent class: [PDF_PageGroupCore](class.PDF_PageGroupCore.md)
* Source: [classes/PDF.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L84)


Contents
--------


### Properties

* [$CurrPageGroup](#property-$CurrPageGroup)
* [$NewPageGroup](#property-$NewPageGroup)
* [$PageGroups](#property-$PageGroups)
* [$_fpdf_core_fonts](#property-$_fpdf_core_fonts)
* [$_iso](#property-$_iso)
* [$_pdfparams](#property-$_pdfparams)
* [$_priceDisplayMethod](#property-$_priceDisplayMethod)
* [$currency](#property-$currency)
* [$delivery](#property-$delivery)
* [$order](#property-$order)
* [$orderReturn](#property-$orderReturn)
* [$orderSlip](#property-$orderSlip)

### Methods

* [DiscTab](#method-DiscTab)
* [Footer](#method-Footer)
* [GroupPageNo](#method-GroupPageNo)
* [Header](#method-Header)
* [PageGroupAlias](#method-PageGroupAlias)
* [ProdReturnTab](#method-ProdReturnTab)
* [ProdTab](#method-ProdTab)
* [ProdTabHeader](#method-ProdTabHeader)
* [StartPageGroup](#method-StartPageGroup)
* [TaxTab](#method-TaxTab)
* [__construct](#method-__construct)
* [_beginpage](#method-_beginpage)
* [_builMerchantFooterDetail](#method-_builMerchantFooterDetail)
* [_getCompleteUSAddressFormat](#method-_getCompleteUSAddressFormat)
* [_initPDFFonts](#method-_initPDFFonts)
* [_isPngFile](#method-_isPngFile)
* [_putpages](#method-_putpages)
* [convertSign](#method-convertSign)
* [embedfont](#method-embedfont)
* [encoding](#method-encoding)
* [fontname](#method-fontname)
* [generateHeaderAddresses](#method-generateHeaderAddresses)
* [invoice](#method-invoice)
* [l](#method-l)
* [multipleDelivery](#method-multipleDelivery)
* [multipleInvoices](#method-multipleInvoices)
* [multipleOrderSlips](#method-multipleOrderSlips)
* [orderReturn](#method-orderReturn)
* [priceBreakDownCalculation](#method-priceBreakDownCalculation)




Properties
----------


### <a name="property-$CurrPageGroup"></a>$CurrPageGroup

```php
public mixed $CurrPageGroup
```





* Visibility: **public**
* Source: [classes/PDF.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L34).


### <a name="property-$NewPageGroup"></a>$NewPageGroup

```php
public mixed $NewPageGroup
```





* Visibility: **public**
* Source: [classes/PDF.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L32).


### <a name="property-$PageGroups"></a>$PageGroups

```php
public mixed $PageGroups
```





* Visibility: **public**
* Source: [classes/PDF.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L33).


### <a name="property-$_fpdf_core_fonts"></a>$_fpdf_core_fonts

```php
protected mixed $_fpdf_core_fonts = array('courier', 'helvetica', 'helveticab', 'helveticabi', 'helveticai', 'symbol', 'times', 'timesb', 'timesbi', 'timesi', 'zapfdingbats')
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/PDF.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L100).


### <a name="property-$_iso"></a>$_iso

```php
protected mixed $_iso
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/PDF.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L95).


### <a name="property-$_pdfparams"></a>$_pdfparams

```php
protected array $_pdfparams = array()
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/PDF.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L99).


### <a name="property-$_priceDisplayMethod"></a>$_priceDisplayMethod

```php
protected mixed $_priceDisplayMethod
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/PDF.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L90).


### <a name="property-$currency"></a>$currency

```php
protected object $currency = NULL
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/PDF.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L93).


### <a name="property-$delivery"></a>$delivery

```php
protected mixed $delivery = NULL
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/PDF.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L89).


### <a name="property-$order"></a>$order

```php
protected mixed $order = NULL
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/PDF.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L86).


### <a name="property-$orderReturn"></a>$orderReturn

```php
protected mixed $orderReturn = NULL
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/PDF.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L87).


### <a name="property-$orderSlip"></a>$orderSlip

```php
protected mixed $orderSlip = NULL
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/PDF.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L88).


Methods
-------


### <a name="method-DiscTab"></a>DiscTab

```php
mixed PDFCore::DiscTab()
```

Discount table with value, quantities.

..

* Visibility: **public**
* Source: [classes/PDF.php line 918](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L918)




### <a name="method-Footer"></a>Footer

```php
mixed PDFCore::Footer()
```

Invoice footer



* Visibility: **public**
* Source: [classes/PDF.php line 258](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L258)




### <a name="method-GroupPageNo"></a>GroupPageNo

```php
mixed PDFCore::GroupPageNo()
```





* Visibility: **public**
* Source: [classes/PDF.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L43)




### <a name="method-Header"></a>Header

```php
mixed PDFCore::Header()
```

Invoice header



* Visibility: **public**
* Source: [classes/PDF.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L140)




### <a name="method-PageGroupAlias"></a>PageGroupAlias

```php
mixed PDFCore::PageGroupAlias()
```





* Visibility: **public**
* Source: [classes/PDF.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L49)




### <a name="method-ProdReturnTab"></a>ProdReturnTab

```php
mixed PDFCore::ProdReturnTab()
```

Product table with references, quantities.

..

* Visibility: **public**
* Source: [classes/PDF.php line 445](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L445)




### <a name="method-ProdTab"></a>ProdTab

```php
mixed PDFCore::ProdTab($delivery)
```

Product table with price, quantities.

..

* Visibility: **public**
* Source: [classes/PDF.php line 787](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L787)


#### Arguments
* $delivery **mixed**



### <a name="method-ProdTabHeader"></a>ProdTabHeader

```php
mixed PDFCore::ProdTabHeader($delivery)
```





* Visibility: **public**
* Source: [classes/PDF.php line 752](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L752)


#### Arguments
* $delivery **mixed**



### <a name="method-StartPageGroup"></a>StartPageGroup

```php
mixed PDFCore::StartPageGroup()
```





* Visibility: **public**
* Source: [classes/PDF.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L37)




### <a name="method-TaxTab"></a>TaxTab

```php
mixed PDFCore::TaxTab($priceBreakDown)
```

Tax table



* Visibility: **public**
* Source: [classes/PDF.php line 1072](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L1072)


#### Arguments
* $priceBreakDown **mixed**



### <a name="method-__construct"></a>__construct

```php
mixed PDFCore::__construct($orientation, $unit, $format)
```

Constructor



* Visibility: **public**
* Source: [classes/PDF.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L105)


#### Arguments
* $orientation **mixed**
* $unit **mixed**
* $format **mixed**



### <a name="method-_beginpage"></a>_beginpage

```php
mixed PDFCore::_beginpage($orientation, $arg2)
```





* Visibility: **public**
* Source: [classes/PDF.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L54)


#### Arguments
* $orientation **mixed**
* $arg2 **mixed**



### <a name="method-_builMerchantFooterDetail"></a>_builMerchantFooterDetail

```php
mixed PDFCore::_builMerchantFooterDetail($conf)
```





* Visibility: **private**
* Source: [classes/PDF.php line 228](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L228)


#### Arguments
* $conf **mixed**



### <a name="method-_getCompleteUSAddressFormat"></a>_getCompleteUSAddressFormat

```php
mixed PDFCore::_getCompleteUSAddressFormat($conf)
```





* Visibility: **private**
* Source: [classes/PDF.php line 208](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L208)


#### Arguments
* $conf **mixed**



### <a name="method-_initPDFFonts"></a>_initPDFFonts

```php
mixed PDFCore::_initPDFFonts()
```





* Visibility: **protected**
* Source: [classes/PDF.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L112)




### <a name="method-_isPngFile"></a>_isPngFile

```php
mixed PDFCore::_isPngFile($file)
```





* Visibility: **private**
* Source: [classes/PDF.php line 186](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L186)


#### Arguments
* $file **mixed**



### <a name="method-_putpages"></a>_putpages

```php
mixed PDFCore::_putpages()
```





* Visibility: **public**
* Source: [classes/PDF.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L70)




### <a name="method-convertSign"></a>convertSign

```php
mixed PDFCore::convertSign($s)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/PDF.php line 1170](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L1170)


#### Arguments
* $s **mixed**



### <a name="method-embedfont"></a>embedfont

```php
mixed PDFCore::embedfont()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/PDF.php line 1197](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L1197)




### <a name="method-encoding"></a>encoding

```php
mixed PDFCore::encoding()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/PDF.php line 1192](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L1192)




### <a name="method-fontname"></a>fontname

```php
mixed PDFCore::fontname()
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/PDF.php line 1202](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L1202)




### <a name="method-generateHeaderAddresses"></a>generateHeaderAddresses

```php
mixed PDFCore::generateHeaderAddresses($pdf, $order, $addressType, $patternRules, $width)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/PDF.php line 476](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L476)


#### Arguments
* $pdf **mixed**
* $order **mixed**
* $addressType **mixed**
* $patternRules **mixed**
* $width **mixed**



### <a name="method-invoice"></a>invoice

```php
mixed PDFCore::invoice(object $order, string $mode, $multiple, $pdf, $slip, $delivery, \Context $context)
```

Main



* Visibility: **public**
* This method is **static**.
* Source: [classes/PDF.php line 538](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L538)


#### Arguments
* $order **object** - Order
* $mode **string** - Download or display (optional)
* $multiple **mixed**
* $pdf **mixed**
* $slip **mixed**
* $delivery **mixed**
* $context **[Context](class.ContextCore.md)**



### <a name="method-l"></a>l

```php
mixed PDFCore::l($string)
```





* Visibility: **protected**
* This method is **static**.
* Source: [classes/PDF.php line 1177](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L1177)


#### Arguments
* $string **mixed**



### <a name="method-multipleDelivery"></a>multipleDelivery

```php
mixed PDFCore::multipleDelivery($slips)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/PDF.php line 351](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L351)


#### Arguments
* $slips **mixed**



### <a name="method-multipleInvoices"></a>multipleInvoices

```php
mixed PDFCore::multipleInvoices($invoices)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/PDF.php line 325](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L325)


#### Arguments
* $invoices **mixed**



### <a name="method-multipleOrderSlips"></a>multipleOrderSlips

```php
mixed PDFCore::multipleOrderSlips($orderSlips)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/PDF.php line 337](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L337)


#### Arguments
* $orderSlips **mixed**



### <a name="method-orderReturn"></a>orderReturn

```php
mixed PDFCore::orderReturn($orderReturn, $mode, $multiple, $pdf)
```





* Visibility: **public**
* This method is **static**.
* Source: [classes/PDF.php line 363](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L363)


#### Arguments
* $orderReturn **mixed**
* $mode **mixed**
* $multiple **mixed**
* $pdf **mixed**



### <a name="method-priceBreakDownCalculation"></a>priceBreakDownCalculation

```php
mixed PDFCore::priceBreakDownCalculation($priceBreakDown)
```





* Visibility: **public**
* Source: [classes/PDF.php line 939](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/PDF.php#L939)


#### Arguments
* $priceBreakDown **mixed**


