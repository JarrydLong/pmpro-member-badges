=== Paid Memberships Pro - Member Badges Add On ===
Contributors: strangerstudios
Tags: paid memberships pro, pmpro, badges, badge, users, members
Requires at least: 3.5
Tested up to: 4.5.2
Stable tag: .3.1

Assign unique member badges (images) to each membership level and display via a shortcode or template PHP function.

== Description ==
This add on for Paid Memberships Pro allows you to upload member badges for each membership level and use a PHP function in your template files or a shortcode to display a member badge for a logged in member anywhere in your WordPress site.

== Installation ==
This plugin works with and without Paid Memberships Pro installed.

= Download, Install and Activate! =
1. Upload the `pmpro-member-badges` directory to the `/wp-content/plugins/` directory of your site.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. Edit your membership levels to upload badges images.
1. Use the [pmpro_member_badge] shortcode or the pmpromb_show_badge() function to show a badge on your site.

== Frequently Asked Questions ==

= I found a bug in the plugin. =

Please post it in the issues section of GitHub and we'll fix it as soon as we can. Thanks for helping. https://github.com/strangerstudios/pmpro-member-badges/issues

= I need help installing, configuring, or customizing the plugin. =

Please visit our premium support site at http://www.paidmembershipspro.com for more documentation and our support forums.

== Changelog ==
= .3.1 =
* BUG: Using a different method to get the image from the upload media popover that should hopefully work more consistently.
* ENHANCEMENT: Showing the text box for the image URL in case you want to edit it manually or at least verify it changed.

= .3 =
* FEATURE: Added badge upload to edit membership level page.
* FEATURE: Added [pmpro_member_badge] shortcode.
* Initial commit with a readme.
