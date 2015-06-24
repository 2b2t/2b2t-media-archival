------------------------- 5.0.0 - MC v1.7.10 ------------------------

Features:

- Updated OptiFine.
- World Downloader added.
- Added module named "Logout Spot". This module will draw a tracer and ESP to where players logout.
- Easily add/remove players to/from your friends list by clicking their name on the Radar.
- FastSprint has now been merged with Sprint.
- Added module named "AutoFarm". This module will harvest/plant whatever you specify
- Added commands "autofarm crop <wheat/carrot/potato/sugarcane>" and "autofarm mode <harvest/plant>".
- AutoRespawn now respawns the player much faster!
- Added module named "AutoApple". Automatically eats G'Apples during PVP only.
- Added module named "Speed". Successful speed bypass. 2.6 times regular speed.
- Added module named "Jesus". Walk on water bypass.
- Added module named "Recover". Removes all negative potion effects instantly.
- Added module named "Blink". Synthetic lag switch.
- Added module named "HitSpheres". Display hit sphere around players (varies on your aura range).
- Added module named "SafeAura". This will attack ALL players that hit you, even friends. Cache refreshed every 5 seconds.
- Added NoCheat mode. Switches modules between their NoCheat modes and non-NoCheat modes.
- Improved Step. Now works much faster and less bugs.
- Improved NoSlowdown greatly, now applies for ladders and allows for climbing ladders just like in Beta.
- Added command to grab a players previous names using ".names <user>"
- Added sub-command to ".friends" to convert all saved friends to their UUID's using ".friends convert".
- External module loading (similar to Bukkit plugins). Now you can add your own modules to Adolf.
- Added the ability to load external modules from websites.
- Added module named "AutoMine", works like Creative Control modules in other clients, but in survival.
- Added multiple fail safes for all Automated methods.
- Ported Pyrobyte's mcmultibot into Adolf. Minor modifications made to improve performance and reliability.
- Added module named "AntiCactus", never be damaged by a cactus again.
- Added module named "MultiAura", hit multiple entities at the EXACT same time.
- Improved KillAura. Improved prioritizing and improved performance.
- Improved NoFall. Now bypasses NoCheat+ on a large majority of servers (NCP config dependent).
- Fly bypass added as a seperate module, works slowly , doesn't allow movement upwards, damage will cause you to teleport back.
- Added whatever the fuck else I've missed, I don't even know anymore...

Visuals:

- Small change to chat.
- All friends are now displayed in Green on the Radar, and everyone else in Red.
- Soup count will not show on Info tab, unless AutoSoup is enabled.
- Improved ESP rendering for doublechests.
- Improved Radar whilst in Freecam (now displays distance between the freecam entity and other players).
- Improved ESP rendering altogether, ESP's now render faster and are less "resource heavy".
- Small changes to sliders (decimal values now display to 2 decimal places, instead of just 1).
- Display health above all players.
- NameTag rendering method(s) changed and improved.
- Added whatever the fuck else I've missed, I don't even know anymore...

Bugfixes/Misc:

- Cleaned up some code (also removed unused code).
- Fixed command "tp", which has only been broken since 4.2.0
- Removed NameTags module.
- Removed Nuker (until fixed).
- Removed FastFall.
- Waypoints will now save and load.
- Fixed a speed modifier bug when Freecam and Flight are on together whilst in water/lava.
- Fixed Flight bug whilst using SafeWalk.
- Fixed a rare bug causing the client to crash when logging into a server with SafeWalk on.
- Removed logging in using Session ID.
- Made client compatible with Yggdrasil login method.
- Renamed "No Knockback" to "AntiVelocity".
- Removed FastHeal.
- Removed all Derp modules.
- 1.7.2 update broke xray, now fixed.
- Max value for PVPLog has been lowered from 20 to 19.
- Cleaned and improved performance of AutoArmor. Basically removed all Spaghetti.
- Repaired Nuker, now works flawlessly.
- Improved Ghetto NoFall, now works flawlessly.
- Created new module loading system with some inspiration from V for performance reasons, saving me time in future and various mod description reasons.
- Implemented DarkMagician6's EventAPI.
- Friends list now work in correlation with a players UUID so players stay on your friends list after namechanges.
- Implemented multiple protection methods to the client to prevent being leaked/cracked in preperation for P2P release.
- Linked Adolf to webserver. Many automated modules shall be moved to the Adolf website for purchase.
- Donators (people who purchase Adolf AND donate) can see how many people on their server are using Adolf, but not WHO, unless playing 2b2t. DEV's can see all.
- Donators (people who purchase Adolf AND donate) & DEV'scan remove themselves from the count of amount of people using Adolf on a server.
- ONLY donators (people who purchase Adolf AND donate) & DEV's may now use external module loading.
- Whatever the fuck else I've missed, I don't even know anymore...

TODO:

- Update to 1.8?


----------------------------- 4.2.0 - MC v1.6.4 -----------------------------

Features:

- AutoArmor has been added back to the client.
- Improved Xray commands.
- New Creative Xray Menu, opened using the UP arrow.
- Displaying Horse stats on Horse Inventory.
- Added module named "HorseJump". Max jump height with a horse everytime.

