PDFGeneratorCore
===============






* Class name: PDFGeneratorCore
* Namespace: 
* Parent class: TCPDF

* This class is defined in [classes/pdf/PDFGenerator.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#33)



Constants
----------


### DEFAULT_FONT

    const DEFAULT_FONT = 'helvetica'



* This constant is defined in [classes/pdf/PDFGenerator.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#35)


Properties
----------


### $header

    public mixed $header





* Visibility: **public**
* This property is defined in [classes/pdf/PDFGenerator.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#37)


### $footer

    public mixed $footer





* Visibility: **public**
* This property is defined in [classes/pdf/PDFGenerator.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#38)


### $content

    public mixed $content





* Visibility: **public**
* This property is defined in [classes/pdf/PDFGenerator.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#39)


### $font

    public mixed $font





* Visibility: **public**
* This property is defined in [classes/pdf/PDFGenerator.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#40)


### $font_by_lang

    public mixed $font_by_lang = array('ja' => 'cid0jp', 'bg' => 'freeserif', 'ru' => 'freeserif', 'uk' => 'freeserif', 'mk' => 'freeserif', 'el' => 'freeserif', 'en' => 'dejavusans', 'vn' => 'dejavusans', 'pl' => 'dejavusans', 'ar' => 'dejavusans', 'fa' => 'dejavusans', 'ur' => 'dejavusans', 'az' => 'dejavusans', 'ca' => 'dejavusans', 'gl' => 'dejavusans', 'hr' => 'dejavusans', 'sr' => 'dejavusans', 'si' => 'dejavusans', 'cs' => 'dejavusans', 'sk' => 'dejavusans', 'ka' => 'dejavusans', 'he' => 'dejavusans', 'lo' => 'dejavusans', 'lt' => 'dejavusans', 'lv' => 'dejavusans', 'tr' => 'dejavusans', 'ko' => 'cid0kr', 'zh' => 'cid0cs', 'tw' => 'cid0cs', 'th' => 'freeserif')





* Visibility: **public**
* This property is defined in [classes/pdf/PDFGenerator.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#42)


Methods
-------


### __construct

    mixed PDFGeneratorCore::__construct(boolean $use_cache, string $orientation)





* Visibility: **public**
* This method is defined in [classes/pdf/PDFGenerator.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#79)


#### Arguments
* $use_cache **boolean**
* $orientation **string**



### setEncoding

    mixed PDFGeneratorCore::setEncoding(string $encoding)

set the PDF encoding



* Visibility: **public**
* This method is defined in [classes/pdf/PDFGenerator.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#90)


#### Arguments
* $encoding **string**



### createHeader

    mixed PDFGeneratorCore::createHeader(string $header)

set the PDF header



* Visibility: **public**
* This method is defined in [classes/pdf/PDFGenerator.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#101)


#### Arguments
* $header **string** - &lt;p&gt;HTML&lt;/p&gt;



### createFooter

    mixed PDFGeneratorCore::createFooter(string $footer)

set the PDF footer



* Visibility: **public**
* This method is defined in [classes/pdf/PDFGenerator.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#112)


#### Arguments
* $footer **string** - &lt;p&gt;HTML&lt;/p&gt;



### createContent

    mixed PDFGeneratorCore::createContent(string $content)

create the PDF content



* Visibility: **public**
* This method is defined in [classes/pdf/PDFGenerator.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#123)


#### Arguments
* $content **string** - &lt;p&gt;HTML&lt;/p&gt;



### setFontForLang

    mixed PDFGeneratorCore::setFontForLang(string $iso_lang)

Change the font



* Visibility: **public**
* This method is defined in [classes/pdf/PDFGenerator.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#133)


#### Arguments
* $iso_lang **string**



### Header

    mixed PDFGeneratorCore::Header()





* Visibility: **public**
* This method is defined in [classes/pdf/PDFGenerator.php line 149](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#149)




### Footer

    mixed PDFGeneratorCore::Footer()





* Visibility: **public**
* This method is defined in [classes/pdf/PDFGenerator.php line 157](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#157)




### render

    string PDFGeneratorCore::render(string $filename, boolean $display)

Render HTML template



* Visibility: **public**
* This method is defined in [classes/pdf/PDFGenerator.php line 170](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#170)


#### Arguments
* $filename **string**
* $display **boolean** - &lt;p&gt;true:display to user, false:save, &#039;I&#039;,&#039;D&#039;,&#039;S&#039; as fpdf display&lt;/p&gt;



### writePage

    mixed PDFGeneratorCore::writePage()

Write a PDF page



* Visibility: **public**
* This method is defined in [classes/pdf/PDFGenerator.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#198)




### getRandomSeed

    mixed PDFGeneratorCore::getRandomSeed($seed)

Override of TCPDF::getRandomSeed() - getmypid() is blocked on several hosting



* Visibility: **protected**
* This method is defined in [classes/pdf/PDFGenerator.php line 210](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/PDFGenerator.php#210)


#### Arguments
* $seed **mixed**


