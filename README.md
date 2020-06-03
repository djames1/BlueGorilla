# BlueGorilla
Fork of the [Iceape-UXP Internet Suite](https://wiki.hyperbola.info/doku.php?id=en:project:iceape-uxp). I forked this to learn how a classic Mozilla application works and also because I feel that Iceape-UXP does not get the love from the Hyperbola developers it deserves.

## Differences from Iceape-UXP
### DONE
* DONE: All build dependencies in one repository. No need to Download Icedove-UXP source code then put Iceape-UXP inside of that.
* DONE: New settings directory: ~/.bluegorilla/bluegorilla
* DONE: Replace iceape-uxp branding with new branding.
* DONE: Apply patches from SeaMonkey 2.49.5. Iceape-UXP was a fork of SeaMonkey 2.49.4.
* DONE: Remove Iceape-UXP user agent override
* DONE: Replace bookmarks
* DONE: New search engines, some ported from Pale Moon, some custom
### ONGOING (Not a one time change/constantly being worked on)
* ONGOING: Patches ported from [Borealis Navigator](https://github.com/binaryoutcast/binoc-central), which is based on the browser component of SeaMonkey.
* ONGOING: Patches ported from Iceape-UXP as well as [Icedove-UXP](https://wiki.hyperbola.info/doku.php?id=en:project:icedove-uxp).
* ONGOING: Patches ported from SeaMonkey
### TODO
* TODO: Fix issues when building Iceowl/Lightning calendar extension. Currently you have to install the .xpi after building, which is not user friendly
* TODO: See if we can make all of the dependencies in the suite directory and remove the browser and mail directories.
* TODO: Include vertical tab bar addon
* TODO: Include fork of last XUL based enigmail addon
* TODO: Different versioning scheme
* TODO: New GUID
* TODO: Put UXP in the platform directory instead of Mozilla directory
### UNDECIDED
* UNDECIDED: Accept SeaMonkey GUID for addons
* UNDECIDED: Include fork of XPFE-classic (Netscape theme) for SeaMonkey

## Build Instructions
### Mac and Windows builds not supported. Please let me know if they work.
* Copy mozconfig.sample to .mozconfig
* Edit .mozconfig as needed
* ./mach build
* You can then run the application by running ./mach run, or package it by running ./mach package

## Gentoo Ebuild
There is a Gentoo live ebuild located in my [UXP Overlay](https://github.com/djames1/uxp-overlay).
