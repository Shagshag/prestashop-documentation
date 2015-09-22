PrestaShopExceptionCore
===============






* Class name: PrestaShopExceptionCore
* Namespace: 
* Parent class: Exception

* This class is defined in [classes/exception/PrestaShopException.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#30)







Methods
-------


### displayMessage

    mixed PrestaShopExceptionCore::displayMessage()

This method acts like an error handler, if dev mode is on, display the error else use a better silent way



* Visibility: **public**
* This method is defined in [classes/exception/PrestaShopException.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#35)




### displayFileDebug

    mixed PrestaShopExceptionCore::displayFileDebug(string $file, integer $line, string $id)

Display lines around current line



* Visibility: **protected**
* This method is defined in [classes/exception/PrestaShopException.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#101)


#### Arguments
* $file **string**
* $line **integer**
* $id **string**



### displayArgsDebug

    mixed PrestaShopExceptionCore::displayArgsDebug(array $args, string $id)

Display arguments list of traced function



* Visibility: **protected**
* This method is defined in [classes/exception/PrestaShopException.php line 131](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#131)


#### Arguments
* $args **array** - &lt;p&gt;List of arguments&lt;/p&gt;
* $id **string** - &lt;p&gt;ID of argument&lt;/p&gt;



### logError

    mixed PrestaShopExceptionCore::logError()

Log the error on the disk



* Visibility: **protected**
* This method is defined in [classes/exception/PrestaShopException.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#145)




### getExentedMessage

    mixed PrestaShopExceptionCore::getExentedMessage($html)





* Visibility: **protected**
* This method is defined in [classes/exception/PrestaShopException.php line 155](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#155)


#### Arguments
* $html **mixed**



### getExtendedMessage

    string PrestaShopExceptionCore::getExtendedMessage($html)

Return the content of the Exception



* Visibility: **protected**
* This method is defined in [classes/exception/PrestaShopException.php line 165](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/exception/PrestaShopException.php#165)


#### Arguments
* $html **mixed**


