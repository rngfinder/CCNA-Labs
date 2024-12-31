Made in Cisco CML 2.8 free tier

It is DHCP snooping lab 

DHCP server is on R1

SW1 and SW2 have standard dhcp snooping config via vlan 1, option 82 is allowed

Both PCs under Alpine Linux, IPv4 dhcp mode. A command to renew IPs => sudo udhcpc

Result: 1) no dhcp binding data on both switches; 2) neither SW2 nor SW1 add option 82 to messages; 3) PCs renew their IPs as usual
