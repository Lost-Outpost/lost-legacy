<a href="#"><img src="images/banner.webp" target="_blank"></a>

---

<p align="center">
  <a href="README.md">Installation</a> ·
  <a href="GAMEPLAY.md">Gameplay Guide</a> ·
  <a href="CONFIGURATION.md">Configuration</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
  <a href="HELP.md">Help</a>
</p>

---


# Configuration

- [Configuration](#configuration)
  - [Optional Content](#optional-content)
    - [Widescreen](#widescreen)
    - [Character Presets](#character-presets)
    - [General Rules](#general-rules)
  - [Mod Configuration](#mod-configuration)
    - [MCM Menus](#mcm-menus)
  - [ENB and Reshade Presets](#enb-and-reshade-presets)
  - [Performance Guide](#performance-guide)

## Optional Content
**As a warning. The optional content has not been tested nearly as heavily as the rest of the list as not everyone has it enabled. Support will be limited if you enable any of the optional content as its more difficult to account for them. If you are at all worried about stability, do NOT enable any.**

When enabling any optional tweaks, the .esp files (if applicable) should already be placed in the correct order in the plugin list for you, but let me know if you notice it at the end of the plugin list so I can fix that.

### Widescreen

**(Not yet implemented)** I have included the necessary mods to enable widescreen UI support. If you play on a widescreen monitor, this can be enabled in the optional mods section.



Also, if you are using the optional NordicUI, enable the mod entitled "NORDIC UI - Ultrawide Fixes and Patches".


### General Rules
When enabling optional content, the plugin should be placed in the correct spot automatically, but verify on the right side of MO2 to be sure it isn't loading at the end of the list. For content with its own section, follow the appropriate readme section for it.

## Mod Configuration

### MCM Menus

All MCM menus have been automated so you are good to ignore them unless you want to change anything.

A few that you may want to tweak:
- Sunhelm - Can tweak Hunger/Thirst/Sleep/Col settings to your liking
- The Ultimate Dodge Mod - Can change the dodge settings and hotkey
- True Directional Movement - Target lock hotkey
- Wildcat combat - Can change the difficulty multipliers and some other combat settings
- Violens - I have killmoves disabled by default, these can be safely enabled/tweaked

## ENB and Reshade Presets

> :ledger: You should only ever enable exactly one preset (regardless of whether it is an ENB or Reshade). You should never enable both an ENB and Reshade preset at the same time.

Lost Legacy includes an awesome tool called ENB Organizer for trying out different ENB presets.

To change ENB presets, do the following:

- Run ENB Organizer from the exe list in the top right of MO2
- If the program warns about not being able to check for updates, simply click ok and ignore it


- Go to presets on the left menu and enable the enb preset you wish to use. Be sure to only enable one preset at a time. The safest way is to disable them all and then simply activate one preset. Mixing presets (including mixing ENB and Reshade presets) will not work. The default ENB preset for the list is "MAIN - Pi-Cho Ultra".


To install a new ENB, do the following:

- Manually download the ENB zip archive
- Create a new temporary folder on your desktop to contain the new ENB
- Open the ENB zip archive, copy the enbseries folder, enblocal.ini, and enbseries.ini into your temporary folder
- Open Lost Legacy MO2, run the ENB Organizer
- Ignore the ENB Organizer error message
- In ENB Organizer, select Presets from the menu
- In ENB Organizer, select the add button, select import folder or archive, import from your temporary folder, change Binary dropdown to "enbseries", then hit Save

Thanks to Lost Outpost community helper Curly for making [this video](https://www.youtube.com/watch?v=4MA5ZLcRYds) to show the process.

## Performance Guide

(In-progress)
- Enable the 4 Performance Mode mods in the bottom left of mo2 (Completely changes the grass and tree setup)
- Try switching ENB to the "PERFORMANCE - Cathedralist Fantasy" preset (instructions above) (Drastically changes the look of the list, but very performance friendly)
- Copy the files from `Lost Legacy\profiles\Lost Legacy\Preset - Performance` to the profile you're using and overwrite `Lost Legacy\profiles\Lost Legacy`
- If you need further performance tweaks, you can try disabling some texture mods like Skyrim 2020, Skyland AIO, Illustrious Whiterun, and Tamrielic Textures
- Enable the POTATO MODE mod at the bottom of the Performance Mode section in mo2 (in version 1.0.4b and higher)


