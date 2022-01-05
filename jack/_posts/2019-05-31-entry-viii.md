---
layout: post
title: Entry 08 - Background Battles
description: >
  A small segment on my attempts to create a scrolling background for the level I'm working on.
author: S00171013
---

This week's been a mixed one, in truth. It was devoted to creating a stage background for my level, one that looked
appropriate and would be easily understood by the player when they perceive it. I've had some small successes, and 
I now have a parallax scrolling background for my level. That being said, my severe lack of skills when it comes 
to creating digital art (as well as traditional art) has me feeling that my background could be made a lot better.

# Parallax Scrolling

My first task in this endeavour was to find out how to achieve parallax scrolling for my level's background. After
some searching, I found some resources online that helped me achieve this. I also found a sample background I 
could use for testing. It can be seen below.

![Sample Background](/assets/img/post_images/jack_images/week-8-sample-background.png){:.lead}
The Sample Background for use with this [Parallax tutorial](https://youtu.be/zit45k6CUMk) from [Dani](https://www.youtube.com/channel/UCIabPXjvT5BVTxRDPCBBOOQ/about). Thanks Dani!
{:.figure}

Getting the parallax scrolling working was a simple enough affair, but there's still an element missing. With the
sample I tested, it is intended for the background to be parented to the scene's camera. This has the unfortunate
side-effect of having the background staying on the same elevation no matter how far up or down the player has 
travelled through the stage (since the background is always following the camera). I took a long hard look at
how backgrounds are handled in games like _Sonic_ and _Freedom Planet_. From what I've found, even the first
Sonic game had its backgrounds changing their elevation according to the height the player is at in the 
level. To better illustrate what I mean, take a look at the image below.

![BG Elevation Example](/assets/img/post_images/jack_images/week-8-elevation-example.png){:.lead}
In these screenshots from the original Sonic, take a look at the orange line I've placed atop the mountain in the background. Here we can see that the background's elevation has increased from the first image to the next.
{:.figure}

For now, I've decided to un-parent the background from the Unity camera and extend the background's verticality.
Now the background will remain at a fixed elevation while still scrolling left and right as the player progresses
through the stage. In future, if I can think up a better solution for the background, I will add it to my scene.
For now, this current solution should suffice.

# Creating a New Background

Despite my aformentioned lack of art skills, I endeavoured to create my own stage background this week. I created it
in [Adobe Illustrator](https://en.wikipedia.org/wiki/Adobe_Illustrator) using the sample background parallax 
background mentioned above as a reference. Not much to mention here, getting the rough shape was easy enough,
the hardest part was making the images completely transparent by removing all the remaining white pixels 
that MS Paint couldn't get rid of. The finished product can be seen below.

![Proto-background](/assets/img/post_images/jack_images/week-8-proto-background.png){:.lead}
My prototype background. It's not much, but it should do the trick for now.
{:.figure}

![Proto-background](/assets/img/post_images/jack_images/week-8-proto-elevation.png){:.lead}
A sample of the background's elevation changing in-game. Not final by any means, but good for testing.
{:.figure}

That's all for this week, next week I want to get back to coding because, for myself, doing art is arduous and 
unsatisfactory.

'Til next time.