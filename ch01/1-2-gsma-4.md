# 1.2 通訊協定　GSMA 練習題（1231 題）（第 4／7 頁）

所屬：[1.2 通訊協定](1-2.md)

只收 GSMA 訓練題；不含驗證集與測試集，並已去除和驗證／測試題相同或相似、重複、標註衝突的題目。題目依小節歸類（抽查正確率約 95%）。

頁次：[1](1-2-gsma-1.md)　[2](1-2-gsma-2.md)　[3](1-2-gsma-3.md)　**4**　[5](1-2-gsma-5.md)　[6](1-2-gsma-6.md)　[7](1-2-gsma-7.md)

## 1.2.7 核心網信令：NAS、NGAP、GTP、Diameter、SBI（75 題）（續）

**1.2.7-54.** In which state should the UE be for the NG-RAN to send a Location Report including the UE's last known location with timestamp? [3GPP Release 18]

- A. UE state does not matter for this type of Location Report
- B. CM-CONNECTED with RRC_CONNECTED state
- C. CM-IDLE state
- D. CM-DISCONNECTED state
- E. CM-CONNECTED with RRC_INACTIVE state

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6824`）

</details>

**1.2.7-55.** What message is sent by the MS to the network in order to perform a GPRS or combined GPRS attach? [3GPP Release 18]

- A. Attach reject
- B. Attach accept
- C. Attach complete
- D. Attach request

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6902`）

</details>

**1.2.7-56.** What guides the target PLMN selection for a UE when its registered PLMN is not available in the target cell? [3GPP Release 17]

- A. SNA Access Information IE
- B. Equivalent PLMNs list
- C. Handover restriction list
- D. Common PLMN-id broadcast
- E. IMSI

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6920`）

</details>

**1.2.7-57.** What are the requirements for network and system selection for multi-mode terminals with 3GPP capability? [3GPP Release 18]

- A. To comply with 3GPP specifications and ensure fair competition environment
- B. To prioritize network selection based on system capabilities
- C. To minimize the impact on 3GPP protocol requirements
- D. To include network priority mechanisms
- E. To support ping-pong between systems

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6954`）

</details>

**1.2.7-58.** What type of messages may be fragmented in the control plane for untrusted non-3GPP access? [3GPP Release 18]

- A. Identity messages
- B. Handover messages
- C. NAS-MM messages
- D. EAP messages
- E. Large NAS messages

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6966`）

</details>

**1.2.7-59.** When does a UE initiate reselection and registration on an alternative available PLMN? [3GPP Release 18]

- A. At switch-on or recovery from lack of coverage
- B. After a successful registration on a PLMN
- C. When a permanent PLMN restriction is detected
- D. When a partial or temporary PLMN restriction is detected
- E. After periodic network selection attempts

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7356`）

</details>

**1.2.7-60.** What is the role of NAS-MM in the control plane between the UE and the AMF? [3GPP Release 18]

- A. Handles Registration Management and Connection Management state machines and procedures with the UE
- B. Provides a secure NAS signalling connection between the UE and the AMF
- C. Decides whether to accept the RM/CM part of N1 signalling without considering non NAS-MM messages
- D. Routes NAS messages to other network functions
- E. Transmits other types of NAS messages together with an RM/CM NAS message

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7797`）

</details>

**1.2.7-61.** What is the behavior of a mobile station in state GMM-REGISTERED with substate NORMAL-SERVICE? [3GPP Release 18]

- A. Not perform cell selection/reselection
- B. Not send any user data
- C. Not initiate normal routing area updating
- D. Not respond to paging
- E. Not transmit any signalling information

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7899`）

</details>

**1.2.7-62.** What is the purpose of the Last Active USIM? [3GPP Release 18]

- A. To provide security features
- B. To store provisioning parameters
- C. To automatically select the active USIM on switch on
- D. To access the IMS services
- E. To update USIM-specific information via the radio interface

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1486`）

</details>

**1.2.7-63.** What is the purpose of the Network notification objective introduced by MUSIM for LTE/NR? [3GPP Release 17]

- A. To address the paging occasion collision issue.
- B. To notify the network of a switch from one network to another for MUSIM purpose.
- C. To support indicating to the MUSIM UE whether an incoming paging is for voice service.
- D. To notify the network of a switch from network A for MUSIM purpose.
- E. To address the issue of network congestion during paging.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3866`）

</details>

**1.2.7-64.** What are the three levels of services defined for a UE in Idle mode? [3GPP Release 17]

- A. Limited service, normal service, and operator service
- B. Emergency service, normal service, and reserved service
- C. Basic service, advanced service, and premium service
- D. Public service, private service, and operator service

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4695`）

</details>

**1.2.7-65.** What does the Paging Cause Indication feature in a Multi-USIM UE and network support? [3GPP Release 18]

- A. Paging for voice service
- B. Paging for data service
- C. Connection release
- D. Paging restriction
- E. All of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6714`）

</details>

**1.2.7-66.** How can the UE indicate its capability to receive Network Exposure information? [3GPP Release 18]

- A. By sending a specific message to the AMF
- B. During the PDU Session Establishment procedure
- C. During the registration procedure
- D. By updating the UDM subscription record
- E. By configuring the AF endpoint counterpart

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6990`）

</details>

**1.2.7-67.** For a prioritized service, will the UE automatically override user and network disallowed RATs if there are no PLMNs on the allowed radio technologies that the UE can access? [3GPP Release 18]

- A. Yes
- B. No

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7643`）

</details>

**1.2.7-68.** What is the purpose of the Diameter Load Control Mechanism? [3GPP Release 14]

- A. To provide dynamic load balancing in Diameter nodes
- B. To prevent overload in Diameter nodes
- C. To convey load information between Diameter nodes
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6584`）

</details>

**1.2.7-69.** Which of the following protocols is NOT used in the 5G Core or Core emulator to support user equipment (UE) communication?

- A. NGAP
- B. HTTP2
- C. PFCP
- D. F1AP

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-203`）

</details>

**1.2.7-70.** What HTTP header field is used to indicate the media type of the associated representation in a response message?

- A. Content-Type
- B. Content-Length
- C. Location
- D. Content-Encoding

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-607`）

</details>

**1.2.7-71.** In the context of Open Radio Access Networks (O-RAN), what does the term "De-registration procedure" refer to?

- A. The process of a User Equipment (UE) disconnecting from the network.
- B. The process of configuring a new O-RAN cell.
- C. The process of updating the network's software.
- D. The process of verifying the performance of an O-RAN cell.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-819`）

</details>

**1.2.7-72.** What is the name of the message that contains information about the cause of a failure in an O-RAN system?

- A. A1PolicyId
- B. Cause
- C. Result
- D. TransportLayerCause

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1178`）

</details>

**1.2.7-73.** What does the Operator controlled signal threshold per access technology specify for network selection? [3GPP Release 18]

- A. The number of PLMNs to be selected
- B. The order in which PLMNs are selected
- C. The priority of different access technologies
- D. The signal quality required for a PLMN to be selected
- E. The coverage area of a PLMN

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6319`）

</details>

**1.2.7-74.** What must a multi-mode terminal do when it enters 3GPP mode of operation? [3GPP Release 18]

- A. Act as a 3GPP only UE which had just been switched-on
- B. Prioritize network selection based on system capabilities
- C. Perform regular investigation scans for higher priority PLMNs
- D. Avoid ping-pong between systems by using a hysteresis function
- E. Store the forbidden PLMNs list in the SIM/USIM

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1498`）

</details>

**1.2.7-75.** Is the user able to re-enable use of a radio technology on a UE that has been previously disallowed? [3GPP Release 18]

- A. Yes
- B. No

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7839`）

</details>

## 1.2.8 Wi-Fi 與 IEEE 802 區域網路（539 題）

**1.2.8-1.** What are the transmission media used in LANs?

- A. Wireless and coaxial cable only
- B. Fiber-optic cable and radio only
- C. Wire-pair, coaxial cable, fiber-optic cable, and radio

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-461`）

</details>

**1.2.8-2.** What frequency band does Bluetooth use? [Bluetooth - Overview]

- A. 4 GHz
- B. 5 GHz
- C. 40 MHz
- D. 1 MHz

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-663`）

</details>

**1.2.8-3.** What connects stations to the network in thick Ethernet? [IEEE 802.3]

