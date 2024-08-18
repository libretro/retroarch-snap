[![Retroarch Snap](https://snapcraft.io/retroarch/badge.svg)](https://snapcraft.io/retroarch)

# RetroArch Snap

This project creates a working snap of RetroArch.

## Current state

This package will include assets, database, cheats, joypad autoconfig, info cores, overlay and shaders.

You will need to use the Online Updater to install cores.

## Daemon mode

`snap.retroarch.service` will automatically enabled and started after installation on Ubuntu Core. On other versions of GNU/Linux to activate daemon run as root the following command:
> WARNING! For most desktop distributions this is not needed

```console
$ snap set ubuntu-frame daemon=true && snap start --enable retroarch.daemon
```
