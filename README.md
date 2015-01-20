=== Recent Posts Slider Responsive ===

Contributors: dilemma123	
Donate link: http://www.anitamourya.com/donate
Tags: responsive slider, responsive carousel, posts, recent, recent posts, recent post, slider, latest posts, posts slider, posts carousel
Requires at least: 1.0.0
Tested up to: 4.1
Stable tag: /trunk/
License: GPLv2 or later

Recent posts slider responsive displays your blog's recent posts using flexisel carousel.

== Description ==

Recent Posts slider responsive displays your blog's recent posts either with thumbnail image of your post and the post title.

You can customize the slider/carousel in many ways (total post in slides, image size to choice, post per slide, auto slider, etc).

Every slider uses a unique id which have to be a number and it should be different if you are using many slider in one page, by default the plugin uses ID number "2" for the slider widgets.

If you find it useful please don't forget to rate this plugin.

== Installation ==

= Installation =

1. You can use the built-in installer.
     OR         
     Download the zip file and extract the contents.
     Upload the 'recent-posts-slider-responsive' folder to your plugins directory (wp-content/plugins/).
1. Activate the plugin through the 'Plugins' menu in WordPress.

Now go to **Settings** and then **Recent Posts Slider Responsive** to configure any options as desired.

= How to use =

In order to display the recent posts slider responsive, you have three options

1. Simply place `<?php if (function_exists('rpf_display_slider')) echo rpf_display_slider(); ?>` in your theme 
or use rpf_display_slider($category_ids, $total_posts, $post_per_slide, $post_include_ids, $post_exclude_ids, $slider_id); to have different slider on same or different page templates.
1. Add the shortcode simply '[rpf]' or '[rpf category_ids="2,3" total_posts="2" post_per_slide="1" post_include_ids="1" post_exclude_ids="2" slider_id="4"]'
1. Using widget.

== Frequently Asked Questions ==

= Why there is need for Slider id? =
If you use many sliders in the same page, then it is necessary to have different id for the div that we use to display the sliders, neither there will be clash as the div's will have same id.

= Having problems, questions, bugs & suggestions =
Please add them in WordPress Plugin support section

== Screenshots ==

1. Demo Page

== Changelog ==

= 1.0.0 =
* Initial release version.

== Upgrade Notice ==

= 1.0.0 =
* Initial release version.