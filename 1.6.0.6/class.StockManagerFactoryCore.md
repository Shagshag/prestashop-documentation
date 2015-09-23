Class StockManagerFactoryCore
=====================





* Class name: StockManagerFactoryCore
* Source: [classes/stock/StockManagerFactory.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/stock/StockManagerFactory.php#L31)


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
* Source: [classes/stock/StockManagerFactory.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/stock/StockManagerFactory.php#L36).


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
* Source: [classes/stock/StockManagerFactory.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/stock/StockManagerFactory.php#L60)




### <a name="method-getManager"></a>getManager

```php
\StockManagerInterface StockManagerFactoryCore::getManager()
```

Returns a StockManager



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockManagerFactory.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.6/classes/stock/StockManagerFactory.php#L43)



