# X-COM: Alien Conquest

An unofficial alien-side campaign for OpenXcom Extended. Command UFOs, build hidden bases, choose operations across Earth, and fight X-COM when it responds.

## Download

Download the single [v1.1 game ZIP](https://github.com/RetchERez/XCom_AlienConquest/releases/download/v1.1/AlienConquest_v1_1.zip). It contains English and Russian, with English selected by default:

- **AlienConquest_v1_1.zip** is the Windows game package with both languages

The executable is unchanged from v1.0. Its [matching source and build kit](https://github.com/RetchERez/XCom_AlienConquest/releases/download/v1.0/AlienConquest_v1_0_Source_and_Build_Kit.zip) remains available. The automatic GitHub “Source code” archive is only a snapshot of this repository.

## Install

1. Extract the game ZIP to a writable location
2. From your own copy of **X-COM: UFO Defense**, copy `GEODATA`, `GEOGRAPH`, `MAPS`, `ROUTES`, `SOUND`, `TERRAIN`, `UFOGRAPH`, `UFOINTRO`, and `UNITS` directly into `AlienConquest/UFO`
3. Run `AlienConquest/openxcom.exe` and start a new game

For example, `C:\AlienConquest\UFO\GEODATA` is the expected layout. The game ZIP does not include the original game data. You do not need a separate OpenXcom installation.

The game package includes `README.txt` for installation and play instructions, plus `Alien Conquest Game Guide.html` for a linked walkthrough.

To play in Russian, open **Options**, choose **Video**, set **Display Language** to **Russian**, and select **OK**. The package includes [Generation_G_ZERO's translation](Language/ru.yml), with the four X-COM air patrol entries completed. Some custom interface labels are embedded in the executable and remain in English, including the operation picker and the Geoscape's `OPERATIONS` button. The detailed HTML guide remains in English.

Read the [complete game guide online](https://retcherez.github.io/XCom_AlienConquest/). The same standalone guide is included in the game ZIP.

## Licensing and attribution

Russian translation by **Generation_G_ZERO**. Alien Conquest by **RetchERezzed**.

The included modified OpenXcom executable is distributed under the GNU GPL, with its matching source in the source and build kit. The packages also include notices for bundled runtime libraries and other components in `AlienConquest/Licenses`. X-COM: UFO Defense data is not included and must come from the player's own copy. This is an unofficial project and is not affiliated with the X-COM rights holders.
