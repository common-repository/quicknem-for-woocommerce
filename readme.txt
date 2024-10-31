=== Plugin Name ===
Contributors: ounziw
Donate link: https://quicknem.com/
Tags: nem, woocommerce, payment
Requires at least: 4.9.7
Tested up to: 4.9.7
Stable tag: 0.8
Requires PHP: 5.4
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

This plugin enables NEM payment for WooCommerce, using Quicknem webservice. Quicknem is available in Japan and you need to register Quicknem. Quicknem costs 1% of the transaction.

== Description ==

In Japan, [Quicknem payment webservice](https://quicknem.com/) is available, which provides an easy-going nem payment gateway. This plugin allows you to connect to Quicknem. Visitors of your shops can pay by NEM(XEM).

* This plugin assumes the WooCommerce plugin is installed and activated.
* This plugin assumes you registered Quicknem payment webservice.

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/quiciknem-for-woocommerce` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the plugin through the 'Plugins' screen in WordPress
1. Go to wp-admin/admin.php?page=wc-settings&tab=checkout&section=quicknem_wc

== Quicknem Registration ==

This plugin assumes you registered Quicknem payment webservice. Quicknem is available in Japan and websites are written in Japanese. In order to register Quicknem, you need to read and understand Japanese Language.

In quicknem.com, you need to set the URLs for success/cancel .

* URL when payment completed:
URL/wc-api/success

* URL when payment cancelled:
URL/wc-api/cancel


== Screenshots ==

1. Settings Area for Quicknem-for-WooCommerce plugin. URL is an endpoint for Quicknem. Desciption will be shown when visitors select a payment service. User ID is an ID for Quicknem. API KEY is a secret Key for Quicknem.

== Changelog ==

= 0.8 =
* Initial release.
