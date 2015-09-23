Class HTMLTemplateOrderReturnCore
=====================





* Class name: HTMLTemplateOrderReturnCore
* Parent class: [HTMLTemplate](class.HTMLTemplateCore.md)
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/pdf/HTMLTemplateOrderReturn.php#L30)


Contents
--------


### Properties

* [$order](#property-$order)
* [$order_return](#property-$order_return)

### Methods

* [__construct](#method-__construct)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)




Properties
----------


### <a name="property-$order"></a>$order

```php
public mixed $order
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/pdf/HTMLTemplateOrderReturn.php#L33).


### <a name="property-$order_return"></a>$order_return

```php
public mixed $order_return
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/pdf/HTMLTemplateOrderReturn.php#L32).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed HTMLTemplateOrderReturnCore::__construct(\OrderReturn $order_return, $smarty)
```





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/pdf/HTMLTemplateOrderReturn.php#L35)


#### Arguments
* $order_return **[OrderReturn](class.OrderReturnCore.md)**
* $smarty **mixed**



### <a name="method-getBulkFilename"></a>getBulkFilename

```php
string HTMLTemplateOrderReturnCore::getBulkFilename()
```

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 89](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/pdf/HTMLTemplateOrderReturn.php#L89)




### <a name="method-getContent"></a>getContent

```php
string HTMLTemplateOrderReturnCore::getContent()
```

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/pdf/HTMLTemplateOrderReturn.php#L53)




### <a name="method-getFilename"></a>getFilename

```php
string HTMLTemplateOrderReturnCore::getFilename()
```

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.10/classes/pdf/HTMLTemplateOrderReturn.php#L80)



