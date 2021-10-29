## 4.9.0

This update brings with it two things (beyond the regular mod updates),

```diff
+Thaumaturgy - An Enchanting Overhaul
+Yet Another Music Merge
```

because both are amazing, nuff said. Due to the inclusion of Thaumaturgy this update will 
```diff
-will not be save safe and will require a new save due to the vast changes to enchanted items.
```
Just as a friendly reminder, you don't have to update if your currently enjoying a playthrough, keep playing and have fun :)

***ESSENTIAL MODS*** 

^[.NET Script Framework](https://www.nexusmods.com/skyrimspecialedition/mods/21294) [Version 18]

***FIXES***

^[Assorted Mesh Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/32117) [Version 0.32.1]

***INTERFACE*** 

+[Alternate Conversation Camera Plus](https://www.nexusmods.com/skyrimspecialedition/mods/40722) [Version 2.4.6]

***LIGHTING***  - Moved Interior Floating Fog Remover above Relighting Skyrim with Window Shadows to let RS effects win.

-Relighting Skyrim

+[Relighting Skyrim SSE with Window Shadows](https://www.nexusmods.com/skyrimspecialedition/mods/8586) [Version 2.0.0WS]

***GRAPHICS BASELINE*** 

-Unofficial Material Fix - High Poly Project Patch - (Included in updated High Poly Project)

^[High Poly Project](https://www.nexusmods.com/skyrimspecialedition/mods/12029) [Version 5.0] (Same FOMOD Install)

***GAMEPLAY OVERHAULS*** 

^[Adamant - A Perk Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/30191) [Version 5.2.1]

^[Aetherius - A Race Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/26686) [Version 2.6.0]

***COMBAT & ENCOUNTERS*** 

^[Dragon War - A Dragon Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/51310) [Version 1.3.1]

***LOOT & CRAFTING***

-Enchanting Adjustments Updated (Replaced by Thaumaturgy)

-Open World Loot - AVL Iron and Steel Addon - Enchanting Adjustments Patch.esp

-Open World Loot - AVL Morrowind Glass Addon - Enchanting Adjustments Patch.esp

-Open World Loot - AVL Nordic Addon - Enchanting Adjustments Patch.esp

+[Thaumaturgy - An Enchanting Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/57138) [Version 1.0.2]

+[Thaumaturgy - An Enchanting Overhaul - WACCF Patch](https://www.nexusmods.com/skyrimspecialedition/mods/57138) [Version 1.0]

+Open World Loot - AVL Iron and Steel Addon - Thaumaturgy Patch.esp

+Open World Loot - AVL Morrowind Glass Addon - Thaumaturgy Patch.esp

+Open World Loot - AVL Nordic Addon - Thaumaturgy Patch.esp

***MUSIC*** - New Seperator with new mods below

+[Musical Lore - Soundtrack Mod by Nir Shor](https://www.nexusmods.com/skyrimspecialedition/mods/3200) [Version 1.2]

+[The Northerner Diaries - Immersive Edition](https://www.nexusmods.com/skyrimspecialedition/mods/28108) [Version 1.2] 

+[Still - Skyrim Inspired Music](https://www.nexusmods.com/skyrimspecialedition/mods/19401) [Version 1.01]

+[Hun Lovaas - Skyrim Fan-Made Combat Music](https://www.nexusmods.com/skyrimspecialedition/mods/16123) [Version 1.0]

+[Melodies of Civilisation - Skyrim Fan-Made Music](https://www.nexusmods.com/skyrimspecialedition/mods/30014) [Version 1.01]

+[Around the Fire - Skyrim Fan-Made Music](https://www.nexusmods.com/skyrimspecialedition/mods/36144) [Version 1.0]

+[Dawnguard Music Overhaul - Skyrim Fan-Made Music](https://www.nexusmods.com/skyrimspecialedition/mods/48613) [Version 1.0]

+[Yet Another Music Merge](https://www.nexusmods.com/skyrimspecialedition/mods/48725) [Version 1.0]

***SOUND FX*** 
^[Dragon War - Audio Overhaul for Skyrim Patch](https://www.nexusmods.com/skyrimspecialedition/mods/51310) [Version 1.3]



ENB Preset Modifications: Under [WATER] - DisableDistantReflections from true to false.

Created a Runtime Generated Mod for the files that get generated when you launch the game, this makes it when crash log get generated you will get the "files are in your overwrite" and only then.

***CONFLICT RESOLUTION PATCH***
```diff
-Removed "EnchFierySouls" Object Effect
-Removed "MAG_FrostSlowFFContact" Magic Effect
```
```diff
+[MGEF] MAG_EnchFrostDamageFFContact [0004605B] - Thaum - Audio Overhaul resolve
+[MGEF] MAG_EnchFrostDamageFFContactChaos [0402C46D] - Thaum - Audio Overhaul resolve
+[WEAP] MAG_EnchIronDaggerShock03 [000896CB] - Thaum - Audio Overhaul resolve
+[WEAP] MAG_EnchSteelDaggerFear01A [000A69FF] - Thaum - Audio Overhaul resolve
+[WEAP] MAG_EnchSteelDaggerTurn01B [000A6A16] - Thaum - Audio Overhaul resolve
+[WEAP] MAG_EnchElvenDaggerFire04 [000BE18F] - Thaum - Audio Overhaul resolve
+[BOOK] Letter from Glover [0402AD41] - Fixed ability to pick it up so it can be turn in for the unqiue sapphire.
+[REFR] MountainCliff02_LightSN [STAT:000201F6] -[07009C55] - boulder blocking entrance to White River Watch fixed.
```