Visuals:

- Improvements to nametags (scaling, see-through walls and seeing nametag whilst sneaking.

----------------------------- 4.1.3 - MC v1.6.4 -----------------------------

Features:

- Added module named "AutoFish".

Bugfixes/General Fixes:

- Keybinds and Macros working again!

----------------------------- 4.1.2 - MC v1.6.4 -----------------------------

Bugfixes/General Fixes:

- Visual fix stopping glint effect rendering over enchanted items whilst using PlayerESP.

----------------------------- 4.1.1 - MC v1.6.4 -----------------------------

Bugfixes/General Fixes:

- AutoUpdate fixed and now saves to /versions/.

----------------------------- 4.1.0 - MC v1.6.4 -----------------------------

Features:

- Changes to spam delay (increased delay).

Visuals:

- Improved Chat (friend changes).
- New Main Menu.
- Small changes to bordered rectangles.
- Changes to positioning of console.

Misc:

- Changed Change Log name to "Detailed Change Log".

Bugfixes/General Fixes:

- Info Tab now displays Freecam Entity coordinates whilst in Freecam.


----------------------------- 4.0.0 - MC v1.6.2 -----------------------------

Features:

- New ClickGUI, opened using the current GRAVE key. Previous GUI opened using RSHIFT.
- Added an option to edit existing alt accounts.
- Added Friend Manager to AdolfOptions.
- Added module named "Jimmie Rustler". Just stand near Note Blocks and watch!
- Added module named "QuakeCraft Aura". A KillAura designed for QuakeCraft.
- Improved KillAura.
- Improvements to Dolphin (now moves forward whilst in water).
- Improvements to NightVision (yes it's possible).

Visuals:

- Potion effect icons now displayed ingame.
- Console has been given a small animation upon load.
- Small change to tracers.

Misc:

- Changed Aura Range default value.

Bugfixes/General fixes:

- Fixed bits of item rendering over players.
- AutoTool fix for sword (same with KillAura).
- AutoWalk fixed.
- Small GUI fixes with new font (allignment, size, etc).

---------------------------------- 3.0.0 - MC v1.6.2 ----------------------------------

NOTE! Some features will most probably be buggy since I have kind of been forced to update, they'll be fixed in a later patch.

Features:

- Obvious update to 1.6.2.
- Newest version of OptiFine added.
- New chat command. "spawntp" to teleport to spawn on any server.
- Minor improvements to AutoEat, also allowing Golden Apples to be eaten whilst AutoEat is
 enabled (not autoeating apples).

- Display messages in chat, notifying the user when a player has logged into, or out of, the server they're playing.
- Updates to ClickGUI. Tooltips are now shown when hovering over a module, providing a description of the module.
- Added module named "FastFall". Causes the player to fall at lightning speed.
- Renamed "Brightness" to "NightVision", now activates the NightVision potion effect instead of simply increasing gamma.
- New Derp tab in the ClickGUI!
- Added new Predictive Command Console to Adolf. Opens up by pressing "U", keybind replaces NameTags keybind. 
- Added module named "AutoRespawn". Automatically respawns the player.
- Tabbed ingame GUI.


Bugfixes:

- Quite a large fix for the FileManager (loading Modules).
-Small, unnoticeable performance fixes with FileManager (BufferedReader wasn't being closed).

Misc:

- Removed malicious coding I had added to grab a users coordinates and shut down their client.
- Removed protection methods, because, #YOLO #SWAG #DISOBEY.
- Removal of SOME modules which aren't loaded.
- Removed Faction spam.
- Removal of AutoArmour due to not working correctly with a full inventory of armour.
- Small change to radar when players appear.
- GUI Hub has been removed for more space on the ClickGUI.
- TTF font now being used for ingame GUI.
- Now using Ubuntu-B font!
---------------------------------------- 2.2.1 ----------------------------------------

- New spam command, designed to spam on 2b2t.org. Can be toggled off using "toggle spam".
- Improved AutoEat, swaps current held hotbar item for food if none can be found and places back in inventory. Also added slider to change when to eat food.
-Added feature named Auto Armour. If armour slots are empty and the player has armour in their inventory, the armour will be equipped.
- Added feature named PvPLog which will logout the player when the player reaches specified health, which is set as 3 (6) by default.

---------------------------------------- 2.2.0 ----------------------------------------

- Added OptiFine HD Ultra.

---------------------------------------- 2.1.9 ----------------------------------------

- Small patch with bug fixes.

>history note: these bugfixes were bugfixes for the backdoor, this has since been removed.

---------------------------------------- 2.1.8 ----------------------------------------

- VoidFog has been removed.
- Checks length of pickupline before sending to stop being disconnected from server.
- Fixes to SafeWalk, players can now jump as usual whilst using SafeWalk.

---------------------------------------- 2.1.7 ----------------------------------------

- Added a changelog to client and began recording changes.
- Added NoSlowdown mod, disables speed modifiers for the following: Eating, pulling Bow, walking on Soulsand and walking through spiderwebs but not falling.

>history note: this is where the known backdoor was first implemented, has since been removed.
