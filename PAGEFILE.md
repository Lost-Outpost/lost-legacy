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

# Pagefile Setup

A pagefile is a file on your disk Windows will use when there is not enough RAM available. Never disable the pagefile - this may lead to various issues on your system, such as a Skyrim memory crash.

If you've never touched the pagefile, perform the following steps to prevent from memory crashes:

1. Press Windows + R on your keyboard and enter `sysdm.cpl ,3`
2. Under the Performance section, press 'Settings'

![pagefile settings](https://raw.githubusercontent.com/Lost-Outpost/lost-legacy/main/images/pagefile1.png)

3. Go to the Advanced tab at the top, and at the Virtual memory section press 'Change...'

![pagefile settings 2](https://raw.githubusercontent.com/Lost-Outpost/lost-legacy/main/images/pagefile2.png)

4. Disable 'Automatically manage paging file size for all drives'

![pagefile settings 3](https://raw.githubusercontent.com/Lost-Outpost/lost-legacy/main/images/pagefile3.png)

5. If you have more than one drive, try enabling it for at least one more drive as a backup (make sure it has a decent bit of free space, like 15GB). Set the size to 'System managed size'.
   Otherwise, set a custom size for the drive it's currently on and increase the maximum size to be at least 20GB.

![pagefile settings 4](https://raw.githubusercontent.com/Lost-Outpost/lost-legacy/main/images/pagefile4.png)

![pagefile settings 5](https://raw.githubusercontent.com/Lost-Outpost/lost-legacy/main/images/pagefile5.png)
