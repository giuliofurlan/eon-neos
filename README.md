
# Still Works on OnePlus 3t

Restoring on macOS & Linux
------
1. Connect your EON
2. Open a terminal
3. Clone this repo, then `cd eon-neos`
4. Run `./download.py`
5. Put your device into fastboot mode by turning off your device, then holding volume down + power.
6. Run `./flash.sh` DO NOT DISCONNECT THE DEVICE!

Restoring on Windows
------
1. Install the Google USB driver for ADB (Android Debug Bridge)... https://developer.android.com/studio/run/win-usb
2. Connect your comma two (via a USB-C to USB-A cable) or EON Gold (via a USB-mini-B to USB-A cable) to your computer
3. Download and extract this repository
4. Download & install Python 3
5. Run download.py to download NEOS and flashing tools
6. Put your device into fastboot mode by turning off your device, then holding volume down + power.
7. Run flash.ps1 (right click, run with powershell). DO NOT DISCONNECT THE DEVICE!
