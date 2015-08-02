---
#The layout determines the page type. Enums include 'post, default, page, none'. Enums can be added to "/_layouts"
layout:     post  

#The title of the post. This will be linked on pages. 
title:      Things Are Heating Up

#Date of Post
date:       2015-08-02 2:58:00

#Author of Post
author:     Brandon Pomeroy

#Not sure what this summary does. Doesn't appear in example posts.
summary:     

#Categories are sort of like folders for Jekyll
categories: ConfinedXY

#Choose the thumbnail at the top of the post. Choose from thumbs in "/_data/thumbnails.yml" or from fontAwesome list
thumbnail:  fire

#Setting this to true will publish this page to the site.
published: false

#Tags for searching.
tags:
 - photos
 - confinedxy
 - printer
 - build
 - plate
 - hot
---

In order to print plastics like ABS and HIPS, it's pretty crucial to have a heated build plate. I'm taking it one step further, and plan to eventually heat the entire chamber. By keeping the entire chamber at an elevated temperature, the printed part ends up having far less internal stresses due to thermal gradients. When the print is done, the model cools down as a whole, distributing stress and shrink across the entire part.

Many printers use a PCB heated build plate to generate the necessary heat. I've never really liked them, for three reasons:
1. They tend to run off of 12/24v, and run at a very high amperage, putting undue stess on the power supply.
2. They tend to warp due to the thermal gradient, so it's hard to get good adhesion to a heat spreader.
3. Many popular designs are made by hobbyists. This is one of the parts of the printers that can **FUCKING BURN YOUR HOUSE DOWN**, so I believe in going with an engineered solution.

With that in mind, I am using a 600W silicone heat mat from Keenovo. This mat comes with an adhesive that should firmly attach it to my aluminum heat spreader. I'll probably reinforce it with some extra fiberglass tape.

![](/images/confinedXY/IMAG1273.jpg)

This mat runs off of 120VAC, so it's switched on and off via a relay (controlled by the MightyBoard).

![](/images/confinedXY/IMAG1274.jpg)

It's pretty nice because it has integrated power leads and thermistor, but its safety features are lacking. I took the advice of Keenovo's support representative, and had them send a thermal fuse along with it.

![](/images/confinedXY/IMAG1276.jpg)

This fuse is wired in series with one of the power leads, and is adhered the mat. If the mat gets hotter than 142°C, this fuse will trip, and power will be cut.

I'm considering putting in a few more failsafes, but this is a nice start. Given that my heat bed is the thermal equivalent of 15 heater block cartridges (600 watt bed vs 40 watt heater cartridge), it doesn't hurt to have some redundancies. Especially considering the [consequences of runaway heaters](https://www.youtube.com/watch?v=xIA2yzb16Gk).

