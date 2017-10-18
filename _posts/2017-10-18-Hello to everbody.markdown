---
layout: post
title:  "Hello to everybody"
date:   2017-10-18 12:13:15 +0200
categories: blog
---

# Hello to everybody

This is my **first test using Jekyll, and it's seems awesome!**

I'm writting this post using *markdown*. It seems fine and awesome. It could be a great option for my purpose: doing post in a easy and quickly way.

Please **keep in mind:** this is just a **test.**

## Images fron the internet

Let's see how works:

![alt text](http://3.bp.blogspot.com/-ajn-9ZveGms/Uim4czBNTgI/AAAAAAAAAWo/cbin6JlIv-w/s1600/Black-And-White-Small-Cat-HD-Wallpaper.jpg")

Ok, it works like a charm! Awesome and easy!

So... how it will work with gifs?


![alt text](https://images.duckduckgo.com/iu/?u=http%3A%2F%2F24.media.tumblr.com%2Ftumblr_mbz08hLeuF1ryaiojo1_400.gif&f=1)


Ok, now we're going to show an image stored inside this website:

![alt text](/assets/pru.png)

What about the post index:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

It works great :)
