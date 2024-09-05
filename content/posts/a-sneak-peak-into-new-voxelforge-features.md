+++ 
title = '[DeepDive] A Sneak Peak Into New VoxelForge features.' 
date = 2024-09-05T01:47:34+01:00 
featured_image = '/images/sneakpeak.png' 
+++

Get your armor ready, and prepare your weapons, cause we've got big news.

You ever get tired of reaching the world edge in an hour ? 
You tired of beautiful terrain generation suddenly cut off ?

Well recently we've forked the MT engine and we're giving it an update. 
We're changing the world size from 16 bit integer (31007 map limit) to 32 bit integer (meaning the generation number is a whopping 2,147,483,008 (much much much bigger)) 
We'll use MineCraft for comparison. The limit of MineCraft java edition is 60 million X 320 X 60 million. VoxelForge should be 4 billion X 4 billion X 4 billion (however NOT bug free).  So from 60k to 4 billion. However the catch is that currently player physics bugs start at 350,000 meaning that the player has 700,000 x 700,000 x 700,000 So still large without bugs, however, not 4 billion when a player reached +1,000,000 then the database freezes (which will bring a device with a memory of 16 GB to a halt in a matter of minutes). Which brings us to the downside. Database size, which is why we will not be making that giant number the average. And to prove we've done it, the image provided shows the player at X 100,000

However that's not all. We've also been working on updating liquids to be more minecraft like, and also we've been adding, emissive textures, better shaders, animated inventory images, and more.
Stay tuned for more details on development.
