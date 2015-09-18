AdminImagesControllerCore
===============






* Class name: AdminImagesControllerCore
* Namespace: 
* Parent class: AdminController





Properties
----------


### $start_time

    protected mixed $start_time





* Visibility: **protected**


### $max_execution_time

    protected mixed $max_execution_time = 7200





* Visibility: **protected**


### $display_move

    protected mixed $display_move





* Visibility: **protected**


### $object

    public \ImageType $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminImagesControllerCore::__construct()





* Visibility: **public**




### postProcess

    mixed AdminImagesControllerCore::postProcess()





* Visibility: **public**




### printEntityActiveIcon

    mixed AdminImagesControllerCore::printEntityActiveIcon($value, $object)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $value **mixed**
* $object **mixed**



### _childValidation

    mixed AdminImagesControllerCore::_childValidation()





* Visibility: **protected**




### initRegenerate

    mixed AdminImagesControllerCore::initRegenerate()

Init display for the thumbnails regeneration block



* Visibility: **public**




### _deleteOldImages

    boolean AdminImagesControllerCore::_deleteOldImages(string $dir, array $type, boolean $product)

Delete resized image then regenerate new one with updated settings



* Visibility: **protected**


#### Arguments
* $dir **string**
* $type **array**
* $product **boolean**



### _regenerateNewImages

    boolean|string AdminImagesControllerCore::_regenerateNewImages($dir, $type, boolean $productsImages)

Regenerate images



* Visibility: **protected**


#### Arguments
* $dir **mixed**
* $type **mixed**
* $productsImages **boolean**



### _regenerateNoPictureImages

    boolean AdminImagesControllerCore::_regenerateNoPictureImages($dir, $type, $languages)

Regenerate no-pictures images



* Visibility: **protected**


#### Arguments
* $dir **mixed**
* $type **mixed**
* $languages **mixed**



### _regenerateWatermark

    mixed AdminImagesControllerCore::_regenerateWatermark($dir, $type)





* Visibility: **protected**


#### Arguments
* $dir **mixed**
* $type **mixed**



### _regenerateThumbnails

    mixed AdminImagesControllerCore::_regenerateThumbnails($type, $deleteOldImages)





* Visibility: **protected**


#### Arguments
* $type **mixed**
* $deleteOldImages **mixed**



### initMoveImages

    mixed AdminImagesControllerCore::initMoveImages()

Init display for move images block



* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminImagesControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### _moveImagesToNewFileSystem

    mixed AdminImagesControllerCore::_moveImagesToNewFileSystem()

Move product images to the new filesystem



* Visibility: **protected**




### initContent

    mixed AdminImagesControllerCore::initContent()





* Visibility: **public**



