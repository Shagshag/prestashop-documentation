Class CSVCore
=====================

Simple class to output CSV data
Uses CollectionCore



* Class name: CSVCore
* Source: [classes/CSV.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/CSV.php#L33)


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
* Source: [classes/CSV.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/CSV.php#L36).


### <a name="property-$delimiter"></a>$delimiter

```php
public mixed $delimiter
```





* Visibility: **public**
* Source: [classes/CSV.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/CSV.php#L37).


### <a name="property-$filename"></a>$filename

```php
public mixed $filename
```





* Visibility: **public**
* Source: [classes/CSV.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/CSV.php#L35).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed CSVCore::__construct(\Collection $collection, string $filename, string $delimiter)
```

Loads objects, filename and optionnaly a delimiter.



* Visibility: **public**
* Source: [classes/CSV.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/CSV.php#L45)


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
* Source: [classes/CSV.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/CSV.php#L57)




### <a name="method-headers"></a>headers

```php
mixed CSVCore::headers()
```

Adds headers



* Visibility: **public**
* Source: [classes/CSV.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/CSV.php#L102)




### <a name="method-output"></a>output

```php
mixed CSVCore::output($data)
```

Wraps data and echoes
Uses defined delimiter



* Visibility: **public**
* Source: [classes/CSV.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/CSV.php#L82)


#### Arguments
* $data **mixed**



### <a name="method-wrap"></a>wrap

```php
string CSVCore::wrap(string $data)
```

Escapes data



* Visibility: **public**
* This method is **static**.
* Source: [classes/CSV.php line 93](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.17/classes/CSV.php#L93)


#### Arguments
* $data **string**


