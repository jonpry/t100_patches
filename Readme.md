Has working backlight. HS200 eMMC, bunch of fixes for timeouts. 

A lot of this code is real bad, hacked together and will only work on T100. Some of the code is just stuff i tried but now is known to not be needed. Other probably not needed but would require more testing. 

Example command line: 

linux	(hd0,gpt1)/vmlinuz nosplash root=UUID=80325787-8fad-4b1e-b0d2-bb70b5c5b264 ro reboot=pci,force video=DSI-1:1368x768e acpi_osi="!Windows2012" rootwait=1 
