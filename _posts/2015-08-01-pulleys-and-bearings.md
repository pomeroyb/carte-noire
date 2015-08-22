---
#The layout determines the page type. Enums include 'post, default, page, none'. Enums can be added to "/_layouts"
layout:     post  

#The title of the post. This will be linked on pages. 
title:      Pulleys and Bearings

#Date of Post
date:       2015-08-01 2:58:00

#Author of Post
author:     Brandon Pomeroy

#Not sure what this summary does. Doesn't appear in example posts.
summary:     

#Categories are sort of like folders for Jekyll
categories: ConfinedXY

#Choose the thumbnail at the top of the post. Choose from thumbs in "/_data/thumbnails.yml" or from fontAwesome list
thumbnail:  gears

#Setting this to true will publish this page to the site.
published: true

#Tags for searching.
tags:
 - photos
 - confinedxy
 - printer
 - build
 - pulleys
 - bearings
---

Whoopsies. Murphy's law applies to building 3D printers. In my order from RobotDigg, I mixed up some numbers. Specifically, I got way too many 5mm bore pulleys and bearings, and way too few 8mm bore pulleys and bearings.

Fortunately, RobotDigg's shipping isn't *too* crazy. I've had some things come from China that took over two months to make it to the US, but RobotDigg seems to get it there within two weeks (often within one week). It's not Amazon Prime, but it's pretty good regardless.

Anyway, we finally got the new pulleys and bearings in. For reference, we are using the style of idler from [OpenBeam](http://www.openbeamusa.com/blog/2013/12/28/design-release-the-openbeam-kossel-reprap) -- it's an 8mm bore GT2 pulley with MF83ZZ bearings on either side. I've put this style of idler on my chocolate printing Kossel, and it works fantastically. (I keep teasing about chocolate printing, and I promise to do a blog post on it eventually)

![](/images/confinedXY/IMAG1270.jpg)

The only real worry I have with these idlers is the fact that they are cantilevered. When the belts are in place and tightened, the moment on the M3 bolt may be high enough to cause the bolt to tilt. I don't have any good references for the amount of force the tightened belt will put on the pulley, but the lever arm is only ~7mm at most.

With that in mind, I've decided to go against the hobbyist mentality of *"over build the everloving fuck out of it"*. If the M3 bolt can't hold against the belt, it's pretty trivial to upgrade to an M5 bolt with MF85ZZ bearings.

That's it for now. I'm still waiting on washers that are small enough to work with MF83ZZ (Remember that Murphy's law?), but other than that, all that is left is getting the X-carriage machined.

Stay tuned.