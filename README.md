# AirMarWeatherUnderground

A small Win32 program that simply reads a COM port for NMEA0183 strings sent by 
an AirMar 110WX (or similar) weatherstation.
It then either outputs the data to a file that is compatible with several popular
weather programs to pick up or it sends it directly to WUnderground.com website.

## Build

Compiling requires Microsoft Visual Studio 2012 or newer.  May work on older tools.
Also requires Microsoft Windows SDK compatible with building X64 components.  
To compile, run NMAKE.

## License

AirMarWeatherStation is available under the MIT license.

## System requirements

Currently compiles just for Windows X64. It would be fairly trivial to compile
a 32 bit version and/or convert to UNICODE for multilanguage support.
