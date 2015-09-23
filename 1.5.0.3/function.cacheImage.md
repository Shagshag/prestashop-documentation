Function cacheImage
===========================

Generate a cached thumbnail for object lists (eg. carrier, order states.

..etc)

```php
mixed cacheImage(string $image, string $cacheImage, integer $size, string $imageType, boolean $disableCache)
```

* Function name: cacheImage
* Source: [images.inc.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.5.0.3/images.inc.php#L37).

Arguments
---------

* $image **string** - Real image filename
* $cacheImage **string** - Cached filename
* $size **integer** - Desired size
* $imageType **string** - Image type
* $disableCache **boolean** - When turned on a timestamp will be added to the image URI to disable the HTTP cache

