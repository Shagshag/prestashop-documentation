Class PrestaShopDatabaseExceptionCore
=====================





* Class name: PrestaShopDatabaseExceptionCore
* Parent class: [PrestaShopException](class.PrestaShopExceptionCore.md)
* Source: [classes/exception/PrestaShopDatabaseException.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/exception/PrestaShopDatabaseException.php#L31)


Contents
--------



### Methods

* [__toString](#method-__toString)
* [displayArgsDebug](#method-displayArgsDebug)
* [displayFileDebug](#method-displayFileDebug)
* [displayMessage](#method-displayMessage)






Methods
-------


### <a name="method-__toString"></a>__toString

```php
mixed PrestaShopDatabaseExceptionCore::__toString()
```





* Visibility: **public**
* Source: [classes/exception/PrestaShopDatabaseException.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/exception/PrestaShopDatabaseException.php#L33)




### <a name="method-displayArgsDebug"></a>displayArgsDebug

```php
mixed PrestaShopExceptionCore::displayArgsDebug(array $args, string $id)
```

Display arguments list of traced function



* Visibility: **protected**
* This method is defined by [PrestaShopExceptionCore](class.PrestaShopExceptionCore.md).
* Source: [classes/exception/PrestaShopException.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/exception/PrestaShopException.php#L133)


#### Arguments
* $args **array** - List of arguments
* $id **string** - ID of argument



### <a name="method-displayFileDebug"></a>displayFileDebug

```php
mixed PrestaShopExceptionCore::displayFileDebug(string $file, integer $line, string $id)
```

Display lines around current line



* Visibility: **protected**
* This method is defined by [PrestaShopExceptionCore](class.PrestaShopExceptionCore.md).
* Source: [classes/exception/PrestaShopException.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/exception/PrestaShopException.php#L104)


#### Arguments
* $file **string**
* $line **integer**
* $id **string**



### <a name="method-displayMessage"></a>displayMessage

```php
mixed PrestaShopExceptionCore::displayMessage()
```

This method acts like an error handler, if dev mode is on, display the error else use a better silent way



* Visibility: **public**
* This method is defined by [PrestaShopExceptionCore](class.PrestaShopExceptionCore.md).
* Source: [classes/exception/PrestaShopException.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/exception/PrestaShopException.php#L36)



