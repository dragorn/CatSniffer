# CatSniffer

CatSniffer is an original multiprotocol and multiband board made for sniffing and communicating with IoT (Internet of Things) devices. It was designed as a highly portable USB stick that integrates the new generation of the chips TI CC1352, Semtech SX1262, and Microchip SAMD21E17. 

This board is an auditing tool for security researchers looking into IoT security. The board can be used with different types of software including third-party sniffers such as [SmartRF Packet Sniffer](https://www.ti.com/tool/PACKET-SNIFFER), [Sniffle](https://github.com/nccgroup/Sniffle), [zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt), [Z-Stack-firmware](https://github.com/Koenkk/Z-Stack-firmware), [our custom firmware](https://github.com/ElectronicCats/CatSniffer/tree/master/firmware), or you can even write your own firmware for your hacking needs.

This work was inspired by our friend's work [Michael Ossmann](https://twitter.com/michaelossmann) as a tribute to his outstanding job in [Greatscott Gadgets](https://greatscottgadgets.com/), making devices like the YardStick, GreatFET, HackRF, and Ubertooth.

<a href="https://electroniccats.com/store/catsniffer/">
  <img src="https://electroniccats.com/wp-content/uploads/badge_store.png" width="200" height="104" />
</a>

## Protocols
- Thread
- Zigbee 
- Bluetooth 5 Low Energy (BLE)
- IEEE 802.15.4g 
- 6LoWPAN (IPv6 over Low power Wireless Personal Area Networks) 
- Sub 1GHz and patented systems
- LoRa/LoRaWAN
    

## Features
- "The SimpleLink™ CC1352P device is a multiprotocol and multi-band Sub-1 GHz and 2.4-GHz wireless microcontroller (MCU) supporting Thread, Zigbee®, Bluetooth® 5.2 Low Energy, IEEE 802.15.4g, IPv6-enabled smart objects (6LoWPAN), MIOTY®, Wi-SUN®, proprietary systems".
- CatSniffer uses SAMD21E17 as a USB-UART bridge to communicate with the CC1352 chip; it's not necessary for a manual driver installation (exceptions could exist).
- Compatible OS: Windows and Linux.
- Auto program through the bootloader from TI CC (as long as it's not disabled in the code). No need for an external programmer, and it can be debugged with cJTAG through the default pin.
- Antenna SMA port for an Antenna of your choice.
- LEDs of general-purpose
- Reset button for SAMD21 & CC1352, Boot of CC1352, and one more for general purpose.


## Compatible Software
- [TI PACKET-SNIFFER-2 v1.8](https://www.ti.com/tool/download/PACKET-SNIFFER-2)
- [Sniffle](https://github.com/nccgroup/Sniffle)
- [zigbee2mqtt](https://github.com/Koenkk/zigbee2mqtt)
- [Z-Stack-firmware](https://github.com/Koenkk/Z-Stack-firmware)


## Prerequisites
- Git
- Python 3
- CCS version: The packet sniffer firmware has been tested with CCS 10.2.
- SimpleLink CC13x2 and CC26x2 SDK 3.40.00.02


## Note
This kit is designed to allow Product developers to evaluate electronic components, circuit, or software associated with the kit to determine whether to incorporate such items in a finished product and Software developers to write software applications for use with the end product. This kit is a developer product and when assembled may not be resold or otherwise marketed unless all required FCC (or any other local authority) equipment authorizations are first obtained. Operation is subject to the condition that this product not cause harmful interference to licensed radio stations and that this product accept harmful interference.

## License

Electronic Cats invests time and resources providing this open source design, please support Electronic Cats and open-source hardware by purchasing products from Electronic Cats!

Designed by Electronic Cats.

Firmware released under an GNU AGPL v3.0 license. See the LICENSE file for more information.

Hardware released under an CERN Open Hardware Licence v1.2. See the LICENSE_HARDWARE file for more3 april 2021Electronic Cats is a registered trademark, please do not use if you sell these PCBs.

3 April 2021
