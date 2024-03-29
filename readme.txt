=== LoginWP (Formerly Peter's Login Redirect) Pro ===
tags: login, logout, redirect, admin, administration, dashboard, users, authentication
Requires at least: 4.7
Tested up to: 6.2
Stable tag: 4.0.8.0
License: GPL-2.0+

Redirect users to different locations after logging in and logging out.

== Description ==
Define a set of redirect rules for specific users, users with specific roles, users with specific capabilities, and a blanket rule for all other users. Also, set a redirect URL for post-registration.

== Frequently Asked Questions ==
See the website for more info https://loginwp.com/

== Changelog ==

= 4.0.8.0 =
* Improved: Compatibility PHP 8
* Improved: Compatibility with WP 6.2
* Fixed: Assets URL
* Updated: Plugin’s Description

= 4.0.7.0 =
* Added [LearnPress](https://loginwp.com/redirect-wordpress-users-after-login-learnpress/?ref=changelog) integration.
* PHP 8 improvements.
* Fixed Warning: Undefined array key "rul_first_login"
* Added filter to execute integrations conditions last.

= 4.0.6.0 =
* Added [WishList Member](https://loginwp.com/redirect-wordpress-users-after-login-wishlist-members/?ref=changelog) integration.

= 4.0.5.0 =
* Added [Paid Memberships Pro condition](https://loginwp.com/redirect-wordpress-users-after-login-paid-memberships-pro-levels/?ref=changelog).
* Fixed error message: syntax error, unexpected ‘?’

= 4.0.4.0 =
* Added ["On First Login" condition](https://loginwp.com/article/redirect-wordpress-users-after-first-login/).
* Fixed: PHP Notice Trying to get property ‘user_login’ of non-object.
* Added redirect_to to LifterLMS sales page.

= 4.0.3.0 =
* Added ProfilePress membership plan integration.
* Fixed bug with wp list pagination per page not working.

= 4.0.2.0 =
* Added Polylang integration.
* Added WPML integration.
* Fixed fatal error caused by other plugin metaboxes.

= 4.0.1.1 =
* Added logout support to all Pro conditions.
* Added support for Uncanny Toolkit.

= 4.0.1.0 =
* Added [TutorLMS integration](https://loginwp.com/?utm_source=wprepo&utm_medium=changelog&utm_campaign=4010#pro-conditions).
* Improved admin page loading speed.

= 4.0.0.8 =
* Added noncache to temporary redirects.
* Added user_id placeholder.
* Added wp_logout() redirection support

= 4.0.0.7 =
* Fix site and website url placeholder bug in multisite.

= 4.0.0.6 =
* Compatibility with WP 5.9.
* Added [LearnDash](https://loginwp.com/?utm_source=wprepo&utm_medium=changelog&utm_campaign=3006#pro-conditions) Enrolled Course and User Group redirect conditions.
* Added [WooCommerce](https://loginwp.com/?utm_source=wprepo&utm_medium=changelog&utm_campaign=3006#pro-conditions) Purchased Product, Purchased Product Category, Active User Subscription, Active Membership Plan redirect conditions.
* Added [MemberPress](https://loginwp.com/?utm_source=wprepo&utm_medium=changelog&utm_campaign=3006#pro-conditions) Subscribed Membership redirect condition.
* Added [Restrict Content Pro](https://loginwp.com/?utm_source=wprepo&utm_medium=changelog&utm_campaign=3006#pro-conditions) Has Membership redirect condition.
* Added [LifterLMS](https://loginwp.com/?utm_source=wprepo&utm_medium=changelog&utm_campaign=3006#pro-conditions) Enrolled Course and Enrolled Membership redirect conditions.

= 4.0.0.5 =
* Added escaping to url fields in redirection UI
* Added https://yoursite.tld/?loginwp_link_redirect=true for triggering login redirection.

= 4.0.0.4 =
* Added MemberMouse integration.
* Prefixed class exist check with backslash.
* Fixed broken link to license page from admin notice.

= 4.0.0.3 =
* Fixed multisite installation bug.
* Fixed issue where database migration didn’t work.

= 4.0.0.2 =
* Fixed bug where redirect_to_front_page function returned null.
* Improved Restrict Content Pro support.

= 4.0.0.1 =
* Fixed issue where placeholders wasn't getting saved as url.
* Improved BuddyPress/BuddyBoss support.

= 4.0.0.0 =
* The genesis
