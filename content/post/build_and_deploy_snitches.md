---
categories: ["development"]
comments: true
date: 2015-03-13T00:11:38-04:00
draft: false
image: ""
tags: ["wercker","github","hugo"]
title: Build and deploy, snitches!
---

#### Yeaaaa Boiiiiii!

Feels like a legit system now, y'all! <!--more-->So now I have it so that I can push new content to the blog by first staging it locally, then committing+pushing the changes to GitHub. I set up a wercker app to then take over, build my master branch using Hugo, then deploy it to my webhost. Rock.