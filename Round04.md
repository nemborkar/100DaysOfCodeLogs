# #100DaysOfCode Round04 Log - Nem Borkar

The log of my #100DaysOfCode challenge. Started on [February 22, Sunday, 2021].

## Log

### 20210502 Day52
Continued my mission to get VPN encryption at an open Starbucks wifi hotspot. With my new VPN server, I was able to read server logs. TLS handshake was failing. I'm assuming they are using a firewall to block OpenVPN's port 1194 traffic

Course of action:
- find commands to check own network firewall and ports (home + starbucks)
- find which ports are blocked by the starbucks network firewall (find and use one that's not blocked)
- change my PC's OpenVPN znd OpenVPN3 to use different ports

### 20210501 Day51
Mostly used [this article](https://www.linode.com/docs/guides/install-openvpn-access-server-on-linux/) and the OpenVPN access server and client software to set it up  
It was only 20% more headache than I originally anticipated  
Keeping the details in my private logs for security purposes  


### 20210430 Day50
Chose Linode to setup my own VPN server  
Mostly read about the architecture and initiated the server  

