# Domi's CS2 Config
This is my fully personalized "modular" cs2 config.
It can be easily customized due to its modularity and should fit all the use cases, but its mainly designed to fit my use case.

## Install

### Option 1 
- Download latest release from [Releases](https://github.com/dom1torii/cs2config/releases).
- Unzip the archive into your `/game/csgo/cfg/` folder with replacing all files.
- Add -exec autoexec into your launch options.

### Option 2 (advanced)
- Make sure git is installed.
- Locate and `cd` into your `/game/csgo/cfg`
- Copy and paste commands below into your terminal 1 by 1:
```
git init
git remote add origin <repo-url>
git fetch origin
git reset --hard origin/main
```
- Add -exec autoexec into your launch options.

## Launch options
I use Linux, so my launch options are probably very different from yours if you use Windows, but here they are:

`gamemoderun mangohud SDL_VIDEO_DRIVER=wayland %command% -vulkan -high -exec autoexec`

If you're on Windows, you probably only want these:

`-high -exec autoexec`

## Credits
https://steamcommunity.com/id/r_by (desubtick binds)

