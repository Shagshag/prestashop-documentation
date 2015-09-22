Class RijndaelCore
=====================





* Class name: RijndaelCore
* Source: [classes/Rijndael.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#L27)


Contents
--------


### Properties

* [$_iv](#property-$_iv)
* [$_key](#property-$_key)

### Methods

* [__construct](#method-__construct)
* [decrypt](#method-decrypt)
* [encrypt](#method-encrypt)




Properties
----------


### <a name="property-$_iv"></a>$_iv

```php
protected mixed $_iv
```





* Visibility: **protected**
* Source: [classes/Rijndael.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#L30).


### <a name="property-$_key"></a>$_key

```php
protected mixed $_key
```





* Visibility: **protected**
* Source: [classes/Rijndael.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed RijndaelCore::__construct($key, $iv)
```





* Visibility: **public**
* Source: [classes/Rijndael.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#L32)


#### Arguments
* $key **mixed**
* $iv **mixed**



### <a name="method-decrypt"></a>decrypt

```php
mixed RijndaelCore::decrypt($ciphertext)
```





* Visibility: **public**
* Source: [classes/Rijndael.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#L54)


#### Arguments
* $ciphertext **mixed**



### <a name="method-encrypt"></a>encrypt

```php
boolean|string RijndaelCore::encrypt(string $plaintext)
```

Base64 is not required, but it is be more compact than urlencode



* Visibility: **public**
* Source: [classes/Rijndael.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Rijndael.php#L44)


#### Arguments
* $plaintext **string**


