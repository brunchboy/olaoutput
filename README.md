This is a fork of olaoutput to work with OLA installed through HomeBrew rather than MacPorts.

olaoutput is an object for Cycling 74's Max visual programming environment which enables the transmission of data to OLA (Open Lighting Architecture), a service allowing transmission and receiving of DMX information via a variety of hardware (Entec DMX USB Pro, uDMX, DMX King) and IP protocols (Art-Net, sACN, ShowNet).

olaoutput currently works with Max 5 through 7 (32-bit and 64-bit) on OS X. OLA is required at development and runtime. To install OLA where this build
expects to find it (and to easily keep it up to date), first [install Homebrew](http://brew.sh), and then run `brew install ola --universal`.

If all you want to do is use olaoutput with Max, you are almost done! [Download](http://deepsymmetry.org/media/olaoutput-HomeBrew.zip) the binary distribution, and [install](https://wiki.openlighting.org/index.php/OlaOutput_Max_External) it as a Max external (ignoring the sections of that page which tell you how to download and install OLA, which you have already chosen to do via HomeBrew, and the version of the external linked there, which does not work with HomeBrew).

Cycling 74's [Max SDK](https://cycling74.com/downloads/sdk/) is required for development only: download it, and copy its `c74support` folder to the top level of this checkout (the same folder in which this document is found).

More usage information and an introduction about how to configure and use OLA can be found on the [home page](https://wiki.openlighting.org/index.php/OlaOutput_Max_External) of the original version of olaoutput.
