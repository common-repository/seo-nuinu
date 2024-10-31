=== SEO nuinu ===
Contributors: Studio nuinu
Tags: seo, meta, post, page, edit, title, description, keywords, nuninu
Requires at least: 2.8.2
Tested up to: 2.9.1
Stable tag: 1.4.2

Customize pages and posts meta title, description and keywords directly in post or page edit window. 

== Description ==

SEO nun makes possible to put custom meta tags for WordPress pages and posts and makes them to be different from the actual page title.

== Screenshots ==
1. Screenshot of SEO nuinu panel displayed below the post and page content editor.
2. Screenshot of SEO nuinu settings.

== Installation ==

1. Upload `seonuinu` files to  the `/wp-content/plugins/` folder
2. Activate it through the 'Plugins' menu in WordPress
3. Place `<?php meta_title(); ?>` with `<?php if (function_exists('meta_title')) { meta_title(); } else { wp_title(); } ?>` in your header template.
4. To override pages title in your templates set `$wppm_title = 'Newly defined title';` before the call to `get_header();`.

== Frequently Asked Questions ==

= What custom field names does it use? =

The field names are `_seonuinu_title`, `_seonuinu_description` and `_seonuinu_keywords`.
The underscore prefix prevents it from being displayed in the list of custom fields.

= How to disable plugin for posts?=
SEO nuinu can be disabled for posts by unchecking the `Enable for posts as well as pages.` option on the settings page.

== Changelog ==

= 1.4.1 =
* Options added
* Tested for wordpress 2.9.1

= 1.4.2 =
* Screenshoots added
* Minor corrections made
* New links and readme added
