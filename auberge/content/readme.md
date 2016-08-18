# What is this?

You are browsing a repository for main demo content XML files of [**Auberge** WordPress theme by WebMan](http://www.webmandesign.eu/auberge-wordpress-theme/).


## Before you begin

1. Install and active the [**Auberge** WordPress theme](http://www.webmandesign.eu/auberge-wordpress-theme/)
2. To allow all the demo content to be imported in whole, please install these plugins:
  * [WebMan Amplifier](https://wordpress.org/plugins/webman-amplifier/) - provides recipes functionality, **works only with [paid **Auberge Plus** theme version](https://www.webmandesign.eu/auberge-wordpress-theme/#donate)**
  * [Beaver Builder](https://wordpress.org/plugins/beaver-builder-lite-version/) - page builder plugin used to build the demo content
  * [Jetpack](https://wordpress.org/plugins/jetpack/) - demo content includes [tiled galleries](https://jetpack.me/support/tiled-galleries/) which are feature of this plugin, also there is a contact form displayed on the "Contact" page - please enable these modules in your website Jetpack settings dashboard
  * [Restaurant Reservations](https://wordpress.org/plugins/restaurant-reservations/) - the reservation form displayed on "Reservations" page is provided with this plugin

Also, please understand that **demo images (and other media files) will be imported in low quality** and you should replace them with your own (properly copyrighted) images.


## One-click installation

**Auberge** theme supports one-click demo content installation via your WordPress dashboard.

It will import all the demo widgets automatically. For more info on one-click demo installation please read [theme documentation](https://www.webmandesign.eu/manual/auberge/#demo-content).

*You do not need to download and install the files from this repository in that case!*


## Installation process

*These instructions are meant for manual installation only:*

1. Download the `.xml` file to your computer (read below for "How to download the files?")
2. Install the demo content XML file according to [WordPress Codex instructions](http://codex.wordpress.org/Importing_Content#WordPress) (or [watch the video](https://webdesign.tutsplus.com/courses/a-beginners-guide-to-using-wordpress/lessons/wordpress-tools) on how to import WordPress XML files)
	> The original [**WordPress Importer** plugin](https://wordpress.org/plugins/wordpress-importer/) is pretty *outdated* and buggy. To eliminate the issues during theme demo content import I suggest using [a new version of the plugin](https://github.com/humanmade/WordPress-Importer). Although it is *still in development*, it is perfectly usable and you can [**download it** from its Github repository](https://github.com/humanmade/WordPress-Importer#how-do-i-use-it).
3. After the demo content is imported, set up your home and blog page under **Settings &raquo; Reading &raquo; "Front page displays"** (set "Front page" to "Homepage" and "Posts page" to "Blog")
4. Now we need to assign navigational menus in **Appearance &raquo; Menus &raquo; Manage Locations** as follows:
  * Set "Main navigation" menu for "Primary Menu" location
  * Set "Social links" menu for "Social Links Menu" location
5. If you would like to set up widgets the way they are displayed on the [theme demo website](http://themedemos.webmandesign.eu/auberge/), use a procedure under [`widgets` subfolder](https://github.com/webmandesign/demo-content/tree/master/auberge/widgets)

> **Failed import messages**: Please note that if you are using [free version of the Auberge theme](http://wordpress.org/themes/auberge), you will encounter failed import messages (such as failed to import ingredients). These are related to content available in [paid version of the theme](https://www.webmandesign.eu/auberge-wordpress-theme/#donate) **only**, that's why the import procedure fails when using the free theme. This is no issue at all and the rest of the demo content will get imported despite these fails.


## Important notes

Please understand that due to how the WordPress works, the database IDs for imported content will differ from the actual IDs used on the theme demo website and thus you need to reset these to the correct values used in your website database (see the step 2 and 3 in "Installation process" above). This is normal in WordPress to prevent current existing content overwriting.

Also, please understand that demo images (and other media files) are of low quality and you should replace them with your own (properly copyrighted) images.


## How to download the files?

*[Watch a video instructions.](https://vimeo.com/170576209)*

1. Click the file name to open the file content page
2. On top of the displayed file content you can see the **Raw** button. Right click the button with your mouse and select "Save link as..." from the options to download the actual file.
