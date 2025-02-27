=== Contact Dialog ===
Contributors: jameslafferty
Tags: contact form, javascript, recaptcha, ajax, jquery-ui
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=JSL4JTA4KMZLG
Requires at least: 3.0.1
Tested up to: 3.1
Stable tag: trunk

Enables display of an AJAX driven contact form when a user clicks on links with a specified class.

== Description ==

This plugin allows you to display a form when users click on links inside of elements with a class you specify. The plugin uses a custom version of jQuery UI on the front end, and does not address situations where Javascript is turned off. It does provide a simple, attractive contact form inside of a modal dialog box.

If you find this plugin useful, please rate it and/or make a donation.

== Installation ==
1. Upload the contact-dialog folder to /wp-content/plugins/.
1. Activate the plugin through the "Plugins" menu in WordPress.
1. Specify your email address on the Contact Dialog options page.
1. Specify a class to attach the Contact Dialog to. The Contact Dialog will open when elements of the class are clicked or when anchors within elements of the class are clicked.
1. Please rate the plugin and/or make a donation.

== Frequently Asked Questions ==

= Why am I not getting emails? =
Could be one of a few things. First, check the version of the plugin you're using. If it's lower than 0.4, upgrade and it should resolve the issue. If that doesn't do it, change the default email address from my address to your own... It'll make my inbox lighter, too. Finally, you may be having an issue with mail in general. Contact your server admin for help.

== Screenshots ==
1. Select the Contact Dialog menu page.
2. Set your email address and pick a class to attach the dialog to.
3. Assign the css class to a link. Here's how you do it in a nav menu.
4. When the link is clicked, the Contact Dialog will display.

== Changelog ==
= 0.5 =
*Updated version of jQuery Validation plugin for compatibility with current WP version of jQuery.

= 0.4.6 =
* Updated Javascript to remove error when trying to close Recaptcha in IE.
= 0.4.5 =
* Minified dialog box Javascript.

= 0.4.4 =
* Fixed bug preventing the display of the Recaptcha in IE. Thank you to [welshylad](http://wordpress.org/support/profile/welshylad) for pointing this out.

* Fixed bug that was preventing proper submission on subdirectory installs of WordPress. Thank you to [jeptech](http://wordpress.org/support/profile/jeptech) for finding this.

= 0.4.2 =
* Added additional French translation on admin side.

= 0.4 =
* Major bugfix. The plugin was sending emails to the sender rather than to the recipient specified in the admin. That must be annoying! Thanks very much to a user who shall remain anonymous for pointing out this issue.

= 0.3 =
* Removed some notices that were appearing in WP_DEBUG mode.

= 0.2.1 =
* Missed some class file updates on the previous commit. This corrects that.

= 0.2 =
* i18n support added.
* French translation added.

= 0.1 =
* First release.

== Upgrade Notice ==
= 0.5 =
* Adds newer version of the jQuery validation plugin to address compatibility issues.

= 0.4.6 =
* Repairs error on dialog close in IE (minor bugfix)

= 0.4.5 =
* Minifies the dialog box javascript.

= 0.4.4 =
* Fixes serious bugs for Internet Explorer and subdirectory installs of WordPress

= 0.4.2 =
* This updates some fields that previously were not being translated into French.

= 0.4 =
* The previous version sent emails to the sender -- an-NOY-ing! -- This version fixes that and actually sends the emails to the specified admin.

= 0.3 =
* Removes some notices that were appearing in WP_DEBUG mode (minor).

= 0.2.1 =
* Adds some class files that were missing from the previous commit.

= 0.2 =
* Added i18n support for localization of the plugin.
* Added French Translation (thank you to Frederick Marcoux for his hard work translating!).

= 0.2 =
* Added i18n support for localization of the plugin.
* Added French Translation (thank you to Frederick Marcoux for his hard work translating!).

= 0.1 =
* First release.

== Internationalization (i18n) ==

This plugin has been translated into the languages listed below:

* fr_FR - French. Thank you to Frederick Marcoux for contributing!

If you're interested in doing a translation into your language, please let me know.
