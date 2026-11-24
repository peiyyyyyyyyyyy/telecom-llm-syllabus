# 1.2 通訊協定　GSMA 練習題（1231 題）（第 2／7 頁）

所屬：[1.2 通訊協定](1-2.md)

只收 GSMA 訓練題；不含驗證集與測試集，並已去除和驗證／測試題相同或相似、重複、標註衝突的題目。題目依小節歸類（抽查正確率約 95%）。

頁次：[1](1-2-gsma-1.md)　**2**　[3](1-2-gsma-3.md)　[4](1-2-gsma-4.md)　[5](1-2-gsma-5.md)　[6](1-2-gsma-6.md)　[7](1-2-gsma-7.md)

## 1.2.3 傳輸層：TCP、UDP、SCTP（94 題）（續）

**1.2.3-74.** What is the purpose of the PAR mechanism in TCP?

- A. To recover from the loss of a segment by retransmitting it at timed intervals
- B. To govern the amount of data dispatched by a sending TCP
- C. To allow multiple ULPs within a single host and multiple processes in a ULP to use TCP simultaneously
- D. To synchronize and initialize the mechanism information between two ULPs
- E. To indicate to a receiving ULP that "urgent" data appear in the upcoming data stream

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6474`）

</details>

**1.2.3-75.** What port is used by DNS protocol? [TCP/IP]

- A. Port 20
- B. Port 53
- C. Port 80
- D. Port 443
- E. Port 8080

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6489`）

</details>

**1.2.3-76.** What main mechanism enables hosts to efficiently utilize different networks with Multipath TCP (Transmission Control Protocol)?

- A. Coupled congestion schemes.
- B. Address allocation.
- C. Network Ingress Filtering.
- D. Per-packet load balancing.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6527`）

</details>

**1.2.3-77.** What are the most urgent issues of TCP (Transmission Control Protocol) that QUIC v1 addresses?

- A. Multiplexing
- B. Head-of-line blocking
- C. Mandatory encryption
- D. Reduced connection establishment time with 0-RTT support
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6668`）

</details>

**1.2.3-78.** What is important for linking incoming messages of a Client to the correct Server thread? [TCP/IP]

- A. Using the main thread to handle all requests
- B. Using a unique local protocol number for each Client
- C. Using the Server's IP address
- D. Using the Server's physical connection

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6830`）

</details>

**1.2.3-79.** What does a concurrent Server do when it receives a request? [TCP/IP]

- A. It waits for other Clients to finish before serving the request
- B. It creates a new thread and a new process for each request
- C. It handles the request with the main thread
- D. It waits for the next incoming request

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6879`）

</details>

**1.2.3-80.** What is the main difference between TAPS and BSD (Berkeley Software Distribution) sockets?

- A. TAPS supports only stream communication, while BSD sockets support both stream and datagram communication
- B. TAPS is fully asynchronous and event-driven, while BSD sockets require active polling for incoming traffic
- C. TAPS provides more modern transport services, while BSD sockets are limited to TCP and UDP
- D. TAPS requires a more complex programming style, while BSD sockets are easier to use

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7185`）

</details>

**1.2.3-81.** Which standardized architecture leverages the 0-RTT Convert protocol?

- A. GRE-based L3 overlay tunneling.
- B. Implicit Multipath TCP deployment mode.
- C. Explicit Multipath TCP deployment mode.
- D. L4 Multipath using MPTCP.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7292`）

</details>

**1.2.3-82.** Which layer provides for the reliability that the IP (Internet Protocol) lacks?

- A. Network layer
- B. Transport layer
- C. Data-link layer
- D. Application layer
- E. Physical layer

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7477`）

</details>

**1.2.3-83.** Which protocol is commonly used for real-time audio? [TCP/IP]

- A. TCP
- B. UDP
- C. FTP
- D. HTTP
- E. SSH

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7660`）

</details>

**1.2.3-84.** What is Multipath TCP (MPTCP)?

- A. A fully backward-compatible extension of Transmission Control Protocol that allows applications to use multiple connections at the same time without any changes to the socket API.
- B. A protocol that increases throughput by using multiple paths simultaneously and provides redundant links in case of link failures.
- C. A protocol that improves load balancing and reduces latency in data centers by using multiple paths between hosts.
- D. A protocol that adds multipath capabilities to the Quick UDP Internet Connections (QUIC) protocol.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7846`）

</details>

**1.2.3-85.** Which protocol uses TCP port 22? [TCP/IP]

- A. HTTP
- B. HTTPS
- C. SSH
- D. NTP

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7981`）

</details>

**1.2.3-86.** What is the purpose of the RACK-TLP loss detection algorithm for TCP (Transmission Control Protocol)?

- A. Fast recovery
- B. Improving tail loss
- C. Triggering ACK feedback through Tail Loss Probes
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7986`）

</details>

**1.2.3-87.** What is the function of a Multipath TCP (Transmission Control Protocol) proxy in hybrid access networks?

- A. To proxy Multipath TCP connections and convert them into TCP connections.
- B. To act as a network function deployed by the network operator.
- C. To allocate addresses to HCPEs and HAGs.
- D. To implement Network Ingress Filtering.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6691`）

</details>

**1.2.3-88.** What is the benefit of using TAPS (Transport services) for smaller players such as small and medium-sized enterprises (SMEs)?

- A. TAPS allows smaller players to develop custom-made protocols
- B. TAPS provides a huge amount of manpower for development
- C. TAPS gives smaller players access to a richer set of services without investing a huge amount of manpower
- D. TAPS promotes unfairness between big and small developers
- E. TAPS only benefits big developers

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7852`）

</details>

**1.2.3-89.** Which of the following IETF RFCs defines the User Datagram Protocol (UDP)?

- A. RFC 791
- B. RFC 768
- C. RFC 1195
- D. RFC 1771

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-425`）

</details>

**1.2.3-90.** Which of the following protocols is used for managing the transport of data between the user equipment (UE) and the network in an O-RAN system?

- A. UDP
- B. SCTP
- C. TCP
- D. HTTP

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-496`）

</details>

**1.2.3-91.** Which protocol is mandated for transporting HTTP/2 traffic according to the provided context?

- A. UDP
- B. TCP
- C. SCTP
- D. TLS

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-602`）

</details>

**1.2.3-92.** Which protocol is used for the transport layer in O-RAN, providing reliable and ordered delivery of data?

- A. Internet Protocol (IP)
- B. Stream Control Transmission Protocol (SCTP)
- C. User Datagram Protocol (UDP)
- D. Transmission Control Protocol (TCP)

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-754`）

</details>

**1.2.3-93.** What is the Incast issue?

- A. A problem in data centers caused by high bandwidth and low latency links
- B. Congestion caused by a large number of simultaneous flows to a single aggregator node
- C. An issue in wireless channels where packets are lost due to degraded channel quality
- D. A phenomenon that occurs when two or more data flows share the same Transmission Control Protocol connection
- E. A problem of bufferbloat in low capacity access links

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2731`）

</details>

**1.2.3-94.** What is the primary motivation behind multipath QUIC?

- A. To improve handovers and user Quality-of-Experience
- B. To enable unreliable delivery for real-time communication
- C. To provide compatibility with other transport protocols
- D. To aggregate all available network resources to send data through a single connection

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6533`）

</details>

## 1.2.4 路由協定：OSPF、BGP（35 題）

**1.2.4-1.** What is a 'Router' in networking?

- A. A device that connects multiple computers within a single household.
- B. A device that connects different types of networks, such as Ethernet and Wi-Fi.
- C. A device used to amplify Wi-Fi signals for extended coverage.
- D. A protocol used for voice communication over the internet.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4996`）

</details>

**1.2.4-2.** What is the purpose of routers in an internet? [TCP/IP]

- A. To monitor all link aggregation groups
- B. To communicate with different hosts connected to different networks
- C. To send LACP frames
- D. To exchange configuration information between systems
- E. To connect networks together

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5813`）

</details>

**1.2.4-3.** What information does a router exchange with its neighbors in EIGRP (Enhanced Interior Gateway Routing Protocol)?

- A. Routing tables
- B. Update messages
- C. Neighbor lists
- D. Topology tables

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-21`）

</details>

**1.2.4-4.** What does a link or router going down mean to the shortest path spanning tree?

