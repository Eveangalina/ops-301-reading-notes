# Layers of OSI Model

Q: What does “OSI” stand for?

A: Open Systems Interconnection (OSI).


Q: List the 7 layers of the OSI model and what each one is responsible for.
A: 
1. Application Layer: Provides application-specific services and protocols, enabling user interaction and data exchange between various applications.
2. Presentation Layer: Formats and transforms data to ensure compatibility between different applications and presentation formats.
3. Session Layer: Establishes, manages, and terminates communication sessions between applications, ensuring synchronization and coordination of data exchange.
4. Transport Layer: Establishes and manages end-to-end communication sessions between applications, providing reliable data transfer and flow control.
5. Network Layer: Routing data packets across a network. 
6. Data Link Layer: error free data transfer over a physical link. This layer is divided into two sublayers which are; 
the Logical Link Control (LLC) and the Media Access Control (MAC). This layer is responsible for framing, physical addressing, error and flow control, as well as access control. 
7. Physical Layer: lowest layer, is responsible for transmitting raw data bits accross a physical medium; from one node to the next. Functions of this layer include bit synchonization, rate control, physical topologies, and transmission mode. 


Q: Distinguish which layers are the “hardware layers”, and which layers are the “software layers”. What does that even mean?

A: The difference between the hardware layers and software layers in this context refers to the relationship between the physical componenets of a network and the software protocols that establish and enforce the rules of communication between the components. 
Layers 1 and 2 are hardware, layers 3 through 7 are software. 


Q: How can the OSI model be used in troubleshooting?

A: It can be used as a structured approach to identifying and resolving problems by systimatically analyzing each layer. 


# What Is Wireshark and How Is It Used?

Q: What is Wireshark?

A: Wireshark is a network protocol analyzer that captures and analyzes network traffic in real time.



Q: What is a packet?

A: Packet is the name given to a discrete unit of data in a typical Ethernet network. It is a container or box that carries data from one device to another.



Q: What 3 high-level things does Wireshark accomplish? How could these be used for nefarious purposes? For benevolent purposes?

A: The three high level activities include capturing and analyzing network traffic, decripting the traffic, as well as replaying the network traffic. Cybercriminals may use wireshark to spy on network traffic, launch denial of service attacks, or steal data. Benevolent uses of Wireshark include troubleshooting, identifying security vulnerabilities and optimizing network performance. 
