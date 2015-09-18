HTMLTemplateSupplyOrderFormCore
===============






* Class name: HTMLTemplateSupplyOrderFormCore
* Namespace: 
* Parent class: HTMLTemplate





Properties
----------


### $supply_order

    public mixed $supply_order





* Visibility: **public**


### $warehouse

    public mixed $warehouse





* Visibility: **public**


### $address_warehouse

    public mixed $address_warehouse





* Visibility: **public**


### $address_supplier

    public mixed $address_supplier





* Visibility: **public**


### $context

    public mixed $context





* Visibility: **public**


Methods
-------


### __construct

    mixed HTMLTemplateSupplyOrderFormCore::__construct(\SupplyOrder $supply_order, $smarty)





* Visibility: **public**


#### Arguments
* $supply_order **SupplyOrder**
* $smarty **mixed**



### getContent

    mixed HTMLTemplateSupplyOrderFormCore::getContent()





* Visibility: **public**




### getLogo

    String HTMLTemplateSupplyOrderFormCore::getLogo()

Returns the invoice logo



* Visibility: **protected**




### getBulkFilename

    mixed HTMLTemplateSupplyOrderFormCore::getBulkFilename()





* Visibility: **public**




### getFilename

    mixed HTMLTemplateSupplyOrderFormCore::getFilename()





* Visibility: **public**




### getTaxOrderSummary

    array|false|\mysqli_result|null|\PDOStatement|resource HTMLTemplateSupplyOrderFormCore::getTaxOrderSummary()

Get order taxes summary



* Visibility: **protected**




### getHeader

    mixed HTMLTemplateSupplyOrderFormCore::getHeader()





* Visibility: **public**




### getFooter

    mixed HTMLTemplateSupplyOrderFormCore::getFooter()





* Visibility: **public**




### roundSupplyOrderDetails

    mixed HTMLTemplateSupplyOrderFormCore::roundSupplyOrderDetails(array|\PrestaShopCollection $collection)

Rounds values of a SupplyOrderDetail object



* Visibility: **protected**


#### Arguments
* $collection **array|PrestaShopCollection**



### roundSupplyOrder

    mixed HTMLTemplateSupplyOrderFormCore::roundSupplyOrder(\SupplyOrder $supply_order)

Rounds values of a SupplyOrder object



* Visibility: **protected**


#### Arguments
* $supply_order **SupplyOrder**


