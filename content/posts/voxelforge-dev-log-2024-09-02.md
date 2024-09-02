+++
title = 'VoxelForge Development log 2024-09-02'
date = 2024-09-02T21:39:34+01:00
+++
## Introduction

Hello. Today we'll be talking about all the progress made over the last month of development. So let's dive right in.

## Experimental Features

### Bundles
Bundles have been introduced under an experimental setting allowing users to put up to 64 items in them at one time and drop them on right-click. They have been improved a good bit since they were first introduced back in Alpha 0.4.0 - Pre 4.

 - Bundles no longer drop items with extra metadata meaning that they can stack perfectly with items not dropped by bundles
 - Bundles use a technique that allows similar functionality to minecraft. Meaning that you can insert items directly into the bundle via the inventory.
 - Bundles are creative only, and under an experimental setting meaning there is no recipe for them yet.
 - Unlike MineCraft's bundles. The Developers of VoxelForge feel like swords and throwable items should be able to stack up to 64 items in the bundle.

## Changes
 - mcl_potions api has been rewritten as vlf_entity_effects, giving a new range of effects, and api features.
   - added new 1.21 effects.
   - fixed saturation not being powerful enough.
 - Plants now have meshes that make them at the edge of the node rather than the center.
 - Added Vaults.
   - Vaults can now glow too.
 - Added Very WIP tridents.
 - A setting has been added so that users can now customize the size of the ingame font.
 - Farmers now have brims in their hats.
 - More deterministic structures
 - Ruined portals are less likely to generate with multiples in one chunk.
 - Added Basic Powdered snow nodes
   Editor's Note: Powdered snow was made in a hurry, it will be revisited soon.
 - Spiders can now scale walls.
 - __builtin:item Now have their itemstring cleared when being picked up or merging with other items.
 - Added a hud overlay for those underwater.
 - Add loot to strongholds.
 - Added Tripwire

## Codebase.
 - Cleaned up the code, removing all luacheck warnings.

## Performance
 - Removed most music and put it into an external mod.

## Bugs Fixed.
 - Fix zombies and skeletons floating.
 - Fix iron golems spawning underwater.
 - Rooted dirt and hanging vines issues fixed.
 - fixes recovery compasses dropping as regular ones.
 - fixes a crash with unknown enhancements.
 - fixes first loot table not being used in shipwrecks.
 - fix vlf_entity_effects images not loading.
 Editor's Note: Upon the potions rewrite crispiebacon realized that the images were all misnamed.
 - fix sqlite database running out of memory when spawning villages.
 - fix golem spawn.
 - fix crash when spawning village.
 - fix crash due to undefined values in breach and density.
 - fix duplicated bowls when eating sus stew.
 - fixed over abundance of breeding hearts.
 - Wind charge no longer sets velocity to entities like chests and signs.
 - Fix item frame item dupe bug.
 - Mace wind burst enchantment always active.
 - fix crash when right clicking horses.
 - undead mobs shouldn't burn if they wear armor.
 - Items dropped by bundles now properly stack with items not dropped by bundles.

## More News
Even with all those changes we're still working hard to get even more content. Keep on the lookout for the next big update in the coming weeks.

## Downloading the latest release
You can download the latest release at [ContentDB](https://content.minetest.net/packages/VoxelForge/voxelforge)

### Testing New Versions Make break your world, Please make a backup to ensure there are no side-effects from the update.

 - Report bugs here:
[VoxelForge Issue Tracker](https://github.com/VoxelForge/VoxelForge/issues)!

- Want to give feedback ?
  - [VoxelForge Feedback Page (Issue Tracker)](https://github.com/VoxelForge/VoxelForge/issues)



 Well that's it for this week, see y'all soon!

