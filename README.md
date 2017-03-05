![](img/4-layer-overview.png?raw=true)
![](img/layer-detail.png?raw=true)

1. The IP Service Model
* Tries to prevent packets looping forever by having datagram's TTL (time to live). It ensures datagram is alive only during TTL, if not, it assumes datagrams stuck in a loop. Every router is required to decrement the TTL value. If the TTL is 0, the router will drop it. 
* It fragments packets if they are too long. 
* It uses a header checksum to reduce chances of delivering datagram to wrong destinatino. 
* It allows for new versions of IP. (IPv4 uses 32 bit addresses. IPv6 uses 128 bit addresses.)

