# ClassicWB GAAE Package

ClassicWB GAAE is a feature rich Workbench enhancement by Bloodwych targeted A500+ / A600 with 2MB or more RAM using 4/8 colour for TVset or TVres Monitor.

## Description

ClassicWB GAAE Package contains ClassicWB GAAE v28 created by Bloodwych from EAB. 

With permission from Bloodwych it has been converted to a package for HstWB Installer.

Original version of ClassicWB GAAE can be downloaded from http://classicwb.abime.net/.

## Requirements

ClassicWB GAAE package can be installed on any Amiga with Amiga OS 3.2, 3.1.4 or 3.1 and about 35MB free space on a harddrive for installation.

## Installation

Download latest release from https://github.com/henrikstengaard/classicwb-gaae-package/releases and copy it to HstWB Installer "packages" directory, which typically is "c:\Program Files (x86)\HstWB Installer\Packages".

Installation through HstWB Installer will install and configure ClassicWB GAAE package using defined assigns.
During installation dialogs are presented to customize ClassicWB installation.

## Assigns

Installation of ClassicWB GAAE package requires and uses following assign and default value:

- SYSTEMDIR: = DH0:

ClassicWB GAAE files will be installed and configured in SYSTEMDIR: assign, which must be set to harddrive containing Workbench.

## Modifications

ClassicWB is installed from a zip file containing all files from ClassicWB System.hdf.

The install script for HstWB Installer is based on S/Startup-Sequence from ClassicWB System.hdf with following changes:

- Removed Workbench installation.
- Paths has been changed: SYS: to SYSTEMDIR:, C: to SYSTEMDIR:C/, L: to SYSTEMDIR:L/.
- Modified versions of Temp enable and disable option scripts with changed paths.
- Removed all "press enter to continue" expect last one used after installation complete message is shown.
- Removed and reduced waits.
- Adjusted text spacing.
- Added support for Amiga OS 3.2 and 3.1.4:
  - Disabled NewIcons.
  - Added arp.library and reqtools.library.
  - Installed FullPalette and patched green, blue and WB13 palettes.
  - Added WB13 pointer.
  - Added LoadModule ROMUPDATE to support Kickstart 3.1 being patched to 3.1.4.
  - Added version checking of DEVS:scsi.device, so it only will be loaded if scsi.device in memory/resident is less than v43.45.
  - Added install patch Amiga OS 3.1.4.1, if Amiga OS 3.1.4.1 update is installed.
  - Disabled StackAttack, HDEnv, SmartWin, Border Blank.

## Screenshots

Screenshots of ClassicWB GAAE installed with Amiga OS 3.2.

![ClassicWB GAAE 3.2 1](screenshots/classicwb_gaae_3.2_1.png?raw=true)

![ClassicWB GAAE 3.2 2](screenshots/classicwb_gaae_3.2_2.png?raw=true)

![ClassicWB GAAE 3.2 3](screenshots/classicwb_gaae_3.2_3.png?raw=true)

![ClassicWB GAAE 3.2 4](screenshots/classicwb_gaae_3.2_4.png?raw=true)

Screenshots of ClassicWB GAAE installed with Amiga OS 3.1.4.

![ClassicWB GAAE 3.1.4 1](screenshots/classicwb_gaae_3.1.4_1.png?raw=true)

![ClassicWB GAAE 3.1.4 2](screenshots/classicwb_gaae_3.1.4_2.png?raw=true)

![ClassicWB GAAE 3.1.4 3](screenshots/classicwb_gaae_3.1.4_3.png?raw=true)

![ClassicWB GAAE 3.1.4 4](screenshots/classicwb_gaae_3.1.4_4.png?raw=true)

Screenshots of ClassicWB GAAE from http://classicwb.abime.net/classicweb/gaaepics.htm.

![ClassicWB GAAE 1](screenshots/classicwb_gaae_1.png?raw=true)

![ClassicWB GAAE 2](screenshots/classicwb_gaae_2.png?raw=true)

![ClassicWB GAAE 3](screenshots/classicwb_gaae_3.png?raw=true)

![ClassicWB GAAE 4](screenshots/classicwb_gaae_4.png?raw=true)

![ClassicWB GAAE 5](screenshots/classicwb_gaae_5.png?raw=true)

![ClassicWB GAAE 6](screenshots/classicwb_gaae_6.png?raw=true)

![ClassicWB GAAE 7](screenshots/classicwb_gaae_7.png?raw=true)

![ClassicWB GAAE 8](screenshots/classicwb_gaae_8.png?raw=true)

![ClassicWB GAAE 9](screenshots/classicwb_gaae_9.png?raw=true)