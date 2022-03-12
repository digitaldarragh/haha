# haha
Home Assistant House Automation. My automation is nothing special. It's inspired by many others. 

I am making this repository public mainly because I'm standing on the shoulders of giants. I'm not doing anything particularly special, but who knows. Perhaps someone might look at this and find something that I'm doing that they can apply to their own HomeAssistant installation. 

## Objective
I want this to be a smart home. That means not needing to touch switches when someone walks in or out of a room. I want things to just happen automatically.  So I use motion sensors and triggers based on time of day or Alexa enabled routines to make things happen instead. 

## Influences
*  [Slacker labs](www.slacker-labs.com) for my TTS components. Specifically from reading his Git Hub repository, I clearly understood how to include jinja scripts. 
*  [HomeAssistant on Discord](https://discord.com/invite/home-assistant) That group of people are just fantastic. When I was just starting off with HomeAssistant I asked a few newby questions there and was always given a great answer.  

## Home layout
I have a small house. In Ireland it would be quite typical.  3 bedrooms, two home offices, a living / family room, a kitchen, a shed, a hall way and an upstairs landing.  Most of the rooms excluding the childrens bedroooms have more than one light. So you will find that I have created groups for these to make things much easier. 

## Technology
I'm running HomeAssistant on a HP workstation running Ubuntu 20.4.  It's running with Supervisor support within a Docker container.  This is not a supported configuration, but it works really well for me.  Attached to this HP workstation is a Combee II Zigbee USB stick. All of the devices in my home excluding the obvious sonos etc are connected via Zigbee.  I will not be using ZWave or SmartHome etc. I have decided to focus exclusively on Zigbee.  I will also avoid devices running on the wireless network when possible. This is personal choice. There's nothing wrong with these other communication protocols. 

## Devices used. 
*  Bulbs from Aldi, Ikia and Philllips. Some are colour changing but most are ambient white bulbs. 
*  A Friant smoke alarm
*  Several Aqara light switches. But one is connected so far
*  Several Ikea wall plugs
*  2 extension leads
*  Five Phillips Motion sensors
*  Three magnetic sensors
*  A Sonos Play 5, Sonos play 1 and a sonos connect. 
*  One Echo dot and one Echo show. 
*  Several IOS devices including watches, iPhones, iPads and a Mac
*  A Ring video door bell

## Admission. 
I'm using HomeAssistant for about five months as of the writing of this readme. So don't expect ground shattering stuff.  What I'm doing is working for me but it might be quite simple compared to others out there.  I also have many plans to improve my setup but some fo these require additional motion sensors, automated blinds etc.  That all costs money and I have other priorities right now. 
