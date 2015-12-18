---
layout: post
title: "Why source maps"
date: 2015-12-17
comments: true
description: "Why source maps?"
keywords: "Tool"
categories:
- Tool
tags:
- Tool
---

Modify CSS inside chrome developer tool, expected changes will automatically occur in related css file. No need for switching to editor and change code again.
<br>
This will create source map file for each CSS file. .map file is retavle for Chrome.
 {% highlight bash %}
 sass --sourcemap application.scss:application.css
 {% endhighlight %}
<br>
Sourcemaps enables us to see the original source instead of compiled one in developer tool
{% highlight bash %}
ls application.scss application.css application.css.map  
{% endhighlight %}