- A. An INVALID_COMPLETE message is sent to the root
- B. A controlled flooding process is initiated
- C. A routing loop is prevented
- D. A subtree of nodes have to modify their route to a particular subnet
- E. A START_ROUTING message is spread to all nodes

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-117`）

</details>

**1.2.4-5.** What is the purpose of setting a timer for each node in RIP-Tree?

- A. To prevent routing loops
- B. To find a new valid route
- C. To spread the START_ROUTING message
- D. To relay messages to all descendants
- E. To handle single failure nodes

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-329`）

</details>

**1.2.4-6.** Which type of routing protocol takes into account the information available from different layers and provides a solution to several networking issues?

- A. Location-based routing
- B. Source-based routing
- C. Hop-by-hop routing
- D. Cross-layer routing
- E. Clustered routing

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1019`）

</details>

**1.2.4-7.** Which routing protocol employs objective functions to specify the selection of routes based on QoS (Quality of Service) requirements?

- A. 6LoWPAN
- B. RPL
- C. 6TiSCH
- D. DSME
- E. IEEE 802.11e

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1143`）

</details>

**1.2.4-8.** What technique does Babel use to solve starvation?

- A. Global synchronization
- B. Sequenced routes
- C. Periodic sequence number increase
- D. Hop by hop forwarding
- E. Forwarding loop detection

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1513`）

</details>

**1.2.4-9.** Which routing protocol is commonly used for inter-domain routing in the Internet?

- A. Intermediate System to Intermediate System
- B. Open Shortest Path First
- C. Routing Information Protocol
- D. Border Gateway Protocol

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1672`）

</details>

**1.2.4-10.** What advantage does AODV (Ad-hoc On-Demand Distance Vector) have over other routing protocols?

- A. Fast reaction to topological changes in the network
- B. Central administrative system control
- C. Large storage and energy requirements
- D. No reliance on route discovery flood

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2050`）

</details>

**1.2.4-11.** What is the maximum hop count in the RIP protocol?

- A. 8
- B. 12
- C. 15
- D. 20

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2111`）

</details>

**1.2.4-12.** What is the purpose of the sequence numbers in the AODV (Ad-hoc On-Demand Distance Vector) protocol?

- A. To determine whether routing information is up-to-date
- B. To prevent routing loops
- C. To distinguish up-to-date routes from older, possibly invalid routes
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2442`）

</details>

**1.2.4-13.** What are the three working modes of RIP-MTI?

- A. Normal Mode, Strict Mode, and Optimistic Mode
- B. Normal Mode, Strict Mode, and Careful Mode
- C. Basic Mode, Advanced Mode, and Expert Mode
- D. Basic Mode, Strict Mode, and Careful Mode
- E. Strict Mode, Optimistic Mode, and Careful Mode

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3402`）

</details>

**1.2.4-14.** What is a disadvantage of the Hold-Down feature in the RIP protocol?

- A. It decreases network security
- B. It limits the size of the network
- C. It consumes more network bandwidth
- D. It increases network latency

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3942`）

</details>

**1.2.4-15.** What is a disadvantage of EIGRP (Enhanced Interior Gateway Routing Protocol)?

- A. Not good at dealing with big hierarchy networks
- B. Slow convergence in large networks
- C. Waste of bandwidth in broadcast networks
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4065`）

</details>

**1.2.4-16.** What is an advantage of AODV (Ad-hoc On-Demand Distance Vector) in terms of storage and energy requirements?

- A. Every node stores the entire routing table
- B. Each node only needs to store routing entries it is responsible or interested in
- C. No need for routing tables in AODV
- D. High energy requirements for AODV

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4160`）

</details>

**1.2.4-17.** What is the count to infinity problem in the RIP protocol?

- A. A problem where routers keep increasing the hop count to infinity
- B. A problem where routers lose connection to each other
- C. A problem where routers get stuck in a routing loop
- D. A problem where routers cannot update their routing tables

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4712`）

</details>

**1.2.4-18.** Which type of routing protocol selects the next hop for transmission based on minimum transmission delay?

- A. Location-based routing
- B. Source-based routing
- C. Hop-by-hop routing
- D. Cross-layer routing
- E. Clustered routing

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4853`）

</details>

**1.2.4-19.** What does the term 'complete view' mean in the context of network view for routing information?

- A. No updating mechanism for routing information is in place
- B. Routing decision-maker has routing information about a subset of the nodes
- C. Routing information is updated in predefined time intervals
- D. Routing information is updated based on events in the network
- E. Routing decision-maker has routing information about all nodes

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4925`）

</details>

**1.2.4-20.** How does a distance-vector routing protocol differ from a link-state routing protocol?

- A. Distance-vector protocols require nodes to store all information about the network topology, while link-state protocols only require storing next hop and distance information.
- B. Link-state protocols only require nodes to store next hop and distance information, while distance-vector protocols require storing all information about the network topology.
- C. Link-state protocols have less computational complexity and message overhead compared to distance-vector protocols.
- D. Distance-vector protocols have less computational complexity and message overhead compared to link-state protocols.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5082`）

</details>

**1.2.4-21.** What is the definition of geographical routing?

- A. The conversion of the PDU's geographical area definition into a network identifier.
- B. The conversion of the PDU's geographical area definition into a radio signal.
- C. The conversion of the PDU's geographical area definition into a radio coverage map.
- D. The conversion of the PDU's geographical area definition into a transmission protocol.
- E. The conversion of the PDU's geographical area definition into a routing table.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5230`）

</details>

**1.2.4-22.** What is the purpose of the Hold-Down feature in the RIP protocol?

- A. Prevents count to infinity problem
- B. Improves network security
- C. Delays the routing updates
- D. Reduces network congestion

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5336`）

</details>

**1.2.4-23.** Which type of networks are distance-vector routing protocols more suitable for?

- A. Small or median sized networks
- B. Large networks divided into areas
- C. Networks with unlimited storage and computing power
- D. All types of networks

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5351`）

</details>

**1.2.4-24.** What information does each entry in the AODV (Ad-hoc On-Demand Distance Vector) routing table include?

- A. Routing destination
- B. Number of hops of the route
- C. Destination sequence number
- D. Expiration time for the routing table entry
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5577`）

</details>

**1.2.4-25.** What is the basis of EIGRP's operation?

- A. Open Shortest Path First (OSPF)
- B. Routing Information Protocol (RIP)
- C. Diffusing Update Algorithm (DUAL)
- D. Intermediate System to Intermediate System (IS-IS)

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5653`）

</details>

**1.2.4-26.** What is the purpose of the INVALID_RELAY message in RIP-Tree?

- A. To prevent routing loops
- B. To find a new valid route
- C. To spread the START_ROUTING message
- D. To relay messages to all descendants
- E. To inform the parent with an INVALID_COMPLETE message

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5767`）

</details>

**1.2.4-27.** What is the purpose of the Split Horizon technique in the RIP protocol?

- A. Enhances security
- B. Improves routing convergence
- C. Reduces network bandwidth
- D. Prevents routing loops

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6217`）

</details>

**1.2.4-28.** What is the Routing Information Protocol (RIP)?

- A. A hierarchical routing protocol
- B. A link-state routing protocol
- C. A distance vector routing protocol
- D. A path vector routing protocol

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7077`）

</details>

**1.2.4-29.** What assumption is AODV (Ad-hoc On-Demand Distance Vector) based on?

- A. All nodes have the same routing destination
- B. All nodes have the same sequence number
- C. All nodes will cooperate
- D. All nodes have the same number of hops

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7166`）

</details>

**1.2.4-30.** Which type of routing strategy combines proactive and reactive routing protocols?

- A. Proactive
- B. Reactive (on-demand)
- C. Hybrid
- D. Geographic
- E. Bio-inspired

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7212`）

</details>

**1.2.4-31.** What is the main advantage of RIP-MTI over RIP?

- A. RIP-MTI reduces the number of loops in network routing
- B. RIP-MTI provides more detailed technical information
- C. RIP-MTI eliminates all CTI problems
- D. RIP-MTI is compatible with newer versions of RIP
- E. RIP-MTI allows for faster convergence in complex network topologies

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7304`）

</details>

**1.2.4-32.** What does AODV (Ad-hoc On-Demand Distance Vector) rely on for route discovery in a highly dynamic network?

