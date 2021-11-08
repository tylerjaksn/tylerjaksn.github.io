---
layout: post
title:  "First Post!"
date:   2021-11-07 18:45:00 -0500
categories:
---
This is a test of the blog of Tyler Jackson. This is only a test.

The motivation for this blog is to learn in public, most recently coming from [Josh Comeau's _How to Learn Stuff Quickly_](https://www.joshwcomeau.com/blog/how-to-learn-stuff-quickly).

I set this blog up by kinda sorta following [Julia Evans's _How to set up a blog in 5 minutes_](https://jvns.ca/blog/2014/10/08/how-to-set-up-a-blog-in-5-minutes/). Though it certainly took more than 5 minutes. Additional steps that I took are a follows:

- Install ruby 3.0.0 via: {% highlight shell %}$ brew install ruby{% endhighlight %}

- Install rbenv via: {% highlight shell %}$ brew install rbenv{% endhighlight %}

- Add {% highlight ruby %}gem "webrick"{% endhighlight %} to the Gemfile because [webrick is no longer a standard library](https://github.com/jekyll/jekyll/issues/8523).