- A. Switches
- B. BNC connectors
- C. BNC terminators
- D. Hubs
- E. Transceivers

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1346`）

</details>

**1.2.8-4.** How many wires are there in a UTP cable for Fast Ethernet? [IEEE 802.3]

- A. 2
- B. 4
- C. 6
- D. 8

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1438`）

</details>

**1.2.8-5.** What is bridging?

- A. A device that connects two different types of networks, such as Ethernet and Wi-Fi.
- B. A device that amplifies the signal strength of a cellular network.
- C. A device used for satellite communication.
- D. A device that converts analog signals to digital signals.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1621`）

</details>

**1.2.8-6.** How many wires are there in a UTP cable used in 10/100Base-T? [IEEE 802.3]

- A. 4
- B. 6
- C. 8
- D. 10

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2125`）

</details>

**1.2.8-7.** What technology does Bluetooth use to transmit data? [Bluetooth - Overview]

- A. MIMO
- B. TPC
- C. DCS
- D. FHSS

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2275`）

</details>

**1.2.8-8.** What is the transmission power of a BLE (Bluetooth Low Energy) beacon?

- A. The power required to connect with other beacons in the area
- B. The power required to receive the beacon signal
- C. The power required to broadcast the beacon signal
- D. The power required to exchange data with nearby devices

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2883`）

</details>

**1.2.8-9.** What is the meaning of Interworking WLAN (I-WLAN)?

- A. A service that allows multimedia conversational communications between two or more users.
- B. A service that provides access to IP Multimedia Services.
- C. A service that provides real-time bidirectional conversational transfer of media.
- D. A WLAN that interworks with a 3GPP system.
- E. All of the above.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3364`）

</details>

**1.2.8-10.** What is the difference between a hub and a repeater in Ethernet? [IEEE 802.3]

- A. A repeater regenerates incoming signals
- B. A hub transmits packets transparently
- C. A hub is a multiport repeater
- D. A repeater is used for network management
- E. A hub is used to avoid collisions

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3627`）

</details>

**1.2.8-11.** How many channels are there in the 2.4 GHz band used by Bluetooth? [Bluetooth - Overview]

- A. 79 channels
- B. 1600 channels
- C. 2 channels
- D. 4 channels

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4487`）

</details>

**1.2.8-12.** What type of cable is used for 10GBase-T Ethernet? [IEEE 802.3]

- A. Ethernet
- B. Fiber optic
- C. Coaxial
- D. Wireless
- E. Twisted pair

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4790`）

</details>

**1.2.8-13.** What is a backbone segment in Ethernet? [IEEE 802.3]

- A. A segment that uses repeaters to connect to other segments
- B. A segment that connects segments of different media with each other
- C. A segment that connects to an access point
- D. A segment that is controlled from a management station

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5021`）

</details>

**1.2.8-14.** What is the primary advantage of using directional antennas in wireless networks? [IEEE 802.11]

- A. They have a shorter wavelength, allowing for clearer signals.
- B. They have higher sensitivity to radio signals in the dominant direction.
- C. They are omnidirectional, allowing for signals from any direction.
- D. They have a larger antenna and can reach farther distances.
- E. They are more resistant to multipath interference.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5278`）

</details>

**1.2.8-15.** What is the definition of DSAF in the context of IEEE Std 802.11-2020?

- A. A class of coordination function used in specific service sets (SSs)
- B. A function within an access point (AP) that provides access between the distribution system (DS) and the wireless medium (WM)
- C. A system used to interconnect a set of basic service sets (BSSs) and integrated local area networks (LANs)
- D. The medium or set of media used by a distribution system (DS) for communications between access points (APs), mesh gates, and the portal of an extended service set (ESS)
- E. The set of services provided by the distribution system (DS) that enable the medium access control (MAC) to transport MAC service tuples between stations (STAs) that are not in direct communication with each other over a single instance of the wireless medium (WM)

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6396`）

</details>

**1.2.8-16.** What does the term '3GPP-WLAN Interworking' refer to?

- A. Interconnectivity between 3GPP systems and WLAN networks
- B. Interworking between 3GPP systems and WAN networks
- C. Interworking between 3GPP and WAP protocols
- D. Interconnectivity between 3GPP and LTE networks
- E. Interconnectivity between 3GPP and VoIP services

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6430`）

</details>

**1.2.8-17.** What is the definition of DSM in the context of IEEE Std 802.11-2020?

- A. A class of coordination function used in specific service sets (SSs)
- B. A function within an access point (AP) that provides access between the distribution system (DS) and the wireless medium (WM)
- C. A system used to interconnect a set of basic service sets (BSSs) and integrated local area networks (LANs)
- D. The medium or set of media used by a distribution system (DS) for communications between access points (APs), mesh gates, and the portal of an extended service set (ESS)
- E. The set of services provided by the distribution system (DS) that enable the medium access control (MAC) to transport MAC service tuples between stations (STAs) that are not in direct communication with each other over a single instance of the wireless medium (WM)

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7037`）

</details>

**1.2.8-18.** What are the key technologies to achieve a high throughput in WLANs using multiple antennas?

- A. SU-MIMO and Downlink MU-MIMO
- B. Uplink MU-MIMO and Massive MIMO
- C. Network MIMO and Distributed antenna solutions
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7243`）

</details>

**1.2.8-19.** Why does an originator regularly send a BlockAckReq frame in the GCR Block Ack retransmission policy? [IEEE 802.11]

- A. To indicate the end of the transmission
- B. To request acknowledgment from the group members
- C. To synchronize the group members
- D. To minimize buffering latency at the receivers

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-12`）

</details>

**1.2.8-20.** What are dependent stations (STA)?

- A. STAs that are registered and have control over their operational parameters
- B. STAs that can operate independently without receiving messages from other STAs
- C. STAs that are not registered and have operational parameters dictated by enabling STAs
- D. STAs that can operate on multiple frequency segments simultaneously

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-23`）

</details>

**1.2.8-21.** What is the purpose of data frames in 802.11? [IEEE 802.11]

- A. To carry data from station to station
- B. To perform area clearing and carrier-sensing maintenance
- C. To join and leave wireless networks
- D. To indicate whether frames are buffered for a station

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-35`）

</details>

**1.2.8-22.** When can the unused portion of a polled TXOP be reallocated by the HC? [IEEE 802.11]

- A. When a PHY-CCA.indication (BUSY) primitive occurs at the STA expecting the Ack frame
- B. When the expected Ack frame is not received
- C. When there is not enough time to transmit a QoS Null frame
- D. When the STA ceases control of the channel
- E. When there are no frames to be sent to the HC

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-42`）

</details>

**1.2.8-23.** What is an overlapping basic service set (OBSS)?

- A. An FT method in which the STA communicates with the target AP via the current AP
- B. A station that is not contained within an access point (AP)
- C. A numerical value used in cryptographic operations associated with a given cryptographic key
- D. An FT method in which the STA communicates over a wireless medium link to the target AP
- E. A basic service set (BSS) operating on the same channel as the station's (STA's) BSS

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-67`）

</details>

**1.2.8-24.** What can be adjusted to ensure responses from all access points in an area can be processed during active scanning? [IEEE 802.11]

- A. Minimum channel time
- B. Maximum channel time
- C. Beacon interval
- D. DTIM period

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-74`）

</details>

**1.2.8-25.** What is a mesh facility?

- A. A basic service set (BSS) that forms a self-contained network of mesh stations (STAs) that use the same mesh profile.
- B. A relationship between two mesh stations (STAs) that is required for direct communication over a single instance of the wireless medium (WM).
- C. The set of enhanced functions, channel access rules, frame formats, mutual authentication methods, and managed objects used to provide data transfer among autonomously operating stations (STAs) that might not be in direct communication with each other over a single instance of the wireless medium.
- D. Any entity that has a mesh station (STA) function and a distribution system access function (DSAF) to provide access to a single distribution system for the mesh basic service set (MBSS).
- E. The set of all neighbor mesh stations (STAs) of a particular mesh STA.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-111`）

</details>

**1.2.8-26.** What is the purpose of spread spectrum technology in unlicensed devices? [IEEE 802.11]

- A. To increase the transmitted power of the devices
- B. To diffuse signal power over a large range of frequencies
- C. To restrict the use of radio signals in certain areas
- D. To encode the transmitted data for security purposes

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-123`）

</details>

**1.2.8-27.** How does an AP set up the protection for the duration of the sectorized beam transmission in an SO frame exchange sequence? [IEEE 802.11]

