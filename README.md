Test center for WinDaqdashboard

1. Download and Unzip the file
2. Save a copy of C:\Program Files (x86)\DATAQ Instruments\common\WinDaq Dashboard.exe
3. Replace C:\Program Files (x86)\DATAQ Instruments\common\WinDaq Dashboard.exe with the one from Step 1)

Rev 1.3.106 is the last stable WinDaq dashboard before DI-188 support was added

Rev 1.3.207 and higher, you can add following switches to the command line to turn on/off modules

1. "debug" generates log file
2. "sendcommand" enable a drop-down menu so that one can send special commands to 2xxx and 4xxx instruments
3. "nocdc" ignore devices in CDC mode
4. "cdc" detect DI-21/41/4200 series in CDC mode 
5. "noarduino" no support for DI-188 family
6. "arduino" provides support for DI-188 family
7. "noxport" will not deal with devices based on xport module, such as DI-71x
8. "xport" will detect devices based on xport module
9. "noftdi" will not deal with devices based on FTDI controller, as as DI-245
10. "ftdi" will detect devices based on FTDI controller
11. "norabbit" will not deal with devices based on RABBIT RCM3200 module, such as DI-72/73x
12. "rabbit" will detect devices based on RABBIT RCM3200 module
13. "noudp" will not deal with UDP-based protocol, such as DI-4xxx-E
14. "udp" will allow UDP-based protocol
15. "nolibusb" will not deal with LibUSB-based protocol, such as DI-2/4xxx-U
16. "libusb" will communicate with LibUSB-based protocol
17. "libusbonly" only work with LibUSB-based protocol 

By default, arduino, nocdc, libusb, noxport, noftdi, udp, norabbit are ON.
