PrestaShopExceptionCore
===============






* Class name: PrestaShopExceptionCore
* Namespace: 
* Parent class: Exception







Methods
-------


### displayMessage

    mixed PrestaShopExceptionCore::displayMessage()

This method acts like an error handler, if dev mode is on, display the error else use a better silent way



* Visibility: **public**




### displayFileDebug

    mixed PrestaShopExceptionCore::displayFileDebug(string $file, integer $line, string $id)

Display lines around current line



* Visibility: **protected**


#### Arguments
* $file **string**
* $line **integer**
* $id **string**



### displayArgsDebug

    mixed PrestaShopExceptionCore::displayArgsDebug(array $args, string $id)

Display arguments list of traced function



* Visibility: **protected**


#### Arguments
* $args **array** - &lt;p&gt;List of arguments&lt;/p&gt;
* $id **string** - &lt;p&gt;ID of argument&lt;/p&gt;



### logError

    mixed PrestaShopExceptionCore::logError()

Log the error on the disk



* Visibility: **protected**




### getExentedMessage

    mixed PrestaShopExceptionCore::getExentedMessage($html)





* Visibility: **protected**


#### Arguments
* $html **mixed**



### getExtendedMessage

    string PrestaShopExceptionCore::getExtendedMessage($html)

Return the content of the Exception



* Visibility: **protected**


#### Arguments
* $html **mixed**


