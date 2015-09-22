WebserviceSpecificManagementImagesCore
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


* Class name: WebserviceSpecificManagementImagesCore
* This class is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L27)
* This class implements: [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface)




Properties
----------

* [$objOutput](#property-$objOutput)
* [$output](#property-$output)
* [$wsObject](#property-$wsObject)
* [$imgExtension](#property-$imgExtension)
* [$imageTypes](#property-$imageTypes)
* [$imageType](#property-$imageType)
* [$imgMaxUploadSize](#property-$imgMaxUploadSize)
* [$acceptedImgMimeTypes](#property-$acceptedImgMimeTypes)
* [$productImageDeclinationId](#property-$productImageDeclinationId)
* [$defaultImage](#property-$defaultImage)
* [$imgToDisplay](#property-$imgToDisplay)
* [$imageResource](#property-$imageResource)

Methods
-------
* [setObjectOutput](#method-setObjectOutput)
* [getObjectOutput](#method-getObjectOutput)
* [setWsObject](#method-setWsObject)
* [getWsObject](#method-getWsObject)
* [getContent](#method-getContent)
* [manage](#method-manage)
* [manageImages](#method-manageImages)
* [manageGeneralImages](#method-manageGeneralImages)
* [manageDefaultDeclinatedImages](#method-manageDefaultDeclinatedImages)
* [manageListDeclinatedImages](#method-manageListDeclinatedImages)
* [manageEntityDeclinatedImages](#method-manageEntityDeclinatedImages)
* [manageDeclinatedImages](#method-manageDeclinatedImages)
* [manageProductImages](#method-manageProductImages)
* [getCustomizations](#method-getCustomizations)
* [manageCustomizationImages](#method-manageCustomizationImages)
* [manageDeclinatedImagesCRUD](#method-manageDeclinatedImagesCRUD)
* [deleteImageOnDisk](#method-deleteImageOnDisk)
* [writeImageOnDisk](#method-writeImageOnDisk)
* [writePostedImageOnDisk](#method-writePostedImageOnDisk)




Properties
----------


### <a name="property-$objOutput"></a>$objOutput

    protected \WebserviceOutputBuilder $objOutput





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L30)


### <a name="property-$output"></a>$output

    protected mixed $output





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L31)


### <a name="property-$wsObject"></a>$wsObject

    protected \WebserviceRequest $wsObject





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L34)


### <a name="property-$imgExtension"></a>$imgExtension

    protected string $imgExtension





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L39)


### <a name="property-$imageTypes"></a>$imageTypes

    protected array $imageTypes = array('general' => array('header' => array(), 'mail' => array(), 'invoice' => array(), 'store_icon' => array()), 'products' => array(), 'categories' => array(), 'manufacturers' => array(), 'suppliers' => array(), 'stores' => array(), 'customizations' => array())





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L44)


### <a name="property-$imageType"></a>$imageType

    protected string $imageType = null





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L62)


### <a name="property-$imgMaxUploadSize"></a>$imgMaxUploadSize

    protected integer $imgMaxUploadSize = 3000000





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L67)


### <a name="property-$acceptedImgMimeTypes"></a>$acceptedImgMimeTypes

    protected array $acceptedImgMimeTypes = array('image/gif', 'image/jpg', 'image/jpeg', 'image/pjpeg', 'image/png', 'image/x-png')





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L72)


### <a name="property-$productImageDeclinationId"></a>$productImageDeclinationId

    protected string $productImageDeclinationId = null





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L77)


### <a name="property-$defaultImage"></a>$defaultImage

    protected boolean $defaultImage = false





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L82)


### <a name="property-$imgToDisplay"></a>$imgToDisplay

    public string $imgToDisplay = null





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L87)


### <a name="property-$imageResource"></a>$imageResource

    public mixed $imageResource = null





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L88)


Methods
-------


### <a name="method-setObjectOutput"></a>setObjectOutput

    mixed WebserviceSpecificManagementInterface::setObjectOutput(\WebserviceOutputBuilderCore $obj)





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface)
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L29)


#### Arguments
* $obj **[WebserviceOutputBuilderCore](WebserviceOutputBuilderCore)**



### <a name="method-getObjectOutput"></a>getObjectOutput

    mixed WebserviceSpecificManagementInterface::getObjectOutput()





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface)
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L30)




### <a name="method-setWsObject"></a>setWsObject

    mixed WebserviceSpecificManagementInterface::setWsObject(\WebserviceRequestCore $obj)





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface)
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L31)


#### Arguments
* $obj **[WebserviceRequestCore](WebserviceRequestCore)**



### <a name="method-getWsObject"></a>getWsObject

    mixed WebserviceSpecificManagementInterface::getWsObject()





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface)
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L32)




### <a name="method-getContent"></a>getContent

    array WebserviceSpecificManagementInterface::getContent()

This must be return an array with specific values as WebserviceRequest expects.



* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface)
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L41)




### <a name="method-manage"></a>manage

    mixed WebserviceSpecificManagementInterface::manage()





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface)
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L34)




### <a name="method-manageImages"></a>manageImages

    boolean WebserviceSpecificManagementImagesCore::manageImages()

Management of images URL segment



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L181)




### <a name="method-manageGeneralImages"></a>manageGeneralImages

    boolean WebserviceSpecificManagementImagesCore::manageGeneralImages()

Management of general images



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L348)




### <a name="method-manageDefaultDeclinatedImages"></a>manageDefaultDeclinatedImages

    mixed WebserviceSpecificManagementImagesCore::manageDefaultDeclinatedImages($directory, $normal_image_sizes)





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L437)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### <a name="method-manageListDeclinatedImages"></a>manageListDeclinatedImages

    mixed WebserviceSpecificManagementImagesCore::manageListDeclinatedImages($directory, $normal_image_sizes)





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L479)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### <a name="method-manageEntityDeclinatedImages"></a>manageEntityDeclinatedImages

    mixed WebserviceSpecificManagementImagesCore::manageEntityDeclinatedImages($directory, $normal_image_sizes)





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L523)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### <a name="method-manageDeclinatedImages"></a>manageDeclinatedImages

    boolean WebserviceSpecificManagementImagesCore::manageDeclinatedImages(string $directory)

Management of normal images (as categories, suppliers, manufacturers and stores)



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 633](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L633)


#### Arguments
* $directory **string** - &lt;p&gt;the file path of the root of the images folder type&lt;/p&gt;



### <a name="method-manageProductImages"></a>manageProductImages

    mixed WebserviceSpecificManagementImagesCore::manageProductImages()





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 652](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L652)