- A. By transmitting an ACK or Response frame after the omnidirectional beam transmission.
- B. By setting the NAV for the duration of the sectorized beam transmission.
- C. By transmitting a BF duration frame after the omnidirectional beam transmission.
- D. By switching to the sectorized beam transmission after the omnidirectional preamble.
- E. By transmitting a NAV protected frame after the omnidirectional beam transmission.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-125`）

</details>

**1.2.8-28.** What does the Omni field indicate? [IEEE 802.11]

- A. The Omni field indicates the type of sectorization operation.
- B. The Omni field indicates if the present transmission is sectorized or omnidirectional.
- C. The Omni field indicates the duration of the current sector transmissions.
- D. The Omni field indicates the ID of the active sector.
- E. The Omni field is reserved when sectorization is activated.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-134`）

</details>

**1.2.8-29.** What is the length of the source MAC address field in an Ethernet frame? [IEEE 802.3]

- A. 2 bytes
- B. 4 bytes
- C. 6 bytes
- D. 8 bytes

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-142`）

</details>

**1.2.8-30.** What is the definition of the Chip Rate field value '1'? [IEEE 802.15.4]

- A. 300 kchip/s
- B. 600 kchip/s
- C. 800 kchip/s
- D. 1 Mchips/s

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-146`）

</details>

**1.2.8-31.** What is the data rate for each clock pulse in 100Base-T? [IEEE 802.3]

- A. 1 bit
- B. 2 bits
- C. 4 bits
- D. 8 bits

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-224`）

</details>

**1.2.8-32.** What is a BLE (Bluetooth Low Energy) beacon?

- A. A small wireless transmitter that broadcasts its identifier to nearby electronic devices
- B. A device that connects with other beacons in its range to exchange data
- C. A protocol used for wireless communication between smartphones and IoT devices
- D. A type of battery that is commonly used in beacons

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-227`）

</details>

**1.2.8-33.** What is the main drawback of using proprietary approaches for stronger security in WEP? [IEEE 802.11]

- A. Limited number of weak IVs
- B. Weakness in the key scheduling algorithm
- C. Vulnerability to keystream analysis
- D. Inadequate key length
- E. Lack of interoperability on multivendor networks

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-277`）

</details>

**1.2.8-34.** What does LACP stand for? [IEEE 802.3]

- A. Local Area Configuration Protocol
- B. Large Area Communication Protocol
- C. Link Aggregation Control Protocol
- D. Laser-Assisted Communication Protocol

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-278`）

</details>

**1.2.8-35.** When is the New Mode FEC field overridden in a mode switch PPDU? [IEEE 802.15.4]

- A. When the New Mode FEC field has a value of zero
- B. When the New Mode FEC field has a value of one
- C. When the new mode packet has an SFD
- D. When the new mode packet does not have FEC
- E. When the Mode Switch field is set to zero

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-280`）

</details>

**1.2.8-36.** What is one of the key aspects of interworking between Wi-Fi and LTE/LTE-A systems?

- A. Package loss
- B. Radio link failure
- C. Seamless mobility
- D. Traffic steering

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-282`）

</details>

**1.2.8-37.** Which authentication method is based on WEP and requires both stations to implement WEP? [IEEE 802.11]

- A. Open-System Authentication
- B. Shared-Key Authentication
- C. Mutual Authentication
- D. MAC Address Filtering
- E. Digital Certificate Authentication

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-283`）

</details>

**1.2.8-38.** What do the TYPE(TAG) and VLAN TPID fields in an IEEE802.1Q tagged frame specify? [IEEE 802.3]

- A. The priority code of the frame
- B. The VLAN identification
- C. The frame's originating segment
- D. The frame's destination segment

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-287`）

</details>

**1.2.8-39.** Which protocol is used for the exchange of configuration information between systems in Link Aggregation? [IEEE 802.3]

- A. Ethernet
- B. TCP
- C. IP
- D. LACP
- E. IEEE

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-301`）

</details>

**1.2.8-40.** What is the purpose of the Hop Dwell Time field in the Hopping Timing IE Content field? [IEEE 802.15.4]

- A. To indicate the amount of time that has passed since the transmitting device hopped to the present channel.
- B. To indicate the time interval between consecutive hops.
- C. To indicate the number of channels hopped by the device.
- D. To indicate the time interval for a single hop.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-326`）

</details>

**1.2.8-41.** What happens if two or more stations send a data frame at the same time in CSMA/CD? [IEEE 802.3]

- A. The frame is delayed
- B. The sender continues sending the frame
- C. The receiver sends an error frame
- D. The frame is discarded
- E. A collision occurs

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-336`）

</details>

**1.2.8-42.** What is one of the key requirements for the IEEE 802.11ax-2019 amendment?

- A. Deployment of LTE networks in the ISM band.
- B. Implementation of advanced multiple-antenna techniques.
- C. Use of centralized self-configuration and self-adaption mechanisms.
- D. Improvement of both system and user throughput.
- E. Operation as licensed devices in the ISM bands.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-345`）

</details>

**1.2.8-43.** What does the Challenge Text in the third frame of a shared-key authentication exchange contain? [IEEE 802.11]

- A. 128 bytes generated using the WEP keystream generator
- B. A random key and initialization vector
- C. Information elements to identify the authentication algorithm and sequence number
- D. Status code indicating the success or failure of the authentication

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-397`）

</details>

**1.2.8-44.** According to IEEE Std 802.11-2020, when would GLK STAs find PS mode useful? [IEEE 802.11]

- A. When carrying unknown traffic loads on behalf of other endpoints
- B. When participating in the same BSS as another GLK STA
- C. When receiving frames with the value of its TA field equal to the MAC address of another GLK STA
- D. When transmitting Block Ack frames in an IBSS or PBSS
- E. When engaging in DMS agreements

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-405`）

</details>

**1.2.8-45.** What is a MAC address in networking?

- A. A code used to access a Wi-Fi network's admin settings.
- B. A type of email address used for marketing campaigns.
- C. A unique hardware address assigned to network devices for identification.
- D. A protocol for secure file transfers over the internet.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-419`）

</details>

**1.2.8-46.** When is the FB Tx Type subfield set to 0? [IEEE 802.11]

- A. When the unsolicited MFB is estimated from a VHT PPDU with the RXVECTOR parameter BEAMFORMED equal to 0
- B. When the unsolicited MFB is estimated from a VHT PPDU with the RXVECTOR parameter BEAMFORMED equal to 1
- C. Reserved
- D. None of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-423`）

</details>

**1.2.8-47.** What is the transmission range of IEEE 802.11ah in outdoor areas?

- A. Up to 100 meters
- B. Up to 500 meters
- C. Up to 1 km
- D. Up to 10 km
- E. Up to 100 km

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-426`）

</details>

**1.2.8-48.** What does LLC stand for in the LAN (Local Area Network) architecture related to OSI (Open System Interconnection)?

- A. Link Layer Control
- B. Logical Layer Control
- C. LAN Link Control
- D. Logical Link Control

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-429`）

</details>

**1.2.8-49.** Which protocol is used for calculating the tree structure in Spanning Tree Protocol (STP)? [IEEE 802.3]

- A. Parallel Redundancy Protocol (PRP)
- B. Topology Change Notiﬁcation BPDU (TCN)
- C. Topology Change Notiﬁcation Acknowledgement (TCA)
- D. Media Redundancy Protocol (MRP)
- E. Conﬁguration BPDU (CBPDU)

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-440`）

</details>

**1.2.8-50.** What service allows the connection of the distribution system to a non-IEEE 802.11 network? [IEEE 802.11]

- A. Distribution service
- B. Integration service
- C. Association service
- D. Reassociation service
- E. Disassociation service

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-474`）

</details>

**1.2.8-51.** What does the macDsmeAct represent in the context of DSME GTS Notify command? [IEEE 802.15.4]

- A. The value of macShortAddress
- B. The allocation of DSME GTS
- C. The management type of GTS Notify command
- D. The Destination Address of GTS Notify command
- E. The value of DSME SAB Specification field

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-528`）

</details>

**1.2.8-52.** What is the feature related to the separation of data and control planes in 802.11be?

- A. Coordinated null steering
- B. Multi-band data aggregation
- C. Data and control plane separation
- D. Simultaneous transmission and reception in different bands/channels

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-554`）

</details>

