---
layout: post
title: "SVG"
date: 2015-12-15
comments: true
description: "SVG Animating Tricks"
keywords: "Trick"
categories:
- Trick
tags:
- Trick
---

SVG handles transform origins differently than HTML element

The default transform origin is (50% 50%)
In SVG element the default value is (0, 0)
firefox dose value percentages
transition: transform .4s ease-out
transform-orgin: 50% 50%
transform: rotate() scale()

~~~ ruby
def what?
  42
end
~~~
