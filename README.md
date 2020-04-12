# BlueGorilla
Fork of the [Iceape-UXP Internet Suite](https://wiki.hyperbola.info/doku.php?id=en:project:iceape-uxp). I forked this to learn how a classic Mozilla application works and also because I feel that Iceape-UXP does not get the love from the Hyperbola developers it deserves. For example, at the time of this writing the last commit to Iceape-UXP was 3 months ago. The last commit to Iceweasel-UXP was about a month ago.

## Differences from Iceape-UXP
### ONGOING means this is a continuous task that is not a one time change
* DONE: All build dependencies in one repository. No need to Download Icedove-UXP source code then put Iceape-UXP inside of that.
* ONGOING: Patches ported from [Binary Outcast's browser and email applications](https://github.com/binaryoutcast/binoc-central).
* TODO: Compatibility with both SeaMonkey and Iceape-UXP GUIDs for addons.
* DONE: New settings directory: ~/.djames/bluegorilla
* DONE: Replace iceape-uxp branding with new branding.
* TODO: Replace old SeaMonkey icons with new icons
* ONGOING: Patches ported from upstream Iceape-UXP as well as [Icedove-UXP](https://wiki.hyperbola.info/doku.php?id=en:project:icedove-uxp).
* TODO: Fix issues when building Lightning calendar extension. Currently you have to install the .xpi after building, which is not user friendly

## Patches to UXP
TODO: There will be .patch files that should be applied before building in the patches directory

## Build Instructions
TODO. See [here](https://wiki.hyperbola.info/doku.php?id=en:project:iceape-uxp) for starter instructions. Compiler version support is essentially the same as [Pale Moon's build instructions](https://developer.palemoon.org/build/linux/). I do not support Windows or Mac builds.