**1.2.8-53.** What is R-TWT used for in Wi-Fi 7?

- A. To improve mobility support
- B. To reduce channel access time
- C. To achieve multi-AP coordination
- D. To provide worst-case latency guarantees

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-616`）

</details>

**1.2.8-54.** When a GLK AP uses a combination of methods to transmit the MSDU, how many times is each peer STA addressed? [IEEE 802.11]

- A. Four times
- B. Twice
- C. Thrice
- D. Once
- E. Depends on the number of general links

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-628`）

</details>

**1.2.8-55.** Which modulation schemes adopted by Wi-Fi devices provide frequency diversity?

- A. Code-division multiple access
- B. Orthogonal frequency-division access
- C. Time-division multiplexing
- D. Carrier sense multiple access
- E. Orthogonal frequency-division multiplexing

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-633`）

</details>

**1.2.8-56.** What is the purpose of the service primitives in IEEE 802.15.4? [IEEE 802.15.4]

- A. To provide synchronization services
- B. To calculate performance metrics
- C. To define the interface between layers
- D. To enable communication between devices

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-679`）

</details>

**1.2.8-57.** What is the purpose of the preamble field in the MAC (Medium Access Control) frame format?

- A. To synchronize the receive PLS with the transmitted symbol stream
- B. To indicate the start of the frame
- C. To provide the source and destination addresses
- D. To indicate the length of the LLC data
- E. To perform error detection

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-712`）

</details>

**1.2.8-58.** What does the dot11SSPNInterfaceActivated parameter indicate? [IEEE 802.11]

- A. The priority of the received frame
- B. The type of the received frame
- C. The resource utilization limit
- D. The activation status of the SSID
- E. The activation status of the interface

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-738`）

</details>

**1.2.8-59.** What is the role of access points in the distribution system? [IEEE 802.11]

- A. To establish associations between access points and users
- B. To prevent unauthorized access to the network
- C. To provide privacy and encryption for data
- D. To extend services from the wired network to the wireless network
- E. To enable MSDU delivery to the recipient

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-746`）

</details>

**1.2.8-60.** What does the ASEL Command subfield in the ASELC (Antenna Selection) subfield indicate? [IEEE 802.11]

- A. Transmit Antenna Selection Sounding Indication (TXASSI)
- B. Transmit Antenna Selection Sounding Request (TXASSR) or Transmit ASEL Sounding Resumption
- C. Receive Antenna Selection Sounding Indication (RXASSI)
- D. Receive Antenna Selection Sounding Request (RXASSR)
- E. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-764`）

</details>

**1.2.8-61.** In which frequency bands does the HRP UWB PHY operate? [IEEE 802.15.4]

- A. Sub-gigahertz band only
- B. Low band only
- C. High band only
- D. Sub-gigahertz band and low band only
- E. Sub-gigahertz band, low band, and high band

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-792`）

</details>

**1.2.8-62.** Which wireless protocol is commonly used by BLE beacons?

- A. Bluetooth Classic
- B. Wi-Fi
- C. Zigbee
- D. BLE (Bluetooth Low Energy)

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-796`）

</details>

**1.2.8-63.** Which interframe space is used for the highest-priority transmissions? [IEEE 802.11]

- A. PIFS
- B. SIFS
- C. DIFS
- D. EIFS
- E. Distributed interframe space (DIFS)

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-801`）

</details>

**1.2.8-64.** Which networking device is used to connect multiple computers in a LAN and forward data packets between them?

- A. Router
- B. Switch
- C. Modem
- D. Firewall

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-802`）

</details>

**1.2.8-65.** When does the AP or PCP start the Polling Period (PP)? [IEEE 802.11]

- A. During a scheduled SP for which the source AID and destination AID are equal to the broadcast AID
- B. During a TXOP within a scheduled CBAP for which the destination AID is equal to the broadcast AID
- C. During the relinquished channel time following an SP truncation
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-828`）

</details>

**1.2.8-66.** What does AID stand for in the context of the association procedure? [IEEE 802.11]

- A. Authentication ID
- B. Associated Identification
- C. Access Point ID
- D. Association ID
- E. Appointed Identifier

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-843`）

</details>

**1.2.8-67.** What does the Max SP Length subfield indicate? [IEEE 802.11]

- A. The length of the Measurement Pilot Interval field.
- B. The interval between target measurement pilot transmission times.
- C. The maximum number of rows in a beamforming feedback matrix.
- D. The number of time units between target measurement pilot transmission times.
- E. The maximum number of buffered BUs the STA is prepared to receive.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-883`）

</details>

**1.2.8-68.** What is the purpose of management frames in 802.11? [IEEE 802.11]

- A. To carry data from station to station
- B. To perform area clearing and carrier-sensing maintenance
- C. To join and leave wireless networks
- D. To indicate whether frames are buffered for a station

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-890`）

</details>

**1.2.8-69.** What should a VHT beamformee do when responding to a Beamforming Report Poll frame? [IEEE 802.11]

- A. Ignore the Beamforming Report Poll frame
- B. Transmit all feedback segments that exist
- C. Transmit a Management frame
- D. Transmit an Ack frame
- E. Transmit only the indicated feedback segments

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-907`）

</details>

**1.2.8-70.** Which wireless standard uses the WEP (wired equivalent privacy) protocol as a security measure?

- A. Bluetooth
- B. Wi-Fi
- C. WiMAX
- D. LTE
- E. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-947`）

</details>

**1.2.8-71.** What is the advantage of VLANs in terms of additional security? [IEEE 802.3]

- A. Broadcast messages are limited
- B. Devices can communicate with devices in other VLANs
- C. Devices can only communicate within the same VLAN
- D. Network load is restricted

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-961`）

</details>

**1.2.8-72.** What is the purpose of the disassociation service in 802.11 networks? [IEEE 802.11]

- A. To integrate non-IEEE 802.11 networks
- B. To evaluate signal strength
- C. To terminate an existing association
- D. To deliver frames to their destination
- E. To register mobile stations with access points

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-974`）

</details>

**1.2.8-73.** What are the three components of the 802.11 management architecture? [IEEE 802.11]

- A. MLME, PLME, and SME
- B. MAC, PHY, and SME
- C. MLME, PHY, and SME
- D. MAC, PLME, and SME

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1007`）

</details>

**1.2.8-74.** What is the role of a RLSS in the GDD system? [IEEE 802.11]

- A. Providing GDBs with the current channel use information for all BSSs and IBSSs
- B. Coordinating emissions footprints of white space systems with controllers
- C. Sharing white space maps and channel utilization among GDD enabling STAs
- D. Providing WSMs and current channel use information to GDD dependent STAs

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1011`）

</details>

**1.2.8-75.** Which PHY operates in the 780 MHz band? [IEEE 802.15.4]

- A. GFSK PHY
- B. BPSK PHY
- C. CSS PHY
- D. HRP UWB PHY
- E. O-QPSK PHY

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1015`）

</details>

**1.2.8-76.** Which VLANs limit the problem of broadcast messages? [IEEE 802.3]

- A. VLANs organized by department
- B. VLANs organized by hierarchy
- C. VLANs organized by use
- D. All VLANs

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1051`）

</details>

**1.2.8-77.** Which architecture relies on one or several APs (Access points) to allocate radio resources and ensure timing among connected devices?

- A. AP-Free Architecture
- B. Self-Coordinated Architecture
- C. AP-Coordinated Architecture
- D. Hybrid Architecture
- E. Partial-Coverage Architecture

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1075`）

</details>

**1.2.8-78.** What is the purpose of the third address in frames to the AP? [IEEE 802.11]

- A. To transmit data from one station to another
- B. To acknowledge other frames without using separate acknowledgments
- C. To identify the receiver and transmitter of the frame on the wireless medium
- D. To send acknowledgments to the frame's transmitter and replies to the frame's source
- E. To forward data to the appropriate location in the distribution system

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1094`）

</details>

**1.2.8-79.** What separates the frames transmitted during the Pairnet associated period (PAP)?

- A. Beacons
- B. Short interframe space (SIFS)
- C. Association Request
- D. Disassociation Request

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1110`）

</details>

**1.2.8-80.** When are reassociations initiated in 802.11 networks? [IEEE 802.11]

- A. By the access point
- B. When signal conditions indicate a different association would be beneficial
- C. During the station shutdown process
- D. When frames are delivered to mobile stations
- E. When stations leave the network without disassociating

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1130`）

