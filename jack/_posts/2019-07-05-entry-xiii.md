---
layout: post
title: Entry 13 - Main Menu Additions
description: >
  Taking a break from the tilemap kerfuffle this week, I talk about some additional options I've added to the main menu.
author: S00171013
---

This week I decided to look into adding graphics options to my options menu, as I was quite fatigued with my tilemap
roadblock. More below.

# Graphics Quality & Resolution Options

![New Video Options](/assets/img/post_images/jack_images/week-13-new-options.png){:.lead}
A showcase of the new video options I've added to my options menu.
{:.figure}

First off, I added a drop-down for Graphics quality. This was a simple enough affair as changing the game's graphics
quality is a simple line of code in Unity. The most I had to do was ensure that my drop-down options exactly 
matched those in Unity's built-in quality presets ("Very Low", "Low", "Medium", "High", "Very High" and "Ultra".
these presets can be found in Unity's Quality settings). Implementing the manipulation of this drop-down with 
controller input was a simple enough operation too.

Next, I added a drop-down menu for changing the game's resolution. I have it set up so that an array of resolutions
is automatically filled by all of the resolution settings made available by Unity. Each resolution is then iterated
through, converted into a string and added as an option to the resolution drop-down. I also have it set so that 
Unity detects the monitor's current resolution and sets it accordingly. While you can select a resolution with the
controller, unfortunately I can't scroll the drop-down up or down with the controller at the minute. For now, scrolling
with the mouse is necessary. While testing the resolution changes in a built version of the game, an old issue has
reared its ugly head: 

![Resolution Issue](/assets/img/post_images/jack_images/week-13-resolution-issue.png){:.lead}
Despite having my UI settings set as recommended (mentioned in [week seven](https://teamviteza.github.io/jack/2019-05-24-entry-vii/)), this issue still plagues me.
{:.figure}

I thought that I had set my UI to appear the same way on whatever screen it's displayed on. This is not the case. 
I'm stumped as to what I should do. I may need to seek assistance from someone about it.

# A Start on Prototype Animations

Aside from the new menu options, this week I made a start on implementing prototype animations for Katt. My plan is to
add in animation states for Katt, so that the states will be coded and ready for Will when he creates the animation
sprites and adds them in. For now, I've created prototype animations sprites by simply recolouring Katt's idle sprite.

![Prototype Animation Sprites](/assets/img/post_images/jack_images/week-13-prototype-animations.png){:.lead}
A quick look at the test animations I've added in.
{:.figure}

That's about it for this week. Next week I hope to finish off the implementation for Katt's animation state machine.

'Til next time!