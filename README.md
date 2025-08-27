# Pstar Client and Addons for Project Epoch

This guide provides instructions for setting up the **[Pstar Client](#pstar-client-installation)** OR **[Pstar Addons/WTF](#pstar-addonswtf-installation)** for Project Epoch, a World of Warcraft private server.

---

## [Pstar Client](#pstar-client-installation) Installation

Offers a fast and easy setup with features like:
- **woltk_awesome**: Cast bars on ALL nameplates, 200-yard nameplate distance, and faster stance swapping.
- HD vanilla textures and improved FPS performance via DXVK. More FPS.
- Risk: Potential ban (unlikely, but possible). I have been playing for over 10 days with it and several friends too and so far, so good.

### Installation Steps
1. **Download the Pstar Client** from the provided link.
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
8. **Adjust nameplate distance**:
   - Use the `Awesome CVar` addon to modify nameplate distance as needed.

### Optional: Borderless Window Mode RECOMMENDED
The client opens in windowed mode (not maximized). To optimize performance and alt-tabbing:
1. Download [**NoMoreBorder**](https://github.com/invcble/NoMoreBorder/releases).
2. Open WoW in windowed mode (not maximized).
3. Use NoMoreBorder to set Project Epoch to borderless mode.
4. Configure NoMoreBorder to launch with Windows for convenience.

### Optional: Additional Textures NOT RECOMMENDED
Enhance visuals by enabling the following:
1. **Improved spell textures**:
   - In `epoch_live/Data`, rename `patch-7.mpq.old` to `patch-7.mpq`.
2. **Upright Orc models**:
   - In `epoch_live/Data`, rename `patch-O.mpq.old` to `patch-O.mpq`.

---

## [Pstar Addons/WTF](#pstar-addonswtf-installation) Installation

This setup provides a streamlined addon configuration without nameplate cast bars (cast bars are only shown for the currently targeted unit because of basic client).

### Installation Steps
1. **Download the Pstar Addons/WTF** from the provided link.
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
- **Gladius**: For arena gameplay.
- **Battleground Addon**: Choose one based on your needs.

---
