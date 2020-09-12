# Claymore-s-Dual-Ethereum-Miner v15.0
What's new in version 15.0?

15.0
now the miner driver does not require switching Windows to test mode. If you want to disable the test mode, use the-driver uninstall command (with administrator rights) and restart the computer, then run the miner with administrator rights to automatically install a new driver if necessary (or directly use the-driver install command).
If you have any problems with a signed driver, you can use the key-driver install_test, it uses the old approach: enables test mode (requires a reboot) and installs an unsigned driver.
Added the-showpower parameter to track video card power consumption statistics, click "s" to see it. AMD and Nvidia cards are supported, with the exception of Linux gpu-pro drivers and Radeon7 cards.
Updated Remote Manager to display total power consumption.
Fixed an issue with the-logsmaxsize parameter when the-logfile parameter is used to specify a directory for log files
Several minor fixes and improvements.
Added support for using optimized memory timings (straps) "on the fly" in Windows, without flashing VBIOS (currently only Polaris, Vega, Nvidia 10xx cards), acceleration up to 20%.
The-strap feature really helps newcomers who don't want to re-flash their cards and lose their warranty.
With the help of a new feature-strap, video cards issue hashing speeds as stitched. I.e., the RX 570/580 outputs about 30-33 Mh/s instead of the standard 18 Mh / s.
