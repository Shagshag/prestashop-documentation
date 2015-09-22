CMSCore
===============






* Class name: CMSCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)

* This class is defined in [classes/CMS.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#27)





Properties
----------


### $meta_title

    public string $meta_title





* Visibility: **public**
* This property is defined in [classes/CMS.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#30)


### $meta_description

    public mixed $meta_description





* Visibility: **public**
* This property is defined in [classes/CMS.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#31)


### $meta_keywords

    public mixed $meta_keywords





* Visibility: **public**
* This property is defined in [classes/CMS.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#32)


### $content

    public mixed $content





* Visibility: **public**
* This property is defined in [classes/CMS.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#33)


### $link_rewrite

    public mixed $link_rewrite





* Visibility: **public**
* This property is defined in [classes/CMS.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#34)


### $id_cms_category

    public mixed $id_cms_category





* Visibility: **public**
* This property is defined in [classes/CMS.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#35)


### $position

    public mixed $position





* Visibility: **public**
* This property is defined in [classes/CMS.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#36)


### $indexation

    public mixed $indexation





* Visibility: **public**
* This property is defined in [classes/CMS.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#37)


### $active

    public mixed $active





* Visibility: **public**
* This property is defined in [classes/CMS.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#38)


### $definition

    public mixed $definition = array('table' => 'cms', 'primary' => 'id_cms', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_cms_category' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'position' => array('type' => self::TYPE_INT), 'indexation' => array('type' => self::TYPE_BOOL), 'active' => array('type' => self::TYPE_BOOL), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 128), 'content' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml', 'size' => 3999999999999.0)))





* Visibility: **public**
* This property is **static**.
* This property is defined in [classes/CMS.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#43)


### $webserviceParameters

    protected mixed $webserviceParameters = array('objectNodeName' => 'content', 'objectsNodeName' => 'content_management_system')





* Visibility: **protected**
* This property is defined in [classes/CMS.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#63)


Methods
-------


### add

    mixed CMSCore::add($autodate, $null_values)





* Visibility: **public**
* This method is defined in [classes/CMS.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#68)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### update

    mixed CMSCore::update($null_values)





* Visibility: **public**
* This method is defined in [classes/CMS.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#74)


#### Arguments
* $null_values **mixed**



### delete

    mixed CMSCore::delete()





* Visibility: **public**
* This method is defined in [classes/CMS.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#82)




### getLinks

    mixed CMSCore::getLinks($id_lang, $selection, $active, \Link $link)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMS.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#90)


#### Arguments
* $id_lang **mixed**
* $selection **mixed**
* $active **mixed**
* $link **[Link](LinkCore)**



### listCms

    mixed CMSCore::listCms($id_lang, $id_block, $active)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMS.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#116)


#### Arguments
* $id_lang **mixed**
* $id_block **mixed**
* $active **mixed**



### updatePosition

    mixed CMSCore::updatePosition($way, $position)





* Visibility: **public**
* This method is defined in [classes/CMS.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#133)


#### Arguments
* $way **mixed**
* $position **mixed**



### cleanPositions

    mixed CMSCore::cleanPositions($id_category)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMS.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#171)


#### Arguments
* $id_category **mixed**



### getLastPosition

    mixed CMSCore::getLastPosition($id_category)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMS.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#191)


#### Arguments
* $id_category **mixed**



### getCMSPages

    mixed CMSCore::getCMSPages($id_lang, $id_cms_category, $active, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMS.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#201)


#### Arguments
* $id_lang **mixed**
* $id_cms_category **mixed**
* $active **mixed**
* $id_shop **mixed**



### getUrlRewriteInformations

    mixed CMSCore::getUrlRewriteInformations($id_cms)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMS.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#232)


#### Arguments
* $id_cms **mixed**



### getCMSContent

    mixed CMSCore::getCMSContent($id_cms, $id_lang, $id_shop)





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMS.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#243)


#### Arguments
* $id_cms **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### getRepositoryClassName

    mixed CMSCore::getRepositoryClassName()





* Visibility: **public**
* This method is **static**.
* This method is defined in [classes/CMS.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#261)



