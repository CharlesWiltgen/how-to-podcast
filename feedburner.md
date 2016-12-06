# FeedBurner

In 2004, FeedBurner arrived to help bloggers and podcasters analyse and monetize their RSS feeds. It was a huge success, and Google aquired it in 2007.

Not long after, Google lost interest. In July 2012, FeedBurner Japan (feedburner.jp) went away without warning and never came back. Everyone using it lost all of their subscribers.

Google shut down the FeedBurner APIs in October 2012, and AdSense for Feeds in December 2012. Since then, FeedBurner has had multiple outages every year. Feeds can take as many as 12 hours to update.

Don’t use FeedBurner for new feeds. If you use it now, consider alternatives before you’re forced to.

## “I use FeedBurner for podcast metrics”

Some podcasters still use FeedBurner for basic podcast metrics. Because it was blog-focused, it was never very good at that, reporting that podcasters have more listeners than they actually do.

I can recommend [Blubrry's free podcast stats](http://create.blubrry.com/resources/podcast-media-download-statistics/basic-statistics/).

## “I use FeedBurner as my ‘permanent’ URL”

Instead of using a FeedBurner URL, you can redirect a feed URL anywhere you like using your web server, or with a WordPress plug-in like [Redirection](https://wordpress.org/plugins/redirection/).

For example, you might use the URL "http://mydomain.com/podcast/feed/" as your official/canonical feed URL, but redirect that to the feed URL of your current host when it's requested.

_(Technical detail: Use an HTTP 302 redirect, instead of a 301 redirect. That way, podcast apps will continue to treat the original URL as canonical.)_



Bonus link: How to leave FeedBurner

Also, legit podcast hosts always provide a way to cleanly move off of their system.
