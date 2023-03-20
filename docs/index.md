---
layout: default
---


#### ABOUT

The 7D2D Mod Launcher finds, downloads, and installs overhauls and modlets for 7 Days To Die.

Originally created in 2014 to help players find mods, the Mod Launcher has gone through complete re-writes over the past few years.

The latest incarnation of the Mod Launcher is V5, created using Unity UI ToolKit.

#### Features

*   Find and download dozens of overhauls, and keep them up to date on the latest versions.
*	Maintain multiple versions of the same mod, switch back and forth for different saves, and worlds.
*   Revisit past Alphas and their mods to relive.
*   Find and install over 300 modlets per Alpha.
*	Easily add in modlets from third party sites, such as nexus mods and 7 Days To Die Mods site.
*	Create "My Mods", an empty overhaul that allows you to customize your vanilla experience.
*	Build-in backups for Generated Worlds and Saves, snapshots taken every time you play.
* 	Defaults to offline mode; no fetching of data on start up.
*	Installer / UnInstaller ( windows only )

#### Support

*	Need some help, join the <a href="https://discord.gg/H6k6gDrgNW">Mod Launcher's Discord</a>
*	Don't have Discord, but still need a hand? Email Support@7D2DModLauncher.org
*	Want to donate? <a href="https://paypal.me/7d2dmodlauncher?locale.x=en_US">PayPal</a>


#### Technical Changes in V5

*	Removed the Git implementation, as it was causing instability issues with larger mods.
* 	Uses git API to find versions and download links for Overhauls and Modlets.
* 	Unity 2021's UI ToolKit.
*	Downloads implemented using HTTP with a custom class to provide download progress.
*	Remove UnityWebRequest download, as it was causing instability issues.
*	Uses an InnoSetup for Windows Installer.

