---
categories: ["development"]
comments: true
date: 2015-09-24T00:17:09-04:00
draft: false
image: ""
imageheight: 100%
tags: ["golang","siteupdates","reading"]
title: New site feature -- "Recent Reading" side pane
---

#### A feed of my insane browsing habits

It's almost like the days of Google Reader are back!<!--more--> I miss being able to follow my friends' shared articles easily. Facebook and Twitter somewhat serve that purpose, but not quite as succinctly as Google Reader did. Well, at least now people can check out my recommended reading and random thoughts.

I had to do a lot Go-template+Hugo template hacking in order to get all of this working, and I know that bits of it are probably still a mess, but I'll throw it on the todo for the site. Some known style-related things:

* Mobile styling support still needs to be verified
* Recommended reading posts aren't formatted properly in the category and tag views
* The "Show more..." view isn't displaying articles properly

