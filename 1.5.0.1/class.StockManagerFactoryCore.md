Class StockManagerFactoryCore
=====================





* Class name: StockManagerFactoryCore
* Source: [classes/stock/StockManagerFactory.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/StockManagerFactory.php#L32)


Contents
--------


### Properties

* [$stock_manager](#property-$stock_manager)

### Methods

* [execHookStockManagerFactory](#method-execHookStockManagerFactory)
* [getManager](#method-getManager)




Properties
----------


### <a name="property-$stock_manager"></a>$stock_manager

```php
protected  $stock_manager
```





* Visibility: **protected**
* This property is **static**.
* Source: [classes/stock/StockManagerFactory.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/StockManagerFactory.php#L37).


Methods
-------


### <a name="method-execHookStockManagerFactory"></a>execHookStockManagerFactory

```php
mixed StockManagerFactoryCore::execHookStockManagerFactory()
```

Looks for a StockManager in the modules list.

@return StockManagerInterface

* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockManagerFactory.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/StockManagerFactory.php#L61)




### <a name="method-getManager"></a>getManager

```php
\StockManagerInterface StockManagerFactoryCore::getManager()
```

Returns a StockManager that corresponds to the Product/Warehouse



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockManagerFactory.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/stock/StockManagerFactory.php#L44)



