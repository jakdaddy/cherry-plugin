Cherry Plugin
=============

Cherry Plugin contains all shortcodes and widgets used in Cherry Framework. Also Cherry Framework Import/Export features are also added by Cherry plugin.

#### v1.2.5 ####
* Not use `wptexturize` in content and excerpt. Removed temporary. (@link  https://core.trac.wordpress.org/ticket/29557)

#### v1.2.4 ####
* ADD: New google map api shortcode
* FIX: Shortcode dialog (changed sizes)
* FIX: A wrong function_exists check for content_box shortcode
* FIX: Trouble when used сyrillic in the tabs shortcode
* FIX: Argumets variable name in carousel_owl shortcode
* UPD: Changed maintenance mode user rights
* UPD: Rename title_box shortcode in wp-editor and edit description

#### v1.2.3 ####
* FIX: Reset to the previous columns.php file version

#### v1.2.2 ####

* FIX: conflicts flexslider.css
* UPD: carousel.php
* ADD: Added style for under-construction page in mobile devices
* UPD: recent post shortcode(video post type)
* upd: my-social-widget widgets
* FIX: Fixed quotes
* ADD: Added clearfix class to the li item in recent_posts shortcode
* ADD: Added to the all shortcodes filters html-formatted data before return
* ADD: Added outputing value for email custom field in Team and Testimonails post type
* ADD: Added some style to the flex-slider
* Fix: Fixed https://github.com/CherryFramework/CherryFramework/issues/17
* Fix: Fixed display parametr in button shortcode
* UPD: ul counter for post grid shotcode
* FIX: https://github.com/CherryFramework/CherryFramework/issues/13
* FIX: https://github.com/CherryFramework/CherryFramework/issues/10
* UPD: recent testimonials shotcode
* ADD: category filter to mini post shotcode
* UPD: postcycle widget
* UPD: flex slider css
* UPD: Updated flexslider to version 2.2.2
* UPD: css .comments-custom
* Fix: hotfix: removed post-cycle's loader
* Fix: hotfix: Fixed rtl-support in post_cycle shortcode
* Fix: hotfix: removed post-cycle's loader
* Fix: hotfix: Fixed rlt-support in post_cycle shortcode


#### v1.2.1 ####

* Add: Added rtl-language support
* Upd: Improved Cherry Recent Comments widget – get comment for posts, pages, attachments and porfolio custom post type
* Add: Added compatibility audio shortcode with MotoPress plugin
* UPD: get_the_date()
* ADD: content_box shortcode
* ADD: tag option to posts grid shortcode
* ADD: tag option to posts-list shortcode
* ADD: tag option to recent posts shortcode
* UPD: Cherry recent posts (the_date(); -> the_time(‘F j, Y’);)
* UPD: widget banner
* ADD: item counter class
* Add: added custom-class option to row, span, shortcodes
* Fix: Fixed outputing notice
* Fix: Fixed outputing notice
* Add: Added define API_URL constant


#### v1.2 ####

* Add: Compatibility with WP 3.9: fix shortcode dialog
* UPD: Exclude widgets manager on customize.php
* UPD: Improved wpml-plugin compatibility for widgets
* FIX: Fixed issue with french translation - https://github.com/CherryFramework/CherryFramework/issues/6
* FIX: Compatibility with old TM-themes
* FIX: fix instagram and banner widgets
* FIX: import algorithm.
* FIX: remote server error
* UPD: Removed logic for style-switcher
* UPD: readme update


#### v1.1 ####

* Fix: import errors
* Add: blocking files on upload
* Fix: sorting errors
* Add: widgets rewrite
* Add: widgets custom classes
* Fix: shortcode Elastislide
* Add: styleswitcher
* Add: plugin-under-construction-content rewrite in child theme
* Add: plugin updater
* Add: intagram widget
* Upd: social widget
* Fix: fixes in social network widget
* Add: banner widget
* Upd: improvements in wpml-compatibility