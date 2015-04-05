This is a fork of olaoutput to work with OLA installed through HomeBrew rather than MacPorts.

olaoutput is an object for Cycling 74's Max visual programming environment which enables the transmission of data to OLA (Open Lighting Architecture), a service allowing transmission and receiving of DMX information via a variety of hardware (Entec DMX USB Pro, uDMX, DMX King) and IP protocols (Art-Net, sACN, ShowNet).

olaoutput currently works with Max 5 through 7 (32-bit and 64-bit) on OS X. OLA is required at development and runtime. To install OLA where this build
expects to find it (and to easily keep it up to date), first [install Homebrew](http://brew.sh), and then run `brew install ola --universal`.

Cycling 74's [Max SDK](https://cycling74.com/downloads/sdk/) is required for development only: download it, and copy its `c74support` folder to the top level of this checkout (the same folder in which this document is found).

See the https://wiki.openlighting.org/index.php/OlaOutput_Max_External for usage information.
