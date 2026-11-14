# KSP Retooled

KSP Retooled is a community made continuation of Kerbal Space Program.
It aims to bring KSP into the modern age, with Unity 6.7 and various performance
improvements that can be made easier.  Now that we can directly change KSP's
source, many things become possible.

We have taken special care to keep it compatible with stock KSP so that you
can continue to use many of the mods that you know and love.

## Installation
Retooled needs a special launcher to install. You can find the installer for
your OS below:
* [Windows](https://github.com/KSP1Retooled/launcher/releases/latest/download/KSPRetooled.Launcher-windows-x64-Setup.exe)
* [Linux](https://github.com/KSP1Retooled/launcher/releases/latest/download/KSPRetooled.Launcher-linux-x64.AppImage)
* [Macos (Arm64)](https://github.com/KSP1Retooled/launcher/releases/latest/download/KSPRetooled.Launcher-macos-arm64.dmg)
* [Macos (x86-64)](https://github.com/KSP1Retooled/launcher/releases/latest/download/KSPRetooled.Launcher-macos-x64.dmg)

The launcher will take care of patching KSP with any retooled version. Once the game
is patched you can either run KSP through the launcher or start through Steam/CKAN
like you normally do. Do note that MacOS Gatekeeper may not initially trust our patcher,
but should have no issues after you authorize it once.

## Reporting Issues
Running into an issue? Have a bug fix request or feature request?
[You can file an issue!](https://github.com/KSP1Retooled/retooled/issues).

## Mod Support
If you are planning on running with mods, you should know that while most mods work on Windows
and Linux just fine, Mac users may run into issues with visual mods due to missing shaders from 
this builds transition from OpenGL to the Metal API.  We expect that to get better over time 
though.

Otherwise, for the moment most mods work!  You can generally set your CKAN (yes it works, we 
identify as 1.13.0) compatibility to 1.12.5 and other than hardlocks, things load!  Not EVERYTHING
though.  Hardcoded version locks will remain an issue until authors deal with them.
