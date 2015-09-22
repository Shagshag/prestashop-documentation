AdminThemesControllerCore
===============






* Class name: AdminThemesControllerCore
* Namespace: 
* Parent class: [AdminController](AdminControllerCore)
* This class is defined in controllers\admin\AdminThemesController.php line 30



Constants
----------


### MAX_NAME_LENGTH

    const MAX_NAME_LENGTH = 128



* This constant is defined in controllers\admin\AdminThemesController.php line 32


Properties
----------


### $check_features_version

    public string $check_features_version = '1.4'

This value is used in isThemeCompatible method. only version node with an
higher version number will be used in [theme]/config.xml



* Visibility: **public**
* This property is **static**.
* This property is defined in controllers\admin\AdminThemesController.php line 47


### $check_features

    public array $check_features = array('ccc' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_CSS_THEME_CACHE' => 0, 'PS_JS_THEME_CACHE' => 0, 'PS_HTML_THEME_COMPRESSION' => 0, 'PS_JS_HTML_THEME_COMPRESSION' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "combine, compress and cache" options.', 'tab' => 'AdminPerformance'), 'guest_checkout' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_GUEST_CHECKOUT_ENABLED' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "guest checkout" feature.', 'tab' => 'AdminPreferences'), 'one_page_checkout' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_ORDER_PROCESS_TYPE' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "one-page checkout" feature.', 'tab' => 'AdminPreferences'), 'store_locator' => array('attributes' => array('available' => array('value' => 'true', 'check_if_not_valid' => array('PS_STORES_SIMPLIFIED' => 0, 'PS_STORES_DISPLAY_FOOTER' => 0))), 'error' => 'This theme may not correctly use PrestaShop\'s "store locator" feature.', 'tab' => 'AdminStores'))

Multidimensional array used to check [theme]/config.xml values,
and also checks prestashop current configuration if not match.



* Visibility: **public**
* This property is **static**.
* This property is defined in controllers\admin\AdminThemesController.php line 55


### $className

    public mixed $className = 'Theme'





* Visibility: **public**
* This property is defined in controllers\admin\AdminThemesController.php line 109


### $table

    public mixed $table = 'theme'





* Visibility: **public**
* This property is defined in controllers\admin\AdminThemesController.php line 110


### $toolbar_scroll

    protected mixed $toolbar_scroll = false





* Visibility: **protected**
* This property is defined in controllers\admin\AdminThemesController.php line 111


### $img_error

    private mixed $img_error





* Visibility: **private**
* This property is defined in controllers\admin\AdminThemesController.php line 112


### $object

    public \Theme $object





* Visibility: **public**
* This property is defined in controllers\admin\AdminThemesController.php line 30


Methods
-------


### __construct

    mixed AdminThemesControllerCore::__construct()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 34




### init

    mixed AdminThemesControllerCore::init()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 114




### renderForm

    mixed AdminThemesControllerCore::renderForm()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 249




### renderList

    mixed AdminThemesControllerCore::renderList()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 469




### copyTheme

    boolean AdminThemesControllerCore::copyTheme(string $base_theme_dir, string $target_theme_dir)

copy $base_theme_dir into $target_theme_dir.



* Visibility: **protected**
* This method is **static**.
* This method is defined in controllers\admin\AdminThemesController.php line 482


#### Arguments
* $base_theme_dir **string** - &lt;p&gt;relative path to base dir&lt;/p&gt;
* $target_theme_dir **string** - &lt;p&gt;relative path to target dir&lt;/p&gt;



### downloadAddonsThemes

    mixed AdminThemesControllerCore::downloadAddonsThemes()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 508




### processAdd

    mixed AdminThemesControllerCore::processAdd()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 553




### processUpdate

    mixed AdminThemesControllerCore::processUpdate()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 613




### processUpdateOptions

    mixed AdminThemesControllerCore::processUpdateOptions()





* Visibility: **protected**
* This method is defined in controllers\admin\AdminThemesController.php line 647




### processDelete

    mixed AdminThemesControllerCore::processDelete()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 656




### initPageHeaderToolbar

    mixed AdminThemesControllerCore::initPageHeaderToolbar()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 696




### checkParentClass

    mixed AdminThemesControllerCore::checkParentClass($name)





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 730


#### Arguments
* $name **mixed**



