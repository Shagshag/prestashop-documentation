CSVCore
===============

Simple class to output CSV data
Uses CollectionCore




* Class name: CSVCore
* Namespace: 





Properties
----------


### $filename

    public mixed $filename





* Visibility: **public**


### $collection

    public mixed $collection





* Visibility: **public**


### $delimiter

    public mixed $delimiter





* Visibility: **public**


Methods
-------


### __construct

    mixed CSVCore::__construct(array|\Iterator $collection, string $filename, string $delimiter)

Loads objects, filename and optionnaly a delimiter.



* Visibility: **public**


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




### output

    mixed CSVCore::output($data)

Wraps data and echoes
Uses defined delimiter



* Visibility: **public**


#### Arguments
* $data **mixed**



### wrap

    string CSVCore::wrap(string $data)

Escapes data



* Visibility: **public**
* This method is **static**.


#### Arguments
* $data **string**



### headers

    mixed CSVCore::headers()

Adds headers



* Visibility: **public**



