Class HTMLTemplateOrderReturnCore
=====================





* Class name: HTMLTemplateOrderReturnCore
* Parent class: [HTMLTemplate](class.HTMLTemplateCore)
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L30)



Properties
----------

* [$order](#property-$order)
* [$order_return](#property-$order_return)

Methods
-------
* [__construct](#method-__construct)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getHeader](#method-getHeader)




Properties
----------


### <a name="property-$order"></a>$order

    public mixed $order





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L33)


### <a name="property-$order_return"></a>$order_return

    public mixed $order_return





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L32)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HTMLTemplateOrderReturnCore::__construct(\OrderReturn $order_return, $smarty)





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L40)


#### Arguments
* $order_return **[OrderReturn](class.OrderReturnCore)**
* $smarty **mixed**



### <a name="method-getBulkFilename"></a>getBulkFilename

    string HTMLTemplateOrderReturnCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L106)




### <a name="method-getContent"></a>getContent

    string HTMLTemplateOrderReturnCore::getContent()

Returns the template's HTML content



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L59)




### <a name="method-getFilename"></a>getFilename

    string HTMLTemplateOrderReturnCore::getFilename()

Returns the template filename



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L96)




### <a name="method-getHeader"></a>getHeader

    string HTMLTemplateOrderReturnCore::getHeader()

Returns the template's HTML header



* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateOrderReturn.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L116)



