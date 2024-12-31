#Cisco CML 2.8 free tier

#DHCP snooping lab 

#DHCP server is on R1

#SW1 and SW2 has standard dhcp snooping set up via vlan 1, option 82 is allowed

#PCs under Alpine Linux, dhcp mode. To renew IP => sudo udhcpc

#Result: 1) no dhcp binding tables, 2) PCs renew IPs as usual 3) 82 option does't work

