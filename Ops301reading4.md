# VirtualBox Network Settings: Complete Guide Notes

## Which network mode in VirtualBox can be used to emulate unplugging the Ethernet cable from the network?
- The network mode you would use is the Internal network mode, because it would cut off connection to the other vms or any connection that wasn't set up for that internal network specifically

## Which network mode would be best if you wanted to run a server on a VM that could be fully accessible from your physical local area network?
- The best network mode for this woul be bridged mode, because it is a direct connection to your actual personal network, so it acts like just another machine on your network

## What are the three options of promiscuous mode and what does each do?
- These would be Deny, Allow, and Allow all. Deny allows only traffic meant for the vm with the correct address will be able to recieve the traffic. Allow will let the VM see all traffic on the network segment. Allow All will let the VM see any traffic that is on the main personal network.

## What is Port Forwarding?
- Port forwarding allows any traffic from the host to be sent to a specific port on a vm. so like letting traffic from port 30 of the host pc go to port 300 on your vm.

### Sources 
("VirtualBox Network Settings: Complete Guide", Nakivo https://www.nakivo.com/blog/virtualbox-network-setting-guide/)

