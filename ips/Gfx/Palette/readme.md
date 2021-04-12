# Fix soldier palette

Original            |  Fixed
:-------------------------:|:-------------------------:
![original palette](./images/Landstalker-gfx-palette1.png "original palette") | ![fixed palette](./images/Landstalker-gfx-palette2.png "fixed palette")


## Technical notes

Updated sprite data to use palette 1 by changing bits 6-7 of the second byte.

_ | _            |  _
:-------------------------:|:-------------------------:|:-------------------------:
Data | 93<span style="color:red; background: black">9D</span>200014328300 | 93<span style="color:green; background: black">5D</span>200014328300
Byte 2 | <span style="color:red; background: black">10 (2) </span>011101 | <span style="color:green; background: black">01 (1) </span>011101
  
<p />

## Offset

Rom            |  _
:-------------------------:|:-------------------------:
Europe| $0215A6
France| $02159A
Germany| $0215A0
Japan| $021552
USA| $0215A6
