# Q-Sys-QR-Code-Generator
This is a QR code generator that does the QR encoding natively in Lua on the core, so does not require internet access.

Current features:

* Code Types:
* HTML5 UCI QR Code (Automatically updated if the IP address on the core changes.)
* iOS QR Codes
* Wifi QR Codes (A QR code to automatically join a mobile device to the wifi network.)
* Custom QR Code (A custom string encoded into a qr code. Useful for web links, or search terms.
* A custom error correction level can be selected.
* A custion version (size) of QR code can be selected.
* Up to 64 codes can be created by each component. (I challenge you to find a need for more!)