- A. Central administrative system control
- B. Route Error messages
- C. Routing Reply messages
- D. Route discovery flood

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7493`）

</details>

**1.2.4-33.** Which routing protocol employs graph routing to enhance network reliability through multiple routing paths?

- A. RPL
- B. 6TiSCH
- C. ISA-100.11a
- D. WirelessHART
- E. TSCH

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7802`）

</details>

**1.2.4-34.** What is the full form of RIP-MTI?

- A. Routing Information Protocol with Minimum Traffic Information
- B. Routing Information Protocol for Maximum Topology Information
- C. Routing Information Protocol with Minimal Technical Information
- D. Routing Information Protocol for Maximum Technical Information
- E. Routing Information Protocol with Minimal Topology Information

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7907`）

</details>

**1.2.4-35.** What is the primary method used by an SR-PCE to gather topology information from different domains in an Open Radio Access Network (O-RAN)?

- A. BGP-4
- B. BGP-LS
- C. PCEP
- D. Flex-algo

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1033`）

</details>

## 1.2.5 MPLS 與 VPN（13 題）

**1.2.5-1.** What does the acronym VPN stand for?

- A. Voice Packet Network
- B. Virtual Private Network
- C. Visual Presentation Network
- D. Voice and Picture Network
- E. Video Protocol Network

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7`）

</details>

**1.2.5-2.** What is the purpose of the sequence numbers added to each encapsulated packet in GRE-based L3 overlay tunneling?

- A. To enable host mobility.
- B. To support Network Ingress Filtering.
- C. To prevent TCP collapse.
- D. To load-balance packets over different access networks.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-8055`）

</details>

**1.2.5-3.** Which technologies can be used to construct a private connection for URLLC (Ultra reliable and low latency communications) in the backbone network?

- A. Software Defined Network (SDN)
- B. Virtual Network Slicing
- C. Both option 1 and option 2
- D. Millimeter-wave communication

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6842`）

</details>

**1.2.5-4.** Which of the following EVPN services is used for point-to-point Layer 2 communication without MAC learning?

- A. EVPN E-Tree
- B. EVPN E-LAN
- C. EVPN E-Line
- D. EVPN VLAN-based

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-231`）

</details>

**1.2.5-5.** What is the primary mechanism used by an ingress PE in a Seamless MPLS architecture to resolve service NLRI received from a remote PE?

- A. BGP-LU loopback of the remote PE
- B. Local intra-domain MPLS tunnel (SR/SR-TE or legacy RSVP/LDP)
- C. Inter-domain BGP-CT tunnels tunneled inside intra-domain tunnels
- D. Intra-domain tunnels (LDP, RSVP, SR/SR-TE)

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-472`）

</details>

**1.2.5-6.** In an SRv6 underlay transport network, what are the three primary functions of an SR-PCE?

- A. Gather topology data, compute paths, and provide control and management functions.
- B. Forward traffic, manage network resources, and provide security services.
- C. Collect user data, analyze traffic patterns, and optimize network performance.
- D. Encrypt traffic, authenticate users, and enforce access control policies.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-487`）

</details>

**1.2.5-7.** Which IETF RFC defines the Segment Routing Architecture?

- A. RFC 8200
- B. RFC 8395
- C. RFC 8402
- D. RFC 8476

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-523`）

</details>

**1.2.5-8.** Which of the following technologies are used for transport in the O-RAN Fronthaul network described in the context?

- A. SR-MPLS and SRv6
- B. Ethernet
- C. eCPRI
- D. L2 VPN and EVPN VPWS

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-596`）

</details>

**1.2.5-9.** How does BGP-LU operation optimize scaling in a seamless MPLS architecture?

- A. By installing BGP-LU prefixes in the forwarding table (FIB) to improve routing efficiency.
- B. By installing BGP-LU prefixes only in the routing table (RIB), minimizing forwarding plane resource usage.
- C. By using a centralized routing control to manage all BGP-LU prefixes.
- D. By utilizing a hierarchical routing approach, with BGP-LU prefixes distributed across multiple routers.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-804`）

</details>

**1.2.5-10.** What are the recommended multicast solutions for overlay networks in O-RAN?

- A. BGP-MVPN and EVPN-BUM with tunnel segmentation
- B. Segment Routing
- C. Underlay tunnel solutions
- D. All of the above

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1086`）

</details>

**1.2.5-11.** In a 5G C-RAN architecture with a legacy D-RAN, what type of VPN service is used to carry Open Fronthaul traffic from the cell site to the O-DU located in the Hub site?

- A. L2TP
- B. IPsec
- C. VPWS EVPN
- D. GRE

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1110`）

</details>

**1.2.5-12.** What type of traffic is classified by the transport network domain PE ingress when it receives Ethernet frames?

- A. Only IP packets
- B. Only Ethernet frames
- C. Both IP packets and Ethernet frames
- D. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1136`）

</details>

**1.2.5-13.** Which of the following is NOT a classic MPLS control plane technology mentioned in the context?

- A. LDP
- B. RSVP
- C. SR
- D. BGP-LU

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1191`）

</details>

## 1.2.6 無線介面協定：RRC、SDAP、PDCP、RLC、MAC、PHY（278 題）

**1.2.6-1.** In the conventional frame structure for downlink transmissions to URLLC (Ultra-Reliable Low-Latency Communication) devices, how are messages encoded?

- A. Each message is encoded into a separate packet
- B. All messages are jointly encoded in a single packet
- C. Each message is encoded into a separate frame
- D. All messages are jointly encoded in a single frame

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-621`）

</details>

**1.2.6-2.** What is the definition of Switching SCell (sSCell)?

- A. A SCell that is used for sidelink transmission.
- B. A SCell that is released when the primary cell fails.
- C. A SCell that uses a different numerology than the parent cell.
- D. A SCell that is configured with cross-carrier scheduling to PCell/PSCell.
- E. A SCell that is used for uplink transmissions only.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-623`）

</details>

**1.2.6-3.** What is the length of the ZC (Zadoff Chu) sequences used for the Primary Synchronization Sequence (PSS) in LTE?

- A. 31
- B. 63
- C. 127
- D. 839
- E. 139

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-750`）

</details>

**1.2.6-4.** What is an acceptable cell? [3GPP Release 17]

- A. A cell that provides limited service for emergency calls and notifications
- B. A cell that provides normal service for public use
- C. A cell that is not barred and fulfills cell selection criteria
- D. A cell that is reserved for operator use

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-774`）

</details>

**1.2.6-5.** What is the procedure called by which a UE acquires time and frequency synchronization with a cell and detects the Cell ID of that cell? [3GPP Release 17]

- A. Power control
- B. Cell search
- C. Link adaptation
- D. Coordinated Multi-Point transmission
- E. Wake-up signal

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-811`）

</details>

**1.2.6-6.** Which physical channel carries the DL-SCH and PCH? [3GPP Release 17]

- A. PDSCH
- B. PMCH
- C. PUCCH
- D. PBCH

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-825`）

</details>

**1.2.6-7.** What is the purpose of the self-contained slot structure in 5G NR?

- A. To support both UL and DL directions within a single slot
- B. To reduce the waiting time in TDD systems
- C. To improve the reliability of control messages
- D. Both option 1 and option 2

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1064`）

</details>

**1.2.6-8.** What physical channel is used for sidelink transmitted data itself? [3GPP Release 17]

- A. PSCCH
- B. PSBCH
- C. PSFCH
- D. PSSCH
- E. Synchronization signal

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1084`）

</details>

**1.2.6-9.** What is the maximum number of OFDM (Orthogonal Frequency Division Multiplex) symbols in a mini-slot in 5G NR?

- A. 2
- B. 4
- C. 7
- D. 8

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1772`）

</details>

**1.2.6-10.** What is the purpose of dynamic time division duplexing in 5G New Radio?

- A. To allocate frequency bands dynamically based on traffic demands
- B. To support single-input single-output
- C. To enable distributed multiple-input multiple-output
- D. To provide power savings for user equipments
- E. To enable multi-hop integrated access and backhaul

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2019`）

</details>

**1.2.6-11.** What does SFN stand for?

- A. System Frame Notation
- B. System Facing Network
- C. System Frame Number
- D. Synchronous Frame Network
- E. Synchronous Frame Notation

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2101`）

</details>

**1.2.6-12.** What is the purpose of bundle frequency hopping in the LTE network? [3GPP Release 14]

