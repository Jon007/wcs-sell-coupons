=== WooCommerce Sell Coupons  ===
Contributors: MarieComet, jonathanmoorebcsorg
Donate link: ...
Tags: woocommerce, coupons
Requires at least: 4.7
Tested up to: 4.9.5
Stable tag: trunk
License: GPLv3
License URI: https://www.gnu.org/licenses/gpl.txt

Quick and easy sell coupons.

[![project status](http://www.repostatus.org/badges/latest/active.svg)](https://github.com/MarieComet/wcs-sell-coupons/)
[![GitHub GitHub latest](https://img.shields.io/github/release/MarieComet/wcs-sell-coupons.svg)](https://github.com/MarieComet/wcs-sell-coupons//releases)
[![Wordpress  Wordpress latest](http://img.shields.io/wordpress/plugin/v/wcs-sell-coupons.svg)](https://wordpress.org/plugins/wcs-sell-coupons)
[![Wordpress downloads](http://img.shields.io/wordpress/plugin/dt/wcs-sell-coupons.svg)](https://wordpress.org/plugins/wcs-sell-coupons/)
[![Wordpress rating](http://img.shields.io/wordpress/plugin/r/wcs-sell-coupons.svg)](https://wordpress.org/plugins/wcs-sell-coupons/)
[![license](https://img.shields.io/github/license/MarieComet/wcs-sell-coupons.svg)](https://github.com/MarieComet/wcs-sell-coupons/blob/master/LICENSE)

== Description ==

This WordPress plugin create a new WooCommerce product type and add possibilty to sell Coupons as Gift Card in front-office.
Please visit WooCommerce > Settings > General once activated to setup some settings !

== Installation ==

This section describes how to install the plugin and get it working.

1. Upload the plugin files to the `/wp-content/plugins/plugin-name` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Use the Settings->Plugin Name screen to configure the plugin
(By default the Translate buttons are turned on in all applicable contexts, in Settings you can individually turn off contexts and you can see a few hints on usage.)


== Frequently Asked Questions ==

= How do I report an issue? =

Please use https://github.com/MarieComet/wcs-sell-coupons/issues.


== Screenshots ==

none yet

== Changelog ==

= 12/Apr/2018 =
#20 replace obsolete hook woocommerce_add_order_item_meta

= 20/Oct/2017 =
#15 add gift message field
#6 add coupon code to order metadata, check coupon is not already issued before issuing
#6 copy purchaser and shop in case email not received by destination
#6 check coupon is not already used, if so add message to emails
#8 filter wcs_gift_coupon_meta allows custom coupon rules metadata to be applied, can be used to 
   implement functionality such as template gift coupon etc 



= Repositories =

* [GitHub](https://github.com/MarieComet/wcs-sell-coupons/)
* [WordPress.org](https://plugins.svn.wordpress.org/wcs-sell-coupons/)  [not available yet]

= Recommended Plugins: =

This tool requires WooCommerce 3.x


== Contribution ==

If you have a feature request, or if you have developed the feature already, please feel free to use the [Issues](https://github.com/MarieComet/wcs-sell-coupons/issues) and/or (Pull Requests)[https://github.com/MarieComet/wcs-sell-coupons/pulls] section.

Plugin translations are provided for English, French, Spanish, please feel to contribute more [translations](https://translate.wordpress.org/projects/wp-plugins/wcs-sell-coupons).
