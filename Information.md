Hello!  This document is more detailed information on each piece of equipment inside the home network.

---9U 10" SWITCH RACK---
ON TOP: Silver Peak FW-7551A-SV1 w/ OpnSense: Purchased on eBay and installed OpnSense on it, used for segmentation of and between 1gbps and 100mbps networks.

1. GeeekPi 12-Port Cat6 Patch Panel: Patch panel providing network connectivity to devices.  Ports 1-5 are for 1gbps devices, port 6-10 are for 100mbps devices, port 11-12 are for uplinks to switches

2. UGREEN 10-port PoE Gigabit switch: Provides internet access for TP-Link Omada Wifi 7 AP, ProxMox Server, OpenMediaVault storage server, and extra ports for testing wired devices

3. Raspberry Pi Station: Houses a Raspberry Pi 4B 8GB for a print server for both color and black and white printers.  Also houses a Raspberry Pi Zero 2 W for PiHole, a DNS Sinkhole for blocking advertisements.

4-5. Dell optiplex 7090 Proxmox cluster: Proxmox Cluster alongside Dell Optiplex 3060 for containers and virtual machines

6-8. Cover Plates for future projects: 2U worth of extra space for future projects

9. 8 outlet power supply: powers all devices in network rack and provides surge protection

---ACCESS POINTS---
1. TP-Link Omada Wifi 7 WAP: Wifi 7 Access Point for wireless devices trusted on the network, including desktop computers, laptops, phones, and video game consoles.

2. Aerohive AP330 100mbps WAP: Older Access point hosting wifi for untrusted devices, smart devices, and original Xbox Live via Insignia.  AP and devices attached are placed on a seperate VLAN to protect trusted devices

---WIRE RACK---
(note: Wire rack is a 3 tier Hyper Tough wire rack from Walmert)
1. OMV (OpenMediaVault): Dell Optiplex 5040 Storage server hosting files and media within the household
   
2. Dell Optiplex 3060 Proxmox Cluster: Proxmox Cluster alongside Dell Optiplex 7090s for containers and virtual machines

3. Printers: Color and black and white printers, running to the Raspberry Pi 4B Print Server to allow netwok wide use of printers.