- A. To enhance bundle frequency hopping
- B. To enable UL/DL bitrate recommendation
- C. To improve PUSCH enhancement mode
- D. To support multi-subframe channel estimation

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2375`）

</details>

**1.2.6-13.** How does the UE determine the p0-PUCCH-Value value if it is not provided any of pdsch-HARQ-ACK-Codebook? [3GPP Release 17]

- A. From the pathlossReferenceRSs value
- B. From the pucch-PathlossReferenceRS-Id value
- C. From the p0-Set value
- D. From the pucch-PowerControl value
- E. From the p0-nominal value

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2665`）

</details>

**1.2.6-14.** Which physical channels are defined in the downlink? [3GPP Release 17]

- A. PDSCH, PUCCH, PHICH
- B. PBCH, PDCCH, PUSCH
- C. PDSCH, PMCH, PBCH
- D. PRACH, PDCCH, PUSCH
- E. PCFICH, PHICH, PBCH

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3055`）

</details>

**1.2.6-15.** Which physical channel carries data from a UE for sidelink communication and V2X sidelink communication? [3GPP Release 17]

- A. PSBCH
- B. PSDCH
- C. PSCCH
- D. PSSCH

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3968`）

</details>

**1.2.6-16.** What is the definition of radio frame?

- A. The mode of the cell, FDD or TDD.
- B. A logical association between single User Equipment and a single UTRAN access point.
- C. The service that the access stratum provides to the non-access stratum for transfer of user data between User Equipment and CN.
- D. A radio frame is a numbered time interval of 10 ms used for data transmission on the radio physical channel.
- E. Two or more CN operators sharing the same RAN.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4543`）

</details>

**1.2.6-17.** Which of the following physical channels carries information originating from higher layers? [3GPP Release 17]

- A. Physical Sidelink Control Channel (PSCCH)
- B. Physical Sidelink Broadcast Channel (PSBCH)
- C. Physical Sidelink Feedback Channel (PSFCH)
- D. Demodulation reference signals (DM-RS)
- E. Sidelink primary synchronization signal (S-PSS)

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4786`）

</details>

**1.2.6-18.** What is a Dedicated Channel?

- A. A channel dedicated to a specific application.
- B. A channel dedicated to a specific RAN.
- C. A channel dedicated to a specific network operator.
- D. A channel dedicated to a specific UE.
- E. A channel dedicated to a specific domain.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4994`）

</details>

**1.2.6-19.** What are the possible classifications of OFDM symbols in a slot in a downlink frame? [3GPP Release 17]

- A. 'downlink', 'flexible', or 'uplink'
- B. 'downlink' or 'flexible' symbols
- C. 'uplink' or 'flexible' symbols
- D. 'downlink' or 'uplink' symbols

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5541`）

</details>

**1.2.6-20.** Which channel is used by M2M (machine-to-machine) devices for initial network entry and demanding system resources?

- A. Physical Downlink Shared Channel (PDSCH)
- B. Physical Uplink Control Channel (PUCCH)
- C. Physical Uplink Shared Channel (PUSCH)
- D. Physical Random Access Channel (PRACH)

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5597`）

</details>

**1.2.6-21.** What does the abbreviation 'SSS' stand for?

- A. Energy per resource element
- B. Channel busy ratio
- C. Timing advance
- D. Scheduling request
- E. Secondary synchronization signal

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5753`）

</details>

**1.2.6-22.** Which physical channel carries the uplink scheduling grant and the sidelink scheduling grant? [3GPP Release 17]

- A. PHICH
- B. EPDCCH
- C. MPDCCH
- D. PDCCH

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5827`）

</details>

**1.2.6-23.** What is the primary cell (PCell) in the context of RRC? [3GPP Release 18]

- A. The cell that broadcasts the MIB
- B. The cell that provides the security input
- C. The cell that handles emergency calls
- D. The cell that provides the NAS mobility information
- E. The cell that handles multicast/broadcast data

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6135`）

</details>

**1.2.6-24.** What does CA stand for?

- A. Connection Assurance
- B. Channel Allocation
- C. Circuit Analysis
- D. Cellular Architecture
- E. Carrier Aggregation

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6401`）

</details>

**1.2.6-25.** What does a '0' value for a bit of the bitmap, provided by dormancyGroupWithinActiveTime, indicate? [3GPP Release 17]

- A. A current active DL BWP for the UE.
- B. A dormant DL BWP for the UE.
- C. An active DL BWP for the UE.
- D. A firstWithinActiveTimeBWP-Id for the UE.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6450`）

</details>

**1.2.6-26.** What does UL SPS (uplink Semi-Persistent Scheduling) repetition allow in LTE? [3GPP Release 18]

- A. Repetition of DL transport blocks with the same PDSCH HARQ process
- B. Repetition of UL transport blocks with the same PUSCH HARQ process
- C. Repetition of UL control information with the same PRACH HARQ process
- D. Repetition of UL data packets with the same PCCH HARQ process

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7223`）

</details>

**1.2.6-27.** What is the purpose of the additional RS provided by gNB? [3GPP Release 16]

- A. Perform fine synchronization
- B. Assist channel/beam tracking
- C. Support CSI/RRM measurements
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7769`）

</details>

**1.2.6-28.** What action is necessary to get access to services in Idle mode? [3GPP Release 17]

- A. Camping on a cell
- B. Performing location registration
- C. Performing CN type selection
- D. Performing RNA update
- E. All of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-48`）

</details>

**1.2.6-29.** What does a UE determine when selecting a power for an S-SS/PSBCH block transmission occasion? [3GPP Release 17]

- A. Value of dl-P0-PSBCH-r16
- B. Value of dl-Alpha-PSBCH
- C. Number of resource blocks for a S-SS/PSBCH block transmission
- D. Value of dl-P0-PSBCH-r17
- E. Value of dl-P0-PSBCH-r16 if provided, else dl-Alpha-PSBCH

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-97`）

</details>

**1.2.6-30.** What is the purpose of grant-free access in UL (uplink) transmission?

- A. To improve reliability
- B. To reserve dedicated bandwidth for each UE
- C. To avoid high collision probability
- D. To improve resource utilization efficiency
- E. To reduce access delay

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-105`）

</details>

**1.2.6-31.** What does the RRC protocol offer to upper layers? [3GPP Release 17]

- A. Broadcast of common control information
- B. Notification of UEs in RRC_IDLE
- C. Transfer of dedicated signalling
- D. Broadcast of positioning assistance data
- E. Transfer of application layer measurement configuration and reporting

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-150`）

</details>

**1.2.6-32.** What is the purpose of the dedicated preambles in the RRC (radio resource control) connection process?

- A. To indicate the user identity and intended traffic class
- B. To allocate radio resources for UL transmissions
- C. To improve the channel estimation quality
- D. To optimize the scheduling process
- E. To perform fast-grant multiple access

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-184`）

</details>

**1.2.6-33.** What level of synchronization is required for uplink transmissions in cellular systems?

- A. Synchronization at the level of chips
- B. Synchronization at the level of OFDM symbols
- C. Synchronization at the level of sub-carriers
- D. Synchronization at the level of frames

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-197`）

</details>

**1.2.6-34.** What channel carries the MulteFire system information broadcast (SIB-MulteFire)?

- A. MulteFire Primary Synchronization Signal (MF-PSS)
- B. MulteFire Secondary Synchronization Signal (MF-SSS)
- C. Cell-specific reference signals (CRS)
- D. Physical Downlink Shared Channel (PDSCH)

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-230`）

</details>

**1.2.6-35.** Which solutions in LTE support configurable reliability and latency combinations? [3GPP Release 18]

- A. Semi-static CFI configuration and PDSCH repetition
- B. UL SPS repetition and PDCP packet duplication
- C. Granular time reference provision and PDCP packet duplication
- D. PDSCH repetition and Granular time reference provision

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-368`）

</details>

**1.2.6-36.** Which RRC state is the UE in when no RRC connection is established? [3GPP Release 17]

- A. RRC_UNAVAILABLE
- B. RRC_INACTIVE
- C. RRC_CONNECTED
- D. RRC_DISCONNECTED
- E. RRC_IDLE

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-444`）

</details>

**1.2.6-37.** Which physical channel informs the UE and the RN about the number of OFDM symbols used for the PDCCHs? [3GPP Release 17]

- A. PBCH
- B. PCFICH
- C. PDSCH
- D. PHICH

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-555`）

