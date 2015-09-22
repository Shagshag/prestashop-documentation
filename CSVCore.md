CSVCore
===============

Simple class to output CSV data
Uses CollectionCore




* Class name: CSVCore
* Namespace: 

* This class is defined in [classes/CSV.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#32)





Properties
----------


### $filename

    public mixed $filename





* Visibility: **public**
* This property is defined in [classes/CSV.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#34)


### $collection

    public mixed $collection





* Visibility: **public**
* This property is defined in [classes/CSV.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#35)


### $delimiter

    public mixed $delimiter





* Visibility: **public**
* This property is defined in [classes/CSV.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#36)


Methods
-------


### __construct

    mixed CSVCore::__construct(array|\Iterator $collection, string $filename, string $delimiter)

Loads objects, filename and optionnaly a delimiter.



* Visibility: **public**
* This method is defined in [classes/CSV.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#44)


#### Arguments
* $collection **array|Iterator** - &lt;p&gt;Collection of objects / arrays (of non-objects)&lt;/p&gt;
* $filename **string** - &lt;p&gt;: used later to save the file&lt;/p&gt;
* $delimiter **string** - &lt;p&gt;Optional : delimiter used&lt;/p&gt;



### export

    mixed CSVCore::export()

Main function
Adds headers
Outputs



* Visibility: **public**
* This method is defined in [classes/CSV.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#56)




### output

    mixed CSVCore::output($data)

Wraps data and echoes
Uses defined delimiter



* Visibility: **public**
* This method is defined in [classes/CSV.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#79)


#### Arguments
* $data **mixed**



### wrap

    string CSVCore::wrap(string $data)

Escapes data



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CSV.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#90)


#### Arguments
* $data **string**



### headers

    mixed CSVCore::headers()

Adds headers



* Visibility: **public**
* This method is defined in [classes/CSV.php line 99](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CSV.php#99)



