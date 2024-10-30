=== LH Dequeue Buddypress ===
Contributors:  shawfactor
Donate link:   https://lhero.org/portfolio/lh-dequeue-buddypress/
Tags: scripts, styles, buddypress, dequeue, speed
Requires at least: 4.0
Tested up to: 5.6
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Dequeue the scripts and styles that buddypress adds for non logged in users.

== Description ==

This plugin simply removes the scripts and styles that buddypress adds to your site, but only for non logged in users. Logged in users who need the buddyoress functionality are not effected

Thus speeding up the experience of normal vistors

This plugin would be more appropriate on a site that has a private buddypress area whilst also having general public facing content.

== Installation ==
1. Upload the `lh-dequeue-buddypress` folder to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress

== Frequently Asked Questions ==

= Can I see an example of a site using this plugin? =
Sure my sports league uses this plugin: https://princesparktouch.com/

= Will this effect my buddypress members experience? =
No once they are logged in the scripts and styles are restored 

= What is something does not work?  =

LH Dequeue Buddypress, and all [https://lhero.org](LocalHero) plugins are made to WordPress standards. Therefore they should work with all well coded plugins and themes. However not all plugins and themes are well coded (and this includes many popular ones). 

If something does not work properly, firstly deactivate ALL other plugins and switch to one of the themes that come with core, e.g. twentyfifeen, twentysixteen etc.

If the problem persists please leave a post in the support forum: [https://wordpress.org/support/plugin/lh-dequeue-buddypress/](https://wordpress.org/support/plugin/lh-dequeue-buddypress/). I look there regularly and resolve most queries.

= What if I need a feature that is not in the plugin?  =

Please contact me for custom work and enhancements here: [https://shawfactor.com/contact/](https://shawfactor.com/contact/)

= Are there any filters to modify the behaviour?  =

Yes a few that you can see in the source. But the most useful is lh_dequeue_buddypress_should_we_deqeue , it can be used to change the logic around when this plugin dequeues assets

== Changelog ==

= 1.00 - November 09, 2017 =
* Initial Release

= 1.02 - June 06, 2018 =
* Extra files

= 1.03 - June 06, 2019 =
* direct file check

= 1.04 - February 16, 2021 =
* Added filters