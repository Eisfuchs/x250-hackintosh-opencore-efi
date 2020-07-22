# x250-hackintosh-opencore-efi

## Laptop Configuration of the Lenovo ThinkPad x250
- Intel i5-5200U (https://ark.intel.com/content/www/us/en/ark/products/85212/intel-core-i5-5200u-processor-3m-cache-up-to-2-70-ghz.html)
- Ram: 8GB 1600Mhz  
- 128GB SSD 
- Resolution: 1366x768
- Intel HD Graphics 5500
- Intel Dual Band Wireless-AC 7265

https://www.notebookcheck.com/Test-Lenovo-ThinkPad-X250-Ultrabook.136036.0.html


### Used BIOS settings

| Item | Setting |
| ------------- | ------------ |
| USB 3.0 Mode | Enabled |
| Power Intel Rapid Start Technology | Disabled |
| Security Predesktop Authentication | Disabled |
| Security Chip | Disabled |
| Memory Protection Execution Prevention | Enabled |
| Virtualization | Enabled |
| Virtualization VT-d | Disabled |
| Computrace | Disabled |
| Secure Boot | Disabled |
| UEFI/Legacy Boot | UEFI Only |
| Boot Mode | Quick |



## MacOS Version:
Catalina 10.15.6

## Used OpenCore Version
0.59

## What is still not working
- WLAN (maybe soon: https://github.com/AppleIntelWifi/adapter or https://github.com/OpenIntelWireless/itlwm/blob/master/.github/README_en.md) 
- SD Card Reader (I had to disable it)
- Mini-DP Port 


## References
OpenCore guide for installation and configuration:
https://dortania.github.io/OpenCore-Install-Guide/

I used this to begin with:
https://www.reddit.com/r/hackintosh/comments/fqpu49/opencore_lenovo_x250_minidp_issues/
