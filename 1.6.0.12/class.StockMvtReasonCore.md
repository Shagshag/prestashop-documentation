Class StockMvtReasonCore
=====================





* Class name: StockMvtReasonCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/stock/StockMvtReason.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/StockMvtReason.php#L27)


Contents
--------


### Properties

* [$date_add](#property-$date_add)
* [$date_upd](#property-$date_upd)
* [$definition](#property-$definition)
* [$deleted](#property-$deleted)
* [$id](#property-$id)
* [$name](#property-$name)
* [$sign](#property-$sign)
* [$webserviceParameters](#property-$webserviceParameters)

### Methods

* [exists](#method-exists)
* [getStockMvtReasons](#method-getStockMvtReasons)
* [getStockMvtReasonsWithFilter](#method-getStockMvtReasonsWithFilter)




Properties
----------


### <a name="property-$date_add"></a>$date_add

```php
public string $date_add
```





* Visibility: **public**
* Source: [classes/stock/StockMvtReason.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/StockMvtReason.php#L39).


### <a name="property-$date_upd"></a>$date_upd

```php
public string $date_upd
```





* Visibility: **public**
* Source: [classes/stock/StockMvtReason.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/StockMvtReason.php#L42).


### <a name="property-$definition"></a>$definition

```php
public mixed $definition = array('table' => 'stock_mvt_reason', 'primary' => 'id_stock_mvt_reason', 'multilang' => true, 'fields' => array('sign' => array('type' => self::TYPE_INT), 'deleted' => array('type' => self::TYPE_BOOL), 'date_add' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'date_upd' => array('type' => self::TYPE_DATE, 'validate' => 'isDate'), 'name' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 255)))
```





* Visibility: **public**
* This property is **static**.
* Source: [classes/stock/StockMvtReason.php line 51](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/StockMvtReason.php#L51).


### <a name="property-$deleted"></a>$deleted

```php
public boolean $deleted
```





* Visibility: **public**
* Source: [classes/stock/StockMvtReason.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/StockMvtReason.php#L45).


### <a name="property-$id"></a>$id

```php
public integer $id
```





* Visibility: **public**
* Source: [classes/stock/StockMvtReason.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/StockMvtReason.php#L30).


### <a name="property-$name"></a>$name

```php
public string $name
```





* Visibility: **public**
* Source: [classes/stock/StockMvtReason.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/StockMvtReason.php#L33).


### <a name="property-$sign"></a>$sign

```php
public integer $sign
```





* Visibility: **public**
* Source: [classes/stock/StockMvtReason.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/StockMvtReason.php#L36).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

```php
protected mixed $webserviceParameters = array('objectsNodeName' => 'stock_movement_reasons', 'objectNodeName' => 'stock_movement_reason', 'fields' => array('sign' => array()))
```





* Visibility: **protected**
* Source: [classes/stock/StockMvtReason.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/StockMvtReason.php#L67).


Methods
-------


### <a name="method-exists"></a>exists

```php
boolean StockMvtReasonCore::exists(integer $id_stock_mvt_reason)
```

For a given id_stock_mvt_reason, tells if it exists



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtReason.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/StockMvtReason.php#L131)


#### Arguments
* $id_stock_mvt_reason **integer**



### <a name="method-getStockMvtReasons"></a>getStockMvtReasons

```php
array StockMvtReasonCore::getStockMvtReasons(integer $id_lang, integer $sign)
```

Gets Stock Mvt Reasons



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtReason.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/StockMvtReason.php#L82)


#### Arguments
* $id_lang **integer**
* $sign **integer** - Optionnal



### <a name="method-getStockMvtReasonsWithFilter"></a>getStockMvtReasonsWithFilter

```php
mixed StockMvtReasonCore::getStockMvtReasonsWithFilter(integer $id_lang, array $ids_ignore, integer $sign)
```

Same as StockMvtReason::getStockMvtReasons(), ignoring a specific lists of ids



* Visibility: **public**
* This method is **static**.
* Source: [classes/stock/StockMvtReason.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/stock/StockMvtReason.php#L104)


#### Arguments
* $id_lang **integer**
* $ids_ignore **array**
* $sign **integer** - optional


