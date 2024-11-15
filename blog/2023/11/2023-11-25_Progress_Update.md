# Progress Update 2023-11-25

 [November 25, 2023](https://pydpainter.blogspot.com/2023/11/progress-update-2023-11-25.html "permanent link")

I've been working on a few things with PyDPainter:

## PyDPainter Web Site

I recently got the [PyDPainter web site](https://pydpainter.org) up and running. It is mostly a copy of the content that is already in [GitHub](https://github.com/mriale/PyDPainter) but in an easier-to-read format. I made a script that refreshes this content directly from GitHub when any of it changes. There is also some exclusive content like the [art gallery](https://pydpainter.org/gallery.php), where artists have submitted some amazing pieces of art that they have drawn with PyDPainter. I also included some of my simple squiggles just for balance.

## Running PyDPainter on the Web

There is a project called [PygBag](https://pypi.org/project/pygbag/) that allows you to run Python programs in a web browser. I've tried to get PyDPainter running in the past but with no success. I tried again yesterday and had some limited success showing the initial PyDPainter screen but only occasionally. I hope I can get a version of PyDPainter running on the web soon. That would really lower the barrier to entry for people who would want to try it out. It would also allow me to have it on the [HippoPlayer web site](http://hippoplayer.se/WB.html), whose author has been clamoring for me to get it running.  

## Animation Features

These basic animation features are working now: 

-   load IFF ANIM 5 animations
-   load GIF animations
-   load a series of numbered frames into an animation  
-   support for multiple palettes for animation
-   toolbar at bottom of screen for animations  
-   seeking through animations with a slider, VCR buttons, and keys  
-   insert/remove frames  
    

These things I have left to do: 

-   playback of animations
-   fix the palette bugs that were introduced by having multiple palettes in animations
-   save numbered frames
-   save IFF ANIM
-   save GIF

##  Release 2.0.0 Projection

I hope to release the 2.0.0 version of PyDPainter with animation features in early January if I can resolve some of these things over the holidays. With more free time however also comes more family responsibilities, so the standard disclaimer applies:

<small>Estimates and forward-looking statements refer only to the date when they were made, and we do not undertake any obligation to update or revise any estimate or forward looking statement due to new information, future events or otherwise, except as required by law.</small>
