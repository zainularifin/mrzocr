# Overview #
An Android library for optically scanning the Machine Readable Zone (MRZ) on ICAO Doc 9303 style passports and eID cards. The library
  * uses the Tesseract engine (through tess-two),
  * does camera management,
  * pre-filtering,
  * and applies MRZ specific logic

# Dependencies #
The library depends on:
  * [tess-two](https://github.com/rmtheis/tess-two)