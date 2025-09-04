This types of networks allow network administrators to use switches to create software-based LAN segments, which can segregate or consolidate traffic across multiple switch ports.
#### Important points to take in consideration

- Devices that shares a VLAN communicate through switches as if they were on the same Layer 2 network.
- Since VLANs act as discrete networks, communications between VLANs must be enabled.
- Broadcast traffic is limited to the VLAN, reducing congestion and reducing the effectiveness of some attacks.
- Administration of the environment is simplified, as the VLANs can be reconfigured when individuals change their physical location or need access to different services.
- VLANs do not guarantee a network's security, there are attacks that allows a malicious user to see traffic from other VLANs (called "VLAN hoping"). 
- VLAN technology is only one tool that can improve the overall security of the network environment.
#### Let's see a short example of a VLAN

![[Pasted image 20240823151654.png]]
##### Interpretation:
Devices that share a VLAN communicate through switches as ==if they were on the same Layer 2 network==. The image upstairs shows different VLANs–red, green, and blue–connecting separate sets of ports together, while sharing the same network segment consisting of the 2 switches and their connection.