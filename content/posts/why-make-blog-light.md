+++
title = "Why This Website is so Bare-bones"
date = "2025-06-27"
description = "The Reasons why I made my Blog a lightweight website"
tags = ["web"]
+++


# Why This Website is so Bare-bones


![⏱️📄](/img/stopwatch-page.png)

With the current state of my blog *(This Website!)*, most pages come in under 100 Kb, total. Obviously, this has some adverse effects on the general quality of the website. The images are blurry, and the site itself looks pretty basic and old-fashioned, with very few images. *Why would I sacrifice the quality of my website for a small file size, when it's 2025 and everyone has broadband all the time?*

---

### People *Don't* have broadband all the time

I can think of many situations where someone would have slow internet ( < 5 mb/s), where website weight plays a *significant* role in how fast the website loads. Here are some low-bandwidth situations I can think of off the top of my head:
- Living in a rural area
- Being on a train/bus/plane and using the wifi
- Being physically far away from a wifi access point
- Being in an area with poor cellular coverage

All of these situations are common enough that I think it's reasonable to be designing a website that works in those situations.

### When a website is light, it loads *even faster* when on broadband

Even if you *can* load a heavy website in a reasonable amount of time, a light website will still be a better overall experience since it can load *even faster*, which is just cool. Also, for cellular data, the connection is often metered, so a light website will use less of your data quota.

### It makes it easier to self-host

While *you* may have a high bandwidth connection, the web server still has to serve you the website. When I'm writing this, the website is hosted on Github pages, so this currently is not a concern for me, though the lighter website should lead to a lower power draw, which is good environmentally. However, I want to host this site on my own hardware in the future. Since allocated home internet upload speeds are usually *much* lower than download speeds, I might only have ~10 mb/s of bandwidth to work with since I need to keep some bandwidth for personal use. In this situation, a lighter website means I can serve more clients with the same connection.

### It's more performant in your browser

If all I use is basic HTML and CSS, with nothing to fancy, your browser can render the site much quicker, meaning scrolling and zooming should be much smoother and lead to a better reading experience.

---

It's not that hard to make a light website. Here, I'm using [Hugo](https://gohugo.io), a static site generator, with the [Hugo Bear](https://github.com/janraasch/hugo-bearblog/) theme, which is specifically designed to compile light websites. With this setup, I can just write markdown and get a light website, even with the style modifications I made to the base theme. 

