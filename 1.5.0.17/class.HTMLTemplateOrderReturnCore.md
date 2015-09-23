Class HTMLTemplateOrderReturnCore
=====================





* Class name: HTMLTemplateOrderReturnCore
* Parent class: [HTMLTemplate](class.HTMLTemplateCore.md)
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplateOrderReturn.php#L31)


Contents
--------


### Properties

* [$order](#property-$order)
* [$order_return](#property-$order_return)
* [$available_in_your_account](#property-$available_in_your_account)
* [$date](#property-$date)
* [$shop](#property-$shop)
* [$smarty](#property-$smarty)
* [$title](#property-$title)

### Methods

* [__construct](#method-__construct)
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


### <a name="property-$order"></a>$order

```php
public mixed $order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplateOrderReturn.php#L34).


### <a name="property-$order_return"></a>$order_return

```php
public mixed $order_return
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplateOrderReturn.php#L33).


### <a name="property-$available_in_your_account"></a>$available_in_your_account

```php
public mixed $available_in_your_account = true
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplate.php#L36).


### <a name="property-$date"></a>$date

```php
public mixed $date
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplate.php#L35).


### <a name="property-$shop"></a>$shop

```php
public mixed $shop
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplate.php#L38).


### <a name="property-$smarty"></a>$smarty

```php
public mixed $smarty
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplate.php#L37).


### <a name="property-$title"></a>$title

```php
public mixed $title
```





* Visibility: **public**
* This property is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplate.php#L34).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateOrderReturnCore::__construct(\OrderReturn $order_return, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplateOrderReturn.php#L36)


#### Arguments
* $order_return **[OrderReturn](class.OrderReturnCore.md)**
* $smarty **mixed**



### <a name="method-assignHookData"></a>assignHookData

```php
mixed HTMLTemplateCore::assignHookData($object)
```

Assign hook data



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplate.php#L126)


#### Arguments
* $object **mixed** - generally the object used in the constructor



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateOrderReturnCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplateOrderReturn.php#L90)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateOrderReturnCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplateOrderReturn.php#L54)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateOrderReturnCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplateOrderReturn.php#L81)




### <a name="method-getFooter"></a>getFooter

```php
string HTMLTemplateCore::getFooter()
```

Returns the template's HTML footer



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplate.php#L72)




### <a name="method-getHeader"></a>getHeader

```php
string HTMLTemplateCore::getHeader()
```

Returns the template's HTML header



* Visibility: **public**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplate.php#L44)




### <a name="method-getLogo"></a>getLogo

```php
mixed HTMLTemplateCore::getLogo()
```

Returns the invoice logo



* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplate.php#L108)




### <a name="method-getShopAddress"></a>getShopAddress

```php
string HTMLTemplateCore::getShopAddress()
```

Returns the shop address



* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplate.php#L91)




### <a name="method-getTemplate"></a>getTemplate

```php
string HTMLTemplateCore::getTemplate($template_name)
```

If the template is not present in the theme directory, it will return the default template
in _PS_PDF_DIR_ directory



* Visibility: **protected**
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplate.php#L162)


#### Arguments
* $template_name **mixed**



### <a name="method-l"></a>l

```php
string HTMLTemplateCore::l(string $string)
```

Translatation method



* Visibility: **protected**
* This method is **static**.
* This method is defined by [HTMLTemplateCore](class.HTMLTemplateCore.md).
* Source: [classes/pdf/HTMLTemplate.php line 182](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/pdf/HTMLTemplate.php#L182)


#### Arguments
* $string **string**


