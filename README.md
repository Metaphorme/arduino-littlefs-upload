# pico-littlefs-upload
MIT license -- (C) 2023  [Earle F. Philhower, III](mailto:earlephilhower@yahoo.com)

Really rough LittleFS uploader compatiblew with IDE 2.2.1 or higher.

## Usage

`[Ctrl]+[Shift]+[P]`, then "`Upload LittleFS to Pico`"

## Glitches

The first sketch auto-opened by the IDE presently has corrupted state and uploads cannot be done on it.
You need to open another sketch, close the first auto-opened sketch, and then re-open it to upload for that one.
You also need to run a build/compile (upload of sketch is uptional) one time for certain file system parameters to be available.

## Installation

Copy the VSIX file to `~/.arduinoIDE/plugins/` (you may need to make this directory yourself beforehand) and restart the IDE.
