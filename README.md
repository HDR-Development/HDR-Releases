

# HDR-Releases
The official stable release channel for HewDraw Remix, the largest and most ambitious overhaul for Super Smash Bros. Ultimate.

 ### What's the difference between this and the other download page?

 
The other repository is dedicated to the [experimental nightly builds](https://github.com/HDR-Development/HDR-Nightlies). If all you intend to do is play the normal release like most users, you're already in the right place and should go to the [release page here](https://github.com/HDR-Development/HDR-Releases/releases) to download the latest stable version of HDR.
If you want to playtest our latest changes, feel free to install the nightly by switching to it in the HDR launcher options menu, and report any issues you have with it via GitHub issues on the main repository [(HewDraw-Remix.)](https://github.com/HDR-Development/HewDraw-Remix)

If you happen to be interested in contributing to the project, check out our Wiki's [developer environment setup page](https://github.com/HDR-Development/HewDraw-Remix/wiki/The-Environment) to get started. More information on how to contribute can be found in the Discord in the #dev-general channel pins.
## Installation
If you are installing on a modded Nintendo Switch, follow the [tutorial on the YouTube channel](https://www.youtube.com/watch?v=jBb8jA4WfHA).
If you have not modded your Nintendo Switch before, use [this tutorial to mod it from scratch](https://gamebanana.com/tuts/13767).

Please note the HDR tutorial is slightly outdated because the `switch-release.zip` package is all you will need to extract and copy to the SD card as long as you have Atmosphere CFW running. If this was done correctly, you should be greeted by the HDR launcher and a play button to launch the game. For more information on the launcher [see this demonstration video.](https://www.youtube.com/watch?v=wjBhxIfk2xA) 

First time users will most likely need to go into the ingame Smash eShop after launching the game for the first time to toggle HDR's folders as seen in the [tutorial mentioned earlier.](https://www.youtube.com/watch?v=jBb8jA4WfHA) 

### Emulator Support
The Yuzu emulator currently does not support Skyline plugins which HDR makes extensive use of. Ryujinx, on the other hand, *does* support Skyline and has comparable performance to Yuzu.

If you are installing on the Ryujinx emulator, make sure to use a fork of Ryujinx that supports Skyline, such as [HDR-Ryujinx](https://github.com/zandm7/Ryujinx-HDR/releases) (an unofficial build not maintained by us or the Ryujinx developers.) 
You will need to copy the contents of the zip labeled `ryujinx-release.zip` into `\AppData\Roaming\Ryujinx\`.

### Troubleshooting

If you encounter any difficulties when installing the mod, please consult the #help-questions channel in the official discord over at [discord.gg/hdr.](https://discord.gg/hdr)

## Uninstall

If you are on Switch and wish to uninstall HDR, delete all folders starting with hdr in `/ultimate/mods` on your SD card.

You can also indefinitely disable HDR by going into the ingame eShop mod manager and toggling off all HDR related folders. 
Holding L while starting the game will guarantee all mods are temporarily disabled regardless on if the mod is enabled or if this menu is somehow inaccessible. 

If you are on Ryujinx, the path with these folders is `/AppData/Roaming/Ryujinx/sdcard/ultimate/mods`.

## Legal Disclaimer
HewDraw Remix is a free to play fan-made modification of Super Smash Bros. Ultimate. The HewDraw Remix Dev Team does not support piracy or any illegal actions that may harm Nintendo or other copyright holders involved in the base game, and their intellectual properties. HewDraw Remix is not endorsed by or associated with Nintendo or any of the companies involved with the Super Smash Bros. series in any way.
