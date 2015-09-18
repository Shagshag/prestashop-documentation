PDFGeneratorCore
===============






* Class name: PDFGeneratorCore
* Namespace: 
* Parent class: TCPDF



Constants
----------


### DEFAULT_FONT

    const DEFAULT_FONT = 'helvetica'





Properties
----------


### $header

    public mixed $header





* Visibility: **public**


### $footer

    public mixed $footer





* Visibility: **public**


### $content

    public mixed $content





* Visibility: **public**


### $font

    public mixed $font





* Visibility: **public**


### $font_by_lang

    public mixed $font_by_lang = array('ja' => 'cid0jp', 'bg' => 'freeserif', 'ru' => 'freeserif', 'uk' => 'freeserif', 'mk' => 'freeserif', 'el' => 'freeserif', 'en' => 'dejavusans', 'vn' => 'dejavusans', 'pl' => 'dejavusans', 'ar' => 'dejavusans', 'fa' => 'dejavusans', 'ur' => 'dejavusans', 'az' => 'dejavusans', 'ca' => 'dejavusans', 'gl' => 'dejavusans', 'hr' => 'dejavusans', 'sr' => 'dejavusans', 'si' => 'dejavusans', 'cs' => 'dejavusans', 'sk' => 'dejavusans', 'ka' => 'dejavusans', 'he' => 'dejavusans', 'lo' => 'dejavusans', 'lt' => 'dejavusans', 'lv' => 'dejavusans', 'tr' => 'dejavusans', 'ko' => 'cid0kr', 'zh' => 'cid0cs', 'tw' => 'cid0cs', 'th' => 'freeserif')





* Visibility: **public**


Methods
-------


### __construct

    mixed PDFGeneratorCore::__construct(boolean $use_cache, string $orientation)





* Visibility: **public**


#### Arguments
* $use_cache **boolean**
* $orientation **string**



### setEncoding

    mixed PDFGeneratorCore::setEncoding(string $encoding)

set the PDF encoding



* Visibility: **public**


#### Arguments
* $encoding **string**



### createHeader

    mixed PDFGeneratorCore::createHeader(string $header)

set the PDF header



* Visibility: **public**


#### Arguments
* $header **string** - &lt;p&gt;HTML&lt;/p&gt;



### createFooter

    mixed PDFGeneratorCore::createFooter(string $footer)

set the PDF footer



* Visibility: **public**


#### Arguments
* $footer **string** - &lt;p&gt;HTML&lt;/p&gt;



### createContent

    mixed PDFGeneratorCore::createContent(string $content)

create the PDF content



* Visibility: **public**


#### Arguments
* $content **string** - &lt;p&gt;HTML&lt;/p&gt;



### setFontForLang

    mixed PDFGeneratorCore::setFontForLang(string $iso_lang)

Change the font



* Visibility: **public**


#### Arguments
* $iso_lang **string**



### Header

    mixed PDFGeneratorCore::Header()





* Visibility: **public**




### Footer

    mixed PDFGeneratorCore::Footer()





* Visibility: **public**




### render

    string PDFGeneratorCore::render(string $filename, boolean $display)

Render HTML template



* Visibility: **public**


#### Arguments
* $filename **string**
* $display **boolean** - &lt;p&gt;true:display to user, false:save, &#039;I&#039;,&#039;D&#039;,&#039;S&#039; as fpdf display&lt;/p&gt;



### writePage

    mixed PDFGeneratorCore::writePage()

Write a PDF page



* Visibility: **public**




### getRandomSeed

    mixed PDFGeneratorCore::getRandomSeed($seed)

Override of TCPDF::getRandomSeed() - getmypid() is blocked on several hosting



* Visibility: **protected**


#### Arguments
* $seed **mixed**


