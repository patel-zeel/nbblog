---
aliases:
- /setup/2021/06/19/blur-affinity
categories:
- setup
date: '2021-06-19'
description: Blurring an image selectively using Affinity Photo
layout: post
title: Blurring an image selectively using Affinity Photo
toc: true

---

In this post (video recording), I selectively blur an image using Affinity Photo on the iPad. I used the following command (borrowed from: https://stackoverflow.com/a/63575228/743775)

![]({{ site.baseurl }}/images/new_image_combined.png "Selectively blurring images")

```bash
convert -append Image-1.png blurred.jpg  -resize x500x new_image_conbined.png
```

<iframe width="560" height="315" src="https://www.youtube.com/embed/5xbhfr4jy8U" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


 
 
