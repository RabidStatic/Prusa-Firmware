# Original Prusa i3 MK2 Firmware with End of Filament sensor enabled

## General instructions

Pre-compiled hex output "Firmware-3.0.11a.hex"

Download and flash it to the electronics

Connect sensor to X MAX connection on Rambo Mini

## Build instructions

### Step 1

Install arduino environment
https://github.com/aderusha/Get-PrusaFwDevEnv.git

### Step 2

Remove Liquid Crystal library from your arduino or rename it

### Step 3

Install the arduino addon located in the root of this repo. Don't forget to install correct version!

### Step 4

Copy the configuration file matching your printer from variants folder to the the Firmware folder

### Step 5

Rename it to "Configuration_prusa.h"

### Step 6

Compile the firmware

### Step 7

Upload the firmware to board





