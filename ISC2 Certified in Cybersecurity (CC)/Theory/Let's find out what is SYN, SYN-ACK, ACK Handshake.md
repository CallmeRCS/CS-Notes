Between the client and the server, there is a system for synchronizing and acknowledging any request that is know as ==three way handshake==. This handshake is used to establish a TCP connection between two devices. Depending on the protocol, there may be additional connection negotiations taking place.
#### Let's go step by step on this handshake

1. The client sends synchronization  ==SYN packet== to the web servers **ports 80 or 443**. This is to stablish a connection.
2. The web server replies to the SYN packet with an acknowledgment known as ==SYN/ACK==.
3. Finally, the client acknowledges the connection with an acknowledgment ACK

![[Pasted image 20250901171515.png]]