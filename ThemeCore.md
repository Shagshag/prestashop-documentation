ThemeCore
===============






* Class name: ThemeCore
* Namespace: 
* Parent class: ObjectModel



Constants
----------


### CACHE_FILE_CUSTOMER_THEMES_LIST

    const CACHE_FILE_CUSTOMER_THEMES_LIST = '/config/xml/customer_themes_list.xml'





### CACHE_FILE_MUST_HAVE_THEMES_LIST

    const CACHE_FILE_MUST_HAVE_THEMES_LIST = '/config/xml/must_have_themes_list.xml'





### UPLOADED_THEME_DIR_NAME

    const UPLOADED_THEME_DIR_NAME = 'uploaded'





Properties
----------


### $name

    public mixed $name





* Visibility: **public**


### $directory

    public mixed $directory





* Visibility: **public**


### $responsive

    public mixed $responsive





* Visibility: **public**


### $default_left_column

    public mixed $default_left_column





* Visibility: **public**


### $default_right_column

    public mixed $default_right_column





* Visibility: **public**


### $product_per_page

    public mixed $product_per_page





* Visibility: **public**


### $access_rights

    public integer $access_rights = 509





* Visibility: **public**
* This property is **static**.


### $definition

    public mixed $definition = array('table' => 'theme', 'primary' => 'id_theme', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 64, 'required' => true), 'directory' => array('type' => self::TYPE_STRING, 'validate' => 'isDirName', 'size' => 64, 'required' => true), 'responsive' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'default_left_column' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'default_right_column' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'product_per_page' => array('type' => self::TYPE_INT, 'validate' => 'isInt')))





* Visibility: **public**
* This property is **static**.


Methods
-------


### getThemes

    mixed ThemeCore::getThemes()





* Visibility: **public**
* This method is **static**.




### getAllThemes

    mixed ThemeCore::getAllThemes($excluded_ids)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $excluded_ids **mixed**



### getAvailable

    array ThemeCore::getAvailable(boolean $installed_only)

return an array of all available theme (installed or not)



* Visibility: **public**
* This method is **static**.


#### Arguments
* $installed_only **boolean**



### isUsed

    boolean ThemeCore::isUsed()

check if a theme is used by a shop



* Visibility: **public**




### add

    boolean ThemeCore::add(boolean $autodate, boolean $null_values)

add only theme if the directory exists



* Visibility: **public**


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### getByDirectory

    boolean|\Theme ThemeCore::getByDirectory(string $directory)

Checks if theme exists (by folder) and returns Theme object.



* Visibility: **public**
* This method is **static**.


#### Arguments
* $directory **string**



### getInstalledThemeDirectories

    mixed ThemeCore::getInstalledThemeDirectories()





* Visibility: **public**
* This method is **static**.




### getThemeInfo

    mixed ThemeCore::getThemeInfo($id_theme)





* Visibility: **public**
* This method is **static**.


#### Arguments
* $id_theme **mixed**



### getNonInstalledTheme

    mixed ThemeCore::getNonInstalledTheme()





* Visibility: **public**
* This method is **static**.




### updateMetas

    mixed ThemeCore::updateMetas(array $metas, boolean $full_update)

update the table PREFIX_theme_meta for the current theme



* Visibility: **public**


#### Arguments
* $metas **array**
* $full_update **boolean** - &lt;p&gt;If true, all the meta of the theme will be deleted prior the insert, otherwise only the current $metas will be deleted&lt;/p&gt;



### hasColumns

    mixed ThemeCore::hasColumns($page)





* Visibility: **public**


#### Arguments
* $page **mixed**



### hasColumnsSettings

    mixed ThemeCore::hasColumnsSettings($page)





* Visibility: **public**


#### Arguments
* $page **mixed**



### hasLeftColumn

    mixed ThemeCore::hasLeftColumn($page)





* Visibility: **public**


#### Arguments
* $page **mixed**



### hasRightColumn

    mixed ThemeCore::hasRightColumn($page)





* Visibility: **public**


#### Arguments
* $page **mixed**



### getMetas

    array|boolean ThemeCore::getMetas()





* Visibility: **public**




### removeMetas

    boolean ThemeCore::removeMetas()





* Visibility: **public**




### toggleResponsive

    mixed ThemeCore::toggleResponsive()





* Visibility: **public**




### toggleDefaultLeftColumn

    mixed ThemeCore::toggleDefaultLeftColumn()





* Visibility: **public**




### toggleDefaultRightColumn

    mixed ThemeCore::toggleDefaultRightColumn()





* Visibility: **public**



