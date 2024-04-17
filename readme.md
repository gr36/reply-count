# New Plugin: Reply Count
This plugin allows you to display how many replies your micro.blog posts have - it's a vanity metric, nothing more.

![](https://github.com/gr36/reply-count/raw/main/docs/replies.png)

## SetUp
Install the plugin from Github by clicking design, edit theme, and then add new plugin.

Call the plugin anything you wish, copy in the URL from [the Github page](https://github.com/gr36/reply-count), and click Add Plugin.

### Add Partial
Add the partial to the place you wish this to show, for example this may go in the meta information for the post. This can be used in a single post, or in a loop of posts. Each reply count is place in a unique div element so feel free to experiment. 

Simply add  ```{{ partial "replycount.html" . }}``` to your page and the number of replies to that specific post will appear.

### Styling
You can style the block however you like using the class `replies`. The count number itself sits inside an inline-block class `reply_count`.

## Config
To aid styling you can add in your own emoji to appear before the number, as well as your own text to appear afterwards. If thats not your thing then either options can be toggled on/off in the plugin settings.

![](https://github.com/gr36/search-partial/raw/main/docs/settings.png)

## Change Log

1.0 Initial Release
1.1 Add in option for different text dependent on single or multiple replies // count does not show if no replies

### Future Updates
- ability to cutomise how zero replies show
- custom styling dependent on level of replies
