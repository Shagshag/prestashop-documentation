Core_Foundation_FileSystem_FileSystem
===============

2007-2015 PrestaShop

NOTICE OF LICENSE

This source file is subject to the Open Software License (OSL 3.0)
that is bundled with this package in the file LICENSE.txt.
It is also available through the world-wide-web at this URL:
http://opensource.org/licenses/osl-3.0.php
If you did not receive a copy of the license and are unable to
obtain it through the world-wide-web, please send an email
to license@prestashop.com so we can send you a copy immediately.

DISCLAIMER

Do not edit or add to this file if you wish to upgrade PrestaShop to newer
versions in the future. If you wish to customize PrestaShop for your
needs please refer to http://www.prestashop.com for more information.


* Class name: Core_Foundation_FileSystem_FileSystem
* This class is defined in [Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php#L27)







Methods
-------
* [normalizePath](#method-normalizePath)
* [joinTwoPaths](#method-joinTwoPaths)
* [joinPaths](#method-joinPaths)
* [listEntriesRecursively](#method-listEntriesRecursively)
* [matchOnlyFiles](#method-matchOnlyFiles)
* [listFilesRecursively](#method-listFilesRecursively)






Methods
-------


### <a name="method-normalizePath"></a>normalizePath

    mixed Core_Foundation_FileSystem_FileSystem::normalizePath($path)

Replaces directory separators with the system's native one
and trims the trailing separator.



* Visibility: **public**
* This method is defined in [Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php#L33)


#### Arguments
* $path **mixed**



### <a name="method-joinTwoPaths"></a>joinTwoPaths

    mixed Core_Foundation_FileSystem_FileSystem::joinTwoPaths($a, $b)





* Visibility: **private**
* This method is defined in [Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php#L41)


#### Arguments
* $a **mixed**
* $b **mixed**



### <a name="method-joinPaths"></a>joinPaths

    mixed Core_Foundation_FileSystem_FileSystem::joinPaths()

Joins an arbitrary number of paths, normalizing them along the way.



* Visibility: **public**
* This method is defined in [Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php line 49](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php#L49)




### <a name="method-listEntriesRecursively"></a>listEntriesRecursively

    \an Core_Foundation_FileSystem_FileSystem::listEntriesRecursively($path)

Performs a depth first listing of directory entries.

Throws exception if $path is not a file.
If $path is a file and not a directory, just gets the file info for it
and return it in an array.

* Visibility: **public**
* This method is defined in [Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php#L80)


#### Arguments
* $path **mixed**



### <a name="method-matchOnlyFiles"></a>matchOnlyFiles

    mixed Core_Foundation_FileSystem_FileSystem::matchOnlyFiles(\SplFileInfo $info)

Filter used by listFilesRecursively.



* Visibility: **private**
* This method is defined in [Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php line 126](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php#L126)


#### Arguments
* $info **SplFileInfo**



### <a name="method-listFilesRecursively"></a>listFilesRecursively

    mixed Core_Foundation_FileSystem_FileSystem::listFilesRecursively($path)

Same as listEntriesRecursively but returns only files.



* Visibility: **public**
* This method is defined in [Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php line 134](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/Core/Foundation/Filesystem/Core_Foundation_FileSystem_FileSystem.php#L134)


#### Arguments
* $path **mixed**


