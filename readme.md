# Reply Count For Micro.blog
This plugin allows you to display how many replies your micro.blog posts have - it's a vanity, nothing more.

## SetUp

Instal the plugin from Github by clicking design, edit theme, and then add new plugin.

Call the plugin anything you wish, copy in the URL from the Github page, and click Add Plugin.

### Add Partial

Add the partial to the page you wish this to show on, for example, in your post meta information. 

Simply add {{ partial "replycount.html" . }} to your page and the number of replies to that specific post will appear.

This can be used in a single post, or in a loop of posts. Each reply count is place in a uniquie div element. 