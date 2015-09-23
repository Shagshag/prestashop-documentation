Class PrestaShopDatabaseExceptionCore
=====================





* Class name: PrestaShopDatabaseExceptionCore
* Parent class: [PrestaShopException](class.PrestaShopExceptionCore.md)
* Source: [classes/exception/PrestaShopDatabaseException.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/exception/PrestaShopDatabaseException.php#L30)


Contents
--------



### Methods

* [__toString](#method-__toString)
* [displayArgsDebug](#method-displayArgsDebug)
* [displayFileDebug](#method-displayFileDebug)
* [displayMessage](#method-displayMessage)
* [getExentedMessage](#method-getExentedMessage)
* [getExtendedMessage](#method-getExtendedMessage)
* [logError](#method-logError)






Methods
-------


### <a name="method-__toString"></a>__toString

```php
mixed PrestaShopDatabaseExceptionCore::__toString()
```





* Visibility: **public**
* Source: [classes/exception/PrestaShopDatabaseException.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/exception/PrestaShopDatabaseException.php#L32)




### <a name="method-displayArgsDebug"></a>displayArgsDebug

```php
mixed PrestaShopExceptionCore::displayArgsDebug(array $args, string $id)
```

Display arguments list of traced function



* Visibility: **protected**
* This method is defined by [PrestaShopExceptionCore](class.PrestaShopExceptionCore.md).
* Source: [classes/exception/PrestaShopException.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/exception/PrestaShopException.php#L131)


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
* Source: [classes/exception/PrestaShopException.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/exception/PrestaShopException.php#L100)


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
* Source: [classes/exception/PrestaShopException.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/exception/PrestaShopException.php#L35)




### <a name="method-getExentedMessage"></a>getExentedMessage

```php
mixed PrestaShopExceptionCore::getExentedMessage($html)
```





* Visibility: **protected**
* This method is defined by [PrestaShopExceptionCore](class.PrestaShopExceptionCore.md).
* Source: [classes/exception/PrestaShopException.php line 156](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/exception/PrestaShopException.php#L156)


#### Arguments
* $html **mixed**



### <a name="method-getExtendedMessage"></a>getExtendedMessage

```php
string PrestaShopExceptionCore::getExtendedMessage($html)
```

Return the content of the Exception



* Visibility: **protected**
* This method is defined by [PrestaShopExceptionCore](class.PrestaShopExceptionCore.md).
* Source: [classes/exception/PrestaShopException.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/exception/PrestaShopException.php#L166)


#### Arguments
* $html **mixed**



### <a name="method-logError"></a>logError

```php
mixed PrestaShopExceptionCore::logError()
```

Log the error on the disk



* Visibility: **protected**
* This method is defined by [PrestaShopExceptionCore](class.PrestaShopExceptionCore.md).
* Source: [classes/exception/PrestaShopException.php line 146](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.12/classes/exception/PrestaShopException.php#L146)



