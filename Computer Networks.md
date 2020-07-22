# Network Port
- On a TCP/IP network every device must have an IP address.The IP address identifies the device (e.g. computer).However an IP address alone is not sufficient for running network applications, as a computer can run multiple applications and/or services.Just as the IP address identifies the computer, The network port identifies the application or service running on the computer.
- So basically we can say that use of ports allow computers/devices to run multiple services/applications.
- Real life example -If you use a house or apartment block analogy the IP address corresponds to the street address.All of the apartments share the same street address.However each apartment also has an apartment number which corresponds to the Port number.
- Applications that provide a service (such as FTP and HTTP servers) open a port on the local computer and listen for connection requests. A client can request the service by pointing the request to the application’s IP address and port. A client can use any locally unused port number for communication
- TCP and UDP specify the source and destination port numbers in their packet headers and that information, along with the source and destination IP addresses and the transport protocol (TCP or UDP), enables applications running on hosts on a TCP/IP network to communicate.
- The reason for having ports is that virtually all modern computers support multitasking. Thus, on a typical computer, there will be multiple programs which need to contact other programs on other computers over the network all at the same time. Ports enable multiple programs to share a single physical network connection simultaneously, as opposed to having only one program using the connection for a long period of time
- To determine what protocol incoming traffic should be directed to, different port numbers are used. They allow a single host with a single IP address to run network services.
## Port Numbers
- The port number is a 16-bit unique port identifier within a ip address
- A port number uses 16 bits and so can therefore have a value from 0 to 65535.
Port numbers 0-1023 – Well known ports. These are allocated to server services by the Internet Assigned Numbers Authority (IANA). e.g Web servers normally use port 80 and SMTP servers use port 25 .

Ports 1024-49151- Registered Port -These can be registered for services with the IANA and should be treated as semi-reserved. User written programs should not use these ports.

Ports 49152-65535– These are used by client programs and you are free to use these in client programs. When a Web browser connects to a web server the browser will allocate itself a port in this range. Also known as ephemeral ports.

# TCP Socket
A connection between two computers uses a socket.So a socket is the combination of IP address plus port
