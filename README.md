# PETPix
PETPix is a drawing tool for CBM/PET machines in 80x50 (or 160x50) "big pixel" / double density mode.

It is entirely written in BASIC and also works on other Commodore 8-bit machine (e.g. VIC20, C64) with a few simple modifications.

## Why?

PETPix can be used to create images or sprites for double density mode directly on the machine or in an emulator to later extract the data and use it in (e.g.) a game.

## Features
- Draw over the full screen in 80x50 (or 160x50, on machines with 80 character columns) resolution.
- Load images from tape #1.
- Save images to tape #1.
- Backup/restore image to/from memory.
- Easily modifiable, because it is written in BASIC.

## How to use
- Cursor keys: Move the cursor around the screen to where you want to draw/modify the "pixels".
- Keys W, S, A and Q: Will draw/erase one of the four "pixels" at the cursor position (W = top-right, S = bottom-right, A = bottom-left, Q = top-left).
- P key: Save image to tape #1.
- L key: Load image from tape #1.
- C key: Backup current image in memory (warning: Storage will be used during load/save).
- R key: Restore image from memory (warning: Storage will be used during load/save).
