The main concept of a network is the following

**"A network is simply two or more computers linked together to share data, information or resources"**

There are 2 basic types of networks:
- Local Area Network (LAN): Is a network typically spanning a single floor or building. This commonly a limited geographical area.
- Wide Are Network (WAN): Is usually assigned to the long-distance connections between geographically remote networks.
#### Introduction to the network devices

- Hubs: Are used to connect multiple devices in a network. They're less likely to be seen in business or corporate networks than in home networks. Those devices are not as smart as switches or routers.

- Firewall: It is an essential tool in managing and controlling network traffic and protecting the network. Is a network device used to filter traffic.  It is typically deployed between a private network and the internet, but it can also be deployed between departments of an organization. It filters traffic based on a defined set of rules, also called filters or ACL (access control list).

- Switch: A better option than a HUB is a switch but not as a smart as routers. Are wired devices that know the addresses of the devices connected to them and route traffic to that port / device rather than retransmitting to all devices. Switches can also create separate broadcast domains when used to create [[VLANs Virtual Local Area Network]].

- Server: Is a computer that provides information to other computers on a network. Some common servers, print servers, databases servers and file servers. All of these are, by design, networked and accessed in some way by a client computer. Usually secured differently than workstation to to protect the information they contain.

- Router: It is used to control traffic flow on networks and are often used to connect similar networks and control traffic flow between them. It can be wired or wireless and can connect multiple switches. It determines the best "route" for the traffic to flow across the network.

- Endpoint: Are the ends of network communication link. One end is often at a server where a resource resides, and the other end is often a client making a request to use a network resource. As an example it could be other workstation, server, laptop, tablet, mobile phone etc.
#### Other Networking terms

- Ethernet (IEEE 802.3): is a standard that defines ==wired connections== of networked devices. Defines the way data is formatted over the wire to ensure disparate devices can communicate over the same cables.
#### Types of devices address

- Media Access Control (MAC) Address: Every network device has a MAC address. Generally assigned in the firmware of the interface.
>An example is: 00-13-02-1F-58-F5 => There are 24 bits and the first 3 bytes of the address denote the vendor or manufacturer of the physical network interface. Every MAC address is unique, it couldn't be 2 devices with the same MAC address in the local network.

- Internet Protocol (IP) Address: An IP hosts associate that address with a unique logical address. This logical IP address represents the network interface within the network and can be useful to maintain communication when a physical device is swapped with new hardware. 
>An example would be: 192.168.1.1 and 2001:db8::ffff:0:1
#### What is Wi-Fi?

Is a form of wireless networking is a popular method of connecting corporate and home systems because of the ease of deployments and relatively low cost. It has made networking more versatile than ever before. Workstations and portable systems are no longer tied to cable but can roam freely within the signal range of the deployed wireless access points. However, with this freedom comes additional vulnerabilities.
>In a LAN, threat actors need to enter the physical space of immediate vicinity of the physical media itself. For wired networks, this can be done by placing sniffer taps onto cables, plugging in USB devices, or using other tools that requires physical access to the network. By contrast, wireless media intrusions can happen at a distance. 
#### Microsegmentation

