# Minimal Class Selection HUD

<img src="docs/classselection-2.png" alt="Image of new Class Selection screen">

> ## _**ONLY** the class selection screen. No other HUD changes._

Due to the removal of the `extendfreeze` command, I'm trying a modified version of [KBNHud's (by Jotunn)](https://gamebanana.com/mods/26847) minimal class selection screen.

The changes that I made to KBNHud's class selection UI:

- Anchor to the left of the screen to get it out of the way
- Swap the custom fonts to built-in fonts
- Refactor hardcoded x/y position values for relative positions to group the core stuff

This is meant to only be used with TF2's default HUD as a minimal change, rather than worked into another custom HUD. I don't use custom HUDs, and I made this for myself.

## Download

[Download the ZIP](https://github.com/rufio-tf2/minimal-class-selection-hud/archive/refs/heads/main.zip) of this repo and extract the ZIP.

## Install

Navigate to your `tf` folder. If you've chosen a custom location for your Steam folder, then you know where it is. If you used the default install path, then it should be:

- Windows: `C:\Program Files (x86)\Steam\steamapps\common\Team Fortress 2\tf\`
- macOS: `~/Library/Application Support/Steam/SteamApps/common/team fortress 2/tf/`
- Linux: `~/.steam/steam/SteamApps/common/Team Fortress 2/tf/`

You can also:

1.  Right click TF2 in your Steam library
1.  Click Properties
1.  Go to the "Local Files" tab
1.  Click the "Browse Local Files..." button
1.  Open the `tf` folder

### Move HUD folder

To install these files, open the `custom` folder that's inside of the `tf` folder. If `custom` doesn't exist, just create it.

1.  Navigate into `tf/custom/`
1.  Move the `minimal-class-selection-hud` folder that you extracted from the ZIP previously into `tf/custom/`

You should now have this HUD located at `tf/custom/minimal-class-selection-hud`.

Restart TF2 and everything should work.

## Disclaimers

- I'm a noob at making HUDs. I don't use custom HUDs, and I haven't cared about them until this workaround for extending spectate.
- I'm likely to test out cleaning up more of the original HUD spec. If anyone sees opportunities to clean up more of the original KBNHud stuff, please let me know.
  - E.g. Using the pin logic improved stuff a lot, but I only touched the minimal stuff necessary to get it working.
  - E.g. KBNHud pushes a lot of the default elements off screen to "remove" them. Maybe there are cleaner ways?

## Thanks

- [@Jotunn](https://gamebanana.com/members/1247574) for making a HUD with a super clean, minimal class selection screen.
- [@JarateKing](https://github.com/JarateKing) for the [TF2-Hud-Reference](https://github.com/JarateKing/TF2-Hud-Reference) docs.
