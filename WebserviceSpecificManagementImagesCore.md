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
* Namespace: 
* This class implements: [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface.md)




Properties
----------


### $objOutput

    protected \WebserviceOutputBuilder $objOutput





* Visibility: **protected**


### $output

    protected mixed $output





* Visibility: **protected**


### $wsObject

    protected \WebserviceRequest $wsObject





* Visibility: **protected**


### $imgExtension

    protected string $imgExtension





* Visibility: **protected**


### $imageTypes

    protected array $imageTypes = array('general' => array('header' => array(), 'mail' => array(), 'invoice' => array(), 'store_icon' => array()), 'products' => array(), 'categories' => array(), 'manufacturers' => array(), 'suppliers' => array(), 'stores' => array(), 'customizations' => array())





* Visibility: **protected**


### $imageType

    protected string $imageType = null





* Visibility: **protected**


### $imgMaxUploadSize

    protected integer $imgMaxUploadSize = 3000000





* Visibility: **protected**


### $acceptedImgMimeTypes

    protected array $acceptedImgMimeTypes = array('image/gif', 'image/jpg', 'image/jpeg', 'image/pjpeg', 'image/png', 'image/x-png')





* Visibility: **protected**


### $productImageDeclinationId

    protected string $productImageDeclinationId = null





* Visibility: **protected**


### $defaultImage

    protected boolean $defaultImage = false





* Visibility: **protected**


### $imgToDisplay

    public string $imgToDisplay = null





* Visibility: **public**


### $imageResource

    public mixed $imageResource = null





* Visibility: **public**


Methods
-------


### setObjectOutput

    mixed WebserviceSpecificManagementInterface::setObjectOutput(\WebserviceOutputBuilderCore $obj)





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface.md)


#### Arguments
* $obj **[WebserviceOutputBuilderCore](WebserviceOutputBuilderCore.md)**



### getObjectOutput

    mixed WebserviceSpecificManagementInterface::getObjectOutput()





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface.md)




### setWsObject

    mixed WebserviceSpecificManagementInterface::setWsObject(\WebserviceRequestCore $obj)





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface.md)


#### Arguments
* $obj **[WebserviceRequestCore](WebserviceRequestCore.md)**



### getWsObject

    mixed WebserviceSpecificManagementInterface::getWsObject()





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface.md)




### getContent

    array WebserviceSpecificManagementInterface::getContent()

This must be return an array with specific values as WebserviceRequest expects.



* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface.md)




### manage

    mixed WebserviceSpecificManagementInterface::manage()





* Visibility: **public**
* This method is defined by [WebserviceSpecificManagementInterface](WebserviceSpecificManagementInterface.md)




### manageImages

    boolean WebserviceSpecificManagementImagesCore::manageImages()

Management of images URL segment



* Visibility: **protected**




### manageGeneralImages

    boolean WebserviceSpecificManagementImagesCore::manageGeneralImages()

Management of general images



* Visibility: **protected**




### manageDefaultDeclinatedImages

    mixed WebserviceSpecificManagementImagesCore::manageDefaultDeclinatedImages($directory, $normal_image_sizes)





* Visibility: **protected**


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### manageListDeclinatedImages

    mixed WebserviceSpecificManagementImagesCore::manageListDeclinatedImages($directory, $normal_image_sizes)





* Visibility: **protected**


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### manageEntityDeclinatedImages

    mixed WebserviceSpecificManagementImagesCore::manageEntityDeclinatedImages($directory, $normal_image_sizes)





* Visibility: **protected**


#### Arguments
* $directory **mixed**
* $normal_image_sizes **mixed**



### manageDeclinatedImages

    boolean WebserviceSpecificManagementImagesCore::manageDeclinatedImages(string $directory)

Management of normal images (as categories, suppliers, manufacturers and stores)



* Visibility: **protected**


#### Arguments
* $directory **string** - &lt;p&gt;the file path of the root of the images folder type&lt;/p&gt;



### manageProductImages

    mixed WebserviceSpecificManagementImagesCore::manageProductImages()





* Visibility: **protected**




### getCustomizations

    mixed WebserviceSpecificManagementImagesCore::getCustomizations()





* Visibility: **protected**




### manageCustomizationImages

    mixed WebserviceSpecificManagementImagesCore::manageCustomizationImages()





* Visibility: **protected**




### manageDeclinatedImagesCRUD

    boolean WebserviceSpecificManagementImagesCore::manageDeclinatedImagesCRUD(boolean $filename_exists, string $filename, array $image_sizes, string $directory)

Management of normal images CRUD



* Visibility: **protected**


#### Arguments
* $filename_exists **boolean** - &lt;p&gt;if the filename exists&lt;/p&gt;
* $filename **string** - &lt;p&gt;the image path&lt;/p&gt;
* $image_sizes **array** - &lt;p&gt;The&lt;/p&gt;
* $directory **string**



### deleteImageOnDisk

    boolean WebserviceSpecificManagementImagesCore::deleteImageOnDisk(string $file_path, array $image_types, string $parent_path)

Delete the image on disk



* Visibility: **protected**


#### Arguments
* $file_path **string** - &lt;p&gt;the image file path&lt;/p&gt;
* $image_types **array** - &lt;p&gt;The different sizes&lt;/p&gt;
* $parent_path **string** - &lt;p&gt;The parent path&lt;/p&gt;



### writeImageOnDisk

    string WebserviceSpecificManagementImagesCore::writeImageOnDisk(string $base_path, string $new_path, integer $dest_width, integer $dest_height, array $image_types, string $parent_path)

Write the image on disk



* Visibility: **protected**


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


#### Arguments
* $reception_path **string**
* $dest_width **integer**
* $dest_height **integer**
* $image_types **array**
* $parent_path **string**


