olaoutput is an object for Cycling 74's Max visual programming environment which enables the
transmission of data to OLA (Open Lighting Architecture), a service allowing transmission and
receiving of DMX information via a variety of hardware (Entec DMX USB Pro, uDMX, DMX King) and
IP protocols (Art-Net, sACN, ShowNet).

olaoutput currently works with Max 5 and 6 (32-bit and 64-bit) on OS X. OLA is required at development
and runtime. Cycling 74's Max SDK is required for development only. To install OLA where this build
expects to find it (and to easily keep it up to date), first [install Homebrew](http://brew.sh), and then run
`brew install ola --universal` and `brew install protobuf` to get the
[Protocol Buffer library](https://github.com/google/protobuf/) it uses to communicate efficiently with OLA.

See the https://wiki.openlighting.org/index.php/OlaOutput_Max_External for usage information.
