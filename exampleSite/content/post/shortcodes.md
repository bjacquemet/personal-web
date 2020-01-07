---
title: Shortcodes
description: Exaplanation on the shortcodes with personal-web
date: 2019-04-29T16:18:12+01:00
publishDate: 2019-04-29T19:12:12+01:00
---

Introduction of the shortcodes defined in the personal-web theme.

<!--more-->

## Add a figure
```go-html-template
{{</* figure src="/post/images/sample_image.jpg" 
caption="Photo by Tim Mossholder on Unsplash" */>}}
```

results in

{{< figure src="/post/images/sample_image.jpg" caption="Photo by Tim Mossholder on Unsplash" >}}

**Note:** files are kept in a `images` folder, directly in the post/portfolio folder.


## Add a single Tweet
```go-html-template
{{</* tweet-single 1120412132036706305 */>}}
```

results in
{{< tweet-single 1120412132036706305 >}}

This shortcode is useful in case of multiple tweets in a thread. If you want to show a single tweet, use this shortcode, with the ID of the Tweet. The ID is the end of the tweet link.

For example: \
https://<span></span>twitter.com/BarackObama/status/**1120412132036706305**
