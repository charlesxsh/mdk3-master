Overview
====

These modifications were not made by me, they were made by a Musket Developer that I have been working with. 
I have been given permission to share it with the public.
This version of MDK3 has a new feature that sends directed probe requests with invalid SSID characters to an AP.
The hope is that if enough probes are sent, the AP will lock up and reboot.
This tool should only be used for experimenting with the security of your own wireless network.

Installation
====

cd /mdk3-master/
make
sudo make install
