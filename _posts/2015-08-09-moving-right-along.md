---
#The layout determines the page type. Enums include 'post, default, page, none'. Enums can be added to "/_layouts"
layout:     post  

#The title of the post. This will be linked on pages. 
title:      Moving Right Along

#Date of Post
date:       2015-08-09 1:24:00

#Author of Post
author:     Brandon Pomeroy

#Not sure what this summary does. Doesn't appear in example posts.
summary:     

#Categories are sort of like folders for Jekyll
categories: ConfinedXY

#Choose the thumbnail at the top of the post. Choose from thumbs in "/_data/thumbnails.yml" or from fontAwesome list
thumbnail:  truck

#Setting this to true will publish this page to the site.
published: true

#Tags for searching.
tags:
 - photos
 - confinedxy
 - printer
 - build
---

When you have a 3D printer, you start to take the ability to make complex shapes for granted. Need a bracket that fits three different sizes of aluminum extrusion? No problem -- Just model it up and hit "print"!

Having to mill parts from a solid block is much more labor intensive, and requires more forethought. I tried to design as few machined parts as possible, but there were some areas where it was a necessary evil. For example, the extruder carriage mount.

![](/images/confinedXY/IMAG1280.jpg)

We needed this part to mount to the carriage on the linear rail, and could not find an aluminum U-Channel that worked well... so we made our own.

![](/images/confinedXY/IMAG1279.jpg)

![](/images/confinedXY/IMAG1284.jpg)

I'm very grateful that my printer build partner has both machining skill and access to a mill. Though the above part is technically the only part that *requires* a mill, there were other parts that benefitted from the accuracy of the mill.

![](/images/confinedXY/IMAG1281.jpg)

A lot of these holes could have been made on a drill press, but it would have taken a lot longer to line them all up.

![](/images/confinedXY/IMAG1282.jpg)

The mill also helped with our leadscrew nuts, which were not *exactly* the size we were expecting.

![](/images/confinedXY/IMAG1283.jpg)

Unfortunately, we didn't catch this error soon enough to backport it to our water jet files... so....

![](/images/confinedXY/IMAG1288.jpg)

Good enough! {% twa twa-sweat-smile %}

Anyways, next step is assembling the Z-Axis. First the cross beam...

![](/images/confinedXY/IMAG1287.jpg)

Then we attached the top plate. It's held on with three M5 bolts, with springs and thumbscrews for easy levelling.

![](/images/confinedXY/IMAG1285.jpg)

Then we loosely affixed the leadscrew nuts.

![](/images/confinedXY/IMAG1289.jpg)

Finally, moment of truth.

![](/images/confinedXY/IMAG1290.jpg)

Oh.... yes.

![](/images/confinedXY/IMAG1291.jpg)

From the top.

![](/images/confinedXY/IMAG1292.jpg)

From the front.

![](/images/confinedXY/IMAG1293.jpg)

From below.

![](/images/confinedXY/IMAG1294.jpg)

Beautiful! {% twa twa-smiley %}

What's coming next? Belts! Stay tuned!