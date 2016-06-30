---
layout: project_post
title: Doggy Treat Dispenser
preview: images/pi.jpg
category: project
---

I decided to build a treat dispenser for my dog, Zoey. The end product will be a web app that lets a visitor dispense the treat and watch Zoey come and eat it. Eventually, I'd like to also add different visual cues to make Zoey do tricks to receive the tricks. But, one step at a time.

I'll also be trying a new format for these two week projects. Instead of writing a post at the end, I'm going to make an effort to write short posts each time I work on the project-- like a journal (I prefer "journal" over diary #manly). Hopefully, this will help me stay focused too!

<!--more-->

Sketches (06-27-2016)
======================

I began the process by drawing up what I had in mind after googling around for some DIY treat dispenser instructions. Most seemed more complicated than I wanted so I had to venture out on my own. I want to build something simple (prepare for ASCII sketch!)

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
              | |
              | | <-- tube holding treats
       _      | |
servo | |     | |
--------------   -- <-- disc with hole 
------------------
{             ||| | <-- cylinder used to measure treats
------------------
-  --------------- <-- disc with hole
       | | <-- servo
        -
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

All the above would be driven with a Raspberry Pi. The idea was that the top disc would rotate and drop treats in to the cylinder. Later, the bottom disc would rotate to the cylinder hole to dispense the measured amount of treats. Unfortunately, this didn't go exactly as planned...see below.

Prototyping (06-28-2016)
=========================

My past experience with building robots (and their failures) really helped me this time. I knew that building the structure would be a struggle for me, so I decided to start by building a paper prototype. The materials I used were styrofoam, foam board, and a plastic bottle I found laying aroudn the house. Total cost: $5!

As expected, I made a ton of mistakes building out what I had sketched. For example, I didn't think about how the servo positions would affect the design; the servo size, gaps created by the gear, and rotation angles caused me to have to adjust by making the bottom disc larger. It was a huge benefit having a paper prototype because I could easily cute and scrap things within minutes.

Check out the paper prototype working below:

<iframe src="//giphy.com/embed/xT8qBp7x2BSCa7Mv5u" width="240" height="425" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="http://giphy.com/gifs/xT8qBp7x2BSCa7Mv5u">via GIPHY</a></p>

Building the Final Version (???)
===========================

To be continued...
