Class HTMLTemplateCore
=====================





* Class name: HTMLTemplateCore
* This is an **abstract** class
* Source: [classes/pdf/HTMLTemplate.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L30)


Contents
--------


### Properties

* [$available_in_your_account](#property-$available_in_your_account)
* [$date](#property-$date)
* [$shop](#property-$shop)
* [$smarty](#property-$smarty)
* [$title](#property-$title)

### Methods

* [assignHookData](#method-assignHookData)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getFooter](#method-getFooter)
* [getHeader](#method-getHeader)
* [getLogo](#method-getLogo)
* [getShopAddress](#method-getShopAddress)
* [getTemplate](#method-getTemplate)
* [l](#method-l)




Properties
----------


### <a name="property-$available_in_your_account"></a>$available_in_your_account

```php
public mixed $available_in_your_account = true
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L34).


### <a name="property-$date"></a>$date

```php
public mixed $date
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L33).


### <a name="property-$shop"></a>$shop

```php
public mixed $shop
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L36).


### <a name="property-$smarty"></a>$smarty

```php
public mixed $smarty
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L35).


### <a name="property-$title"></a>$title

```php
public mixed $title
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L32).


Methods
-------


### <a name="method-assignHookData"></a>assignHookData

```php
mixed HTMLTemplateCore::assignHookData($object)
```

Assign hook data



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L124)


#### Arguments
* $object **mixed** - generally the object used in the constructor



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/pdf/HTMLTemplate.php line 151](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L151)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/pdf/HTMLTemplate.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L138)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/pdf/HTMLTemplate.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L145)




### <a name="method-getFooter"></a>getFooter

```php
string HTMLTemplateCore::getFooter()
```

Returns the template's HTML footer



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 70](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L70)




### <a name="method-getHeader"></a>getHeader

```php
string HTMLTemplateCore::getHeader()
```

Returns the template's HTML header



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L42)




### <a name="method-getLogo"></a>getLogo

```php
mixed HTMLTemplateCore::getLogo()
```

Returns the invoice logo



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplate.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L106)




### <a name="method-getShopAddress"></a>getShopAddress

```php
string HTMLTemplateCore::getShopAddress()
```

Returns the shop address



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplate.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L89)




### <a name="method-getTemplate"></a>getTemplate

```php
string HTMLTemplateCore::getTemplate($template_name)
```

If the template is not present in the theme directory, it will return the default template
in _PS_PDF_DIR_ directory



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplate.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L160)


#### Arguments
* $template_name **mixed**



### <a name="method-l"></a>l

```php
string HTMLTemplateCore::l(string $string)
```

Translatation method



* Visibility: **protected**
* This method is **static**.
* Source: [classes/pdf/HTMLTemplate.php line 180](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.8/classes/pdf/HTMLTemplate.php#L180)


#### Arguments
* $string **string**


