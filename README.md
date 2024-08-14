# AFK Crucible reputation, Weapon level & Event items farm
### Download Link:
Download the "COMBINED.zip" file from the [latest release](https://github.com/KeelNode/afk_pvp_tabbedout_zc/releases/)

## About the macro
This macro farms Zone Control game mode by capturing all 3 flags, while occasionally pressing Super to complete challenges, bounties etc.
<br> There is some setup involved so please check the "**Guide**" section below 
<br>If you are interested in learning more about how this macro works or about similar macros that work while you are tabbed out of the game join the [Discord](https://thrallway.com).

### Features:
- Captures all 3 flags in Zone Control game mode
- Increase valor points (only gain reputation if Match Score limit set to 50 or higher)
- Increase weapon level XP
- Cast Super for bounties/orbs etc.. use a Well Warlock or Bubble Titan
- Obtain event items such as Silver Leaves (during Solstice)
- Option for choosing Match Score Limit set in game (25, 50, 100)
  - 75 provides same Crucible Reputation points as 50, so I have removed that
- Option for choosing if game is on HDD or SSD to account for slow load times
### Work In Progress: 
✅ option to swap between Score Limits of 25/50/100 - respectively prioritising and providing more rep.
<br>🚧 HDD/SSD options to automagically accounting for timings, allowing fastest possible runtime of each instance.
<br>🚧 Auto-setup private crucible settings for this farm.
<br>

# Support
If you like this macro and want to support my work, you can do so via Ko-Fi - [Keelnode](https://ko-fi.com/kielchrishi) 
<br>Your support means the world to us and allows us to keep enhancing and developing macros like this one. 🥰

# Destiny setup/settings/guide:
## Quick guide:
```
- GAME setup:
    - GAME TYPE  : Zone Control
    - GAME MAP   : Javelin-4
    - SUPER REGEN: x50 (optional to cast super for orbs)
    - SCORE LIMIT: 25, 50 or 100
       - 25 Provides Event items, Weapon XP but 0 crucible reputation points 
       - 50, 75 and 100 (or higher) Provides Event items, Weapon XP and crucible Reputation points
          - 50 and 75 provide same amount of crucible reputation

- CONTROLLER setup:
    - Default settings - see screenshot below

OTHER 
- BE IN ORBIT BEFORE STARTING THE MACRO 
- Ready the GREEN LAUNCH BUTTON 
- Default hotkeys: 
    - F8 to Start
    - F7 to Reload/stop
    - F6 to Quit/Exit script
- ANY RESOLUTION WORKS
```
  
## Full guide:

### Controller Settings
- **Button Layout:** Reset to Default
- **Look sensitivity:** `3`
- **Sprint-Turn Scale:** `0.4`
- **Axial Dead Zone:** `0`
- **Radial Dead Zone:** `0`
- **Vertical Inversion:** Not Inverted
- **Horizontal Inversion:** Not Inverted
- **Autolook Centering:** Off
![afk_controllerSettings](https://github.com/user-attachments/assets/ef717555-ea9b-4537-a74d-8496265249fa)

### Display Settings (not necessary but best experience)
- Window Mode: Windowed
- Resolution: `1280 x 720`
- Frame rate cap enabled: `on`
- Frame rate cap: `30`
- Field of View: `105`
- Screen bounds: Set them to highest possible
![video_settings](https://github.com/user-attachments/assets/66a49ce9-8f33-4c8b-b426-e955a05ec8ff)

### Character Requirements:
- MUST HAVE 100 mobility on any class

### PRIVATE Crucible settings:
 - GAME TYPE  : Zone Control
 - GAME MAP   : Javelin-4
 - SUPER REGEN: x50 (optional to cast super for orbs)
 - SCORE LIMIT: 25, 50 or 100
`note: 75 score limit works, but provides same crucible reputation as 100 score limit)`
    - 25  = NO   Crucible reputation & Weapon XP & event items (if available, such as Silver Leaves from Solstice)
    - 50  = SOME Crucible reputation & Weapon XP & event items (if available, such as Silver Leaves from Solstice)
    - 100 = MORE Crucible reputation & Weapon XP & event items (if available, such as Silver Leaves from Solstice)
<br>
# How To Use
1. Install AutoHotkey
    - Make sure you have AutoHotkey v1.1.37 (not AHK v2) installed on your computer.

2. Download the Latest Release
    - Download the latest release of the macro from the [releases page](https://github.com/KeelNode/afk_pvp_tabbedout_zc/releases).
    - Once downloaded, unzip the file to a folder of your choice.
    - `Do Not Compile the scripts. They are intended to run in their raw .ahk state.`

3. Ensure Settings Match
    - Run the macro and follow the settings on the prompt, only START the Macro once everything is done (can check the settings here too)
  
4. Run the Macro
    - Navigate to the unzipped folder and run `AFK_zC_ACB_combined.ahk` by double clicking it. `DO NOT Compile the scripts into an exe.`
    - Choose the score limit option: 25, 50, 100 etc

5. Keybinds
    - Use the following keybinds to control the macro:
      - **Start Macro:** Press `F8`
      - **Stop/Reload Macro:** `F7`
      - **Close/Quit Macro: ** `F6`

# Further Help
<br>For more help or to ask other questions please join the [Discord](https://thrallway.com)

## Frequently Asked Questions:
## Can I get Banned for this?
- Most likely **NO**, but do ensure you run this ONLY IN PRIVATE MATCH CRUCIBLE, otherwise you will definitely suffer. Reference this TWAB from 2023.

## HOW CAN I PLAY OTHER GAMES WHILE THIS IS RUNNING
- Follow this link and give this software a shot. Credit to @crushrr for the guide https://discord.com/channels/1119279989486010498/1259482362765377538
