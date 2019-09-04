![NextMod](https://i.imgur.com/HnT19l1.png)
###### None of these changes are final. This config is still being actively worked on.

### ⚠ For Server Owners:
> NextMod is designed to work with the [Competitive Rework Platform](https://github.com/LuckyServ/l4d2_luckylock_server_install_public/tree/master/cfg) if your server is not set up correctly you may have to alter files in order for the config to work properly!

### ℹ About NextMod
> NextMod is heavily influenced by community feedback, if you have a suggestion don't feel afraid to get at [me](https://steamcommunity.com/id/lonesome-spoon/).
 
NextMod is a competitive config based upon the community favourite ZoneMod, but it also brings back some of our old favourite features from other mods such as the Witch, and jump rocks, as well as some new features!

#### Main Features / Reasoning Behind Them
---
**Jump Rocks** 
Jump Rocks were added due to community requests. Tank Jump Rocks can only be done every 20 seconds. So once every 2 rocks or so.

**The Witch**
The Witch was added due to community requests and to add a bit of dynamic to the game.

**Witch Voting**
 Witch Voting was added due to the mixed feelings on Witches. Not everybody agrees with having them in the game, so adding an option to disable it only seems fair.

**Sound Removing**
Sound Removing was added to save our ears and to remove the unfair advantage some players get when they use the `snd_restart` command, while others do not.

**Health Bonus System**
The new health bonus system was added due to the amount of complaints I've heard about damage bonus. Bonus will now be determined by Perma-Health, Temp-Health, Pills, and whether or not Tank/Witch have been killed. For further detail, please read [here](https://camo.githubusercontent.com/d86c7163fdf887d943947ba2accf7e74c32632e7/68747470733a2f2f692e696d6775722e636f6d2f63517471747a312e706e67) or [here](https://github.com/LuckyServ/sourcemod-plugins/blob/master/source/l4d2_health_temp_bonus.sp)

**Fixed Spawn Rotations**
Spawn rotations are now handled by a plugin rather than the bestest engine ever. This means that infected spawn rotations will be more consistent, predictable and reliable, benefiting both teams!

---
## Version 1.0.3 Changes
#### Infected
* Infected spawn times set to **15 seconds**.
* Max common changed from **30** to **28**.
* Spit Damage changed from alternating between **2 - 3** to static **3**.
* Spit god-frames set to **6**.
* Hunter claw changed from **6** to **4**.
* Enabled Hunter M2's on **standing** Hunters.
* Added Tank Jump Rocks.
* Added a **20 second** cooldown on Tank Jump Rocks.
#### Weapons
> Weapons are still under heavy development, if you think something is too OP let me know!
* Silenced Uzi reload speed changed from **1.85** to **2.1**.
* Silenced Uzi spread per-shot from **0.32** to **0.30**.
* Unsilenced Uzi reload speed changed from **1.74** to **1.75**.
* Unsilenced Uzi damage changed from **22** to **20**.
* Unsilenced Uzi spread per-shot changed from **0.26** to **0.29**.
* Unsilenced Uzi max move-spread from **1.85** to **1.95**.
* Increased SMG Ammo from **650** to **750**.
* Pumpshotgun pellets changed from **21** to **20**.
* Chrome-Shotgun pellets **17** to **16**.
* Removed all Mini-guns/Turrets.
* Limited Melee's to **3**
* Only blunt melees will spawn outside saferoom.
    * Baseball Bats, Cricket Bats, Guitars, and Frying Pans.
* One Fireaxe will spawn in saferoom.
#### General/Gameplay
* Fixed SI Spawn Rotations. (Created by: [Sir](https://github.com/SirPlease/))
* Added option to enable/diable the Witch via voting.
* New Bonus System. (Created by: [LuckyLock](https://github.com/LuckyServ))
* Tank Rocks are now lag-compensated. (Created by: [LuckyLock](https://github.com/LuckyServ))
* Removed Generator/Lift/Plane/Tractor/Fuel Truck/"Ambient" Explosion/Heartbeat Sounds.
* It will now be announced when a teammate is black and white.
* Tanks can now see hittable glows through objects/from far away.
* Added the Witch.
* You now get **20** extra bonus for killing the Witch. (To discourage rushing past it)
#### Small Fixes
* Ready Up footers will no longer stack (such as boss percents when chagned)
* Removed throwables from spawning on some custom maps.
* Fixed issue where tank hittables weren't incapping god-framed survivors.
### Map Changes
> Maps are the same as ZoneMod 1.9.4 besides the mentioned changes.
---
#### Dead Center
##### Hotel (Map 1)
* Removed background explosion sounds.
---
#### Dark Carnival
##### Highway (Map 1)
* Added a hittable Police Car near the saferoom.
* Added a HUMVEE by the tree near the saferoom.
* Added an Ambulance where survivors take the roof rock Tank.
* Added a hittable car where survivors take the roof rock Tank.
##### Coaster (Map 3)
* Removed Coaster Sounds.
---
##### Hard Rain
##### Mill Escape (Map 3)
* Changed Map distance from **600** to **500**.
##### Milltown Escape (Finale)
* Removed the damn storm sounds.
---
#### The Parish
##### Park (Map 2)
* Added a small bush on the left side of the park on a tree.
* Added a prop to make climbing onto the tree easier for infected.
* Added a large bush near the 'tank chip fence' in the park.
* Blocked the 'tank chip fence' in the park from being shot through.
##### Cemetery (Map 3)
* You can still do spit damage at the sewer drop. :D
##### Quarter (Map 4)
* Fixed an out of map glitch.
---
#### The Passing
##### Bedlam (Map 2)
* Blocked Tank Spawn past **70%**.
* Changed Map distance from **800** to **500**.
* Fixed those wanky stairs.
* Added a box stack to make climbing onto the RV easier for tank.
---
#### The Sacrifice
##### Docks (Map 1)
* Changed Map distance from **700** to **500**.
##### Barge (Map 2)
* Changed Map distance from **700** to **500**.
---
#### Dead Air
##### Runway (Finale)
* Removed Plane + Crashing Plane SFX
* Removed Crashing Plane Screen Shake
---
#### Blood Harvest
##### Corn Field (Finale)
* Added props for extra SI spawns.
---
###### Please Note: I probably missed a thing or two 😃
