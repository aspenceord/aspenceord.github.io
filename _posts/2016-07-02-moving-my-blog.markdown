---
layout: post
title:  "Moving my blog"
---

I'm trying to resurrect my dormant blog, even if I'm the only one who will read it. I've decided to move to [github pages](https://pages.github.com/) and use [Jekyll](https://jekyllrb.com/) to manage my blog.

It has proven fairly simple to set up. To use github pages you need a repository called username.github.io hosted on github, where username is your github username. Files in that repository will be served when you visit that URL.

I'm using Jekyll to generate the site content. I had to install Jekyll first. Installing gems on OSX is not straightforward apparently. I had to change the installation folder to /usr/local/bin like so: `$sudo gem install jekyll -n/usr/local/bin`. Once I installed the jekyll gem it was just a matter of running `$jekyll new .` in the root folder of my repository.

Another little wrinkle is that I installed the github-pages gem, and that apparently broke the dependency on kramdown for Jekyll. I installed [Bundler](http://bundler.io/) deals with the dependencies better. 

I haven't got many old posts so I could just recreate them manually, but I'm going to look at some way of pulling them out of blogspot automatically. I'll write about how that goes soon.