### <a name="method-getCustomizations"></a>getCustomizations

    mixed WebserviceSpecificManagementImagesCore::getCustomizations()





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L657)




### <a name="method-manageCustomizationImages"></a>manageCustomizationImages

    mixed WebserviceSpecificManagementImagesCore::manageCustomizationImages()





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 674](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L674)




### <a name="method-manageDeclinatedImagesCRUD"></a>manageDeclinatedImagesCRUD

    boolean WebserviceSpecificManagementImagesCore::manageDeclinatedImagesCRUD(boolean $filename_exists, string $filename, array $image_sizes, string $directory)

Management of normal images CRUD



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 774](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L774)


#### Arguments
* $filename_exists **boolean** - &lt;p&gt;if the filename exists&lt;/p&gt;
* $filename **string** - &lt;p&gt;the image path&lt;/p&gt;
* $image_sizes **array** - &lt;p&gt;The&lt;/p&gt;
* $directory **string**



### <a name="method-deleteImageOnDisk"></a>deleteImageOnDisk

    boolean WebserviceSpecificManagementImagesCore::deleteImageOnDisk(string $file_path, array $image_types, string $parent_path)

Delete the image on disk



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 843](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L843)


#### Arguments
* $file_path **string** - &lt;p&gt;the image file path&lt;/p&gt;
* $image_types **array** - &lt;p&gt;The different sizes&lt;/p&gt;
* $parent_path **string** - &lt;p&gt;The parent path&lt;/p&gt;



### <a name="method-writeImageOnDisk"></a>writeImageOnDisk

    string WebserviceSpecificManagementImagesCore::writeImageOnDisk(string $base_path, string $new_path, integer $dest_width, integer $dest_height, array $image_types, string $parent_path)

Write the image on disk



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 883](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L883)


#### Arguments
* $base_path **string**
* $new_path **string**
* $dest_width **integer**
* $dest_height **integer**
* $image_types **array**
* $parent_path **string**



### <a name="method-writePostedImageOnDisk"></a>writePostedImageOnDisk

    boolean WebserviceSpecificManagementImagesCore::writePostedImageOnDisk(string $reception_path, integer $dest_width, integer $dest_height, array $image_types, string $parent_path)

Write the posted image on disk



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#L1003)


#### Arguments
* $reception_path **string**
* $dest_width **integer**
* $dest_height **integer**
* $image_types **array**
* $parent_path **string**


