+++
title = "Reclaiming My Attention: Ditching the YouTube Algorithm for RSS"
date = 2025-03-11
+++

Social media platforms are designed to be addictive, feeding us an endless stream of notifications, trending topics, and algorithmically curated distractions. While these platforms can be useful for staying informed, they often waste more time than they save.

I personally have been addicted to YouTube very much. And lately I have realised how I keep scrolling YouTube trying to find a way to "engage" my brain with the next mindless video, which people who use a lot of YouTube would like to call it: "slop content". 

As I struggled to cut down my YouTube usage, I realised that the biggest problem wasn’t the content itself—it was the way YouTube delivered it. The endless recommendations kept pulling me back in. I found myself scrolling and refreshing YouTube to find something to watch. The 'add to queue' button made things worse by allowing me to scroll and make a queue of videos which I'd watch, which I'd do on loop. I've probably even broken the algorithm on a few occasions from excessive scrolling. Ironically, the solution to my addiction came from something I learned on YouTube. I remembered a video I saw about RSS feeds few months ago.

RSS (Really Simple Syndication) allows you to subscribe directly to your favorite blogs, news sites, and creators—without ads, algorithms, or distractions. Instead of scrolling past clickbait and viral trends, you can get straight to the content that matters to you. Unlike social media platforms that use algorithms to decide what you see, RSS puts you in full control.

RSS is better than social media algorithms in every single way:

 -  **No clickbait or distractions** – You only see content from sources you choose.
-   **No endless scrolling** – Once you’ve read everything in your feed, you’re done.
-   **No engagement farming** – You’re not bombarded with “recommended” content designed to keep you hooked.
-   **Works across platforms** – RSS isn’t tied to one service; it works for blogs, YouTube, and even some social media sites.


## Closing the YouTube Tab
[Bugswriter](https://www.youtube.com/@bugswriter_), a YouTuber who has inspired my Linux journey, on a [video](https://www.youtube.com/watch?v=Vq5NpUncvkA) about RSS said something along the lines of 'when Linux YouTubers ask you to subscribe to their channel, they don't ask you to do that on YouTube, they really are just asking you to use the RSS feeds of  their YouTube channel.' Although it is clearly meant as an exaggeration, it was this sentiment that came to me when wondering over how I can reduce my usage of YouTube.

[jschlatt](https://www.youtube.com/@jschlattLIVE) on a [video](https://www.youtube.com/watch?v=aCVCfyyZOlk) about habit building on one of his other channels, [theweeklyslap](https://www.youtube.com/@theweeklyslap), introduced me to an idea of adding friction to bad habits as a way to discourage them. I knew, if I want to reduce my time spent on YouTube, I'd have to make trying to watch something on YouTube invovle additional steps, and make it feel like a chore every time.

Everyday when I turn on my PC, the first thing I open on my web browser is YouTube. The YouTube tab on my browser is never closed, and is usually the first tab to open when I first open my web browser. Whenever I have nothing else to do *(read procrastinate)*, I'd scroll through my YouTube recommendations to watch anything that mildly catches my interest. 

So I closed the YouTube tab.

But there still are some things on YouTube that I like to keep up with. Even if I close the YouTube tab, every morning, I'd open YouTube and scroll through my recommendation to make sure I'm not missing anything. This is where RSS feeds come in for me.

## De-bloating YouTube
I spent nearly 30 minutes to think of channels whose videos I watch daily or whose videos make part of my daily routine and made a list. I decided to make an RSS feed for these channels. It is fairly easy making an RSS feed of YouTube channels. While some RSS readers do require getting the channel-id to fetch the RSS feeds, the reader I use works with just the channel's URL.

I started off with using [Fluent](https://hyliu.me/fluent-reader/), which is free to use and has a desktop app. There is an initial time input required to set up your first RSS feed. Getting a YouTube RSS feed into Fluent involved the getting channel-id method, which I didn't mind. But soon after setting things up, I realised that opening youtube links from Fluent didn't work. For some reason Fluent also wasn't able to show any content from YouTube when you open any post on the feed. It probably works really well the normal use case of getting news directly from publishers, but for my use case, Fluent was useless. 

Luckily, most RSS readers support exporting your RSS subscriptions for easily switching between readers. So, I settled on using [yarr](https://github.com/nkanaev/yarr) (yet-another-rss-reader) as my RSS reader of choice. It is simple, lightweight, minimal and works out of the box. yarr provides prebuilt binaries for macOS, Windows and Linux so there is no installation required (you can also build from source!). If it is more your style, you can self host it on your server as well. It doesn't have any frills like Fluent did, but it does what it needs to do without any issues.

Once set up with my feed, I can truly close my YouTube tab. Now I get my "subscriptions" directly into yarr. I can see new videos in the 'Unread' tab in yarr. If I feel like watching a video, I open the YouTube link in a new tab through yarr, and then set my playback speed to 2x (yes, I'm one of those people) before I start watching. I have to do this for every single video I want to watch, hence making the process of watching videos feel like a chore, which works as negative reinforcement.

I know some channels that upload very rarely, and have very high quality videos that I haven't added to my feed yet simply because I'd probably forgotten about them while making my RSS feed. But I do have notifications turned on for them on my smartphone, so whenever they end up uploading next, I will add them to my RSS feed.

I do still think I'll casually open the YouTube homepage every once-in-a-while to scroll through, but hopefully it'll be in moderation from now on. I might even find new creators that I might want to follow, but I'll know that when they say 'subscribe to my channel', to me it means something completely different from what normal people would think.

With RSS feeds, I will hopefully gain freedom from the algorithm gods and only get prompted to watch what I decide is worthy of my time. I don't use any other social media platform even though I may have accounts on them, but if you do use them, I'm sure there would most likely be a way to get your social media feeds into your RSS reader to achieve the ultimate freedom from the algorithms. YouTube does its best to hide the fact that you can set up RSS feeds to encourage subscribing on their platform, and hence keep users there for as long as possible. But the Open Source community has still found a way to streamline the process. So surely, some way must also exist for other social media platforms too. If you also want to decouple from social media, set up your RSS feed today. I'm not going to give you a step-by-step guide here, but there are excellent resources and friendly people on the internet who are more than willing to help.
