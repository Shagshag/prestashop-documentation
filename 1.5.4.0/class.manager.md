Class manager
=====================





* Class name: manager
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 10](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L10)


Contents
--------


### Properties

* [$calculateSubdir](#property-$calculateSubdir)
* [$currentFolderInfo](#property-$currentFolderInfo)
* [$currentFolderPath](#property-$currentFolderPath)
* [$fileTypes](#property-$fileTypes)
* [$flags](#property-$flags)
* [$folderPathIndex](#property-$folderPathIndex)
* [$forceFolderOnTop](#property-$forceFolderOnTop)
* [$lastVisitedFolderPathIndex](#property-$lastVisitedFolderPathIndex)
* [$sessionAction](#property-$sessionAction)

### Methods

* [__construct](#method-__construct)
* [_getExtension](#method-_getExtension)
* [getCurrentFolderPath](#method-getCurrentFolderPath)
* [getFileList](#method-getFileList)
* [getFileType](#method-getFileType)
* [getFileTypes](#method-getFileTypes)
* [getFolderInfo](#method-getFolderInfo)
* [isDirEmpty](#method-isDirEmpty)
* [manager](#method-manager)
* [printFileTypes](#method-printFileTypes)
* [setSessionAction](#method-setSessionAction)




Properties
----------


### <a name="property-$calculateSubdir"></a>$calculateSubdir

```php
public mixed $calculateSubdir = true
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L33).


### <a name="property-$currentFolderInfo"></a>$currentFolderInfo

```php
public mixed $currentFolderInfo = array('name' => '', 'subdir' => 0, 'file' => 0, 'ctime' => '', 'mtime' => '', 'is_readable' => '', 'is_writable' => '', 'size' => 0, 'path' => '', 'type' => 'folder', 'flag' => 'noFlag', 'friendly_path' => '')
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 16](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L16).


### <a name="property-$currentFolderPath"></a>$currentFolderPath

```php
public mixed $currentFolderPath
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 12](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L12).


### <a name="property-$fileTypes"></a>$fileTypes

```php
public mixed $fileTypes = array(array(array("exe", "com"), "fileExe", SEARCH_TYPE_EXE, 0), array(array("gif", "jpg", "png", "bmp", "tif"), "filePicture", SEARCH_TYPE_IMG, 1), array(array("zip", "sit", "rar", "gz", "tar"), "fileZip", SEARCH_TYPE_ARCHIVE, 0), array(array("htm", "html", "php", "jsp", "asp", 'js', 'css'), "fileCode", SEARCH_TYPE_HTML, 1), array(array("mov", "ram", "rm", "asx", "dcr", "wmv"), "fileVideo", SEARCH_TYPE_VIDEO, 1), array(array("mpg", "avi", "asf", "mpeg"), "fileVideo", SEARCH_TYPE_MOVIE, 1), array(array("aif", "aiff", "wav", "mp3", "wma"), "fileMusic", SEARCH_TYPE_MUSIC, 1), array(array("swf", 'flv'), "fileFlash", SEARCH_TYPE_FLASH, 1), array(array("ppt"), "filePPT", SEARCH_TYPE_PPT, 0), array(array("rtf"), "fileRTF", SEARCH_TYPE_DOC, 0), array(array("doc"), "fileWord", SEARCH_TYPE_WORD, 0), array(array("pdf"), "fileAcrobat", SEARCH_TYPE_PDF, 0), array(array("xls", "csv"), "fileExcel", SEARCH_TYPE_EXCEL, 0), array(array("txt"), "fileText", SEARCH_TYPE_TEXT, 1), array(array("xml", "xsl", "dtd"), "fileXml", SEARCH_TYPE_XML, 1))
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L34).


### <a name="property-$flags"></a>$flags

```php
public mixed $flags = array('no' => 'noFlag', 'cut' => 'cutFlag', 'copy' => 'copyFlag')
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 14](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L14).


### <a name="property-$folderPathIndex"></a>$folderPathIndex

```php
public mixed $folderPathIndex = "path"
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L32).


### <a name="property-$forceFolderOnTop"></a>$forceFolderOnTop

```php
public mixed $forceFolderOnTop = false
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 15](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L15).


### <a name="property-$lastVisitedFolderPathIndex"></a>$lastVisitedFolderPathIndex

```php
public mixed $lastVisitedFolderPathIndex = 'ajax_last_visited_folder'
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L31).


### <a name="property-$sessionAction"></a>$sessionAction

```php
public mixed $sessionAction = null
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 13](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L13).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed manager::__construct($path, $calculateSubdir)
```

constructor



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L57)


#### Arguments
* $path **mixed**
* $calculateSubdir **mixed**



### <a name="method-_getExtension"></a>_getExtension

```php
string manager::_getExtension(string $file, $checkIfDir)
```

Get the extension of a file name



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 339](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L339)


#### Arguments
* $file **string**
* $checkIfDir **mixed**



### <a name="method-getCurrentFolderPath"></a>getCurrentFolderPath

```php
string manager::getCurrentFolderPath()
```

get current folder path



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 132](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L132)




### <a name="method-getFileList"></a>getFileList

```php
array manager::getFileList()
```

get the list of files and folders under this current fold



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 140](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L140)




### <a name="method-getFileType"></a>getFileType

```php
array manager::getFileType($fileName, $checkIfDir)
```

return the file type of a file.



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 268](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L268)


#### Arguments
* $fileName **mixed**
* $checkIfDir **mixed**



### <a name="method-getFileTypes"></a>getFileTypes

```php
\arrray manager::getFileTypes()
```

return the predefined file types



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 310](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L310)




### <a name="method-getFolderInfo"></a>getFolderInfo

```php
array manager::getFolderInfo(string $path)
```

get current or the specified dir information



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L247)


#### Arguments
* $path **string**



### <a name="method-isDirEmpty"></a>isDirEmpty

```php
mixed manager::isDirEmpty($path)
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 352](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L352)


#### Arguments
* $path **mixed**



### <a name="method-manager"></a>manager

```php
mixed manager::manager($path, $calculateSubdir)
```

constructor



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 124](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L124)


#### Arguments
* $path **mixed**
* $calculateSubdir **mixed**



### <a name="method-printFileTypes"></a>printFileTypes

```php
mixed manager::printFileTypes()
```

print out the file types



* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L318)




### <a name="method-setSessionAction"></a>setSessionAction

```php
mixed manager::setSessionAction($session)
```





* Visibility: **public**
* Source: [admin-dev/ajaxfilemanager/inc/class.manager.php line 117](https://github.com/PrestaShop/PrestaShop/blob/1.5.4.0/admin-dev/ajaxfilemanager/inc/class.manager.php#L117)


#### Arguments
* $session **mixed**


