ImageCore
===============






* Class name: ImageCore
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in [classes/Image.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L27)





Properties
----------


### $id

    public mixed $id





* Visibility: **public**
* This property is defined in [classes/Image.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#29)


### $id_image

    public integer $id_image





* Visibility: **public**
* This property is defined in [classes/Image.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#32)


### $id_product

    public integer $id_product





* Visibility: **public**
* This property is defined in [classes/Image.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#35)


### $position

    public integer $position





* Visibility: **public**
* This property is defined in [classes/Image.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#38)


### $cover

    public boolean $cover





* Visibility: **public**
* This property is defined in [classes/Image.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#41)


### $legend

    public string $legend





* Visibility: **public**
* This property is defined in [classes/Image.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#44)


### $image_format

    public string $image_format = 'jpg'





* Visibility: **public**
* This property is defined in [classes/Image.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#47)


### $source_index

    public string $source_index





* Visibility: **public**
* This property is defined in [classes/Image.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#50)


### $folder

    protected string $folder





* Visibility: **protected**
* This property is defined in [classes/Image.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#53)


### $existing_path

    protected string $existing_path





* Visibility: **protected**
* This property is defined in [classes/Image.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#56)


### $access_rights

    protected integer $access_rights = 509





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Image.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#59)


### $definition

    public mixed $definition = array('table' => 'image', 'primary' => 'id_image', 'multilang' => true, 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'shop' => 'both', 'validate' => 'isUnsignedId', 'required' => true), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'cover' => array('type' => self::TYPE_BOOL, 'allow_null' => true, 'validate' => 'isBool', 'shop' => true), 'legend' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/Image.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#64)


### $_cacheGetSize

    protected mixed $_cacheGetSize = array()





* Visibility: **protected**
* This property is **static**.
* This property is defined in [classes/Image.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#76)


Methods
-------


### __construct

    mixed ImageCore::__construct($id, $id_lang)





* Visibility: **public**
* This method is defined in [classes/Image.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#78)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### add

    mixed ImageCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/Image.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#85)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed ImageCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/Image.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#100)


#### Arguments
* $null_values **mixed**



### delete

    mixed ImageCore::delete()





* Visibility: **public**
* This method is defined in [classes/Image.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#112)




### getBestImageAttribute

    array ImageCore::getBestImageAttribute(integer $id_shop, integer $id_lang, integer $id_product, integer $id_product_attribute)

Return first image (by position) associated with a product attribute



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#143)


#### Arguments
* $id_shop **integer** - &lt;p&gt;Shop ID&lt;/p&gt;
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $id_product **integer** - &lt;p&gt;Product ID&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Product Attribute ID&lt;/p&gt;



### getImages

    array ImageCore::getImages(integer $id_lang, integer $id_product, integer $id_product_attribute)

Return available images for a product



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#174)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $id_product **integer** - &lt;p&gt;Product ID&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Product Attribute ID&lt;/p&gt;



### hasImages

    boolean ImageCore::hasImages(integer $id_lang, integer $id_product, integer $id_product_attribute)

Check if a product has an image available



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#198)


#### Arguments
* $id_lang **integer** - &lt;p&gt;Language ID&lt;/p&gt;
* $id_product **integer** - &lt;p&gt;Product ID&lt;/p&gt;
* $id_product_attribute **integer** - &lt;p&gt;Product Attribute ID&lt;/p&gt;



### getAllImages

    array ImageCore::getAllImages()

Return Images



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#218)




### getImagesTotal

    integer ImageCore::getImagesTotal(integer $id_product)

Return number of images for a product



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#232)


#### Arguments
* $id_product **integer** - &lt;p&gt;Product ID&lt;/p&gt;



### getHighestPosition

    integer ImageCore::getHighestPosition(integer $id_product)

Return highest position of images for a product



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#247)


#### Arguments
* $id_product **integer** - &lt;p&gt;Product ID&lt;/p&gt;



### deleteCover

    boolean ImageCore::deleteCover(integer $id_product)

Delete product cover



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#262)


#### Arguments
* $id_product **integer** - &lt;p&gt;Product ID&lt;/p&gt;



### getCover

    boolean ImageCore::getCover(integer $id_product)

Get product cover



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#290)


#### Arguments
* $id_product **integer** - &lt;p&gt;Product ID&lt;/p&gt;



### duplicateProductImages

    mixed ImageCore::duplicateProductImages(integer $id_product_old, boolean $id_product_new, $combination_images)

Copy images from a product to another



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 305](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#305)


#### Arguments
* $id_product_old **integer** - &lt;p&gt;Source product ID&lt;/p&gt;
* $id_product_new **boolean** - &lt;p&gt;Destination product ID&lt;/p&gt;
* $combination_images **mixed**



### replaceAttributeImageAssociationId

    mixed ImageCore::replaceAttributeImageAssociationId($combination_images, $saved_id, $id_image)





* Visibility: **protected**
* This method is **static**.
* This method is defined in [classes/Image.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#350)


#### Arguments
* $combination_images **mixed**
* $saved_id **mixed**
* $id_image **mixed**



### duplicateAttributeImageAssociations

    boolean ImageCore::duplicateAttributeImageAssociations($combination_images)

Duplicate product attribute image associations



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#369)


#### Arguments
* $combination_images **mixed**



### positionImage

    mixed ImageCore::positionImage(integer $position, boolean $direction)

Reposition image



* Visibility: **public**
* This method is defined in [classes/Image.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#391)


#### Arguments
* $position **integer** - &lt;p&gt;Position&lt;/p&gt;
* $direction **boolean** - &lt;p&gt;Direction&lt;/p&gt;



### updatePosition

    integer ImageCore::updatePosition(integer $way, integer $position)

Change an image position and update relative positions



* Visibility: **public**
* This method is defined in [classes/Image.php line 426](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#426)


#### Arguments
* $way **integer** - &lt;p&gt;position is moved up if 0, moved down if 1&lt;/p&gt;
* $position **integer** - &lt;p&gt;new position of the moved image&lt;/p&gt;



### getSize

    mixed ImageCore::getSize($type)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 450](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#450)


#### Arguments
* $type **mixed**



### getWidth

    mixed ImageCore::getWidth($params, $smarty)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 462](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#462)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### getHeight

    mixed ImageCore::getHeight($params, $smarty)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 468](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#468)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### clearTmpDir

    mixed ImageCore::clearTmpDir()

Clear all images in tmp dir



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 477](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#477)




### deleteProductAttributeImage

    mixed ImageCore::deleteProductAttributeImage()

Delete Image - Product attribute associations for this image



* Visibility: **public**
* This method is defined in [classes/Image.php line 488](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#488)




### deleteImage

    mixed ImageCore::deleteImage($force_delete)

Delete the product image from disk and remove the containing folder if empty
Handles both legacy and new image filesystems



* Visibility: **public**
* This method is defined in [classes/Image.php line 501](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#501)


#### Arguments
* $force_delete **mixed**



### deleteAllImages

    boolean ImageCore::deleteAllImages(string $path, string $format)

Recursively deletes all product images in the given folder tree and removes empty folders.



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 563](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#563)


#### Arguments
* $path **string** - &lt;p&gt;folder containing the product images to delete&lt;/p&gt;
* $format **string** - &lt;p&gt;image format&lt;/p&gt;



### getExistingImgPath

    mixed ImageCore::getExistingImgPath()

Returns image path in the old or in the new filesystem

@ returns string image path

* Visibility: **public**
* This method is defined in [classes/Image.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#603)




### getImgFolder

    string ImageCore::getImgFolder()

Returns the path to the folder containing the image in the new filesystem



* Visibility: **public**
* This method is defined in [classes/Image.php line 625](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#625)




### createImgFolder

    boolean ImageCore::createImgFolder()

Create parent folders for the image in the new filesystem



* Visibility: **public**
* This method is defined in [classes/Image.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#643)




### getImgPath

    string ImageCore::getImgPath()

Returns the path to the image without file extension



* Visibility: **public**
* This method is defined in [classes/Image.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#669)




### getImgFolderStatic

    string ImageCore::getImgFolderStatic(mixed $id_image)

Returns the path to the folder containing the image in the new filesystem



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 685](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#685)


#### Arguments
* $id_image **mixed**



### moveToNewFileSystem

    mixed ImageCore::moveToNewFileSystem(integer $max_execution_time)

Move all legacy product image files from the image folder root to their subfolder in the new filesystem.

If max_execution_time is provided, stops before timeout and returns string "timeout".
If any image cannot be moved, stops and returns "false"

* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 702](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#702)


#### Arguments
* $max_execution_time **integer**



### testFileSystem

    boolean ImageCore::testFileSystem()

Try to create and delete some folders to check if moving images to new file system will be possible



* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/Image.php line 752](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#752)




### getPathForCreation

    string ImageCore::getPathForCreation()

Returns the path where a product image should be created (without file format)



* Visibility: **public**
* This method is defined in [classes/Image.php line 787](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#787)



