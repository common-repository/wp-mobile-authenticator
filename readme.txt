=== Nova's Mobile Authenticator ===
Contributors: (elrond1369)
Tags: security, 2 step verification
Requires at least: 3.9
Tested up to: 4.2.2
Stable tag: 1.1.0
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Adds 2 step verification to your site

== Description ==

When used with my app this plugin will generate a one time code that you must enter when login into the admin panel. This 2 step verification can be switched on per account by going to your profile in the admin panel. The normal mode changes the code every 15 seconds and the relaxed mode changes it every 30 seconds.


== Installation ==
* [Download app for Android](https://play.google.com/store/apps/details?id=net.jswebdev.novasauth)
* iOS users [Get the web app](http://jacobsommerfeld.net/apps/novas-auth/) and use add to homescreen to use as a native app.
1. Place in wp-content/plugin
2. Activate.
3. Go to your profile.
4. At the bottom of the page, type in the keys the app gives you and click update profile.
5. Make sure the current code in your profile matches the code in the app.
6. Check enable then click update profile.

== Frequently Asked Questions ==

Q. Can I setup for another account keys for someone else.

A. No. You can only set up for the account you are logged into.

== Screenshots ==
1. View of place to put keys in.
2. View of login page with plugin activated.

== Changelog ==

= 1.0.0 =
* Initial release

= 1.0.1 =
* Name change
* New link for new apps

= 1.1.0 =
* Resets keys if the code is entered correct password 3 times without a correct password