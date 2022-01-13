
![Chiaki Logo](assets/chiaki_wide.png)

# Chiaki

[![AppVeyor Build status](https://ci.appveyor.com/api/projects/status/jwyohbj6ammexdld?svg=true)](https://ci.appveyor.com/project/Egoistically/chiaki) [![builds.sr.ht Status](https://builds.sr.ht/~thestr4ng3r/chiaki.svg)](https://builds.sr.ht/~thestr4ng3r/chiaki?)


Fixed YUV420P to RGB conversion, which produced color inaccuracies.

**Original repo**: https://git.sr.ht/~thestr4ng3r/chiaki.

## Comparisons
A few image comparisons, since it might be hard to notice (otherwise they would've fixed it already?).

### Bloodborne
Original Chiaki
![Original Chiaki](assets/comparisons/bloodborne_original.png)
Fixed
![Fixed Chiaki](assets/comparisons/bloodborne_fixed.png)

### Remote Package Installer
Original Chiaki
![Original Chiaki](assets/comparisons/rpi_original.png)
Fixed
![Fixed Chiaki](assets/comparisons/rpi_fixed.png)
Capture Card
![Capture Card](assets/comparisons/rpi_elgato.png)
(Credit to MODDED WARFARE)

## Download
Download the latest release from here: https://github.com/Egoistically/chiaki/releases/latest.

If you want to patch it yourself, [here's the the code changed](https://github.com/Egoistically/chiaki/blob/master/gui/src/avopenglwidget.cpp#L32) (adapted from here: https://stackoverflow.com/q/55930123).

Because AppVeyor updates their images every so often, some changes might need to be made in the future.