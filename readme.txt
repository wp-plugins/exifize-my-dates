=== Plugin Name ===
Contributors: lbell, driftless1
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=BTMZ87DJDYBPS
Tags: EXIF, date, photoblog, custom, 
Requires at least: 3.0
Tested up to: 3.3
Stable tag: 0.1
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Photoblog plugin to change the published dates of a selected post type to the EXIF:capture_date of the Featured or 1st attached image of the post.

== Description ==

This tool will attempt to irreversably change the actual post date of Post Type selected.

The date will be changed using (in order of priority):

1. 'exifize_date' custom meta (date or 'skip')**
2. EXIF date of Featured Image
3. EXIF date of the first attached image
4. Do nothing. Be nothing.

**To override the function with a custom date, create a new custom meta field with the name: 'exifize_date' and value: 'YYYY-MM-DD hh:mm:ss' -- for example: '2012-06-23 14:07:00' (no quotes). You can also enter value: 'skip' to prevent the EXIFizer from making any changes.

== Installation ==

1. Upload the `/exifize-my-dates/` directory to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Navigate to 'EXIFize Dates' under the 'Tools' menu 

== Frequently Asked Questions ==

= Can this plugin do X,Y, or Z? =

Probably not. It is simple, straightforward, and ugly. If there is a feature you think would be absolutely killer, let me know, and I'll what I can do.

= Can you add feature X,Y, or Z? =

Possibly - though I do this in my spare time.

= I'm getting unexpected results, what should I do? =

Post on the Wordpress.org forums would be your best bet - so others can benefit from the discussion.

== Screenshots ==


== Changelog ==

= 0.1 =
First release


