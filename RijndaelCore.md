RijndaelCore
===============






* Class name: RijndaelCore
* Namespace: 





Properties
----------


### $_key

    protected mixed $_key





* Visibility: **protected**


### $_iv

    protected mixed $_iv





* Visibility: **protected**


Methods
-------


### __construct

    mixed RijndaelCore::__construct($key, $iv)





* Visibility: **public**


#### Arguments
* $key **mixed**
* $iv **mixed**



### encrypt

    boolean|string RijndaelCore::encrypt(string $plaintext)

Base64 is not required, but it is be more compact than urlencode



* Visibility: **public**


#### Arguments
* $plaintext **string**



### decrypt

    mixed RijndaelCore::decrypt($ciphertext)





* Visibility: **public**


#### Arguments
* $ciphertext **mixed**


