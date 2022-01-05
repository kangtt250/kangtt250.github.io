---
layout: post
title: Entry 18 - Orienteering
description: >
  A post on the issues of ensuring Katt and her blaster behave properly when it comes to directional input.
author: S00171013
---

This week I've managed to fix the rotation issue I had been having with Katt before we took our break. More below.

# Handling an airborne Katt's rotation.

As I mentioned previously I had an issue where Katt would remain slanted at a slope's angle even if she jumped
off said slope. I had implemented a method to revert Katt to a neutral rotation upon becoming airborne, but it didn't
seem to be affecting anything. I soon realised that I had set it so that Katt should rotate by my "orientationH"
value, which could be either 0 or -180. I realised that rotating by 0 would obviously have no effect. I soon fixed
the issue and now Katt appears upright in mid-air as she should.

![Revert Rotation Method](/assets/img/post_images/jack_images/week-18-revert-rotation-method.png){:.lead}
The old method (top) and the new improved method (bottom).
{:.figure}

![Method in Action](/assets/img/post_images/jack_images/week-18-method-in-action.png){:.lead}
An explanation of what I mean when I want Katt to stand upright when airborne.
{:.figure}

# Katt's New Blaster

We had a basic projectile firing system implemented previously, but it was quite basic. This week I started 
improving the implementation of Katt's blaster by giving it a sprite and ensuring shots fired spawn in their 
appropriate place. I also made the bullets smaller to fit the blaster sprite's size. Here's a closer look.

![Katt's Blaster](/assets/img/post_images/jack_images/week-18-katt-blaster.png){:.lead}
Katt's blaster.
{:.figure}

For a long while the weapon fire mechanic would not work with the newer "s_katt" model I had been working with, 
projectiles wouldn't fire, though they would fire if I used the older "proto_katt" model. First I realised that
the bullet sprite's draw order was 0, meaning that every other sprite (including the backgrounds) would be drawn
in front of it, rendering it invisible. After altering this value, I noticed the projectile would only appear 
briefly when fired. Soon the reason dawned on me: s_katt's got sensors on either side of her, the projectile would
hit the hitbox of one of these sensors and  disappear as soon as it spawned. Fixing the issue was simple enough, 
just a case of ensuring in code that no projectile would collide with any object tagged "Sensor".

It took some fiddling to get the blaster to keep its orientation synced up with Katt's so that it's always firing
in the right direction. I'm still working at it because currently I have an issue where jumping for some reason 
throws the blaster's rotation out of sync with Katt's rotation, which can cause bullets to fire behind her. Once
I've fixed this issue I then want to ensure projectiles fire from the direction that Katt is slanted at. 

As an aside, I also want to mention that I have merged all of the old movement script's functionality into my S 
Movement script, rendering the old one defunct.

That's all for this week, next week I'll be continuing work on movement and hopefully fixing the blaster's 
projectile direction issue. Wish me luck! Only two weeks to go!

'Til next time!