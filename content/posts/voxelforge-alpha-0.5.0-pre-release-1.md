+++
title = 'VoxelForge Alpha 0.5.0 Pre Release 1'
date = 2024-09-12T20:39:12+01:00
featured_image = '/images/a-0_5-pre-1.png'
+++

Well. After an unavoidable crash was reported on 5.9.0 we've decided to go ahead and do this week's snapshot, a bit early. This one is packed with bug fixes, bundle improvements, new advancments, and More!

## Experimental

### Bundles
  - Bundles can now be dyed 16 different colors.
  - Bundles can now have the drop item selected by left-click.
    (Editor's Note: This is due to engine limitations, of not allowed formspec tooltips)
  - Bundles can now be crafted.
  - Bundles now use only one item per color rather than 64 items per.
  - Colored Bundles can be crafted using dye and a bundle, of any color.
    (Editor's Note: You can use bundles with items in them, however don't be worried if the color of the bundle doesn't change after crafting, just take out an item and insert it and it'll be the correct color.)
  - Bundles have a compat alias allowing for old bundles to be updated to the new ones.
    (Editor's Note: To properly get the texture change, please rightclick until all items are out of the bundle.)
  - Textures have been updated again to better match MC, while complying with the 20% difference rule.

## Changes
  - Added Armadillo
    (Editor's Note: Armadillo's are static models due to no-one in the dev team knowing animation.)
  - Updated aliases to work properly.
  - From now on after this version, worlds will crash upon changing versions. With the message to make sure the user makes a backup, or wishes to procede
    (Editor's Note: Don't worry, this will be toggleable in the next update. To reload the world after the crash, simply exit the crash window and attempt to open the world.)
  - Added Ominous Vaults
  - Added Bees
  - Added Torchflowers
  - Added Skeleton Horse Traps.
  - Added new jock_to_other function in vlf_mobs api
  - Added new jock_detach_and_resize function in vlf_mobs api
  - Arrows now can be set on fire
  - Added invis itemframes to match the MC property that allows for them invis
  - Added new biome: Meadow
  - Added new biome: Grove Ocean

## Advancements
  - Added New: Caves and Cliffs Advancement.
  - Added New: Isn't it Scute? Advancement.
  - Added New: Star Trader Advancement.
  - Added New: Suit Up Advancement.
  - Added New: Cover Me with Diamonds Advancement.
  - Added New: Cover Me in Debris Advancement.
  - Added New: Ol' Betsy Advancement.
  - Added New: Eye Spy Advancement.
  - Added New: Sound of Music Advancement.
  - Added New: Light as a Rabbit Advancement.
  - Added New: Is It a Bird? Advancement.
  - Added New: Is It a Balloon? Advancement.
  - Added New: Is It a Plane? Advancement.
  - Added New: Lighen Up Advancement.
  - Added New Over-Overkill Advancement.
  - Added New Under Lock and Key Advancement.
  - Added New Revaulting Advancement.


## Performance
 - Fireflies now have a smaller chance of spawning

## Bugs Fixed
 - [VLF-196](https://github.com/VoxelForge/VoxelForge/issues/196) Axes can't remove oxidation from copper.
 - [VLF-197](https://github.com/VoxelForge/VoxelForge/issues/197) Mace no longer has any effect from enhancements.
 - [VLF-198](https://github.com/VoxelForge/VoxelForge/issues/198) If you spam the spyglass then it'll bug out your client, until you reconnect.
 - [VLF-199](https://github.com/VoxelForge/VoxelForge/issues/199) Occasional crash when placing swords in itemframes.
 - [VLF-201](https://github.com/VoxelForge/VoxelForge/issues/201) Crash when using 5.9.0 mt with single biome mapgen.
 - [VLF-204](https://github.com/VoxelForge/VoxelForge/issues/204) Firefly spawners caused any non-air block they were next to to become transparent.



## Downloading the latest release
You can download the latest release at [ContentDB](https://content.minetest.net/packages/VoxelForge/voxelforge)

### Testing New Versions May break your world, Please make a backup to ensure there are no side-effects from the update.

 - Report bugs here:
[VoxelForge Issue Tracker](https://github.com/VoxelForge/VoxelForge/issues)!

- Want to give feedback ?
  - [VoxelForge Feedback Page](https://github.com/VoxelForge/VoxelForge/discussions/141)
