# LGhubReverseEng

## Problem
I'm a big user of [Shadow Cloud](https://shadow.tech/fr/) computer and one of the negative part of these cloud computer is you can't use profile with the physical keyboard/mouse. 

This means light and macros. 

One of the way to make this works would be that Shadow itself start using the real HID keyboard/mouse of physical computer. I guess it's not even possible on their side, and I don't really see why they would care for such a useless feature. 

## Solution
One of the way I thought of making it works somehow is by making a modded LGHub made with two option. 

One server (basically the cloud computer) and one client (the physical computer). 

When a profile is set on the server, the client will start using the profile. 

For this to be done, I have to understand how LGHub app set the profile, then edit this part of the code to add a function that will basically send the profile to the client. 

## Legal 

I guess any of these research are purely illegal, and this github can be taken down at any moment. Nothing made here is my property, and I'll try to put respective licenses whenever I can. This is a one man made research, for a really specific idea, but I know that any research publicly posted can lead to abuse. Just contact me if you're Logitech and want it removed please. 
