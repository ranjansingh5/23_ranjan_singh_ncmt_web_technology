# Group A: Short Questions 
---
# 1. Define the term ”Protocol” in the context of the Internet.❓
-> In networking, a protocol is a standardized set of rules for formatting and processing data. Protocols enable computers to communicate with one another.

---
# 2. What is the primary difference between a Web Browser and a Search Engine?❓
-> The primary difference between a Web Browser and Search Engine are mention below:
* Search Engine
- Help users find information from the WWW by returning relevant web pages
* Web Browser
- Retrives and displays web pages using a search engine or entered URL.

---
# 3. Define the World Wide Web (WWW).❓
-> The World Wide Web (WWW), often called the Web, is a system of interconnected webpages and information that you can access using the Internet. It was created to help people share and find information easily, using links that connect different pages together.

---
# 4. Distinguish between a static web page and a dynamic web page.❓
-> The difference between a static web page and a dynamic web page are mention below:-
* Static Web Page	
- In static web pages, Pages will remain same until someone changes it manually.
- Static Web Pages are simple in terms of complexity.	

* Dynamic Web Page
- In dynamic web pages, Content of pages are different for different visitors.
- Dynamic web pages are complicated.

---
# Group B: Long Questions 
# 5. Explain the client-server architecture of the web with a neat diagram.❓
-> A Client Server Architecture is a network-based computing structure where responsibilities and operations get distributed between clients and servers. Client-Server Architecture is widely used for network applications such as email, web, online banking, e-commerce, etc.
This model divides the system into two parts: the client side and the server side.
a. Client: An application that requests services from the server, such as data retrieval, storage, calculations, or other functions.

b. Server: An application that processes client requests, sends responses, or performs specified actions. The server and client may reside on the same machine or different devices across the network. Effective Communication occurs via predefined protocols like HTTP, FTP, or SMTP.

+.............+        HTTP Request        +.................+
|             |  ---------------------->   |                 |
|   Client    |                            |      Web        |
| (Browser)   |  <----------------------   |    Server       |
|             |        HTTP Response       | (Application +  |
+.............+                            |   Database)     |
        |                                  +........+........+
        |                                           | 
        |                                  +..................+
        |                                  |                  |
        +..................................|     Database     |
                                           |                  |
                                           +..................+

---
# 6. Describe the functions of the following Internet services: Email, FTP, and VoIP. ❓
-> The functions of the following Internet services are mentioned below:
* Email
- Email is used to discuss business decisions, share documents, and act as written evidence in disputes.
- Communication: Sending instant text, images, and files (documents, audio, video) to individuals or groups across vast distances.
- File Sharing: Attaching various file types for easy distribution.
- Marketing & Business: Used for newsletters, customer communication, and business correspondence.

* FTP
- Uploading Files This allows a user on a local machine (the client) to transfer files to a remote server (e.g., uploading website files to   a web host).
- Downloading Files This enables a user to retrieve files from a server to their local computer.
- Remote File Management Users with appropriate permissions can perform various operations on the server's file system, such as listing directory contents, renaming, deleting, and copying files and folders.

* VoIP
- Voice Communication: The primary function is facilitating high-quality, cost-effective audio calls over the internet, especially for long-distance and international calls.
- Scalability: Businesses can easily add or remove users and lines as their needs change, without the need for extensive physical infrastructure upgrades.
- Security: VoIP protocols include security measures such as encryption (e.g., SRTP) to protect communication privacy over the internet. 

---
# 7. "The Internet is a network of networks." Elaborate on this statement explaining how packet switching works.❓
-> Internet is called network of networks because it connects computers all over the world forming a network.
And all computers are also connected to each other , hence computers form a network and when they all join with internet it is called network of networks.
The internet is a global network of computers. It is called a network of networks because rather than having one layer where all computers are connected together on the same level, computers are grouped together on separate networks or LANs (Local Area Network). These networks are small groups of computers which can all talk to each other. When any of these grouped computers needs to communicate with a computer outside of their group or "network" they will send information through what is called a "gateway" which will rout traffic across the internet to either another network or to a specific computer on the internet.

* Packet Switching:- Packet switching is a technique used in computer networks to transmit data as packets. Instead of reserving a dedicated communication channel for the entire duration of a transmission, packet switching breaks the data into packets and sends them independently. This method enables multiple users to share the network resources effectively.
The Packet Switching works by this way, mention below:
- Data Division: When a device sends data (e.g., a web page request or an email), the data is divided into small packets. Each packet contains a portion of the message, as well as routing information, including the destination address.
- Routing Packets: These packets are sent to their destination through intermediate devices like routers and switches. Each packet may take a different route, depending on the current network conditions (such as congestion or outages).
- Reassembly of Data: Once all the packets arrive at the destination, they are reassembled in the correct order by the receiving device or system, allowing the full message to be reconstructed.
- Acknowledgement and Error Handling: The receiving system may send back acknowledgments to ensure that the data has arrived correctly. If any packet is lost or corrupted during transmission, it can be retransmitted.

# Group C: Scenario-Based Questions

# 8. A startup company wants to host a website that displays the same information to all visitors and requires very low maintenance costs. However, they are being advised to usea dynamic website. As a consultant, would you agree? Justify your answer.❓
-> No, I would not agree with the advice to use a dynamic website.
Since the startup’s website shows the same information to all visitors and needs very low maintenance, a static website is the better choice.

* A static website:

- It's displays the same content to everyone.
- Is simple to build and manage.
- It's has very low hosting and maintenance cost.
- It's does not require a database or server-side programming.

* A dynamic website is useful only when:

- The content changes frequently.
- Different users see different information.
- It's features like login, database, or real-time updates are required.

->> A startup company wants to host a website that displays the same information to all visitors and requires very low maintenance costs because the startup does not need these features, using a dynamic website would increase cost and complexity unnecessarily.

# 9. A user types www.google.com into their browser, but the browser displays a "Server Not Found" error, even though the internet connection is active. However, accessing the site via 142.250.190.46 works. Diagnose the problem and explain the underlying technology that failed.❓
-> The problem is related to DNS (Domain Name System) failure.
When a user types www.google.com, the browser does not understand domain names directly. It first contacts a DNS server to translate the domain name into an IP address.

* What should happen normally:
1. The user enters www.google.com
2. And,browser sends a request to a DNS server
3. After that, DNS server returns the IP address (e.g., 142.250.190.46)
4. Then, browser connects to the server using that IP address.

In this case:
- The browser shows 'Server Not Found' when using www.google.com
- The site opens correctly when using (142.250.190.46)
- This proves that:
   - There is no issue with the internet connection.
   - The google’s server can be accessed without any problem.
   - The website name was not translated into an IP address, so the browser could not find the server.

When the underlying technology that failed:
The DNS server may be:
- The DNS server is not replying to requests.
- The DNS settings are wrong or not set properly.
- The service is unavailable for now.

# 10. A multinational corporation wants to share sensitive inventory data with specific suppliers but does not want this information available to the general public. Explain which network type (Intranet, Extranet, or Internet) they should implement and why.❓
->The company should use an Extranet.
Reason:
- The data is sensitive, so it should not be open to the public.
- The company wants to share information only with specific suppliers, not everyone.

* An Extranet:
- Is a private network
- Allows controlled access to external partners like suppliers
- Uses security methods such as login and passwords
- Keeps information safe while allowing limited sharing

* Why not others?

- Internet: Open to everyone → not secure for sensitive data
- Intranet: Only for internal employees → suppliers cannot access it
