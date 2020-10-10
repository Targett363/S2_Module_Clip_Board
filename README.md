# S2_Module_Clip_Board
Clip in programmer/prototyping board for ESP32-S2 modules

What is it?

This board will allow you to clip in an ESP32-S2 WROOM or WROVER module for programming and testing. Slot the module into the pins where it will be held securely while you upload your code.

The Board has two USB micro sockets: The first is connected to a CP2104 USB to UART to upload of your firmware and receive serial messages. The second is directly connected to GPIO19 & 20 that are the onboard USB - & + pins.

The board can be powered from either of the USB sockets, the UART USB has a power switch and the S2 USB will directly power the board. These sockets are separated by diodes so neither can reverse power the other. The S2 USB has bridgeable solder pads so that it can be used to supply USB power if acting as OTG Host.

The CP2104 handles the USB to UART conversion as well as putting the module into "programming mode".

Where Espressif have enabled programming via the S2 USB and the module can be put in "programming mode" using the IO_0 and Reset buttons.

All GPIO pins are broken out to 2.54mm header pins. Caution should be taken as some pins are used by the WROVER module for PSRAM.

Why did you make it?

I made the V0.1 board as a personal challenge, just to see if I could. Then as I chatted with other makers I became a little more serious about designing this for more general use. V0.2 provided a reasonable working prototype and with V0.3 I think it's ready for public consumption.

What makes it special?

As far as I know, this is the only available board of it's type at the moment.

