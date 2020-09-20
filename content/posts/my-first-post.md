---
title: "Image Processing Shortcode Test "
date: 2020-09-20T20:22:06+12:00
draft: true
---


Image added the normal way (markdown) from /static.

```![bird](/images/bird.jpg)```

![bird](/images/bird.jpg)

Image imported the normal way (markdown) from content/posts/

```![building](/posts/building.jpg)```

![building](/posts/building.jpg)

Image shortcode get froms /static/images/

{{ 	&lt; ```image src="/images/forest.png" alt="name"``` &gt; }}

{{< image src="/images/forest.jpg" alt="name" >}}