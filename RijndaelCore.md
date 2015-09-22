RijndaelCore
===============






* Class name: RijndaelCore
* This class is defined in [classes/Rijndael.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#L27)





Properties
----------


### $_key

    protected mixed $_key





* Visibility: **protected**
* This property is defined in [classes/Rijndael.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#29)


### $_iv

    protected mixed $_iv





* Visibility: **protected**
* This property is defined in [classes/Rijndael.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#30)


Methods
-------


### __construct

    mixed RijndaelCore::__construct($key, $iv)





* Visibility: **public**
* This method is defined in [classes/Rijndael.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#32)


#### Arguments
* $key **mixed**
* $iv **mixed**



### encrypt

    boolean|string RijndaelCore::encrypt(string $plaintext)

Base64 is not required, but it is be more compact than urlencode



* Visibility: **public**
* This method is defined in [classes/Rijndael.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#44)


#### Arguments
* $plaintext **string**



### decrypt

    mixed RijndaelCore::decrypt($ciphertext)





* Visibility: **public**
* This method is defined in [classes/Rijndael.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#54)


#### Arguments
* $ciphertext **mixed**


