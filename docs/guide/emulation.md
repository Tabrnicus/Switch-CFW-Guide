# Emulation (RetroArch)

!!! error "WIP"
    This article is a work in progress!

## Summary

RetroArch is a front-end for emulating a variety of games. Specifically, RetroArch is not itself an emulator, rather it loads stripped down emulators (called cores) to actually handle the brunt of the work, while providing a nice interface to interact with everything.

## Adding ROMs

### Moving to SD Card

Once you have your ROM (sourced however you want), you want to add them into a directory on your Switch's SD card. The actual location doesn't matter but it is suggested that you keep all the ROMs in one location, preferably organized into subfolders.

An example of this could be:
```
/roms/
├── arcade/
│   ├── 1942w.zip
│   └── 19xx.zip
├── gba/
│   └── Mario vs. Donkey Kong (USA).gba
└── snes/
    ├── Super Mario World (USA).sfc
    ├── Super Mario World 2 - Yoshi's Island (USA).sfc
    └── Final Fantasy III (USA).sfc
```

!!! tip "Be as Organized as You Want"
    The organization tips above are entirely optional. RetroArch will ultimately scan for compatible files in any directory you provide it, regardless of the structure. So you may be as organized or disorganized as you'd like.  

### Scanning For New Files

## Downloading Cores

While the default RetroArch installation comes with a handful of cores installed, you will likely need to download a couple. thankfully, RetroArch has a convenient way of obtaining them.

Navigate to `Main Menu` > `Online Updater` > `Core Downloader`. You should see a list of cores available for download, listing the console that they emulate, followed by the unique name in parentheses.

!!! warning "Many Cores, One Console"
    There can be many cores that emulate a given console. Each are different projects that aim to do the same thing, so naturally there can be some differences between them. Some cores emulate specific games better than others, so make sure you do some cursory research to see which core is better for your particular game. Most of the time though, any choice from the RetroArch list should be fine. The only exception to this is arcade games, as they are more sensitive to core differences.

## Running Games

### Quick Menu

## Enabling Cheats