</details>

**1.2.6-38.** What is the definition of a traffic channel?

- A. A service that connects to telecommunication networks
- B. Ports intended to be connected to telecommunication networks
- C. A type of telecommunication service that provides complete communication capability
- D. A set of transport blocks exchanged between L1 and 
- E. A logical channel that carries user information

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-579`）

</details>

**1.2.6-39.** Which transmission mode in SL (Sidelink) RLC (Radio Link Control) is used for the groupcast and broadcast services in NR SL?

- A. Transparent Mode (TM)
- B. Unacknowledged Mode (UM)
- C. Acknowledged Mode (AM)
- D. Hybrid Automatic Repeat reQuest (HARQ)

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-727`）

</details>

**1.2.6-40.** What functionalities does the RRC sublayer provide for sidelink communication? [3GPP Release 18]

- A. Configuration of sidelink resource allocation
- B. Reporting of UE sidelink information
- C. Measurement configuration and reporting related to sidelink
- D. Reporting of UE assistance information for SL traffic pattern(s)
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-854`）

</details>

**1.2.6-41.** Why are odd but not prime numbers chosen for the length of ZC (Zadoff Chu) sequences?

- A. To achieve better auto and crosscorrelations under fractional timing and frequency offsets
- B. To reduce computational complexity at the UE
- C. To achieve better synchronization between the UE and the BS
- D. To allow multiple UEs to send control information at the same time and frequency
- E. To achieve better robustness to collisions in the random access channel

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-861`）

</details>

**1.2.6-42.** What is the purpose of Msg4 in the PRACH (Physical Random Access Channel) procedure?

- A. Uplink timing synchronization
- B. Transmitting a meaningful uplink message
- C. Contention resolution
- D. Resource allocation

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-892`）

</details>

**1.2.6-43.** How can channel feedback delay be reduced?

- A. By having shorter time slots and feeding back more often
- B. By increasing the transmit power
- C. By reducing the number of users
- D. By decreasing the channel fluctuations
- E. None of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-894`）

</details>

**1.2.6-44.** What does the Timing Delta MAC CE indicate to an IAB-node? [3GPP Release 17]

- A. Time difference between DU transmission and IAB-MT reception
- B. Time difference between IAB-MT reception and transmission
- C. Timing advance offset value for a serving cell
- D. Timing Case Indication for a serving cell

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-910`）

</details>

**1.2.6-45.** What is the key functionality introduced for prioritization between overlapping uplink resources of one UE in the 5G Core network? [3GPP Release 16]

- A. Support for up to eight simultaneously active semi-persistent scheduling (SPS) configurations
- B. Support for accurate reference timing delivery
- C. Support for prioritization between overlapping uplink resources of one UE
- D. Support for multiple active configured grant configurations for a BWP
- E. Support for PDCP packet duplication enhancements

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-927`）

</details>

**1.2.6-46.** What are the two main groups of logical channels in the MAC sublayer? [3GPP Release 17]

- A. Broadcast channels and Dedicated channels
- B. Control channels and Traffic channels
- C. Physical channels and Transport channels
- D. Scheduling channels and Error correction channels
- E. Primary channels and Secondary channels

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1023`）

</details>

**1.2.6-47.** Which state is the UE expected to receive the DL PRS for RTT-based propagation delay compensation in? [3GPP Release 17]

- A. RRC_IDLE state
- B. RRC_CONNECTED state
- C. RRC_INACTIVE state
- D. RRC_RELEASED state
- E. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1066`）

</details>

**1.2.6-48.** Where can the UE receive PLMN identity and CN type information in a given cell? [3GPP Release 17]

- A. Data channel
- B. Access channel
- C. Control channel
- D. Broadcast channel
- E. Paging channel

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1074`）

</details>

**1.2.6-49.** How are the metrics related to the provided thresholds evaluated for WLAN BSS? [3GPP Release 17]

- A. The UE evaluates all metrics related to the provided thresholds.
- B. The UE excludes the WLAN BSS if not all metrics related to the provided thresholds can be acquired.
- C. The WLAN BSS is excluded if the UE cannot evaluate the provided thresholds.
- D. The UE considers the metrics with unprovided thresholds as zero.
- E. The UE considers the metrics with unprovided thresholds as infinite.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1095`）

</details>

**1.2.6-50.** What is the purpose of the power headroom reports (PHR)? [3GPP Release 18]

- A. To provide support for power-aware packet scheduling
- B. To allocate resources for the initial HARQ transmissions to UEs
- C. To enable coordination of TDM and FDM cell resources between MAC in the gNB and the corresponding entity in the ng-eNB
- D. To enable fast SCell activation when CA is configured
- E. To provide support for QoS-aware packet scheduling

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1098`）

</details>

**1.2.6-51.** What does the UE ignore regarding cell access restrictions for cell reselection when camping on E-UTRA connected to 5GC? [3GPP Release 17]

- A. Access Class or ACDC category restrictions
- B. Access Category and Identity restrictions
- C. Emergency call restrictions
- D. Cell status restrictions
- E. Access restrictions for NAS initiated access attempts

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1200`）

</details>

**1.2.6-52.** What does the abbreviation 'UL-SCH' stand for?

- A. Uplink control information
- B. Uplink shared channel
- C. Reference signal received power
- D. Quasi co-location
- E. Timing advance

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1217`）

</details>

**1.2.6-53.** When does the UE monitor DCP on the active BWP? [3GPP Release 18]

- A. During active-time and BWP switching
- B. During measurement gaps and CFRA preamble transmission
- C. During PUSCH transmission and MIMO layers
- D. At a configured offset before the on-duration

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1256`）

</details>

**1.2.6-54.** What happens if the SDT procedure is unsuccessful? [3GPP Release 18]

- A. The UE transitions to RRC_INACTIVE state.
- B. The UE transitions to RRC_CONNECTED state.
- C. The UE transitions to RRC_RELEASE state.
- D. The UE transitions to RRC_SUSPEND state.
- E. The UE transitions to RRC_IDLE state.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1311`）

</details>

**1.2.6-55.** What are the main services and functions of the PDCP sublayer? [3GPP Release 17]

- A. Header compression and decompression, ciphering and deciphering, and timer-based SDU discard
- B. Transfer of upper layer PDUs, error correction through ARQ, and reassembly of SDUs
- C. Mapping between logical channels and transport channels, error correction through HARQ, and priority handling
- D. Marking QoS flow ID in packets, mapping between QoS flows and data radio bearers, and transfer of data
- E. Multiplexing/demultiplexing of MAC SDUs, scheduling information reporting, and priority handling

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1312`）

</details>

**1.2.6-56.** When does the NG-RAN node initiate Unified Access Control? [3GPP Release 18]

- A. When AMFs request load restriction
- B. When OAM requests access control
- C. When NG-RAN receives overload start messages
- D. When UE indicates extended access barring
- E. When NG-RAN is under lawful interception

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1411`）

</details>

**1.2.6-57.** Which message is generated by the gNB-CU to transition the UE from RRC connected to RRC inactive? [3GPP Release 17]

- A. PAGING message
- B. RRCResumeRequest message
- C. RRCRelease message
- D. UE CONTEXT RELEASE COMMAND message

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1425`）

</details>

**1.2.6-58.** What does SDAP stand for?

- A. Sidelink Dynamic Adaptation Protocol
- B. Sidelink Data Adaptation Protocol
- C. Service Dynamic Adaptation Protocol
- D. Service Data Adaptation Protocol

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1472`）

</details>

**1.2.6-59.** What is the purpose of the Small Data Transmission (SDT) feature in NR? [3GPP Release 17]

- A. To enable data transmission in the INACTIVE state for UEs with periodic data packets
- B. To enable data transmission in the RRC_CONNECTED state for UEs with small data packets
- C. To enable data transmission in the RRC_INACTIVE state for UEs with frequent data traffic
- D. To enable data transmission in the RRC_INACTIVE state for UEs with infrequent data traffic

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1584`）

</details>

**1.2.6-60.** How are QoS flows mapped to DRBs in the uplink? [3GPP Release 18]

- A. Reflective mapping
- B. Explicit configuration
- C. Both reflective mapping and explicit configuration
- D. Random mapping

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1595`）

</details>

**1.2.6-61.** Which identity is used for UE identification temporarily used for scheduling during the random access procedure? [3GPP Release 17]

- A. CI-RNTI
- B. RA-RNTI
- C. Temporary C-RNTI
- D. Random value for contention resolution
- E. I-RNTI

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1601`）

