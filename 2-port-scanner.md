# Port Scanner / How it Works

### What is a port? 
-  A port is a computer's tunnel / doorway to different features like Remote Desktop Protocol or Secure Shell. 

### What does a port scanner send to a port to check the current status?

-  A port scanner sends data packets to various ports on a computer or network device to check their status. It does this by sending a specially crafted message to the target port, attempting to establish a connection or elicit a response. Depending on the response (or lack thereof), the port scanner determines if the port is open, closed, or filtered.

### When a port scanner sends a request to connect, what are the three possible responses? Describe them.

- <u> Open: </u> If a port receives a connection request and responds positively, indicating that it's actively accepting connections, the port scanner identifies it as "open." This means that there's likely a service or application actively listening and ready to receive data on that port.
- <u> Closed: </u> When a port scanner sends a request, and the port responds with a refusal or an indication that no service is listening on that port, it's labeled as "closed." This typically means that no application is actively accepting connections on that specific port.
- <u> Filtered: </u> If the port scanner receives no response or an incomplete response (such as being blocked by a firewall), it categorizes the port as "filtered." This means that the scanner couldn’t determine the status of the port due to security measures or network configurations, preventing access or providing no re


## What is the difference between TCP and UDP?

- Functionality and speed are the difference between Transmission Control Protocol and User Diagram Protocol. 
#### TCP:
<u> Connection-oriented protocol:</u>  It establishes a reliable and ordered connection between two devices before transmitting data. It ensures data integrity, error checking, and retransmission of lost packets if needed.
Acknowledgment of data: It uses acknowledgments to confirm the receipt of data packets, ensuring data delivery.
Slower but more reliable: Ideal for applications requiring guaranteed delivery, such as web browsing, email, and file transfer.
#### UDP:
<u> Connectionless protocol: </u> It does not establish a direct connection before sending data. It’s a fire-and-forget protocol, sending data without confirming whether it's received or not.
No acknowledgment or error checking: UDP doesn’t involve acknowledgments or retransmission of lost packets, making it faster but less reliable than TCP.
Used for real-time applications: Suitable for applications like video streaming, online gaming, VoIP (Voice over Internet Protocol), where speed matters more than guaranteed delivery.


## List and describe the ports used for the following:
<u>Terminal Network (Telnet) - 23</u> Telnet is an unencrypted protocol used for remote terminal connections. It transmits data in plain text, which makes it less secure compared to SSH. <br/>

<u>Secure Shell (SSH) - 22</u> is a secure replacement for Telnet. It provides encrypted communication between two systems, commonly used for remote access, file transfer, and command execution.<br/> 

<u>Domain Name System (DNS) - 53 (both UDP and TCP) </u> DNS resolves domain names to IP addresses and vice versa. It translates user-friendly domain names into IP addresses, allowing users to access resources on the internet. <br/>

<u> Simple Mail Transfer Protocol (SMTP) - 25 </u> <br/> ***[Ports 25 (SMTP), 587 (SMTP with TLS), 465 (SMTPS)]***<br/>
 SMTP is used for sending emails between servers. Port 25 is the default port for unencrypted SMTP, while ports 587 and 465 are used for SMTP with encryption (TLS/SSL).

<u> Hypertext Transfer Protocol (HTTP) - 80</u>  is used for transmitting web pages and data on the World Wide Web. It operates in clear text and is not secure.<br/>

<u> Hypertext Transfer Protocol Secure (HTTPS) - 443</u> is a secure version of HTTP that uses encryption (TLS/SSL) to secure data transmission over the internet, commonly used for secure online transactions and sensitive data transfer. <br/>

<u> Remote Desktop Protocol (RDP) - 3389 </u> is a proprietary protocol developed by Microsoft for remote desktop access and control of a computer over a network connection.<br/>

<u> Ping does not use a specific port;</u> instead ICMP Echo Request (Type 8) and ICMP Echo Reply (Type 0)*

 Ping uses ICMP (Internet Control Message Protocol) to check the connectivity between two devices. It doesn’t utilize a specific port; rather, it sends ICMP echo request packets and listens for ICMP echo replies.


 #### Resources <br>
 [ChatGPT] (https://chat.openai.com/share/a3ba0ffe-b837-4bb9-bdbc-8223f58434fa) <br>
 [What is a Port Scanner and How Does it Work?] (https://www.varonis.com/blog/port-scanning-techniques)
