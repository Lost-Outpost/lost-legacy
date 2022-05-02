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

When enabling any optional tweaks, make sure they are always loaded BEFORE realisticwatertwo.esp in your load order. See the alternate start section for an example of this.

### Widescreen

I have included the necessary mods to enable widescreen UI support. If you play on a widescreen monitor, this can be enabled in the optional mods section.

![Widescreen](https://raw.githubusercontent.com/Guitarninja2/Lost Legacy/main/images/widescreen.png)

Also, if you are using the optional NordicUI, enable the mod entitled "NORDIC UI - Ultrawide Fixes and Patches".

### Character Presets

Lost Legacy includes mod that contains a few character presets, and you can also copy presets you download from the [Lost Legacy Character Presets Discord thread](https://discord.com/channels/773659452392865792/952965520083275796) to load when creating new characters. 

The presets mod is here:

![Lost Legacy-character-presets](https://user-images.githubusercontent.com/508163/159598073-ee99e599-2f5a-4ce3-93d3-169233858689.png)

You can select this mod, right-click it, and then select "Open in Explorer" to see the presets directory, which will be at this location:

```
Lost Legacy\mods[NoDelete] Character Presets\SKSE\Plugins\CharGen\Presets
```

### General Rules
When enabling this content, just like with alternate start mods, ensure all mod esp files are just above realisticwatertwo.esp in your load order and if there is a Lost Legacy patch for them, load that after the mod's esp and above all other Lost Legacy patches. This applies for any optional content not specifically mentioned here. For content with its own section, follow the appropriate readme section for it.

## Mod Configuration

### MCM Menus

All MCM menus have been automated so you are good to ignore them unless you want to change anything.

## ENB and Reshade Presets

> :ledger: You should only ever enable exactly one preset (regardless of whether it is an ENB or Reshade). You should never enable both an ENB and Reshade preset at the same time.

Lost Legacy includes an awesome tool called ENB Organizer for trying out different ENB and Reshade presets.

To change ENB & Reshade presets, do the following:

- Run ENB Organizer from the exe list in the top right of MO2
- If the program warns about not being able to check for updates, simply click ok and ignore it

![Exe List](https://raw.githubusercontent.com/Guitarninja2/Lost Legacy/main/images/exe_menu.png)

- Go to presets on the left menu and enable the enb preset you wish to use. Be sure to only enable one preset at a time. The safest way is to disable them all and then simply activate one preset. Mixing presets (including mixing ENB and Reshade presets) will not work.

![Enb Organizer](https://raw.githubusercontent.com/Guitarninja2/Lost Legacy/main/images/enb_enable.png)

- Very low spec users may want to switch to Cathedral Reshade instead of ENB for extra performance

To install a new ENB, do the following:

- Manually download the ENB zip archive
- Create a new temporary folder on your desktop to contain the new ENB
- Open the ENB zip archive and navigate to the ELFX sub-folder
- From the ENB zip archive ELFX sub-folder, copy the enbseries folder, enblocal.ini, and enbseries.ini into your temporary folder
- Open Lost Legacy MO2, run the ENB Organizer
- Ignore the ENB Organizer error message
- In ENB Organizer, select Presets from the menu
- In ENB Organizer, selct one of the Lost Legacy ENB (not Reshade!) presets, and use the View Files menu item
- Copy the two .DLL files from the Lost Legacy ENB preset into your temporary folder
- Your temporary folder should now have the enbseries folder, enblocal.ini, enbseries.ini, and two .DLLs
- In ENB Organizer, select the add button, select import folder or archive, and import from your temporary folder

Thanks to Lost Legacy community helper Curly for making [this video](https://www.youtube.com/watch?v=4MA5ZLcRYds) to show the process.

## Performance Guide

- Try turning off any ENB that might be enabled and switching to the ultra lite reshade preset
- Activate the performance grass and dyndolod mods under Lost Legacy - Performance Mode
- Copy the files from one of the presets in Lost Legacy/Performance Options to the profile you're using and overwrite (Lost Legacy/profiles/Lost Legacy [- Anniversary Edition])

![Perf Options](https://raw.githubusercontent.com/Guitarninja2/Lost Legacy/main/images/perf_options.png)
![Perf Options 2](https://raw.githubusercontent.com/Guitarninja2/Lost Legacy/main/images/perf_options2.png)
![Perf Options 3](https://raw.githubusercontent.com/Guitarninja2/Lost Legacy/main/images/perf_options3.png)
- Double click on `SSE Display Tweaks - Lost Legacy Settings` under `Essentials` and set the resolution to match your monitor resolution and remove the # at the beginning of the line
