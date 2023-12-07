# Netrwork Address Translation (NAT)

### What is the main purpose for implementing NAT on a network?
- NAT is primarily used to enable multiple devices within a private network to share a single public IP address.

### At what layer of the OSI model does NAT happen?
- Network Layer (Layer 3) of the OSI model. NAT modifies IP addresses within the IP packet header, translating private IP addresses to public ones and vice versa, enabling communication across different network boundaries.

### What happens to packets when NAT runs out of addresses in the pool of available IPs?
-  If NAT exhausts the pool of available IP addresses, new devices attempting to access the internet will be unable to acquire a unique public IP address. As a result, those devices won't be able to establish connections outside the local network, causing issues such as connection failures or limited internet access for new devices.

### What disadvantage does using NAT pose for routers?
 The main drawback of employing NAT in routers is the increased processing burden it creates. NAT demands routers to uphold and administer translation tables, aligning various private IP addresses with either a single public IP or a set of public IPs. This procedure complicates router functionality, possibly resulting in higher latency, greater resource usage, and increased processing demands on the router, particularly in scenarios with heavy network traffic or intricate NAT setups.


#### Resources 
[NAT] (https://www.geeksforgeeks.org/network-address-translation-nat/) <br>
[ChatGPT] (https://chat.openai.com/share/a3ba0ffe-b837-4bb9-bdbc-8223f58434fa)