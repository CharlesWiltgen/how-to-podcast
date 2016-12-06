# FeedBurner

In 2004, FeedBurner appeared to help bloggers and podcasters analyse and monetize their RSS feeds. It was a huge success, and Google aquired it in 2007.

Not long after, Google lost interest. In July 2012, FeedBurner Japan (feedburner.jp) went away without warning and never came back, and everyone using it lost all of their subscribers.

The FeedBurner APIs were shut down in October 2012, and AdSense for Feeds in December 2012.

Since then, FeedBurner has had multiple outages, and feeds can take as many as 12 hours to update. Someday it will die without warning, taking your hard-won subscribers with it.

Don’t use it for new feeds. If you use it now, stop using it while you still can.


FeedBurner stats were created for blogs and their web pages, not podcasts and their MP3 enclosures. As a result, the stats are inaccurate and will report that you have more listeners than you actually do.

"Do Not Resuscitate" is tattooed on FB's chest. It's going to die someday, without warning, taking years of your hard-won subscribers with it. This happened in Japan in late July, 2012.
Happily, the solutions are straightforward:

Blubrry provides basic podcast stats for free.

> i've been using feedburner just as a "PO Box" in case I need to switch hosting services.

> i've been using feedburner just as a "PO Box" in case I need to switch hosting services.

Gotcha. If you ever want to eliminate the FeedBurner dependency (and the change you'll lose your subscribers when it goes down), you can redirect a designated public podcast feed URL anywhere you like using your web server, or with a WordPress plug-in like [Redirection](https://wordpress.org/plugins/redirection/).

For example, you might use the URL "http://mydomain.com/podcast/feed/" as your official/canonical feed URL, but redirect that to the feed URL of your current host when it's requested.

(Technical detail: Use an HTTP 302 redirect, instead of a 301 redirect. That way, podcast apps will continue to treat the original URL as canonical.)
Bonus link: How to leave FeedBurner

Also, legit podcast hosts always provide a way to cleanly move off of their system.

> All I want to do is see how many listens and how many subscribers I have.

I can recommend [Blubrry's free podcast stats](http://create.blubrry.com/resources/podcast-media-download-statistics/basic-statistics/).