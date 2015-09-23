Class WebserviceSpecificManagementImagesCore
=====================





* Class name: WebserviceSpecificManagementImagesCore
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 28](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L28)
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
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 69](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L69).


### <a name="property-$defaultImage"></a>$defaultImage

```php
protected boolean $defaultImage = false
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 79](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L79).


### <a name="property-$imageResource"></a>$imageResource

```php
public mixed $imageResource = null
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L85).


### <a name="property-$imageType"></a>$imageType

```php
private string $imageType = NULL
```





* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L59).


### <a name="property-$imageTypes"></a>$imageTypes

```php
private array $imageTypes = array('general' => array('header' => array(), 'mail' => array(), 'invoice' => array(), 'store_icon' => array()), 'products' => array(), 'categories' => array(), 'manufacturers' => array(), 'suppliers' => array(), 'stores' => array())
```





* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L42).


### <a name="property-$imgExtension"></a>$imgExtension

```php
protected string $imgExtension = 'jpg'
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L37).


### <a name="property-$imgMaxUploadSize"></a>$imgMaxUploadSize

```php
private integer $imgMaxUploadSize = 3000000
```





* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L64).


### <a name="property-$imgToDisplay"></a>$imgToDisplay

```php
public string $imgToDisplay = null
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 84](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L84).


### <a name="property-$objOutput"></a>$objOutput

```php
protected mixed $objOutput
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L30).


### <a name="property-$output"></a>$output

```php
protected mixed $output
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L31).


### <a name="property-$productImageDeclinationId"></a>$productImageDeclinationId

```php
protected string $productImageDeclinationId = NULL
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L74).


### <a name="property-$wsObject"></a>$wsObject

```php
protected mixed $wsObject
```





* Visibility: **protected**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L32).


Methods
-------


### <a name="method-deleteImageOnDisk"></a>deleteImageOnDisk

```php
boolean WebserviceSpecificManagementImagesCore::deleteImageOnDisk(string $filePath, array $imageTypes, string $parentPath)
```

Delete the image on disk



* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 738](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L738)


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
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L116)




### <a name="method-getObjectOutput"></a>getObjectOutput

```php
mixed WebserviceSpecificManagementImagesCore::getObjectOutput()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 97](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L97)




### <a name="method-getWsObject"></a>getWsObject

```php
mixed WebserviceSpecificManagementImagesCore::getWsObject()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 108](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L108)




### <a name="method-manage"></a>manage

```php
mixed WebserviceSpecificManagementImagesCore::manage()
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 142](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L142)




### <a name="method-manageDeclinatedImages"></a>manageDeclinatedImages

```php
boolean WebserviceSpecificManagementImagesCore::manageDeclinatedImages(string $directory)
```

Management of normal images (as categories, suppliers, manufacturers and stores)



* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 637](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L637)


#### Arguments
* $directory **string** - the file path of the root of the images folder type



### <a name="method-manageDeclinatedImagesCRUD"></a>manageDeclinatedImagesCRUD

```php
boolean WebserviceSpecificManagementImagesCore::manageDeclinatedImagesCRUD(boolean $filename_exists, string $filename, array $imageSizes, string $directory)
```

Management of normal images CRUD



* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 672](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L672)


#### Arguments
* $filename_exists **boolean** - if the filename exists
* $filename **string** - the image path
* $imageSizes **array** - The
* $directory **string**



### <a name="method-manageDefaultDeclinatedImages"></a>manageDefaultDeclinatedImages

```php
mixed WebserviceSpecificManagementImagesCore::manageDefaultDeclinatedImages($directory, $normal_image_sizes)
```





* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 413](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L413)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### <a name="method-manageEntityDeclinatedImages"></a>manageEntityDeclinatedImages

```php
mixed WebserviceSpecificManagementImagesCore::manageEntityDeclinatedImages($directory, $normal_image_sizes)
```





* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 505](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L505)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### <a name="method-manageGeneralImages"></a>manageGeneralImages

```php
boolean WebserviceSpecificManagementImagesCore::manageGeneralImages()
```

Management of general images



* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 318](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L318)




### <a name="method-manageImages"></a>manageImages

```php
boolean WebserviceSpecificManagementImagesCore::manageImages()
```

Management of images URL segment



* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 153](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L153)




### <a name="method-manageListDeclinatedImages"></a>manageListDeclinatedImages

```php
mixed WebserviceSpecificManagementImagesCore::manageListDeclinatedImages($directory, $normal_image_sizes)
```





* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 458](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L458)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### <a name="method-manageProductImages"></a>manageProductImages

```php
mixed WebserviceSpecificManagementImagesCore::manageProductImages()
```





* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 658](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L658)




### <a name="method-setObjectOutput"></a>setObjectOutput

```php
mixed WebserviceSpecificManagementImagesCore::setObjectOutput(\WebserviceOutputBuilderCore $obj)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 91](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L91)


#### Arguments
* $obj **[WebserviceOutputBuilderCore](class.WebserviceOutputBuilderCore.md)**



### <a name="method-setWsObject"></a>setWsObject

```php
mixed WebserviceSpecificManagementImagesCore::setWsObject(\WebserviceRequestCore $obj)
```





* Visibility: **public**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 102](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L102)


#### Arguments
* $obj **[WebserviceRequestCore](class.WebserviceRequestCore.md)**



### <a name="method-writeImageOnDisk"></a>writeImageOnDisk

```php
string WebserviceSpecificManagementImagesCore::writeImageOnDisk(string $basePath, string $newPath, integer $destWidth, integer $destHeight, array $imageTypes, string $parentPath)
```

Write the image on disk



* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 781](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L781)


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



* Visibility: **private**
* Source: [classes/webservice/WebserviceSpecificManagementImages.php line 891](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.2/classes/webservice/WebserviceSpecificManagementImages.php#L891)


#### Arguments
* $receptionPath **mixed**
* $destWidth **integer**
* $destHeight **integer**
* $imageTypes **array**
* $parentPath **string**


