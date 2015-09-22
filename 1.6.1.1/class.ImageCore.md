Class ImageCore
=====================





* Class name: ImageCore
* Parent class: [ObjectModel](class.ObjectModelCore)
* Source: [classes/Image.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L27)



Properties
----------

* [$_cacheGetSize](#property-$_cacheGetSize)
* [$access_rights](#property-$access_rights)
* [$cover](#property-$cover)
* [$definition](#property-$definition)
* [$existing_path](#property-$existing_path)
* [$folder](#property-$folder)
* [$id](#property-$id)
* [$id_image](#property-$id_image)
* [$id_product](#property-$id_product)
* [$image_format](#property-$image_format)
* [$legend](#property-$legend)
* [$position](#property-$position)
* [$source_index](#property-$source_index)

Methods
-------
* [__construct](#method-__construct)
* [add](#method-add)
* [clearTmpDir](#method-clearTmpDir)
* [createImgFolder](#method-createImgFolder)
* [delete](#method-delete)
* [deleteAllImages](#method-deleteAllImages)
* [deleteCover](#method-deleteCover)
* [deleteImage](#method-deleteImage)
* [deleteProductAttributeImage](#method-deleteProductAttributeImage)
* [duplicateAttributeImageAssociations](#method-duplicateAttributeImageAssociations)
* [duplicateProductImages](#method-duplicateProductImages)
* [getAllImages](#method-getAllImages)
* [getBestImageAttribute](#method-getBestImageAttribute)
* [getCover](#method-getCover)
* [getExistingImgPath](#method-getExistingImgPath)
* [getHeight](#method-getHeight)
* [getHighestPosition](#method-getHighestPosition)
* [getImages](#method-getImages)
* [getImagesTotal](#method-getImagesTotal)
* [getImgFolder](#method-getImgFolder)
* [getImgFolderStatic](#method-getImgFolderStatic)
* [getImgPath](#method-getImgPath)
* [getPathForCreation](#method-getPathForCreation)
* [getSize](#method-getSize)
* [getWidth](#method-getWidth)
* [hasImages](#method-hasImages)
* [moveToNewFileSystem](#method-moveToNewFileSystem)
* [positionImage](#method-positionImage)
* [replaceAttributeImageAssociationId](#method-replaceAttributeImageAssociationId)
* [testFileSystem](#method-testFileSystem)
* [update](#method-update)
* [updatePosition](#method-updatePosition)




Properties
----------


### <a name="property-$_cacheGetSize"></a>$_cacheGetSize

    protected mixed $_cacheGetSize = array()





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Image.php line 76](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L76)


### <a name="property-$access_rights"></a>$access_rights

    protected integer $access_rights = 509





* Visibility: **protected**
* This property is **static**.
* Source: [classes/Image.php line 59](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L59)


### <a name="property-$cover"></a>$cover

    public boolean $cover





* Visibility: **public**
* Source: [classes/Image.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L41)


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'image', 'primary' => 'id_image', 'multilang' => true, 'fields' => array('id_product' => array('type' => self::TYPE_INT, 'shop' => 'both', 'validate' => 'isUnsignedId', 'required' => true), 'position' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'cover' => array('type' => self::TYPE_BOOL, 'allow_null' => true, 'validate' => 'isBool', 'shop' => true), 'legend' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 128)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/Image.php line 64](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L64)


### <a name="property-$existing_path"></a>$existing_path

    protected string $existing_path





* Visibility: **protected**
* Source: [classes/Image.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L56)


### <a name="property-$folder"></a>$folder

    protected string $folder





* Visibility: **protected**
* Source: [classes/Image.php line 53](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L53)


### <a name="property-$id"></a>$id

    public mixed $id





* Visibility: **public**
* Source: [classes/Image.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L29)


### <a name="property-$id_image"></a>$id_image

    public integer $id_image





* Visibility: **public**
* Source: [classes/Image.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L32)


### <a name="property-$id_product"></a>$id_product

    public integer $id_product





* Visibility: **public**
* Source: [classes/Image.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L35)


### <a name="property-$image_format"></a>$image_format

    public string $image_format = 'jpg'





* Visibility: **public**
* Source: [classes/Image.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L47)


### <a name="property-$legend"></a>$legend

    public string $legend





* Visibility: **public**
* Source: [classes/Image.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L44)


### <a name="property-$position"></a>$position

    public integer $position





* Visibility: **public**
* Source: [classes/Image.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L38)


### <a name="property-$source_index"></a>$source_index

    public string $source_index





* Visibility: **public**
* Source: [classes/Image.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L50)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed ImageCore::__construct($id, $id_lang)





* Visibility: **public**
* Source: [classes/Image.php line 78](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L78)


#### Arguments
* $id **mixed**
* $id_lang **mixed**



### <a name="method-add"></a>add

    mixed ImageCore::add($autodate, $null_values)





* Visibility: **public**
* Source: [classes/Image.php line 85](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L85)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-clearTmpDir"></a>clearTmpDir

    mixed ImageCore::clearTmpDir()

Clear all images in tmp dir



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 477](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L477)




### <a name="method-createImgFolder"></a>createImgFolder

    boolean ImageCore::createImgFolder()

Create parent folders for the image in the new filesystem



* Visibility: **public**
* Source: [classes/Image.php line 643](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L643)




### <a name="method-delete"></a>delete

    mixed ImageCore::delete()





* Visibility: **public**
* Source: [classes/Image.php line 112](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L112)




### <a name="method-deleteAllImages"></a>deleteAllImages

    boolean ImageCore::deleteAllImages(string $path, string $format)

Recursively deletes all product images in the given folder tree and removes empty folders.



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 563](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L563)


#### Arguments
* $path **string** - folder containing the product images to delete
* $format **string** - image format



### <a name="method-deleteCover"></a>deleteCover

    boolean ImageCore::deleteCover(integer $id_product)

Delete product cover



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 262](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L262)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-deleteImage"></a>deleteImage

    mixed ImageCore::deleteImage($force_delete)

Delete the product image from disk and remove the containing folder if empty
Handles both legacy and new image filesystems



* Visibility: **public**
* Source: [classes/Image.php line 501](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L501)


#### Arguments
* $force_delete **mixed**



### <a name="method-deleteProductAttributeImage"></a>deleteProductAttributeImage

    mixed ImageCore::deleteProductAttributeImage()

Delete Image - Product attribute associations for this image



* Visibility: **public**
* Source: [classes/Image.php line 488](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L488)




### <a name="method-duplicateAttributeImageAssociations"></a>duplicateAttributeImageAssociations

    boolean ImageCore::duplicateAttributeImageAssociations($combination_images)

Duplicate product attribute image associations



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 369](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L369)


#### Arguments
* $combination_images **mixed**



### <a name="method-duplicateProductImages"></a>duplicateProductImages

    mixed ImageCore::duplicateProductImages(integer $id_product_old, boolean $id_product_new, $combination_images)

Copy images from a product to another



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 305](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L305)


#### Arguments
* $id_product_old **integer** - Source product ID
* $id_product_new **boolean** - Destination product ID
* $combination_images **mixed**



### <a name="method-getAllImages"></a>getAllImages

    array ImageCore::getAllImages()

Return Images



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L218)




### <a name="method-getBestImageAttribute"></a>getBestImageAttribute

    array ImageCore::getBestImageAttribute(integer $id_shop, integer $id_lang, integer $id_product, integer $id_product_attribute)

Return first image (by position) associated with a product attribute



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 143](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L143)


#### Arguments
* $id_shop **integer** - Shop ID
* $id_lang **integer** - Language ID
* $id_product **integer** - Product ID
* $id_product_attribute **integer** - Product Attribute ID



### <a name="method-getCover"></a>getCover

    boolean ImageCore::getCover(integer $id_product)

Get product cover



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 290](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L290)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-getExistingImgPath"></a>getExistingImgPath

    mixed ImageCore::getExistingImgPath()

Returns image path in the old or in the new filesystem

@ returns string image path

* Visibility: **public**
* Source: [classes/Image.php line 603](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L603)




### <a name="method-getHeight"></a>getHeight

    mixed ImageCore::getHeight($params, $smarty)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 468](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L468)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-getHighestPosition"></a>getHighestPosition

    integer ImageCore::getHighestPosition(integer $id_product)

Return highest position of images for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 247](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L247)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-getImages"></a>getImages

    array ImageCore::getImages(integer $id_lang, integer $id_product, integer $id_product_attribute)

Return available images for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 174](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L174)


#### Arguments
* $id_lang **integer** - Language ID
* $id_product **integer** - Product ID
* $id_product_attribute **integer** - Product Attribute ID



### <a name="method-getImagesTotal"></a>getImagesTotal

    integer ImageCore::getImagesTotal(integer $id_product)

Return number of images for a product



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L232)


#### Arguments
* $id_product **integer** - Product ID



### <a name="method-getImgFolder"></a>getImgFolder

    string ImageCore::getImgFolder()

Returns the path to the folder containing the image in the new filesystem



* Visibility: **public**
* Source: [classes/Image.php line 625](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L625)




### <a name="method-getImgFolderStatic"></a>getImgFolderStatic

    string ImageCore::getImgFolderStatic(mixed $id_image)

Returns the path to the folder containing the image in the new filesystem



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 685](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L685)


#### Arguments
* $id_image **mixed**



### <a name="method-getImgPath"></a>getImgPath

    string ImageCore::getImgPath()

Returns the path to the image without file extension



* Visibility: **public**
* Source: [classes/Image.php line 669](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L669)




### <a name="method-getPathForCreation"></a>getPathForCreation

    string ImageCore::getPathForCreation()

Returns the path where a product image should be created (without file format)



* Visibility: **public**
* Source: [classes/Image.php line 787](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L787)




### <a name="method-getSize"></a>getSize

    mixed ImageCore::getSize($type)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 450](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L450)


#### Arguments
* $type **mixed**



### <a name="method-getWidth"></a>getWidth

    mixed ImageCore::getWidth($params, $smarty)





* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 462](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L462)


#### Arguments
* $params **mixed**
* $smarty **mixed**



### <a name="method-hasImages"></a>hasImages

    boolean ImageCore::hasImages(integer $id_lang, integer $id_product, integer $id_product_attribute)

Check if a product has an image available



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 198](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L198)


#### Arguments
* $id_lang **integer** - Language ID
* $id_product **integer** - Product ID
* $id_product_attribute **integer** - Product Attribute ID



### <a name="method-moveToNewFileSystem"></a>moveToNewFileSystem

    mixed ImageCore::moveToNewFileSystem(integer $max_execution_time)

Move all legacy product image files from the image folder root to their subfolder in the new filesystem.

If max_execution_time is provided, stops before timeout and returns string "timeout".
If any image cannot be moved, stops and returns "false"

* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 702](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L702)


#### Arguments
* $max_execution_time **integer**



### <a name="method-positionImage"></a>positionImage

    mixed ImageCore::positionImage(integer $position, boolean $direction)

Reposition image



* Visibility: **public**
* Source: [classes/Image.php line 391](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L391)


#### Arguments
* $position **integer** - Position
* $direction **boolean** - Direction



### <a name="method-replaceAttributeImageAssociationId"></a>replaceAttributeImageAssociationId

    mixed ImageCore::replaceAttributeImageAssociationId($combination_images, $saved_id, $id_image)





* Visibility: **protected**
* This method is **static**.
* Source: [classes/Image.php line 350](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L350)


#### Arguments
* $combination_images **mixed**
* $saved_id **mixed**
* $id_image **mixed**



### <a name="method-testFileSystem"></a>testFileSystem

    boolean ImageCore::testFileSystem()

Try to create and delete some folders to check if moving images to new file system will be possible



* Visibility: **public**
* This method is **static**.
* Source: [classes/Image.php line 752](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L752)




### <a name="method-update"></a>update

    mixed ImageCore::update($null_values)





* Visibility: **public**
* Source: [classes/Image.php line 100](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L100)


#### Arguments
* $null_values **mixed**



### <a name="method-updatePosition"></a>updatePosition

    integer ImageCore::updatePosition(integer $way, integer $position)

Change an image position and update relative positions



* Visibility: **public**
* Source: [classes/Image.php line 426](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/Image.php#L426)


#### Arguments
* $way **integer** - position is moved up if 0, moved down if 1
* $position **integer** - new position of the moved image


