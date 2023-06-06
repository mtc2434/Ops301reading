# Network Address Translation (NAT) (Notes)

## What is the main purpose for implementing NAT on a network?
- The main purpose for implementing an NAT on a network is if you want to have multiple devices access the internet through one public IP address
## At what layer of the OSI model does NAT happen?
- Layer 3 because of the network level
## What happens to packets when NAT runs out of addresses in the pool of available IPs?
- The packet will be dropped and you will get an error message from ICMP (internet contol message protocol)
## What disadvantage does using NAT pose for routers?
- Some applications wont work
- might create problems with tunneling protocols
- There are path delays due to translation

### Source
("Network Address Translation (NAT)" saurabhsharma56, https://www.geeksforgeeks.org/network-address-translation-nat/)
