Class PDFGeneratorCore
=====================





* Class name: PDFGeneratorCore
* Parent class: TCPDF
* Source: [classes/pdf/PDFGenerator.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L33)


Contents
--------

### Constants

* [DEFAULT_FONT](#constant-DEFAULT_FONT)

### Properties

* [$content](#property-$content)
* [$font](#property-$font)
* [$font_by_lang](#property-$font_by_lang)
* [$footer](#property-$footer)
* [$header](#property-$header)

### Methods

* [Footer](#method-Footer)
* [Header](#method-Header)
* [__construct](#method-__construct)
* [createContent](#method-createContent)
* [createFooter](#method-createFooter)
* [createHeader](#method-createHeader)
* [getRandomSeed](#method-getRandomSeed)
* [render](#method-render)
* [setEncoding](#method-setEncoding)
* [setFontForLang](#method-setFontForLang)
* [writePage](#method-writePage)


Constants
----------


### <a name="constant-DEFAULT_FONT"></a>DEFAULT_FONT

```php
const DEFAULT_FONT = 'helvetica'
```





* Source: [classes/pdf/PDFGenerator.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L35).


Properties
----------


### <a name="property-$content"></a>$content

```php
public mixed $content
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L39).


### <a name="property-$font"></a>$font

```php
public mixed $font
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L40).


### <a name="property-$font_by_lang"></a>$font_by_lang

```php
public mixed $font_by_lang = array('ja' => 'cid0jp', 'bg' => 'freeserif', 'ru' => 'freeserif', 'uk' => 'freeserif', 'mk' => 'freeserif', 'el' => 'freeserif', 'en' => 'dejavusans', 'vn' => 'dejavusans', 'pl' => 'dejavusans', 'ar' => 'dejavusans', 'fa' => 'dejavusans', 'ur' => 'dejavusans', 'az' => 'dejavusans', 'ca' => 'dejavusans', 'gl' => 'dejavusans', 'hr' => 'dejavusans', 'sr' => 'dejavusans', 'si' => 'dejavusans', 'cs' => 'dejavusans', 'sk' => 'dejavusans', 'ka' => 'dejavusans', 'he' => 'dejavusans', 'lo' => 'dejavusans', 'lv' => 'dejavusans', 'tr' => 'dejavusans', 'ko' => 'cid0kr', 'zh' => 'cid0cs', 'tw' => 'cid0cs', 'th' => 'freeserif')
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L42).


### <a name="property-$footer"></a>$footer

```php
public mixed $footer
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L38).


### <a name="property-$header"></a>$header

```php
public mixed $header
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L37).


Methods
-------


### <a name="method-Footer"></a>Footer

```php
mixed PDFGeneratorCore::Footer()
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 147](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L147)




### <a name="method-Header"></a>Header

```php
mixed PDFGeneratorCore::Header()
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L139)




### <a name="method-__construct"></a>__construct

```php
mixed PDFGeneratorCore::__construct($use_cache, $orientation)
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L75)


#### Arguments
* $use_cache **mixed**
* $orientation **mixed**



### <a name="method-createContent"></a>createContent

```php
mixed PDFGeneratorCore::createContent(string $content)
```

create the PDF content



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L115)


#### Arguments
* $content **string** - HTML



### <a name="method-createFooter"></a>createFooter

```php
mixed PDFGeneratorCore::createFooter(string $footer)
```

set the PDF footer



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 105](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L105)


#### Arguments
* $footer **string** - HTML



### <a name="method-createHeader"></a>createHeader

```php
mixed PDFGeneratorCore::createHeader(string $header)
```

set the PDF header



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L95)


#### Arguments
* $header **string** - HTML



### <a name="method-getRandomSeed"></a>getRandomSeed

```php
mixed PDFGeneratorCore::getRandomSeed($seed)
```

Override of TCPDF::getRandomSeed() - getmypid() is blocked on several hosting



* Visibility: **protected**
* Source: [classes/pdf/PDFGenerator.php line 199](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L199)


#### Arguments
* $seed **mixed**



### <a name="method-render"></a>render

```php
mixed PDFGeneratorCore::render(string $filename, $display)
```

Render the pdf file



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 159](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L159)


#### Arguments
* $filename **string**
* $display **mixed** - :  true:display to user, false:save, &#039;I&#039;,&#039;D&#039;,&#039;S&#039; as fpdf display



### <a name="method-setEncoding"></a>setEncoding

```php
mixed PDFGeneratorCore::setEncoding(string $encoding)
```

set the PDF encoding



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L85)


#### Arguments
* $encoding **string**



### <a name="method-setFontForLang"></a>setFontForLang

```php
mixed PDFGeneratorCore::setFontForLang(string $iso_lang)
```

Change the font



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L124)


#### Arguments
* $iso_lang **string**



### <a name="method-writePage"></a>writePage

```php
mixed PDFGeneratorCore::writePage()
```

Write a PDF page



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 185](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/classes/pdf/PDFGenerator.php#L185)



