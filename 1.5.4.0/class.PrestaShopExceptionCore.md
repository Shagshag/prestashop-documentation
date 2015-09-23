Class PrestaShopExceptionCore
=====================





* Class name: PrestaShopExceptionCore
* Parent class: Exception
* Source: [classes/exception/PrestaShopException.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/exception/PrestaShopException.php#L30)


Contents
--------



### Methods

* [displayArgsDebug](#method-displayArgsDebug)
* [displayFileDebug](#method-displayFileDebug)
* [displayMessage](#method-displayMessage)
* [getExentedMessage](#method-getExentedMessage)
* [logError](#method-logError)






Methods
-------


### <a name="method-displayArgsDebug"></a>displayArgsDebug

```php
mixed PrestaShopExceptionCore::displayArgsDebug(array $args, string $id)
```

Display arguments list of traced function



* Visibility: **protected**
* Source: [classes/exception/PrestaShopException.php line 129](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/exception/PrestaShopException.php#L129)


#### Arguments
* $args **array** - List of arguments
* $id **string** - ID of argument



### <a name="method-displayFileDebug"></a>displayFileDebug

```php
mixed PrestaShopExceptionCore::displayFileDebug(string $file, integer $line, string $id)
```

Display lines around current line



* Visibility: **protected**
* Source: [classes/exception/PrestaShopException.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/exception/PrestaShopException.php#L100)


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
* Source: [classes/exception/PrestaShopException.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/exception/PrestaShopException.php#L35)




### <a name="method-getExentedMessage"></a>getExentedMessage

```php
string PrestaShopExceptionCore::getExentedMessage($html)
```

Return the content of the Exception



* Visibility: **protected**
* Source: [classes/exception/PrestaShopException.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/exception/PrestaShopException.php#L155)


#### Arguments
* $html **mixed**



### <a name="method-logError"></a>logError

```php
mixed PrestaShopExceptionCore::logError()
```

Log the error on the disk



* Visibility: **protected**
* Source: [classes/exception/PrestaShopException.php line 144](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/classes/exception/PrestaShopException.php#L144)



