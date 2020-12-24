# OpenCore for GA-Z97X-UD5H and i7-4790K

Board: Gigabyte GA-Z97X-UD5H  
CPU: Intel(R) Core(TM) i7-4790K CPU @ 4.00GHz  
OpenCore: 4D1FDA02-38C7-4A6A-9CC6-4BCCA8B30102:opencore-version	REL-064-2020-12-07
OS: macOS 11 Big Sur  
  
Do not use this without the proper modifications (i.e. SMBios)!  

For details check out https://trick77.com/ga-z97x-ud5h-and-macos-11-big-sur-with-opencore/

## Post installation recommendations

- Add and enable USBMap.kext after properly configuring the ports in use (see https://github.com/corpnewt/USBMap)
- Disable XhciPortLimit after inserting your own USBMap.kext
