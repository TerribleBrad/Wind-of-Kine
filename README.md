MAJOR WIP. THIS IS NOT COMPLETE!!!!

![Logo]()

# Wind of Kyne

- [Preamble](#preamble)
- [Noteworthy Mods and What Gameplay to Expect](#noteworthy-mods-and-what-gameplay-to-expect)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Config](#steam-config)
      - [Disable the Steam Overlay](#disable-the-steam-overlay)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
    - [Set the Game language to English](#set-the-game-language-to-english)
    - [Clean Skyrim](#clean-skyrim)
    - [Start Skyrim](#start-skyrim)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading and Installing](#downloading-and-installing)
      - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
    - [Pagefile in prevention of memory crashes](#pagefile-in-prevention-of-memory-crashes)
- [Updating](#updating)
- [In Game MCM Options](#in-game-mcm-options)
- [How to start playing](#How-to-start-playing)
- [Last Things to Note](#Last-things-to-note)
- [FAQ](#faq)
  - [Ultrawide Options](#ultrawide-options)
  - [Removing the Modlist](#removing-the-modlist)
  - [Controller Support](#controller-support)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)
- [Contributing](#contributing)
- [Changelog](#changelog)

# Preamble

Wind of Kyne is a vanilla+ modlist with modernized combat. Visuals have been greatly enhanced 

Wind of Kyne is a fork of the my own list Streamlined Skyrim list which is a fork of SME/FT. Forkception!

Check out the full modlist here: [link](https://loadorderlibrary.com/lists/wind-of-kyne-1)


**Please read the ReadMe in Full. The installation process is not completed once you have finished the Wabbajack installation. Do not report issues/bugs/errors to mod authors! Seek out help from me or the other folks on the Wabbajack Discord**

## Streamlined Skyrim does not work with Anniversary Addition!! If you accidently updated use [this](https://www.nexusmods.com/skyrimspecialedition/mods/57618?tab=files) to downgrade. ##


# Noteworthy Mods and What Gameplay to Expect
Just trust me it's good.

# Installation
### Prerequisites
#### PC Specifications
Wind of Kyne is designed for low to mid tier systems and does not include an ENB.

TerribleBrad’s System:

GPU: Radeon RX 580 Series 8GB

CPU Ryzen 6 2600

RAM: 16 GB

Storage: 500 GB SSD

Fps: 50-60 (mostly 60 fps)

#### Size on Drive

  - Over  GB for the Downloads folder
  - Over  GB for the Installation folder
  - ~15 GB for temporary files

So  GB **minimum** is required. I cannot stress how much a SSD is needed for **at least** the game and the list. You can put your downloads in an HDD so it will only slow your installation process.

### Pre-Installation

These steps are only needed if you install the Modlist for the first time. If you are updating the Modlist, jump straight to [Updating](#updating).

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. This package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Library

If you have your Steam library in Program Files, read [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it somewhere else.
I will not provide support to people with Skyrim in their Program Files folder.
Locations like Documents, Downloads, Desktop, or OneDrive are NOT fine. The best location would be ``C:\SteamLibrary`` if you have a single drive, or whichever Drive Letter you have on your main Games drive. Such a location is also called the "root of the drive."

#### Change Steam's Update Behavior

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_. You should also disable the Steam Cloud while you're at it.

#### Set the Game language to English

Just do it. This entire Modlist is in English and 99% of all mods you will find are also in English. I highly recommend playing the game in English and **I will not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

#### Clean Skyrim

I highly recommend uninstalling the game through Steam, deleting the game folder, and reinstalling it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents in it. Alternatively, use the [Shredder](https://www.nexusmods.com/skyrimspecialedition/mods/30133).

If you ever used Vortex to mod Skyrim SE, using the Shredder becomes a critically important step, as Vortex will conflict heavily with any Wabbajack installation, so backup your stuff or shred it.

If the Shredder is unavailable at the time you read this, manually uninstall Vortex and manually delete the `Skyrim Special Edition` folder located in your `SteamLibrary\steamapps\common`, where your SteamLibrary is.

[THIS](https://imgur.com/a/1dySo8q) is approximately what a clean Skyrim install should look like after shredding or cleaning it manually.

## Start Skyrim

After you have done everything above and got a clean SSE installation ready, start the Launcher and open the _Options_ menu.

1. Leave the quality to what Skyrim sets it to, but you can lower it if you wish. FPS gain is minor though.
2. Set the _Aspect Ratio_ and _Resolution_ to your monitor's native values
3. Check _Windowed Mode_ and _Borderless_

Start the game and exit once you're in the main menu.

## Revert to pre-AE Skyrim
Wind of Kyne does not currently support Skyrim Anniversary Edition.

If you downloaded or updated Skyrim SE after 11/11/2021, you are on version 1.6.318.0 which will not work with Streamlined, regardless of whether you own the Anniversary Edition DLC or not. You need to downgrade your installation to 1.5.97.0 before you can proceed.

Download halgari’s [Unofficial Skyrim Special Edition Downgrade Patcher](https://www.nexusmods.com/skyrimspecialedition/mods/57618) from the Nexus (Full Patcher).
Extract the contents of the archive to a convenient location and run Patcher.exe.
It should find your Skyrim SE folder automatically and display the file path.
Click the green Start Patching button and wait for the process to complete.
When the tool returns Finished Patching, enjoy your game!, you can close it and proceed.
Skyrim SE Version Downgrade

### Using Wabbajack

## Preparations

Download the release to a _working folder_. This folder **must not** be in a _common folder_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the _working folder_.

Wabbajack will not work with Windows 7, I will not offer any kind of support for users of that operating system.

## Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Find Wind of Kyne in the Wabbajack user interface and press the download arrow.
2. Create a folder for the List at the root of your drive (like the Wabbajack folder) called "Streamliend Skyrim." This will be your "Installation" folder.
3. Create another folder called "Wabbajack Downloads Folder". This specific folder can be on a different drive if you wish. This will be your "Downloads" folder.
4. Select your Installation and Download folders (the ones you just made)
5. Click the Go/Begin button.
6. Wait for Wabbajack to finish.


### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update the Modlist.

Some files are known to be problematic, you can find them stickied in my Discord Channel

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Post-Installation

## Pagefile in prevention of memory crashes

Bigger Skyrim modlists need a lot of memory, and when there is not enough available it may fail allocating more. To fix this, you'll want to have a bigger pagefile.
A pagefile is a file on your disk Windows will use when there is not enough RAM available.
Never disable the pagefile - this may lead to various issues on your system, such as this Skyrim crash.

If you've never touched the pagefile, perform the following steps to prevent from memory crashes:
1. Press Windows + R on your keyboard and enter `sysdm.cpl ,3`
2. Under the Performance section, press 'Settings'
3. Go to the Advanced tab at the top, and at the Virtual memory section press 'Change...'
4. Disable 'Automatically manage paging file size for all drives'
5. If you have more than one drive, try enabling it for at least one more drive as a backup (make sure it has a decent bit of free space, like 15GB). Set the size to 'System managed size'.
Otherwise, set a custom size for the drive it's currently on and increase the maximum size to be at least 20GB.

## Updating

If this Modlist receives an update, please check the Changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your saves will be kept, but please check each update changelog to see if the update is save compatible.  Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

## How to start up Streamlined Skyrim

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. Once it's launched, there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

Select 'New' to start a new game. Once you have finished character creation allow all of the start of game scripts to finish loading before doing anything. Do NOT change race with showracemenu after confirming your character! It is time to configure all the mcm menus!


## In-Game MCM Options


#### A Matter of Time

- Presets :
  - Load User Settings

#### Commentary Rate Configuration
- Minimum Time Between Comments : 20
- Maximum Time Between Comments : 30

#### CGO
- Change dodge key to hotkey: Make it Spacebar
- Grip swap key: G
- Dual wield block: M5

#### EVG Conditional Idles: (Personal Preference)
- Player
    - Movement Enabled:
        - Cold : Disabled
        - Injured : Disabled
    - Idle
        - Fatigued Stage 1 : Disable
        - Fatigued Stage 2 : Disable
- NPC
    - Movement Enabled:
        - Cold : Disabled
    - Idle
        - Fatigued Stage 1 : Disable
        
#### Immersive HUD
- Activation
  - Compass Activation
    - iHUD hotkey : (your choice you'll click it once and never use it again)
    - Key press toggles : Enabled
  - Crosshair Activation
    - Wielding ranged weapon : Disabled
    - Wielding spell : Disabled

#### moreHUD
- Presets
  - Save Settings with FISS
    - Load User Settings? : GO

#### NASC
- Mod Options
  - Stamina Consumption : 10

#### Optimal Potion Hotkey
- Hotkeys
 - Health potion hotkey : H
 
#### Smart NPC Potions
- Custom Values
  - Max number of potions : 2

#### SmoothCam  
- Presets
  - Load Preset : Modern Camera Preset
- Crosshair
   - Sneak Settings
      - Enable Stealth Meter Offset : Disable

#### Timing is Everything
- Extra Options 
  - Load Preset  

#### True Directional Movement
- General
    - Controls
      - Toggle Target Lock Key : ( It is set to Mouse 4, but if you don't have a mouse with extra buttons use a key near WASD like G)

#### Game Difficulty
- The difficulty of Wind of Kyne is higher than Vanilla so I suggest not using Legendary. I personally play on Expert.

## Key Bindings:
  - Space bar : it is the dodge key in this mod list. You will need to change jump to be a different key to allow yourself to dodge.
  - Toggle Target Lock : Mouse 4. If you don't have a mouse with extra buttons use a key near WASD like G
  - Health Potion Hotkey : H
  - Dual Wield Block : Mouse 5
  - Map: x
  - Jump: c
 

## How to start playing
Make character. Talk to the dragon. P

## Last Things to Note
Nothing to see here


## FAQ

### Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

### Ultrawide Options

I have an ultra-wide, but it's just not worth the hassle of setting Skyrim up for it, in my opinion. Skyrim isn't made for it; if you disagree, check [this guide](https://docs.google.com/document/d/1D3Yapmu_IkTWSszJ4h9wpNxgNLCi46f7XiJknpdMb6E/edit?usp=sharing) by my friend Mantis for compatibility with such screens.

### Controller Support

I don't play Skyrim with a controller so at the moment I don't offer support for it. Although, I am working on making Streamlined Controller friendly :)

### I have a question

Ask it in my Discord, link [here](https://discord.gg/JK3V6GwqfM) or Wabbajack's Discord, [link here](https://discord.com/invite/wabbajack). But make sure you're using the right support channel and not a general channel!


### Creation Club (CC Content) Support?

No, I don't like them.

CC Content isn't considered like DLCs (Dawnguard/Dragonborn/Hearthfire) and will never be treated as such.

Using them with Wind of Kyne would be like installing your own mods: Support is forfeited and they will NOT work without patching.


## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!
- Halgari and everyone in the WJ Team.
- Sovn for teaching me how to use xEdit, testing my list, letting me fork his Readme and answering all of my questions.
- Chris for also teaching me xEdit, testing my list and finding everything I needed to patch.
- To the members of my Discord, for their feedback, suggestions and bug finding.


## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack), feel free to check out my own [Discord](https://discord.gg/JK3V6GwqfM). **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS**.

## Changelog

See [Changelog](https://github.com/TerribleBrad/Wind-of-Kyne/blob/main/Changelog.md).
