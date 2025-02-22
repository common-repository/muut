=== Muut – Commenting and Forums Re-Imagined ===
Contributors: PaulHughes01, tipiirai, jannelehtinen, monikamuut, courtneycouch
Tags: forum, commenting, comments, social, realtime, discussion, widgets
Requires at least: 3.7
Tested up to: 4.8.0
Stable tag: 3.0.6
License: MIT
License URI: https://github.com/muut/wordpress-plugin/blob/master/license

== Description ==

Muut represents a complete re-imagination of what internet discussion forums and commenting should be. It’s a modern, fast, highly scalable discussion platform that you can embed onto your WordPress website, and personalize with css to match the design of your site.

[youtube https://www.youtube.com/watch?v=huOjL8t-q_0]

Starting at just $16 a month, you have a discussion platform that offers unlimited posts, comments, users, threads — and we never charge you based on usage. That means you'll never be punished by having to pay more for a successful community.

Whether you’re setting up for the first time or have just updated to the new version of the plugin, you’re going to love what we’ve done to make implementing Muut in your WordPress website easy and flexible.

= Why Muut? = 

* Unified system for both forums and commenting. Same users and design
* Full featured forums makes your WordPress site conversational
* Flat or threaded commenting for small or big topics
* Real-time. No page reloads – posts, replies, likes and users appear in real-time
* Spam filtering, email notifications and 20+ different language versions

= Built For WordPress =

* Skinnable style the discussion directly from the WordPress CSS editor
* Focus on content. Text focused, uncluttered and linear user interface
* Comes with five widgets, all of which update in real-time 
* Single Sign-On. Use the WordPress login, users and avatars

= Optimized for SEO =

* Micro format optimized static content
* Static content served from your domain
* Custom S3 bucket support for Developer accounts
* Escaped fragment support for Google

= New! Widget Details =

* _Online Users_ – Now the Online Users list isn’t limited to just your main forum page and channel embeds. You can use the Online Users widget on any of your pages to show who is currently logged in (and how many other people are viewing the site). Watch users’ portraits appear on the fly as they sign in to join the discussion.
* _Latest Comments_ – Since Muut is so great to use as the commenting system on your posts and pages, the Latest Comments widget keeps track of which posts have received the latest comments and who made them, and all the users on your website can see it update in real-time as they participate in the discussions on all your posts.
* _Trending Topics_ – If you want to help users stay on top of which posts are getting the most activity on your forum, the Trending Posts widget does just that, with real-time updates to comments and likes—not to mention the trademark Muut green “currently typing” circle.
* _Discussion Channel_ – You can now embed a single specific channel in your website’s sidebar. Users can watch and join the discussion without having to stop browsing the rest of your website.
* _My Feed_ – By using the My Feed widget, users can keep track of all the activity on all the discussions they’ve joined and postes they’ve made right in your website’s sidebars.

You can find more information about Muut at our [website](https://muut.com) and read the full [plugin documentation](http://learn.muut.com/integrations/wordpress/getting-started). For more information about why we do what we do, check out our [Manifesto](https://muut.com/manifesto/) and see our [pricing page](https://muut.com/pricing/) for details on the features available on your Muut subscription.

== Installation ==

1. From your website admin, visit _Plugins > Add New_
2. Search for _“Muut”_
3. Click _Install Now_
4. Activate the plugin
5. Visit the _Muut_ menu item on the Admin navigation
6. Set your forum settings
7. Create pages and posts integrating Muut by using the Muut panel added to the editor!

= Getting Help =
If you need help with any aspect of integrating with the plugin, feel free to check out the full [plugin documentation](http://learn.muut.com/integrations/wordpress/docs), visit our [forum](https://muut.com/forum/#!/wordpress), or you can submit a support request here.

== Frequently Asked Questions ==

= Can I still use WordPress commenting if I only want to use the main forum functionality? =

Absolutely. You simply can deactivate the “Use Muut for post commenting” Muut setting in the Muut administration page. Alternatively, you can disable or enable Muut commenting on specific posts by enabling that global setting and then activating/deactivating “Use Muut for commenting” option on a post-by-post basis.

= Can I embed a Muut channel with content surrounding it, before and after? =

You can, although we are planning to make it easier in a future release. For now, the best way is to use the old shortcode ([muut path="/the/channel/path"]) in the content editor.

= Where can I get more help with the plugin? =

There are several great ways to learn more about and get help with the plugin. The first is our full [plugin documentation](http://learn.muut.com/integrations/wordpress/docs); you can also ask for help on our [forum](https://muut.com/forum/#!/wordpress) or submit a support ticket right here on the WordPress plugin page.

== Screenshots ==

1. A Muut forum
2. Muut post commenting
3. Online Users widget
4. Latest Comments widget (with subscription)
5. Trending Posts widget (with subscription)
6. Discussion Channel widget
7. My Feed widget
8. Muut settings page
9. Muut post/page editor panel

== Upgrade Notice ==

= 3.0.6 =
The update to version 3.0.6 contains some updates to the widgets as they are handled on cached websites as well as speed optimizations.

= 3.0.5 =
The update to version 3.0.5 adds an option for signed embeds to work better with caching plugins, along with some other small improvements and bug fixes.

= 3.0.4 =
The update to version 3.0.4 is mainly small but important bug fixes and improvements in notifications for errors and possible problems with environment.

= 3.0.3 =
The update to version 3.0.3 is mainly an update for compatibility with 4.1 and Twenty-Fifteen.

= 3.0.2 =
The update to version 3.0.2 is mostly a feature update, focusing on the five added widgets.

= 3.0.1 =
The update to version 3.0.1 is a small update with a couple big fixes and better SEO and S3 bucket support.

= 3.0 =
The update to version 3.0 is a major update that enhances the plugin experience in a large way. The update _does_ support all of the earlier plugin functionality (such as the shortcodes), but we recommend updating when you have a little bit of time to experiment and ensure that everything continues to work as expected. We hope you enjoy the new version!

== Changelog ==

= 3.0.6 =
Notes

* Improved the functionality of widgets in relation to websites with caching enabled.
* Improved performance on websites with large numbers of posts and pages displaying large numbers of them at once.

= 3.0.5 =
Notes

* Added option in plugin settings for signed embeds to dynamically fetch the signature info for websites that us caching plugins so that pages with Muut can be cached properly, but they still need to expire at least once every 24 hours.
* Comment Counts are cached to decrease the API calls to the Muut servers.

Bug Fixes

* Base domains with ":" in them (such as for ports) have that replaced with "_" in the comment path generation.

= 3.0.4 =
Notes

* S3 bucket now accepts just the bucket name rather than the full URL. Should adjust transparently, but a very small group of users may need to change by hand (the plugin will notify).

Bug Fixes

* Fixed problem where SEO link was not displaying for some signed communities.
* Added admin notifications for small permissions problems, such as unwriteable .htaccess or inaccessible uploads directory.
* Various small bug fixes.

= 3.0.3.1 =
Notes

* Added filter `muut_latest_comments_show_avatar` to allow not-showing the avatars in the Latest Comments widget; defaults to true.

Bug Fixes

* Fixed some errors with the Latest Comments widget such that not all posts necessarily were being registered as changing, such as if domain name was changing.

= 3.0.3 =
Features, UX, Improvements

* Added support for new WordPress Twenty-Fifteen theme.
* Updated default Forum Template.
* Added "old" directory under templates to house older template versions for reference.

Notes

* Added filter for Federated Identity user avatar `muut_fedid_user_avatar_url`. Filters avatar URL and passes User ID and User object as arguments.

Bug Fixes

* Forum name more strictly validated, to prevent corrupted .htaccess file.
* Fixed PHP Notice that displays when shortcodes are being used.

= 3.0.2.3 =
Features, UX, Improvements

* Added back the Custom S3 Bucket Support.
* Added support for signed embeds separate from SSO/Federated Identities (for secure embedding).

Notes

* Webhooks: 'post' webhook now also stores the body content (replies already were).

Bug Fixes

* Various small fixes.

= 3.0.2.2 =
Bug Fixes

* Fixed problem with webhooks stopping working after a while since activation.
* Internationalized strings in widgets on the frontend.
* Validating fields more strictly on the backend.

= 3.0.2.1 =
Bug Fixes

* Spamming / Unspamming work properly with webhooks.
* Various small webhook event fixes.
* Widget caches update properly with all webhook events.
* Widget caches can be reset by visiting Muut plugin settings page.

= 3.0.2 =
Features, UX, Improvements

* Added “Who’s Online” widget.
* Added “Discussion Channel” widget.
* Added “My Feed” widget.
* Added “Latest Comments” widget.
* Added “Trending Posts” widget.
* Added Muut Webhooks support.
* Clean framework to setup listeners for Muut websocket events (devs).
* Easy to hook into Muut webhook events to extend functionality (devs).

Notes

* When webhooks are activated and functioning, more data is stored in the WordPress database regarding Muut content. Note that the *actual displayed content* is always pulled from the embed properly and NOT the WordPress database.

Bug Fixes

* Fixed problem for websites who use Muut for forums and another plugin for commenting.
* Muut embedding using the template tags has better support for unique uses.
* Removed the S3 bucket settings section in favor of having that entirely managed on Muut end. This, in turn, will improve SEO further.
* Returns a proper error if the administrator tries to enter a forum name with spaces in it.

= 3.0.1 =
Features, UX, Improvements

* Added support for escaped fragments so that actual forum content is indexed right in pages by Google.
* Added S3 bucket support for serving content and SEO indexing for Developer accounts.
* Easy to upgrade to Developer account straight from Muut settings page.

Bug Fixes

* If Muut commenting is globally disabled, pages no longer default to being Channel embed pages on creation.
* Able to disable Muut commenting on specific pages and posts, even if “Use Muut commenting on posts with existing comments” is on.

= 3.0 =
* Added meta box / panel to the post editor (and page editor) that controls the Muut embeds for that post, including Muut commenting.
* Deprecated shortcodes in favor of the added meta box.
* Added some options for embedding functionality to the various embed types.
* For posts using Muut commenting, a comment count for that post is fetched from the Muut API.
* Allowing search engines to index Muut content at the site’s domain now built in for Apache (can be disabled).
* Tied Muut commenting tighter with WordPress’s default commenting so that many of the WordPress commenting settings (like allowing comments on future articles) directly affect Muut commenting.
* Ships with default templates for Commenting overrides and the main Forum Page. Both templates can be overridden in a muut directory in the active theme root.
* Added a bunch of helpful template tags so that websites can, for example, add extra customizations on their own page templates.
* Powered by many more actions and filters that can be used for extra customizations.
* Modified and standardized Muut terminology; what was called a “sub-forum” or “category” is now known as a Channel.
* Moved the administrative settings to its own admin menu item “Muut” (rather than a sub-menu item under Plugins).
* Adds a global constant ‘MUUT_VERSION’ that can be defined as a specific Muut version if an older version should be used (the plugin defaults to the latest version).