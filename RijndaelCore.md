RijndaelCore
===============






* Class name: RijndaelCore
* This class is defined in [classes/Rijndael.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#L27)





Properties
----------

* [$_key](#property-$_key)
* [$_iv](#property-$_iv)

Methods
-------
* [__construct](#method-__construct)
* [encrypt](#method-encrypt)
* [decrypt](#method-decrypt)




Properties
----------


### <a name="property-$_key"></a>$_key

    protected mixed $_key





* Visibility: **protected**
* This property is defined in [classes/Rijndael.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#L29)


### <a name="property-$_iv"></a>$_iv

    protected mixed $_iv





* Visibility: **protected**
* This property is defined in [classes/Rijndael.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed RijndaelCore::__construct($key, $iv)





* Visibility: **public**
* This method is defined in [classes/Rijndael.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#L32)


#### Arguments
* $key **mixed**
* $iv **mixed**



### <a name="method-encrypt"></a>encrypt

    boolean|string RijndaelCore::encrypt(string $plaintext)

Base64 is not required, but it is be more compact than urlencode



* Visibility: **public**
* This method is defined in [classes/Rijndael.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#L44)


#### Arguments
* $plaintext **string**



### <a name="method-decrypt"></a>decrypt

    mixed RijndaelCore::decrypt($ciphertext)





* Visibility: **public**
* This method is defined in [classes/Rijndael.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#L54)


#### Arguments
* $ciphertext **mixed**


