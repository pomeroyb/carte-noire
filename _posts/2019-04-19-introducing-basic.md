---

#The layout determines the page type. Enums include 'post, default, page, none'. Enums can be added to "/_layouts"

layout:     post  



#The title of the post. This will be linked on pages. 

title:      Introducing Basic



#Date of Post

date:       2019-04-19 1:24:00



#Author of Post

author:     Brandon Pomeroy



#Not sure what this summary does. Doesn't appear in example posts.

summary:     



#Categories are sort of like folders for Jekyll

categories: Basic



#Choose the thumbnail at the top of the post. Choose from thumbs in "/_data/thumbnails.yml" or from fontAwesome list

thumbnail:  print



#Setting this to true will publish this page to the site.

published: true



#Tags for searching.

tags:

 - basic

 - pictures

 - build

 - portfolio

---



This is a post on a relatively old project, started November 2015.

<center><blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">I am designing another new 3D printer. Please send help. I can&#39;t stop. <a href="https://t.co/iVjnEU2oMr">pic.twitter.com/iVjnEU2oMr</a></p>&mdash; Brandon Pomeroy (@AchillePomeroy) <a href="https://twitter.com/AchillePomeroy/status/665021833876402177">November 13, 2015</a></blockquote>

<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script></center>



After spending so many hours working on my BIG METAL PRINTER, I felt the need to step back and atone for all the mistakes I had made on the journey. This printer is the result of many late nights modeling. Unlike my last printer, this will be the entire ride in a single post. Get ready for a long one!



To start off, lets see a photo of the finished product:

![](/images/basic/introducing-basic.jpg)


##The Regrets of the Past

One of my biggest regrets of ConfinedXY was rushing the modeling of it. We were so eager to begin building that we basically stopped digital work once the skeleton was finished. We rationalized it by saying *"Oh, it will be easy to just figure out what we need once we have the frame"*. In reality, the opposite happened. Putting together the frame made us complacent, and we never did get around to actually adding a nice skin. It also skewed the BOM and price -- adding a proper skin to ConfinedXY would probably be an additional $1000 or more (Remember that we were building these quantity of 2).  



A secondary issue arose when we went to do wire routing. We didn't really plan out where the wires would go, and our resulting bots look very messy. I am a huge advocate of proper wire routing, and realizing that we were going to have to do so much work just to make the wiring acceptable was very disheartening.  



Neither of these problems exist with Basic, and I attribute that to much more strict and proper planning. It was a lot more work upfront, but was absolutely worth it.  



## The Basic Frame

