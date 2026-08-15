# grscheller/miscInstall

Repository to maintain and install miscellaneous configuration files for
software development on either Linux or Windows 11. At this point
it is not clear whether to have separate scripts for Windows and Linux.

## Installation scripts

A dash based POSIX shell script, [develInstall](bin/develInstall),
installs the "dotfiles" from the cloned repo into the appropriate native
locations on Linux. Script works from a MSYS2 environment on Windows 11.

- nvimInstall has shebang `#!/bin/dash`
  - on PopOS `/usr/bin/sh -> dash`
  - on MSYS2 I install dash with `pacman -S dash`
  - will work just fine if shebang is changed to `#!/bin/sh`
- does more than just install, see `miscInstall --help` 

### Note

Windows 11 integration is still very much a work in progress. Probably
will not mirror the Linux version.

## Public Domain Declaration

To the extent possible under law,
[Geoffrey R. Scheller](https://github.com/grscheller)
has waived all copyright and related or neighboring rights
to [grscheller/dotfiles](https://github.com/grscheller/dotfiles).
This work is published from the United States of America.

See [LICENSE](LICENSE) for details.
