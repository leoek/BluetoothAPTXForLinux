# BluetoothAPTXForLinux Aptx support for linux with FFMpeg and bluez-alsa
To checkout : git submodule init

To install :
Install all the packages required to build FFmpeg (we require to build it because the Aptx codec is very recent and not included in packages distribs), bluez-alsa and openaptx

Make sure you have these packages installed: libsndfile-dev, libasound2-dev, libbluetooth-dev, libsbc-dev

To build : `./build`
If you get the error: `No package 'openaptx' found` during building: `./install-openaptx` (this requires root)

To install openaptx and bluez-alsa : `./install` (this requires root)

Please note that depending of your country, building FFMpeg may be subject to copyrights
Do not redistribute your binaries
I disclaim all warranty, use this at your risks.

Code in this repo (not submodules) is in GPL v3.

