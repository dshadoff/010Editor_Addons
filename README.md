# 010Editor_Addons

Templates and Scripts for use on game files in 010 Editor (editor by Sweetscape.com)

## Introduction

010 Editor is an editor with powerful functions and user extensibility, including
extensibility for the hex editor and binary file parsing.

File formats related to retrogaming (i.e. patch files, backup memory files, etc.) may
be more easily read if extensions are made for these file formats, and this is what I
set out to do with the work contained in this repository.

Any files in tis repository are free to use, if you have 010 Editor.
Pull Requests are welcome for updates and/or new Templates/Scripts


### Templates

Templates for 010 Editor are used to help the user to navigate binary file structures,
by indicating what information is stored in the header, and to be able to browse the
data in the body of the files.

Templates in this repository:

#### ROM Patching formats:

Marks out each patch section's location, size and data with colour-coding.

| Name | File type | Function |
|------|-----------|----------|
| IPS.bt | IPS Patch File | ("International Paych System") Old ROM patching format. |
| BPS.bt | BPS Patch File | ("Beat Patching System") ROM patching format which "constructs" the output file, and uses variable-length numbering system. |
| PPF.bt | PPF Patch File | ("Playstation Patch Format") Patch format with validation and patch-undo options. Supports PPF 3.0 version. |

#### Console Save Memory formats:

| Name | File type | Function |
|------|-----------|----------|
| PCESAV.bt | PC Engine Backup Memory File | Marks out each game's save data with colour-coding |
| PCFXSAV.bt | PC-FX Internal / External Backup Memory File | supports FAT12 and FAT16 PCFX save files, including all differences from regular DOS FAT disks |


#### Sample_Files

Sample files are included for evaluation and testing purposes, for each of the templates in the repository


### Scripts

There are no scripts in the repository at this time.
