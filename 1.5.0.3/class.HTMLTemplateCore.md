Class HTMLTemplateCore
=====================





* Class name: HTMLTemplateCore
* This is an **abstract** class
* Source: [classes/pdf/HTMLTemplate.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L32)


Contents
--------


### Properties

* [$address](#property-$address)
* [$available_in_your_account](#property-$available_in_your_account)
* [$date](#property-$date)
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
* [l](#method-l)




Properties
----------


### <a name="property-$address"></a>$address

```php
public mixed $address
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L36).


### <a name="property-$available_in_your_account"></a>$available_in_your_account

```php
public mixed $available_in_your_account = true
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L37).


### <a name="property-$date"></a>$date

```php
public mixed $date
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L35).


### <a name="property-$smarty"></a>$smarty

```php
public mixed $smarty
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L38).


### <a name="property-$title"></a>$title

```php
public mixed $title
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L34).


Methods
-------


### <a name="method-assignHookData"></a>assignHookData

```php
mixed HTMLTemplateCore::assignHookData($object)
```

Assign hook data



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L99)


#### Arguments
* $object **mixed** - generally the object used in the constructor



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/pdf/HTMLTemplate.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L126)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/pdf/HTMLTemplate.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L113)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* This method is **abstract**.
* Source: [classes/pdf/HTMLTemplate.php line 120](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L120)




### <a name="method-getFooter"></a>getFooter

```php
string HTMLTemplateCore::getFooter()
```

Returns the template's HTML footer



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L62)




### <a name="method-getHeader"></a>getHeader

```php
string HTMLTemplateCore::getHeader()
```

Returns the template's HTML header



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplate.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L44)




### <a name="method-getLogo"></a>getLogo

```php
mixed HTMLTemplateCore::getLogo()
```

Returns the invoice logo



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplate.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L82)




### <a name="method-l"></a>l

```php
string HTMLTemplateCore::l(string $string)
```

Translatation method



* Visibility: **protected**
* This method is **static**.
* Source: [classes/pdf/HTMLTemplate.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/classes/pdf/HTMLTemplate.php#L134)


#### Arguments
* $string **string**


