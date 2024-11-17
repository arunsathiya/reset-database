=== Reset Database ===

Contributors: arunsathiya
Original Author: maltesesolutions
Tags: Reset Database, reset wordpress, database reset, reset wordpress database, clean wordpress, default wordpress, restore wordpress, database reset, developers, programmers, wordpress reset
License: GPLv2
Requires at least: 4.0
Tested up to: 6.7
Stable tag: 1.0.0
Requires PHP: 7.4

Enhanced WordPress database reset tool that preserves specified plugin states after reset.

== Description ==

This is a fork of the Reset Database plugin by MalteseSolutions, enhanced with the ability to preserve specific plugin states after database reset.

Key Features:
* Resets your database to default installation
* Deletes media files
* Preserves activation state of specified plugins
* Secure - requires admin password
* Available via Tools -> Reset Database
* Automatic updates via Git Updater

== Installation ==

1. Install the [Git Updater](https://git-updater.com/) plugin
2. In WordPress admin, go to Settings > Git Updater > Install Plugin
3. Enter: https://github.com/[your-username]/reset-database
4. Click "Install Plugin"

Alternative installation:
1. Download the latest release from the GitHub repository
2. Upload to your WordPress plugins directory
3. Activate the plugin
4. Access via Tools -> Reset Database

== Requirements ==

* WordPress 4.0 or higher
* PHP 7.4 or higher
* [Git Updater](https://git-updater.com/) plugin (for automatic updates)

== Credits ==

This plugin is based on Reset Database by MalteseSolutions (http://www.maltesesolutions.com). Enhanced and maintained by [Your Name].

== Using Git Updater ==

This plugin supports automatic updates via Git Updater. To receive updates:

1. Install the Git Updater plugin
2. Activate Git Updater
3. Go to Settings > Git Updater
4. Enter your GitHub token if using a private repository
5. Updates will appear in your WordPress dashboard

[Rest of the original readme content...]

== Changelog ==

= 1.0.0 =
* Initial fork from Reset Database
* Added plugin state preservation feature
* Added Git Updater support