# RADIUS Authentication
## Computer Network - AAA (Authentication, Authorization and Accounting)

### Explain each of the three A’s as you would to a non-technical family member. Use an analogy or a story.
- <u> Authentication:</u> Imagine you have a secret club with a special handshake to get in. Authentication is like checking if someone knows that secret handshake before letting them into the club. In computer networks, it's confirming someone's identity before allowing them access to resources or services, like entering a secure website by using a username and password.

- <u> Authorization:</u>  Once someone is inside the club, they might have different levels of access or permissions. Authorization is like determining what parts of the club someone is allowed to enter or what they can do once they're inside. In networks, it's about deciding what a user can access or do after they've been authenticated, like limiting access to certain files or areas of a network.

- <u> Accounting:</u>  Imagine keeping track of who comes in and out of the club, what they do while they're there, and how long they stay. Accounting in networking is about recording and tracking the activities of users while they're on the network, like monitoring data usage, time spent online, or resources accessed. This helps in keeping records for billing, auditing, or security purposes.

### What should the administrator do if the ACS server fails to authenticate a user during AAA implementation?
- Check the local database for a backup option. 

### What is the role of the NAS in the AAA implementation using an ACS server? Use a diagram.
- Regarding the role of NAS (Network Access Server)

    +-----------+<br>
    |   User    |<br>
    +-----------+<br>
         |<br>
         | Authentication Request<br>
         v<br>
+--------------------+<br>
|    Network Access  |<br>
|      Server (NAS)  |<br> 
+--------------------+<br>
         |<br>
         | Authentication Request forwarded<br>
         v<br>
+--------------------+<br>
|   ACS (Server)     |<br>
|  (Authentication,  |<br> 
|   Authorization,   |<br>
|    Accounting)     |<br>
+--------------------+<br>
         |<br>
         | Authentication Response<br>
         v<br>
+--------------------+<br>
|    Network Access  |<br> 
|      Server (NAS)  |<br> 
+--------------------+<br>
         |<br>
         | Access Granted/Denied<br>
         v<br>
    +-----------+<br>
    |   User    |<br>
    +-----------+<br>


#### Resources 
[ChatGPT] () <br>
[Computer Network - AAA (Authentication, Authorization and Accounting)] (https://www.geeksforgeeks.org/computer-network-aaa-authentication-authorization-and-accounting/) <br>