# Oneiric Quest - Virtual Reality Samba de Amigo Emulator

<div align="center">
  <a href="http://www.youtube.com/watch?v=XiwWT4TSFoo"><img width="510" height="310" src="https://github-production-user-asset-6210df.s3.amazonaws.com/22997468/254255425-a592ebef-eaaa-4986-8887-0f3f48ebb22e.png" alt="Oneiric Quest YouTube promo video"></a>

  <img width="310" height="310" src="https://raw.githubusercontent.com/AltoRetrato/Oneiric-Quest/main/images/cover.jpg" alt="A Virtual Reality screenshot of a player holding virtual maracas and playing Samba de Amigo for the Dreamcast on a Samba de Amigo Ver. 2000 arcade cabinet">
</div>


This project is a virtual reality emulator for the Sega Dreamcast games _Samba de Amigo_ and _Samba de Amigo: Ver. 2000_. It allows you to play Samba de Amigo with virtual maracas in a virtual reality environment.

**Disclaimer:** This emulator is an unofficial project created by a fan and is not associated with Sega. All trademarks, game titles, and copyrights mentioned within the project belong to their respective owners.

**Please note**: Oneiric Quest is not related to the official games "Samba de Amigo: Party Central" or "Samba de Amigo" for the Meta Quest. For official information about those games, please visit [https://sambadeamigo.sega.com/](https://sambadeamigo.sega.com/).

## Alpha Version Notice

The current version is an alpha release, which means it is a work in progress and may have rough edges. While I strive to provide the best experience possible, please be aware that some features are incomplete or subject to bugs. Feedback and bug reports are appreciated.

## Table of Contents

- [Release History](#release-history)
- [Requirements](#requirements)
- [Installation and Configuration](#installation-and-configuration)
- [Roadmap / To-Do List](#roadmap--to-do-list)
- [Contributing and Support](#contributing-and-support)
- [Thanks](#thanks)
- [Legal Information](#legal-information)

## Release History

- (2023-07-18) **Alpha 0.1.0**

## Requirements

Before running Oneiric Quest, ensure that you have the following:

- A virtual reality headset (e.g., Oculus Rift, Meta Quest / Meta Quest 2, HTC Vive, etc.) that can be connected to a Windows PC.
- A Windows PC capable of running virtual reality applications.
- A legally obtained disc image of _Samba de Amigo_ or _Samba de Amigo: Ver. 2000_ for the Dreamcast (not provided by this project).

## Installation and Configuration

To install and configure Oneiric Quest:

1. Download the latest release of Oneiric Quest from the [Releases page](https://github.com/AltoRetrato/Oneiric-Quest/releases).
2. Unpack the file and copy the game disc image into `Plugins\UnrealLibretro\MyROMs\sda\sda.gdi`

Better local multiplayer support might be added soon, with Player 2 using either a gamepad or the keyboard, using the following keyboard mapping:
- arrow keys for D-Pad
- `[Z]` for button A
- `[X]` for button B
- `[A]` for button X
- `[S]` for button Y
- `[Enter]` for Start

For a better experience for Player 2, set the game to use control `Type B` (start the game, go to Options, Control Settings). Then you can use keys `[E][D][C]` and `[O][K][M]` on a QUERTY keyboard for a more intuitive play. `Type B` also improves gamepad gameplay, IMO.

Just keep in mind that playing Samba de Amigo without maracas is an unforgivable sin, a heresy against the very essence of those sacred instruments!

For a better shake detection, shake the maracas towards the screen.

## Roadmap / To-Do List

Planned features (subject to change, and that might never be implemented):

- Develop a better shake detection algorithm.
- Add interface for game selection and configuration of emulator options.
- Internationalization.
- Automatic translation of Samba de Amigo: Ver. 2000 into English.
- Multiplayer support (local and remote).
- Add support for additional Dreamcast games and controllers (e.g., Fishing Controller, DreamParaPara, ...).
- Support custom songs, including songs from other versions or even other games.
- Maybe native Quest 2 (or at least Quest 3) support.
- Linux and Mac support.

## Contributing and Support

If you encounter any issues or have any questions, suggestions or feedback regarding Oneiric Quest, please feel free to [open an issue](https://github.com/AltoRetrato/Oneiric-Quest/issues) or send a pull request.

## Thanks

Oneiric Quest would not be possible without the incredible and amazing hard work of the following projects:

- [Flycast](https://github.com/flyinghead/flycast): a multiplatform Sega Dreamcast, Naomi, Naomi 2 and Atomiswave emulator
- [UnrealLibretro](https://github.com/N7Alpha/UnrealLibretro): a Libretro Frontend for Unreal Engine
- [Unreal Engine](https://www.unrealengine.com/)

## Legal Information

This project is a fan creation and is not affiliated with Sega. Please note:

- No Dreamcast BIOS file is provided by nor is required for this project to run.
- Oneiric Quest is an unofficial project and does not endorse or encourage piracy.
- The emulator requires (but doesn't provide) a Dreamcast game disc image to play Samba de Amigo.
- This project is provided "as is," without warranty of any kind, express or implied. I am not responsible for any damages or legal issues that may arise from the use of this software.
