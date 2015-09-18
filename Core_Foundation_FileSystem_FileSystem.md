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
* Namespace: 







Methods
-------


### normalizePath

    mixed Core_Foundation_FileSystem_FileSystem::normalizePath($path)

Replaces directory separators with the system's native one
and trims the trailing separator.



* Visibility: **public**


#### Arguments
* $path **mixed**



### joinTwoPaths

    mixed Core_Foundation_FileSystem_FileSystem::joinTwoPaths($a, $b)





* Visibility: **private**


#### Arguments
* $a **mixed**
* $b **mixed**



### joinPaths

    mixed Core_Foundation_FileSystem_FileSystem::joinPaths()

Joins an arbitrary number of paths, normalizing them along the way.



* Visibility: **public**




### listEntriesRecursively

    \an Core_Foundation_FileSystem_FileSystem::listEntriesRecursively($path)

Performs a depth first listing of directory entries.

Throws exception if $path is not a file.
If $path is a file and not a directory, just gets the file info for it
and return it in an array.

* Visibility: **public**


#### Arguments
* $path **mixed**



### matchOnlyFiles

    mixed Core_Foundation_FileSystem_FileSystem::matchOnlyFiles(\SplFileInfo $info)

Filter used by listFilesRecursively.



* Visibility: **private**


#### Arguments
* $info **SplFileInfo**



### listFilesRecursively

    mixed Core_Foundation_FileSystem_FileSystem::listFilesRecursively($path)

Same as listEntriesRecursively but returns only files.



* Visibility: **public**


#### Arguments
* $path **mixed**


