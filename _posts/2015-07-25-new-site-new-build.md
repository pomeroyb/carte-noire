---
#The layout determines the page type. Enums include 'post, default, page, none'. Enums can be added to "/_layouts"
layout:     post  

#The title of the post. This will be linked on pages. 
title:      New Website, New Printer Build

#Date of Post
date:       2015-07-25 2:21:19

#Author of Post
author:     Brandon Pomeroy

#Not sure what this summary does. Doesn't appear in example posts.
summary:     

#Categories are sort of like folders for Jekyll
categories: jekyll

#Choose the thumbnail at the top of the post. Choose from thumbs in "/_data/thumbnails.yml" or from fontAwesome list
thumbnail:  wrench

#Setting this to true will publish this page to the site.
published: true

#Tags for searching.
tags:
 - new
 - site
 - confinedxy
 - printer
 - build
---

I've finally gotten around to building a website for myself. I'm hosting the site off of Amazon AWS, and am using the excellent [Carte Noire][1] as the base theme.

I've also been working on a new 3D printer design over the past few months, and what better way to announce that than on this brand new site?

##ConfinedXY
ConfinedXY is a large format 3D printer, based on the [CoreXY][2] motion platform. It is not a RepRap machine -- in fact, the design incorporates zero 3D printed parts so far. It uses 3 belt driven leadscrews to move the print bed along the Z axis. The bot will be driven off of a Rev. E MightyBoard, and will be powered by the excellent [Sailfish firmware][3].

![](/images/confinedXY/01.png)

Currently, the machine has a build volume of approximately 500mm in X, 330mm in Y, and 600mm in Z (Or about 20" x 13" by 24"). The gantry is comprised of MGN12H rails on a waterjet aluminum sheet.

![](/images/confinedXY/02.png)

The frame iself is comprised of 1515 aluminum extrusion from Misumi, and is 510mm x 700mm x 1000mm (Or about 20" x 27.5" x 39").

The hope is to eventually enclose the entire bot. Though this may seem to be in direct violation of [Stratasys' patent][4], we have been careful not to step on its toes. Our motion system (Both the gantry and the Z axis) will lie within the heated build chamber. We also have components that cannot withstand temperatures greater than 140° C, so we will never heat our chamber above 150° C (as specified in the patent).

Being able to enclose the chamber means that we can print with ABS and HIPS, as well as other high warp plastics. We can also go the opposite direction, and be able to refrigerate our chamber. Not useful for plastics, but if chocolate was to ever come through those nozzles... Well, that's for a later post.

Stay tuned! 

[1]: https://github.com/jacobtomlinson/carte-noire
[2]: http://corexy.com/
[3]: https://github.com/jetty840/Sailfish-MightyBoardFirmware
[4]: https://www.google.com/patents/US6722872