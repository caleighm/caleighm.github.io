---
title: Another shiny new blog -- this time on GitHub!
date: 2017-10-17
author: Caleigh
layout: post
comments: true
permalink: /2017/10/17/another-shiny-new-blog/
categories:
  - Miscellaneous
---
I have so much to update! How my co-op is going (and the application process for my co-op), how my directed study is going, my top five favourite bugs (spoiler: one of them includes crashing the head node on a supercomputer!)... I owe you many, many posts.

But I've been a little busy. For one thing, moving over to GitHub pages has been on my to-do list for at least a year. Why pay for hosting when I can put the blog here for free? I also wanted to turn the site into a bit more of a portfolio. Getting all the WordPress posts, media, and comments imported over here was a bit of a pain, but not too bad. I plan on putting a notice up at http://caleighm.com and then shutting down that domain permanently.

I don't want to rewrite an entire tutorial, but I did find that I had to combine info from a couple different sources to get this thing up and running.

So if you're looking to migrate your own blog over, here are some places to start:

# [GirlieMac](http://www.girliemac.com/blog/2013/12/27/wordpress-to-jekyll/)
This one was the bread and butter. It's a couple years old and I didn't find exporting my posts from WordPress to Jekyll as seamless as she did; I ended up having to go through my old posts and fix up a lot of the images' html, in particular. Also, she skips over installing Jekyll on Windows (but you can learn more about that at [Jekyll for Windows](https://jekyllrb.com/docs/windows/)).

Also, she doesn't mention this, but to use https://{GH username}.github.io as a personal site you'll need to have all your site in the master branch -- not gh-pages, like you would for a repo!

# Disqus
Exporting my WordPress comments to Disqus was pretty easy, but then don't forget you have to add your new GitHub domain to the Trusted Domains section on Disqus. You'll also need to use the URL Mapper to migrate from the WordPress domain to the new GitHub one for all your previous posts. This part was pretty tedious; if you have a lot of blog posts, you might want to write a script that maps the URLs for you.

Good luck! I'm glad I did it. Let me know in the comments if you run into any trouble.
