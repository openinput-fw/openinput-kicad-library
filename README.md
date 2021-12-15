# openinput-kicad-library

[<img src="docs/assets/logo.svg" alt="" width="20%" align="right">](https://github.com/openinput-fw)

Kicad symbol and footprint library for input device related components not available in the official libraries.

## Available components

| Footprints                   |
|------------------------------|
| PXI-DIP-16 (PMW33xx/PAW3399) |
| Generic Micro switch         |
| Generic Encoder              |

| Symbols              |
|----------------------|
| PAW3399DM‐T4QU       |
| PMW3360DM-T2QU       |
| PMW3389DM‐T3QU       |
| Generic Micro switch |

# Installation

This library is made with Kicad `6.0.0-rc1` and over in mind.

## Through PCM (Recomended)

The library should be available in the official KiCad PCM repository, proceed if you wish to install manually or offline.

To Install open Kicad's `Plugin and Content Manager` (shortcut `Ctrl+M`) and `Install from File...` with the packaged library found in [releases](https://github.com/openinput-fw/openinput-kicad-library/releases).

Kicad uses library tables to keep track of installed libraries. As of `6.0.0-rc1` Content Manager DOES NOT automatically update these library tables.

To be able to use this library you will need to add it manually in `Manage Symbol Libraries...` and `Manage Footprint Libraries...` in `Preferences`.

The following entries are needed:

| Library    | Nickname   | Library Path                                                                                 |
|------------|------------|----------------------------------------------------------------------------------------------|
| Symbols    | openinput  | `${KICAD6_3RD_PARTY}/symbols/com_github_openinput-fw_openinput-kicad-library/openinput.kicad_sym` |
| Footprints | openinput  | `${KICAD6_3RD_PARTY}/footprints/com_github_openinput-fw_openinput-kicad-library/openinput.pretty` |

## Manual

Extract the same ackaged library found in [releases](https://github.com/openinput-fw/openinput-kicad-library/releases) to where you want the library stored, and add the relevant entries to the library tables in `Manage Symbol Libraries...` and `Manage Footprint Libraries...` in `Preferences`.

`note: the path to the 3d models is fixed, so depending on where you install the library they might not show up by default`
