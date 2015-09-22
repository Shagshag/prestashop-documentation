HTMLTemplateOrderReturnCore
===============






* Class name: HTMLTemplateOrderReturnCore
* Parent class: [HTMLTemplate](HTMLTemplateCore)
* This class is defined in [classes/pdf/HTMLTemplateOrderReturn.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L30)





Properties
----------

* [$order_return](#property-$order_return)
* [$order](#property-$order)

Methods
-------
* [__construct](#method-__construct)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getBulkFilename](#method-getBulkFilename)
* [getHeader](#method-getHeader)




Properties
----------


### <a name="property-$order_return"></a>$order_return

    public mixed $order_return





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateOrderReturn.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L32)


### <a name="property-$order"></a>$order

    public mixed $order





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateOrderReturn.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L33)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HTMLTemplateOrderReturnCore::__construct(\OrderReturn $order_return, $smarty)





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateOrderReturn.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L40)


#### Arguments
* $order_return **[OrderReturn](OrderReturnCore)**
* $smarty **mixed**



### <a name="method-getContent"></a>getContent

    string HTMLTemplateOrderReturnCore::getContent()

Returns the template's HTML content



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateOrderReturn.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L59)




### <a name="method-getFilename"></a>getFilename

    string HTMLTemplateOrderReturnCore::getFilename()

Returns the template filename



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateOrderReturn.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L96)




### <a name="method-getBulkFilename"></a>getBulkFilename

    string HTMLTemplateOrderReturnCore::getBulkFilename()

Returns the template filename when using bulk rendering



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateOrderReturn.php line 106](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L106)




### <a name="method-getHeader"></a>getHeader

    string HTMLTemplateOrderReturnCore::getHeader()

Returns the template's HTML header



* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateOrderReturn.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateOrderReturn.php#L116)