I have been involved in the [RepRap](http://reprap.org/) scene for quite a while. I built my first printer in Fall of 2012. It was a Clonedel, a Prusa Mendel fork made by Mark Ganter and the UW Solheim Lab. ([I still have a short build log of that on my old site!](http://pomeroyprinting.blogspot.com/2012/09/just-starting-out.html)). 3D printers printing themselves has always been the catchphrase of the RepRap movement, but I've always been a bit disappointed by the application. Sure, the custom brackets can be printed and can save an enormous amount of time, but the user still has to assemble the printer. Printers like the Prusa Mendel/Clonedel, the PrintrBot, and the early MakerBot machines require a tremendous amount of vitamins (Non printed parts) to be assembled. Basic doesn't get away from that completely, but does so more than most.  



In most printers, any printed parts are usually limited to brackets that hold the rods or lasercut panels that form the printer frame. Basic's frame, by contrast, is printed all in one piece, and pops off the machine nearly ready to go (Some built in support material is removed). This made things like wire routing and overall industrial design SUPER EASY in comparison. If I needed a mounting point for cables, I just added one in digitally. If I wanted to chamfer the edge of the printer or emboss some text, it was just a few more features on the model's tree.  



Another great advantage of having a robot fabricate your entire frame is precision. Basic's linear system is a set of MGN9H rails bolted to the frame. Normally when building a printer, you have to carefully align the linear components to avoid binding. With Basic, I *know* that the rails are parallel. It makes assembly much faster and less error-prone.



## The Journey

Alright, enough about *why* I made Basic the way it is, let's get to *how*. Less words, more photos!



<center><blockquote class="instagram-media" data-instgrm-captioned data-instgrm-version="7" style=" background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:450px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"><div style="padding:8px;"> <div style=" background:#F8F8F8; line-height:0; margin-top:40px; padding:50.0% 0; text-align:center; width:100%;"> <div style=" background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACwAAAAsCAMAAAApWqozAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAMUExURczMzPf399fX1+bm5mzY9AMAAADiSURBVDjLvZXbEsMgCES5/P8/t9FuRVCRmU73JWlzosgSIIZURCjo/ad+EQJJB4Hv8BFt+IDpQoCx1wjOSBFhh2XssxEIYn3ulI/6MNReE07UIWJEv8UEOWDS88LY97kqyTliJKKtuYBbruAyVh5wOHiXmpi5we58Ek028czwyuQdLKPG1Bkb4NnM+VeAnfHqn1k4+GPT6uGQcvu2h2OVuIf/gWUFyy8OWEpdyZSa3aVCqpVoVvzZZ2VTnn2wU8qzVjDDetO90GSy9mVLqtgYSy231MxrY6I2gGqjrTY0L8fxCxfCBbhWrsYYAAAAAElFTkSuQmCC); display:block; height:44px; margin:0 auto -44px; position:relative; top:-22px; width:44px;"></div></div> <p style=" margin:8px 0 0 0; padding:0 4px;"> <a href="https://www.instagram.com/p/-MPMsNTRWv/" style=" color:#000; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none; word-wrap:break-word;" target="_blank">New #3dprinter design is coming along nicely. I&#39;ve finished 80% of the work, all that&#39;s left is the other 80%. #160%</a></p> <p style=" color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;">A photo posted by Brandon Pomeroy (@pomeroyb) on <time style=" font-family:Arial,sans-serif; font-size:14px; line-height:17px;" datetime="2015-11-17T15:37:09+00:00">Nov 17, 2015 at 7:37am PST</time></p></div></blockquote>

<script async defer src="//platform.instagram.com/en_US/embeds.js"></script></center>



The real magic of Basic (Other than its printed frame) is the CoreXY gantry and belt configuration that I designed for it. I have not seen this particular belt configuration anywhere else, but it solves a lot of problems that I've experienced with the CoreXY system. It hides the belt crossover to the casual observer (Which just makes the printer look a bit cleaner), and it makes it dead simple to clamp the belts to a carriage. Please note that the above image is an early iteration, and the kinematics are not exactly correct. This was corrected in a later revision.



<center><blockquote class="instagram-media" data-instgrm-captioned data-instgrm-version="7" style=" background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:450px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"><div style="padding:8px;"> <div style=" background:#F8F8F8; line-height:0; margin-top:40px; padding:50.0% 0; text-align:center; width:100%;"> <div style=" background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACwAAAAsCAMAAAApWqozAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAMUExURczMzPf399fX1+bm5mzY9AMAAADiSURBVDjLvZXbEsMgCES5/P8/t9FuRVCRmU73JWlzosgSIIZURCjo/ad+EQJJB4Hv8BFt+IDpQoCx1wjOSBFhh2XssxEIYn3ulI/6MNReE07UIWJEv8UEOWDS88LY97kqyTliJKKtuYBbruAyVh5wOHiXmpi5we58Ek028czwyuQdLKPG1Bkb4NnM+VeAnfHqn1k4+GPT6uGQcvu2h2OVuIf/gWUFyy8OWEpdyZSa3aVCqpVoVvzZZ2VTnn2wU8qzVjDDetO90GSy9mVLqtgYSy231MxrY6I2gGqjrTY0L8fxCxfCBbhWrsYYAAAAAElFTkSuQmCC); display:block; height:44px; margin:0 auto -44px; position:relative; top:-22px; width:44px;"></div></div> <p style=" margin:8px 0 0 0; padding:0 4px;"> <a href="https://www.instagram.com/p/-RQETXzRdK/" style=" color:#000; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none; word-wrap:break-word;" target="_blank">My basic #3dprinter design has an LCD screen and controller now.</a></p> <p style=" color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;">A photo posted by Brandon Pomeroy (@pomeroyb) on <time style=" font-family:Arial,sans-serif; font-size:14px; line-height:17px;" datetime="2015-11-19T14:20:57+00:00">Nov 19, 2015 at 6:20am PST</time></p></div></blockquote>

<script async defer src="//platform.instagram.com/en_US/embeds.js"></script></center>



Here's a great example of being able to keep both function and form while designing Basic. The SmartRap Full Graphics controller has its SD card slot on the left hand side of the screen, but I wanted the display to be on the right side of the machine (Since I am right handed). I was able to cut a small pocket into the frame, and get the best of both worlds.



<center><blockquote class="instagram-media" data-instgrm-captioned data-instgrm-version="7" style=" background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:450px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"><div style="padding:8px;"> <div style=" background:#F8F8F8; line-height:0; margin-top:40px; padding:50.0% 0; text-align:center; width:100%;"> <div style=" background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACwAAAAsCAMAAAApWqozAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAMUExURczMzPf399fX1+bm5mzY9AMAAADiSURBVDjLvZXbEsMgCES5/P8/t9FuRVCRmU73JWlzosgSIIZURCjo/ad+EQJJB4Hv8BFt+IDpQoCx1wjOSBFhh2XssxEIYn3ulI/6MNReE07UIWJEv8UEOWDS88LY97kqyTliJKKtuYBbruAyVh5wOHiXmpi5we58Ek028czwyuQdLKPG1Bkb4NnM+VeAnfHqn1k4+GPT6uGQcvu2h2OVuIf/gWUFyy8OWEpdyZSa3aVCqpVoVvzZZ2VTnn2wU8qzVjDDetO90GSy9mVLqtgYSy231MxrY6I2gGqjrTY0L8fxCxfCBbhWrsYYAAAAAElFTkSuQmCC); display:block; height:44px; margin:0 auto -44px; position:relative; top:-22px; width:44px;"></div></div> <p style=" margin:8px 0 0 0; padding:0 4px;"> <a href="https://www.instagram.com/p/-syu7mTRcW/" style=" color:#000; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none; word-wrap:break-word;" target="_blank">My #3dprinter is called &#34;Basic&#34;.</a></p> <p style=" color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;">A photo posted by Brandon Pomeroy (@pomeroyb) on <time style=" font-family:Arial,sans-serif; font-size:14px; line-height:17px;" datetime="2015-11-30T07:03:21+00:00">Nov 29, 2015 at 11:03pm PST</time></p></div></blockquote>

<script async defer src="//platform.instagram.com/en_US/embeds.js"></script></center>



As an added bonus, that area is perfect for some branding! I embossed the printer's name onto the machine.



I don't have any images here, but I also built in cable management. I wanted to see no more than 2 inches of wire at any time. I integrated printed channels into the back of the machine that hid the wires from view, which worked out beautifully!



## The Printing

Just over a month after my first tweet about Basic, the printing had begun. The first step was to print just the base, to make sure that the electronics fit correctly. MakerBot Desktop told me that the print time would be only 10 hours...



<center><blockquote class="instagram-media" data-instgrm-captioned data-instgrm-version="7" style=" background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:450px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"><div style="padding:8px;"> <div style=" background:#F8F8F8; line-height:0; margin-top:40px; padding:50.0% 0; text-align:center; width:100%;"> <div style=" background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACwAAAAsCAMAAAApWqozAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAMUExURczMzPf399fX1+bm5mzY9AMAAADiSURBVDjLvZXbEsMgCES5/P8/t9FuRVCRmU73JWlzosgSIIZURCjo/ad+EQJJB4Hv8BFt+IDpQoCx1wjOSBFhh2XssxEIYn3ulI/6MNReE07UIWJEv8UEOWDS88LY97kqyTliJKKtuYBbruAyVh5wOHiXmpi5we58Ek028czwyuQdLKPG1Bkb4NnM+VeAnfHqn1k4+GPT6uGQcvu2h2OVuIf/gWUFyy8OWEpdyZSa3aVCqpVoVvzZZ2VTnn2wU8qzVjDDetO90GSy9mVLqtgYSy231MxrY6I2gGqjrTY0L8fxCxfCBbhWrsYYAAAAAElFTkSuQmCC); display:block; height:44px; margin:0 auto -44px; position:relative; top:-22px; width:44px;"></div></div> <p style=" margin:8px 0 0 0; padding:0 4px;"> <a href="https://www.instagram.com/p/_UxVYQTRVy/" style=" color:#000; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none; word-wrap:break-word;" target="_blank">Well that test print took way longer then I thought it would.</a></p> <p style=" color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;">A photo posted by Brandon Pomeroy (@pomeroyb) on <time style=" font-family:Arial,sans-serif; font-size:14px; line-height:17px;" datetime="2015-12-15T19:40:45+00:00">Dec 15, 2015 at 11:40am PST</time></p></div></blockquote>

<script async defer src="//platform.instagram.com/en_US/embeds.js"></script></center>



Alright, so that was slightly off. But the print finished, and things mostly fit:

<center><blockquote class="instagram-media" data-instgrm-captioned data-instgrm-version="7" style=" background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:450px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"><div style="padding:8px;"> <div style=" background:#F8F8F8; line-height:0; margin-top:40px; padding:50.0% 0; text-align:center; width:100%;"> <div style=" background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACwAAAAsCAMAAAApWqozAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAMUExURczMzPf399fX1+bm5mzY9AMAAADiSURBVDjLvZXbEsMgCES5/P8/t9FuRVCRmU73JWlzosgSIIZURCjo/ad+EQJJB4Hv8BFt+IDpQoCx1wjOSBFhh2XssxEIYn3ulI/6MNReE07UIWJEv8UEOWDS88LY97kqyTliJKKtuYBbruAyVh5wOHiXmpi5we58Ek028czwyuQdLKPG1Bkb4NnM+VeAnfHqn1k4+GPT6uGQcvu2h2OVuIf/gWUFyy8OWEpdyZSa3aVCqpVoVvzZZ2VTnn2wU8qzVjDDetO90GSy9mVLqtgYSy231MxrY6I2gGqjrTY0L8fxCxfCBbhWrsYYAAAAAElFTkSuQmCC); display:block; height:44px; margin:0 auto -44px; position:relative; top:-22px; width:44px;"></div></div> <p style=" margin:8px 0 0 0; padding:0 4px;"> <a href="https://www.instagram.com/p/_VMBxjzRUi/" style=" color:#000; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none; word-wrap:break-word;" target="_blank">But it was a moderately successful test! Found a few areas that needs looser tolerances, but overall not bad.</a></p> <p style=" color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;">A photo posted by Brandon Pomeroy (@pomeroyb) on <time style=" font-family:Arial,sans-serif; font-size:14px; line-height:17px;" datetime="2015-12-15T23:34:00+00:00">Dec 15, 2015 at 3:34pm PST</time></p></div></blockquote>

<script async defer src="//platform.instagram.com/en_US/embeds.js"></script></center>



<center><blockquote class="instagram-media" data-instgrm-captioned data-instgrm-version="7" style=" background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:450px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"><div style="padding:8px;"> <div style=" background:#F8F8F8; line-height:0; margin-top:40px; padding:50.0% 0; text-align:center; width:100%;"> <div style=" background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACwAAAAsCAMAAAApWqozAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAMUExURczMzPf399fX1+bm5mzY9AMAAADiSURBVDjLvZXbEsMgCES5/P8/t9FuRVCRmU73JWlzosgSIIZURCjo/ad+EQJJB4Hv8BFt+IDpQoCx1wjOSBFhh2XssxEIYn3ulI/6MNReE07UIWJEv8UEOWDS88LY97kqyTliJKKtuYBbruAyVh5wOHiXmpi5we58Ek028czwyuQdLKPG1Bkb4NnM+VeAnfHqn1k4+GPT6uGQcvu2h2OVuIf/gWUFyy8OWEpdyZSa3aVCqpVoVvzZZ2VTnn2wU8qzVjDDetO90GSy9mVLqtgYSy231MxrY6I2gGqjrTY0L8fxCxfCBbhWrsYYAAAAAElFTkSuQmCC); display:block; height:44px; margin:0 auto -44px; position:relative; top:-22px; width:44px;"></div></div> <p style=" margin:8px 0 0 0; padding:0 4px;"> <a href="https://www.instagram.com/p/_VOcWGzRX_/" style=" color:#000; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none; word-wrap:break-word;" target="_blank">Nicely organized electronics.</a></p> <p style=" color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;">A photo posted by Brandon Pomeroy (@pomeroyb) on <time style=" font-family:Arial,sans-serif; font-size:14px; line-height:17px;" datetime="2015-12-15T23:55:06+00:00">Dec 15, 2015 at 3:55pm PST</time></p></div></blockquote>

<script async defer src="//platform.instagram.com/en_US/embeds.js"></script></center>



Time for the real thing. After a few false starts, we were cruising!



<center><blockquote class="instagram-media" data-instgrm-captioned data-instgrm-version="7" style=" background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:450px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"><div style="padding:8px;"> <div style=" background:#F8F8F8; line-height:0; margin-top:40px; padding:50.0% 0; text-align:center; width:100%;"> <div style=" background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACwAAAAsCAMAAAApWqozAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAMUExURczMzPf399fX1+bm5mzY9AMAAADiSURBVDjLvZXbEsMgCES5/P8/t9FuRVCRmU73JWlzosgSIIZURCjo/ad+EQJJB4Hv8BFt+IDpQoCx1wjOSBFhh2XssxEIYn3ulI/6MNReE07UIWJEv8UEOWDS88LY97kqyTliJKKtuYBbruAyVh5wOHiXmpi5we58Ek028czwyuQdLKPG1Bkb4NnM+VeAnfHqn1k4+GPT6uGQcvu2h2OVuIf/gWUFyy8OWEpdyZSa3aVCqpVoVvzZZ2VTnn2wU8qzVjDDetO90GSy9mVLqtgYSy231MxrY6I2gGqjrTY0L8fxCxfCBbhWrsYYAAAAAElFTkSuQmCC); display:block; height:44px; margin:0 auto -44px; position:relative; top:-22px; width:44px;"></div></div> <p style=" margin:8px 0 0 0; padding:0 4px;"> <a href="https://www.instagram.com/p/_r5iLJTRTo/" style=" color:#000; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none; word-wrap:break-word;" target="_blank">Less than 2 days until my #3dprint finishes!</a></p> <p style=" color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;">A photo posted by Brandon Pomeroy (@pomeroyb) on <time style=" font-family:Arial,sans-serif; font-size:14px; line-height:17px;" datetime="2015-12-24T19:14:56+00:00">Dec 24, 2015 at 11:14am PST</time></p></div></blockquote>

<script async defer src="//platform.instagram.com/en_US/embeds.js"></script></center>



Here's a quick timelapse that I recorded and put on the intentional3D YouTube Channel. You can find our "official" blog post about Basic [here](http://intentional3d.com/introducing-basic/)... this post is just my personal ramblings!



<center><iframe width="560" height="315" src="https://www.youtube.com/embed/uLgjq5cj-rg?rel=0" frameborder="0" allowfullscreen></iframe></center>



So after a total of 149 hours, 35 minutes, and 33 seconds, the Basic frame was completely done!That's just over 6 days of straight printing! This was definitely my longest and most stressful print I have ever done.



<center><blockquote class="instagram-media" data-instgrm-captioned data-instgrm-version="7" style=" background:#FFF; border:0; border-radius:3px; box-shadow:0 0 1px 0 rgba(0,0,0,0.5),0 1px 10px 0 rgba(0,0,0,0.15); margin: 1px; max-width:450px; padding:0; width:99.375%; width:-webkit-calc(100% - 2px); width:calc(100% - 2px);"><div style="padding:8px;"> <div style=" background:#F8F8F8; line-height:0; margin-top:40px; padding:50.0% 0; text-align:center; width:100%;"> <div style=" background:url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACwAAAAsCAMAAAApWqozAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAMUExURczMzPf399fX1+bm5mzY9AMAAADiSURBVDjLvZXbEsMgCES5/P8/t9FuRVCRmU73JWlzosgSIIZURCjo/ad+EQJJB4Hv8BFt+IDpQoCx1wjOSBFhh2XssxEIYn3ulI/6MNReE07UIWJEv8UEOWDS88LY97kqyTliJKKtuYBbruAyVh5wOHiXmpi5we58Ek028czwyuQdLKPG1Bkb4NnM+VeAnfHqn1k4+GPT6uGQcvu2h2OVuIf/gWUFyy8OWEpdyZSa3aVCqpVoVvzZZ2VTnn2wU8qzVjDDetO90GSy9mVLqtgYSy231MxrY6I2gGqjrTY0L8fxCxfCBbhWrsYYAAAAAElFTkSuQmCC); display:block; height:44px; margin:0 auto -44px; position:relative; top:-22px; width:44px;"></div></div> <p style=" margin:8px 0 0 0; padding:0 4px;"> <a href="https://www.instagram.com/p/_1BAq4zRen/" style=" color:#000; font-family:Arial,sans-serif; font-size:14px; font-style:normal; font-weight:normal; line-height:17px; text-decoration:none; word-wrap:break-word;" target="_blank">#3dprint successful! 140.5 hours and 3.97 pounds of filament, plus tons of footage for a timelapse. Time to assemble!</a></p> <p style=" color:#c9c8cd; font-family:Arial,sans-serif; font-size:14px; line-height:17px; margin-bottom:0; margin-top:8px; overflow:hidden; padding:8px 0 7px; text-align:center; text-overflow:ellipsis; white-space:nowrap;">A photo posted by Brandon Pomeroy (@pomeroyb) on <time style=" font-family:Arial,sans-serif; font-size:14px; line-height:17px;" datetime="2015-12-28T08:13:26+00:00">Dec 28, 2015 at 12:13am PST</time></p></div></blockquote>

<script async defer src="//platform.instagram.com/en_US/embeds.js"></script></center>

## Assembly
Once the printing was finished and my belts and pulleys showed up, it was time to put it all together. Thanks again to modeling everything, down to the nuts and bolts, I knew exactly what I would need.

First remove the part from the printer and remove any support material
![](/images/basic/IMAG1472.jpg)

Appreciate the branding
![](/images/basic/IMAG1473.jpg)

Linear motion was achieved with MGN9H rails
![](/images/basic/IMAG1474.jpg)

Captive nuts hold the rails in place
![](/images/basic/IMAG1477.jpg)

The rails were very easily installed
![](/images/basic/IMAG1479.jpg)

Next came the motors, and the cables were threaded through the buit in wire management
![](/images/basic/IMAG1484.jpg)

Bearing idlers were assembled and installed
![](/images/basic/IMAG1488.jpg)

The X-Axis crossbeam was assembled
![](/images/basic/IMAG1490.jpg)

The Z-Axis mount was assembled and installed
![](/images/basic/IMAG1495.jpg)

The Z-Axis motor with integrated leadscrew and crossbeam were installed
![](/images/basic/IMAG1500.jpg)

The extruder carriage was installed. It includes the X-Axis endstop as well as strain relief for the extruder and hotend cables
![](/images/basic/IMAG1502.jpg)

Belts were then wrapped and the CoreXY gantry was completed
![](/images/basic/IMAG1510.jpg)

I added a spare MakerBot Extruder
![](/images/basic/IMG_20160119_190153.jpg)

And lastly threw in some electronics
![](/images/basic/IMG_20160108_213701.jpg)

I quickly calibrated Basic (Which was fairly easy, given that I used 20 tooth pulleys for X and Y, a sane leadscrew for Z, and a known extruder) and printed my first part: A small box
![](/images/basic/IMG_20160123_204555.jpg)

I printed another test, Yoda-lite
![](/images/basic/IMG_20160125_225217.jpg)

And lastly a photoshoot with a delicious PSL
![](/images/basic/IMG_20160124_014723.jpg)

##The Regrets of the Future
Overall I am very, very pleased with how this project came out. It's incredibly satisfying to take a project from nothing to completion over the course of a few months, and I think my meticulous planning while working in CAD helped this. There were definitely hiccups along the way, however. 3D printing every part of this printer (Including the print bed itself!) proved to be a detriment to actually printing parts on the machine. The X crossbeam is a little wobbly due to the natural flex of the plastic. I had to slow my printing speed and acceleration way down to deal with this.

I also wish I had added even more wire management than I did -- I modelled the placement of the various components like the PSU and RAMPs board, but neglected to model the wires themselves. It ended up working out, but was a bit of a mess.

## Moving Forward
This particular model is the *Basic #PSL*. In a project for work I built out a *Basic #NoFilter*, which moved from a printed frame to a folded sheet metal one. That particular model unfortunately stalled out, and the current model I am tinkering with is *Basic #TBT*, which will have some neat features like dissolvable support material and a really beautiful interface. Hopefully I'll be writing a blog post about that one day!