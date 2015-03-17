---
categories: ["development"]
comments: true
date: 2015-03-16T00:02:15-04:00
draft: true
image: ""
imageheight: 100%
tags: ["video.js","javascript","hugo"]
title: Video.js support with Hugo shortcodes
---

#### Verified: I can glue stuff together. Hooray for me!

{{< videojs aatf "http://drunkenarts.com/films/20140820_ice_water_challenge.mp4" mp4 640 480 "http://drunkenarts.com/images/20140820_ice_water_challenge.png" >}}
<!--more-->
Video.js makes embedding videos easy. Hugo shortcodes+Go templating allow me to embed these videos with a handful of params. I feel like I'm cheating by not writing this infrastructure myself. Somehow, I don't ever feel that way when I'm writing C++ code even though I make heavy use of existing libraries/etc., but with web development I feel like I'm just pasting things together, probably because of how high up the stack this is(which isn't necessarily a bad thing).

I think it's because I have this subconscious paranoia about some sort of crazy event(e.g. zombie apocalypse, nuclear holocaust, alien attack, deletion of all JavaScript engines on Earth) where we will end up in a situation where we need to rebuild things from scratch, and we will have lost a lot of the fundamentals that we used to build our modern society. I'm not saying that we'd want to have this knowledge to rebuild what we have today from scratch -- in fact, it would probably be smarter to build something **better** based on what we've learned from its evolution -- but regardless of what we wanted to do, we'd benefit from having that history and intimate familiarity with the infrastructure.

I guess it's part of my nature to always worry about redundancy of knowledge and depth of understanding. Fortunately, there are way too many problems to solve in the world and way too much cool stuff to build, and not nearly enough time, so I think I'm done here. Time to go do things. :)