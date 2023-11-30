# VirtualBox Network Settings Guide

Q: Which network mode in VirtualBox can be used to emulate unplugging the Ethernet cable from the network?

A: When a Network mode is set to Not attached this emulates unplugging. 


Q: Which network mode would be best if you wanted to run a server on a VM that could be fully accessible from your physical local area network?

A: Bridge adapter mode would be best to be fully accessible from your physical local area network. 


Q: What are the three options of promiscuous mode and what does each do?

A: 
1. **Deny** Any traffic that is not intended to the virtual network adapter of the VM is hidden from the VM. This option is set by default.
2. **Allow VMs.** All traffic is hidden from the VM network adapter except the traffic transmitted to and from other VMs.
3. **Allow All.** There are no restrictions in this mode. A VM network adapter can see all incoming and outgoing traffic.

Q: What is Port Forwarding?

A: Port forwarding is a networking technique used to allow external devices or computers to access specific services or applications running on a device within a local network. It works by redirecting communication requests from a specific port on the router or network gateway to a particular port on a device within the local network.


## Resources 
[Virtualbox Network Settings Guide] https://www.nakivo.com/blog/virtualbox-network-setting-guide/ 
