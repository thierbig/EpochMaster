# Pstar Client and Addons for Project Epoch
![WoWScrnShot_082725_120103](https://github.com/user-attachments/assets/b71f4f9b-9250-4731-8788-f6eea4ed641e)

This guide provides instructions for setting up the **[Pstar Client](#pstar-client-installation)** OR **[Pstar Addons/WTF](#pstar-addonswtf-installation)** for Project Epoch, a World of Warcraft private server.

Choose between both approaches depending on your needs!!!

---

## [Pstar Client](#pstar-client-installation) Installation Approach

Offers a fast and easy setup with features like:
- **woltk_awesome**: Cast bars on ALL nameplates, 200-yard nameplate distance, and faster stance swapping.
- HD vanilla textures and improved FPS performance via DXVK. Better looking, more fluid.
- Risk: Potential ban (unlikely, but possible). I have been playing for over 10 days with it and several friends too and so far, so good.
- NEVER CHANGE YOUR GRAPHICS IN-GAME EXCEPT FOR WINDOWED MODE STUFF
- NEVER UPDATE YOUR GAME VIA THE ASCENSION LAUNCHER OR THE NAMEPLATES CASTING AND 200 YARD DISTANCE WILL DISAPPEAR

### Installation Steps
1. **Download the Pstar Client** from my [Google Drive](https://drive.google.com/file/d/1SwLxVS8g1iXTUlNUK3Tsdy13YTM5QkQL/view?usp=sharing)
2. **Backup your current setup**:
   - Locate your `epoch_live` folder (found in `Ascension Launcher/resources`).
   - Rename `epoch_live` to `epoch_live_old` to preserve your existing setup.
3. **Copy your account details**:
   - Navigate to `epoch_live_old/WTF/Account`.
   - Note down your account name (e.g., `bob@gmail.com`) in a text editor.
4. **Extract the new client**:
   - Extract the downloaded `epoch_live` folder next to `epoch_live_old`.
   - Navigate to `epoch_live/WTF/Account`.
   - Rename the placeholder account folder (e.g., `example@gmail.com`) to your actual account name.
   - Inside the renamed account folder, open the `Gurubashi` folder and rename `CharacterName` to your character's name.
5. **Launch the game**:
   - Always use `Ascension.exe` to open the game (not the launcher).
   - Create a desktop shortcut for `Ascension.exe` if desired.
6. **Customize WeakAuras**:
   - Remove unwanted WeakAuras by typing `/wa` in-game and managing them.
7. **Disable Blizzard's target cast bar**:
   - In-game, go to `Interface > Combat > Cast Bars` and disable the target cast bar.
   <img width="1391" height="1081" alt="image" src="https://github.com/user-attachments/assets/a5c03103-7f11-4170-858a-c9b33276b2cf" />

8. **Adjust nameplate distance**:
   - Use the `Awesome CVar` addon to modify nameplate distance as needed.
   <img width="1232" height="646" alt="image" src="https://github.com/user-attachments/assets/40e30058-fc6d-462d-a15c-ba559c766a67" />

9. **Change Kui Nameplates profile RECOMMENDED
   - Go into `Interface > Addons` and do like screenshot
   <img width="1356" height="1036" alt="image" src="https://github.com/user-attachments/assets/085c34ee-81ac-4c86-bbc2-b3a99b27adb5" />
   - Do /reload after changing



### Optional: Borderless Window Mode RECOMMENDED
The client opens in windowed mode (not maximized). To optimize performance and alt-tabbing:
1. Download [**NoMoreBorder**](https://github.com/invcble/NoMoreBorder/releases).
2. Open WoW in windowed mode (not maximized).
3. Use NoMoreBorder to set Project Epoch to borderless mode.
4. Configure NoMoreBorder to launch with Windows for convenience.
<img width="403" height="424" alt="image" src="https://github.com/user-attachments/assets/280cf599-5088-41e0-8b30-c9d1a139488f" />


### Optional: Additional Textures NOT RECOMMENDED
Enhance visuals by enabling the following:
1. **Upright Orc models**:
   - In `epoch_live/Data`, rename `patch-O.mpq.old` to `patch-O.mpq`.

### Optional: Extra quality with NVIDIA Control Panel NVIDIA GPU ONLY
Give more juice to the WoW Client
1. Do like the screenshots:
<img width="953" height="737" alt="image" src="https://github.com/user-attachments/assets/2d819824-4373-4ec6-ab34-acd3ea42d8b5" />
<img width="935" height="709" alt="image" src="https://github.com/user-attachments/assets/85623bd1-743a-4966-8ca2-0589cbfcdffc" />
<img width="937" height="719" alt="image" src="https://github.com/user-attachments/assets/6256bd75-275b-41d2-b3bb-92bcca8809aa" />




---

## [Pstar Addons/WTF](#pstar-addonswtf-installation) Installation Approach

This setup provides a streamlined addon configuration without nameplate cast bars (cast bars are only shown for the currently targeted unit because of basic client).

### Installation Steps
1. **Download the Pstar Addons/WTF** from my [Google Drive](https://drive.google.com/file/d/1vvGNk32zhuT-JKafxPo8zrBNtdY0cE51/view?usp=sharing)
2. **Replace the Addons folder**:
   - Navigate to `epoch_live` (in `Ascension Launcher/resources`).
   - Go to `epoch_live/Interface` and delete the existing `Addons` folder.
   - Extract the downloaded `Addons` folder to `epoch_live/Interface`.
3. **Copy your account details**:
   - Navigate to `epoch_live/WTF/Account`.
   - Note down your account name (e.g., `bob@gmail.com`) in a text editor.
4. **Replace the WTF folder**:
   - Replace the `epoch_live/WTF` folder with the downloaded `WTF` folder.
5. **Rename account and character**:
   - In `epoch_live/WTF/Account`, rename the placeholder account folder (e.g., `example@gmail.com`) to your actual account name.
   - Inside the renamed account folder, open the `Gurubashi` folder and rename `CharacterName` to your character's name.
6. **Customize WeakAuras**:
   - Remove unwanted WeakAuras by typing `/wa` in-game and managing them.
7. **Disable Blizzard's target cast bar**:
   - In-game, go to `Interface > Combat > Cast Bars` and disable the target cast bar.
   <img width="1391" height="1081" alt="image" src="https://github.com/user-attachments/assets/a5c03103-7f11-4170-858a-c9b33276b2cf" />
   - Do /reload after changing
8 **Activate castbars in KuiNamePlates since you are not using my patched client**
   - Figure it out

---

## Included Addons

The following addons are included in both setups (latest versions for Project Epoch, some with custom bug fixes):
- !!ClassicAPI
- AbbreviatedStatus
- Accountant
- AddFriend
- AddonList
- AI_VoiceOver
- AI_VoiceOverData_Vanilla
- AllStats
- AnyIDTooltip
- AtlasLoot
- AtlasLoot_Crafting
- AtlasLoot_OriginalWoW
- AtlasLoot_WorldEvents
- AtlasLootFu
- Auctionator
- AwesomeCVar (Pstar Client only, for cast bars and nameplate distance)
- Bagnon
- Bagnon_Config
- Bagnon_Forever
- Bagnon_GuildBank
- Bagnon_NewItems
- Bagnon_Tooltips
- BigDebuffs
- Broker_ItemRack
- Cheese
- Clique
- CombatLogFix
- CompactRaidFrame
- CompactRaidFrame_HealEx
- Cooldowns
- Details
- Details_3DModelsPaths
- Details_ChartViewer
- Details_DataStorage
- Details_DeathGraphs
- Details_EncounterDetails
- Details_SunderCount
- Details_TimeLine
- Details_TinyThreat
- DWD_TooltipDeltaFix
- EnhancedRaidFrames
- Flash (Pstar Client only, for cast bars)
- FonzAppraiser
- FrameSort
- GearScoreLite
- GroupBulletinBoard
- ItemRack
- ItemRackOptions
- Kui_Nameplates
- Kui_Nameplates_Auras
- Leatrix_Plus
- LFG
- Magnify-WotLK
- Mapster
- MoveAnything
- PlateCastBar (Pstar Client only, for cast bars)
- pMinimap
- Postal
- Prat-3.0
- Prat-3.0_HighCPUUsageModules
- Prat-3.0_Libraries
- Quartz
- Questie
- ShadowedUF_Options
- ShadowedUnitFrames
- TomTom
- WeakAuras
- WeakAurasArchive
- WeakAurasModelPaths
- WeakAurasOptions
- Whats-Training-Epoch

### Addon Updates
Keep the following addons updated for the best experience:
- **Questie**: [https://github.com/esurm/Questie](https://github.com/esurm/Questie)
- **AtlasLoot**: [https://github.com/Raynbock/AtlaslootProjectEpoch](https://github.com/Raynbock/AtlaslootProjectEpoch)

### Recommended Additional Addons
- **Gladdy**: For arena gameplay : [https://gitlab.com/Tsoukie/gladdy-3.3.5](https://gitlab.com/Tsoukie/gladdy-3.3.5)
- **Omnibar**: Track enemy cds : [https://gitlab.com/Tsoukie/omnibar-3.3.5](https://gitlab.com/Tsoukie/omnibar-3.3.5)
- **TskoukiePartyTracker**: Omnibar for allies in Party : [https://gitlab.com/Tsoukie/tsoukiepartytracker](https://gitlab.com/Tsoukie/tsoukiepartytracker)
- **Battleground Addon**: Choose one based on your needs

---
![WoWScrnShot_082725_121439](https://github.com/user-attachments/assets/438037a6-585f-426f-aca5-13e4338659a5)
![WoWScrnShot_082725_120623](https://github.com/user-attachments/assets/1bec3732-457e-48df-9a24-c9f6d95cce3a)
