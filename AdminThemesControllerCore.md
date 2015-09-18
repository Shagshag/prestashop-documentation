AdminThemesControllerCore
===============






* Class name: AdminThemesControllerCore
* Namespace: 
* Parent class: AdminController



Constants
----------


### MAX_NAME_LENGTH

    const MAX_NAME_LENGTH = 128





Properties
----------


### $check_features_version

    public string $check_features_version = '1.4'

This value is used in isThemeCompatible method. only version node with an
higher version number will be used in [theme]/config.xml



* Visibility: **public**
* This property is **static**.


### $check_features

    public array $check_features = array('ccc' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_CSS_THEME_CACHE' => 0, 'PS_JS_THEME_CACHE' => 0, 'PS_HTML_THEME_COMPRESSION' => 0, 'PS_JS_HTML_THEME_COMPRESSION' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "combine, compress and cache" options.', 'tab' => 'AdminPerformance'), 'guest_checkout' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_GUEST_CHECKOUT_ENABLED' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "guest checkout" feature.', 'tab' => 'AdminPreferences'), 'one_page_checkout' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_ORDER_PROCESS_TYPE' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "one-page checkout" feature.', 'tab' => 'AdminPreferences'), 'store_locator' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_STORES_SIMPLIFIED' => 0, 'PS_STORES_DISPLAY_FOOTER' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "store locator" feature.', 'tab' => 'AdminStores'))

Multidimensional array used to check [theme]/config.xml values,
and also checks prestashop current configuration if not match.



* Visibility: **public**
* This property is **static**.


### $className

    public mixed $className = 'Theme'





* Visibility: **public**


### $table

    public mixed $table = 'theme'





* Visibility: **public**


### $toolbar_scroll

    protected mixed $toolbar_scroll = false





* Visibility: **protected**


### $img_error

    private mixed $img_error





* Visibility: **private**


### $object

    public \Theme $object





* Visibility: **public**


Methods
-------


### __construct

    mixed AdminThemesControllerCore::__construct()





* Visibility: **public**




### init

    mixed AdminThemesControllerCore::init()





* Visibility: **public**




### renderForm

    mixed AdminThemesControllerCore::renderForm()





* Visibility: **public**




### renderList

    mixed AdminThemesControllerCore::renderList()





* Visibility: **public**




### copyTheme

    boolean AdminThemesControllerCore::copyTheme(string $base_theme_dir, string $target_theme_dir)

copy $base_theme_dir into $target_theme_dir.



* Visibility: **protected**
* This method is **static**.


#### Arguments
* $base_theme_dir **string** - &lt;p&gt;relative path to base dir&lt;/p&gt;
* $target_theme_dir **string** - &lt;p&gt;relative path to target dir&lt;/p&gt;



### downloadAddonsThemes

    mixed AdminThemesControllerCore::downloadAddonsThemes()





* Visibility: **public**




### processAdd

    mixed AdminThemesControllerCore::processAdd()





* Visibility: **public**




### processUpdate

    mixed AdminThemesControllerCore::processUpdate()





* Visibility: **public**




### processUpdateOptions

    mixed AdminThemesControllerCore::processUpdateOptions()





* Visibility: **protected**




### processDelete

    mixed AdminThemesControllerCore::processDelete()





* Visibility: **public**




### initPageHeaderToolbar

    mixed AdminThemesControllerCore::initPageHeaderToolbar()





* Visibility: **public**




### checkParentClass

    mixed AdminThemesControllerCore::checkParentClass($name)





* Visibility: **private**


#### Arguments
* $name **mixed**



### checkNames

    mixed AdminThemesControllerCore::checkNames()





* Visibility: **private**




### checkDocumentation

    mixed AdminThemesControllerCore::checkDocumentation()





* Visibility: **private**




### checkVersionsAndCompatibility

    mixed AdminThemesControllerCore::checkVersionsAndCompatibility()





* Visibility: **private**




### checkPostedDatas

    mixed AdminThemesControllerCore::checkPostedDatas()





* Visibility: **private**




