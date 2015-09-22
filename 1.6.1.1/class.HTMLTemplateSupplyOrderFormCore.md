Class HTMLTemplateSupplyOrderFormCore
=====================





* Class name: HTMLTemplateSupplyOrderFormCore
* Parent class: [HTMLTemplate](class.HTMLTemplateCore.md)
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L30)



Properties
----------

* [$address_supplier](#property-$address_supplier)
* [$address_warehouse](#property-$address_warehouse)
* [$context](#property-$context)
* [$supply_order](#property-$supply_order)
* [$warehouse](#property-$warehouse)

Methods
-------
* [__construct](#method-__construct)
* [getBulkFilename](#method-getBulkFilename)
* [getContent](#method-getContent)
* [getFilename](#method-getFilename)
* [getFooter](#method-getFooter)
* [getHeader](#method-getHeader)
* [getLogo](#method-getLogo)
* [getTaxOrderSummary](#method-getTaxOrderSummary)
* [roundSupplyOrder](#method-roundSupplyOrder)
* [roundSupplyOrderDetails](#method-roundSupplyOrderDetails)




Properties
----------


### <a name="property-$address_supplier"></a>$address_supplier

    public mixed $address_supplier





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L35).


### <a name="property-$address_warehouse"></a>$address_warehouse

    public mixed $address_warehouse





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L34).


### <a name="property-$context"></a>$context

    public mixed $context





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L36).


### <a name="property-$supply_order"></a>$supply_order

    public mixed $supply_order





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L32).


### <a name="property-$warehouse"></a>$warehouse

    public mixed $warehouse





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L33).


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HTMLTemplateSupplyOrderFormCore::__construct(\SupplyOrder $supply_order, $smarty)





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L43)


#### Arguments
* $supply_order **[SupplyOrder](class.SupplyOrderCore.md)**
* $smarty **mixed**



### <a name="method-getBulkFilename"></a>getBulkFilename

    mixed HTMLTemplateSupplyOrderFormCore::getBulkFilename()





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L115)




### <a name="method-getContent"></a>getContent

    mixed HTMLTemplateSupplyOrderFormCore::getContent()





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L62)




### <a name="method-getFilename"></a>getFilename

    mixed HTMLTemplateSupplyOrderFormCore::getFilename()





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L123)




### <a name="method-getFooter"></a>getFooter

    mixed HTMLTemplateSupplyOrderFormCore::getFooter()





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L191)




### <a name="method-getHeader"></a>getHeader

    mixed HTMLTemplateSupplyOrderFormCore::getHeader()





* Visibility: **public**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L163)




### <a name="method-getLogo"></a>getLogo

    String HTMLTemplateSupplyOrderFormCore::getLogo()

Returns the invoice logo



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L99)




### <a name="method-getTaxOrderSummary"></a>getTaxOrderSummary

    array|false|\mysqli_result|null|\PDOStatement|resource HTMLTemplateSupplyOrderFormCore::getTaxOrderSummary()

Get order taxes summary



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L135)




### <a name="method-roundSupplyOrder"></a>roundSupplyOrder

    mixed HTMLTemplateSupplyOrderFormCore::roundSupplyOrder(\SupplyOrder $supply_order)

Rounds values of a SupplyOrder object



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L231)


#### Arguments
* $supply_order **[SupplyOrder](class.SupplyOrderCore.md)**



### <a name="method-roundSupplyOrderDetails"></a>roundSupplyOrderDetails

    mixed HTMLTemplateSupplyOrderFormCore::roundSupplyOrderDetails(array|\PrestaShopCollection $collection)

Rounds values of a SupplyOrderDetail object



* Visibility: **protected**
* Source: [classes/pdf/HTMLTemplateSupplyOrderForm.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L213)


#### Arguments
* $collection **array|[array](class.PrestaShopCollectionCore.md)**