</details>

**1.2.8-81.** What triggers a Transmit Stream/Category Measurement report to be generated in the Delay bit mode? [IEEE 802.11]

- A. The number of MSDUs for the TC or TS that are discarded out of the number of preceding MSDUs
- B. The number of MSDUs for the TC or TS that are discarded in succession
- C. The number of consecutive MSDUs for the TC or TS that experience a transmit delay
- D. The value specified in the Average Error Threshold field
- E. The value specified in the Delay Threshold subfield

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1138`）

</details>

**1.2.8-82.** What is the purpose of the length field in the MAC (Medium Access Control) frame format?

- A. To synchronize the receive PLS with the transmitted symbol stream
- B. To indicate the start of the frame
- C. To provide the source and destination addresses
- D. To indicate the length of the LLC data
- E. To perform error detection

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1168`）

</details>

**1.2.8-83.** What is the name of the mechanism that combines soft-bits to improve the decoding of retransmitted MPDUs (MAC protocol data units) in 802.11be?

- A. ARQ
- B. HARQ
- C. CSMA/CA
- D. MU-MIMO

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1212`）

</details>

**1.2.8-84.** What is one of the benefits of coordinated OFDMA (Orthogonal Frequency Division Multiple Access) in 802.11be?

- A. Reduced latency of short packet data transmissions
- B. Improved spatial multiplexing
- C. Minimized collision probability in dense scenarios
- D. Enhanced sharing of time/frequency resources

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1235`）

</details>

**1.2.8-85.** What does the Pairnet device (PRDEV) do in response to the Beacon during the Pairnet setup period (PSP)?

- A. Sends higher-layer protocol information.
- B. Sends an Association Response.
- C. Sends an Association Request.
- D. Sends data frames.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1243`）

</details>

**1.2.8-86.** What is the meaning of a group address?

- A. A contiguous block of spectrum used by a transmission
- B. A unit of data exchanged between peer protocol entities
- C. The information maintained by a mesh station (STA) that allows the mesh STA to perform its path selection and forwarding functions
- D. A medium access control (MAC) address with the group bit equal to 1
- E. A location within an earth-centric frame of reference

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1244`）

</details>

**1.2.8-87.** What type of scanning saves battery power by listening for Beacon frames? [IEEE 802.11]

- A. Active scanning
- B. Passive scanning
- C. Broadcast scanning
- D. Channel scanning

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1268`）

</details>

**1.2.8-88.** What does MSTP stand for? [IEEE 802.3]

- A. Multiple Switching Tree Protocol
- B. Multi-Spanning Tree Protocol
- C. Maximum Spanning Tree Protocol
- D. Master Switching Tree Protocol

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1269`）

</details>

**1.2.8-89.** What is the maximum segment length for Ethernet over twisted pair (10Base-T)? [IEEE 802.3]

- A. 500 meters
- B. 200 meters
- C. 1000 meters
- D. 100 meters
- E. 50 meters

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1283`）

</details>

**1.2.8-90.** What is the purpose of the integration service in IEEE Std 802.11-2020?

- A. To bridge different LANs together
- B. To provide security for the distribution system (DS)
- C. To enable communication between the DS and a local area network (LAN)
- D. To manage multicast traffic within the LAN
- E. To synchronize time across multiple LANs

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1297`）

</details>

**1.2.8-91.** What is contained in the SD Bitmap field? [IEEE 802.15.4]

- A. The index of the current SD in a beacon interval
- B. The ID of the channel hopping sequence in use
- C. A bitmap indicating the Beacon frame allocation information of all 2(BO – SO) superframes within one beacon interval
- D. The length of the Beacon frame allocation information bitmap
- E. The value of the SD Bitmap Length field in octets

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1320`）

</details>

**1.2.8-92.** What is the purpose of the DMG protected period? [IEEE 802.11]

- A. To minimize interference by limiting the transmission of frames during a specific period
- B. To allow STAs to protect their SP and limit interference with other stations
- C. To negotiate a bandwidth that can be used in the SP
- D. To ensure both source and destination DMG STAs can receive frames from each other

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1322`）

</details>

**1.2.8-93.** What are the first and second address fields used for in WDS frames? [IEEE 802.11]

- A. Receiver and Transmitter
- B. Source and Destination
- C. Acknowledgments and control traffic
- D. Wireless link addresses

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1349`）

</details>

**1.2.8-94.** What is the purpose of the MAC PIB attribute macSuperframeOrder? [IEEE 802.15.4]

- A. To determine the number of CAP slots
- B. To specify the duration of beacon intervals
- C. To control the allocation of GTSs
- D. To define the length of the active portion of the superframe

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1359`）

</details>

**1.2.8-95.** What is the aim of IEEE 802 Time-Sensitive Networking?

- A. Improve spectral efficiency
- B. Support high data rates
- C. Reduce transmission time
- D. Enhance medium access latency
- E. Deliver deterministic latency over Ethernet networks

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1367`）

</details>

**1.2.8-96.** How is the default hopping sequence generated? [IEEE 802.15.4]

- A. Randomly shuffled set of channels
- B. Linear feedback shift register
- C. Monotonically increasing set of channels
- D. Pseudo-random sequence

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1378`）

</details>

**1.2.8-97.** Which MAC (medium access control) layer protocol of IEEE 802.11 family of wireless network standards introduces significant enhancements to support soft real-time applications?

- A. IEEE 802.11
- B. IEEE 802.11e
- C. HCF
- D. PCF
- E. EDCA

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1432`）

</details>

**1.2.8-98.** What is the definition of unicast in the context of IEEE Std 802.11-2020?

- A. An interval of time during which a particular QoS station (STA) has the right to initiate frame exchange sequences
- B. A set of traffic specifications defined by traffic classification (TCLAS) elements
- C. The use of a resource not consistent with the defined security policy
- D. The process of making information available to unauthorized individuals, entities, or processes
- E. An individually addressed frame sent from one station to another

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1454`）

</details>

**1.2.8-99.** What is a neighbor station (STA)?

- A. A STA that can directly transmit to and receive from other STAs over the wireless medium.
- B. A STA that is not contained within an access point (AP).
- C. A STA that is a potential service set transition candidate.
- D. A STA that supports the quality-of-service (QoS) facility.
- E. A STA that does not support the quality-of-service (QoS) facility.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1474`）

</details>

**1.2.8-100.** What is the purpose of the Spanning Tree Protocol (STP)? [IEEE 802.3]

- A. Easy to configure; everything is done using the switch.
- B. Redundant links are integrated; an automated backup path is provided.
- C. Recovery time of 1 to 10 seconds; can be used for redundant ring structures.
- D. Guarantees a closed loop-free LAN and provides an automated backup path if an active link drops out.
- E. Cost is low; does not require any configuration.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1481`）

</details>

**1.2.8-101.** What should a centralized clustering enabled STA do if it receives a DMG Beacon frame from a member AP of another ECAPC? [IEEE 802.11]

- A. Continue and become an S-AP in the CCSS
- B. Join the cluster of the S-AP as a member AP or member PCP
- C. Cease its activity on this channel
- D. Attempt operation on a different channel
- E. Unenroll from its current CCSS

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1503`）

</details>

**1.2.8-102.** Which protocol is recommended to use instead of Spanning Tree Protocol (STP) according to IEEE standards? [IEEE 802.3]

- A. Media Redundancy Protocol (MRP)
- B. Parallel Redundancy Protocol (PRP)
- C. (R)STP: (Rapid) Spanning Tree Protocol
- D. Fast Ring Detection
- E. Bridge Protocol Data Units (BPDUs)

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1512`）

</details>

**1.2.8-103.** What does the RA frame signal? [IEEE 802.11]

- A. Presence of uplink buffered data
- B. Presence of downlink buffered data for paged STAs and their assigned RAW slots
- C. Presence of raw data packets
- D. Presence of a newly connected STA

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1544`）

</details>

**1.2.8-104.** What does a CDMG STA support in addition to CDMG features? [IEEE 802.11]

- A. MAC sublayer operations
- B. BSS management
- C. DMG features
- D. Radio environment control

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1569`）

</details>

**1.2.8-105.** What is the purpose of the TYPE field in an Ethernet frame? [IEEE 802.3]

