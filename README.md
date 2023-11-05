# swsh-camera-tweaks-patch
Patches/Cheats modifying the limits on the camera in pokemon sword and shield

Mod idea, feedback, and testing by [@norainthefuture](https://twitter.com/norainthefuture)

# [Download](https://github.com/Lincoln-LM/swsh-camera-tweaks-patch/releases/)

# Features
- Increased camera pitch ranges from [-20°, -5°] to [-1.25rad, 0.25rad] (from horizontal to top-down view)
- Increased camera adjustment speed from 3° to 3.75° (1.25x)
- Increased camera distance from the player, default 370 -> 450 & zoomed out 800 -> 1000 (roughly 25% increase)

# Installation
## Patches
### Atmosphère
- Extract the zip to the root of your sd card and it should create ``sdmc://atmosphere/exefs_patches/swsh-camera-tweaks-patch/A16802625E7826BF83B6F9708E475B912A9AB7DF000000000000000000000000.ips`` (shield) and ``sdmc://atmosphere/exefs_patches/swsh-camera-tweaks-patch/A3B75BCD3311385AEED67FBEEB79CBB7BF02F471000000000000000000000000.ips`` (sword)
- You can remove the .ips file for the game you do not want to patch if you would only like to install the patch for one version
### Emulator
- Place the patches in the appropriate folder for exefs patches in your emulator of choice
## Cheats
### Atmosphère
- Extract the zip to the root of your sd card and it should create ``sdmc://atmosphere/contents/{TitleID}/cheats/{BuildID}.txt`` for TitleID:01008DB008C2C000 BuildID:A16802625E7826BF (shield) and TitleID:0100ABF008968000 BuildID:A3B75BCD3311385A (sword)
- Install a cheat manager like [Edizon-SE](https://github.com/tomvita/EdiZon-SE)
### Emulator
- Place the cheat files in the appropriate folder for your emulator of choice

### Alternatively you may install with [IP-Switch](https://github.com/3096/ipswitch) and the *.pchtxt files in the repo
