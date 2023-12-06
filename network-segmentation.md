# CIDR Block Notation Explained in 2 Minutes

### What is CIDR notation? a CIDR block?
- CIDR (Classless Inter-Domain Routing) Notation: It's a method used to represent IP addresses and their associated network prefixes. It combines the IP address with a subnet mask represented by a slash followed by a number. For instance; 192.168.1.0/24.
- CIDR Block: It refers to a range of IP addresses within a CIDR notation. For example, 192.168.1.0/24 denotes a block of IP addresses ranging from 192.168.1.0 to 192.168.1.255, where the last octet (in this case, 0) represents the network address, and the range extends up to the broadcast address (192.168.1.255).

### How many octets are found in an IPv4 address?
- An IPv4 address consists of <ins>four octets</ins> separated by dots (.). Each octet represents 8 bits, forming a total of 32 bits for an IPv4 address (4 octets x 8 bits = 32 bits).

### Setting binary aside and using the decimal system, what is the range of numbers found in an octet?

- Range of Numbers in an Octet:
An octet in decimal notation ranges from 0 to 255.
In binary, an octet is represented by 8 bits (2^8 = 256), but in the decimal system, it ranges from 0 to 255 (2^8 - 1 = 256 - 1 = 255).
<br/>
### What does the final digit after the “/” represent in an IPv4 address?
- The final digit after the / in CIDR notation represents the subnet mask.

### How many IP addresses are in the CIDR block 10.0.0.0/24?
-  In the CIDR notation 10.0.0.0/24, the /24 indicates that the first 24 bits are used for the network portion, leaving 8 bits for host addresses (32 bits total - 24 bits for the network = 8 bits for hosts).
- The number of possible addresses for hosts in this block is 2^8 - 2 (subtracting network and broadcast addresses).
Therefore, there are 256 - 2 = 254 usable IP addresses in the CIDR block 10.0.0.0/24.

# What Is Network Segmentation and Why It Matters?

### In your own words, describe network segmentation.
- 
Network segmentation is a cybersecurity technique that divides a network into smaller, isolated segments to enhance security and control network traffic. It's like creating separate neighborhoods within a city, each with its own security measures and restricted access to other areas.

### Network segmentation isn’t important as long as the network is using a well configured firewall. Do you agree? Why or why not?
- I do not agree, attackers can find ways to get pass firewalls. Network segmentation is an additional layer of protection because after bypassing the firewall the attacker would then need to pass each network segment individually.

### What is a screened subnet?
- A screened subnet, also known as a <ins>demilitarized zone (DMZ)</ins>, is a separate network segment that acts as a buffer between the internal network and the public Internet. It helps protect sensitive resources from unauthorized access and attacks originating from the Internet.

### Cameras, ID card scanners, locked doors and biometrics are just a few examples of what type of security?
- Traditional physical security.

#### Resources
[ChatGPT] (https://chat.openai.com/share/b1daa33f-e031-433c-b542-64822c9680b4)
<br/>
[CIDR Block Notation Explained in 2 Minutes] (https://medium.com/@ethicalentrepreneur/cidr-block-notation-explained-in-2-minutes-1010ec0dbc15)