AdminImagesControllerCore
===============






* Class name: AdminImagesControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminImagesController.php line 30





Properties
----------


### $start_time

    protected mixed $start_time





* Visibility: **protected**
* This property is defined in controllers\admin\AdminImagesController.php line 32


### $max_execution_time

    protected mixed $max_execution_time = 7200





* Visibility: **protected**
* This property is defined in controllers\admin\AdminImagesController.php line 33


### $display_move

    protected mixed $display_move





* Visibility: **protected**
* This property is defined in controllers\admin\AdminImagesController.php line 34


### $object

    public \ImageType $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminImagesController.php line 30


Methods
-------


### __construct

    mixed AdminImagesControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminImagesController.php line 36




### postProcess

    mixed AdminImagesControllerCore::postProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminImagesController.php line 360




### printEntityActiveIcon

    mixed AdminImagesControllerCore::printEntityActiveIcon($value, $object)





* Visibility: **public**
* This method is **static**.
* This method is defined in controllers\admin\AdminImagesController.php line 407


#### Arguments
* $value **mixed**
* $object **mixed**



### _childValidation

    mixed AdminImagesControllerCore::_childValidation()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminImagesController.php line 412




### initRegenerate

    mixed AdminImagesControllerCore::initRegenerate()

Init display for the thumbnails regeneration block



* Visibility: **public**
* This method is defined in controllers\admin\AdminImagesController.php line 422




### _deleteOldImages

    boolean AdminImagesControllerCore::_deleteOldImages(string $dir, array $type, boolean $product)

Delete resized image then regenerate new one with updated settings



* Visibility: **protected**
* This method is defined in controllers\admin\AdminImagesController.php line 453


#### Arguments
* $dir **string**
* $type **array**
* $product **boolean**



### _regenerateNewImages

    boolean|string AdminImagesControllerCore::_regenerateNewImages($dir, $type, boolean $productsImages)

Regenerate images



* Visibility: **protected**
* This method is defined in controllers\admin\AdminImagesController.php line 502


#### Arguments
* $dir **mixed**
* $type **mixed**
* $productsImages **boolean**



### _regenerateNoPictureImages

    boolean AdminImagesControllerCore::_regenerateNoPictureImages($dir, $type, $languages)

Regenerate no-pictures images



* Visibility: **protected**
* This method is defined in controllers\admin\AdminImagesController.php line 581


#### Arguments
* $dir **mixed**
* $type **mixed**
* $languages **mixed**



### _regenerateWatermark

    mixed AdminImagesControllerCore::_regenerateWatermark($dir, $type)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminImagesController.php line 609


#### Arguments
* $dir **mixed**
* $type **mixed**



### _regenerateThumbnails

    mixed AdminImagesControllerCore::_regenerateThumbnails($type, $deleteOldImages)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminImagesController.php line 637


#### Arguments
* $type **mixed**
* $deleteOldImages **mixed**



### initMoveImages

    mixed AdminImagesControllerCore::initMoveImages()

Init display for move images block



* Visibility: **public**
* This method is defined in controllers\admin\AdminImagesController.php line 700




### initPageHeaderToolbar

    mixed AdminImagesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminImagesController.php line 708




### _moveImagesToNewFileSystem

    mixed AdminImagesControllerCore::_moveImagesToNewFileSystem()

Move product images to the new filesystem



* Visibility: **protected**
* This method is defined in controllers\admin\AdminImagesController.php line 724




### initContent

    mixed AdminImagesControllerCore::initContent()





* Visibility: **public**
* This method is defined in controllers\admin\AdminImagesController.php line 741



