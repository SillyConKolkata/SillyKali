# SillyKali
Kali 2017.1 SDCARD IMG for CubieBoard2 based on Armbian , Debian Jessie, Kali 2017.1 and Linux-SunXI 

Default Login Details

login: root
password: toor

SSH is default enabled. IP will be assigned by DHCP of the network. Check your Router Web Interface to determine the IP.

You can also connect to X11 interface ( LXDE ) . But, found VNC is not a good solution for me. 
So, it is preinstalled with "NoMachine" server.

Download NoMachine client from https://www.nomachine.com/download and use the provided login details to use LXDE remotely.

PS: Having trouble to upload the BIG image file to github. Here is the download link from Mega


https://mega.nz/#!OIhFgAhD!GvXlEgTDANSpmCuubs6hjs0dNpJQxHFyV2xjUps0okM

Support Channel:
https://t.me/sillycon


Issues:
* No NAND Support. 
* Use a fast ( CLASS 10 ) MicroSD to burn image. Recommended size 32GB.
* No Mali drivers
* No hardware accelerated video decoding
* Different GPIO numbering compared to the legacy kernel
* schedutil CPU governor may cause clicks and pops on audio output – change to ondemand to work around this issue
