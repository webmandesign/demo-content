# What is this?

You are browsing a repository for main demo content XML files of [**Mustang** WordPress theme by WebMan](http://www.webmandesign.eu/mustang-wordpress-theme/).


## Before you begin

1. Install and active the [**Mustang** WordPress theme](http://www.webmandesign.eu/mustang-wordpress-theme/)
2. To allow all the demo content to be imported in whole, please install these plugins:
  * [WebMan Amplifier](https://wordpress.org/plugins/webman-amplifier/) - provides additional functionality, widgets, shortcodes, icon font and custom post types
  * [Beaver Builder](https://wordpress.org/plugins/beaver-builder-lite-version/) - page builder plugin used to build the demo content (make sure the page builder is enabled for Pages and Projects - check this under **Settings &raquo; Page Builder &raquo; Post Types**)
  * [WooCommerce](https://wordpress.org/plugins/woocommerce/) - provides e-commerce functionality
  * [bbPress](https://wordpress.org/plugins/bbpress/) - provides forum functionality
  * [WooSidebars](https://wordpress.org/plugins/woosidebars/) - allows to create custom sidebars
  * [Breadcrumb NavXT](https://wordpress.org/plugins/breadcrumb-navxt/) - provides breadcrumbs navigation

Also, please understand that **demo images (and other media files) will be imported in low quality** and you should replace them with your own (properly copyrighted) images.


## One-click installation

**Mustang** theme supports one-click demo content installation via your WordPress dashboard.

Once you have installed and activated demo content required plugins as listed above, refer to [theme documentation](https://www.webmandesign.eu/manual/mustang/#demo-content) for information on how to run the one-click demo installation process.

*You do not need to download and install the files from this repository in that case!*


## Installation process

*These instructions are meant for manual installation only:*

1. Download the `.xml` file to your computer (read below for "How to download the files?")
2. Install the demo content XML file according to [WordPress Codex instructions](http://codex.wordpress.org/Importing_Content#WordPress) (or [watch the video](https://webdesign.tutsplus.com/courses/a-beginners-guide-to-using-wordpress/lessons/wordpress-tools) on how to import WordPress XML files)
  > The original [**WordPress Importer** plugin](https://wordpress.org/plugins/wordpress-importer/) is pretty *outdated* and buggy. To eliminate the issues during theme demo content import I suggest using [a new version of the plugin](https://github.com/humanmade/WordPress-Importer). Although it is *still in development*, it is perfectly usable and you can [**download it** from its Github repository](https://github.com/humanmade/WordPress-Importer#how-do-i-use-it).
3. After the demo content is imported, set up your home and blog page under **Settings &raquo; Reading &raquo; "Front page displays"** (set "Front page" to "Homepage" and "Posts page" to "Blog")
4. Now we need to assign navigational menus in **Appearance &raquo; Menus &raquo; Manage Locations** as follows:
  * Set "Main" menu for "Main navigation" location
5. If you would like to set up widgets the way they are displayed on the [theme demo website](http://themedemos.webmandesign.eu/mustang/), use a procedure under [`widgets` subfolder](https://github.com/webmandesign/demo-content/tree/master/mustang/widgets)


## Important notes

*These instructions are meant for manual installation only:*

Please understand that due to how the WordPress works, the database IDs for imported content will differ from the actual IDs used on the theme demo website and thus you need to reset these to the correct values used in your website database (see the step 2 and 3 in "Installation process" above). This is normal in WordPress to prevent current existing content overwriting.


## How to download the files?

*These instructions are meant for manual installation only:*

*[Watch a video instructions.](https://vimeo.com/170576209)*

1. Click the file name to open the file content page
2. On top of the displayed file content you can see the **Raw** button. Right click the button with your mouse and select "Save link as..." from the options to download the actual file.
