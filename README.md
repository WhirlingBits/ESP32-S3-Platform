# ESP32-S3-Platform
Schematics of basic ESP32-S3-WROOM platform with versatile power management for 12V and 5V supply and microSD card slot. The board offers 2 USB-C receptables, one connecting to a USB-2-UART converter (CP2102) feeding the genuine UART0 on ESP32-S3 and another directly connecting to the ESP32-S3's USB OTG port. The board may be powered by one of the USB ports (VBUS) or with an external poweer supply connected via BarrelJack. Thanx to the buck/boost capability of the LTC3111 used the external power input voltage my supply a voltage between 3..15V

Alternatively it is possible to use an external battery controller (e.g. Babysitter) which is connected on J5 whereas J5.4 (+5VD) will be the input for the controller and J5.1,2 the output.
