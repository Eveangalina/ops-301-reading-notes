# Layers of OSI Model

**What does “OSI” stand for?**
<br>
Open Systems Interconnection (OSI).


**List the 7 layers of the OSI model and what each one is responsible for.**<br>
* <u>Physical Layer (Layer 1)</U>  
Responsible for transmitting raw data bits over a physical medium (cables, fibers, wireless signals).
Defines electrical, mechanical, procedural, and functional specifications for activating, maintaining, and deactivating physical links between devices.
<br><br>
* <U>Data Link Layer (Layer 2)</U> Provides error detection and correction within the transmitted frames.
Organizes bits into frames, performs error checking, and handles physical addressing (MAC addresses).
Controls access to the physical media and manages data flow to ensure reliable and efficient communication between devices
<br><br>
* <u>Network Layer (Layer 3)</U>  Handles logical addressing and routing of data packets across multiple networks.
Determines the best path for data transmission through routers.
Manages logical addressing (IP addresses) and ensures the delivery of packets to their intended destinations.
<br><br>
* <u>Transport Layer (Layer 4)</U>  Ensures end-to-end communication between devices.
Segments and reassembles data into smaller units (segments) for transmission.
Provides error checking, flow control, and data integrity between devices using TCP (Transmission Control Protocol) or UDP (User Datagram Protocol).
<br><br>
* <u>Session Layer (Layer 5)</U>  Establishes, manages, and terminates sessions between applications on different devices.
Handles session setup, maintenance, and teardown, allowing data exchange and synchronization between devices.
<br><br>
* <u>Presentation Layer (Layer 6)</U>  Responsible for data translation, encryption, compression, and formatting.
Converts data from the application layer into a format suitable for transmission over the network and ensures data compatibility between different systems.
<br><br>
* <u>Application Layer (Layer 7)</U>  Provides network services directly to user applications and end-users.
Handles high-level protocols, user interfaces, and network-aware applications (such as email, web browsers, file transfer, etc.).
Allows software applications to access network resources and communicate over the network.

**Distinguish which layers are the “hardware layers”, and which layers are the “software layers”. What does that even mean?**<br>
- The difference between the hardware layers and software layers in this context refers to the relationship between the physical componenets of a network and the software protocols that establish and enforce the rules of communication between the components. 
Layers 1 and 2 are hardware, layers 3 through 7 are software. 


**How can the OSI model be used in troubleshooting?**
<br>It can be used as a structured approach to identifying and resolving problems by systimatically analyzing each layer. 


# What Is Wireshark and How Is It Used?

**What is Wireshark?**<br>
- Wireshark is a network protocol analyzer that captures and analyzes network traffic in real time.


**What is a packet?**
- Packet is the name given to a discrete unit of data in a typical Ethernet network. It is a container or box that carries data from one device to another.

**What 3 high-level things does Wireshark accomplish? How could these be used for nefarious purposes? For benevolent purposes?**
- The three high level activities include capturing and analyzing network traffic, decripting the traffic, as well as replaying the network traffic. Cybercriminals may use wireshark to spy on network traffic, launch denial of service attacks, or steal data. Benevolent uses of Wireshark include troubleshooting, identifying security vulnerabilities and optimizing network performance. 
### Resources
[Chat BPT] (https://chat.openai.com) 