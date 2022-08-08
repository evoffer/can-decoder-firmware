# can-decoder-firmware
Firmware Update for CAN Decoder for Tailgate Foot Activation and Lighted Applique (Tesla Model S/X/3/Y) from EVOffer

## Update Note

### update222
1. Update charging logic for Model S/X 2021+ for Tesla Version 2022.20 or above.

### update209
1. Add Tailgate Foot Activation disablement feature when emergency flash light is on.

### update214
1. Add Car Wash Mode for Model 3/Y Tailgate Foot Activation

### update216
1. Update Model S/X Lighted Applique charging effect

### update219
1. Fix Model S/X Lighted Applique effect
2. Add blind spot signal

## Software Update

### Step 1 - Prepare Memory Card
Prepare a microSD (32GB or below capacity is preferred). Make sure it is in FAT32 format.

### Step 2 - Getting the Update File
Rename the file to `formware.bin` (v1.00) or `wsoft0.bin` (v1.15 / v2.00) and place it under the root of the microSD.
Eject it from the computer afterwards.

### Step 3 - Flashing the Update
Disconnect the deocder from power.
Insert the microSD into the control unit and reconnect the CAN Decoder.
The LED will be flashing rapidly. 
Wait until the LED becomes solid and eject the microSD.

### Complete! Test the System
The LED should be stay on now and you are all set!