- A. To identify the destination address
- B. To identify the source address
- C. To indicate the start of the frame
- D. To specify the higher-level protocol that uses the Ethernet frame

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1605`）

</details>

**1.2.8-106.** What does the TIM (Traffic indication map) and Page Segmentation mechanism in the IEEE 802.11ah MAC (Medium Access Control) layer enable?

- A. Reduced time for stations to compete for the channel and increased sleep time
- B. Increased time for stations to compete for the channel and reduced sleep time
- C. Increased network efficiency and packet delivery ratio
- D. Enhanced QoS and power-saving mode
- E. Reduced number of stations supported by the AP

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1652`）

</details>

**1.2.8-107.** What does the BufSizeB parameter indicate in the DMG block ack architecture? [IEEE 802.11]

- A. The size of the transmission window
- B. The size of the reception window
- C. The number of buffers negotiated in the block ack agreement
- D. The SN of the first MSDU or A-MSDU that has not yet been delivered

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1679`）

</details>

**1.2.8-108.** What is the maximum number of rows of CSI explicit feedback that an HT beamformer or calibration initiator can support? [IEEE 802.11]

- A. 0
- B. 1
- C. 2
- D. 3

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1693`）

</details>

**1.2.8-109.** Which IEEE 802.11 amendment is targeting fast handoff between APs (Access Points)?

- A. IEEE 802.11ai-2016
- B. IEEE 802.11ad-2012
- C. IEEE 802.11aa-2012
- D. IEEE 802.11ak-2017
- E. IEEE 802.11aq-2018

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1700`）

</details>

**1.2.8-110.** What is the advantage of using Bluetooth in the industry? [Bluetooth - Overview]

- A. Higher transmission speed
- B. Perfect co-existence with WLAN
- C. Ability to transmit Ethernet data frames
- D. Automated co-existence mechanism

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1701`）

</details>

**1.2.8-111.** What is the purpose of the Wi-Fi Alliance in relation to 802.11be?

- A. To develop appropriate certifications for high profile features
- B. To define the objectives of 802.11be
- C. To ensure backward compatibility with legacy 802.11 devices
- D. To establish carrier frequencies for 802.11be

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1708`）

</details>

**1.2.8-112.** Which devices are commonly powered using IEEE802.3af Power over Ethernet? [IEEE 802.3]

- A. WLAN access points
- B. Bluetooth access points
- C. IP telephones
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1782`）

</details>

**1.2.8-113.** What is the relationship between macOffsetTimeSlot and OTD? [IEEE 802.15.4]

- A. OTD = macOffsetTimeSlot
- B. OTD = aBaseSlotDuration + macOffsetTimeSlot
- C. OTD = aBaseSlotDuration × macOffsetTimeSlot
- D. OTD = aBaseSlotDuration - macOffsetTimeSlot

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1808`）

</details>

**1.2.8-114.** What are the rules for adopting the received timestamp in an independent network? [IEEE 802.11]

- A. Synchronize all timers to the fastest-running clock in the BSS
- B. Adjust the timestamp for processing delays
- C. Update the local timer if the received timestamp is later
- D. Compare the received timestamp to the local TSF
- E. Adjust the timestamp for transmission delays

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1813`）

</details>

**1.2.8-115.** What is the maximum number of GTS descriptors that can be maintained? [IEEE 802.15.4]

- A. Three
- B. Five
- C. Seven
- D. Nine
- E. Eleven

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1825`）

</details>

**1.2.8-116.** What starts the Pairnet associated period (PAP)?

- A. Successful reception of the Association Response.
- B. The sending of a Probe Request.
- C. The sending of a Disassociation Request.
- D. Timeout due to no message received from the PRDEV.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1826`）

</details>

**1.2.8-117.** Which IEEE802 standard is responsible for ZigBee?

- A. IEEE802.1 Bridging
- B. IEEE802.2 Logical Link Control
- C. IEEE802.3 CSMA/CD
- D. IEEE802.15.4 ZigBee
- E. IEEE802.21 Media Independent Handoff

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1839`）

</details>

**1.2.8-118.** What is the characteristic of Fast Ethernet? [IEEE 802.3]

- A. Half Duplex communication
- B. Wireless Ethernet
- C. 10Mbps data rate
- D. Full Duplex communication

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1845`）

</details>

**1.2.8-119.** What is a TVWS multichannel cluster tree PAN (TMCTP)? [IEEE 802.15.4]

- A. A form of single cluster network
- B. A form of mesh network
- C. A form of cluster tree network
- D. A form of super PAN coordinator network

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1854`）

</details>

**1.2.8-120.** What is the maximum segment length for thick Ethernet (10Base5)? [IEEE 802.3]

- A. 500 meters
- B. 200 meters
- C. 1000 meters
- D. 100 meters
- E. 50 meters

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1890`）

</details>

**1.2.8-121.** What is the purpose of the IEEE 802.15.6 standard?

- A. To regulate short-range wireless communications inside or in the vicinity of the human body
- B. To define the maximum transmit power for wireless communications
- C. To allocate frequency bands for medical devices usage
- D. To establish communication standards for smart jamming attacks

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1910`）

</details>

**1.2.8-122.** What does the Average Queue Delay field represent? [IEEE 802.11]

- A. Delay exceeding the Delay Threshold
- B. Delay between passing the MSDU to the MAC and the start of transmission
- C. Average delay of the successfully transmitted frames
- D. Number of MSDUs successfully transmitted
- E. Average delay of the frames due to retransmissions

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1915`）

</details>

**1.2.8-123.** What does a Measurement Method field value of 0 indicate in IEEE Std 802.11-2020? [IEEE 802.11]

- A. Reserved
- B. RSNI
- C. Directional Channel Quality Reporting
- D. Directional Channel Quality Reference Value
- E. ANIPI

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1928`）

</details>

**1.2.8-124.** What parameter is used to specify whether to seek out independent ad hoc networks, infrastructure networks, or both during scanning? [IEEE 802.11]

- A. BSSType
- B. BSSID
- C. SSID
- D. ScanType

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1933`）

</details>

**1.2.8-125.** What does the SPC do if it does not receive a Beacon frame from the TMCTP-child PAN coordinator within three BIs? [IEEE 802.15.4]

- A. Switches to the TMCTP-child PAN coordinator's channel and sends a response command
- B. Switches to a different channel and sends a response command
- C. Continues listening on the same channel
- D. Switches to the SPC channel and sends a response command
- E. Switches to the next CAP superframe

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1935`）

</details>

**1.2.8-126.** What does the Power Of Two Horizontal Error field indicate? [IEEE 802.11]

- A. Vertical location error
- B. Error between horizontal location and Latitude and Longitude fields
- C. Relative horizontal error of greater than 32 m
- D. Relative horizontal error
- E. Usage rules of the reporting STA

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1942`）

</details>

**1.2.8-127.** What type of frame is sent by a QoS STA when it has no queued traffic to send? [IEEE 802.11]

- A. QoS Control
- B. QoS Null frame
- C. Ack frame
- D. MPDU
- E. TXOP

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1965`）

</details>

**1.2.8-128.** What is the purpose of the Link Layer Discovery Protocol (LLDP)? [IEEE 802.3]

- A. Detection of network errors
- B. Replacement of modules
- C. Network configuration and management
- D. Distribution of information about network participants
- E. Visualizing a network topology

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1985`）

</details>

**1.2.8-129.** Which element is present if dot11HighThroughputOptionImplemented is true? [IEEE 802.11]

- A. TIM Broadcast Response
- B. MSCS Descriptor
- C. QoS Map
- D. HT Capabilities
- E. QMF Policy

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2005`）

</details>

**1.2.8-130.** What is the purpose of the super PAN coordinator (SPC) in a TMCTP? [IEEE 802.15.4]

- A. To define the active portion of the superframe
- B. To reduce collisions between clusters
- C. To provide synchronization services to other PAN coordinators
- D. To provide channel availability information

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2013`）

</details>

**1.2.8-131.** What is the maximum allowable channel switch time? [IEEE 802.15.4]

- A. 500 ns
- B. 500 ms
- C. 500 µs
- D. 500 ps
- E. 500 ks

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2040`）

</details>

**1.2.8-132.** Which frequency band is commonly used for WiFi networks in the U.S.? [IEEE 802.11]

- A. UHF ISM
- B. S-Band
- C. C-Band
- D. X-Band
- E. Ku-Band

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2048`）

</details>

**1.2.8-133.** Which PHY operates with characteristics that enable support of LECIM applications? [IEEE 802.15.4]

