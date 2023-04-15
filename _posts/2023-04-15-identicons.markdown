---
layout: post
title: "Monte-Carlo identicons"
date: 2023-04-15 17:45:00 +0100
categories: posts
---

# Monte-Carlo identicons

I recently made this website and decided it would be nice to have a cool [favicon](https://en.wikipedia.org/wiki/Favicon). However, I really didn't know what deserves this spot. Was I supposed to design my own logo? Or create a small sprite? Or put a tiny picture of myself? I did not know.   

I decided to create a logo-ish thing and go with it. This turned out to be no small task. Imagine, creating a small image 32 pixels in size which needs to relay enough information to the world about your personality, interests, skills and so on. Knowing that if given the opportunity I would probably spend too much time fiddling with Inkscape and GIMP, I decided to program something cool.

I made an [identicon](https://en.wikipedia.org/wiki/Identicon) generator, the output of which I would use as a favicon and quote on quote logo of mine. After some reading, I decided to use my name instead of an IP and to introduce some randomness to the process to allow myself regeneration opportunities if I did not like the inital output.

To create this randomness, I decided to go with a Monte-Carlo algorithm (I have been working on those at work) and a true randomness sampler, curtesy of random.org.

The final product is on my github: [https://github.com/Helios113/identicons](https://github.com/Helios113/identicons)

Here is a sample of what I made:   


<img src="../img.png" alt="img" class="img-responsive" width=50% height=50% />
