This is a markdown file about how to format your posts in order to make my life easier.

The file extension is `.markdown`. Your title needs to be formatted as following: `YYYY-MM-DD-This-is-my-title.markdown`, where `YYYY` is the year, `MM` is the month, and `DD` is the day.

For example, `2017-10-11-the-site-is-up.markdown`, goes to [https://codeclubwollaston.github.io/update/2017/10/11/the-site-is-up.html](https://codeclubwollaston.github.io/update/2017/10/11/the-site-is-up.html) once the website is generated.

```
---
layout:
title:  ""
date:
categories:
author:
---
```

This is the standard file for a post and needs to be at the top of each of your posts. When writing for the website, make sure that the above is filled out correctly. It will not be visible on the blog, but is very important for the generation of HTML code.

For a standard post, the layout should be `post`.

For a YouTube post, the layout should be `video` and the additional variable `yt-id` should be added, where the ID of the YouTube video should be. For example:
```
---
layout: video
title:  "Video Test"
date:   2017-06-07
categories: video
author: Sam Drage
yt-id: foFKXS6Nyho
---

This is a video by TomSka, published on YouTube.
```
would generate a page with a the ASDF Movie 10 video on it with the text `This is a video by TomSka, published on YouTube.` underneith it. In the web address `https://www.youtube.com/watch?v=foFKXS6Nyho`, the appropriate `yt-id` would be `foFKXS6Nyho`.

>"Life needs things to live"
>~Lord Percival Fredrickstein Von Musel Klossowski de Rolo III