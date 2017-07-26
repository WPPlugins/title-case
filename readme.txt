=== Title Case ===
Contributors: nanovivid
Tags: title, case, capitalize
Requires at least: 1.0
Tested up to: 2.5.1
Stable tag: 1.1

This is a simple plugin that attempts to intelligently capitalize post titles.

== Description ==

This is a PHP port/WordPress adaptation of [John Gruber](http://daringfireball.net/)'s [title case code](http://daringfireball.net/2008/05/title_case). Once activated, it will automatically filter post titles as they are output and put them in proper Title Case. To quote Gruber's introduction:

> It’s pretty easy to write a non-clever title-casing function. The simplest way is to just capitalize the first letter of every word. That’s not right, though, because it’ll leave you with capitalized small words like if, in, of, on, etc. What you want is something that not only knows not to capitalize such words, but will un-capitalize them if they’re erroneously capitalized in the input.

Title Case handles all edge cases the original code does. In addition, it will avoid capitalizing the i in "-ing" if you happen to end a word with that.

== Installation ==

1. Upload `title-case.php` to the `/wp-content/plugins/` directory.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. That's it!

== Version History ==

= 1.1 =

Fixes bugs related to HTML entities.

= 1.0 =

Initial release.