</details>

**1.2.6-62.** What is a Paging Occasion (PO)? [3GPP Release 17]

- A. A subframe where RRC_IDLE state is entered
- B. A subframe where the paging message is transmitted
- C. A subframe where DRX is used
- D. A subframe where RRC_INACTIVE state is entered
- E. A subframe where P-RNTI is transmitted

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1631`）

</details>

**1.2.6-63.** What is the formula to determine the Paging Frame (PF)? [3GPP Release 17]

- A. SFN mod T= (T div N)*(UE_ID mod W)
- B. SFN mod T= (T div N)*(UE_ID_H mod N)
- C. SFN mod T= (T div N)*(UE_ID_H mod TeDRX,H)
- D. SFN mod T= (T div N)*(UE_ID mod TeDRX,H)
- E. SFN mod T= (T div N)*(UE_ID mod N)

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1664`）

</details>

**1.2.6-64.** What is the purpose of recoverySearchSpaceId? [3GPP Release 17]

- A. To provide a configuration for PRACH transmission.
- B. To monitor PDCCH for detection of a DCI format.
- C. To indicate the presence of SSB-MTCAdditionalPCI.
- D. To link a search space set for monitoring PDCCH in a CORESET.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1732`）

</details>

**1.2.6-65.** What does a '0' value for the Wake-up indication bit, when reported to higher layers, indicate? [3GPP Release 17]

- A. To start the drx-onDurationTimer for the next long DRX cycle.
- B. To not start the drx-onDurationTimer for the next long DRX cycle.
- C. To activate the dormantBWP-Id for the UE.
- D. To activate the firstOutsideActiveTimeBWP-Id for the UE.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1746`）

</details>

**1.2.6-66.** Which identity is used for Semi-Persistent Scheduling in the downlink or configured grant in the uplink? [3GPP Release 17]

- A. C-RNTI
- B. CI-RNTI
- C. CS-RNTI
- D. INT-RNTI
- E. P-RNTI

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1799`）

</details>

**1.2.6-67.** How is the SCG of the UE suspended in RRC_INACTIVE state? [3GPP Release 17]

- A. The CU of SN sends the UE CONTEXT RELEASE COMMAND
- B. The CU of SN sends the UE CONTEXT MODIFICATION RESPONSE
- C. The DU of SN sends the UE CONTEXT MODIFICATION RESPONSE
- D. The CU of SN sends the UE CONTEXT MODIFICATION REQUEST
- E. The DU of SN sends the UE CONTEXT MODIFICATION REQUEST

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1863`）

</details>

**1.2.6-68.** What is one enhancement required for realizing packet duplication in CA (carrier aggregation)?

- A. Reusing existing CA procedures
- B. Visibility of logical channel-component carrier association
- C. Association of logical channels with uplink grants
- D. MAC layer prioritization

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1906`）

</details>

**1.2.6-69.** Which feature in Rel-16 allows transmission of uplink data payload using preconfigured uplink resources? [3GPP Release 16]

- A. UE-group wake-up signals (GWUS)
- B. Mobile-terminated early data transmission (MT-EDT)
- C. Support for Preconfigured uplink resources (PUR) in idle mode
- D. Scheduling of multiple DL/UL transport blocks with single DCI
- E. Presence of NRS on a non-anchor carrier for paging

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1977`）

</details>

**1.2.6-70.** What does the UE do if it receives an RRC message on DCCH or CCCH that does not include a mandatory field? [3GPP Release 17]

- A. Ignore the message
- B. Treat the list as if the entry including the missing or not comprehended field was absent
- C. Consider the 'parent' field to be set to a not comprehended value
- D. Apply the generic error handling to the subsequent 'parent' field(s)

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1993`）

</details>

**1.2.6-71.** Which protocol sublayer is responsible for maintaining the PDCP sequence numbers? [3GPP Release 18]

- A. MAC sublayer
- B. RLC sublayer
- C. PDCP sublayer
- D. SDAP sublayer

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2053`）

</details>

**1.2.6-72.** What problem can occur with the current paging procedures in 5G networks? [3GPP Release 17]

- A. Handover failures
- B. Coverage holes
- C. Low UE throughput
- D. Repeated paging attempts
- E. Insufficient transmission power

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2054`）

</details>

**1.2.6-73.** What is TRS used for in TRS occasions? [3GPP Release 17]

- A. To configure DRX parameters
- B. To trigger PDCCH monitoring
- C. To enable cross-slot scheduling
- D. To track UE paging occasions
- E. To indicate L1 availability

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2065`）

</details>

**1.2.6-74.** Which layer supports Frequency Division Duplex (FDD) and Time Division Duplex (TDD)?

- A. Radio Link Control (RLC) Layer
- B. Medium Access Control (MAC) Layer
- C. Physical (PHY) Layer
- D. Packet Data Convergence Protocol (PDCP) Layer
- E. Radio Resource Control (RRC) Layer

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2093`）

</details>

**1.2.6-75.** What does the feature Scheduling of multiple DL/UL transport blocks with single DCI allow? [3GPP Release 16]

- A. Scheduling of multiple transport blocks in uplink
- B. Scheduling of multiple transport blocks in downlink
- C. HARQ bundling for uplink transmission
- D. Reduced DCI overhead for contiguous UL/DL transmissions
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2096`）

</details>

**1.2.6-76.** What is the purpose of paging in mobile networks?

- A. To track service and resource usage levels
- B. To transmit data as discrete units
- C. To seek a User Equipment
- D. To reduce power consumption
- E. To provide feedback on network reliability

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2116`）

</details>

**1.2.6-77.** What control mechanism allows/prevents UEs from accessing the network based on their capabilities? [3GPP Release 18]

- A. Access Class Barring
- B. Service Specific Access Control
- C. Control of UE Capabilities
- D. Extended Access Barring
- E. Application Specific Congestion Control for Data Communication

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2118`）

</details>

**1.2.6-78.** What are the functionalities implemented in the PHYsical (PHY), Medium Access Control (MAC), Radio Link Control (RLC), and Packet Data Control Protocol (PDCP) layers of an eNB (eNodeB)?

- A. User-plane header-compression and encryption
- B. Control-plane protocol terminations towards the user equipment (UE)
- C. Network congestion management
- D. Power consumption management
- E. All of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2138`）

</details>

**1.2.6-79.** What actions can a UE take based on the recommended bitrate from the eNB? [3GPP Release 14]

- A. Perform CSFB
- B. Perform SRVCC
- C. Perform HARQ
- D. Perform MU-MIMO
- E. Initiate an end-to-end rate adaptation with the peer UE

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2146`）

</details>

**1.2.6-80.** When is a default DRB used? [3GPP Release 18]

- A. When there is congestion in the network
- B. When there is no matching mapping rule for an incoming UL packet
- C. When there is an RRC configured mapping rule
- D. When there is a reflective mapping rule

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2178`）

</details>

**1.2.6-81.** How do schedulers assign resources between UEs in MAC in gNB? [3GPP Release 17]

- A. Based on radio conditions reported by the UE
- B. Based on the maximum transmit power of the UE
- C. Based on the UE buffer status and QoS requirements
- D. Based on the UE's location in the network

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2181`）

</details>

**1.2.6-82.** What is the purpose of code block group (CBG)-based transmissions in 5G NR?

- A. To increase the number of code blocks in a transport block
- B. To reduce the size of transport blocks for XR cases
- C. To provide HARQ acknowledgment (ACK) or negative-acknowledgment (NACK) bits per CBG
- D. To align with the transmission of huge payloads such as XR cases
- E. To improve the resource efficiency in HARQ retransmissions

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2287`）

</details>

**1.2.6-83.** What is the purpose of the prohibit timer in the network? [3GPP Release 14]

- A. To trigger SR counters
- B. To perform rate adaptation
- C. To limit frequent query messages
- D. To enable CSFB
- E. To configure bundle frequency hopping

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2294`）

</details>

**1.2.6-84.** How do non-supporting UEs handle the broadcast system information in a shared network? [3GPP Release 17]

