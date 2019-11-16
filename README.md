# Barcode reader Cartridge for the 2019 Hackaday Superconference Badge

![Barcode Cartridge render](https://github.com/flummer/supercon2019-barcodecartridge/raw/master/IMAGES/front_back_render.png "Barcode Cartridge render")

This is designed to use the GM65 barcode reader module, that supports both 1D and 2D barcodes and is able to read from a screen (eg. a smartphone or the screen on the badge)

This cartridge is based on the [unofficial Superconference 2019 Badge Cartridge template](https://github.com/flummer/supercon2019-cartridgetemplate) and hence include the w25q128 SPI flash and a 100nF cap in addition to the 2x20 pin angled male pin header for the badge connection. The flash allows badge configurations and firmware specific to this cartridge to be loaded from the cartridge it self making it selfcontained.

## Version 1.2 update

This updated version fixes an error in the pin connections on the cartridge connector (the two columns was flipped for some signals).

## Special note about the original version

If you want to use a PCB based on the original version with incorrect connections, it is possible to make a hardware hack on the 20x2 angeled header, where you move the pins around and bend some of them a bit, very precisely.

## License

The contents of this repository is released under the following licence:

 * the "Creative Commons Attribution-ShareAlike 4.0 International License"
   (CC BY-SA 4.0) full text of this license is included in the LICENSE file
   and a copy can also be found at
   http://creativecommons.org/licenses/by-sa/4.0/
