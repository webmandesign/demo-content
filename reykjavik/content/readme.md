# What is this?

You are browsing a repository for main demo content XML files of [**Reykjavik** WordPress theme by WebManDesign.eu](https://www.webmandesign.eu/portfolio/reykjavik-wordpress-theme/).


## Before you begin

1. Install and active the [**Reykjavik** WordPress theme](https://www.webmandesign.eu/portfolio/reykjavik-wordpress-theme/).
2. **Required plugins**: To allow all the demo content to be imported in whole, please install these plugins (they are required for [one-click demo content installation](#one-click-installation) too):
    * [**Jetpack**](https://wordpress.org/plugins/webman-amplifier/) - provides additional Portfolio and Testimonials custom post types (please do not forget to [enable these post types in plugin settings](https://jetpack.com/support/custom-content-types/)), and other cool features such as [tiled galleries](https://jetpack.me/support/tiled-galleries/), ([how to install Jetpack?](https://jetpack.com/support/installing-jetpack/)),
    * [**WooCommerce**](https://wordpress.org/plugins/woocommerce/) - provides e-commerce functionality,
    * [**Beaver Builder**](https://wordpress.org/plugins/beaver-builder-lite-version/) - page builder plugin used to build some of demo pages (make sure the page builder is enabled for Pages and Products post types - check this under **Settings &raquo; Page Builder &raquo; Post Types**),
    * [**WooSidebars**](https://wordpress.org/plugins/woosidebars/) - provides custom sidebars and widget areas functionality, allows you to disable sidebar on any page.
3. **Optional plugins**: If you want to match your website exactly to [the theme demo website](http://themedemos.webmandesign.eu/reykjavik/), please install also these plugins: 
    * [*Subtitles*](https://wordpress.org/plugins/subtitles/) - to display page/post subtitles used in the demo content,
    * [*Widget CSS Classes*](https://wordpress.org/plugins/widget-css-classes/) - allows applying layout CSS classes on theme demo [widgets](https://github.com/webmandesign/demo-content/tree/master/reykjavik/widgets),
    * [*Breadcrumbs NavXT*](https://wordpress.org/plugins/breadcrumb-navxt/) - for adding a perfect, SEO friendly [breadcrumbs navigation](http://en.wikipedia.org/wiki/Breadcrumb_%28navigation%29) (see [theme documentation](https://www.webmandesign.eu/manual/reykjavik/#breadcrumbs) for custom plugin setup),
    * [*Advanced Custom Fields*](https://wordpress.org/plugins/advanced-custom-fields/) - for easy [page/post attributes editing](https://www.webmandesign.eu/manual/reykjavik/#custom-fields),
    * ...and you can use any other plugin you want. See [theme documentation](https://www.webmandesign.eu/manual/reykjavik/#plugins-others) for information on some additional, tested and recommended plugins.

Also, please understand that **demo images (and other media files) will be imported in low quality** and you should replace them with your own (properly copyrighted) images.


## One-click installation

**Reykjavik** theme supports one-click demo content installation via your WordPress dashboard.

Once you have installed and activated demo content required plugins as listed above, refer to [theme documentation](https://www.webmandesign.eu/manual/reykjavik/#demo-content) for information on how to run the one-click demo installation process.

*You do not need to download and install the files from this repository in that case!*


## Installation process

*These instructions are meant for manual installation only:*

1. Download the `.xml` file to your computer (read below for "How to download the files?")
2. Install the demo content XML file according to [WordPress Codex instructions](http://codex.wordpress.org/Importing_Content#WordPress) (or [watch the video](https://webdesign.tutsplus.com/courses/a-beginners-guide-to-using-wordpress/lessons/wordpress-tools) on how to import WordPress XML files)
    > The original [**WordPress Importer** plugin](https://wordpress.org/plugins/wordpress-importer/) is pretty *outdated* and buggy. To eliminate the issues during theme demo content import I suggest using [a new version of the plugin](https://github.com/humanmade/WordPress-Importer). Although it is *still in development*, it is perfectly usable and you can [**download it** from its Github repository](https://github.com/humanmade/WordPress-Importer#how-do-i-use-it).
3. After the demo content is imported, set up your home and blog page under **Settings &raquo; Reading &raquo; "Front page displays" &raquo;** *"A static page (select below)"*:
    * Set "Front page" to "Hello from Reykjavík" page
    * Set "Posts page" to "Blog" page
4. Now we need to assign navigational menus in **Appearance &raquo; Menus &raquo; Manage Locations** as follows:
    * Set "Primary" menu for "Primary" location
    * Set "Secondary" menu for "Secondary" location
    * Set "Social links" menu for "Social Links" location
5. If you would like to set up widgets the way they are displayed on the [theme demo website](http://themedemos.webmandesign.eu/reykjavik/), use a procedure under [`widgets` subfolder](https://github.com/webmandesign/demo-content/tree/master/reykjavik/widgets)


## Important notes

*These instructions are meant for manual installation only:*

Please understand that due to how the WordPress works, the database IDs for imported content will differ from the actual IDs used on the theme demo website and thus you need to reset these to the correct values used in your website database (see the step 3 and 4 in "Installation process" above). This is normal in WordPress to prevent current existing content overwriting.


## How to download the files?

*These instructions are meant for manual installation only:*

*[Watch the video instructions.](https://vimeo.com/170576209)*

1. Click the file name to open the file content page
2. On top of the displayed file content you can see the **Raw** button. Right click the button with your mouse and select "Save link as..." from the options to download the actual file.
