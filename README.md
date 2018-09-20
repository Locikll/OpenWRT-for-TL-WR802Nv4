# Instructions for Flashing OpenWRT on a TL-WR802Nv4

1. Build/Download (from releases section) the sysupgrade and recovery binary images, rename the recovery binary to tp_recovery.bin
2. Install TFTP server such as Tftpd64
3. Connect to your TL-WR802Nv4 to your PC via Ethernet, and change your local IP address to 192.168.0.66
4. Launch the TFTP server and route to 192.168.0.66, with the directory where your recovery binary image is saved as tp_recovery.bin
5. Hold down the reset button on the router for ~ 10 seconds
6. Congratulations, it should now be flashed and you can connect to it via 192.168.1.1 AFTER changing back your local IP to 192.168.1.x or 'automatic'



