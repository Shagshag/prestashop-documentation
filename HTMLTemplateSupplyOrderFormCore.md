HTMLTemplateSupplyOrderFormCore
===============






* Class name: HTMLTemplateSupplyOrderFormCore
* Parent class: [HTMLTemplate](HTMLTemplateCore)
* This class is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L30)





Properties
----------

* [$supply_order](#property-$supply_order)
* [$warehouse](#property-$warehouse)
* [$address_warehouse](#property-$address_warehouse)
* [$address_supplier](#property-$address_supplier)
* [$context](#property-$context)

Methods
-------
* [__construct](#method-__construct)
* [getContent](#method-getContent)
* [getLogo](#method-getLogo)
* [getBulkFilename](#method-getBulkFilename)
* [getFilename](#method-getFilename)
* [getTaxOrderSummary](#method-getTaxOrderSummary)
* [getHeader](#method-getHeader)
* [getFooter](#method-getFooter)
* [roundSupplyOrderDetails](#method-roundSupplyOrderDetails)
* [roundSupplyOrder](#method-roundSupplyOrder)




Properties
----------


### <a name="property-$supply_order"></a>$supply_order

    public mixed $supply_order





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L32)


### <a name="property-$warehouse"></a>$warehouse

    public mixed $warehouse





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L33)


### <a name="property-$address_warehouse"></a>$address_warehouse

    public mixed $address_warehouse





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L34)


### <a name="property-$address_supplier"></a>$address_supplier

    public mixed $address_supplier





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L35)


### <a name="property-$context"></a>$context

    public mixed $context





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L36)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed HTMLTemplateSupplyOrderFormCore::__construct(\SupplyOrder $supply_order, $smarty)





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L43)


#### Arguments
* $supply_order **[SupplyOrder](SupplyOrderCore)**
* $smarty **mixed**



### <a name="method-getContent"></a>getContent

    mixed HTMLTemplateSupplyOrderFormCore::getContent()





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L62)




### <a name="method-getLogo"></a>getLogo

    String HTMLTemplateSupplyOrderFormCore::getLogo()

Returns the invoice logo



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L99)




### <a name="method-getBulkFilename"></a>getBulkFilename

    mixed HTMLTemplateSupplyOrderFormCore::getBulkFilename()





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L115)




### <a name="method-getFilename"></a>getFilename

    mixed HTMLTemplateSupplyOrderFormCore::getFilename()





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L123)




### <a name="method-getTaxOrderSummary"></a>getTaxOrderSummary

    array|false|\mysqli_result|null|\PDOStatement|resource HTMLTemplateSupplyOrderFormCore::getTaxOrderSummary()

Get order taxes summary



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L135)




### <a name="method-getHeader"></a>getHeader

    mixed HTMLTemplateSupplyOrderFormCore::getHeader()





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L163)




### <a name="method-getFooter"></a>getFooter

    mixed HTMLTemplateSupplyOrderFormCore::getFooter()





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L191)




### <a name="method-roundSupplyOrderDetails"></a>roundSupplyOrderDetails

    mixed HTMLTemplateSupplyOrderFormCore::roundSupplyOrderDetails(array|\PrestaShopCollection $collection)

Rounds values of a SupplyOrderDetail object



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L213)


#### Arguments
* $collection **array|[array](PrestaShopCollectionCore)**



### <a name="method-roundSupplyOrder"></a>roundSupplyOrder

    mixed HTMLTemplateSupplyOrderFormCore::roundSupplyOrder(\SupplyOrder $supply_order)

Rounds values of a SupplyOrder object



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#L231)


#### Arguments
* $supply_order **[SupplyOrder](SupplyOrderCore)**


