# Support Definitions, Criteria and Relationships 

## Overview

As mentioned in [our announcement](https://www.armbian.com/newsflash/armbian-needs-your-help/), made adjustments to ease the burden on the team, make the meaning supported" status of an SBC clear to the community and vendors.

Support Status from Lowest to Highest are the following:

1. EOL
2. CSC
3. WIP
4. Standard
5. Gold
6. Platinum

## EOL - End of Life

EOL Devices are not under active development by any entity or community.   Can be removed from Armbian code base at any time.  Left as a courtesy in case a community member wants to attempt to resurrect development.

### No benefits provided

## Community Support

Community Support SBCs are exclusively supported by the community.

**No Images** are provided for Community Supported SBCs 
* no stable
* no periodic / nightly
* users must use Armbian Build Framework to produce an image

### Benefits for Community Support

* Pull Requests are accepted
* Armbian Team will interact on Github with contributors considered to be acting in Good Faith
* Periodic / Nightly debian packages are built and published into Armbian's Community Apt repository

### Requirements for Community Support

* Patch or component does not break Armbian Build Framework
* Patch or component does not break build of Supported or other CSCs
* Generally considered to "work most of the time"
* Generally considered to recieve periodic maintenace from community.


## WIP - Work in Progress

WIP status is for when a maintainer has commited to an SBC, but is not ready to ship stable images.

Benefits of Community Supported SBCs apply to WIP.

### Additional Benefits provided for a WIP SBC

* periodic / nightly CLI images are published by Armbian
* Armbian will work with SBC maintainer to assure compatiblity within the [Armbian Build System](https://github.com/armbian/build)
* Eligible for promotion to Standard Support

### Criteria for WIP status

* must satisfy standard support criteria
* must show active development

## Armbian Standard Support

### Benefits provided for a Supported SBC

* Armbian will publish and distribute "stable" CLI images through its mirror network
* Armbian will publish and distribute "periodic / nightly" CLI and Desktop images
* Armbian will work with SBC maintainer to assure compatiblity within the [Armbian Build System](https://github.com/armbian/build)
* Armbian will provide the team's unique expertise to assist maintainer with general challenges
* Best-effort compensation will be provided to maintainer from the "Armbian Community Fund"

### Criteria for Supported

For an SBC to be considered supported:

* A named individual as "maintainer" along with GitHub ID must be clearly identifed in the [Board Configuration File](https://github.com/armbian/build/tree/master/config)
* A named individual must commit to providing "Best Effort" support for their SBC on the Armbian forums
* Maintainer must participate in the [Release Process](https://docs.armbian.com/Process_Release-Model/#release-coordinating)
* Maintainer must sign-off that device has been tested, is stable, and ready for release during release process.
* Maintainer must have physical access to the SBC they're supporting

Additional Caveats:

* Supported is **not** applied to a "family" or group of related SBCs.  It is per SBC.
* A maintainer can support multiple devices, but must satisfy all requirements above, per SBC.
* Any individual can be a maintainer for a standard support SBC
* Missed released will result in immediate forfeit of "Armbian Supported" status and demotion to CSC status unless Armbian team grants exemption.


## Gold and Platinum Support

Gold and Platinum Support are intended to be business relationships with the Armbian project or team, and are out of scope of this document.   Please connect with Armbian team for more information.