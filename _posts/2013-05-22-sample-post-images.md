---
layout: post
title: "HELLO HELLO"
date: 2020-06-15
excerpt: "Examples and code for displaying images in posts."
tags: [sample post, images, test]
---



### Figures (for images or video)

#### One Up

<figure>
	<a href="https://www.color-hex.com/palettes/22927.png"><img src="https://www.color-hex.com/palettes/22927.png"></a>
	<figcaption><a href="https://www.color-hex.com/palettes/22927.png" title="Morning Fog Emerging From Trees by A Guy Taking Pictures, on Flickr">Morning Fog Emerging From Trees by A Guy Taking Pictures, on Flickr</a>.</figcaption>
</figure>

I like purple!!

#### Two Up

Apply the `half` class like so to display two images side by side that share the same caption.

{% highlight html %}
<figure class="half">
    <a href="/images/image-filename-1-large.jpg"><img src="/images/image-filename-1.jpg"></a>
    <a href="/images/image-filename-2-large.jpg"><img src="/images/image-filename-2.jpg"></a>
    <figcaption>Caption describing these two images.</figcaption>
</figure>
{% endhighlight %}

And you'll get something that looks like this:

<figure class="half">
	<a href="http://placehold.it/1200x600.JPG"><img src="http://placehold.it/600x300.jpg"></a>
	<a href="http://placehold.it/1200x600.jpeg"><img src="http://placehold.it/600x300.jpg"></a>
	<figcaption>Two images.</figcaption>
</figure>


