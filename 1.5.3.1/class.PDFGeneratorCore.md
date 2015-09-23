Class PDFGeneratorCore
=====================





* Class name: PDFGeneratorCore
* Parent class: TCPDF
* Source: [classes/pdf/PDFGenerator.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L33)


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





* Source: [classes/pdf/PDFGenerator.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L35).


Properties
----------


### <a name="property-$content"></a>$content

```php
public mixed $content
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L39).


### <a name="property-$font"></a>$font

```php
public mixed $font
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L40).


### <a name="property-$font_by_lang"></a>$font_by_lang

```php
public mixed $font_by_lang = array('jp' => 'cid0jp')
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L42).


### <a name="property-$footer"></a>$footer

```php
public mixed $footer
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L38).


### <a name="property-$header"></a>$header

```php
public mixed $header
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L37).


Methods
-------


### <a name="method-Footer"></a>Footer

```php
mixed PDFGeneratorCore::Footer()
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L115)




### <a name="method-Header"></a>Header

```php
mixed PDFGeneratorCore::Header()
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L107)




### <a name="method-__construct"></a>__construct

```php
mixed PDFGeneratorCore::__construct($use_cache)
```





* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L45)


#### Arguments
* $use_cache **mixed**



### <a name="method-createContent"></a>createContent

```php
mixed PDFGeneratorCore::createContent(string $content)
```

create the PDF content



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L84)


#### Arguments
* $content **string** - HTML



### <a name="method-createFooter"></a>createFooter

```php
mixed PDFGeneratorCore::createFooter(string $footer)
```

set the PDF footer



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L74)


#### Arguments
* $footer **string** - HTML



### <a name="method-createHeader"></a>createHeader

```php
mixed PDFGeneratorCore::createHeader(string $header)
```

set the PDF header



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L64)


#### Arguments
* $header **string** - HTML



### <a name="method-getRandomSeed"></a>getRandomSeed

```php
mixed PDFGeneratorCore::getRandomSeed($seed)
```

Override of TCPDF::getRandomSeed() - getmypid() is blocked on several hosting



* Visibility: **protected**
* Source: [classes/pdf/PDFGenerator.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L166)


#### Arguments
* $seed **mixed**



### <a name="method-render"></a>render

```php
mixed PDFGeneratorCore::render(string $filename, $display)
```

Render the pdf file



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L127)


#### Arguments
* $filename **string**
* $display **mixed** - :  true:display to user, false:save, &#039;I&#039;,&#039;D&#039;,&#039;S&#039; as fpdf display



### <a name="method-setEncoding"></a>setEncoding

```php
mixed PDFGeneratorCore::setEncoding(string $encoding)
```

set the PDF encoding



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L54)


#### Arguments
* $encoding **string**



### <a name="method-setFontForLang"></a>setFontForLang

```php
mixed PDFGeneratorCore::setFontForLang(string $iso_lang)
```

Change the font



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L93)


#### Arguments
* $iso_lang **string**



### <a name="method-writePage"></a>writePage

```php
mixed PDFGeneratorCore::writePage()
```

Write a PDF page



* Visibility: **public**
* Source: [classes/pdf/PDFGenerator.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.1/classes/pdf/PDFGenerator.php#L151)



