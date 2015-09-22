Class CMSCore
=====================





* Class name: CMSCore
* Parent class: [ObjectModel](class.ObjectModelCore.md)
* Source: [classes/CMS.php line 27](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L27)



Properties
----------

* [$active](#property-$active)
* [$content](#property-$content)
* [$definition](#property-$definition)
* [$id_cms_category](#property-$id_cms_category)
* [$indexation](#property-$indexation)
* [$link_rewrite](#property-$link_rewrite)
* [$meta_description](#property-$meta_description)
* [$meta_keywords](#property-$meta_keywords)
* [$meta_title](#property-$meta_title)
* [$position](#property-$position)
* [$webserviceParameters](#property-$webserviceParameters)

Methods
-------
* [add](#method-add)
* [cleanPositions](#method-cleanPositions)
* [delete](#method-delete)
* [getCMSContent](#method-getCMSContent)
* [getCMSPages](#method-getCMSPages)
* [getLastPosition](#method-getLastPosition)
* [getLinks](#method-getLinks)
* [getRepositoryClassName](#method-getRepositoryClassName)
* [getUrlRewriteInformations](#method-getUrlRewriteInformations)
* [listCms](#method-listCms)
* [update](#method-update)
* [updatePosition](#method-updatePosition)




Properties
----------


### <a name="property-$active"></a>$active

    public mixed $active





* Visibility: **public**
* Source: [classes/CMS.php line 38](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L38).


### <a name="property-$content"></a>$content

    public mixed $content





* Visibility: **public**
* Source: [classes/CMS.php line 33](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L33).


### <a name="property-$definition"></a>$definition

    public mixed $definition = array('table' => 'cms', 'primary' => 'id_cms', 'multilang' => true, 'multilang_shop' => true, 'fields' => array('id_cms_category' => array('type' => self::TYPE_INT, 'validate' => 'isUnsignedInt'), 'position' => array('type' => self::TYPE_INT), 'indexation' => array('type' => self::TYPE_BOOL), 'active' => array('type' => self::TYPE_BOOL), 'meta_description' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_keywords' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'size' => 255), 'meta_title' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isGenericName', 'required' => true, 'size' => 128), 'link_rewrite' => array('type' => self::TYPE_STRING, 'lang' => true, 'validate' => 'isLinkRewrite', 'required' => true, 'size' => 128), 'content' => array('type' => self::TYPE_HTML, 'lang' => true, 'validate' => 'isCleanHtml', 'size' => 3999999999999.0)))





* Visibility: **public**
* This property is **static**.
* Source: [classes/CMS.php line 43](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L43).


### <a name="property-$id_cms_category"></a>$id_cms_category

    public mixed $id_cms_category





* Visibility: **public**
* Source: [classes/CMS.php line 35](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L35).


### <a name="property-$indexation"></a>$indexation

    public mixed $indexation





* Visibility: **public**
* Source: [classes/CMS.php line 37](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L37).


### <a name="property-$link_rewrite"></a>$link_rewrite

    public mixed $link_rewrite





* Visibility: **public**
* Source: [classes/CMS.php line 34](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L34).


### <a name="property-$meta_description"></a>$meta_description

    public mixed $meta_description





* Visibility: **public**
* Source: [classes/CMS.php line 31](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L31).


### <a name="property-$meta_keywords"></a>$meta_keywords

    public mixed $meta_keywords





* Visibility: **public**
* Source: [classes/CMS.php line 32](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L32).


### <a name="property-$meta_title"></a>$meta_title

    public string $meta_title





* Visibility: **public**
* Source: [classes/CMS.php line 30](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L30).


### <a name="property-$position"></a>$position

    public mixed $position





* Visibility: **public**
* Source: [classes/CMS.php line 36](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L36).


### <a name="property-$webserviceParameters"></a>$webserviceParameters

    protected mixed $webserviceParameters = array('objectNodeName' => 'content', 'objectsNodeName' => 'content_management_system')





* Visibility: **protected**
* Source: [classes/CMS.php line 63](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L63).


Methods
-------


### <a name="method-add"></a>add

    mixed CMSCore::add($autodate, $null_values)





* Visibility: **public**
* Source: [classes/CMS.php line 68](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L68)


#### Arguments
* $autodate **mixed**
* $null_values **mixed**



### <a name="method-cleanPositions"></a>cleanPositions

    mixed CMSCore::cleanPositions($id_category)





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 171](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L171)


#### Arguments
* $id_category **mixed**



### <a name="method-delete"></a>delete

    mixed CMSCore::delete()





* Visibility: **public**
* Source: [classes/CMS.php line 82](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L82)




### <a name="method-getCMSContent"></a>getCMSContent

    mixed CMSCore::getCMSContent($id_cms, $id_lang, $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 243](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L243)


#### Arguments
* $id_cms **mixed**
* $id_lang **mixed**
* $id_shop **mixed**



### <a name="method-getCMSPages"></a>getCMSPages

    mixed CMSCore::getCMSPages($id_lang, $id_cms_category, $active, $id_shop)





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 201](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L201)


#### Arguments
* $id_lang **mixed**
* $id_cms_category **mixed**
* $active **mixed**
* $id_shop **mixed**



### <a name="method-getLastPosition"></a>getLastPosition

    mixed CMSCore::getLastPosition($id_category)





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 191](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L191)


#### Arguments
* $id_category **mixed**



### <a name="method-getLinks"></a>getLinks

    mixed CMSCore::getLinks($id_lang, $selection, $active, \Link $link)





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 90](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L90)


#### Arguments
* $id_lang **mixed**
* $selection **mixed**
* $active **mixed**
* $link **[Link](class.LinkCore.md)**



### <a name="method-getRepositoryClassName"></a>getRepositoryClassName

    mixed CMSCore::getRepositoryClassName()





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 261](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L261)




### <a name="method-getUrlRewriteInformations"></a>getUrlRewriteInformations

    mixed CMSCore::getUrlRewriteInformations($id_cms)





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 232](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L232)


#### Arguments
* $id_cms **mixed**



### <a name="method-listCms"></a>listCms

    mixed CMSCore::listCms($id_lang, $id_block, $active)





* Visibility: **public**
* This method is **static**.
* Source: [classes/CMS.php line 116](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L116)


#### Arguments
* $id_lang **mixed**
* $id_block **mixed**
* $active **mixed**



### <a name="method-update"></a>update

    mixed CMSCore::update($null_values)





* Visibility: **public**
* Source: [classes/CMS.php line 74](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L74)


#### Arguments
* $null_values **mixed**



### <a name="method-updatePosition"></a>updatePosition

    mixed CMSCore::updatePosition($way, $position)





* Visibility: **public**
* Source: [classes/CMS.php line 133](https://github.com/PrestaShop/PrestaShop/blob/1.6.1.1/classes/CMS.php#L133)


#### Arguments
* $way **mixed**
* $position **mixed**


