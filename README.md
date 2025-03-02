
<p align="center"><img src="https://i.imgur.com/sylzjp8.png"></p>

[![Unknown](https://img.shields.io/badge/Untested_Seed-565656?logo=awesomelists&logoColor=ffffff)](https://)

Goemon Hardcore Randomizer is a collection of randomly generated seeds that activate **Hard Mode**, significantly increasing the difficulty of the game.  

## Editions  

There are two **editions** of the challenge:  

- **Goemon Edition** – Start with **Goemon** and **Ebisumaru** as your default characters.  
- **Sasuke Edition** – Start with **Sasuke** and **Yae** instead.  

The core rules of the challenge remain the same across both editions. The main difference is which characters you begin the game with, affecting early-game strategies and routing.  

## What is Goemon Hardcore Randomizer?

Goemon Hardcore Randomizer is a challenge created by Emerald_Void, built using the [Ancient Cave Starring Goemon Randomizer](https://github.com/abyssonym/mn64rando). Inspired by classic challenge modes such as Kaizo, Nuzlockes, and Iron Mario, this randomizer pushes players to their limits. Special thanks to abyssonym for their incredible work on the original tool that makes this challenge possible.

Hardcore Randomizer introduces the following challenge:  

> *"Quadruples the damage taken from all sources. As a result, most enemies will deal a full 2 hearts of damage, meaning you can only survive 2 hits with the starting five hearts. This gives restaurants, shops, and cat dolls more importance throughout the game. Note that helmets and armor will still negate the full damage of a hit, making them much more valuable. A side effect of this option is that any damage taken during the Sweets Minigame is a one-hit kill."*  

Additionally, other settings can be toggled to further increase the challenge, including randomized maps and doors for an extra layer of difficulty.

# What is the objective of the game?
Obtain the four Miracle Items, then use the Pemo Pemo Statue at Ugo Stone Circle to travel to space and defeat the final boss. The Miracle Items are all in their original locations, but there is a setting to start with Miracle Snow already, which is enabled by default.

## Getting Started  
Check the [latest releases](https://github.com/YOUR-REPO/releases) to get the most up-to-date version of this challenge.  

## Rules & Settings  

### **Mandatory Rules**  
These settings must be enabled for Hard Mode to function correctly:  

- **`hard_mode: True`** – This is the core setting and must remain enabled.  
- **`avoid_softlocks: True`** – Prevents softlocks. This is set to `True` by default in `mn64_settings.yaml`, but double-check that it is enabled.  
- **`enable_debug: True`**  
- **`fix_bad_maps: True`**
- **`randomize_enemies: True`** - This will randomize enemies in the areas giving the game a fresh feel.

### **Optional Rules**  
For additional challenge and convenience, you can enable the following:  

- **`auto_mash: True`** – Speeds up long cutscenes by progressing them automatically.  
- **`start_flute: True`** – Start with Yae recruited and Yae’s flute in your possession, updating the maze logic accordingly. This is recommended to reduce excessive backtracking, as the flute is not guaranteed to be obtainable otherwise. *(Note: Castles will no longer be warp locations; you can only warp to Goemon’s house, teahouses, and inns.)*  
- **`flute_anywhere: True`** – Allows the flute to be used in any room, including castles and shops. If `start_flute` is enabled, this slightly improves seed generation times; if `start_flute` is disabled, it greatly increases generation times. It is recommended to enable both `start_flute` and `flute_anywhere` together.  
- **No Fortune Dolls** – You cannot collect any fortune dolls during your run (unless unavoidable).  
- **`sasuke_mode: True`** – Enabled by default in the **Sasuke Edition**, this setting starts you as **Sasuke** and **Yae** instead of Goemon and Ebisumaru, with maze logic updated accordingly. Cutscenes remain unchanged, but Ebisumaru can be recruited by viewing Yae’s cutscene, and Goemon by viewing Sasuke’s. *(If playing the Goemon Edition, this should be disabled.)*
- **Restart on Death** - If you die during a run, you must reset back to the beginning.

  ### 🧩 Additional Info:
- **Shops, Restaurants, and Cat Dolls Matter More** – With resources being scarcer and damage being higher, healing becomes crucial.  
- **Armor & Helmets Are Essential** – They still negate full damage from a hit, making them invaluable.


## 🔧 Installation & Usage  

1️⃣ **You must have a working ROM file.** (I cannot provide links to ROMs.)  
   - **Verify ROM compatibility** using the following MD5 hashes:  

   **English ROM Hashes:**  
   ```
   643cce1ab06f97e9590241d27e5c2363  
   f2162be647e4aa59254ec5ed7db1e94a (byte-swapped)  
   e8d83efd203e533d734933e0a14f1a8c (little-endian)  
   ```  
   
   **Japanese ROM Hashes:**  
   ```
   9b929e0bf8d63e62820f2fa6257cc5cf  
   9704b99f5f86879c0482d7223257dcef (byte-swapped)  
   e5e8d1d0cd03bbcf8bd58151bd84e58f (little-endian)  
   ```  

2️⃣ Download either the **Goemon Edition** or **Sasuke Edition** `.yaml` file.  
3️⃣ Move the selected `.yaml` file into the **Goemon Randomizer folder**.  
4️⃣ **Backup your existing `mn64_settings.yaml` file!** (This ensures you can revert changes.)  
5️⃣ Rename the downloaded **Goemon or Sasuke Edition** `.yaml` file to **`mn64_settings.yaml`**.  
6️⃣ Run the **Ancient Cave Starring Goemon Randomizer** ([GitHub Repo](https://github.com/abyssonym/mn64rando)).  
7️⃣ Your **randomized ROM** is now ready to play!  

## ⚠️ Notes  

- Some generated seeds **may not be completable**.  
- If you get stuck, ensure **`avoid_softlocks: True`** is enabled.  
- `sasuke_mode` is **enabled by default in the Sasuke Edition** but should be **disabled in the Goemon Edition**.  

## Good Luck!  
Try out some of the **Hardcore Seeds** and test your skills. Be sure to check for updates and share your experiences!  