### archiveThisFile

    mixed AdminThemesControllerCore::archiveThisFile(\ZipArchive $obj, string $file, string $server_path, string $archive_path)





* Visibility: **private**


#### Arguments
* $obj **ZipArchive**
* $file **string**
* $server_path **string**
* $archive_path **string**



### generateArchive

    mixed AdminThemesControllerCore::generateArchive()





* Visibility: **private**




### generateXML

    mixed AdminThemesControllerCore::generateXML($theme_to_export, $metas)





* Visibility: **private**


#### Arguments
* $theme_to_export **mixed**
* $metas **mixed**



### processExportTheme

    mixed AdminThemesControllerCore::processExportTheme()





* Visibility: **public**




### renderExportTheme1

    mixed AdminThemesControllerCore::renderExportTheme1()





* Visibility: **private**




### renderExportTheme

    mixed AdminThemesControllerCore::renderExportTheme()





* Visibility: **public**




### checkXmlFields

    mixed AdminThemesControllerCore::checkXmlFields($xml_file)





* Visibility: **private**


#### Arguments
* $xml_file **mixed**



### recurseCopy

    mixed AdminThemesControllerCore::recurseCopy($src, $dst)





* Visibility: **private**


#### Arguments
* $src **mixed**
* $dst **mixed**



### processImportTheme

    mixed AdminThemesControllerCore::processImportTheme()





* Visibility: **public**




### extractTheme

    mixed AdminThemesControllerCore::extractTheme($theme_zip_file, $sandbox)





* Visibility: **protected**


#### Arguments
* $theme_zip_file **mixed**
* $sandbox **mixed**



### installTheme

    mixed AdminThemesControllerCore::installTheme($theme_dir, $sandbox, $redirect)





* Visibility: **protected**


#### Arguments
* $theme_dir **mixed**
* $sandbox **mixed**
* $redirect **mixed**



### isThemeInstalled

    mixed AdminThemesControllerCore::isThemeInstalled($theme_name)





* Visibility: **protected**


#### Arguments
* $theme_name **mixed**



### importThemeXmlConfig

    array|string AdminThemesControllerCore::importThemeXmlConfig(\SimpleXMLElement $xml, boolean $theme_dir)





* Visibility: **protected**


#### Arguments
* $xml **SimpleXMLElement**
* $theme_dir **boolean** - &lt;p&gt;only used if the theme directory to import is already located on the shop&lt;/p&gt;



### renderImportTheme

    mixed AdminThemesControllerCore::renderImportTheme()





* Visibility: **public**




### initContent

    mixed AdminThemesControllerCore::initContent()





* Visibility: **public**




### ajaxProcessGetAddonsThemes

    mixed AdminThemesControllerCore::ajaxProcessGetAddonsThemes()





* Visibility: **public**




### _isThemeCompatible

    boolean AdminThemesControllerCore::_isThemeCompatible(string $theme_dir)

This function checks if the theme designer has thunk to make his theme compatible 1.4,
and noticed it on the $theme_dir/config.xml file. If not, some new functionnalities has
to be desactivated



* Visibility: **protected**


#### Arguments
* $theme_dir **string** - &lt;p&gt;theme directory&lt;/p&gt;



### _checkConfigForFeatures

    boolean AdminThemesControllerCore::_checkConfigForFeatures(array $arrFeatures, mixed $configItem)

_checkConfigForFeatures



* Visibility: **protected**


#### Arguments
* $arrFeatures **array** - &lt;p&gt;array of feature code to check&lt;/p&gt;
* $configItem **mixed** - &lt;p&gt;will precise the attribute which not matches. If empty, will check every attributes&lt;/p&gt;



### getNativeModule

    array AdminThemesControllerCore::getNativeModule(integer $type)





* Visibility: **private**


#### Arguments
* $type **integer** - &lt;p&gt;$type = 0 both native &amp; partner (default)
$type = 1 native
$type = 2 partner&lt;/p&gt;



### getModules

    mixed AdminThemesControllerCore::getModules($xml)





* Visibility: **private**


#### Arguments
* $xml **mixed**



### formatHelperArray

    mixed AdminThemesControllerCore::formatHelperArray($origin_arr)





