=== Behavior Flow ===
Contributors: julien731,SiamKreative
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=KADEESTQ9H3GW
Tags: prerendering,prerender,speed,optimization,performance,seo,conversion,preload
Requires at least: 4.0
Tested up to: 4.3
Stable tag: 1.0
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Better site performance and increased conversion rates using visitors' behavior flow

== Description ==

This plugin does only one thing: it allows you to prerender specific pages / posts on your WordPress site.

The [prerendering](https://developers.google.com/chrome/whitepapers/prerender) feature which will make your website faster, as the browser will fetch and render the entire next page on the background.

Therefore, if you know which page your visitors are most likely to visit next, you can preload it. The User Experience (UX) will therefore be slightly better.

= Getting Started =

If you want more in-depth explanations, we've written a mini-tutorial on our blog: [Behavior Flow: Speed Up Your WordPress Site](https://themeavenue.net/behavior-flow-faster-wordpress/)

1. Firstly, you need to determine how your users traverse and interact with your site. Simply [sign in to Google Analytics](https://www.google.com/analytics/web/#home/) and go to the Behavior Flow page ([Analytics Help](https://support.google.com/analytics/answer/2785577?hl=en)).
2. Login to your WordPress site, install and activate this plugin.
3. Edit the page where most visitors land (*most likely your homepage*).
4. Scroll down to the meta box "Page to Prerender" and select the next page from the dropdown menu (the one that most visitors will browse next).
5. Hit the "Update" button!

= Cons =

Enabling page prerendering will likely increase server load. You should figure out a good balance between prerendering and increasing the server load. Visitors that land on your site will request the entire next page even if they do not visit it...

== Installation ==

= Using The WordPress Dashboard =

1. Navigate to the 'Add New' in the plugins dashboard
2. Search for 'Behavior Flow'
3. Click 'Install Now'
4. Activate the plugin on the Plugin dashboard

= Uploading in WordPress Dashboard =

1. Download `behavior-flow.zip` from this page
2. Navigate to the 'Add New' in the plugins dashboard
3. Navigate to the 'Upload' area
4. Select `behavior-flow.zip` from your computer
5. Click 'Install Now'
6. Activate the plugin in the Plugin dashboard

= Using FTP =

1. Download `behavior-flow.zip` from this page
2. Extract the `behavior-flow` directory to your computer
3. Upload the `behavior-flow` directory to the `/wp-content/plugins/` directory
4. Activate the plugin in the Plugin dashboard

== Frequently Asked Questions ==

None yet.

== Screenshots ==

1. Metabox that lets you select the next page to pre-load
2. Example of behavior flow

== Changelog ==

= 1.0 =
* First stable release

== Upgrade Notice ==

No upgrades yet.