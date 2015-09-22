PrestaShopExceptionCore
===============






* Class name: PrestaShopExceptionCore
* Parent class: Exception
* This class is defined in [classes/exception/PrestaShopException.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#L30)







Methods
-------
* [displayMessage](#method-displayMessage)
* [displayFileDebug](#method-displayFileDebug)
* [displayArgsDebug](#method-displayArgsDebug)
* [logError](#method-logError)
* [getExentedMessage](#method-getExentedMessage)
* [getExtendedMessage](#method-getExtendedMessage)






Methods
-------


### <a name="method-displayMessage"></a>displayMessage

    mixed PrestaShopExceptionCore::displayMessage()

This method acts like an error handler, if dev mode is on, display the error else use a better silent way



* Visibility: **public**
* This method is defined in [classes/exception/PrestaShopException.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#L35)




### <a name="method-displayFileDebug"></a>displayFileDebug

    mixed PrestaShopExceptionCore::displayFileDebug(string $file, integer $line, string $id)

Display lines around current line



* Visibility: **protected**
* This method is defined in [classes/exception/PrestaShopException.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#L101)


#### Arguments
* $file **string**
* $line **integer**
* $id **string**



### <a name="method-displayArgsDebug"></a>displayArgsDebug

    mixed PrestaShopExceptionCore::displayArgsDebug(array $args, string $id)

Display arguments list of traced function



* Visibility: **protected**
* This method is defined in [classes/exception/PrestaShopException.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#L131)


#### Arguments
* $args **array** - &lt;p&gt;List of arguments&lt;/p&gt;
* $id **string** - &lt;p&gt;ID of argument&lt;/p&gt;



### <a name="method-logError"></a>logError

    mixed PrestaShopExceptionCore::logError()

Log the error on the disk



* Visibility: **protected**
* This method is defined in [classes/exception/PrestaShopException.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#L145)




### <a name="method-getExentedMessage"></a>getExentedMessage

    mixed PrestaShopExceptionCore::getExentedMessage($html)





* Visibility: **protected**
* This method is defined in [classes/exception/PrestaShopException.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#L155)


#### Arguments
* $html **mixed**



### <a name="method-getExtendedMessage"></a>getExtendedMessage

    string PrestaShopExceptionCore::getExtendedMessage($html)

Return the content of the Exception



* Visibility: **protected**
* This method is defined in [classes/exception/PrestaShopException.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#L165)


#### Arguments
* $html **mixed**


