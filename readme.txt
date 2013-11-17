=== Genesis Taxonomy Images ===

Version: 0.8.1
Author: Ade Walker
Author page: http://www.studiograsshopper.ch
Plugin page: http://www.studiograsshopper.ch/genesis-taxonomy-images/
Donate link: http://www.studiograsshopper.ch/genesis-taxonomy-images/
Contributors: studiograsshopper
Tags: genesis, genesiswp, studiopress, taxonomy images, image
Requires at least: 3.6
Tested up to: 3.7.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Stable tag: 0.8.1

Create and manage Taxonomy Images for the Genesis theme framework.


== Description ==

Enables you to upload and display an image for your taxonomy terms, eg Categories, Tags, or any custom taxonomy term that you may use. The plugin uses the Genesis Term Meta functionality to manage and display your image, for example in the archive description area of your archive pages.

Note: this plugin is designed for use with the Genesis theme framework and a Genesis Child Theme. If you're not using Genesis, this plugin won't work for you.



== Installation ==

Either use the WordPress Plugin Installer (Dashboard > Plugins > Add New, then search for "genesis taxonomy images"), or manually as follows:

1. Upload the entire `genesis-taxonomy-images` folder to the `/wp-content/plugins/` directory
2. DO NOT change the name of the `genesis-taxonomy-images` folder
3. Activate the plugin through the 'Plugins' menu in the WordPress Dashboard

Note: You must be using a Genesis child theme with Genesis 2.0+ installed before installing and activating this plugin.

Note for WordPress Multisite users:

* Install the plugin in your */plugins/* directory (do not install in the */mu-plugins/* directory).
* In order for this plugin to be visible to Site Admins, the plugin has to be activated for each blog by the Network Admin.

**Upgrading from a previous version**
-------------------------------------

You can use the Wordpress Automatic Plugin upgrade link in the Dashboard Plugins menu to automatically upgrade the plugin.



== Frequently Asked Questions ==

= Where can I get Support? =

Further information about setting up and using the plugin can be found in the plugin's [User Guide](http://www.studiograsshopper.ch/genesis-taxonomy-images/user-guide/).

If, having read the information linked to above, you cannot solve your issue, or if you find a bug, you can post a message on the plugin's [Support Forum](http://wordpress.org/support/plugin/genesis-taxonomy-images).

Support is provided in my free time but every effort will be made to respond to support queries as quickly as possible.


= Can I Donate? =

Yes, of course you can! You can find a link [here](http://www.studiograsshopper.ch/genesis-taxonomy-images/). Thanks!


= Where is the Settings page? =

There is no need for a Settings page. Images are uploaded/added via the Dashboard Edit screen for the taxonomy term in question.


= How do I display these images in my theme? =

You need to add some code to your Genesis Child Theme's `functions.php` file. Code examples can be found in the plugin's [User Guide](http://www.studiograsshopper.ch/genesis-taxonomy-images/user-guide/).


= License and Disclaimer =

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License 2 as published by
the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

The license for this software can be found here: [http://www.gnu.org/licenses/gpl-2.0.html](http://www.gnu.org/licenses/gpl-2.0.html)

Thanks for downloading the plugin.



== Other Notes ==

In order to use this plugin your current theme must be a Genesis Child Theme.



== Screenshots ==
1. Taxonomy Admin screen
2. Term edit screen
3. Sample display on Archive page



== Changelog ==

= 0.8.1 =
* Released 17 November 2013
* Enhance: Added gtaxi_get_taxonomies() function
* Bug fix: Added low priority of 999 to init hook to ensure that taxonomies are already registered
* Bug fix: Fixed issue of wp_enqueue_media script not loading on custom taxonomy term edit screens

= 0.8.0 =
* Initial Release 28 October 2013