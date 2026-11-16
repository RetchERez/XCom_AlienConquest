# X-COM: Alien Conquest

An unofficial alien-side campaign for OpenXcom Extended. Command UFOs, build hidden bases, choose operations across Earth, and fight X-COM when it responds.

## Download

Download the single [v1.1.1 game ZIP](https://github.com/RetchERez/XCom_AlienConquest/releases/download/v1.1.1/AlienConquest_v1_1_1.zip). It contains English and Russian, with English selected by default:

- **AlienConquest_v1_1_1.zip** is the Windows game package with both languages and both guides

The executable is unchanged from v1.0. Its [matching source and build kit](https://github.com/RetchERez/XCom_AlienConquest/releases/download/v1.0/AlienConquest_v1_0_Source_and_Build_Kit.zip) remains available. The automatic GitHub “Source code” archive is only a snapshot of this repository.

## Install

1. Extract the game ZIP to a writable location
2. From your own copy of **X-COM: UFO Defense**, copy `GEODATA`, `GEOGRAPH`, `MAPS`, `ROUTES`, `SOUND`, `TERRAIN`, `UFOGRAPH`, `UFOINTRO`, and `UNITS` directly into `AlienConquest/UFO`
3. Run `AlienConquest/openxcom.exe` and start a new game

For example, `C:\AlienConquest\UFO\GEODATA` is the expected layout. The game ZIP does not include the original game data. You do not need a separate OpenXcom installation.

The game package includes `README.txt` for installation and play instructions, plus separate linked walkthroughs in `Alien Conquest Game Guide.html` and `Alien Conquest Game Guide RU.html`.

To play in Russian, open **Options**, choose **Video**, set **Display Language** to **Russian**, and select **OK**. The package includes [Generation_G_ZERO's in-game translation](Language/ru.yml), with the four X-COM air patrol entries completed. Some custom interface labels are embedded in the executable and remain in English, including the operation picker and the Geoscape's `OPERATIONS` button.

Read the [English guide](https://retcherez.github.io/XCom_AlienConquest/) or the [Russian guide](https://retcherez.github.io/XCom_AlienConquest/ru/) online. Each page links to the other, and both standalone guides are included in the game ZIP. The Russian guide was prepared separately from Generation_G_ZERO's in-game translation.

## Licensing and attribution

Russian translation by **Generation_G_ZERO**. Alien Conquest by **RetchERezzed**.

The included modified OpenXcom executable is distributed under the GNU GPL, with its matching source in the source and build kit. The packages also include notices for bundled runtime libraries and other components in `AlienConquest/Licenses`. X-COM: UFO Defense data is not included and must come from the player's own copy. This is an unofficial project and is not affiliated with the X-COM rights holders.
