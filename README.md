# Switch

![](https://img.shields.io/badge/switch-sx--os-red.svg)
![](https://img.shields.io/badge/switch-sdfiles-orange.svg)

## Installation

You can download the latest version in a zip file: https://github.com/GreatWizard/switch/archive/master.zip

Then extract the whole zip file at the root of your SD card.

## Content

### Homebrews

- [appstore v2.0](https://github.com/vgmoose/appstorenx): Switch App Store - download/manage homebrew apps for hbmenu
- [Checkpoint v3.6.0](https://github.com/BernardoGiordano/Checkpoint/): Fast and simple homebrew save manager for 3DS and Switch
- [EdiZon v3.0.1](https://github.com/thomasnet-mc/EdiZon): A save editor for Horizon by thomasnet and WerWolv
- [EdiZon ConfigAndScripts f4b955de](https://github.com/WerWolv98/EdiZon_ConfigsAndScripts): The official EdiZon Editor Config and Editor Script repository
- [ftpd v2.3](https://github.com/mtheall/ftpd): FTP Server
- [gcdumptool v1.0.5](https://github.com/DarkMatterCore/gcdumptool): Nintendo Switch Game Card Dump Tool
- [Goldleaf v0.4](https://github.com/XorTroll/Goldleaf): 🍂 Nintendo Switch multipurpose homebrew tool
- [Homebrew Menu v3.0.1](https://github.com/switchbrew/nx-hbmenu): The Nintendo Switch Homebrew Menu
- [ldnmitm config v1.1.2](https://github.com/spacemeowx2/ldn_mitm)
- [NX-Shell v1.20](https://github.com/joel16/NX-Shell): 3DShell port for the Nintendo Switch
- [NXThemes Installer v1.3](https://github.com/exelix11/SwitchThemeInjector): A layout installer for the Nintendo Switch
- [ReiNXToolkit (2019-03-10)](https://github.com/Reisyukaku/ReiNXToolkit): A toolkit to be used with the ReiNX CFW
- [SX Dumper v1.0.3](https://sx.xecuter.com/): Dump your retail game cartridges
- Tinfoil v1.3.0: A homebrew game, update, and DLC installer

### Others

- [Switch Themes](https://suchmememanyskill.github.io/Themes/Switch_Themes/)

### Tools

- [XCI_Trimmer ed672240](https://github.com/AnalogMan151/XCI_Trimmer): Python3 script to trim and pad XCI ROM files
- [XCI-Explorer v1.4.4](https://github.com/StudentBlake/XCI-Explorer): A decompiled version of XCI Explorer using ILSpy

### CFW

#### SX OS

A Custom Firmware for Nintendo Switch.

- [Xecuter SX OS v2.6.1 beta](https://sx.xecuter.com/)

#### ReiNX

A modular Switch custom firmware.

- [ReiNX latest (2019-03-05)](https://reinx.guide/builds): A modular Switch custom firmware
- Homebrew menu over album (titleid 010000000000100D)
- Creport (titleid 0100000000000036)
- [ldn_mitm sysmodule v1.1.2](https://github.com/spacemeowx2/ldn_mitm)

#### hekate

Nintendo Switch Bootloader - CTCaer mod.

- [hekate - CTCaer mod v4.9.1](https://github.com/CTCaer/hekate/releases/tag/v4.9.1_): OFW supported: 7.0.1
- [hekate - CTCaer mod v4.6 svc](https://github.com/CTCaer/hekate/releases/tag/v4.6svc): OFW supported: 6.2.0

## Troubleshootings

### Mac and empty Homebrew Menu

> When booting into SX OS hbmenu I get the error "No applications could be found on the SD card. Make sure a folder named /switch exists in the root of the SD card and it contains applications.".

In order to fix it, run in a terminal:

```
sudo chflags -R arch /Volumes/<SDCARD>/switch
```
