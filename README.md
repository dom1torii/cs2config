# Domi's CS2 Config
This is my fully personalized "modular" cs2 config.  
It can be easily customized due to its modularity and should fit all the use cases, but its mainly designed to fit me.

## Features
- Modularity - everything is in its place where it can be easily changed.
- Made mostly for movement with the most recent binds.
- Server connect aliases (*servers to list them all).
- Easy to install.

## Help
This config has some useful command-like aliases you might wanna use. All of them start with `*`.  
Typing `*help` will show all the available commands:
```
=======================================================
<Config help>
Info commands:
> *help ---- Config help (you are here).
> *hello --- Show hello message.
> *servers - List available server connection aliases.
Mode commands:
> *vnlkz - Switch to vanilla kz mode.
> *ckz --- Switch to classic kz mode.
> *demo -- Switch to demo viewing mode.
=======================================================
```

## Install

> [!TIP]
> Before installing the config, you might want to make a backup of your old config.

### Option 1 
- Download latest release from [Releases](https://github.com/dom1torii/cs2config/releases).
- Unzip the archive into your `/game/csgo/cfg/` folder with replacing all files.

### Option 2 (advanced)
- Make sure git is installed.
- Locate and `cd` into your `/game/csgo/cfg/`
- Copy and paste commands below into your terminal 1 by 1:
```bash
git init
git remote add origin https://github.com/dom1torii/cs2config.git
git fetch origin
git reset --hard origin/main
```

## Launch options
I use Linux, so my launch options are probably very different from yours if you use Windows, but here they are:

`gamemoderun mangohud SDL_VIDEO_DRIVER=wayland %command% -high -disable_workshop_command_filtering`

If you're on windows you probably only want this to be able to exec while on the server:

`-disable_workshop_command_filtering`

## Crosshairs
Default: `CSGO-sOyFo-sVEif-Ap49Y-MTZ2J-D7kXM`  
<img width="805" height="190" src="https://github.com/user-attachments/assets/f1904711-e3f6-4bad-a678-bc8df110979c" />

Dot: `CSGO-w8TKi-L2UPG-BckOn-wPNSL-zSqhH`  
<img width="805" height="190" src="https://github.com/user-attachments/assets/defd192f-fe66-44a2-a136-74e3bcf45221" />




## Notes

### Checkpoints + Teleports
To make [cptp.cfg](https://github.com/dom1torii/cs2config/blob/main/utils/cptp.cfg) work, you will need to make a script that pastes contents of your clipboard into `/cfg/utils/pos.cfg`

[Example script for linux with wl-clipboard](https://gist.github.com/dom1torii/4d5fa8d97bc9d1288c0396b4d91fe44d)

## Credits
https://steamcommunity.com/id/dom1tori 

