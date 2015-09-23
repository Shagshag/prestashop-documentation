Class AdminImagesControllerCore
=====================





* Class name: AdminImagesControllerCore
* Parent class: [AdminController](class.AdminControllerCore.md)
* Source: [controllers/admin/AdminImagesController.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L27)


Contents
--------


### Properties

* [$display_move](#property-$display_move)
* [$max_execution_time](#property-$max_execution_time)
* [$start_time](#property-$start_time)

### Methods

* [__construct](#method-__construct)
* [_childValidation](#method-_childValidation)
* [_deleteOldImages](#method-_deleteOldImages)
* [_moveImagesToNewFileSystem](#method-_moveImagesToNewFileSystem)
* [_regenerateNewImages](#method-_regenerateNewImages)
* [_regenerateNoPictureImages](#method-_regenerateNoPictureImages)
* [_regenerateThumbnails](#method-_regenerateThumbnails)
* [_regenerateWatermark](#method-_regenerateWatermark)
* [initContent](#method-initContent)
* [initMoveImages](#method-initMoveImages)
* [initPageHeaderToolbar](#method-initPageHeaderToolbar)
* [initRegenerate](#method-initRegenerate)
* [postProcess](#method-postProcess)
* [printEntityActiveIcon](#method-printEntityActiveIcon)




Properties
----------


### <a name="property-$display_move"></a>$display_move

```php
protected mixed $display_move
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImagesController.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L31).


### <a name="property-$max_execution_time"></a>$max_execution_time

```php
protected mixed $max_execution_time = 7200
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImagesController.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L30).


### <a name="property-$start_time"></a>$start_time

```php
protected mixed $start_time
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImagesController.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L29).


Methods
-------


### <a name="method-__construct"></a>__construct

```php
mixed AdminImagesControllerCore::__construct()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImagesController.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L33)




### <a name="method-_childValidation"></a>_childValidation

```php
mixed AdminImagesControllerCore::_childValidation()
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImagesController.php line 400](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L400)




### <a name="method-_deleteOldImages"></a>_deleteOldImages

```php
mixed AdminImagesControllerCore::_deleteOldImages($dir, $type, $product)
```

Delete resized image then regenerate new one with updated settings



* Visibility: **protected**
* Source: [controllers/admin/AdminImagesController.php line 433](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L433)


#### Arguments
* $dir **mixed**
* $type **mixed**
* $product **mixed**



### <a name="method-_moveImagesToNewFileSystem"></a>_moveImagesToNewFileSystem

```php
mixed AdminImagesControllerCore::_moveImagesToNewFileSystem()
```

Move product images to the new filesystem



* Visibility: **protected**
* Source: [controllers/admin/AdminImagesController.php line 664](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L664)




### <a name="method-_regenerateNewImages"></a>_regenerateNewImages

```php
boolean|string AdminImagesControllerCore::_regenerateNewImages($dir, $type, boolean $productsImages)
```

Regenerate images



* Visibility: **protected**
* Source: [controllers/admin/AdminImagesController.php line 476](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L476)


#### Arguments
* $dir **mixed**
* $type **mixed**
* $productsImages **boolean**



### <a name="method-_regenerateNoPictureImages"></a>_regenerateNoPictureImages

```php
boolean AdminImagesControllerCore::_regenerateNoPictureImages($dir, $type, $languages)
```

Regenerate no-pictures images



* Visibility: **protected**
* Source: [controllers/admin/AdminImagesController.php line 535](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L535)


#### Arguments
* $dir **mixed**
* $type **mixed**
* $languages **mixed**



### <a name="method-_regenerateThumbnails"></a>_regenerateThumbnails

```php
mixed AdminImagesControllerCore::_regenerateThumbnails($type, $deleteOldImages)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImagesController.php line 580](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L580)


#### Arguments
* $type **mixed**
* $deleteOldImages **mixed**



### <a name="method-_regenerateWatermark"></a>_regenerateWatermark

```php
mixed AdminImagesControllerCore::_regenerateWatermark($dir)
```





* Visibility: **protected**
* Source: [controllers/admin/AdminImagesController.php line 552](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L552)


#### Arguments
* $dir **mixed**



### <a name="method-initContent"></a>initContent

```php
mixed AdminImagesControllerCore::initContent()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImagesController.php line 681](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L681)




### <a name="method-initMoveImages"></a>initMoveImages

```php
mixed AdminImagesControllerCore::initMoveImages()
```

Init display for move images block



* Visibility: **public**
* Source: [controllers/admin/AdminImagesController.php line 641](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L641)




### <a name="method-initPageHeaderToolbar"></a>initPageHeaderToolbar

```php
mixed AdminImagesControllerCore::initPageHeaderToolbar()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImagesController.php line 649](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L649)




### <a name="method-initRegenerate"></a>initRegenerate

```php
mixed AdminImagesControllerCore::initRegenerate()
```

Init display for the thumbnails regeneration block



* Visibility: **public**
* Source: [controllers/admin/AdminImagesController.php line 409](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L409)




### <a name="method-postProcess"></a>postProcess

```php
mixed AdminImagesControllerCore::postProcess()
```





* Visibility: **public**
* Source: [controllers/admin/AdminImagesController.php line 344](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L344)




### <a name="method-printEntityActiveIcon"></a>printEntityActiveIcon

```php
mixed AdminImagesControllerCore::printEntityActiveIcon($value, $object)
```





* Visibility: **public**
* This method is **static**.
* Source: [controllers/admin/AdminImagesController.php line 395](https://github.com/PrestaShop/PrestaShop/blob/1.6.0.11/controllers/admin/AdminImagesController.php#L395)


#### Arguments
* $value **mixed**
* $object **mixed**