* Visibility: **private**


#### Arguments
* $origin_arr **mixed**



### formatHelperValuesArray

    mixed AdminThemesControllerCore::formatHelperValuesArray($originArr)





* Visibility: **private**


#### Arguments
* $originArr **mixed**



### renderChooseThemeModule

    mixed AdminThemesControllerCore::renderChooseThemeModule()





* Visibility: **public**




### updateImages

    mixed AdminThemesControllerCore::updateImages($xml)





* Visibility: **private**


#### Arguments
* $xml **mixed**



### hookModule

    mixed AdminThemesControllerCore::hookModule($id_module, $module_hooks, $shop)





* Visibility: **private**


#### Arguments
* $id_module **mixed**
* $module_hooks **mixed**
* $shop **mixed**



### processThemeInstall

    mixed AdminThemesControllerCore::processThemeInstall()





* Visibility: **public**




### renderView

    mixed AdminThemesControllerCore::renderView()





* Visibility: **public**




### postProcess

    mixed AdminThemesControllerCore::postProcess()

This functions make checks about AdminThemes configuration edition only.



* Visibility: **public**




### updateOptionPsLogo

    mixed AdminThemesControllerCore::updateOptionPsLogo()

Update PS_LOGO



* Visibility: **public**




### updateOptionPsLogoMobile

    mixed AdminThemesControllerCore::updateOptionPsLogoMobile()

Update PS_LOGO_MOBILE



* Visibility: **public**




### updateOptionPsLogoMail

    mixed AdminThemesControllerCore::updateOptionPsLogoMail()

Update PS_LOGO_MAIL



* Visibility: **public**




### updateOptionPsLogoInvoice

    mixed AdminThemesControllerCore::updateOptionPsLogoInvoice()

Update PS_LOGO_INVOICE



* Visibility: **public**




### updateOptionPsStoresIcon

    mixed AdminThemesControllerCore::updateOptionPsStoresIcon()

Update PS_STORES_ICON



* Visibility: **public**




### updateLogo

    boolean AdminThemesControllerCore::updateLogo($field_name, $logo_prefix)

Generic function which allows logo upload



* Visibility: **protected**


#### Arguments
* $field_name **mixed**
* $logo_prefix **mixed**



### updateOptionPsFavicon

    mixed AdminThemesControllerCore::updateOptionPsFavicon()

Update PS_FAVICON



* Visibility: **public**




### updateOptionThemeForShop

    mixed AdminThemesControllerCore::updateOptionThemeForShop()

Update theme for current shop



* Visibility: **public**




### uploadIco

    mixed AdminThemesControllerCore::uploadIco($name, $dest)





* Visibility: **protected**


#### Arguments
* $name **mixed**
* $dest **mixed**



### initProcess

    mixed AdminThemesControllerCore::initProcess()





* Visibility: **public**




### printResponsiveIcon

    mixed AdminThemesControllerCore::printResponsiveIcon($value)





* Visibility: **public**


#### Arguments
* $value **mixed**



### processResponsive

    mixed AdminThemesControllerCore::processResponsive()





* Visibility: **public**




### processDefaultLeftColumn

    mixed AdminThemesControllerCore::processDefaultLeftColumn()





* Visibility: **public**




### processDefaultRightColumn

    mixed AdminThemesControllerCore::processDefaultRightColumn()





* Visibility: **public**




### ajaxProcessLeftMeta

    mixed AdminThemesControllerCore::ajaxProcessLeftMeta()





* Visibility: **public**




### processLeftMeta

    mixed AdminThemesControllerCore::processLeftMeta()





* Visibility: **public**




### ajaxProcessRightMeta

    mixed AdminThemesControllerCore::ajaxProcessRightMeta()





* Visibility: **public**




### processRightMeta

    mixed AdminThemesControllerCore::processRightMeta()





* Visibility: **public**




### renderOptions

    mixed AdminThemesControllerCore::renderOptions()

Function used to render the options for this controller



* Visibility: **public**




### setMedia

    mixed AdminThemesControllerCore::setMedia()





* Visibility: **public**



