=== Genesis Taxonomy Images ===
Version: 1.0.0
Plugin page: http://www.studiograsshopper.ch/genesis-taxonomy-images/
Donate link: http://www.studiograsshopper.ch/genesis-taxonomy-images/
Contributors: studiograsshopper, themiked
Tags: genesis, genesiswp, studiopress, taxonomy images, image
Requires at least: 3.6
Tested up to: 4.2.4
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html
Stable tag: 0.8.1

Create and manage taxonomy images for the Genesis theme framework.


== Description ==

Once activated, this plugin enables you to upload and display an image for your taxonomy terms. Think of it as featured images for terms. It works with categories, tags, and custom taxonomies.

The plugin uses the Genesis term meta functionality to manage and display the term image.

Note: this plugin is designed for use with the Genesis theme framework version 2 or greater, and will not work without it.



== Installation ==

Either use the WordPress Plugin Installer (Dashboard > Plugins > Add New, then search for "genesis taxonomy images"), or manually as follows:

1. Upload the entire `genesis-taxonomy-images` folder to the `/wp-content/plugins/` directory
1. DO NOT change the name of the `genesis-taxonomy-images` folder
1. Activate the plugin through the 'Plugins' menu in the WordPress Dashboard

You can now add images to any taxonomy by visiting the taxonomy admin page.

Note: You must be using a Genesis child theme with Genesis version 2 or greater or the plugin will not activate.

Note for WordPress Multisite users:

* Install the plugin in your */plugins/* directory (do not install in the */mu-plugins/* directory).
* In order for this plugin to be visible to Site Admins, the plugin has to be activated for each blog by the Network Admin.

**Upgrading from a previous version**
-------------------------------------

Use the upgrade link in the Dashboard (Dashboard > Updates) to upgrade this plugin.



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


= Does this plugin support custom taxonomies? =
Yep.


= Can you be more specific? =
This plugin supports any taxonomy that has 'show_ui' set to true in its declaration.


= Can I disable it for a specific taxonomy? =
Yes, but it requires coding. There is a filter to manipulate the supported taxonomies. Look at the `gtaxi_get_taxonomies` filter in `gtaxi_get_taxonomies()`


= License and Disclaimer =

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License 2 as published by
the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

The license for this software can be found here: [http://www.gnu.org/licenses/gpl-2.0.html](http://www.gnu.org/licenses/gpl-2.0.html)

Thanks!



== Other Notes ==

This plugin is designed for use with the Genesis theme framework version 2 or greater, and will not work without it.



== Screenshots ==
1. Taxonomy admin screen, in this case for tags. A new column (highlighted) is added to show the assigned term image.
2. Term edit screen, in this case for tags. A new section (highlighted) is added to allow an image to be managed for the term.



== Changelog ==
1.0.0
* FIXED: On term edit screen, the image is now shown at its true aspect (no longer forced square)
* NEW: On term edit screen, the image is bigger now; it uses the 'medium' size for display
* NEW: Added `term` to options accepted by `gtaxi_get_taxonomy_image()`. If set to a term object, it will get the image for that term
* NEW: Plugin auto-deactivates if theme is switched from Genesis to non-Genesis
* ENHANCEMENT: Modified UI to be consistent with WP syntax used elsewhere
* ENHANCEMENT: Re-written plugin initialization code to use wp-standard admin notices on fail
* ENHANCEMENT: Speedup of admin screens by using 'medium' images (not full-sized ones)
* ENHANCEMENT: Code clean-up & refactoring
* ENHANCEMENT: Added inline comments; added documentation for filters; improved function documentation



= 0.8.1 =
* Released 17 November 2013
* Enhance: Added gtaxi_get_taxonomies() function
* Bug fix: Added low priority of 999 to init hook to ensure that taxonomies are already registered
* Bug fix: Fixed issue of wp_enqueue_media script not loading on custom taxonomy term edit screens

= 0.8.0 =
* Initial Release 28 October 2013