### checkNames

    mixed AdminThemesControllerCore::checkNames()





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 754




### checkDocumentation

    mixed AdminThemesControllerCore::checkDocumentation()





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 772




### checkVersionsAndCompatibility

    mixed AdminThemesControllerCore::checkVersionsAndCompatibility()





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 801




### checkPostedDatas

    mixed AdminThemesControllerCore::checkPostedDatas()





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 819




### archiveThisFile

    mixed AdminThemesControllerCore::archiveThisFile(\ZipArchive $obj, string $file, string $server_path, string $archive_path)





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 843


#### Arguments
* $obj **ZipArchive**
* $file **string**
* $server_path **string**
* $archive_path **string**



### generateArchive

    mixed AdminThemesControllerCore::generateArchive()





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 857




### generateXML

    mixed AdminThemesControllerCore::generateXML($theme_to_export, $metas)





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 923


#### Arguments
* $theme_to_export **mixed**
* $metas **mixed**



### processExportTheme

    mixed AdminThemesControllerCore::processExportTheme()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 1024




### renderExportTheme1

    mixed AdminThemesControllerCore::renderExportTheme1()





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 1147




### renderExportTheme

    mixed AdminThemesControllerCore::renderExportTheme()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 1343




### checkXmlFields

    mixed AdminThemesControllerCore::checkXmlFields($xml_file)





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 1394


#### Arguments
* $xml_file **mixed**



### recurseCopy

    mixed AdminThemesControllerCore::recurseCopy($src, $dst)





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 1421


#### Arguments
* $src **mixed**
* $dst **mixed**



### processImportTheme

    mixed AdminThemesControllerCore::processImportTheme()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 1441




### extractTheme

    mixed AdminThemesControllerCore::extractTheme($theme_zip_file, $sandbox)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminThemesController.php line 1512


#### Arguments
* $theme_zip_file **mixed**
* $sandbox **mixed**



### installTheme

    mixed AdminThemesControllerCore::installTheme($theme_dir, $sandbox, $redirect)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminThemesController.php line 1522


#### Arguments
* $theme_dir **mixed**
* $sandbox **mixed**
* $redirect **mixed**



### isThemeInstalled

    mixed AdminThemesControllerCore::isThemeInstalled($theme_name)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminThemesController.php line 1577


#### Arguments
* $theme_name **mixed**



### importThemeXmlConfig

    array|string AdminThemesControllerCore::importThemeXmlConfig(\SimpleXMLElement $xml, boolean $theme_dir)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminThemesController.php line 1596


#### Arguments
* $xml **SimpleXMLElement**
* $theme_dir **boolean** - &lt;p&gt;only used if the theme directory to import is already located on the shop&lt;/p&gt;



### renderImportTheme

    mixed AdminThemesControllerCore::renderImportTheme()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 1694




### initContent

    mixed AdminThemesControllerCore::initContent()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 1815




### ajaxProcessGetAddonsThemes

    mixed AdminThemesControllerCore::ajaxProcessGetAddonsThemes()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 1851




### _isThemeCompatible

    boolean AdminThemesControllerCore::_isThemeCompatible(string $theme_dir)

This function checks if the theme designer has thunk to make his theme compatible 1.4,
and noticed it on the $theme_dir/config.xml file. If not, some new functionnalities has
to be desactivated



* Visibility: **protected**
* This method is defined in controllers\admin\AdminThemesController.php line 1874


#### Arguments
* $theme_dir **string** - &lt;p&gt;theme directory&lt;/p&gt;



### _checkConfigForFeatures

    boolean AdminThemesControllerCore::_checkConfigForFeatures(array $arrFeatures, mixed $configItem)

_checkConfigForFeatures



* Visibility: **protected**
* This method is defined in controllers\admin\AdminThemesController.php line 1925


#### Arguments
* $arrFeatures **array** - &lt;p&gt;array of feature code to check&lt;/p&gt;
* $configItem **mixed** - &lt;p&gt;will precise the attribute which not matches. If empty, will check every attributes&lt;/p&gt;



### getNativeModule

    array AdminThemesControllerCore::getNativeModule(integer $type)





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 1980


#### Arguments
* $type **integer** - &lt;p&gt;$type = 0 both native &amp; partner (default)
$type = 1 native
$type = 2 partner&lt;/p&gt;



