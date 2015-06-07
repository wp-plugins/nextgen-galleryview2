=== NextGEN-Galleryview ===
Contributors: alexrabe, bhubbard
Donate link: https://brandonhubbard.com
Tags: photos, slideshow,images,gallery,media,admin,post,photo-albums,pictures,widgets,photo,picture,image,nextgen-gallery,nextgen gallery
Requires at least: 3.7
Tested up to: 4.0
Stable tag: 1.3.5
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Adds the Galleryview template for use with the NextGen-Gallery plugin.

== Description ==

NextGEN-Galleryview (originally created by Alex Rabe) is a Wordpress plugin providing NextGen-Gallery plugin users a new template based on the Galleryview jQuery Plugin created by Jack Wanders (@jackwanders). The plugin has been updated by Brandon Hubbard (@bhubbard).

<h1> NOTICE REGARDING SUPPORT</h1>
<p>Two years ago, this plugin was in the WordPress repo, but was no longer being updated. I (@bhubbard) happens to work for a WordPress development company who had many clients using this plugin. At the time I took over supporting it, focusing primarily on improving performance and keeping it up with WordPress, not really adding any features. Since then a lot of changes have happened in the WordPress community. Since I started supporting this plugin, the WordPress builtin Gallery features have improved greatly, and NextGen-Gallery has gone thru some <a target="_blank" href="http://www.nextgen-gallery.com/nextgen-gallery-2-0/">MAJOR CHANGES</a>. On top of that the <a target="_blank" href="https://github.com/jackwanders/GalleryView">galleryview.js</a> script is no longer being actively developed on or supported by any developer.</p>

<p>This plugin has the largest number of users for any plugin I have ever worked on, and its been a great learning experience. If any developers are interested in taking over support I encourage you to <a target="_blank" href="https://github.com/Galleryview/NextGEN-Galleryview/issues">open a issue on github</a> for the plugin with details on how you would want to improve it and continue support. For users I encourage to look into alternative solutions, as there are MANY slider plugins available. I highly recommend <a target="_blank" href="https://soliloquywp.com">Soliloquy</a> as a WordPress Slider, however since most of you have your image in NextGen-Gallery already then I suggest getting <a target="_blank" href="http://www.nextgen-gallery.com/nextgen-pro/">NextGen-Gallery Pro</a>. The NextGen-Gallery Pro offers a <a target="_blank" href="http://www.nextgen-gallery.com/nextgen-pro/#profilmstrip">Filmstrip gallery</a> which will replicate what GalleryView was currently offering. </p>


== Credits ==

Brandon Hubbard - @bhubbard
Alex Rabe
Jack Wanders

== Installation ==

= Basic Usage: =

1. Download, install, and activate the NextGEN Gallery plugin.
1. Download, install, and activate the NextGEN-Galleryview plugin
1. From your Wordpress Dashboard, go to Gallery > Add Gallery/Images > Follow the on-screen cues.
1. When adding a gallery via the shortcode add template="galleryview"

= Advanced Usage: =

1. Create a folder called "nggallery" within your Wordpress theme.
1. Copy "gallery-galleryview.php" from the "view" folder of the plugin and place it within the nggallery folder you created.
1. Now modify the template and galleryview javascript to meet your needs.
1. When adding a gallery via the shortcode add template="galleryview"

== Screenshots ==



== Shortcode ==

= Examples =


[nggallery id=1 template="galleryview"]


== Frequently Asked Questions ==



== Changelog ==

= V1.3.5 =
* Fixed Documentation Page
* Added Notice regarding support

= V1.3.4 =

* Added a Documentation page under NextGEN-Gallery Menu
* Updated JS/CSS override option to use get_stylesheet_directory_uri instead of get_stylesheet_directory

= V1.3.3 =

* Added Support to override CSS & JS within Theme (thanks @jonrandahl - PrecisionCoding)
* Updated PressTrends Functions, added support for Events
* Small CSS Updated, Minified CSS for Performance
* Created jquery.galleryview.min.js & jquery.timers.min.js for Performance

= V1.3.2 =

* Added support for Jetpack Photon

= V1.3.1 =

* Switched galleryview script to responsive version (Thanks to Jeroen Penninck)

= V1.3 =

* Fixed issue with plugin replacing all galleries. Thanks @vtxyzzy
* Updated Easing call to use // instead of http://

= V1.1 =

* Updated GalleryView to latest version (Version 3.0 beta 3)
