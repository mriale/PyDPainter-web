# Animation Debugging for Fun and Profit!

 [February 13, 2024](https://pydpainter.blogspot.com/2024/02/animation-debugging-for-fun-and-profit.html "permanent link")

Wait... "profit?" Well, maybe intangible profit since I _am_ giving this away. 😀 I do get pleasure in making something usable that makes other people happy, though.  

## Animation Changes Things

My spare time in the last few weeks has been filled with debugging code in PyDPainter that used to make sense and work just fine, but now that animation features are being added, it breaks. Some of these things are as simple as changing the resolution (Screen Format) of the screen. It used to scale the screen and reduce the number of colors if needed and everything was fine. Now it has to repeat the same thing for every frame of an animation. I haven't gotten to that part yet. Another thing is backgrounds: should there be a separate background for every frame of the animation? I think that's what I'll end up doing because it will also make way for a feature to load a video to trace over. How should stencils behave? Create or remake the stencil for every frame? Or are stencils something that are better left in the past because we have enough memory to do layers now?  

So it isn't just adding animation features that I have been working on -- it's also fixing the things that don't play well with animation and extending other tools to work better in the context of an animation. This process has taken longer than I expected, so I missed my "early January" goal to release version 2.0.0. It turns out that this will take some time to do right.

## Big Bang

If I implement these basic animation features and rush the release out the door, will people take a look at PyDPainter and dismiss it because it doesn't do much? At this point, I am leaning toward the "big bang" approach where I'll wait to release the new version and build up some more features that people would expect for animation. I'd also like to get it all running on the web. These things will ensure a good experience for new people trying out PyDPainter for the first time.

## What's Left?

I'll keep working on the issues list:  
[https://github.com/mriale/PyDPainter/issues](https://github.com/mriale/PyDPainter/issues)

I'll give updates periodically.  

## Keeping up with "develop"

At any time, anybody is free to grab a branch like "develop" at any time and get the latest features along with the latest bugs. I might make a more stable branch that is more like a beta version when I get some of the bugs worked out.
