Class PDFGeneratorCore
=====================





* Class name: PDFGeneratorCore
* Parent class: TCPDF
* Source: [classes/pdf/PDFGenerator.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L35)


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
* [createContent](#method-createContent)
* [createFooter](#method-createFooter)
* [createHeader](#method-createHeader)
* [render](#method-render)
* [setEncoding](#method-setEncoding)
* [setFontForLang](#method-setFontForLang)
* [writePage](#method-writePage)


Constants
----------


### <a name="constant-DEFAULT_FONT"></a>DEFAULT_FONT

```php
const DEFAULT_FONT = 'dejavusans'
```





* Source: [classes/pdf/PDFGenerator.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L37).


Properties
----------


### <a name="property-$content"></a>$content

```php
public mixed $content
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L41).


### <a name="property-$font"></a>$font

```php
public mixed $font
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L42).


### <a name="property-$font_by_lang"></a>$font_by_lang

```php
public mixed $font_by_lang = array('jp' => 'cid0jp')
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L44).


### <a name="property-$footer"></a>$footer

```php
public mixed $footer
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L40).


### <a name="property-$header"></a>$header

```php
public mixed $header
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L39).


Methods
-------


### <a name="method-Footer"></a>Footer

```php
mixed PDFGeneratorCore::Footer()
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L108)




### <a name="method-Header"></a>Header

```php
mixed PDFGeneratorCore::Header()
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L99)




### <a name="method-createContent"></a>createContent

```php
mixed PDFGeneratorCore::createContent(string $content)
```

create the PDF content



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L80)


#### Arguments
* $content **string** - HTML



### <a name="method-createFooter"></a>createFooter

```php
mixed PDFGeneratorCore::createFooter(string $footer)
```

set the PDF footer



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L70)


#### Arguments
* $footer **string** - HTML



### <a name="method-createHeader"></a>createHeader

```php
mixed PDFGeneratorCore::createHeader(string $header)
```

set the PDF header



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L60)


#### Arguments
* $header **string** - HTML



### <a name="method-render"></a>render

```php
mixed PDFGeneratorCore::render(string $filename)
```

Render the pdf file



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L120)


#### Arguments
* $filename **string**



### <a name="method-setEncoding"></a>setEncoding

```php
mixed PDFGeneratorCore::setEncoding(string $encoding)
```

set the PDF encoding



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L50)


#### Arguments
* $encoding **string**



### <a name="method-setFontForLang"></a>setFontForLang

```php
mixed PDFGeneratorCore::setFontForLang(\unknown_type $iso_lang)
```

Change the font



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L89)


#### Arguments
* $iso_lang **unknown_type**



### <a name="method-writePage"></a>writePage

```php
mixed PDFGeneratorCore::writePage()
```

Write a PDF page



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/pdf/PDFGenerator.php#L132)



