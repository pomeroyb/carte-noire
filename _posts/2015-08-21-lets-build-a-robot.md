---
#The layout determines the page type. Enums include 'post, default, page, none'. Enums can be added to "/_layouts"
layout:     post  

#The title of the post. This will be linked on pages. 
title:      Let's Build a Robot!

#Date of Post
date:       2015-08-21 1:24:00

#Author of Post
author:     Brandon Pomeroy

#Not sure what this summary does. Doesn't appear in example posts.
summary:     

#Categories are sort of like folders for Jekyll
categories: Create2

#Choose the thumbnail at the top of the post. Choose from thumbs in "/_data/thumbnails.yml" or from fontAwesome list
thumbnail:  phone

#Setting this to true will publish this page to the site.
published: true

#Tags for searching.
tags:
 - create2
 - telepresence
 - build
---

My beautiful and wonderful fiancée, Brittany, is currently down in Nevada, studying to become a doctor. Unfortunately, I'm still up in Seattle. We Skype fairly often, but one person is always at the mercy of the other -- You only get to look where they are pointing the phone/laptop.

So the problem is that I want to control my view. The solution?

Telepresence robots.

I started searching online, and found a few.

Double Robotics has a slick, minimalist one:
![](/images/create/double_robotics.png)

Suitable Tech has one called "Beam":
![](/images/create/Beam_Tele.jpg)

And iRobot has the "Ava 500" that could double as a battering ram:
![](/images/create/irobot-cisco.jpg)

None of these really fit my price point, and anyway, what fun would it be if I just bought one?

I decided to build my own. I knew that the quality of the bot would depend a lot on the base that allowed it to move. Rather than try to reinvent the wheel (And chassis, and drive system...), I went with an [iRobot Create 2](http://www.irobot.com/About-iRobot/STEM/Create-2.aspx)

![](/images/create/IMAG1316.jpg)

As a quick summary, the Create 2 is a series 600 Roomba that has an exposed serial port and the vacuum removed. You can hook up some electronics to its port, and give the Create2 instructions over serial.

![](/images/create/IMAG1317.jpg)

I initially looked at [pyrobot2.py](http://www.jonathanleroux.org/research/micbots/pyrobot2.py) as the method of Create2 control. Originally written by Damon Kohler for a standard Roomba, it was modified by Jonathan Le Roux to work with the Create 2. Unfortunately, it shows... The API isn't very intuitive to use, and seemed much more in depth than is required for simple Create 2 control. {% twa twa-confused %}

With this in mind, I've been building my own API for controlling the Create 2. [You can find it on GitHub](https://github.com/pomeroyb/Create2Control).

![](/images/create/code_screen.png)

I plan to use this API in conjunction with the [PetBot project](https://github.com/arizzitano/petbot). The gist of the setup is a Node.js server hosted remotely. The Create 2 will have a Raspberry Pi running a local Node.js server, and the pilot (me) will have a web interface that I can log into. Any commands sent to the web interface will get re-broadcasted to the Pi, and then into the Create 2.

As far as the actual video chat, I'm starting with low hanging fruit -- I'm going to continue using Skype for now. I'd like to eventually integrate the video chat and control system together (but realistically that will probably never happen {% twa twa-wink %}). 

The Skype will be running off some kind of tablet... But I haven't really thought that through yet. The Create 2 has a pretty terrible mounting system... you can drill holes through the faceplate and use flush mounted threaded inserts:

![](/images/create/IMAG1318.jpg)

Unfortunately, this faceplate just snaps into the top of the Create 2 with a few tabs. It's not the most sturdy or permanent fixture, so I may have to drill into the Create 2's chassis to mount this thing. We'll see.

Anyway, that's it for now. Stay tuned!