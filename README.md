# PCSX-Reloaded
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/iCatButler/pcsxr?branch=master&svg=true)](https://ci.appveyor.com/project/iCatButler/pcsxr)
[![Travis Build Status](https://travis-ci.org/iCatButler/pcsxr.svg?branch=master)](https://travis-ci.org/iCatButler/pcsxr)

PCSX-Reloaded is a forked version of the dead PCSX emulator, with a nicer
interface and several improvements to stability and functionality.

PCSX-Reloaded uses the PSEMU plugin interface to provide most functionality;
without them, you will not be able to use it to play games. PCSX-Reloaded
provides a number of plugins to provide basic functionality out of the box.

PCSX-Reloaded has a very capable Internal HLE BIOS that can run many games
without problems. It is recommended that you use it. However, if you own a
real PlayStation, you may be able to use your own BIOS image. PCSX-Reloaded
will find it in ~/.pcsx/bios/ or /usr/share/psemu/bios/ if you place it there.
This can improve compatibility, especially with certain games and with the
use of memory cards.

See the doc/ folder in the source, or /usr/share/doc/pcsx/ on Debian systems,
for more detailed information on PCSX-Reloaded. A UNIX manpage is also
available.
