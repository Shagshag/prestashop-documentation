Class AdminUpgrade
=====================





* Class name: AdminUpgrade
* Parent class: AdminPreferences
* Source: [admin-dev/tabs/AdminUpgrade.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L30)


Contents
--------


### Properties

* [$_includeContainer](#property-$_includeContainer)
* [$ajax](#property-$ajax)
* [$autoupgradeDir](#property-$autoupgradeDir)
* [$autoupgradePath](#property-$autoupgradePath)
* [$backupFileList](#property-$backupFileList)
* [$backupIgnoreAbsoluteFiles](#property-$backupIgnoreAbsoluteFiles)
* [$backupIgnoreFiles](#property-$backupIgnoreFiles)
* [$currentParams](#property-$currentParams)
* [$destDownloadFilename](#property-$destDownloadFilename)
* [$error](#property-$error)
* [$excludeAbsoluteFilesFromUpgrade](#property-$excludeAbsoluteFilesFromUpgrade)
* [$excludeFilesFromUpgrade](#property-$excludeFilesFromUpgrade)
* [$latestRootDir](#property-$latestRootDir)
* [$loopBackupFiles](#property-$loopBackupFiles)
* [$loopRemoveSamples](#property-$loopRemoveSamples)
* [$loopUpgradeFiles](#property-$loopUpgradeFiles)
* [$next](#property-$next)
* [$nextDesc](#property-$nextDesc)
* [$nextParams](#property-$nextParams)
* [$nextQuickInfo](#property-$nextQuickInfo)
* [$nextResponseType](#property-$nextResponseType)
* [$prodRootDir](#property-$prodRootDir)
* [$rootWritable](#property-$rootWritable)
* [$sampleFileList](#property-$sampleFileList)
* [$skipAction](#property-$skipAction)
* [$stepDone](#property-$stepDone)
* [$svnDir](#property-$svnDir)
* [$toUpgradeFileList](#property-$toUpgradeFileList)
* [$useSvn](#property-$useSvn)

### Methods

* [ZipExtract](#method-ZipExtract)
* [__construct](#method-__construct)
* [_cleanUp](#method-_cleanUp)
* [_displayRollbackForm](#method-_displayRollbackForm)
* [_displayUpgraderForm](#method-_displayUpgraderForm)
* [_getJsErrorMsgs](#method-_getJsErrorMsgs)
* [_getJsInit](#method-_getJsInit)
* [_listArchivedFiles](#method-_listArchivedFiles)
* [_listBackupFiles](#method-_listBackupFiles)
* [_listFilesToUpgrade](#method-_listFilesToUpgrade)
* [_listSampleFiles](#method-_listSampleFiles)
* [_modelDoUpgrade](#method-_modelDoUpgrade)
* [_removeOneSample](#method-_removeOneSample)
* [_setFields](#method-_setFields)
* [_skipFile](#method-_skipFile)
* [ajaxPreProcess](#method-ajaxPreProcess)
* [ajaxProcessBackupDb](#method-ajaxProcessBackupDb)
* [ajaxProcessBackupFiles](#method-ajaxProcessBackupFiles)
* [ajaxProcessDesactiveShop](#method-ajaxProcessDesactiveShop)
* [ajaxProcessDownload](#method-ajaxProcessDownload)
* [ajaxProcessRemoveSamples](#method-ajaxProcessRemoveSamples)
* [ajaxProcessRestoreDb](#method-ajaxProcessRestoreDb)
* [ajaxProcessRestoreFiles](#method-ajaxProcessRestoreFiles)
* [ajaxProcessRollback](#method-ajaxProcessRollback)
* [ajaxProcessSvnCheckout](#method-ajaxProcessSvnCheckout)
* [ajaxProcessSvnExport](#method-ajaxProcessSvnExport)
* [ajaxProcessUnzip](#method-ajaxProcessUnzip)
* [ajaxProcessUpgradeComplete](#method-ajaxProcessUpgradeComplete)
* [ajaxProcessUpgradeDb](#method-ajaxProcessUpgradeDb)
* [ajaxProcessUpgradeFiles](#method-ajaxProcessUpgradeFiles)
* [ajaxProcessUpgradeNow](#method-ajaxProcessUpgradeNow)
* [apacheModExists](#method-apacheModExists)
* [buildAjaxResult](#method-buildAjaxResult)
* [display](#method-display)
* [displayAjax](#method-displayAjax)
* [displayConf](#method-displayConf)
* [getFilePath](#method-getFilePath)
* [init](#method-init)
* [isUpgradeAllowed](#method-isUpgradeAllowed)
* [postProcess](#method-postProcess)
* [upgradeThisFile](#method-upgradeThisFile)




Properties
----------


### <a name="property-$_includeContainer"></a>$_includeContainer

```php
protected mixed $_includeContainer = false
```





* Visibility: **protected**
* Source: [admin-dev/tabs/AdminUpgrade.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L85).


### <a name="property-$ajax"></a>$ajax

```php
public mixed $ajax = false
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L32).


### <a name="property-$autoupgradeDir"></a>$autoupgradeDir

```php
public string $autoupgradeDir = 'autoupgrade'
```

autoupgradeDir



* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L53).


### <a name="property-$autoupgradePath"></a>$autoupgradePath

```php
public mixed $autoupgradePath = ''
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L47).


### <a name="property-$backupFileList"></a>$backupFileList

```php
public mixed $backupFileList = array()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 60](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L60).


### <a name="property-$backupIgnoreAbsoluteFiles"></a>$backupIgnoreAbsoluteFiles

```php
private mixed $backupIgnoreAbsoluteFiles = array()
```





* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L63).


### <a name="property-$backupIgnoreFiles"></a>$backupIgnoreFiles

```php
private mixed $backupIgnoreFiles = array()
```





* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L62).


### <a name="property-$currentParams"></a>$currentParams

```php
public mixed $currentParams = array()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L46).


### <a name="property-$destDownloadFilename"></a>$destDownloadFilename

```php
public mixed $destDownloadFilename = 'prestashop.zip'
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L58).


### <a name="property-$error"></a>$error

```php
public mixed $error = '0'
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L42).


### <a name="property-$excludeAbsoluteFilesFromUpgrade"></a>$excludeAbsoluteFilesFromUpgrade

```php
private mixed $excludeAbsoluteFilesFromUpgrade = array()
```





* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L65).


### <a name="property-$excludeFilesFromUpgrade"></a>$excludeFilesFromUpgrade

```php
private mixed $excludeFilesFromUpgrade = array()
```





* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L64).


### <a name="property-$latestRootDir"></a>$latestRootDir

```php
public mixed $latestRootDir = ''
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 54](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L54).


### <a name="property-$loopBackupFiles"></a>$loopBackupFiles

```php
public mixed $loopBackupFiles = 1000
```

int loopBackupFiles : if your server has a low memory size, lower this value



* Visibility: **public**
* This property is **static**.
* Source: [admin-dev/tabs/AdminUpgrade.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L71).


### <a name="property-$loopRemoveSamples"></a>$loopRemoveSamples

```php
public mixed $loopRemoveSamples = 1000
```

intloopRemoveSamples : if your server has a low memory size, lower this value



* Visibility: **public**
* This property is **static**.
* Source: [admin-dev/tabs/AdminUpgrade.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L79).


### <a name="property-$loopUpgradeFiles"></a>$loopUpgradeFiles

```php
public mixed $loopUpgradeFiles = 1000
```

int loopUpgradeFiles : if your server has a low memory size, lower this value



* Visibility: **public**
* This property is **static**.
* Source: [admin-dev/tabs/AdminUpgrade.php line 75](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L75).


### <a name="property-$next"></a>$next

```php
public mixed $next = 'N/A'
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L34).


### <a name="property-$nextDesc"></a>$nextDesc

```php
public mixed $nextDesc = '.'
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L43).


### <a name="property-$nextParams"></a>$nextParams

```php
public mixed $nextParams = array()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L44).


### <a name="property-$nextQuickInfo"></a>$nextQuickInfo

```php
public mixed $nextQuickInfo = array()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L45).


### <a name="property-$nextResponseType"></a>$nextResponseType

```php
public mixed $nextResponseType = 'json'
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L33).


### <a name="property-$prodRootDir"></a>$prodRootDir

```php
public mixed $prodRootDir = ''
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 55](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L55).


### <a name="property-$rootWritable"></a>$rootWritable

```php
public mixed $rootWritable = false
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L56).


### <a name="property-$sampleFileList"></a>$sampleFileList

```php
public mixed $sampleFileList = array()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 61](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L61).


### <a name="property-$skipAction"></a>$skipAction

```php
public mixed $skipAction
```





* Visibility: **public**
* This property is **static**.
* Source: [admin-dev/tabs/AdminUpgrade.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L82).


### <a name="property-$stepDone"></a>$stepDone

```php
public boolean $stepDone = true
```

set to false if the current step is a loop



* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L41).


### <a name="property-$svnDir"></a>$svnDir

```php
public mixed $svnDir = 'svn'
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 57](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L57).


### <a name="property-$toUpgradeFileList"></a>$toUpgradeFileList

```php
public mixed $toUpgradeFileList = array()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L59).


### <a name="property-$useSvn"></a>$useSvn

```php
public mixed $useSvn
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L83).


Methods
-------


### <a name="method-ZipExtract"></a>ZipExtract

```php
boolean AdminUpgrade::ZipExtract($fromFile, $toDir)
```





* Visibility: **private**
* This method is **static**.
* Source: [admin-dev/tabs/AdminUpgrade.php line 1781](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1781)


#### Arguments
* $fromFile **mixed**
* $toDir **mixed**



### <a name="method-__construct"></a>__construct

```php
mixed AdminUpgrade::__construct()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L87)




### <a name="method-_cleanUp"></a>_cleanUp

```php
mixed AdminUpgrade::_cleanUp($path)
```





* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1741](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1741)


#### Arguments
* $path **mixed**



### <a name="method-_displayRollbackForm"></a>_displayRollbackForm

```php
mixed AdminUpgrade::_displayRollbackForm()
```





* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1208](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1208)




### <a name="method-_displayUpgraderForm"></a>_displayUpgraderForm

```php
mixed AdminUpgrade::_displayUpgraderForm()
```





* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1226](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1226)




### <a name="method-_getJsErrorMsgs"></a>_getJsErrorMsgs

```php
mixed AdminUpgrade::_getJsErrorMsgs()
```





* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1143](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1143)




### <a name="method-_getJsInit"></a>_getJsInit

```php
mixed AdminUpgrade::_getJsInit()
```





* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1443](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1443)




### <a name="method-_listArchivedFiles"></a>_listArchivedFiles

```php
mixed AdminUpgrade::_listArchivedFiles()
```





* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1814](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1814)




### <a name="method-_listBackupFiles"></a>_listBackupFiles

```php
mixed AdminUpgrade::_listBackupFiles($dir)
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 378](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L378)


#### Arguments
* $dir **mixed**



### <a name="method-_listFilesToUpgrade"></a>_listFilesToUpgrade

```php
mixed AdminUpgrade::_listFilesToUpgrade($dir)
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 398](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L398)


#### Arguments
* $dir **mixed**



### <a name="method-_listSampleFiles"></a>_listSampleFiles

```php
void AdminUpgrade::_listSampleFiles(string $dir, string $fileext)
```

_listSampleFiles will make a recursive call to scandir() function
and list all file which match to the $fileext suffixe (this can be an extension or whole filename)



* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 354](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L354)


#### Arguments
* $dir **string** - directory to look in
* $fileext **string** - suffixe filename



### <a name="method-_modelDoUpgrade"></a>_modelDoUpgrade

```php
void AdminUpgrade::_modelDoUpgrade()
```

model_doUpgrade prepare the call to doUpgrade.php file (like model.php)



* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 496](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L496)




### <a name="method-_removeOneSample"></a>_removeOneSample

```php
mixed AdminUpgrade::_removeOneSample($removeList)
```





* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 921](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L921)


#### Arguments
* $removeList **mixed**



### <a name="method-_setFields"></a>_setFields

```php
void AdminUpgrade::_setFields()
```

_setFields function to set fields (only when we need it).



* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L102)




### <a name="method-_skipFile"></a>_skipFile

```php
mixed AdminUpgrade::_skipFile(\type $file, \type $fullpath, \type $way)
```

bool _skipFile : check whether a file is in backup or restore skip list



* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1846](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1846)


#### Arguments
* $file **type** - : current file or directory name eg:&#039;.svn&#039; , &#039;settings.inc.php&#039;
* $fullpath **type** - : current file or directory fullpath eg:&#039;/home/web/www/prestashop/img&#039;
* $way **type** - : &#039;backup&#039; , &#039;upgrade&#039;



### <a name="method-ajaxPreProcess"></a>ajaxPreProcess

```php
mixed AdminUpgrade::ajaxPreProcess()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1098](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1098)




### <a name="method-ajaxProcessBackupDb"></a>ajaxProcessBackupDb

```php
mixed AdminUpgrade::ajaxProcessBackupDb()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 807](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L807)




### <a name="method-ajaxProcessBackupFiles"></a>ajaxProcessBackupFiles

```php
mixed AdminUpgrade::ajaxProcessBackupFiles()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 825](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L825)




### <a name="method-ajaxProcessDesactiveShop"></a>ajaxProcessDesactiveShop

```php
mixed AdminUpgrade::ajaxProcessDesactiveShop()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 424](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L424)




### <a name="method-ajaxProcessDownload"></a>ajaxProcessDownload

```php
mixed AdminUpgrade::ajaxProcessDownload()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1042](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1042)




### <a name="method-ajaxProcessRemoveSamples"></a>ajaxProcessRemoveSamples

```php
mixed AdminUpgrade::ajaxProcessRemoveSamples()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 943](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L943)




### <a name="method-ajaxProcessRestoreDb"></a>ajaxProcessRestoreDb

```php
\type AdminUpgrade::ajaxProcessRestoreDb()
```

try to restore db backup file



* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 743](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L743)




### <a name="method-ajaxProcessRestoreFiles"></a>ajaxProcessRestoreFiles

```php
boolean AdminUpgrade::ajaxProcessRestoreFiles()
```

ajaxProcessRestoreFiles restore the previously saved files.



* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 690](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L690)




### <a name="method-ajaxProcessRollback"></a>ajaxProcessRollback

```php
mixed AdminUpgrade::ajaxProcessRollback()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 654](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L654)




### <a name="method-ajaxProcessSvnCheckout"></a>ajaxProcessSvnCheckout

```php
mixed AdminUpgrade::ajaxProcessSvnCheckout()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 984](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L984)




### <a name="method-ajaxProcessSvnExport"></a>ajaxProcessSvnExport

```php
mixed AdminUpgrade::ajaxProcessSvnExport()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 283](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L283)




### <a name="method-ajaxProcessUnzip"></a>ajaxProcessUnzip

```php
mixed AdminUpgrade::ajaxProcessUnzip()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 320](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L320)




### <a name="method-ajaxProcessUpgradeComplete"></a>ajaxProcessUpgradeComplete

```php
mixed AdminUpgrade::ajaxProcessUpgradeComplete()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 272](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L272)




### <a name="method-ajaxProcessUpgradeDb"></a>ajaxProcessUpgradeDb

```php
mixed AdminUpgrade::ajaxProcessUpgradeDb()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 559](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L559)




### <a name="method-ajaxProcessUpgradeFiles"></a>ajaxProcessUpgradeFiles

```php
mixed AdminUpgrade::ajaxProcessUpgradeFiles()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 440](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L440)




### <a name="method-ajaxProcessUpgradeNow"></a>ajaxProcessUpgradeNow

```php
mixed AdminUpgrade::ajaxProcessUpgradeNow()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 278](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L278)




### <a name="method-apacheModExists"></a>apacheModExists

```php
boolean AdminUpgrade::apacheModExists(string $name)
```

apacheModExists return true if the apache module $name is loaded



* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1128](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1128)


#### Arguments
* $name **string** - module name



### <a name="method-buildAjaxResult"></a>buildAjaxResult

```php
mixed AdminUpgrade::buildAjaxResult()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1065](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1065)




### <a name="method-display"></a>display

```php
mixed AdminUpgrade::display()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1365](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1365)




### <a name="method-displayAjax"></a>displayAjax

```php
mixed AdminUpgrade::displayAjax()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1204](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1204)




### <a name="method-displayConf"></a>displayConf

```php
void AdminUpgrade::displayConf()
```

displayConf



* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 1088](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L1088)




### <a name="method-getFilePath"></a>getFilePath

```php
void AdminUpgrade::getFilePath()
```

getFilePath return the path to the zipfile containing prestashop.



* Visibility: **private**
* Source: [admin-dev/tabs/AdminUpgrade.php line 259](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L259)




### <a name="method-init"></a>init

```php
void AdminUpgrade::init()
```

init to build informations we need



* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L154)




### <a name="method-isUpgradeAllowed"></a>isUpgradeAllowed

```php
void AdminUpgrade::isUpgradeAllowed()
```

isUpgradeAllowed checks if all server configuration is valid for upgrade



* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 139](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L139)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminUpgrade::postProcess()
```





* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 264](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L264)




### <a name="method-upgradeThisFile"></a>upgradeThisFile

```php
void AdminUpgrade::upgradeThisFile(mixed $file)
```

upgradeThisFile



* Visibility: **public**
* Source: [admin-dev/tabs/AdminUpgrade.php line 598](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.1/admin-dev/tabs/AdminUpgrade.php#L598)


#### Arguments
* $file **mixed**


