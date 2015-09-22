HTMLTemplateSupplyOrderFormCore
===============






* Class name: HTMLTemplateSupplyOrderFormCore
* Namespace: 
* Parent class: [HTMLTemplate](HTMLTemplateCore)

* This class is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#30)





Properties
----------


### $supply_order

    public mixed $supply_order





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#32)


### $warehouse

    public mixed $warehouse





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#33)


### $address_warehouse

    public mixed $address_warehouse





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#34)


### $address_supplier

    public mixed $address_supplier





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#35)


### $context

    public mixed $context





* Visibility: **public**
* This property is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#36)


Methods
-------


### __construct

    mixed HTMLTemplateSupplyOrderFormCore::__construct(\SupplyOrder $supply_order, $smarty)





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#43)


#### Arguments
* $supply_order **[SupplyOrder](SupplyOrderCore)**
* $smarty **mixed**



### getContent

    mixed HTMLTemplateSupplyOrderFormCore::getContent()





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#62)




### getLogo

    String HTMLTemplateSupplyOrderFormCore::getLogo()

Returns the invoice logo



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#99)




### getBulkFilename

    mixed HTMLTemplateSupplyOrderFormCore::getBulkFilename()





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#115)




### getFilename

    mixed HTMLTemplateSupplyOrderFormCore::getFilename()





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#123)




### getTaxOrderSummary

    array|false|\mysqli_result|null|\PDOStatement|resource HTMLTemplateSupplyOrderFormCore::getTaxOrderSummary()

Get order taxes summary



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 135](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#135)




### getHeader

    mixed HTMLTemplateSupplyOrderFormCore::getHeader()





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 163](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#163)




### getFooter

    mixed HTMLTemplateSupplyOrderFormCore::getFooter()





* Visibility: **public**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#191)




### roundSupplyOrderDetails

    mixed HTMLTemplateSupplyOrderFormCore::roundSupplyOrderDetails(array|\PrestaShopCollection $collection)

Rounds values of a SupplyOrderDetail object



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 213](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#213)


#### Arguments
* $collection **array|[array](PrestaShopCollectionCore)**



### roundSupplyOrder

    mixed HTMLTemplateSupplyOrderFormCore::roundSupplyOrder(\SupplyOrder $supply_order)

Rounds values of a SupplyOrder object



* Visibility: **protected**
* This method is defined in [classes/pdf/HTMLTemplateSupplyOrderForm.php line 231](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/pdf/HTMLTemplateSupplyOrderForm.php#231)


#### Arguments
* $supply_order **[SupplyOrder](SupplyOrderCore)**


