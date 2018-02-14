# ESP32-8266-File-Download
Using HTTP and an HTML interface to download files from an ESP32/ESP8266

1. Download all files to a sketch folder.

2. Edit the Network tab and add in your SSID and PASSWORD, more if you have them.

3. Choose your IP address, currently it is fixed to 192.168.0.150

4. You can edit the logical name 'fileserver' to your requirements access the device with http://fileserver.local

5. NOTE: the Directory command is not included, this comes later.

NOTES:

The ESP32 is not reliable when using SD Cards, please ensure you know how to connect the SPI bus to the SD-Card if not using an MH-ET Live ESP32 board and a Wemos SD-Card Shield. Although pull-ups are enabled, you may need t oadd an external 4k7 pull-up too on the MSIO line.

