# Network-Scanning-Code-using-Python


The script I provided is using the Scapy library to perform network scanning in a local area network (LAN). Specifically, it's conducting an ARP scan, which is a common technique for discovering devices on a local network.

In the script:
> An ARP request packet is crafted for a specified IP address or range.
> The script then sends this ARP request as a broadcast to all devices on the local network.
> It listens for responses and collects information about devices that respond.
> Finally, it prints out the list of devices that responded (answered) and those that did not respond (unanswered).

This type of network scanning can be useful for various purposes, such as network troubleshooting, device discovery, or security auditing. ARP scanning allows you to build a list of devices and their corresponding MAC addresses on the local network. 
