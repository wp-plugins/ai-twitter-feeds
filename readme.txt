=== AI Twitter Feeds (Twitter widget & shortcode) ===
Contributors: augustinfotech
Tags: Twitter, Twitter API, Twitter 1.1, Twitter authentication, Feed, Twitter Shortcode, Twitter tweet, tweets, twitter, widget, twitter connect, twitter follow, twitter follow button, twitter share, twitter share button,Dashboard Twitter
Requires at least: 3.2
Tested up to: 3.6
Stable tag: 1.3
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

As traditional version of twitter API is no longer working now, this plugin provides facility to display twitter tweets on your website using Twitter 1.1 API with authentication.

== Description ==

Features:

* Embed timelines using only username or Hashtags/keywords.
* Highly configurable, many visual options.
* Using Twitter 1.1 API with authentication in Admin.
* No JavaScript embedded.
* You can manage tweets limits, twitter profile image,date, retweet link, reply link, favourite link and username from admin panel.
* You can manage color scheme such as background color, link color, link hover color, border color, text color, header text color, header username color, header hover color on username.
* NEW Admin side display tweets in Dashboard.
* NEW Admin side Manage Show "Follow @username" links.
* NEW Multiple times you can use Twitter widget & shortcode.

Plugin Develop by August Infotech [Visit website](http://www.augustinfotech.com)


== Installation ==

Important

To use this plugin, please follow the steps given below:

1) Register at https://dev.twitter.com/apps/new and create a new app.

2) After registering, fill in App name, e.g. "_domain name_ App", description, e.g "My Twitter App", and write the address of your website. Check "I agree" next to their terms of service and click "create your Twitter application".

3) After this, your app will be created. Click "Create my access token" and you should see at the bottom "Access token" and "Access token secret". Refresh the page if you don't see them.

4) Copy "Consumer Key", "Consumer Secret", "Access Token" and "Access Token Secret" to admin panel, Menu ->'Settings' -> 'AI Twitter Settings'.
 

Follow below steps to install plugin:

1. Download plugin and place 'AI-Twitter-Feeds' folder to the '/wp-content/plugins/' directory or Install plugin directly from your wordpress admin, Menu-> Plugins -> Add New, and search for 'AI-Twitter-Feeds'zip and Install.
2. Activate the plugin through the WordPress admin panel,'Plugins' menu -> Installed Plugins -> find the 'AI Twitter Feeds' -> Activate.
3. Set Options for Twitter feeds from the admin panel menu link,'Settings -> AI Twitter Settings'.
4. Place PHP code '< ? php do_shortcode("[AIGetTwitterFeeds ai_username='Your Twitter Name(Without the "@" symbol)' ai_numberoftweets='Number Of Tweets' ai_tweet_title='Your Title']"); ? >' to display twitter feeds in your page template.
5. Place shortcode '[AIGetTwitterFeeds ai_username='Your Twitter Name(Without the "@" symbol)' ai_numberoftweets='Number Of Tweets' ai_tweet_title='Your Title']' to display twitter feeds in your post(s).
6. Use the widget to place it in your sidebar or other areas!

== Frequently Asked Questions ==
No Questions

== Screenshots ==

1. Widget Setting example in admin.
2. Widget view on front side.
3. Use Shortcode OR PHP code in Post/Template.
4. Settings Screen from WordPress Admin.
5. WordPress Admin Tweets Display In Dashboard.

== Changelog ==
= 1.0 =
* First version.

= 1.1 =
* NEW Admin side display tweets in Dashboard.
* NEW Admin side Manage Show "Follow @username" links.
* NEW Multiple times you can use Twitter widget & shortcode.

= 1.2 =
* Fixed the issue of appending feeds content on the top of page where shortcode is included. Now content is displayed where you keep your shortcode in templates.

= 1.3 =
* Fixed the widget width in admin panel. Modified links and Installation steps.

== Upgrade Notice ==

* Fixed the issue of appending feeds content on the top of page where shortcode is included. Now content is displayed where you keep your shortcode in templates.
