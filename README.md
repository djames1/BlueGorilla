# BlueGorilla
Fork of the [Iceape-UXP Internet Suite](https://wiki.hyperbola.info/doku.php?id=en:project:iceape-uxp). I forked this to learn how a classic Mozilla application works and also because I feel that Iceape-UXP does not get the love from the Hyperbola developers it deserves. For example, at the time of this writing the last commit to Iceape-UXP was 3 months ago. The last commit to Iceweasel-UXP was about a month ago.

## Differences from Iceape-UXP
### ONGOING means this is a continuous task that is not a one time change
* DONE: All build dependencies in one repository. No need to Download Icedove-UXP source code then put Iceape-UXP inside of that.
* ONGOING: Patches ported from [Borealis Navigator](https://github.com/binaryoutcast/binoc-central), which is based on the browser component of SeaMonkey.
* DONE: New settings directory: ~/.djames/bluegorilla
* DONE: Replace iceape-uxp branding with new branding.
* TODO: Replace iceowl-uxp branding with new branding
* TODO: Replace old SeaMonkey icons with new icons
* TODO: Remove modern theme and allow it to be installed as a separate addon
* ONGOING: Patches ported from Iceape-UXP as well as [Icedove-UXP](https://wiki.hyperbola.info/doku.php?id=en:project:icedove-uxp).
* ONGOING: Patches ported from SeaMonkey
* TODO: Fix issues when building Lightning calendar extension. Currently you have to install the .xpi after building, which is not user friendly

## Build Instructions
* Copy mozconfig.sample to .mozconfig
* Edit .mozconfig as needed
* ./mach build
* You can then run the application by running ./mach run, or package it by running ./mach package

## Gentoo Ebuild
TODO
