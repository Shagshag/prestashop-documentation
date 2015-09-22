AdminImagesControllerCore
===============






* Class name: AdminImagesControllerCore
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in [controllers/admin/AdminImagesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L30)





Properties
----------

* [$start_time](#property-$start_time)
* [$max_execution_time](#property-$max_execution_time)
* [$display_move](#property-$display_move)
* [$object](#property-$object)

Methods
-------
* [__construct](#method-__construct)
* [postProcess](#method-postProcess)
* [printEntityActiveIcon](#method-printEntityActiveIcon)
* [_childValidation](#method-_childValidation)
* [initRegenerate](#method-initRegenerate)
* [_deleteOldImages](#method-_deleteOldImages)
* [_regenerateNewImages](#method-_regenerateNewImages)
* [_regenerateNoPictureImages](#method-_regenerateNoPictureImages)
* [_regenerateWatermark](#method-_regenerateWatermark)
* [_regenerateThumbnails](#method-_regenerateThumbnails)
* [initMoveImages](#method-initMoveImages)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [_moveImagesToNewFileSystem](#method-_moveImagesToNewFileSystem)
* [initContent](#method-initContent)




Properties
----------


### <a name="property-$start_time"></a>$start_time

    protected mixed $start_time





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminImagesController.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L32)


### <a name="property-$max_execution_time"></a>$max_execution_time

    protected mixed $max_execution_time = 7200





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminImagesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L33)


### <a name="property-$display_move"></a>$display_move

    protected mixed $display_move





* Visibility: **protected**
* This property is defined in [controllers/admin/AdminImagesController.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L34)


### <a name="property-$object"></a>$object

    public \ImageType $object





* Visibility: **public**
* This property is defined in [controllers/admin/AdminImagesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L30)


Methods
-------


### <a name="method-__construct"></a>__construct

    mixed AdminImagesControllerCore::__construct()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImagesController.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L36)




### <a name="method-postProcess"></a>postProcess

    mixed AdminImagesControllerCore::postProcess()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImagesController.php line 360](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L360)




### <a name="method-printEntityActiveIcon"></a>printEntityActiveIcon

    mixed AdminImagesControllerCore::printEntityActiveIcon($value, $object)





* Visibility: **public**
* This method is **static**.
* This method is defined in [controllers/admin/AdminImagesController.php line 407](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L407)


#### Arguments
* $value **mixed**
* $object **mixed**



### <a name="method-_childValidation"></a>_childValidation

    mixed AdminImagesControllerCore::_childValidation()





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImagesController.php line 412](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L412)




### <a name="method-initRegenerate"></a>initRegenerate

    mixed AdminImagesControllerCore::initRegenerate()

Init display for the thumbnails regeneration block



* Visibility: **public**
* This method is defined in [controllers/admin/AdminImagesController.php line 422](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L422)




### <a name="method-_deleteOldImages"></a>_deleteOldImages

    boolean AdminImagesControllerCore::_deleteOldImages(string $dir, array $type, boolean $product)

Delete resized image then regenerate new one with updated settings



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImagesController.php line 453](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L453)


#### Arguments
* $dir **string**
* $type **array**
* $product **boolean**



### <a name="method-_regenerateNewImages"></a>_regenerateNewImages

    boolean|string AdminImagesControllerCore::_regenerateNewImages($dir, $type, boolean $productsImages)

Regenerate images



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImagesController.php line 502](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L502)


#### Arguments
* $dir **mixed**
* $type **mixed**
* $productsImages **boolean**



### <a name="method-_regenerateNoPictureImages"></a>_regenerateNoPictureImages

    boolean AdminImagesControllerCore::_regenerateNoPictureImages($dir, $type, $languages)

Regenerate no-pictures images



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImagesController.php line 581](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L581)


#### Arguments
* $dir **mixed**
* $type **mixed**
* $languages **mixed**



### <a name="method-_regenerateWatermark"></a>_regenerateWatermark

    mixed AdminImagesControllerCore::_regenerateWatermark($dir, $type)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImagesController.php line 609](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L609)


#### Arguments
* $dir **mixed**
* $type **mixed**



### <a name="method-_regenerateThumbnails"></a>_regenerateThumbnails

    mixed AdminImagesControllerCore::_regenerateThumbnails($type, $deleteOldImages)





* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImagesController.php line 637](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L637)


#### Arguments
* $type **mixed**
* $deleteOldImages **mixed**



### <a name="method-initMoveImages"></a>initMoveImages

    mixed AdminImagesControllerCore::initMoveImages()

Init display for move images block



* Visibility: **public**
* This method is defined in [controllers/admin/AdminImagesController.php line 700](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L700)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

    mixed AdminImagesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImagesController.php line 708](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L708)




### <a name="method-_moveImagesToNewFileSystem"></a>_moveImagesToNewFileSystem

    mixed AdminImagesControllerCore::_moveImagesToNewFileSystem()

Move product images to the new filesystem



* Visibility: **protected**
* This method is defined in [controllers/admin/AdminImagesController.php line 724](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L724)




### <a name="method-initContent"></a>initContent

    mixed AdminImagesControllerCore::initContent()





* Visibility: **public**
* This method is defined in [controllers/admin/AdminImagesController.php line 741](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/controllers/admin/AdminImagesController.php#L741)



