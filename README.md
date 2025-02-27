
<p align="center"><img src="https://i.imgur.com/sylzjp8.png"></p>

[![Unknown](https://img.shields.io/badge/Untested_Seed-565656?logo=awesomelists&logoColor=ffffff)](https://)


Goemon Randomizer: Hard Mode is a collection of randomly generated seeds that activate **Hard Mode**, significantly increasing the difficulty of the game.  

### What is Hard Mode?  
Hard Mode introduces the following challenge:  

> *"Quadruples the damage taken from all sources. As a result, most enemies will deal a full 2 hearts of damage, meaning you can only survive 2 hits with the starting five hearts. This gives restaurants, shops, and cat dolls more importance throughout the game. Note that helmets and armor will still negate the full damage of a hit, making them much more valuable. A side effect of this option is that any damage taken during the Sweets Minigame is a one-hit kill."*

Additionally, other settings can be toggled to further increase the challenge, including randomized maps and doors for an extra layer of difficulty.  

## Getting Started  
Check the [latest releases](https://github.com/EmeraldVoid/Goemon-Hardcore-Randomizer/releases] to get the most up-to-date version of this challenge.  

## Rules & Settings  

### **Mandatory Rules**  
These settings must be enabled for Hard Mode to function correctly:  

- **`hard_mode: True`** – This is the core setting and must remain enabled.  
- **`avoid_softlocks: True`** – Prevents softlocks. This is set to `True` by default in `mn64_settings.yaml`, but double-check that it is enabled.  
- **`enable_debug: True`**  
- **`fix_bad_maps: True`**  

### **Optional Rules**  
For additional challenge and convenience, you can enable the following:  

- **`auto_mash: True`** – Speeds up long cutscenes by progressing them automatically.  
- **`start_flute: True`** – Start with Yae recruited and Yae’s flute in your possession, updating the maze logic accordingly. This is recommended to reduce excessive backtracking, as the flute is not guaranteed to be obtainable otherwise. *(Note: Castles will no longer be warp locations; you can only warp to Goemon’s house, teahouses, and inns.)*  
- **`flute_anywhere: True`** – Allows the flute to be used in any room, including castles and shops. If `start_flute` is enabled, this slightly improves seed generation times; if `start_flute` is disabled, it greatly increases generation times. It is recommended to enable both `start_flute` and `flute_anywhere` together.  
- **No Fortune Dolls** – You cannot collect any fortune dolls during your run (unless unavoidable).  
- **`sasuke_mode: True`** – Start as Sasuke and Yae instead of Goemon and Ebisumaru, with maze logic updated accordingly. Cutscenes remain unchanged, but Ebisumaru can be recruited by viewing Yae’s cutscene, and Goemon by viewing Sasuke’s. *(Enabled by default to give Sasuke some time in the spotlight.)*  

## Good Luck!  
Try out some of the **Hardcore Seeds** and test your skills. Be sure to check for updates and share your experiences!

