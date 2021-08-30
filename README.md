# Enterprise-Network-Packet-Tracer-
A simulation of a real world network. Illustrates the following technologies:
1. DHCP Server configuration for automatic IP allocation
2. VLAN creation
3. Router-on-a-stick Inter-VLAN Routing
4. Configuration of Web server, DNS server, and FTP server.
5. OSPF routing within enterprise network
6. Default routing to connect to ISP
7. ACL Configuration for granting and denying permissions to networks

Verify the working of this project by following the below steps:
1. From the browser of hosts of Network A (VLAN 10), try accessing the two web servers. A message saying "Request Timeout" will appear indicating that hosts are restricted.
   Also, try pinging hosts of other networks from these hosts. The pings do not work due to a NACL configuration.
2. Try accessing the two web servers from Network B. Hosts of Network B (VLAN 20) cannot access the ISP server and a "Request timeout" message is displayed, but can access the web    server of network D (www.nscbttc.co.in). 
3. Try accessing the two web servers from Network C. Hosts of Network C cannot access the web server of Network D and a "Request timeout" message is displayed, but can access the    ISP server(www.training.co.in).
4. Try pinging PC2 and PC3 of Network D using their names. Create a file in the PC2’s text editor and upload it to the ftp server. Now, verify the existence of this file on the      FTP server via the Services->FTP tab.  
