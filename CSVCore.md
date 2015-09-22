CSVCore
===============

Simple class to output CSV data
Uses CollectionCore




* Class name: CSVCore
* This class is defined in [classes/CSV.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#L32)





Properties
----------

* [$filename](#property-$filename)
* [$collection](#property-$collection)
* [$delimiter](#property-$delimiter)

Methods
-------
* [__construct](#method-__construct)
* [export](#method-export)
* [output](#method-output)
* [wrap](#method-wrap)
* [headers](#method-headers)




Properties
----------


### <a name="property-$filename"></a>$filename

    public mixed $filename





* Visibility: **public**
* This property is defined in [classes/CSV.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#L34)


### <a name="property-$collection"></a>$collection

    public mixed $collection





* Visibility: **public**
* This property is defined in [classes/CSV.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#L35)


### <a name="property-$delimiter"></a>$delimiter

    public mixed $delimiter





* Visibility: **public**
* This property is defined in [classes/CSV.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#L36)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed CSVCore::__construct(array|\Iterator $collection, string $filename, string $delimiter)

Loads objects, filename and optionnaly a delimiter.



* Visibility: **public**
* This method is defined in [classes/CSV.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#L44)


#### Arguments
* $collection **array|Iterator** - &lt;p&gt;Collection of objects / arrays (of non-objects)&lt;/p&gt;
* $filename **string** - &lt;p&gt;: used later to save the file&lt;/p&gt;
* $delimiter **string** - &lt;p&gt;Optional : delimiter used&lt;/p&gt;



### <a name="method-export"></a>export

    mixed CSVCore::export()

Main function
Adds headers
Outputs



* Visibility: **public**
* This method is defined in [classes/CSV.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#L56)




### <a name="method-output"></a>output

    mixed CSVCore::output($data)

Wraps data and echoes
Uses defined delimiter



* Visibility: **public**
* This method is defined in [classes/CSV.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#L79)


#### Arguments
* $data **mixed**



### <a name="method-wrap"></a>wrap

    string CSVCore::wrap(string $data)

Escapes data



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CSV.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#L90)


#### Arguments
* $data **string**



### <a name="method-headers"></a>headers

    mixed CSVCore::headers()

Adds headers



* Visibility: **public**
* This method is defined in [classes/CSV.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#L99)



