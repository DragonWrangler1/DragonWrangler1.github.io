+++
title = 'VoxelForge Beta 0.5.0 Release Candidate 1'
date = 2024-09-22T23:32:07+01:00
featured_image = '/images/b-0_5-rc-1.png'
+++

Today we are updating api features, and we are taking bundles out of the experimental setting, and more.

## Changes
  - Removed Cavegen api, due to some unstable activity, and performance reasons.
    (Editor's Note: It would occasionally fully crash MT.)
  - Bundles have been removed from experimental settings.
  - Added a setting to toggle whether or not phantoms can spawn.
  - Animated the armadillo
    (Editor's Note: This is the first animation done by VoxelForge developers. Expect bugs)
  - Added new *randomly_turn* api feature to mobs
  - players can now fall as far as y-120 and still get the *Caves & Cliffs* Advancement.
  - Added phantom membrane.
  - 
## Node Ids
  buttons have been renamed to mesecons_button:*button material name*_button_off/_on

## Bugs Fixed
 - [VLF-184](https://github.com/VoxelForge/VoxelForge/issues/184) Upward bubble columns are too powerful.
 - [VLF-185](https://github.com/VoxelForge/VoxelForge/issues/184) It sometimes rains in caves.
 - [VLF-213](https://github.com/VoxelForge/VoxelForge/issues/213) Phantoms don't die in sunlight.
 - [VLF-214](https://github.com/VoxelForge/VoxelForge/issues/214) Phantoms spawn no matter the time of day.
 - [VLF-215](https://github.com/VoxelForge/VoxelForge/issues/215) Foxes spawn mid-air.
 - [VLF-217](https://github.com/VoxelForge/VoxelForge/issues/217) Crash with lingering status effects.

## Downloading the latest release
You can download the latest release at [ContentDB](https://content.minetest.net/packages/VoxelForge/voxelforge)

### Testing New Versions May break your world, Please make a backup to ensure there are no side-effects from the update.

 - Report bugs here:
[VoxelForge Issue Tracker](https://github.com/VoxelForge/VoxelForge/issues)!

- Want to give feedback ?
  - [VoxelForge Feedback Page](https://github.com/VoxelForge/VoxelForge/discussions/141)
