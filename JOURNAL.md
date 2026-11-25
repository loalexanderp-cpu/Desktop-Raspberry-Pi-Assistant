---
title: "Desktop Raspberry Pi Assistant"
github: "Desktop-Raspbeberry-Pi-Assistant"
description: "I am making a mini desktop assistant able to stream music, check the weather, and set alarms."
created_at: "2026-22-11"
total_time: "13h 30min"
---


## November 22, 2026: Initial Design and Ideation (Published on the 24th)

Started working on this project with defining the functions I wanted on the assistant. These included spotify connectivity, alarms, touchscreen display, and wifi connectivity, all built with a Raspberry Pi on Raspberry OS.

I also started doing some research into some designs like this including commercial assistants like Amazon's Alexa or Google's Nest Hub. I planned out the schedule as well ensuring the project can be completed by the New Year. 

This GitHub repository was also set up being made private for now.

![](https://fabricate.hackclub-assets.com/52dc44b996f54b122883bd3b7b3da9b939de81fe6cd685d92abe128106134d84/image-png/image.png)

**Total time spent: 1h**


## November 23, 2026: Planning Objectives and Starting BOM (Published on the 24th)

Continued planning out the objectives for this project. These included budget and also availability to others. Given that this project is meant to be shipped, I want to make it as easy to make as possible by laying out project requirements like making it 3D printed rather than made of aluminium or wood. Limiting tools and equipment to a 3D printer, soldering iron, a screw driver set, and a laptop to push code for the Pi. 

I then moved to planning out the basics for the Bill of Materials. I listed general items like the Raspberry Pi 3B+ which can be changed to newer models, a 7 inch touchscreen which then became a 5" touchscreen, and a 3W speaker module. 

I also added links and started calculating costs as well to make sure I don't blow my budget of $275 AUD.


![](https://fabricate.hackclub-assets.com/0453621364fe8bc0adfe49fc11a72525738833b357719dc4d0abf471e66cfc08/image-png/image.png)

**Total time spent: 1h**


## November 24, 2026: Finishing the BOM and starting PCB design

I finished up the BOM going back and forth on small things like whether I use M3 or M2.5 screws and whether I should upgrade to a Raspberry Pi 4 for additional computing power. 

I still chose to go with the Pi 3B+ however as it is not only cheap, but also available to almost anyone. I want to ensure that everyone could make it by using older, more outdated products but also by using these older products, I can ensure that they can in fact be used for my project.

After producing a rough draft of my BOM I worked on bringing the price down from $295 AUD to $275 minimum. I did this by checking other retailers and replacing or removing unnecessary parts from the BOM. In the end I was able to save $60 going to $235.34 without shipping which is about $155.85 USD.

After finalising my sensors that I wished to be added, I found their respectable LCSC Electronics part numbers and jumped onto Easy EDA to lay out my schematic. 

A lot of time today was me doing way too much trying to cut a few dollars off every part. Most of the savings made today was from removing things that just weren't required. WHY IS IT ALL SO EXPENSIVE!! 

To ensure everyone would pay a similar price for all materials, I specifically chose to avoid jumping onto a resale market or buy things secondhand or used to ensure everyone receives an equal pricing on their versions of my design.

I also made this repository public.


![](https://fabricate.hackclub-assets.com/f8829053fd94dc803d65d7ecc7bd03242d5f929b8f3e0aa441488be87594a75a/image-png/image.png)
![](https://fabricate.hackclub-assets.com/053abdf2280e827231a44a0d24ec75c878ae3ed5688ca21f596c5d185ae4934f/image-png/image.png)

**Total time spent: 7h 12m**

# November 25, 2026: Designing and Starting the PCB Schematic

## PCB Planning ##

### Planning the Connections ###

I started working on planning out all the requirements for each of the sensors and the amplifier and compiled them all into one large table (Below is a small part of the whole thing). This took the majority of the time spent on this project today as there was a lot of research ensuring there wasn't a connection skipped or an accidental connection to another pin causing a short. 

![](https://fabricate.hackclub-assets.com/244d6d778b9d1b7622cfacc9cacf55cf2e3c51bfac84219b89d80b0021447116/image-png/image.png)

### Prepping the Schematic ###

After that was completed, I worked on prepping everything to start wiring. I laid out the Net Flag connections, GND, 3V3, and 5V connections and organised everything into 6 sectors for each of the sensors, GPIO header, and speaker amplifier. This didn't take long as everything was planned out already from the previous step.

![](https://fabricate.hackclub-assets.com/e6e0257045c0c6f11ea70545b4c7fbc29b549ea59b4b439806e77f153c8464cb/image-png/image.png)


### Commencing Wiring ###

Finished off the day with a bit of wiring. Connected the general power distribution to the GPIO header and the three sensors I am using. There isn't much to talk about as it was pretty straightforward as it was just using the table but I also colour-coded everything for it to look nicer and spot potential issues. 

Organisation is Key!!

![](https://fabricate.hackclub-assets.com/e0906f005309662242131640f450b097e879d5fc3381c9be930d7ef3a2042f90/image-png/image.png)

**Total time spent: 4h 18m**
