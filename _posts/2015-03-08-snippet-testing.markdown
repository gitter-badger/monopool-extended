---
layout: post
title: Code snippet testing
category: development
tags: [dev, testing]
---
Testing out highlight.js within jekyll on github pages.  There seems to be this bug in liquid that causes highlighting to crash when using a "read more" tag.  So instead of using it's internal methods I decided to just use a javascript solution.

<!-- more -->

Just testing a few random types of code:

#### Bash
{% highlight bash %}
#! /bin/bash
echo -n "Pick a screen color (blue, yellow, red ): "
read -e COLOR
setterm -background $COLOR
echo It is a $COLOR day
{% endhighlight %}

#### HTML
{% highlight html %}
<div class="post">
  <h1 class="post-title">{{ page.title }}</h1>
  <span class="post-date">{{ page.date | date_to_string }}</span>
  {{ content }}
</div>
{% endhighlight %}

#### CSS
{% highlight css %}
html,
body {
  margin: 0;
  padding: 0;
}

html {
  font-family: 'Noto Sans', sans-serif;
  font-size: 16px;
  line-height: 1.5;
}
{% endhighlight %}
