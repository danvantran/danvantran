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

Feels like a legit system now, y'all! <!--more-->So now I have it so that I can push new content to the blog by first staging it locally, then committing+pushing the changes to GitHub. I set up a Wercker app to then take over, building my master branch using Hugo, then auto-deploying it to my webhost. Rock.

Edit: This ended up being a bit trickier than I thought, given that I wanted to use protected environment variables in Wercker. But it works!

2nd Edit: It ended up needing even more cleaning up, because of how the FTP deployment Wercker module works and where it dumps the files. Had to make some changes to my web host config but I think the full-automation is finally set. Huzzah.