- A. TVWS-FSK PHY
- B. LECIM FSK PHY
- C. LECIM DSSS PHY
- D. TVWS-OFDM PHY
- E. TVWS-NB-OFDM PHY

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2061`）

</details>

**1.2.8-134.** What are the carrier frequencies used by IEEE 802.11ah for M2M (Machine-to-Machine) communications?

- A. Approximately 900 MHz
- B. Approximately 2.4 GHz
- C. Approximately 5 GHz
- D. Approximately 60 GHz
- E. Approximately 100 GHz

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2067`）

</details>

**1.2.8-135.** What is the role of a mobile station (STA) in IEEE Std 802.11?

- A. Allow multiple stations to simultaneously transmit to a single STA
- B. Support multiple BSSIDs in a single frame
- C. Manage multiple cooperating STAs
- D. Enable fast BSS transitions
- E. Use network communications while in motion

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2081`）

</details>

**1.2.8-136.** What does the Channel Width subfield indicate in the VHT MIMO Control field? [IEEE 802.11]

- A. The number of columns in the compressed beamforming feedback matrix
- B. The number of rows in the compressed beamforming feedback matrix
- C. The width of the channel in which the measurement to create the compressed beamforming feedback matrix was made
- D. The subcarrier grouping used for the compressed beamforming feedback matrix
- E. The size of codebook entries

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2095`）

</details>

**1.2.8-137.** What does 'Idle medium' mean in terms of EDCA channel access in a VHT or TVHT BSS? [IEEE 802.11]

- A. Idle primary channel
- B. Idle secondary channel
- C. Idle secondary 40 MHz channel
- D. Idle secondary 80 MHz channel

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2099`）

</details>

**1.2.8-138.** What is the basis for full duplex Ethernet? [IEEE 802.3]

- A. UTP cable
- B. Twisted pair
- C. MAU
- D. Patch cable

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2124`）

</details>

**1.2.8-139.** What does the RAW slot assignment procedure define? [IEEE 802.11]

- A. The number of RAW slots in a RAW
- B. The procedure for accessing the medium within a RAW
- C. The mapping function for determining the RAW slot index
- D. The position index of the AID of a STA

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2126`）

</details>

**1.2.8-140.** What are IEEE 802.11ad devices capable of?

- A. Reach 7 Gbps peak rates
- B. Reach 1 Gbps peak rates
- C. Reach 4 Gbps peak rates
- D. Reach 25 Gbps peak rates
- E. Reach 10 Gbps peak rates

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2143`）

</details>

**1.2.8-141.** What type of field does the Public Identifier URI/FQDN field contain? [IEEE 802.11]

- A. Location server
- B. FQDN
- C. URL
- D. Location object
- E. URI

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2150`）

</details>

**1.2.8-142.** What does the Channel Number field indicate? [IEEE 802.11]

- A. The channel set of the AP indicated by this BSSID
- B. The last known primary channel of the AP indicated by this BSSID
- C. The PHY type of the AP indicated by this BSSID
- D. The subelement format and ordering of subelements
- E. The reserved bits

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2161`）

</details>

**1.2.8-143.** What does the Pairnet coordinator (PRC) do when the Pairnet associated period (PAP) is over?

- A. Continues transmitting Beacons and waiting for new connections.
- B. Creates a new pairnet for other devices.
- C. Sends a Probe Request to restart the timeout timer.
- D. Sends a Disassociation Request to the PRDEV.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2205`）

</details>

**1.2.8-144.** What are the two forms of services provided by the LLC (Logical Link Control) to its users?

- A. Unacknowledged connectionless service and Acknowledged connectionless service
- B. Unacknowledged connectionless service and Connection mode services
- C. Connection mode services and Acknowledged connectionless service
- D. Connection mode services and Connection-oriented service

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2209`）

</details>

**1.2.8-145.** What are the potential benefits of integrating cellular and WiFi technologies?

- A. Reduced network capacity
- B. Increased network congestion
- C. Improved performance
- D. Limited coverage

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2224`）

</details>

**1.2.8-146.** What does the Stream Timeout subfield indicate? [IEEE 802.11]

- A. The duration of time a new STA joining the BSS can expect to be available for transmission.
- B. The percentage of time a new STA joining the BSS can expect to be available for transmission.
- C. The minimum timeout value for maintaining a variable UP in the MSCS list.
- D. The maximum time a STA needs to remain on the channel to receive a GAS response.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2229`）

</details>

**1.2.8-147.** What mechanism does Bluetooth use to avoid interference with WLAN? [Bluetooth - Overview]

- A. DCS
- B. AFH
- C. MIMO
- D. TPC

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2232`）

</details>

**1.2.8-148.** What is the definition of distribution system access function (DSAF)?

- A. A system used to interconnect a set of basic service sets (BSSs) and integrated local area networks (LANs) to create an extended service set (ESS)
- B. A function within an access point (AP) or mesh gate that uses the medium access control (MAC) service and distribution system service (DSS) to provide access between the distribution system (DS) and the wireless medium (WM)
- C. The medium or set of media used by a distribution system (DS) for communications between access points (APs), mesh gates, and the portal of an extended service set (ESS)
- D. A set of services provided by the distribution system (DS) that enable the medium access control (MAC) to transport MAC service tuples between stations (STAs) that are not in direct communication with each other over a single instance of the wireless medium (WM)
- E. Facilities mandated to satisfy requirements in some regulatory domains for radar detection and uniform channel spreading in the 5 GHz band

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2248`）

</details>

**1.2.8-149.** What does IPI stand for in the context of IEEE Std 802.11-2020?

- A. Information Processing Indicator
- B. Independent Power Indicator
- C. Intrusion Prevention Indicator
- D. Idle Power Indicator
- E. Integrated Performance Indicator

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2262`）

</details>

**1.2.8-150.** Which pair of wires is connected to pin 3 and pin 6 in the 10/100Base-T connector? [IEEE 802.3]

- A. Pair 1
- B. Pair 2
- C. Pair 3
- D. Pair 4

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2321`）

</details>

**1.2.8-151.** What is the purpose of the sub-slotting mechanisms in the IEEE 802.11ah MAC (Medium Access Control) layer?

- A. To ensure maximum channel occupancy and energy savings
- B. To reduce the number of stations competing for the channel
- C. To extend the time spent in the sleeping mode
- D. To increase the number of stations supported by the AP
- E. To divide the channel into separate frequency bands

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2330`）

</details>

**1.2.8-152.** Which IEEE standard introduced the 10Base-T technology? [IEEE 802.3]

- A. IEEE802.3d
- B. IEEE802.3e
- C. IEEE802.3i
- D. IEEE802.3j
- E. IEEE802.3u

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2333`）

</details>

**1.2.8-153.** What is a mesh link?

- A. A basic service set (BSS) that forms a self-contained network of mesh stations (STAs) that use the same mesh profile.
- B. A concatenated set of mesh links from a source mesh station (STA) to a destination mesh STA.
- C. The set of all neighbor mesh stations (STAs) of a particular mesh STA.
- D. A link from one mesh station (STA) to a neighbor mesh STA that have a mesh peering with each other.
- E. The process of selecting a mesh path.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2343`）

</details>

**1.2.8-154.** What is the purpose of coordinated beamforming (CBF) in 802.11be?

- A. To facilitate backward compatibility and product certification
- B. To increase the network throughput
- C. To suppress interference from overlapping BSSs
- D. To provide information for uplink transmissions
- E. To enhance the performance of devices in high-density scenarios

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2409`）

</details>

**1.2.8-155.** What is the condition for the TXOP holder to transmit a frame using a modulation class other than the DMG Control modulation class at the start of the TXOP? [IEEE 802.11]

- A. When the Heartbeat field in the TXOP responder's DMG Capabilities element is equal to 1
- B. When the time elapsed since the last frame received from the TXOP responder is shorter than the Heartbeat Elapsed Time value computed using the Heartbeat Elapsed Indication field
- C. When there is enough time within the CBAP
- D. When the TXOP holder is a CMMG STA

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2423`）

</details>

**1.2.8-156.** What is the purpose of autocrossing in current Ethernet ports? [IEEE 802.3]

- A. Detect the cable used and correct any crossing errors internally
- B. Enable wireless communication
- C. Switch automatically between 10Mbps and 100Mbps
- D. Support a data rate of 1000Mbps

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2451`）

</details>

