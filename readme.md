<!-- DO NOT EDIT THIS FILE; it is auto-generated from readme.txt -->
# Stream

![Banner](assets/banner-1544x500.png)
Track and monitor every change made on your WordPress site in beautifully organized detail.

**Contributors:** [x-team](http://profiles.wordpress.org/x-team), [shadyvb](http://profiles.wordpress.org/shadyvb), [fjarrett](http://profiles.wordpress.org/fjarrett), [akeda](http://profiles.wordpress.org/akeda), [kucrut](http://profiles.wordpress.org/kucrut)  
**Tags:** [actions](http://wordpress.org/plugins/tags/actions), [activity](http://wordpress.org/plugins/tags/activity), [admin](http://wordpress.org/plugins/tags/admin), [analytics](http://wordpress.org/plugins/tags/analytics), [log](http://wordpress.org/plugins/tags/log), [notification](http://wordpress.org/plugins/tags/notification), [stream](http://wordpress.org/plugins/tags/stream), [users](http://wordpress.org/plugins/tags/users)  
**Requires at least:** 3.6  
**Tested up to:** 3.8  
**Stable tag:** trunk (master)  
**License:** [GPLv2 or later](http://www.gnu.org/licenses/gpl-2.0.html)  

## Description ##

**Note: This plugin requires PHP 5.3 or higher to be activated.**

Never be in the dark about WP Admin activity again. Stream allows you to know exactly when changes to your site have been made, and more importantly, who did them.

Every logged-in user action is logged in an activity stream and organized for easy filtering by context, action, and even IP address.

**Recorded activity:**

 * Posts
 * Pages
 * Custom Post Types
 * Users
 * Themes
 * Plugins
 * Tags
 * Categories
 * Custom Taxonomies
 * Settings
 * Menus
 * Media Library
 * Widgets

**Coming soon:**

 * Comments
 * Multisite

Built with performance in mind, you can determine how long records should live before being purged (depending on the amount of user activity your site can expect). Stream also won’t pollute your default posts table with records or slow down content querying on your site.

Stream is built to extend, allowing developers to easily build their own connectors to track any type of action in the activity stream (developer documentation coming soon).

**Development of this plugin is done [on GitHub](https://github.com/x-team/wp-stream). Pull requests welcome. Please see [issues](https://github.com/x-team/wp-stream/issues) reported there before going to the plugin forum.**

[![Build Status](https://travis-ci.org/x-team/wp-stream.png)](https://travis-ci.org/x-team/wp-stream?branch=master)

## Screenshots ##

### Every logged-in user action is logged in the activity stream and organized for easy filtering and searching.

![Every logged-in user action is logged in the activity stream and organized for easy filtering and searching.](assets/screenshot-1.png)

### Control which user roles can access Stream, determine how long records should live before being purged, or purge them from the database manually at any time.

![Control which user roles can access Stream, determine how long records should live before being purged, or purge them from the database manually at any time.](assets/screenshot-2.png)

## Changelog ##

### 0.7.2 ###
**2013/12/12** - Bug fixes for the Installer connector. Props [shadyvb](http://profiles.wordpress.org/shadyvb/)

### 0.7.1 ###
**2013/12/12** - Hotfix to remove PHP 5.4-only syntax. Role Access option added to Settings. Props [kucrut](http://profiles.wordpress.org/kucrut/)

### 0.7 ###
**2013/12/11** - Added connectors for Taxonomies and Settings. Bug fixes. Props [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.6 ###
**2013/12/09** - UX improvements to manual DB purge. Cron event for user-defined TTL of records. Bug fixes. Props [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.5 ###
**2013/12/08** - Require PHP 5.3 to activate plugin. Provide action links for records when applicable. Bug fixes. Props [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.4 ###
**2013/12/08** - Improved support for pages and custom post types. Chosen for filter dropdowns. Pagination support in screen options. Bug fixes. Props [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.3 ###
**2013/12/07** - Improved actions for Users context. Action for edited images in Media context. Bug fixes in Menus context. Props [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/), [akeda](http://profiles.wordpress.org/akeda/)

### 0.2 ###
**2013/12/06** - Second iteration build using custom tables data model. First public release. Props [shadyvb](http://profiles.wordpress.org/shadyvb/), [fjarrett](http://profiles.wordpress.org/fjarrett/)

### 0.1 ###
Initial concept built using custom post type/taxonomies as the data model. Props [shadyvb](http://profiles.wordpress.org/shadyvb/)


