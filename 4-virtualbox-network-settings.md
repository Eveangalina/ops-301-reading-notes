# VirtualBox Network Settings Guide

### Which network mode in VirtualBox can be used to emulate unplugging the Ethernet cable from the network?
- <u> Disconnected or Not Attached mode</u> in VirtualBox can be used to emulate unplugging the Ethernet cable from the network. When a Virtual Machine (VM) is set to this mode, it effectively isolates the VM from any network connectivity, resembling the absence of a network connection.


### Which network mode would be best if you wanted to run a server on a VM that could be fully accessible from your physical local area network?

- <u> Bridged network mode</u> would be the ideal choice if you wanted to run a server on a VM that needs full accessibility from your physical local area network. In Bridged mode, the VM's network interface is directly connected to the physical network adapter of the host system. This setup enables the VM to obtain its own IP address on the local network, making it accessible as a standalone entity on the same network as the host system.


### What are the three options of promiscuous mode and what does each do?

A: 
1. **Deny** This mode restricts the VM's network interface to accept only the traffic intended explicitly for it, denying any other traffic on the network. This option is set by default.
2. **Allow VMs.** It enables the VM to receive frames that are part of the same broadcast domain or virtual network, allowing communication between VMs on the same virtual network.
3. **Allow All.** This mode permits the VM to receive all frames on the physical network, irrespective of whether they are intended for that VM or not. It places the VM's network interface in promiscuous mode, allowing it to capture all network traffic on the physical network.

### What is Port Forwarding?

Port Forwarding is a networking technique used to redirect specific incoming communication requests from one address and port number combination to another address and port.


## Resources 
[Virtualbox Network Settings Guide] (https://www.nakivo.com/blog/virtualbox-network-setting-guide/) <br>
[ChatGPT] (https://chat.openai.com/share/a3ba0ffe-b837-4bb9-bdbc-8223f58434fa)