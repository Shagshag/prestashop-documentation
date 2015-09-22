HelperUploaderCore
===============






* Class name: HelperUploaderCore
* Parent class: [Uploader](UploaderCore)
* This class is defined in [classes/helper/HelperUploader.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L27)



Constants
----------

* [DEFAULT_TEMPLATE_DIRECTORY](#constant-DEFAULT_TEMPLATE_DIRECTORY)
* [DEFAULT_TEMPLATE](#constant-DEFAULT_TEMPLATE)
* [DEFAULT_AJAX_TEMPLATE](#constant-DEFAULT_AJAX_TEMPLATE)
* [TYPE_IMAGE](#constant-TYPE_IMAGE)
* [TYPE_FILE](#constant-TYPE_FILE)

Properties
----------

* [$_context](#property-$_context)
* [$_drop_zone](#property-$_drop_zone)
* [$_id](#property-$_id)
* [$_files](#property-$_files)
* [$_name](#property-$_name)
* [$_max_files](#property-$_max_files)
* [$_multiple](#property-$_multiple)
* [$_post_max_size](#property-$_post_max_size)
* [$_template](#property-$_template)
* [$_template_directory](#property-$_template_directory)
* [$_title](#property-$_title)
* [$_url](#property-$_url)
* [$_use_ajax](#property-$_use_ajax)

Methods
-------
* [setContext](#method-setContext)
* [getContext](#method-getContext)
* [setDropZone](#method-setDropZone)
* [getDropZone](#method-getDropZone)
* [setId](#method-setId)
* [getId](#method-getId)
* [setFiles](#method-setFiles)
* [getFiles](#method-getFiles)
* [setMaxFiles](#method-setMaxFiles)
* [getMaxFiles](#method-getMaxFiles)
* [setMultiple](#method-setMultiple)
* [setName](#method-setName)
* [getName](#method-getName)
* [setPostMaxSize](#method-setPostMaxSize)
* [getPostMaxSize](#method-getPostMaxSize)
* [setTemplate](#method-setTemplate)
* [getTemplate](#method-getTemplate)
* [setTemplateDirectory](#method-setTemplateDirectory)
* [getTemplateDirectory](#method-getTemplateDirectory)
* [getTemplateFile](#method-getTemplateFile)
* [setTitle](#method-setTitle)
* [getTitle](#method-getTitle)
* [setUrl](#method-setUrl)
* [getUrl](#method-getUrl)
* [setUseAjax](#method-setUseAjax)
* [isMultiple](#method-isMultiple)
* [render](#method-render)
* [useAjax](#method-useAjax)


Constants
----------


### <a name="constant-DEFAULT_TEMPLATE_DIRECTORY"></a>DEFAULT_TEMPLATE_DIRECTORY

    const DEFAULT_TEMPLATE_DIRECTORY = 'helpers/uploader'



* This constant is defined in [classes/helper/HelperUploader.php line 29](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L29)


### <a name="constant-DEFAULT_TEMPLATE"></a>DEFAULT_TEMPLATE

    const DEFAULT_TEMPLATE = 'simple.tpl'



* This constant is defined in [classes/helper/HelperUploader.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L30)


### <a name="constant-DEFAULT_AJAX_TEMPLATE"></a>DEFAULT_AJAX_TEMPLATE

    const DEFAULT_AJAX_TEMPLATE = 'ajax.tpl'



* This constant is defined in [classes/helper/HelperUploader.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L31)


### <a name="constant-TYPE_IMAGE"></a>TYPE_IMAGE

    const TYPE_IMAGE = 'image'



* This constant is defined in [classes/helper/HelperUploader.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L33)


### <a name="constant-TYPE_FILE"></a>TYPE_FILE

    const TYPE_FILE = 'file'



* This constant is defined in [classes/helper/HelperUploader.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L34)


Properties
----------


### <a name="property-$_context"></a>$_context

    private mixed $_context





* Visibility: **private**
* This property is defined in [classes/helper/HelperUploader.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L36)


### <a name="property-$_drop_zone"></a>$_drop_zone

    private mixed $_drop_zone





* Visibility: **private**
* This property is defined in [classes/helper/HelperUploader.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L37)


### <a name="property-$_id"></a>$_id

    private mixed $_id





* Visibility: **private**
* This property is defined in [classes/helper/HelperUploader.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L38)


### <a name="property-$_files"></a>$_files

    private mixed $_files





* Visibility: **private**
* This property is defined in [classes/helper/HelperUploader.php line 39](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L39)


### <a name="property-$_name"></a>$_name

    private mixed $_name





* Visibility: **private**
* This property is defined in [classes/helper/HelperUploader.php line 40](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L40)


### <a name="property-$_max_files"></a>$_max_files

    private mixed $_max_files





* Visibility: **private**
* This property is defined in [classes/helper/HelperUploader.php line 41](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L41)


### <a name="property-$_multiple"></a>$_multiple

    private mixed $_multiple





* Visibility: **private**
* This property is defined in [classes/helper/HelperUploader.php line 42](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L42)


### <a name="property-$_post_max_size"></a>$_post_max_size

    private mixed $_post_max_size





* Visibility: **private**
* This property is defined in [classes/helper/HelperUploader.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L43)


### <a name="property-$_template"></a>$_template

    protected mixed $_template





* Visibility: **protected**
* This property is defined in [classes/helper/HelperUploader.php line 44](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L44)


### <a name="property-$_template_directory"></a>$_template_directory

    private mixed $_template_directory





* Visibility: **private**
* This property is defined in [classes/helper/HelperUploader.php line 45](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L45)


### <a name="property-$_title"></a>$_title

    private mixed $_title





* Visibility: **private**
* This property is defined in [classes/helper/HelperUploader.php line 46](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L46)


### <a name="property-$_url"></a>$_url

    private mixed $_url





* Visibility: **private**
* This property is defined in [classes/helper/HelperUploader.php line 47](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L47)


### <a name="property-$_use_ajax"></a>$_use_ajax

    private mixed $_use_ajax





* Visibility: **private**
* This property is defined in [classes/helper/HelperUploader.php line 48](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L48)


Methods
-------


### <a name="method-setContext"></a>setContext

    mixed HelperUploaderCore::setContext($value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 50](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L50)


#### Arguments
* $value **mixed**



### <a name="method-getContext"></a>getContext

    mixed HelperUploaderCore::getContext()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 56](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L56)




### <a name="method-setDropZone"></a>setDropZone

    mixed HelperUploaderCore::setDropZone($value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 65](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L65)


#### Arguments
* $value **mixed**



### <a name="method-getDropZone"></a>getDropZone

    mixed HelperUploaderCore::getDropZone()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 71](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L71)




### <a name="method-setId"></a>setId

    mixed HelperUploaderCore::setId($value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 80](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L80)


#### Arguments
* $value **mixed**



### <a name="method-getId"></a>getId

    mixed HelperUploaderCore::getId()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 86](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L86)




### <a name="method-setFiles"></a>setFiles

    mixed HelperUploaderCore::setFiles($value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 95](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L95)


#### Arguments
* $value **mixed**



### <a name="method-getFiles"></a>getFiles

    mixed HelperUploaderCore::getFiles()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 101](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L101)




### <a name="method-setMaxFiles"></a>setMaxFiles

    mixed HelperUploaderCore::setMaxFiles($value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 110](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L110)


#### Arguments
* $value **mixed**



### <a name="method-getMaxFiles"></a>getMaxFiles

    mixed HelperUploaderCore::getMaxFiles()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L116)




### <a name="method-setMultiple"></a>setMultiple

    mixed HelperUploaderCore::setMultiple($value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 121](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L121)


#### Arguments
* $value **mixed**



### <a name="method-setName"></a>setName

    mixed HelperUploaderCore::setName($value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 127](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L127)


#### Arguments
* $value **mixed**



### <a name="method-getName"></a>getName

    mixed HelperUploaderCore::getName()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L133)




### <a name="method-setPostMaxSize"></a>setPostMaxSize

    mixed HelperUploaderCore::setPostMaxSize($value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 138](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L138)


#### Arguments
* $value **mixed**



### <a name="method-getPostMaxSize"></a>getPostMaxSize

    mixed HelperUploaderCore::getPostMaxSize()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 145](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L145)




### <a name="method-setTemplate"></a>setTemplate

    mixed HelperUploaderCore::setTemplate($value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 154](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L154)


#### Arguments
* $value **mixed**



### <a name="method-getTemplate"></a>getTemplate

    mixed HelperUploaderCore::getTemplate()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 160](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L160)




### <a name="method-setTemplateDirectory"></a>setTemplateDirectory

    mixed HelperUploaderCore::setTemplateDirectory($value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 169](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L169)


#### Arguments
* $value **mixed**



### <a name="method-getTemplateDirectory"></a>getTemplateDirectory

    mixed HelperUploaderCore::getTemplateDirectory()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 175](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L175)




### <a name="method-getTemplateFile"></a>getTemplateFile

    mixed HelperUploaderCore::getTemplateFile($template)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 184](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L184)


#### Arguments
* $template **mixed**



### <a name="method-setTitle"></a>setTitle

    mixed HelperUploaderCore::setTitle($value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 212](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L212)


#### Arguments
* $value **mixed**



### <a name="method-getTitle"></a>getTitle

    mixed HelperUploaderCore::getTitle()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 218](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L218)




### <a name="method-setUrl"></a>setUrl

    mixed HelperUploaderCore::setUrl($value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 223](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L223)


#### Arguments
* $value **mixed**



### <a name="method-getUrl"></a>getUrl

    mixed HelperUploaderCore::getUrl()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 229](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L229)




### <a name="method-setUseAjax"></a>setUseAjax

    mixed HelperUploaderCore::setUseAjax($value)





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 234](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L234)


#### Arguments
* $value **mixed**



### <a name="method-isMultiple"></a>isMultiple

    mixed HelperUploaderCore::isMultiple()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 240](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L240)




### <a name="method-render"></a>render

    mixed HelperUploaderCore::render()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 245](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L245)




### <a name="method-useAjax"></a>useAjax

    mixed HelperUploaderCore::useAjax()





* Visibility: **public**
* This method is defined in [classes/helper/HelperUploader.php line 291](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/helper/HelperUploader.php#L291)



