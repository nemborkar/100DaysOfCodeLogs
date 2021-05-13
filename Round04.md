# #100DaysOfCode Round04 Log - Nem Borkar

The log of my #100DaysOfCode challenge. Started on [February 22, Sunday, 2021].

## Log

### 20210513 Day57
Continued the string related coding challenges  
TIL When solving for space complexity, see if you can predict and define dataset sizes (regardless of input)  
Keeping it independent from the input improves Big O time and optimizes memory usage  

### 20210512 Day56
Tried some coding challenges and found these nuggets  
- when counting chars in a given string, try using a 26 char hashmap A-Z
- when iterating, if space is not a problem, copy list. After processing an element, move it to end + pop to shorten next iteration

### 20210510 Day55
Getting back in after a long break. Started taking a look at Jenkins and CI/CD pipelines  

### 20210506 Day54
Dipped my toes into memcache. It's very similar to Redis (because essentially datastore and in-memory caching)  
Seems like Memcache is multithreaded and simple but Redis is simglethreaded and offers a lot of utility  
Also ended up reading [this comparison](https://www.linkedin.com/pulse/memcached-vs-redis-which-one-pick-ranjeet-vimal/)

[AWS' Elasticache compares them too](https://aws.amazon.com/elasticache/redis-vs-memcached/)


### 20210503 Day53
Learned the basics of redis today and tried out the RDM GUI 
I'm guessing memory-optimized virtual servers would be ideal for redis since it's optimized for time but sacrifices space by caching queries in memory  
Docs are pretty solid too. Installation and running server is pretty streamline too, so no complains there  

When you try to ping the server, it responds with PONG  
I laughed WAY TOO HARD  

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

