Class WebserviceSpecificManagementImagesCore
=====================





* Class name: WebserviceSpecificManagementImagesCore
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L27)
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
* [getObjectOutput](#method-getObjectOutput)
* [getWsObject](#method-getWsObject)
* [manage](#method-manage)
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
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L68).


### <a name="property-$defaultImage"></a>$defaultImage

```php
protected boolean $defaultImage = false
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L78).


### <a name="property-$imageResource"></a>$imageResource

```php
public mixed $imageResource = null
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L84).


### <a name="property-$imageType"></a>$imageType

```php
protected string $imageType = null
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 58](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L58).


### <a name="property-$imageTypes"></a>$imageTypes

```php
protected array $imageTypes = array('general' => array('header' => array(), 'mail' => array(), 'invoice' => array(), 'store_icon' => array()), 'products' => array(), 'categories' => array(), 'manufacturers' => array(), 'suppliers' => array(), 'stores' => array())
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L41).


### <a name="property-$imgExtension"></a>$imgExtension

```php
protected string $imgExtension
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L36).


### <a name="property-$imgMaxUploadSize"></a>$imgMaxUploadSize

```php
protected integer $imgMaxUploadSize = 3000000
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L63).


### <a name="property-$imgToDisplay"></a>$imgToDisplay

```php
public string $imgToDisplay = null
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 83](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L83).


### <a name="property-$objOutput"></a>$objOutput

```php
protected mixed $objOutput
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L29).


### <a name="property-$output"></a>$output

```php
protected mixed $output
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L30).


### <a name="property-$productImageDeclinationId"></a>$productImageDeclinationId

```php
protected string $productImageDeclinationId = null
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 73](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L73).


### <a name="property-$wsObject"></a>$wsObject

```php
protected mixed $wsObject
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L31).


Methods
-------


### <a name="method-deleteImageOnDisk"></a>deleteImageOnDisk

```php
boolean WebserviceSpecificManagementImagesCore::deleteImageOnDisk(string $filePath, array $imageTypes, string $parentPath)
```

Delete the image on disk



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 753](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L753)


#### Arguments
* $filePath **string** - the image file path
* $imageTypes **array** - The differents sizes
* $parentPath **string** - The parent path



### <a name="method-getContent"></a>getContent

```php
mixed WebserviceSpecificManagementImagesCore::getContent()
```

This must be return an array with specific values as WebserviceRequest expects.



* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 115](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L115)




### <a name="method-getObjectOutput"></a>getObjectOutput

```php
mixed WebserviceSpecificManagementImagesCore::getObjectOutput()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 96](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L96)




### <a name="method-getWsObject"></a>getWsObject

```php
mixed WebserviceSpecificManagementImagesCore::getWsObject()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 107](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L107)




### <a name="method-manage"></a>manage

```php
mixed WebserviceSpecificManagementImagesCore::manage()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 162](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L162)




### <a name="method-manageDeclinatedImages"></a>manageDeclinatedImages

```php
boolean WebserviceSpecificManagementImagesCore::manageDeclinatedImages(string $directory)
```

Management of normal images (as categories, suppliers, manufacturers and stores)



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 647](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L647)


#### Arguments
* $directory **string** - the file path of the root of the images folder type



### <a name="method-manageDeclinatedImagesCRUD"></a>manageDeclinatedImagesCRUD

```php
boolean WebserviceSpecificManagementImagesCore::manageDeclinatedImagesCRUD(boolean $filename_exists, string $filename, array $imageSizes, string $directory)
```

Management of normal images CRUD



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 682](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L682)


#### Arguments
* $filename_exists **boolean** - if the filename exists
* $filename **string** - the image path
* $imageSizes **array** - The
* $directory **string**



### <a name="method-manageDefaultDeclinatedImages"></a>manageDefaultDeclinatedImages

```php
mixed WebserviceSpecificManagementImagesCore::manageDefaultDeclinatedImages($directory, $normal_image_sizes)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 434](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L434)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### <a name="method-manageEntityDeclinatedImages"></a>manageEntityDeclinatedImages

```php
mixed WebserviceSpecificManagementImagesCore::manageEntityDeclinatedImages($directory, $normal_image_sizes)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 526](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L526)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### <a name="method-manageGeneralImages"></a>manageGeneralImages

```php
boolean WebserviceSpecificManagementImagesCore::manageGeneralImages()
```

Management of general images



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 338](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L338)




### <a name="method-manageImages"></a>manageImages

```php
boolean WebserviceSpecificManagementImagesCore::manageImages()
```

Management of images URL segment



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 173](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L173)




### <a name="method-manageListDeclinatedImages"></a>manageListDeclinatedImages

```php
mixed WebserviceSpecificManagementImagesCore::manageListDeclinatedImages($directory, $normal_image_sizes)
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L479)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### <a name="method-manageProductImages"></a>manageProductImages

```php
mixed WebserviceSpecificManagementImagesCore::manageProductImages()
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 668](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L668)




### <a name="method-setObjectOutput"></a>setObjectOutput

```php
mixed WebserviceSpecificManagementImagesCore::setObjectOutput(\WebserviceOutputBuilderCore $obj)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L90)


#### Arguments
* $obj **[WebserviceOutputBuilderCore](class.WebserviceOutputBuilderCore.md)**



### <a name="method-setWsObject"></a>setWsObject

```php
mixed WebserviceSpecificManagementImagesCore::setWsObject(\WebserviceRequestCore $obj)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L101)


#### Arguments
* $obj **[WebserviceRequestCore](class.WebserviceRequestCore.md)**



### <a name="method-writeImageOnDisk"></a>writeImageOnDisk

```php
string WebserviceSpecificManagementImagesCore::writeImageOnDisk(string $basePath, string $newPath, integer $destWidth, integer $destHeight, array $imageTypes, string $parentPath)
```

Write the image on disk



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 796](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L796)


#### Arguments
* $basePath **string**
* $newPath **string**
* $destWidth **integer**
* $destHeight **integer**
* $imageTypes **array**
* $parentPath **string**



### <a name="method-writePostedImageOnDisk"></a>writePostedImageOnDisk

```php
boolean WebserviceSpecificManagementImagesCore::writePostedImageOnDisk($receptionPath, integer $destWidth, integer $destHeight, array $imageTypes, string $parentPath)
```

Write the posted image on disk



* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 911](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.9/classes/webservice/WebserviceSpecificManagementImages.php#L911)


#### Arguments
* $receptionPath **mixed**
* $destWidth **integer**
* $destHeight **integer**
* $imageTypes **array**
* $parentPath **string**


