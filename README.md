![NextMod](https://i.imgur.com/HnT19l1.png)
###### None of these changes are final. This config is still being actively worked on.

### ⚠ For Server Owners:
> NextMod is designed to work with the [Competitive Rework Platform](https://github.com/SirPlease/L4D2-Competitive-Rework) if your server is not set up correctly you may have to alter files in order for the config to work properly!

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
## Version 1.0.1 Changes
> Release Version Wowee! Changes are compared to ZoneMod 1.9.3
#### Infected
* Infected spawn times set to **15 seconds**
* Spit Damage changed from alternating between **2 - 3** to static **3**.
* Spit god-frames set to **6**.
* Hunter claw changed from **6** to **4**.
* Enabled Hunter M2's on **standing** hunters.
* Added Tank Jump Rocks.
* Added a **20 second** cooldown on Tank Jump Rocks.
* Added the Witch.
#### Weapons
* Silenced Uzi reload speed changed from **1.85** to **1.9**.
* Silenced Uzi max move spread changed from **2.15** to **2.05**.
* Unsilenced Uzi damage changed from **22** to **20**.
* Unsilenced Uzi spread per-shot changed from **0.26** to **0.28**.
* Unsilenced Uzi max move-spread from **1.85** to **1.95**.
* Pumpshotgun damage changed from **15** to **14**.
* Pumpshotgun pellets changed from **21** to **20**.
* Chrome-Shotgun damage changed from **16** to **15**.
* Chrome-Shotgun pellets changed from **17** to **15**.
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
* You now get **50** extra bonus for killing the Tank.
* You now get **20** extra bonus for killing the Witch.
#### Small Fixes
* Ready Up footers will no longer stack (such as boss percents when chagned)
### Map Changes
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
#### Hard Rain
##### Mill Escape (Map 3)
* Changed Map distance from **600** to **500**.
---
#### The Parish
##### Park (Map 2)
* Added a small bush on the left side of the park on a tree.
* Added a large bush near the 'tank chip fence' in the park.
* Blocked the 'tank chip fence' in the park from being shot through.
---
#### Swamp Fever
##### Swamp (Map 2)
* Added a large tree by the dock before the plane.
* Added a medium tree before the plan near the shack.
---
#### The Passing
##### Bedlam (Map 2)
* Added props to allow infected to climb onto a small bridge before the final tunnel to the left.
* Changed Map distance from **800** to **700**.
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
###### Please Note: I probably missed a thing or two 😃
