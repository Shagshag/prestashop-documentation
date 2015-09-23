Class file
=====================

file modification



* Class name: file
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 9](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L9)


Contents
--------


### Properties

* [$debug](#property-$debug)
* [$errors](#property-$errors)
* [$fileInfo](#property-$fileInfo)
* [$filePath](#property-$filePath)
* [$fileStat](#property-$fileStat)
* [$mask](#property-$mask)

### Methods

* [__construct](#method-__construct)
* [__recursive_remove_directory](#method-__recursive_remove_directory)
* [_debug](#method-_debug)
* [chown](#method-chown)
* [close](#method-close)
* [copyTo](#method-copyTo)
* [delete](#method-delete)
* [emptyFolder](#method-emptyFolder)
* [file](#method-file)
* [getFileInfo](#method-getFileInfo)
* [getNextAvailableFileName](#method-getNextAvailableFileName)
* [isReadable](#method-isReadable)
* [isWritable](#method-isWritable)
* [mkdir](#method-mkdir)
* [setLastModified](#method-setLastModified)




Properties
----------


### <a name="property-$debug"></a>$debug

```php
public mixed $debug = false
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 15](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L15).


### <a name="property-$errors"></a>$errors

```php
public mixed $errors = array()
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 16](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L16).


### <a name="property-$fileInfo"></a>$fileInfo

```php
public mixed $fileInfo = ""
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 11](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L11).


### <a name="property-$filePath"></a>$filePath

```php
public mixed $filePath = ""
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 12](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L12).


### <a name="property-$fileStat"></a>$fileStat

```php
public mixed $fileStat = ""
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 13](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L13).


### <a name="property-$mask"></a>$mask

```php
public mixed $mask = '0775'
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 14](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L14).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed file::__construct(string $path)
```

constructor



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 22](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L22)


#### Arguments
* $path **string** - the path to a file or folder



### <a name="method-__recursive_remove_directory"></a>__recursive_remove_directory

```php
boolean file::__recursive_remove_directory(string $directory, boolean $empty)
```

recursive_remove_directory( directory to delete, empty )
expects path to directory and optional TRUE / FALSE to empty
of course PHP has to have the rights to delete the directory
you specify and all files and folders inside the directory

to use this function to totally remove a directory, write:
recursive_remove_directory('path/to/directory/to/delete');
to use this function to empty a directory, write:
recursive_remove_directory('path/to/full_directory',TRUE);

* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L369)


#### Arguments
* $directory **string**
* $empty **boolean**



### <a name="method-_debug"></a>_debug

```php
mixed file::_debug($info)
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 345](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L345)


#### Arguments
* $info **mixed**



### <a name="method-chown"></a>chown

```php
mixed file::chown($path, $owner)
```

change the own of a file or folder



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 166](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L166)


#### Arguments
* $path **mixed**
* $owner **mixed**



### <a name="method-close"></a>close

```php
mixed file::close()
```

close



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 302](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L302)




### <a name="method-copyTo"></a>copyTo

```php
boolean file::copyTo(string $source, string $dest)
```

Copy a file, or recursively copy a folder and its contents



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 187](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L187)


#### Arguments
* $source **string** - Source path
* $dest **string** - Destination path



### <a name="method-delete"></a>delete

```php
boolean file::delete(string $path)
```

delete a file or a folder and all contents within that folder



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 313](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L313)


#### Arguments
* $path **string**



### <a name="method-emptyFolder"></a>emptyFolder

```php
boolean file::emptyFolder(string $path)
```

empty a folder



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 335](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L335)


#### Arguments
* $path **string**



### <a name="method-file"></a>file

```php
mixed file::file(string $path)
```

contructor



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L65)


#### Arguments
* $path **string**



### <a name="method-getFileInfo"></a>getFileInfo

```php
array file::getFileInfo()
```

get file information



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 294](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L294)




### <a name="method-getNextAvailableFileName"></a>getNextAvailableFileName

```php
string file::getNextAvailableFileName(string $fileToMove, string $destFolder)
```

get next available file name



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 257](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L257)


#### Arguments
* $fileToMove **string** - the path of the file will be moved to
* $destFolder **string** - the path of destination folder



### <a name="method-isReadable"></a>isReadable

```php
boolean file::isReadable($path)
```

Returns true if the files is readable.



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 113](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L113)


#### Arguments
* $path **mixed**



### <a name="method-isWritable"></a>isWritable

```php
boolean file::isWritable($path)
```

check if a file or folder writable



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L77)


#### Arguments
* $path **mixed**



### <a name="method-mkdir"></a>mkdir

```php
boolean file::mkdir($path, $mask, $dirOwner)
```

create a new folder



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L140)


#### Arguments
* $path **mixed**
* $mask **mixed**
* $dirOwner **mixed**



### <a name="method-setLastModified"></a>setLastModified

```php
boolean file::setLastModified(string $path, string $time)
```

change the modified time



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.file.php line 125](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.9/admin-dev/ajaxfilemanager/inc/class.file.php#L125)


#### Arguments
* $path **string**
* $time **string**


