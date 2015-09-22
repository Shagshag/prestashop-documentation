StockManagerFactoryCore
===============






* Class name: StockManagerFactoryCore
* Namespace: 

* This class is defined in [classes/stock/StockManagerFactory.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManagerFactory.php#31)





Properties
----------


### $stock_manager

    protected  $stock_manager





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/stock/StockManagerFactory.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManagerFactory.php#36)


Methods
-------


### getManager

    \StockManagerInterface StockManagerFactoryCore::getManager()

Returns a StockManager



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockManagerFactory.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManagerFactory.php#43)




### execHookStockManagerFactory

    mixed StockManagerFactoryCore::execHookStockManagerFactory()

Looks for a StockManager in the modules list.

@return StockManagerInterface

* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/stock/StockManagerFactory.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/stock/StockManagerFactory.php#60)