### getModules

    mixed AdminThemesControllerCore::getModules($xml)





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 2118


#### Arguments
* $xml **mixed**



### formatHelperArray

    mixed AdminThemesControllerCore::formatHelperArray($origin_arr)





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 2139


#### Arguments
* $origin_arr **mixed**



### formatHelperValuesArray

    mixed AdminThemesControllerCore::formatHelperValuesArray($originArr)





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 2160


#### Arguments
* $originArr **mixed**



### renderChooseThemeModule

    mixed AdminThemesControllerCore::renderChooseThemeModule()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2172




### updateImages

    mixed AdminThemesControllerCore::updateImages($xml)





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 2377


#### Arguments
* $xml **mixed**



### hookModule

    mixed AdminThemesControllerCore::hookModule($id_module, $module_hooks, $shop)





* Visibility: **private**
* This method is defined in controllers\admin\AdminThemesController.php line 2406


#### Arguments
* $id_module **mixed**
* $module_hooks **mixed**
* $shop **mixed**



### processThemeInstall

    mixed AdminThemesControllerCore::processThemeInstall()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2428




### renderView

    mixed AdminThemesControllerCore::renderView()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2560




### postProcess

    mixed AdminThemesControllerCore::postProcess()

This functions make checks about AdminThemes configuration edition only.



* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2579




### updateOptionPsLogo

    mixed AdminThemesControllerCore::updateOptionPsLogo()

Update PS_LOGO



* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2603




### updateOptionPsLogoMobile

    mixed AdminThemesControllerCore::updateOptionPsLogoMobile()

Update PS_LOGO_MOBILE



* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2611




### updateOptionPsLogoMail

    mixed AdminThemesControllerCore::updateOptionPsLogoMail()

Update PS_LOGO_MAIL



* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2619




### updateOptionPsLogoInvoice

    mixed AdminThemesControllerCore::updateOptionPsLogoInvoice()

Update PS_LOGO_INVOICE



* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2627




### updateOptionPsStoresIcon

    mixed AdminThemesControllerCore::updateOptionPsStoresIcon()

Update PS_STORES_ICON



* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2635




### updateLogo

    boolean AdminThemesControllerCore::updateLogo($field_name, $logo_prefix)

Generic function which allows logo upload



* Visibility: **protected**
* This method is defined in controllers\admin\AdminThemesController.php line 2648


#### Arguments
* $field_name **mixed**
* $logo_prefix **mixed**



### updateOptionPsFavicon

    mixed AdminThemesControllerCore::updateOptionPsFavicon()

Update PS_FAVICON



* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2719




### updateOptionThemeForShop

    mixed AdminThemesControllerCore::updateOptionThemeForShop()

Update theme for current shop



* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2736




### uploadIco

    mixed AdminThemesControllerCore::uploadIco($name, $dest)





* Visibility: **protected**
* This method is defined in controllers\admin\AdminThemesController.php line 2750


#### Arguments
* $name **mixed**
* $dest **mixed**



### initProcess

    mixed AdminThemesControllerCore::initProcess()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2765




### printResponsiveIcon

    mixed AdminThemesControllerCore::printResponsiveIcon($value)





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2806


#### Arguments
* $value **mixed**



### processResponsive

    mixed AdminThemesControllerCore::processResponsive()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2811




### processDefaultLeftColumn

    mixed AdminThemesControllerCore::processDefaultLeftColumn()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2829




### processDefaultRightColumn

    mixed AdminThemesControllerCore::processDefaultRightColumn()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2847




### ajaxProcessLeftMeta

    mixed AdminThemesControllerCore::ajaxProcessLeftMeta()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2865




### processLeftMeta

    mixed AdminThemesControllerCore::processLeftMeta()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2884




### ajaxProcessRightMeta

    mixed AdminThemesControllerCore::ajaxProcessRightMeta()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2903




### processRightMeta

    mixed AdminThemesControllerCore::processRightMeta()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2922




### renderOptions

    mixed AdminThemesControllerCore::renderOptions()

Function used to render the options for this controller



* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2945




### setMedia

    mixed AdminThemesControllerCore::setMedia()





* Visibility: **public**
* This method is defined in controllers\admin\AdminThemesController.php line 2969



