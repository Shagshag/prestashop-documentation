Class CSVCore
=====================

Simple class to output CSV data
Uses CollectionCore



* Class name: CSVCore
* Source: [classes/CSV.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.1/classes/CSV.php#L32)


Contents
--------


### Properties

* [$collection](#property-$collection)
* [$delimiter](#property-$delimiter)
* [$filename](#property-$filename)

### Methods

* [__construct](#method-__construct)
* [export](#method-export)
* [headers](#method-headers)
* [output](#method-output)
* [wrap](#method-wrap)




Properties
----------


### <a name="property-$collection"></a>$collection

```php
public mixed $collection
```





* Visibility: **public**
* Source: [classes/CSV.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.1/classes/CSV.php#L35).


### <a name="property-$delimiter"></a>$delimiter

```php
public mixed $delimiter
```





* Visibility: **public**
* Source: [classes/CSV.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.1/classes/CSV.php#L36).


### <a name="property-$filename"></a>$filename

```php
public mixed $filename
```





* Visibility: **public**
* Source: [classes/CSV.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.1/classes/CSV.php#L34).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CSVCore::__construct(\Collection $collection, string $filename, string $delimiter)
```

Loads objects, filename and optionnaly a delimiter.



* Visibility: **public**
* Source: [classes/CSV.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.1/classes/CSV.php#L44)


#### Arguments
* $collection **[Collection](class.CollectionCore.md)** - collection of objects / array (of non-objects)
* $filename **string** - : used later to save the file
* $delimiter **string** - Optional : delimiter used



### <a name="method-export"></a>export

```php
mixed CSVCore::export()
```

Main function
Adds headers
Outputs



* Visibility: **public**
* Source: [classes/CSV.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.1/classes/CSV.php#L56)




### <a name="method-headers"></a>headers

```php
mixed CSVCore::headers()
```

Adds headers



* Visibility: **public**
* Source: [classes/CSV.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.1/classes/CSV.php#L101)




### <a name="method-output"></a>output

```php
mixed CSVCore::output($data)
```

Wraps data and echoes
Uses defined delimiter



* Visibility: **public**
* Source: [classes/CSV.php line 81](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.1/classes/CSV.php#L81)


#### Arguments
* $data **mixed**



### <a name="method-wrap"></a>wrap

```php
string CSVCore::wrap(string $data)
```

Escapes data



* Visibility: **public**
* This method is **static**.
* Source: [classes/CSV.php line 92](https://github.com/PrestaShop/PrestaShop/blob/1.5.6.1/classes/CSV.php#L92)


#### Arguments
* $data **string**


