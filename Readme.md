-=(IremM107_Senhor notes)=-

Tested: Working Video 720p, 1080p & Sound

___
# Irem M107 Core

![](docs/fire_barrel.png)

This is the MiSTer FPGA core for the Irem M107 arcade system (http://www.system16.com/hardware.php?id=749). It is almost entirely based on the M92 core implementation (https://github.com/MiSTer-devel/Arcade-IremM92_MiSTer) with changes to support an additional tile layer and more advanced sprite rendering.

## Controls
All of the games use standard 8-way input with two buttons with the exception of Superior Soldiers which uses six button input. Several of the games support 3 or 4 players but you will need to change a DIP switch in the DIP switch menu to enable that. By default the button buttons are mapped to the MiSTers SNES-like layout as B,A,X,Y,L,R. The Coin and Start buttons are mapped to Select and Start. There are two additional buttons that can be mapped that are not mapped by default. P2 Start maps the the second players start button. The only purpose this serves is for accessing the service menu with a single controller since most games require pressing P1 and P2 start to access it. The second unmapped button is Pause which pauses the core.

Standard MAME keyboard controls are also supported for up to 4-players.


## Thanks
Many people, knowingly or not, contributed to this work.
- Grinning Cat and XtraSmiley for helping me acquire an M107 PCB.
- Mark, for his R-Type Leo PCB and his support through the years.
- @sorgelig, for developing and maintaining MiSTer.
- @RobertPeip, for the v30mz cpu I am using as the basis for the v33 & v35.
- @jotego, for the YM2151 implementation and analog adjustment module.
- @ArtemioUrbina, for their support building [MDfourier](https://junkerhq.net/MDFourier/) tests.
- @zakk4223, for hiscore support.
- @birdybro, @Toryalai1 & @wwark for MRA help.
- Sanborn, for help with the docs.
- The people from PLD Archive collecting and archiving PAL information https://wiki.pldarchive.co.uk/index.php?title=Category:Irem_M107
- The MiSTer FPGA discord server for support, advice and testing.