Modern cyber attacks take advantage of traditional security models to move easily between systems within datacenter. Microsegmentation aids in protecting against threats. A fundamental design requirement of microsegmentation is to understand the protection requirements for traffic within data center and traffic to and from the internet traffic flows. Let's see [[Characteristics of microsegmentation]]. [[Let's see and example of microsegmentation called Demilitarized zone or DMZ]].
#### Tools to identify and prevent threats
![[Pasted image 20240816050544.png]]
>This table lists tools used to identify threats that can help to protect against many types of attacks like virus and malware denial of service attacks. Spoofing on path and side channel attacks. From monitoring activity on a single computer like with HIDS to gathering log data like with seam to filtering network traffic. Like with firewalls, these tools help to protect entire networks and individual systems. While anti malware, firewall and intrusion protection system tools also have the added ability to prevent threats
#### Other topics regardless to network and threats 
[[Let's talk more in depth about the tools to identifying and prevent threats]].
[[Let's talk more in depth about the 7 OSI Layers in a practical way]]
[[Let's find out some of the most common attacks or exploits within the Network (TCP-IP)]].
[[Let's find out what is SYN, SYN-ACK, ACK Handshake]].
[[🌐Types of DoS (Denial of Services) Attacks]]
[[🦠 Types of Malware]]
[[🎭 Social Engineering & Fraud Attack Types]]
[[Physical vs Logical ports (Main characteristics)]]
[[Most common logical ports]]
[[Networks design overall]]
[[Firewalls defenses on a OSI layer context]]
#### Preventing threats (some basic steps to reduce the risk of a possible threat)

- Keep systems and applications up to date.
- Remove or disable unneeded services and protocols
- Use intrusion detection and prevention systems
- Use firewalls
>Firewalling refers to the process of designing, using, or operating different processes in ways that isolate high-risk activities from lower-risk ones. Depending on the context, firewalls would be position on a gateway; it may be need it in a network zoning or segregation of different levels of sensivity.
- Use up-to-date anti-malware softwares
#### Managed Service Provider (MSP)

Is a company that manages information technology assets for another company. Small and medium-sized businesses commonly outsource part or all of their information technology functions to and MSP to manage day-to-day operations or to provide expertise in areas the company do not have. 

Today, many MSPs offer cloud-based services augmenting SaaS solutions with active incident investigation and response activities. 
>Example could be a Managed Detection and Response (MDR) service, where a vendor monitors firewall and other security tools to provide expertise in triaging events. 
#### Service-Level Agreement (SLA) in Cloud environment

Is an agreement between a cloud service provider and a cloud service customer based on a taxonomy of cloud computing-specific terms to set the quality of the cloud service delivered. Think of a rule book and legal contract; that combination is what you have in a service-level agreement (SLA). The purpose is to document specific parameters, minimum service levels, and remedies for any failure to meet the specified requirements. [[Some important points to be aware in SLA]].
#### SLA vs Memorandum of Understanding (MOU) / Memorandum of Agreement (MOA)

Before entering to talk about the main difference let's talk about what means each of the new concepts beside the Service Level Agreement. Let's first explain a short example in which we have 2 companies, each are on the same industry, some of them make an agreement in which something happens to one of the duplex, the other part will help providing the resources need it to stay on board during the disaster or situation at the moment. In other terms, both companies had decide that they are not going to compete based on safety and a security instead based on service, price and customer loyalty. 

As the example explain a concept called "Joint Operating Agreements" JOA. It exist the Memorandum of Understanding (MOU) and the Memorandum of Agreement (MOA). ==Sometimes these agreements are mandated by regulatory requirements, or they might be part of the administrative safeguard instituted by an entity within the guidelines of its industry==.

**The difference between a MOA or MOU and a SLA is that an MOU is more directly related to what can be done with a system or the information. MOUs/MOAs focus on the broader scope of agreements, while SLAs provide detailed specifications about the services.**
>If for example, the SLA promises 100% accessibility to information, is the access directly to you at the moment, or is it access to their website or through their portal when they open on Monday? That's where you'll rely on your legal team, who can supervise and review the conditions carefully before you sign on the dotted line.
#### Redundancy

The idea of designing with redundancy is to create systems with duplicate components so that if a failure were to occur, there would be a backup. This can apply to the data center as well. Risk assessments pertaining to the data center should identify when multiple separate utility service entrances are necessary for redundant communication channels and/or mechanisms.
>If the organization requires full redundancy, devices should have 2 power supplies connected to diverse power sources. Those power source would be backed up by batteries and generators. In a high-availability environment, even generators would be redundant and fed by different fuel types.
#### On-Premises Data Centers conformation

At this point, we all know what is an on-premises data centers and which is their functionality. But we do not talk a lot on how is conformed it and which measure do we need to have to reduce risks and have a better performance. 

1. Data Center / Closest: Basically is where we safeguard all the servers of a company. Is integral to overall information system security and reliability. Protecting access to the physical layer of the network is important in minimizing intentional or unintentional damage. It may include:
	- Phone, network, special connections
	- ISP or telecommunications provider equipment
	- Servers
	- Wiring and/or switch components

2. Heating, Ventilation, and Air Conditioning (HVAC) / Environmental: Proper management of data center temperatures, including cooling, is essential. Cooling is not the only issue with airflow: Contaminants like dust and noxious fumes require appropriate controls to minimize their impact on equipment.
>	For example, the recommended range for optimized maximum uptime and hardware life is from 64° to 81° F (18° to 27° C). And it is recommended that a rack have 3 temperature sensors, positioned at the top, middle, and bottom of the rack, to measure the actual operating temperature of the environment


3. Power: Power at the site is always an integral part of data center operations. Regardless of fuel source, backup generators must be sized to provide for the critical load (the computing resources) and the supporting infrastructure. As with data backups, testing is necessary to ensure the failover to alternate power works properly.

4. Fire Suppression: For server rooms, appropriate fire detection / suppression must be considered based on the size of the room, typical human occupation, egress routes, and risk of damage to equipment,