- A. They rely on the SIM/USIM card for information.
- B. They decode the broadcast system information to determine available operators.
- C. They request the broadcast system information from the RAN.
- D. They ignore the broadcast system information.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2339`）

</details>

**1.2.6-85.** When does a UE start and stop PDCCH monitoring according to search space sets with different group indexes? [3GPP Release 17]

- A. At the beginning of a slot after the last symbol of a PDCCH reception
- B. At the beginning of a slot after a PUCCH transmission
- C. At the beginning of a slot following timer expiration
- D. At the beginning of a slot after a PDCCH skipping duration expires
- E. At the beginning of a slot after a PDCCH reception providing the DCI format with the PDCCH monitoring adaptation field

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2443`）

</details>

**1.2.6-86.** What does BA configuration in the UE mean? [3GPP Release 18]

- A. The UE has to monitor PDCCH on the entire DL frequency of the cell
- B. The UE does not have to monitor PDCCH on the entire DL frequency of the cell
- C. The UE has to monitor PDCCH on dedicated SSSG
- D. The UE has to monitor PDCCH continuously

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2483`）

</details>

**1.2.6-87.** What is the definition of a Coded Composite Transport Channel?

- A. A data stream resulting from encoding and multiplexing of one or several transport channels
- B. A channel not dedicated to a specific UE
- C. A logical channel that carries system control information
- D. A modulation and coding method intended for transmission of text in voice channels
- E. The combined losses of all transmission system components between the transmitter output and the antenna input

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2505`）

</details>

**1.2.6-88.** What is the purpose of Ethernet Header Compression (EHC) in the support of NR Industrial Internet of Things? [3GPP Release 16]

- A. To increase efficiency of Ethernet frames transmission over the NR air interface
- B. To provide redundancy over N3 tunnel between UPF and NG-RAN on a per QoS flow basis
- C. To support strict synchronization accuracy requirements of Time Sensitive Communications
- D. To maximize the reliability of transmission over the air interface
- E. To optimize handling of a mixture of URLLC and eMBB traffic

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2565`）

</details>

**1.2.6-89.** Which feature enhances the granularity of RSTD reporting? [3GPP Release 14]

- A. OTDOA enhancements in shared physical cell identity scenario
- B. PRS based Beacon
- C. PRS plus CRS measurement for OTDOA
- D. Multipath Time of Arrival (ToA)
- E. Reduced quantization error

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2608`）

</details>

**1.2.6-90.** How does a UE determine the number of repetitions and MCS for a PUSCH transmission scheduled by a RAR UL grant? [3GPP Release 17]

- A. By the number of RBs in the initial UL BWP
- B. By the SCS for the PUSCH transmission
- C. By the MCS field in the RAR UL grant
- D. By the PUSCH repetition type

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2637`）

</details>

**1.2.6-91.** In which case is the HARQ-ACK message transmitted on PUCCH? [3GPP Release 17]

- A. When the first uplink symbol of the PUCCH starts no earlier than at symbol L1
- B. When the PUCCH resource is overlapping with another PUCCH or PUSCH resource
- C. When the UE is configured with multiple active component carriers
- D. When the PDSCH DM-RS position for the additional DM-RS is 0
- E. When the uplink switching gap is triggered for the PUCCH

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2657`）

</details>

**1.2.6-92.** What does the demodulation enhancement feature in LTE enable the UE to do? [3GPP Release 14]

- A. Increase the number of SFNs that can be handled by the UE
- B. Handle the Doppler shift issue in SFN scenario caused by opposite Doppler shifts associated with separate paths on the UE
- C. Improve the demodulation performance under 350km/h and 30km/h in SFN scenario
- D. Reduce the impact of opposite Doppler shifts on the UE demodulation under high speed
- E. No improvements were made to UE demodulation in LTE

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2735`）

</details>

**1.2.6-93.** What happens when the BWP inactivity timer expires? [3GPP Release 18]

- A. The UE goes back to sleep
- B. The UE switches to the default BWP
- C. The UE starts the inactivity timer
- D. The UE restarts PDCCH decoding

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2747`）

</details>

**1.2.6-94.** What is the purpose of the Wake-up signalling feature in NB-IoT? [3GPP Release 15]

- A. To instruct the UE to regularly check for paging messages
- B. To reduce UE power consumption by allowing the UE to skip paging procedures
- C. To enhance the Rel-13/14 NB-IoT air interface and protocol layers
- D. To support small cells and extensions to NB-IoT standalone operation mode
- E. To increase the accuracy of narrowband measurement

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2748`）

</details>

**1.2.6-95.** Which of the following physical signals are used by the physical layer but do not carry information originating from higher layers? [3GPP Release 17]

- A. Phase-tracking reference signals (PT-RS)
- B. Channel-state information reference signals (CSI-RS)
- C. Demodulation reference signals (DM-RS)
- D. Sidelink primary synchronization signal (S-PSS)
- E. Sidelink secondary synchronization signal (S-SSS)

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2765`）

</details>

**1.2.6-96.** What does CFI stand for? [3GPP Release 15]

- A. Carrier Frequency Indicator
- B. Control Format Indicator
- C. Channel Frame Initialization
- D. Converged Frequency Indicator
- E. Codebook Feedback Indicator

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2807`）

</details>

**1.2.6-97.** What is the purpose of segmentation of RRC messages? [3GPP Release 18]

- A. To support sidelink communication
- B. To improve the reliability of NAS message delivery
- C. To enable inter-frequency handovers
- D. To reduce the size of encoded RRC messages
- E. To allow efficient resource allocation

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2818`）

</details>

**1.2.6-98.** If a location request fails due to barring, what happens? [3GPP Release 17]

- A. The request is postponed
- B. An error cause is returned to the LCS Requestor
- C. A notification is sent to the target UE
- D. The request is cancelled
- E. The request is forwarded to the PLMN operator

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2835`）

</details>

**1.2.6-99.** In an FDD (Frequency Division Duplex) system, how does the transmitter obtain channel state information?

- A. Through channel reciprocity
- B. Through feedback from the receiver
- C. Through channel measurements

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2885`）

</details>

**1.2.6-100.** What release cause is indicated when the UE fails the mobility from NR procedure? [3GPP Release 17]

- A. 'Handover failure'
- B. 'RRC connection release'
- C. 'RRC connection failure'
- D. 'Mobility failure'
- E. 'Other'

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2891`）

</details>

**1.2.6-101.** What does the UE generate as HARQ-ACK information when it correctly decodes a transport block? [3GPP Release 17]

- A. CRC value
- B. NACK value
- C. ACK value
- D. ID value

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2914`）

</details>

**1.2.6-102.** Which identity is used to control the power of SRS? [3GPP Release 17]

- A. SFI-RNTI
- B. TPC-PUCCH-RNTI
- C. TPC-PUSCH-RNTI
- D. TPC-SRS-RNTI
- E. RA-RNTI

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3030`）

</details>

**1.2.6-103.** What does the physical layer interface in the LTE radio interface protocol architecture? [3GPP Release 17]

- A. MAC sub-layer of Layer 2
- B. RLC sub-layer of Layer 2
- C. RRC Layer of Layer 3
- D. PDCCH
- E. PHICH

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3049`）

</details>

**1.2.6-104.** What does a UE configured for operation in bandwidth parts (BWPs) receive from higher layers? [3GPP Release 17]

- A. Frequency domain resource allocation
- B. Scheduling cell information
- C. Parameter configurations for DL and UL BWPs
- D. PDCCH and PDSCH transmissions

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3050`）

</details>

**1.2.6-105.** Which sublayer is responsible for routing and next-hop determination on the backhaul link? [3GPP Release 18]

- A. MAC sublayer
- B. RLC sublayer
- C. PDCP sublayer
- D. BAP sublayer

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3080`）

</details>

**1.2.6-106.** What does the UE do if it is unable to comply with any part of the configuration included in the MobilityFromNRCommand message? [3GPP Release 17]

- A. Revert back to the configuration used in the source PCell
- B. Stop all timers and release radio resources
- C. Initiate the connection re-establishment procedure
- D. Store handover failure information in VarRLF-Report
- E. Attempt to select an E-UTRA cell

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3137`）

</details>

**1.2.6-107.** What is the purpose of the SDAP sublayer in Layer 2? [3GPP Release 17]

- A. Mapping between logical channels and transport channels
- B. Transfer of upper layer PDUs
- C. Transfer of data radio bearers
- D. Marking QoS flow ID in packets
- E. Error correction through ARQ

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3308`）