**1.2.8-157.** What is the purpose of scanning in the context of 802.11 networks? [IEEE 802.11]

- A. To encrypt network traffic
- B. To establish a physical connection to the network
- C. To identify existing networks in the area
- D. To optimize network performance

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2453`）

</details>

**1.2.8-158.** What is the difference between PRP (parallel redundancy protocol) and Wi-Red?

- A. PRP is designed for industrial Ethernet networks, while Wi-Red is designed for Wi-Fi networks
- B. PRP duplicates every data packet, while Wi-Red duplicates only specific packets
- C. PRP provides seamless redundancy, while Wi-Red improves network speed and performance
- D. PRP guarantees high availability, while Wi-Red focuses on reducing latency

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2455`）

</details>

**1.2.8-159.** What is the distribution system (DS) used for?

- A. To interconnect basic service sets (BSSs) and integrated local area networks (LANs) to create an extended service set (ESS)
- B. To interconnect access points (APs) and mesh gates
- C. To transport MAC service tuples between stations (STAs) that are not in direct communication with each other
- D. To enable the medium access control (MAC) to transport MAC service tuples between APs and BSSs
- E. To enable the medium access control (MAC) to transport MAC service tuples between STAs in the same BSS

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2489`）

</details>

**1.2.8-160.** According to the IEEE Std 802.11-2020 document, how should MSDUs or A-MSDUs be passed up to the next MAC process in a non-DMG STA? [IEEE 802.11]

- A. They should be passed up in order of increasing value of the Sequence Number subfield starting with WinStartB and proceeding sequentially until there is no buffered MSDU or A-MSDU for the next sequential Sequence Number subfield value.
- B. They should be passed up in order of increasing value of the Sequence Number subfield starting with the MSDU or A-MSDU that has SN=WinStartB or if SN>WinStartB, the STA is a DMG STA.
- C. They should be passed up in order of decreasing value of the Sequence Number subfield starting with the MSDU or A-MSDU that has SN=WinStartB or if SN>WinStartB, the STA is a DMG STA.
- D. They should be passed up in reverse order, starting with the last buffered MSDU or A-MSDU and ending with the first one.
- E. They should be passed up in random order, depending on the order in which they were stored in the buffer.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2493`）

</details>

**1.2.8-161.** What does the TWT wake interval in a TWT element transmitted by a TWT requesting STA represent? [IEEE 802.11]

- A. The average time between successive TWT SPs for the requesting STA
- B. The average time between successive TWT SPs for the responding STA
- C. The total time of TWT SPs for the requesting STA
- D. The total time of TWT SPs for the responding STA
- E. The average time between successive TWT SPs for both the requesting and responding STAs

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2494`）

</details>

**1.2.8-162.** What is the advantage of a multicluster network structure? [IEEE 802.15.4]

- A. Improved synchronization services
- B. Reduced message latency
- C. Decreased communication flow
- D. Increased coverage area

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2495`）

</details>

**1.2.8-163.** What was the primary purpose for developing the IEEE802.3af Power over Ethernet (PoE) standard? [IEEE 802.3]

- A. To transmit data and power over the same Ethernet cable
- B. To improve network security
- C. To increase data transmission speeds
- D. To reduce network latency

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2496`）

</details>

**1.2.8-164.** What is another term for Link Aggregation? [IEEE 802.3]

- A. Topology detection
- B. Authentication
- C. Spanning tree
- D. Trunking
- E. EAP

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2507`）

</details>

**1.2.8-165.** What allows a station to synchronize its hopping pattern when joining an 802.11 frequency-hopping network? [IEEE 802.11]

- A. Hop pattern number
- B. Hop index
- C. Timestamp field
- D. Beacon frames

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2515`）

</details>

**1.2.8-166.** Which authentication method requires both stations to implement WEP? [IEEE 802.11]

- A. Open-system authentication
- B. Shared-key authentication
- C. MAC address filtering
- D. No authentication is required

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2557`）

</details>

**1.2.8-167.** What does the Next TWT Request subfield indicate when set to 1? [IEEE 802.11]

- A. The TWT Information frame does not contain a Next TWT field.
- B. The TWT Information frame is not a request for the delivery of a TWT Information frame containing a nonzero length Next TWT field.
- C. The TWT Information frame is a request for the delivery of a TWT Information frame.
- D. The TWT Information frame is not a request for the delivery of a TWT Information frame.
- E. The TWT Information frame is a request for the delivery of a TWT Information frame containing a nonzero length Next TWT field.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2561`）

</details>

**1.2.8-168.** What is the advantage of static VLANs over dynamic VLANs? [IEEE 802.3]

- A. Provides optimal network redundancy
- B. Automatic membership based on user's address
- C. Can handle network errors
- D. Requires special hardware
- E. Easy to configure

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2571`）

</details>

**1.2.8-169.** What pins are used for bi-directional data transmission in Gigabit Ethernet? [IEEE 802.3]

- A. Pin 5 and 6
- B. Pin 1 and 2
- C. Pin 3 and 6
- D. Pin 7 and 8

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2579`）

</details>

**1.2.8-170.** Which protocol provides a compaction and fragmentation mechanism to efficiently transport IPv6 (Internet Protocol version 6) packets in IEEE 802.15.4 frames?

- A. RPL
- B. 6TiSCH
- C. WirelessHART
- D. 6LoWPAN
- E. IEEE 802.11

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2582`）

</details>

**1.2.8-171.** What is the purpose of the DMG link adaptation? [IEEE 802.11]

- A. To request a link measurement report from a STA
- B. To transmit frames to a specific STA
- C. To aggregate link measurement request frames
- D. To perform measurement on received frames

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2599`）

</details>

**1.2.8-172.** What is the definition of beamforming in the context of IEEE Std 802.11-2020?

- A. A station that receives a physical layer protocol data unit transmitted using a beamforming steering matrix
- B. A station that transmits a physical layer protocol data unit using a beamforming steering matrix
- C. A matrix determined using knowledge of the channel between a transmitter and an intended receiver that maps from space-time streams to transmit antennas with the goal of improving signal power or signal-to-noise ratio
- D. A group address that specifies all stations
- E. A spatial filtering mechanism used at a transmitter to improve the received signal power or signal-to-noise ratio at an intended receiver

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2612`）

</details>

**1.2.8-173.** What is a collision domain? [IEEE 802.3]

- A. A common transmission medium
- B. A station that is sending data
- C. A segment where a collision occurs
- D. A random period of time before making a new attempt
- E. An 'idle period' on the network

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2622`）

</details>

**1.2.8-174.** How are the fragments of a single MSDU or MMPDU transmitted? [IEEE 802.11]

- A. Sent as individual frames using the DCF
- B. Sent as a burst in an EDCA or HCCA TXOP
- C. Sent as a group addressed message into the BSS
- D. Sent as a four-address frame using STBC
- E. Sent as a non-STBC frame with Normal Ack ack policy

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2643`）

</details>

**1.2.8-175.** What does a station do in the passive scanning procedure? [IEEE 802.11]

- A. Transmits Probe Request frames
- B. Sweeps from channel to channel and records information from any Beacons received
- C. Buffers Beacon frames to extract information about the BSS that sent them
- D. Waits for Probe Response frames from networks with a given name
- E. Transmits Beacon frames to allow stations to find out everything they need to match parameters with the BSS

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2649`）

</details>

**1.2.8-176.** What happens to a non-DMG STA that receives a CF-End frame? [IEEE 802.11]

- A. It resets its NAV and can start contending for the medium without further delay.
- B. It waits for a specific time interval before contending for the medium.
- C. It starts transmitting immediately upon receiving the CF-End frame.
- D. It discards the CF-End frame and does not contend for the medium.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2659`）

</details>

**1.2.8-177.** What is the clock rate for 10Base-T? [IEEE 802.3]

- A. 10MHz
- B. 100MHz
- C. 125MHz
- D. 1000MHz

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2678`）

</details>

**1.2.8-178.** How long is the slot time in the DS PHY? [IEEE 802.11]

- A. 10µs
- B. 20µs
- C. 31 slots
- D. 48µs
- E. 1,023 slots

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2698`）

</details>

頁次：[1](1-2-gsma-1.md)　[2](1-2-gsma-2.md)　[3](1-2-gsma-3.md)　**4**　[5](1-2-gsma-5.md)　[6](1-2-gsma-6.md)　[7](1-2-gsma-7.md)
