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


### $objOutput

    protected \WebserviceOutputBuilder $objOutput





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#30)


### $output

    protected mixed $output





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#31)


### $wsObject

    protected \WebserviceRequest $wsObject





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#34)


### $imgExtension

    protected string $imgExtension





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#39)


### $imageTypes

    protected array $imageTypes = array('general' => array('header' => array(), 'mail' => array(), 'invoice' => array(), 'store_icon' => array()), 'products' => array(), 'categories' => array(), 'manufacturers' => array(), 'suppliers' => array(), 'stores' => array(), 'customizations' => array())





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#44)


### $imageType

    protected string $imageType = null





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 62](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#62)


### $imgMaxUploadSize

    protected integer $imgMaxUploadSize = 3000000





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 67](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#67)


### $acceptedImgMimeTypes

    protected array $acceptedImgMimeTypes = array('image/gif', 'image/jpg', 'image/jpeg', 'image/pjpeg', 'image/png', 'image/x-png')





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 72](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#72)


### $productImageDeclinationId

    protected string $productImageDeclinationId = null





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 77](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#77)


### $defaultImage

    protected boolean $defaultImage = false





* Visibility: **protected**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#82)


### $imgToDisplay

    public string $imgToDisplay = null





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 87](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#87)


### $imageResource

    public mixed $imageResource = null





* Visibility: **public**
* This property is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 88](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#88)


Methods
-------


### setObjectOutput

    mixed WebserviceSpecificManagementInterface::setObjectOutput(\WebserviceOutputBuilderCore $obj)





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface)
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#29)


#### Arguments
* $obj **[WebserviceOutputBuilderCore](WebserviceOutputBuilderCore)**



### getObjectOutput

    mixed WebserviceSpecificManagementInterface::getObjectOutput()





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface)
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#30)




### setWsObject

    mixed WebserviceSpecificManagementInterface::setWsObject(\WebserviceRequestCore $obj)





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface)
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#31)


#### Arguments
* $obj **[WebserviceRequestCore](WebserviceRequestCore)**



### getWsObject

    mixed WebserviceSpecificManagementInterface::getWsObject()





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface)
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#32)




### getContent

    array WebserviceSpecificManagementInterface::getContent()

This must be return an array with specific values as WebserviceRequest expects.



* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface)
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#41)




### manage

    mixed WebserviceSpecificManagementInterface::manage()





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface)
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#34)




### manageImages

    boolean WebserviceSpecificManagementImagesCore::manageImages()

Management of images URL segment



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 181](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#181)




### manageGeneralImages

    boolean WebserviceSpecificManagementImagesCore::manageGeneralImages()

Management of general images



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 348](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#348)




### manageDefaultDeclinatedImages

    mixed WebserviceSpecificManagementImagesCore::manageDefaultDeclinatedImages($directory, $normal_image_sizes)





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 437](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#437)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### manageListDeclinatedImages

    mixed WebserviceSpecificManagementImagesCore::manageListDeclinatedImages($directory, $normal_image_sizes)





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 479](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#479)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### manageEntityDeclinatedImages

    mixed WebserviceSpecificManagementImagesCore::manageEntityDeclinatedImages($directory, $normal_image_sizes)





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 523](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#523)


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### manageDeclinatedImages

    boolean WebserviceSpecificManagementImagesCore::manageDeclinatedImages(string $directory)

Management of normal images (as categories, suppliers, manufacturers and stores)



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 633](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#633)


#### Arguments
* $directory **string** - &lt;p&gt;the file path of the root of the images folder type&lt;/p&gt;



### manageProductImages

    mixed WebserviceSpecificManagementImagesCore::manageProductImages()





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 652](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#652)




### getCustomizations

    mixed WebserviceSpecificManagementImagesCore::getCustomizations()





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 657](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#657)




### manageCustomizationImages

    mixed WebserviceSpecificManagementImagesCore::manageCustomizationImages()





* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 674](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#674)




### manageDeclinatedImagesCRUD

    boolean WebserviceSpecificManagementImagesCore::manageDeclinatedImagesCRUD(boolean $filename_exists, string $filename, array $image_sizes, string $directory)

Management of normal images CRUD



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 774](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#774)


#### Arguments
* $filename_exists **boolean** - &lt;p&gt;if the filename exists&lt;/p&gt;
* $filename **string** - &lt;p&gt;the image path&lt;/p&gt;
* $image_sizes **array** - &lt;p&gt;The&lt;/p&gt;
* $directory **string**



### deleteImageOnDisk

    boolean WebserviceSpecificManagementImagesCore::deleteImageOnDisk(string $file_path, array $image_types, string $parent_path)

Delete the image on disk



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 843](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#843)


#### Arguments
* $file_path **string** - &lt;p&gt;the image file path&lt;/p&gt;
* $image_types **array** - &lt;p&gt;The different sizes&lt;/p&gt;
* $parent_path **string** - &lt;p&gt;The parent path&lt;/p&gt;



### writeImageOnDisk

    string WebserviceSpecificManagementImagesCore::writeImageOnDisk(string $base_path, string $new_path, integer $dest_width, integer $dest_height, array $image_types, string $parent_path)

Write the image on disk



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 883](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#883)


#### Arguments
* $base_path **string**
* $new_path **string**
* $dest_width **integer**
* $dest_height **integer**
* $image_types **array**
* $parent_path **string**



### writePostedImageOnDisk

    boolean WebserviceSpecificManagementImagesCore::writePostedImageOnDisk(string $reception_path, integer $dest_width, integer $dest_height, array $image_types, string $parent_path)

Write the posted image on disk



* Visibility: **protected**
* This method is defined in [classes/webservice/WebserviceSpecificManagementImages.php line 1003](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/webservice/WebserviceSpecificManagementImages.php#1003)


#### Arguments
* $reception_path **string**
* $dest_width **integer**
* $dest_height **integer**
* $image_types **array**
* $parent_path **string**


