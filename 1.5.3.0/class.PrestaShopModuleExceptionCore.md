Class PrestaShopModuleExceptionCore
=====================





* Class name: PrestaShopModuleExceptionCore
* Parent class: [PrestaShopException](class.PrestaShopExceptionCore.md)
* Source: [classes/exception/PrestaShopModuleException.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/exception/PrestaShopModuleException.php#L30)


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
* This method is defined by [PrestaShopExceptionCore](class.PrestaShopExceptionCore.md).
* Source: [classes/exception/PrestaShopException.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/exception/PrestaShopException.php#L132)


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
* Source: [classes/exception/PrestaShopException.php line 103](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/exception/PrestaShopException.php#L103)


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
* Source: [classes/exception/PrestaShopException.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.3.0/classes/exception/PrestaShopException.php#L35)



