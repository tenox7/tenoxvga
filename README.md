# ECL2VGA Adapter for Atari TT 030 High Resolution Mode

TenoxVGA is an adapter that lets you use a standard LCD flat panel or a CRT monitor with Atari TT built-in video card in TT-HIGH mode (1280x960). You can think of it as TTM194 or TTM195 monitor replacement or ECL to VGA video signal converter.

Atari TT traditionally lets you use VGA monitors in ST and TT low to medium resolutions. The maximum you can get on a standard monitor or a flat panel is 640x480 with a rather large white border around. In order to go any higher than that you need to have a special ECL monitor such as TTM194 / TTM195, or a VME bus graphics card. These are nowadays rather hard to come by. This project was conceived to fix this issue. There are few other projects that convert ECL to TTL signal. Unfortunately they only allow non-Atari ECL CRTs such as EIZO to be used in TT-HIGH mode. This adapter is a full signal conversion from ECL to VGA and allows you to use any standard VGA monitor or flat panel.

The adapter plugs in directly to the Atari TT monitor port and switches the computer in to TT-HIGH mode. Just connect your standard LCD panel or CRT monitor, no drivers, configuration changes or opening the case / soldering required. TenoxVGA requires a 12V external power supply to operate. A wall adapter is available as an option. It is possible to draw power from TT internal PSU by using Y splitter cable for HDD power. Also the device plugs directly to Atari TT video port which requires some additional space on back of the computer. If this is a problem we also sell a short VGA cable that can go between Atari and the adapter.

## Technical Specifications:

```
Input Port: Atari TT DSUB Video port
Output Port:Standard VGA 15 pin DSUB
Resolution: 1280 x 960
Colors: 2 (BW), 1 BPP
Aspect ratio: 4:3
H. Sync: 71.911 KHz
V. Sync: 71.624 Hz
Power Source: external 12V DC, Centre Positive
DC Power Plug: 2.1mm ID x 5.5mm OD x 9.5mm plug 
Case Dimensions: 85mm x 41mm x 21mm
```

## Credits:
* Copyright © 2013 by Antoni Sawicki <as@tenoware.com>
* The device was designed and is manufactured by MSDUS http://www.msdus.com/

## License:
Apache 2.0