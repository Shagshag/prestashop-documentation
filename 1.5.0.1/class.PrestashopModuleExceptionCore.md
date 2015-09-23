Class PrestashopModuleExceptionCore
=====================





* Class name: PrestashopModuleExceptionCore
* Parent class: [PrestashopException](class.PrestashopExceptionCore.md)
* Source: [classes/exception/PrestashopModuleException.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/exception/PrestashopModuleException.php#L31)


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
mixed PrestashopExceptionCore::displayArgsDebug(array $args, string $id)
```

Display arguments list of traced function



* Visibility: **protected**
* This method is defined by [PrestashopExceptionCore](class.PrestashopExceptionCore.md).
* Source: [classes/exception/PrestashopException.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/exception/PrestashopException.php#L133)


#### Arguments
* $args **array** - List of arguments
* $id **string** - ID of argument



### <a name="method-displayFileDebug"></a>displayFileDebug

```php
mixed PrestashopExceptionCore::displayFileDebug(string $file, integer $line, string $id)
```

Display lines around current line



* Visibility: **protected**
* This method is defined by [PrestashopExceptionCore](class.PrestashopExceptionCore.md).
* Source: [classes/exception/PrestashopException.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/exception/PrestashopException.php#L104)


#### Arguments
* $file **string**
* $line **integer**
* $id **string**



### <a name="method-displayMessage"></a>displayMessage

```php
mixed PrestashopExceptionCore::displayMessage()
```

This method acts like an error handler, if dev mode is on, display the error else use a better silent way



* Visibility: **public**
* This method is defined by [PrestashopExceptionCore](class.PrestashopExceptionCore.md).
* Source: [classes/exception/PrestashopException.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/classes/exception/PrestashopException.php#L36)



