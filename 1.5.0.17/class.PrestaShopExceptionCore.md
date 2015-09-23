Class PrestaShopExceptionCore
=====================





* Class name: PrestaShopExceptionCore
* Parent class: Exception
* Source: [classes/exception/PrestaShopException.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/exception/PrestaShopException.php#L31)


Contents
--------



### Methods

* [displayArgsDebug](#method-displayArgsDebug)
* [displayFileDebug](#method-displayFileDebug)
* [displayMessage](#method-displayMessage)






Methods
-------


### <a name="method-displayArgsDebug"></a>displayArgsDebug

```php
mixed PrestaShopExceptionCore::displayArgsDebug(array $args, string $id)
```

Display arguments list of traced function



* Visibility: **protected**
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
* Source: [classes/exception/PrestaShopException.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/exception/PrestaShopException.php#L36)



