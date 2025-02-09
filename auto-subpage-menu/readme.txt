=== Auto Subpage Menu ===

Contributors: jojoee
Donate link: 
Tags: admin, navigation, menu, menus, child page, child pages, page, pages, submenu, submenus, subpage, subpages, child page, child pages
Requires at least: 3.3.0
Tested up to: 5.4.2
Stable tag: 4.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

== Description ==

By default wordpress menu system, wordpress can only automatically add/remove **top-level page** to/from menus

* When **publish** top-level page then add it into menus
* When **move** top-level page to trash then remove it from menus
* When **restore** top-level page then add it into menus

this feature has no effect with **subpage** (child page), but **Auto Subpage Menu** can

* When **publish** subpage (child page) then add it into menus (if its page parent exists in menu)
* When **update** subpage (child page) then update menus
* When **move** subpage (child page) to trash then remove it from menus
* When **restore** subpage (child page) then add it into menus

== Installation ==

1. Install the plugin via plugin's dashboard or download and upload this plugin into `wp-content/plugins` directory
2. Activate the plugin through the **Plugins** menu in WordPress
3. Go to **Menus** and check `Automatically add new top-level pages to this menu`
4. Let's see the magic

== Frequently Asked Questions ==

= How to use it ==
activate the plugin on your plugin dashboard (`/wp-admin/plugins.php`)

= How it work ==
please see [screenshot](https://wordpress.org/plugins/auto-subpage-menu/screenshots/)

== Screenshots ==

1. When publish subpage then add it into menus (screenshot-1.jpg)
2. When update subpage then update menus (screenshot-2.jpg)
3. When trash subpage then remove it from menus (screenshot-3.jpg)
4. When restore subpage then add it into menus (screenshot-4.jpg)

== Changelog ==

= 1.1.4 (24 Apr 2016) =
* Fix issue - plugin is not working if not using default table prefix (wp_), found and fixed by [ncwebdev](https://wordpress.org/support/profile/ncwebdev), [topic](https://wordpress.org/support/topic/menu-link-doesnt-work-properly-when-moving-a-page)
* Update code style
* Add TODO section

= 1.1.3 (14 Feb 2016) =
* Update meta (readme file, description, link)

= 1.1.2 (27 Aug 2015) =
* Update readme file according wordpress readme file standard

= 1.1.1 (26 Aug 2015) =
* Change file name from README.md to readme.txt
* Update plugin description

= 1.1.0 (24 Aug 2015) =
* Fix issue (twice add child page to menus when update with unchanged page parent)
* Refactoring

= 1.0.0 (23 Aug 2015) =
* First release

== Notes ==

* [WordPress Coding Standards](https://codex.wordpress.org/WordPress_Coding_Standards)
* [phpDocumentor](http://www.phpdoc.org/) DocBlock Standard
* [Auto Subpage Menu](https://wordpress.org/plugins/auto-subpage-menu/) - Wordpress Directory Uri
* 2 spaces for indent
* [Repository on Github](https://github.com/jojoee/auto-subpage-menu)

== TODO ==

* [ ] Implement DocBlock to all
* [ ] Automatically update child-page when its parent have been move, suggested by [ncwebdev](https://wordpress.org/support/profile/ncwebdev), [topic](https://wordpress.org/support/topic/menu-link-doesnt-work-properly-when-moving-a-page)
* [ ] Add other versions into wordpress download page
