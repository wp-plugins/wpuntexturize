=== wpuntexturize ===
Contributors: coffee2code
Donate link: http://coffee2code.com
Tags: quotes, curly, substituions, wptexturize, post, content, coffee2code
Requires at least: 1.5
Tested up to: 2.9.1
Stable tag: 1.0.1
Version: 1.0.1

Prevent WordPress from displaying single and double quotation marks as their curly alternatives.

== Description ==

Prevent WordPress from displaying single and double quotation marks as their curly alternatives.

Despite the unfortunately misleading name, this plugin is NOT the antithesis of WordPress's `wptexturize()` function.  This ONLY prevents WordPress from making HTML entity code substitutions of single and double quotation marks with their curly alternatives and does NOT prevent `wptexturize()` from making any other character and string substitutions. 

== Installation ==

1. Unzip `wpuntexturize.zip` inside the `/wp-content/plugins/` directory (or install via the built-in WordPress plugin installer)
1. Activate the plugin through the 'Plugins' admin menu in WordPress

== Frequently Asked Questions ==

= Why are certain characters in my posts still being replaced by their HTML entity encoded version? =

This ONLY prevents WordPress from making HTML entity code substitutions of single and double quotation marks with their curly alternatives and does NOT prevent WordPress from making any other character and string substitutions.

= What text does this plugin modify (aka filter)? =

This plugin potentially modifies the post content, excerpt, title, comment text, and widget text.

== Changelog ==

= 1.0.1 =
* Now also filter widget_text
* Note compatibility with WP 2.9+
* Update readme.txt (including adding Changelog)

= 1.0 =
* Initial release