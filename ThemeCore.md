ThemeCore
===============






* Class name: ThemeCore
* Namespace: 
* Parent class: [ObjectModel](ObjectModelCore)
* This class is defined in classes\Theme.php line 27



Constants
----------


### CACHE_FILE_CUSTOMER_THEMES_LIST

    const CACHE_FILE_CUSTOMER_THEMES_LIST = '/config/xml/customer_themes_list.xml'



* This constant is defined in classes\Theme.php line 36


### CACHE_FILE_MUST_HAVE_THEMES_LIST

    const CACHE_FILE_MUST_HAVE_THEMES_LIST = '/config/xml/must_have_themes_list.xml'



* This constant is defined in classes\Theme.php line 38


### UPLOADED_THEME_DIR_NAME

    const UPLOADED_THEME_DIR_NAME = 'uploaded'



* This constant is defined in classes\Theme.php line 40


Properties
----------


### $name

    public mixed $name





* Visibility: **public**
* This property is defined in classes\Theme.php line 29


### $directory

    public mixed $directory





* Visibility: **public**
* This property is defined in classes\Theme.php line 30


### $responsive

    public mixed $responsive





* Visibility: **public**
* This property is defined in classes\Theme.php line 31


### $default_left_column

    public mixed $default_left_column





* Visibility: **public**
* This property is defined in classes\Theme.php line 32


### $default_right_column

    public mixed $default_right_column





* Visibility: **public**
* This property is defined in classes\Theme.php line 33


### $product_per_page

    public mixed $product_per_page





* Visibility: **public**
* This property is defined in classes\Theme.php line 34


### $access_rights

    public integer $access_rights = 509





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Theme.php line 43


### $definition

    public mixed $definition = array('table' => 'theme', 'primary' => 'id_theme', 'fields' => array('name' => array('type' => self::TYPE_STRING, 'validate' => 'isGenericName', 'size' => 64, 'required' => true), 'directory' => array('type' => self::TYPE_STRING, 'validate' => 'isDirName', 'size' => 64, 'required' => true), 'responsive' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'default_left_column' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'default_right_column' => array('type' => self::TYPE_BOOL, 'validate' => 'isBool'), 'product_per_page' => array('type' => self::TYPE_INT, 'validate' => 'isInt')))





* Visibility: **public**
* This property is **static**.
* This property is defined in classes\Theme.php line 47


Methods
-------


### getThemes

    mixed ThemeCore::getThemes()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Theme.php line 60




### getAllThemes

    mixed ThemeCore::getAllThemes($excluded_ids)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Theme.php line 67


#### Arguments
* $excluded_ids **mixed**



### getAvailable

    array ThemeCore::getAvailable(boolean $installed_only)

return an array of all available theme (installed or not)



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Theme.php line 85


#### Arguments
* $installed_only **boolean**



### isUsed

    boolean ThemeCore::isUsed()

check if a theme is used by a shop



* Visibility: **public**
* This method is defined in classes\Theme.php line 123




### add

    boolean ThemeCore::add(boolean $autodate, boolean $null_values)

add only theme if the directory exists



* Visibility: **public**
* This method is defined in classes\Theme.php line 136


#### Arguments
* $autodate **boolean**
* $null_values **boolean**



### getByDirectory

    boolean|\Theme ThemeCore::getByDirectory(string $directory)

Checks if theme exists (by folder) and returns Theme object.



* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Theme.php line 152


#### Arguments
* $directory **string**



### getInstalledThemeDirectories

    mixed ThemeCore::getInstalledThemeDirectories()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Theme.php line 163




### getThemeInfo

    mixed ThemeCore::getThemeInfo($id_theme)





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Theme.php line 174


#### Arguments
* $id_theme **mixed**



### getNonInstalledTheme

    mixed ThemeCore::getNonInstalledTheme()





* Visibility: **public**
* This method is **static**.
* This method is defined in classes\Theme.php line 214




### updateMetas

    mixed ThemeCore::updateMetas(array $metas, boolean $full_update)

update the table PREFIX_theme_meta for the current theme



* Visibility: **public**
* This method is defined in classes\Theme.php line 244


#### Arguments
* $metas **array**
* $full_update **boolean** - &lt;p&gt;If true, all the meta of the theme will be deleted prior the insert, otherwise only the current $metas will be deleted&lt;/p&gt;



### hasColumns

    mixed ThemeCore::hasColumns($page)





* Visibility: **public**
* This method is defined in classes\Theme.php line 268


#### Arguments
* $page **mixed**



### hasColumnsSettings

    mixed ThemeCore::hasColumnsSettings($page)





* Visibility: **public**
* This method is defined in classes\Theme.php line 278


#### Arguments
* $page **mixed**



### hasLeftColumn

    mixed ThemeCore::hasLeftColumn($page)





* Visibility: **public**
* This method is defined in classes\Theme.php line 288


#### Arguments
* $page **mixed**



### hasRightColumn

    mixed ThemeCore::hasRightColumn($page)





* Visibility: **public**
* This method is defined in classes\Theme.php line 305


#### Arguments
* $page **mixed**



### getMetas

    array|boolean ThemeCore::getMetas()





* Visibility: **public**
* This method is defined in classes\Theme.php line 324




### removeMetas

    boolean ThemeCore::removeMetas()





* Visibility: **public**
* This method is defined in classes\Theme.php line 336




### toggleResponsive

    mixed ThemeCore::toggleResponsive()





* Visibility: **public**
* This method is defined in classes\Theme.php line 345




### toggleDefaultLeftColumn

    mixed ThemeCore::toggleDefaultLeftColumn()





* Visibility: **public**
* This method is defined in classes\Theme.php line 362




### toggleDefaultRightColumn

    mixed ThemeCore::toggleDefaultRightColumn()





* Visibility: **public**
* This method is defined in classes\Theme.php line 375



