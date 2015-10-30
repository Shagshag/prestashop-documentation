Class WebserviceSpecificManagementImagesCore
=====================

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

* Class name: WebserviceSpecificManagementImagesCore
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L27)
* This class implements: [WebserviceSpecificManagementInterface](interface.WebserviceSpecificManagementInterface.md)

Contents
--------


### Properties

* [$acceptedImgMimeTypes](#property-$acceptedImgMimeTypes)
* [$defaultImage](#property-$defaultImage)
* [$imageResource](#property-$imageResource)
* [$imageType](#property-$imageType)
* [$imageTypes](#property-$imageTypes)
* [$imgExtension](#property-$imgExtension)
* [$imgMaxUploadSize](#property-$imgMaxUploadSize)
* [$imgToDisplay](#property-$imgToDisplay)
* [$objOutput](#property-$objOutput)
* [$output](#property-$output)
* [$productImageDeclinationId](#property-$productImageDeclinationId)
* [$wsObject](#property-$wsObject)

### Methods

* [deleteImageOnDisk](#method-deleteImageOnDisk)
* [getContent](#method-getContent)
* [getCustomizations](#method-getCustomizations)
* [getObjectOutput](#method-getObjectOutput)
* [getWsObject](#method-getWsObject)
* [manage](#method-manage)
* [manageCustomizationImages](#method-manageCustomizationImages)
* [manageDeclinatedImages](#method-manageDeclinatedImages)
* [manageDeclinatedImagesCRUD](#method-manageDeclinatedImagesCRUD)
* [manageDefaultDeclinatedImages](#method-manageDefaultDeclinatedImages)
* [manageEntityDeclinatedImages](#method-manageEntityDeclinatedImages)
* [manageGeneralImages](#method-manageGeneralImages)
* [manageImages](#method-manageImages)
* [manageListDeclinatedImages](#method-manageListDeclinatedImages)
* [manageProductImages](#method-manageProductImages)
* [setObjectOutput](#method-setObjectOutput)
* [setWsObject](#method-setWsObject)
* [writeImageOnDisk](#method-writeImageOnDisk)
* [writePostedImageOnDisk](#method-writePostedImageOnDisk)




Properties
----------


### <a name="property-$acceptedImgMimeTypes"></a>$acceptedImgMimeTypes

```php
protected array $acceptedImgMimeTypes = array('image/gif', 'image/jpg', 'image/jpeg', 'image/pjpeg', 'image/png', 'image/x-png')
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L72).


### <a name="property-$defaultImage"></a>$defaultImage

```php
protected boolean $defaultImage = false
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L82).


### <a name="property-$imageResource"></a>$imageResource

```php
public mixed $imageResource = null
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L88).


### <a name="property-$imageType"></a>$imageType

```php
protected string $imageType = null
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L62).


### <a name="property-$imageTypes"></a>$imageTypes

```php
protected array $imageTypes = array('general' => array('header' => array(), 'mail' => array(), 'invoice' => array(), 'store_icon' => array()), 'products' => array(), 'categories' => array(), 'manufacturers' => array(), 'suppliers' => array(), 'stores' => array(), 'customizations' => array())
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L44).


### <a name="property-$imgExtension"></a>$imgExtension

```php
protected string $imgExtension
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L39).


### <a name="property-$imgMaxUploadSize"></a>$imgMaxUploadSize

```php
protected integer $imgMaxUploadSize = 3000000
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L67).


### <a name="property-$imgToDisplay"></a>$imgToDisplay

```php
public string $imgToDisplay = null
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L87).


### <a name="property-$objOutput"></a>$objOutput

```php
protected \WebserviceOutputBuilder $objOutput
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L30).


### <a name="property-$output"></a>$output

```php
protected mixed $output
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L31).


### <a name="property-$productImageDeclinationId"></a>$productImageDeclinationId

```php
protected string $productImageDeclinationId = null
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L77).


### <a name="property-$wsObject"></a>$wsObject

```php
protected \WebserviceRequest $wsObject
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L34).


Methods
-------


### <a name="method-deleteImageOnDisk"></a>deleteImageOnDisk

```php
boolean WebserviceSpecificManagementImagesCore::deleteImageOnDisk(string $file_path, array $image_types, string $parent_path)
```

Delete the image on disk



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 843](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L843)


#### Arguments
* $file_path **string** - the image file path
* $image_types **array** - The different sizes
* $parent_path **string** - The parent path



### <a name="method-getContent"></a>getContent

```php
mixed WebserviceSpecificManagementImagesCore::getContent()
```

This must be return an array with specific values as WebserviceRequest expects.



* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 123](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L123)




### <a name="method-getCustomizations"></a>getCustomizations

```php
mixed WebserviceSpecificManagementImagesCore::getCustomizations()
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L657)




### <a name="method-getObjectOutput"></a>getObjectOutput

```php
mixed WebserviceSpecificManagementImagesCore::getObjectOutput()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 104](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L104)




### <a name="method-getWsObject"></a>getWsObject

```php
mixed WebserviceSpecificManagementImagesCore::getWsObject()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L115)




### <a name="method-manage"></a>manage

```php
mixed WebserviceSpecificManagementImagesCore::manage()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 168](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L168)




### <a name="method-manageCustomizationImages"></a>manageCustomizationImages

```php
mixed WebserviceSpecificManagementImagesCore::manageCustomizationImages()
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 674](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L674)




### <a name="method-manageDeclinatedImages"></a>manageDeclinatedImages

```php
boolean WebserviceSpecificManagementImagesCore::manageDeclinatedImages(string $directory)
```

Management of normal images (as categories, suppliers, manufacturers and stores)



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 633](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L633)


#### Arguments
* $directory **string** - the file path of the root of the images folder type



### <a name="method-manageDeclinatedImagesCRUD"></a>manageDeclinatedImagesCRUD

```php
boolean WebserviceSpecificManagementImagesCore::manageDeclinatedImagesCRUD(boolean $filename_exists, string $filename, array $image_sizes, string $directory)
```

Management of normal images CRUD



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 774](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L774)


#### Arguments
* $filename_exists **boolean** - if the filename exists
* $filename **string** - the image path
* $image_sizes **array** - The
* $directory **string**



### <a name="method-manageDefaultDeclinatedImages"></a>manageDefaultDeclinatedImages

```php
mixed WebserviceSpecificManagementImagesCore::manageDefaultDeclinatedImages($directory, $normal_image_sizes)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L437)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### <a name="method-manageEntityDeclinatedImages"></a>manageEntityDeclinatedImages

```php
mixed WebserviceSpecificManagementImagesCore::manageEntityDeclinatedImages($directory, $normal_image_sizes)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L523)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### <a name="method-manageGeneralImages"></a>manageGeneralImages

```php
boolean WebserviceSpecificManagementImagesCore::manageGeneralImages()
```

Management of general images



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L348)




### <a name="method-manageImages"></a>manageImages

```php
boolean WebserviceSpecificManagementImagesCore::manageImages()
```

Management of images URL segment



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L181)




### <a name="method-manageListDeclinatedImages"></a>manageListDeclinatedImages

```php
mixed WebserviceSpecificManagementImagesCore::manageListDeclinatedImages($directory, $normal_image_sizes)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L479)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### <a name="method-manageProductImages"></a>manageProductImages

```php
mixed WebserviceSpecificManagementImagesCore::manageProductImages()
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 652](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L652)




### <a name="method-setObjectOutput"></a>setObjectOutput

```php
\WebserviceSpecificManagementInterface WebserviceSpecificManagementImagesCore::setObjectOutput(\WebserviceOutputBuilderCore $obj)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 98](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L98)


#### Arguments
* $obj **[WebserviceOutputBuilderCore](class.WebserviceOutputBuilderCore.md)**



### <a name="method-setWsObject"></a>setWsObject

```php
mixed WebserviceSpecificManagementImagesCore::setWsObject(\WebserviceRequestCore $obj)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 109](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L109)


#### Arguments
* $obj **[WebserviceRequestCore](class.WebserviceRequestCore.md)**



### <a name="method-writeImageOnDisk"></a>writeImageOnDisk

```php
string WebserviceSpecificManagementImagesCore::writeImageOnDisk(string $base_path, string $new_path, integer $dest_width, integer $dest_height, array $image_types, string $parent_path)
```

Write the image on disk



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 883](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L883)


#### Arguments
* $base_path **string**
* $new_path **string**
* $dest_width **integer**
* $dest_height **integer**
* $image_types **array**
* $parent_path **string**



### <a name="method-writePostedImageOnDisk"></a>writePostedImageOnDisk

```php
boolean WebserviceSpecificManagementImagesCore::writePostedImageOnDisk(string $reception_path, integer $dest_width, integer $dest_height, array $image_types, string $parent_path)
```

Write the posted image on disk



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.2/classes/webservice/WebserviceSpecificManagementImages.php#L1003)


#### Arguments
* $reception_path **string**
* $dest_width **integer**
* $dest_height **integer**
* $image_types **array**
* $parent_path **string**


