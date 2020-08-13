# BlueGorilla
Fork of the [Iceape-UXP Internet Suite](https://wiki.hyperbola.info/doku.php?id=en:project:iceape-uxp). I forked this to learn how a classic Mozilla application works and also because I feel that development on Iceape-UXP is too slow. In addition to the below changes I also port patches from [binoc-central](https://github.com/binaryoutcast/binoc-central), [Iceape-UXP](https://wiki.hyperbola.info/doku.php?id=en:project:iceape-uxp), and upstream SeaMoney as needed.

## Differences from Iceape-UXP
### DONE
* DONE: New settings directory: ~/.bluegorilla/bluegorilla
* DONE: Replace iceape-uxp branding with new branding.
* DONE: Apply missing patches from SeaMonkey 2.49.5. Iceape-UXP was a fork of SeaMonkey 2.49.4.
* DONE: Remove Iceape-UXP user agent override
* DONE: Replace default bookmarks
* DONE: New search engines, some ported from Pale Moon, some custom
* DONE: Change version to 52.9.`number of days since Seamonkey 2.49.5 released`
* DONE: Backport ability to close tabs to the right from SeaMonkey 2.53.2
* DONE: Remove modern theme. I have no reason to maintain updates for a theme I don't even use.
### TODO
* TODO: Fix issues when building Iceowl/Lightning calendar extension. Currently you have to install the .xpi after building, which is not user friendly
* TODO: Investigate removing the mail directory, which contains most of the Icedove-UXP code.
* TODO: Include vertical tab bar addon
* TODO: Get a version of enigmail working properly
* TODO: Put UXP in the `platform` directory instead of `mozilla` directory
* TODO: Include fork of XPFE-classic (Netscape theme). Make this the default theme.

## Build Instructions
### I do not use Mac or Windows so I have no idea if builds for those platforms works.
* Copy mozconfig.sample to .mozconfig
* Edit .mozconfig as needed
* ./mach build
* You can then run the application by running ./mach run, or package it by running ./mach package

## Gentoo Ebuild
There is a Gentoo live ebuild located in my [UXP Overlay](https://github.com/djames1/uxp-overlay).