</details>

**1.2.6-108.** Which SRB is used for RRC messages using the CCCH logical channel? [3GPP Release 17]

- A. SRB0
- B. SRB1
- C. SRB2
- D. SRB3
- E. SRB4

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3370`）

</details>

**1.2.6-109.** Under what conditions does the UE ignore PDCCH skipping? [3GPP Release 17]

- A. When SR is sent and is pending on all serving cells of the Cell Group
- B. During monitoring of the RAR/MsgB window on SpCell
- C. While contention resolution timer is running on SpCell
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3380`）

</details>

**1.2.6-110.** Which PUCCH (physical uplink control channel) format uses supplemental ZC (Zadoff Chu) sequences for control information transmission in LTE?

- A. Format 0
- B. Format 1
- C. Format 2
- D. Format 3
- E. Format 4

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3482`）

</details>

**1.2.6-111.** What is the definition of Paging Block Periodicity?

- A. The act of seeking a User Equipment
- B. The frame where the UE receives actual paging message
- C. The period of the occurrence of Paging Blocks
- D. The frame where the UE monitors in FDD or the paging block, which consists of several frames, for TDD
- E. A network protocol data unit

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3561`）

</details>

**1.2.6-112.** How should the UE handle an error regarding the conditionality of a field in an extension addition group? [3GPP Release 17]

- A. Ignore the extension addition group
- B. Ignore just the field in error
- C. Ignore the entire itemInfo entry
- D. Apply the generic error handling to the subsequent 'parent' field(s)

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3634`）

</details>

**1.2.6-113.** What is the purpose of power headroom reports in MAC in gNB? [3GPP Release 17]

- A. To allocate physical layer resources for downlink and uplink
- B. To measure radio conditions at the gNB
- C. To provide support for power-aware packet scheduling
- D. To configure the parameters of gNB and UE

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3705`）

</details>

**1.2.6-114.** How many times can the DL (Downlink) PRS (Positioning Reference Signal) resources be repeated within a resource set period?

- A. 32 times
- B. 16 times
- C. 8 times
- D. 4 times

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3712`）

</details>

**1.2.6-115.** Which identity is used for indicating an alternative MCS table for PDSCH and PUSCH? [3GPP Release 17]

- A. C-RNTI
- B. CI-RNTI
- C. CS-RNTI
- D. MCS-C-RNTI
- E. P-RNTI

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3733`）

</details>

**1.2.6-116.** What does a UE monitor for detection of DCI format 0_0 or DCI format 1_0 with CRC scrambled by C-RNTI for scheduling respective PUSCH transmissions or PDSCH receptions? [3GPP Release 17]

- A. PDCCH according to Type1-PDCCH CSS set
- B. PRACH with SS/PBCH block index associated with the PUSCH transmission
- C. SS/PBCH block with the same index as the PRACH transmission
- D. PDCCH according to sdt-SearchSpace CSS set
- E. PDCCH according to the same CSS set as for PRACH transmission

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3826`）

</details>

**1.2.6-117.** Which transmission mode does the RLC sublayer use for SRB0, paging, and broadcast system information? [3GPP Release 18]

- A. Transparent Mode (TM)
- B. Unacknowledged Mode (UM)
- C. Acknowledged Mode (AM)
- D. All of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3832`）

</details>

**1.2.6-118.** Which identity is used for identification of Broadcast and System Information in the downlink? [3GPP Release 17]

- A. C-RNTI
- B. CI-RNTI
- C. CS-RNTI
- D. SI-RNTI
- E. P-RNTI

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3870`）

</details>

**1.2.6-119.** Which layer introduces the scalable Orthogonal Frequency Division Multiplexing (OFDM) numerology?

- A. Packet Data Convergence Protocol (PDCP) Layer
- B. Medium Access Control (MAC) Layer
- C. Radio Link Control (RLC) Layer
- D. Physical (PHY) Layer
- E. Radio Resource Control (RRC) Layer

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3903`）

</details>

**1.2.6-120.** When is the SDT procedure initiated? [3GPP Release 18]

- A. When the network sends an RRCReject message.
- B. When the DL RSRP is below a configured threshold.
- C. When there is no valid SDT resource available.
- D. When the UE is in RRC_CONNECTED state.
- E. When there is a configured amount of UL data awaiting transmission across all radio bearers for which SDT is enabled.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-3913`）

</details>

**1.2.6-121.** Which of the following is NOT supported by PDCP packet duplication? [3GPP Release 15]

- A. Signalling Radio Bearers (SRBs) using RLC AM
- B. Data Radio Bearers (DRBs) using RLC UM
- C. Data Radio Bearers (DRBs) using RLC AM
- D. Carrier Aggregation (CA) scenarios
- E. Dual Connectivity (DC) scenarios

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3921`）

</details>

**1.2.6-122.** When should a UE adjust the contention window size and the backoff counter for Type 1 channel access procedures? [3GPP Release 17]

- A. After sensing the channel to be busy
- B. After receiving an UL grant or an AUL-DFI with DCI format 0A
- C. After receiving an UL grant or an AUL-DFI with DCI format 1A
- D. After transmitting a PUCCH transmission
- E. After transmitting a PUSCH transmission

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3945`）

</details>

**1.2.6-123.** Which layer is responsible for managing QoS (Quality of Service) when connected to the 5GC (5G Core Network)?

- A. Physical (PHY) Layer
- B. Medium Access Control (MAC) Layer
- C. Service Data Adaptation Protocol (SDAP) Layer
- D. Radio Link Control (RLC) Layer
- E. Packet Data Convergence Protocol (PDCP) Layer

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3959`）

</details>

**1.2.6-124.** Which layer handles the mapping of a logical channel onto certain numerology/TTI?

- A. Physical (PHY) Layer
- B. Medium Access Control (MAC) Layer
- C. Radio Link Control (RLC) Layer
- D. Packet Data Convergence Protocol (PDCP) Layer
- E. Radio Resource Control (RRC) Layer

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4008`）

</details>

**1.2.6-125.** What is the challenge posed by packet duplication in the RLC (radio link control) layer?

- A. Unequal successful transmission in different legs
- B. Redundant retransmission and wastage of resources
- C. Interference with data split in DC
- D. Complexity of UE implementation

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4082`）

</details>

**1.2.6-126.** What message does the UE respond with after receiving the RRCSetup message? [3GPP Release 17]

- A. RRC_CONNECTION_SETUP_COMPLETE
- B. SecurityModeCommand
- C. SecurityModeComplete
- D. RRCReconfiguration
- E. UE CONTEXT SETUP RESPONSE

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4097`）

</details>

**1.2.6-127.** What is the main service and function of the SDAP sublayer? [3GPP Release 18]

- A. Mapping between logical channels and transport channels
- B. Error correction through HARQ
- C. Compression and decompression of headers
- D. Mapping between a QoS flow and a data radio bearer

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4139`）

</details>

**1.2.6-128.** What does CFI stand for in the context of LTE_HRLLC? [3GPP Release 18]

- A. Controlled Format Indicator
- B. Controlled Frequency Indicator
- C. Control Format Indicator
- D. Control Frequency Indicator

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4190`）

</details>

**1.2.6-129.** What are the three factors that govern the PDCCH monitoring activity of the UE in RRC connected mode? [3GPP Release 18]

- A. DRX, BA, and DCP
- B. RRC_IDLE, RRC_INACTIVE, and RRM
- C. MIMO, PUSCH, and CSI-RS
- D. SSSG, BWP, and TRS

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4291`）

</details>

**1.2.6-130.** How is the recommended bitrate conveyed from the eNB to the UE? [3GPP Release 14]

- A. Via RRC signaling
- B. Through SR counters
- C. Using a MAC Control Element (CE)
- D. By direct modulation
- E. Via S1 interface

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4417`）

</details>

**1.2.6-131.** Which layer of NR is split into sublayers such as MAC, RLC, PDCP, and SDAP? [3GPP Release 17]

- A. Layer 1
- B. Layer 2
- C. Layer 3
- D. Layer 4
- E. Layer 5

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4506`）

</details>

頁次：[1](1-2-gsma-1.md)　**2**　[3](1-2-gsma-3.md)　[4](1-2-gsma-4.md)　[5](1-2-gsma-5.md)　[6](1-2-gsma-6.md)　[7](1-2-gsma-7.md)
