# 1.7 網路優化與終端　GSMA 練習題（173 題）

所屬：[1.7 網路優化與終端](1-7.md)

只收 GSMA 訓練題；不含驗證集與測試集，並已去除和驗證／測試題相同或相似、重複、標註衝突的題目。題目依小節歸類（抽查正確率約 95%）。

## 1.7.1 涵蓋與涵蓋容量優化（CCO）（8 題）

**1.7.1-1.** What function in NG-RAN supports the positioning functionality? [3GPP Release 17]

- A. RACH Optimization Function
- B. PCI Optimization Function
- C. Support of dynamic PTP and PTM switching
- D. Support for CCO
- E. Support for NR MBS

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6727`）

</details>

**1.7.1-2.** What is the tradeoff between coverage and capacity in conventional direct transmission systems?

- A. As the coverage decreases, the capacity increases
- B. As the coverage increases, the capacity decreases
- C. Increasing coverage does not affect capacity
- D. Decreasing coverage does not affect capacity

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2388`）

</details>

**1.7.1-3.** What is the coverage probability?

- A. The probability that there are no satellites in the spherical cap at the intersection of the spherical surface and the cone
- B. The probability that the SINR is larger than a predetermined acceptable threshold
- C. The probability that the user is covered by both the satellite-GW link and the GW-user link
- D. The probability that the signal is not affected by any interference and noise in transmission

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3228`）

</details>

**1.7.1-4.** Which deployment scenario may require coverage recovery for Message 2 in the DL (downlink)?

- A. Rural
- B. Urban micro
- C. Urban macro
- D. Indoor
- E. All of the above

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3902`）

</details>

**1.7.1-5.** What is the purpose of the NR Coverage and Capacity Optimization (CCO) function? [3GPP Release 17]

- A. To detect and mitigate coverage and cell edge interference issues
- B. To enable inter-system load balancing
- C. To optimize 2-step RACH procedure
- D. To enhance mobility optimization

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4614`）

</details>

**1.7.1-6.** What determines the coverage of a cell in wireless communication?

- A. Transmit power
- B. Received power
- C. Attenuation with distance
- D. Density of obstacles
- E. Number of mobiles in the cell

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6015`）

</details>

**1.7.1-7.** What is one of the challenges in providing indoor connectivity with 5G cellular networks?

- A. Lack of high data rate
- B. Lack of reliable connectivity
- C. Lack of low latency
- D. Lack of spectral efficiency
- E. Difficulty in penetrating dielectric materials

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6377`）

</details>

**1.7.1-8.** What is the definition of a coverage area?

- A. An area where mobile cellular services are provided by that mobile cellular system
- B. A data stream resulting from encoding and multiplexing of one or several transport channels
- C. The combined losses of all transmission system components between the transmitter output and the antenna input
- D. A logical association between several users
- E. A link between the card and the external world starting and ending with a reset or a deactivation of the card

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6550`）

</details>

## 1.7.2 干擾管理：遠端干擾（RIM）與交叉鏈路干擾（CLI）（20 題）

**1.7.2-1.** What kind of coordination communication is used in the RIM frameworks? [3GPP Release 18]

- A. Wireless communication
- B. Backhaul communication
- C. Core network communication
- D. Satellite communication
- E. Fiber optic communication

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-745`）

</details>

**1.7.2-2.** What does Layer 3 filtering apply to in CLI measurement results? [3GPP Release 18]

- A. TDD DL-UL configurations
- B. Signal strengths
- C. Aggressor UE(s)
- D. RSSI resources
- E. CLI measurement results

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4628`）

</details>

**1.7.2-3.** What are the two types of CLI measurements? [3GPP Release 18]

- A. SRS-RSRP measurement and CLI-ULI measurement
- B. CLI-RSSI measurement and SRS-CSI measurement
- C. RSRP measurement and RSSI measurement
- D. SRS-RSRP measurement and CLI-RSSI measurement
- E. ULI measurement and CSI measurement

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3615`）

</details>

**1.7.2-4.** What is the term for the interference between UL transmission in one cell and DL reception in another cell? [3GPP Release 18]

- A. Remote interference
- B. Backhaul-based interference
- C. CLI interference
- D. RIM interference
- E. Semi-static interference

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-483`）

</details>

**1.7.2-5.** What does coordination in UDNs involve?

- A. Association of each UE with the nearest AN
- B. Tuning of power and multiple-antenna precoder
- C. Allocation of AN-UE pairs into orthogonal time-frequency resource blocks
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2082`）

</details>

**1.7.2-6.** What are the classic techniques to enhance system performance in multi-tier networks?

- A. Optimizing cell associations and transmit powers
- B. Maximizing spectral efficiency
- C. Minimizing power consumption
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2482`）

</details>

**1.7.2-7.** What is the purpose of the almost-blank subframe (ABS) feature in LTE Rel-10?

- A. To improve security between LTE and Wi-Fi
- B. To increase LTE coverage area
- C. To provide better coordination between macro-cells and small-cells
- D. To improve LTE mobility management
- E. To enhance LTE carrier aggregation

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2573`）

</details>

**1.7.2-8.** What are the key challenges for interference management in 5G multi-tier networks?

- A. Heterogeneity and dense deployment of wireless devices
- B. Coverage and traffic load imbalance
- C. Public or private access restrictions
- D. Carrier aggregation and cooperation among BSs
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-3408`）

</details>

**1.7.2-9.** What is one of the major factors that limits the system performance in traditional communication networks?

- A. Information decoding
- B. Strong interference
- C. Energy harvesting
- D. RF-to-DC conversion loss
- E. Co-channel interference

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-3809`）

</details>

**1.7.2-10.** What is the nature of co-channel interference (CCI)?

- A. Interference caused by multiple transmissions taking place on orthogonal channels.
- B. Interference caused by multiple transmissions taking place on mutually non-orthogonal channels.
- C. Interference caused by multiple transmissions taking place on unrelated channels.
- D. Interference caused by multiple transmissions taking place on orthogonal channels.
- E. Interference caused by multiple transmissions taking place on partially orthogonal channels.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3953`）

</details>

**1.7.2-11.** What are the two categories of interference suppression techniques in F-RANs?

- A. Centralized and distributed precoding
- B. Global and local scheduling
- C. Coordinated precoding and coordinated scheduling
- D. Massive MIMO and cooperative MIMO

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4256`）

</details>

**1.7.2-12.** What is the purpose of S-FFR in LS-CRRM?

- A. To improve capacity and extend coverage
- B. To reduce interference and improve signal strength
- C. To optimize resource allocation and management
- D. To enhance QoS for different user types

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4765`）

</details>

**1.7.2-13.** What is the main difference between interference control in single source-destination pair scenarios and multi-source multi-destination scenarios?

- A. Interference collaboration and coordination
- B. Antenna selection and interference alignment
- C. Power transfer and beamforming
- D. Co-channel interference mitigation and user scheduling

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4922`）

</details>

**1.7.2-14.** What is the technique used in traditional OFDMA heterogeneous networks to avoid cross-tier interference?

- A. Subcarrier allocation to different users
- B. Precoding technique and resource management
- C. Successive interference cancelation (SIC)
- D. Frequency band sharing between macrocell and small cells

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5991`）

</details>

**1.7.2-15.** Which interference mitigation technique can convert harmful line-of-sight BS (Base Station) interferers into useful signal contributors?

- A. UAV location and flight plan knowledge
- B. Enhancement of existing report mechanisms
- C. Full dimension MIMO (FD-MIMO) multi-antenna BSs
- D. UAVs with directional antennas and beamforming capabilities
- E. Cooperative multipoint (CoMP)

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6153`）

</details>

**1.7.2-16.** How does increased network density affect coverage and interference in interference-limited networks?

- A. Increases both coverage and interference
- B. Decreases coverage and increases interference
- C. Increases coverage and decreases interference
- D. Decreases both coverage and interference
- E. No impact on coverage and interference

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6771`）

</details>

**1.7.2-17.** What is the purpose of the Remote Interference Management (RIM) function? [3GPP Release 17]

- A. To detect and mitigate coverage and cell edge interference issues.
- B. To optimize the Physical Random Access Channel (PRACH) configuration.
- C. To manage cross-link interference in non-split gNB architecture.
- D. To support radio access network sharing.
- E. To support positioning functionality.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6871`）

</details>

**1.7.2-18.** What is the purpose of interference avoidance in a network?

- A. To minimize the backhaul capacity
- B. To maximize the number of co-channel transmitters
- C. To improve the long-term system throughput
- D. To increase the delay in information sharing
- E. To reduce the interference estimation accuracy

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7838`）

</details>

**1.7.2-19.** In a remote interference scenario, how are victim and aggressor gNBs grouped? [3GPP Release 18]

- A. By their geographical locations
- B. By their signal strengths
- C. By their set IDs
- D. By their TDD DL-UL configurations
- E. By their atmospheric conditions

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7878`）

</details>

**1.7.2-20.** What are some alternative terms for co-channel interference (CCI)?

- A. ISI, ICI, IAI, MUI, MAI, MSI
- B. ISI, ICI, IAI, MUI, MAI
- C. AFI, BCI, FDI, IDI, MDI
- D. ISI, ICI, MUI, MAI
- E. None of the above.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7950`）

</details>

## 1.7.3 換手與移動性管理（32 題）

**1.7.3-1.** What does the eNodeB use the selected core network information for? [3GPP Release 17]

- A. To indicate the PLMN-index to the SGSN
- B. To transmit in broadcast system information
- C. To indicate the PLMN-id to the MME
- D. To select target cells for future handovers
- E. To select the GERAN/UTRAN target network

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3531`）

</details>

**1.7.3-2.** What is the main role of the DeNB in the mobility of a UE to or from an RN? [3GPP Release 17]

- A. To trigger the S1 or X2 handover procedure for the UE
- B. To provide GUMMEI information to the RN
- C. To update the cell information of the RN
- D. To transfer neighbouring information to the RN
- E. To initiate the RRC connection establishment for the UE

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-571`）

</details>

**1.7.3-3.** What is the inter RAT mobility characteristic of handover from E-UTRA to NR? [3GPP Release 17]

- A. Radio resources are prepared in the source RAT before the handover
- B. In-sequence and lossless handover is supported
- C. Both Xn and NG based inter-RAT handover are not supported
- D. The source RAT configures Target RAT measurement and reporting
- E. Inter RAT measurements are limited to E-UTRA

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3099`）

</details>

**1.7.3-4.** What is the definition of 'Late Data Forwarding'?

- A. Data forwarding that is initiated before the UE executes the handover.
- B. Initiation of data forwarding after the source NG-RAN node knows that the UE has successfully accessed a target NG-RAN node.
- C. An identifier used during SNPN selection to enhance the likelihood of selecting a preferred SNPN.
- D. A PLMN cell broadcasting at least one Closed Access Group identity.
- E. A type of UE-to-Network transmission path where data is transmitted between a UE and the network without sidelink relaying.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6696`）

</details>

**1.7.3-5.** What are the two main procedures in mobility management?

- A. Location registration and handover management
- B. Control plane and user plane
- C. SDN and RAN
- D. Core cloud and edge cloud
- E. Multi-RAT and SDWN

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7585`）

</details>

**1.7.3-6.** What is the definition of service continuity?

- A. A service area solely relying on infrastructures and positioning technologies present anywhere 5G is present
- B. A network deployment that does not interact with a public network
- C. The uninterrupted user experience of a service during an access change
- D. A dedicated network slice deployment for a specific third-party
- E. The time taken to transfer a given piece of information from a source to a destination

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-945`）

</details>

**1.7.3-7.** What is the purpose of service continuity in the Evolved Packet System? [3GPP Release 17]

- A. To optimize routing for user plane traffic
- B. To support mobility within and across access systems
- C. To minimize packet loss during inter- and/or intra-access technology changes
- D. To provide continuous service during and following changes of access systems
- E. To support simultaneous usage of multiple accesses

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-962`）

</details>

**1.7.3-8.** What RRC message is received by the gNB-CU when a UE performs an Intra gNB-DU Inter Cell handover?

- A. RRC Release
- B. RRC Reconfiguration Complete
- C. RRC Resume Complete
- D. RRC Connection Re-establishment

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-191`）

</details>

**1.7.3-9.** What is the focus of the scenario described in the provided context?

- A. Verifying successful inter-O-DU handover within an O-CU with multiple PDU sessions.
- B. Examining the impact of different Quality of Service (QoS) parameters on handover performance.
- C. Testing the admission control mechanism for PDU sessions at the target DU.
- D. Evaluating the performance of multiple QFI configurations for PDU sessions.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-415`）

</details>

**1.7.3-10.** What is the purpose of handover in a cellular system?

- A. To assign a vacant voice channel to a mobile unit
- B. To change frequency for communication between a mobile unit and a new cell site
- C. To transmit voice and data messages on the voice radio channel
- D. To provide continuous positive supervision for the speech transmission

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-198`）

</details>

**1.7.3-11.** What is the main problem with densely deployed devices with ultra-high mobility?

- A. High number of sidelobes in a 3D pattern
- B. High load from a mobility management perspective
- C. Substantial delay from handoffs
- D. Lack of contiguous coverage probability
- E. Low antenna gain cross-sections

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-464`）

</details>

**1.7.3-12.** What is the purpose of the Make-Before-Break solution? [3GPP Release 14]

- A. To minimize the mobility interruption including handover and SeNB change
- B. To reduce the grant request delay in the UL
- C. To improve the DL beamforming performance
- D. To increase the latency reduction gains
- E. None of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-739`）

</details>

**1.7.3-13.** What is the definition of an intracell handover?

- A. A handover within one sector or between different sectors of the same cell
- B. A handover between different PLMNs
- C. A handover between different cells
- D. A handover within the same network
- E. A handover between networks using different radiosystems

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1919`）

</details>

**1.7.3-14.** What is the main idea of the low complexity handover scheme?

- A. Allow high speed macrocell users to handover to the small cell
- B. Allow low speed users to handover to the small cell
- C. Allow real-time service users to handover to the small cell
- D. Allow non-real-time service users to handover to the small cell

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2098`）

</details>

**1.7.3-15.** What is essential in the scenario of HCSNet (Heterogeneous cloud small cell network) with high mobility users?

- A. BBU pools
- B. Small cells
- C. Handover management
- D. MRRHs
- E. SRRHs

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3537`）

</details>

**1.7.3-16.** What is an Active Set in the context of a communication service between an UE and a UTRAN?

- A. The ratio of the average power centered on the assigned channel frequency to the average power centered on an adjacent channel frequency
- B. A list of forbidden PLMNs in the UE
- C. A set of security attributes associated with a file
- D. A performance criterion that describes the degree of correctness with which a function is performed
- E. A set of radio links involved in a specific communication service

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-3731`）

</details>

**1.7.3-17.** Which measurements are performed for intra- and inter-frequency handover? [3GPP Release 17]

- A. Inter-RAT handover measurements
- B. Radio characteristics measurements
- C. Timing measurements
- D. Measurements for RRM
- E. Measurements for positioning

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4067`）

</details>

**1.7.3-18.** What is the definition of an Intra PLMN handover?

- A. A handover between different PLMNs, regardless of the radio access system.
- B. A handover between different cells within the same network.
- C. A handover between networks using different radio systems.
- D. A handover between different sectors of the same cell.
- E. A handover within the same network, regardless of the radio access system.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4255`）

</details>

**1.7.3-19.** When is handover necessary?

- A. When there is interference
- B. When there is delay
- C. When the user moves between cells
- D. When there is a tracking error
- E. When the signal strength is low

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4498`）

</details>

**1.7.3-20.** What is an inter PLMN handover?

- A. A handover between different cells
- B. A handover between different PLMNs
- C. A handover within one sector or between different sectors of the same cell
- D. A handover between networks using different radiosystems
- E. A handover within the same network

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4706`）

</details>

**1.7.3-21.** What is the definition of Soft Handover?

- A. Handover with continuous monitoring of different network cells
- B. Handover with the merging of multiple radio links
- C. Handover without interruption of the radio connection
- D. Handover with complete loss of the radio connection
- E. Handover without perceptible interruption of the radio connection

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4738`）

</details>

**1.7.3-22.** What is the definition of an Intercell handover?

- A. A handover between different cells that requires network connections to be altered
- B. A handover within one sector or between different sectors of the same cell
- C. A handover between networks using different radiosystems
- D. A handover between different PLMNs

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4753`）

</details>

**1.7.3-23.** What is a Hard Handover?

- A. A handover procedure that occurs between cells with different characteristics
- B. A handover procedure that smoothly transitions the user's connection from one channel to another
- C. A handover procedure that involves abandoning old radio links before establishing new ones
- D. A handover procedure that is managed by the Home Environment
- E. A handover procedure that is performed by the radio access network

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5161`）

</details>

**1.7.3-24.** What does the source RAT do in inter-RAT handover? [3GPP Release 18]

- A. Configures Target RAT measurement
- B. Decides on the preparation initiation
- C. Provides necessary information to the target RAT
- D. Prepares radio resources in the target RAT
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5213`）

</details>

**1.7.3-25.** What is the definition of Handover?

- A. The process of changing the core network connection of a UE.
- B. The process of allocating radio resources to a UE in a cell.
- C. The process of checking whether a UE is a member of a hybrid cell.
- D. The process of selecting a serving cell for a UE during a handover procedure.
- E. The process of changing the serving cell of a UE in RRC_CONNECTED.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5489`）

</details>

**1.7.3-26.** What are the RRM requirements enhancements introduced in Rel-16 for connected mode at a velocity of 500km/h? [3GPP Release 16]

- A. Reduced cell identification delay
- B. Reduced cell detection delay
- C. Reduced measurement period
- D. Enhanced UL timing adjustment
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5658`）

</details>

**1.7.3-27.** What is the primary issue related to user mobility in HetNets (heterogeneous networks)?

- A. Higher interference
- B. Reduced coverage
- C. Frequent handovers
- D. Lower throughput
- E. Unbalanced load

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6035`）

</details>

**1.7.3-28.** What is the mobility management approach in cases of low mobility?

- A. VM migration
- B. New communication path selection
- C. Power control at the SCeNBs/eNBs side
- D. Data replication

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6065`）

</details>

**1.7.3-29.** What is the purpose of the handover to NR procedure? [3GPP Release 17]

- A. To establish SRBs and DRBs in another RAT
- B. To move a UE in RRC_CONNECTED to a cell using another RAT
- C. To transfer a connection between the UE and another RAN to NR
- D. To activate ciphering in E-UTRA
- E. To re-establish radio resources in NR

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6159`）

</details>

**1.7.3-30.** What is an inter system change?

- A. A change of radio access between different radio access technologies
- B. A change of radio access within the same network
- C. A change of radio access within one sector or between different sectors of the same cell
- D. A change of radio access between different PLMNs
- E. A change of radio access between different cells

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6352`）

</details>

**1.7.3-31.** What causes the UE to fail the mobility from NR procedure? [3GPP Release 17]

- A. A failure to establish the connection to the target radio access technology
- B. A protocol error in the inter RAT information
- C. An emergency services fallback indication
- D. An ongoing emergency call with no suitable E-UTRA cell available
- E. An inter-RAT measurement reporting failure

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6876`）

</details>

**1.7.3-32.** What is soft handoff in CDMA (Code Division Multiple Access) systems?

- A. The ability for a user to receive or transmit signals to two or more base-stations
- B. The ability to switch between different cell frequencies
- C. The ability for users to directly communicate with each other
- D. The ability to allocate different time slots to different users

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7116`）

</details>

## 1.7.4 容量與負載平衡（29 題）

**1.7.4-1.** What are the ThreshServingOffloadWLAN parameters used for? [3GPP Release 17]

- A. To specify the WLAN channel utilization threshold.
- B. To define the RSRP threshold for traffic steering from WLAN to E-UTRAN.
- C. To specify the WLAN RSSI threshold in dB.
- D. To determine the timer value for traffic steering between E-UTRAN and WLAN.
- E. To define the RSRP threshold for traffic steering from E-UTRAN to WLAN.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-425`）

</details>

**1.7.4-2.** Which conditions must be satisfied for traffic steering from E-UTRAN to WLAN? [3GPP Release 17]

- A. RSRPmeas < ThreshServingOffloadWLAN, LowP and ChannelUtilizationWLAN < ThreshChUtilWLAN, Low
- B. RSRQmeas < ThreshServingOffloadWLAN, LowQ and BackhaulRateDlWLAN > ThreshBackhRateDLWLAN, High
- C. RSRPmeas > ThreshServingOffloadWLAN, HighP and BackhaulRateUlWLAN > ThreshBackhRateULWLAN, High
- D. ChannelUtilizationWLAN > ThreshChUtilWLAN, High and WLANRSSI < ThreshWLANRSSI, Low
- E. RSRPmeas < ThreshServingOffloadWLAN, LowP and WLANRSSI > ThreshWLANRSSI, High

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-880`）

</details>

**1.7.4-3.** What is the purpose of Extended Access Barring? [3GPP Release 18]

- A. To prevent overload of the access network and/or the core network
- B. To control access to network provided services or functions
- C. To allow/prevent new access attempts from particular applications
- D. To differentiate between CS and PS domains
- E. To specify the categories of subscribers who are barred from network access

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2261`）

</details>

**1.7.4-4.** Under high network load conditions, how does the network protect itself? [3GPP Release 18]

- A. By restricting access attempts from UEs
- B. By increasing resource allocation
- C. By encrypting all data traffic
- D. By prioritizing certain services
- E. By disabling identification and authentication

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2685`）

</details>

**1.7.4-5.** What short-term traffic load variations are a function of?

- A. The number of active user equipments
- B. The interference
- C. The number of active user equipments and the interference
- D. The traffic types

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7094`）

</details>

**1.7.4-6.** Which component of an O-RAN architecture is responsible for managing the radio resources and optimizing network performance?

- A. O-CU-CP
- B. O-RU
- C. RRM
- D. O-DU

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-931`）

</details>

**1.7.4-7.** Which of the following is NOT a type of measurement data required for traffic steering in Open Radio Access Networks (O-RAN)?

- A. Measurement reports with RSRP/RSRQ/CQI information.
- B. UE connection and mobility/handover statistics.
- C. Cell load statistics such as number of active users.
- D. User equipment (UE) location information based on GPS coordinates.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1037`）

</details>

**1.7.4-8.** What is the primary benefit of applying admission control in an O-RAN network?

- A. To prevent network congestion by limiting traffic from applications that exceed their agreed-upon usage.
- B. To improve the overall network performance by prioritizing high-priority traffic.
- C. To ensure that all applications have equal access to network resources.
- D. To enable network operators to charge different rates for different types of traffic.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1121`）

</details>

**1.7.4-9.** What is the primary performance metric employed for user association analysis in HetNets (heterogeneous networks)?

- A. Throughput
- B. Latency
- C. Outage/coverage probability
- D. Energy efficiency
- E. SINR

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7184`）

</details>

**1.7.4-10.** How can radio resource allocation approaches be classified?

- A. Centralized and decentralized
- B. Optimization-based, heuristic, game-theoretic, or machine learning based
- C. Throughput, latency, fairness, energy-efficiency, and spectral-efficiency
- D. All of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-307`）

</details>

**1.7.4-11.** What is the trade-off between network load balancing and network throughput in biased user association?

- A. Decreased network load balancing, decreased network throughput
- B. Decreased network load balancing, increased network throughput
- C. Increased network load balancing, increased network throughput
- D. Increased network load balancing, decreased network throughput
- E. No trade-off

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-710`）

</details>

**1.7.4-12.** What is the drawback of biased user association in HetNets (heterogeneous networks)?

- A. Reduced coverage
- B. Increased interference
- C. Lower throughput
- D. Higher latency
- E. Unbalanced load

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1396`）

</details>

**1.7.4-13.** What are the three different control mechanisms for user association algorithms in 5G networks?

- A. Centralized control, Distributed control, and Hybrid control
- B. Grid model, Random spatial model, and Combinatorial optimization
- C. Outage/coverage probability, Spectrum efficiency, and Energy efficiency
- D. Game theory, Combinatorial optimization, and Stochastic geometry
- E. HetNets, Massive MIMO Networks, and MmWave Networks

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1467`）

</details>

**1.7.4-14.** What is a key advantage of heterogenous networks (HetNets) compared to massive MIMO networks?

- A. Lower interference coordination
- B. Higher array gains
- C. Lower signal attenuation
- D. Higher channel coherence times
- E. Lower power consumption per small cell access point

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1644`）

</details>

**1.7.4-15.** Which performance criterion is used to minimize cell congestion in the Evolved Packet System? [3GPP Release 17]

- A. Reduced network complexity
- B. Steering of roaming methods
- C. Mixed traffic support
- D. Enhanced load balancing

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1815`）

</details>

**1.7.4-16.** What is the benefit of using a heterogeneous small cell network?

- A. Improving the coverage and capacity of cell-edge users and hotspot
- B. Reducing the capital expenditure (CAPEX) and operating expenditure (OPEX)
- C. Lowering the number of BBUs in densely deployed heterogeneous small cell network
- D. Mitigating interference and improving spectrum efficiency
- E. Reducing the consumed power

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1920`）

</details>

**1.7.4-17.** What is the effect of increasing the number of antennas at the macro BS (base station) in HetNets (heterogeneous networks)?

- A. Increases the fairness
- B. Decreases the probability of association with the macro BS
- C. Increases the spectrum efficiency
- D. Decreases the spectrum efficiency
- E. Increases the probability of association with the macro BS

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2158`）

</details>

**1.7.4-18.** What is the advantage of using small cells?

- A. Improved coverage and capacity
- B. Higher frequency band availability
- C. Reduced interference
- D. Lower power consumption
- E. Better signal-to-noise ratio

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2448`）

</details>

**1.7.4-19.** What is the purpose of deploying small cell networks?

- A. To increase coverage and boost network capacity
- B. To reduce mobile data traffic
- C. To decrease the share of social networking traffic
- D. To lower the cost of bringing contents closer to users
- E. To improve the quality of service for multimedia streaming

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2512`）

</details>

**1.7.4-20.** What is the main purpose of using small cells?

- A. Reducing the capital expenditure (CAPEX) and operating expenditure (OPEX)
- B. Improving the coverage and capacity of cell-edge users and hotspot
- C. Mitigating interference and improving spectrum efficiency
- D. Lowering the number of BBUs in densely deployed heterogeneous small cell network
- E. Reducing the consumed power

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3045`）

</details>

**1.7.4-21.** Why is underload also considered a problem in a network?

- A. Underload is not a problem, only overload is
- B. Underload can result in traffic surges during major events
- C. Underload can cause delays in web-based applications
- D. Underload can lead to network congestion
- E. Underload can lead to inefficient utilization of network capacity

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-3345`）

</details>

**1.7.4-22.** What is the advantage of network densification in ultra dense networks (UDNs)?

- A. Reduced system capacity
- B. Increased interference
- C. Decreased signal power from serving ANs
- D. Improved propagation conditions

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3397`）

</details>

**1.7.4-23.** What benefits can be achieved by leveraging small cell network deployments?

- A. Optimizing reactive networks
- B. Analyzing user's traffic and caching content locally
- C. Predicting future events in an intelligent manner
- D. Exploiting users' social relationships and ties
- E. Improving network resource management

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-3620`）

</details>

**1.7.4-24.** Which of the following cell association schemes aims to balance the traffic load in multi-tier networks?

- A. RSRP-based scheme
- B. Bias-based Cell Range Expansion (CRE)
- C. Association based on Almost Blank Sub-frame (ABS) ratio
- D. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3927`）

</details>

**1.7.4-25.** What is the main problem faced by mobile operators due to the proliferation of mobile devices?

- A. Lack of coverage
- B. Network congestion
- C. Insufficient network capacity
- D. Lack of interference management mechanisms
- E. Inability to integrate different radio access technologies

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4041`）

</details>

**1.7.4-26.** What is the densification ratio defined as?

- A. Per-user rate divided by density of ANs
- B. Density of UEs divided by density of ANs
- C. Density of ANs divided by density of UEs
- D. Per-user rate divided by density of UEs

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5447`）

</details>

**1.7.4-27.** What is the main purpose of deploying small base stations?

- A. To increase mobile data traffic
- B. To reduce infrastructure logs
- C. To improve the quality of service
- D. To boost network capacity
- E. To decrease the cost of installation

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5681`）

</details>

**1.7.4-28.** What is the purpose of cell densification in the hotspot tier of a cellular network?

- A. To increase the number of BSs and bandwidth
- B. To reduce the average inter-BS distance
- C. To improve the coverage in high mobility areas
- D. To utilize mmWave bands efficiently
- E. Not mentioned in the document

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7275`）

</details>

**1.7.4-29.** What are the five branches of the taxonomy developed for user association algorithms in 5G networks?

- A. HetNets, Massive MIMO Networks, MmWave Networks, Energy Harvesting Networks, and Other 5G Candidate Technologies
- B. Scope, Metrics, Topology, Control, and Model
- C. Conventional MIMO, Centralized Control, Spectrum Efficiency, Fairness, and Cloud Radio Access Networks
- D. Grid model, Random spatial model, Outage/coverage probability, QoS, and Hybrid control
- E. Picocells, Femtocells, Relays, SONs, and D2D communication

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7798`）

</details>

## 1.7.5 終端能力與類別（28 題）

**1.7.5-1.** What is required for SRS bandwidth aggregation from RRM perspective? [3GPP Release 18]

- A. Different numerology for different carriers to be aggregated.
- B. Same slot and symbol for SRS resources from different carriers to be aggregated.
- C. Different TRP for SRS resources from different carriers to be aggregated.
- D. Different Antenna Reference Point (ARP) for SRS resources from different carriers to be aggregated.
- E. Different bandwidths for SRS resources from different carriers to be aggregated.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2003`）

</details>

**1.7.5-2.** In what frequency range should RedCap (reduced capability) be deployable?

- A. 4 to 7.1 GHz
- B. 4 to 5 GHz
- C. 5 to 10 GHz
- D. 10 to 20 GHz
- E. 20 to 40 GHz

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2357`）

</details>

**1.7.5-3.** Which frequency range does RedCap (reduced capability) support for deployment?

- A. Frequency range 1 (FR1) and frequency range 2 (FR2)
- B. Frequency range 2 (FR2) only
- C. Frequency range 1 (FR1) only
- D. Frequency range 3 (FR3) only

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3127`）

</details>

**1.7.5-4.** Can a UE disable use of one or more of its radio technologies, regardless of PLMNs? [3GPP Release 18]

- A. Yes
- B. No

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4834`）

</details>

**1.7.5-5.** Where is the UE Radio Capability ID signaled by the UE? [3GPP Release 16]

- A. Over Uu interface between the UE and the CN
- B. Within the RAN in handover procedures
- C. Within the CN
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-291`）

</details>

**1.7.5-6.** How is the indication of reduced capabilities provided during the random-access procedure?

- A. In Message 1
- B. In Message 2
- C. In Message 3 (or Message A)
- D. In Message 4
- E. In PUCCH

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-870`）

</details>

**1.7.5-7.** What is the purpose of the UE Capability Retrieval framework? [3GPP Release 18]

- A. To report the UE's radio access capabilities to the network
- B. To request specific capabilities from the network
- C. To optimize the UE's power consumption
- D. To enable sidelink communication
- E. All of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1190`）

</details>

**1.7.5-8.** What is the purpose of UE radio capability signalling optimization? [3GPP Release 16]

- A. To increase the size of UE radio capabilities
- B. To efficiently signal UE radio capability information
- C. To reduce the number of supported bands
- D. To implement new RAN interfaces

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1698`）

</details>

**1.7.5-9.** When does the gNB request the UE UTRA-FDD capabilities? [3GPP Release 18]

- A. During NAS signalling
- B. Before handover to UTRAN
- C. When responding to the gNB
- D. When the capabilities are the same
- E. During NR capabilities request

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2097`）

</details>

**1.7.5-10.** What is the purpose of providing an ID in NAS signalling that represents a UE's radio capabilities? [3GPP Release 18]

- A. To assign UE capabilities by the manufacturer
- B. To reduce signalling overhead
- C. To store UE Radio Capabilities in the AMF
- D. To request UE capabilities for NR, EUTRA, UTRA-FDD
- E. To support intra-band non-contiguous CA

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3063`）

</details>

**1.7.5-11.** Which message is used to transfer UE radio access capabilities? [3GPP Release 17]

- A. MeasurementReportSidelink
- B. UECapabilityEnquirySidelink
- C. UECapabilityInformationSidelink
- D. RRCReconfigurationSidelink
- E. RRCReconfigurationCompleteSidelink

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3730`）

</details>

**1.7.5-12.** What does the gNB do with the UE UTRA-FDD capabilities? [3GPP Release 18]

- A. Upload them to the AMF
- B. Send them to the UE
- C. Signal them to the network
- D. Store them in the gNB
- E. Skip uploading them

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4566`）

</details>

**1.7.5-13.** What is the purpose of the manufacturer-assigned ID in NAS signalling? [3GPP Release 18]

- A. To request UE capabilities
- B. To assign UE capabilities dynamically
- C. To reduce signalling overhead
- D. To support non-contiguous carrier aggregation
- E. To pre-provision a set of capabilities

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5127`）

</details>

**1.7.5-14.** How is the indication to identify RedCap (reduced capability) devices provided during the random-access procedure?

- A. In Message 1
- B. In Message 2
- C. In Message 3
- D. In Message 4

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6575`）

</details>

**1.7.5-15.** Which of the following is not a cost/complexity reduction feature of RedCap (reduced capability) devices?

- A. Reduction of maximum device bandwidth
- B. Reduction of minimum antenna configuration at the device
- C. Reduction of minimum supported number of downlink (DL) MIMO layers
- D. Relaxed maximum DL modulation order
- E. Support for full-duplex operation in FDD bands

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6602`）

</details>

**1.7.5-16.** What is the purpose of UE Capability Segmentation? [3GPP Release 16]

- A. To reduce the size of the capability information message
- B. To encode the capability information message
- C. To reassemble the capability information message
- D. To divide the capability information message into segments

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6832`）

</details>

**1.7.5-17.** What are baseline implementation capabilities?

- A. Capabilities to search for and register to a network
- B. Capabilities to synchronize with a network
- C. Capabilities for a service-less UE to operate within a network
- D. Implementation capabilities required to enable a UE to support baseline capabilities
- E. Capabilities to negotiate with the network for UE and network capabilities

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7631`）

</details>

**1.7.5-18.** What are the desired characteristics for a single RedCap (reduced capability) device type?

- A. Low power consumption and long battery lifetime
- B. High data rate and low latency
- C. Compatibility with LTE-M and NB-IoT
- D. Support for wearables and industrial wireless sensors
- E. Reduced market fragmentation and economies of scale

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-299`）

</details>

**1.7.5-19.** What is the purpose of the RedCap UE type? [3GPP Release 17]

- A. To enable carrier aggregation and dual connectivity in NR
- B. To support high data rate requirements for IoT devices
- C. To reduce UE complexity and power consumption for IoT use cases
- D. To enable messaging communication in the 5G System

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3232`）

</details>

**1.7.5-20.** What is the purpose of the Restriction of use of Enhanced Coverage feature? [3GPP Release 14]

- A. To allocate extensive resources from the network for specific subscribers
- B. To enable the operator to restrict specific subscribers from using Enhanced Coverage
- C. To provide enhanced coverage functionality for both data and voice centric UEs
- D. To prevent the MME from sending the Enhanced Coverage Restricted parameter to the UE

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4755`）

</details>

**1.7.5-21.** What was one of the key design objectives in the RedCap (reduced capability) work item?

- A. To maximize the coverage of RedCap devices
- B. To minimize the impact of RedCap devices on system performance
- C. To ensure efficient coexistence between RedCap and other NR devices
- D. To increase the number of antenna elements in RedCap devices
- E. To support non-contiguous PUSCH resource allocation

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4873`）

</details>

**1.7.5-22.** What is a Multi-USIM UE? [3GPP Release 17]

- A. A UE that supports multiple frequencies of USIM cards.
- B. A UE that can use multiple USIMs and maintain a separate registration state for each one.
- C. A UE that is capable of simultaneous connection with multiple USIMs.
- D. A UE that can switch between different USIMs during a call.
- E. A UE that has multiple USIM slots for redundancy.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7503`）

</details>

**1.7.5-23.** What is the purpose of RedCap NR devices?

- A. To provide better coexistence with NR eMBB and URLLC on an NR carrier than LTE-based solutions
- B. To fulfill the requirements of wearables, industrial wireless sensors, and video surveillance
- C. To support a very wide range of frequency bands
- D. To connect to the 5G core network (5GC)
- E. To provide support for reduced capability devices that fall between eMBB, URLLC, and mMTC

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7702`）

</details>

**1.7.5-24.** What is a MExE classmark?

- A. A certification for a MExE application
- B. A category of MExE UE
- C. An identifier for MExE servers
- D. An executable content conforming to MExE specification

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2982`）

</details>

**1.7.5-25.** What is the target coverage requirement for each channel of a RedCap (reduced capability) device?

- A. The maximum number of antenna elements
- B. The maximum device bandwidth
- C. The minimum device size
- D. The maximum device power consumption
- E. The maximum isotropic loss (MIL) of the reference device

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4854`）

</details>

**1.7.5-26.** What is nominal maximum output power?

- A. A label used for identification of end users
- B. A protocol independent model describing managed objects representing network resources
- C. The nominal power defined by the UE power class
- D. Relating to general, CHV related, GSM security related and subscription related procedures
- E. An association established by a network layer between two users

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5196`）

</details>

**1.7.5-27.** What is the target coverage requirement for RedCap (reduced capability)?

- A. Coverage in rural areas
- B. National coverage
- C. Global coverage
- D. Coverage similar to Release 15/16 NR devices
- E. Coverage in urban areas

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6535`）

</details>

**1.7.5-28.** What is the potential effect of eDRX (extended DRX) on the battery lifetime of RedCap (reduced capability) devices?

- A. No significant impact
- B. Battery lifetime reduction
- C. Battery lifetime extension
- D. Battery lifetime remains unchanged

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6705`）

</details>

## 1.7.6 終端一致性測試（Conformance testing）（31 題）

**1.7.6-1.** What is an Ancillary Equipment?

- A. Equipment used to provide additional operational and control features to radio equipment.
- B. Equipment used for measuring the thermal power of the radio access mode.
- C. Equipment used for establishing the correct identity of an entity or party.
- D. Equipment used for transferring data over the access stratum.
- E. Equipment used for setting up and tearing down transport bearers.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-800`）

</details>

**1.7.6-2.** What is the purpose of the Single link polarization measurement? [3GPP Release 18]

- A. To calculate the CDF of the EIRP/EIS distribution in 3D
- B. To determine the total power radiated by the DUT in the TX beam peak direction
- C. To determine the RX beam peak direction
- D. To measure the EIRP spherical coverage
- E. To reduce the test time for the FR2 2Tx test cases

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4900`）

</details>

**1.7.6-3.** What are the two types of reference points for SAN type 1-H? [3GPP Release 18]

- A. Radiated and conducted reference points
- B. Operating band specific radiated interface and conducted reference points
- C. Transceiver array boundary and satellite payload
- D. Radio distribution network and antenna array

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7000`）

</details>

**1.7.6-4.** What is the maximum number of spatial/antenna streams supported in the LTE FDD IOT Profile 2?

- A. 1
- B. 2
- C. 4
- D. 8

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-41`）

</details>

**1.7.6-5.** What is the outcome of the test if all U-Plane data is successfully received by the Test UE or UE emulator and the Application Test server?

- A. The test is considered a failure.
- B. The test is considered successful.
- C. The test is considered successful with remarks.
- D. The test is inconclusive.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-42`）

</details>

**1.7.6-6.** What is the purpose of comparing the payload of the uplink signal with the payload of the signal communicated on the O-RAN interface?

- A. To ensure the O-RU is properly configured for operation.
- B. To verify the accuracy of the signal transmission and reception.
- C. To determine the power level of the signal source.
- D. To synchronize the O-RU using G.8275.1.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-44`）

</details>

**1.7.6-7.** Which of the following testing services can be supported in an O-RAN OTIC (Open Testing and Integration Centre)?

- A. Conformance Testing
- B. Interoperability Testing
- C. E2E System Testing in Lab
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-51`）

</details>

**1.7.6-8.** Which of the following is a type of test case used in Open Radio Access Networks (O-RAN) technology specifications?

- A. Optical layer tests
- B. Packet layer tests
- C. Synchronization tests
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-81`）

</details>

**1.7.6-9.** Which of the following is NOT a general test use case for Open Radio Access Networks?

- A. Equipment Testing
- B. PHY layer test
- C. Alarm and Monitoring Test Cases
- D. WDM-based Fronthaul Transport Testing

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-146`）

</details>

**1.7.6-10.** What is the primary purpose of the O-RAN E2E Badge?

- A. To certify the security and functionality of end-to-end systems or subsystems utilizing O-RAN open interfaces.
- B. To validate the performance of O-RAN devices in a laboratory setting.
- C. To ensure compatibility between different O-RAN vendors.
- D. To assess the energy efficiency of O-RAN deployments.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-156`）

</details>

**1.7.6-11.** What is the expected outcome regarding the downlink U-Plane data generated in the test scenario?

- A. All U-Plane data should be successfully transmitted and received by the Test UE or UE emulator.
- B. The data rate should be high enough to verify the user plane data transmission.
- C. The Secondary Node Change procedure should be completed successfully.
- D. Xn logs should be aligned with the message flow specified in the NR C-Plane profile specification.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-179`）

</details>

**1.7.6-12.** What is the primary purpose of the Open Testing and Integration Centre (OTIC) within the O-RAN ecosystem?

- A. To develop and maintain the O-RAN specifications.
- B. To certify the compliance and interoperability of O-RAN devices.
- C. To provide training and support for O-RAN deployments.
- D. To manage the O-RAN Alliance membership.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-193`）

</details>

**1.7.6-13.** Which entity is responsible for performing O-RAN certification and badging?

- A. O-RAN ALLIANCE
- B. O-RAN Test and Integration Focus Group (TIFG)
- C. O-RAN Open Testing and Integration Centers (OTICs)
- D. O-RAN WGs/FGs

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-228`）

</details>

**1.7.6-14.** Which of the following O-RAN elements is NOT explicitly mentioned as a DUT (Device Under Test) in the provided context?

- A. O-RU
- B. O-CU-UP
- C. RAN Intelligent Controller (RIC)
- D. O-Cloud

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-244`）

</details>

**1.7.6-15.** What type of sequence is used for the downlink shared channel in the CUSM emulator described in the provided context?

- A. PN23
- B. PN9
- C. Zadoff-Chu
- D. Gold

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-254`）

</details>

**1.7.6-16.** Which of the following protocols is NOT used in the O-RAN test setup described in the context?

- A. F1AP
- B. NGAP
- C. GTP
- D. PFCP

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-270`）

</details>

**1.7.6-17.** Which of the following is NOT a step involved in testing the gNB-DU's ability to gather Assistance Information?

- A. Initiating a Service Request procedure from the UE or UE emulator.
- B. Sending Downlink User Data PDU(s) from the gNB-CU to the gNB-DU with the Assistance Information Report polling Flag IE set to '1'.
- C. Analyzing the Protocol Analyzer F1 logs and Test UE or UE emulator logs.
- D. Configuring the Test UE or UE emulator to send specific data patterns, such as all zeros, to the gNB-DU.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-282`）

</details>

**1.7.6-18.** What is the purpose of using a different seed to initialize the PN23 data for each user when building test signals?

- A. To ensure that the test signals are unique for each user.
- B. To calibrate the test antennas and TER equipment.
- C. To synchronize the O-RU using G.8275.1.
- D. To place the O-RU into a test calibrated point within the OTA chamber.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-286`）

</details>

**1.7.6-19.** An O-RU supports TDD, operates at FR2 bands, and does not have access to antenna ports. Which scenario should this O-RU be tested against to achieve O-RAN conformance?

- A. Scenario #1
- B. Scenario #2
- C. Scenario #3
- D. Scenario #4

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-317`）

</details>

**1.7.6-20.** What is the primary goal of repeating the frame transmission multiple times with different beam directions during O-RAN testing?

- A. To verify the synchronization of the DUT and O-DU.
- B. To ensure the O-DU can demodulate, decode, and extract the payload.
- C. To test the O-RU's ability to receive signals from various beam directions.
- D. To validate the U-plane message transmission between the O-RU and O-DU.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-328`）

</details>

**1.7.6-21.** What is the primary purpose of an Observer in an O-RAN Test and Integration Center (OTIC)?

- A. To actively participate in testing activities and contribute to the development of O-RAN standards.
- B. To observe testing activities in the OTIC for a limited period and/or a limited purpose.
- C. To provide technical support and expertise to participants during testing activities.
- D. To represent the interests of their company or organization in the O-RAN ALLIANCE.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-346`）

</details>

**1.7.6-22.** When testing the open fronthaul interface of the O-DU, what is the name of the test equipment that is connected to it?

- A. O-CU Emulator
- B. O-RU Emulator
- C. Test Equipment O-DU (TED)
- D. Core + O-CU Emulator

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-350`）

</details>

**1.7.6-23.** What is the purpose of the Protocol Analyzer used in testing Open Radio Access Networks (O-RAN)?

- A. To emulate the 5G Core or CN, supporting N1, N2, and HTTP messages.
- B. To record and observe various protocol content, including F1AP, NGAP, FH-eCPRI, FAPI, NAS, HTTP2, and PFCP.
- C. To configure the O-DU and O-RU for testing.
- D. To verify the broadcast of SystemInformation-MIB.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-375`）

</details>

**1.7.6-24.** Which of the following components is NOT typically required for testing an Open Radio Access Network (O-RAN)?

- A. O-RU emulator
- B. 5G Core or Core emulator
- C. LTE eNodeB
- D. Protocol Analyzer

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-390`）

</details>

**1.7.6-25.** What is the primary purpose of an FH Protocol Analyzer in the context of O-RAN testing?

- A. To analyze the Radio Layer 3 C-Plane establishment procedure.
- B. To validate the transfer of Uplink FH C/U-Plane messages with higher MIMO layers and modulation schemes.
- C. To analyze the protocol behavior of O-RAN FH protocols, including C/U-Plane procedural flows and contents.
- D. To ensure the O-RU is transmitting correctly on configured broadcast and synchronization signals.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-423`）

</details>

**1.7.6-26.** What are some of the key functionalities tested in an Open Radio Access Network (O-RAN) environment?

- A. Cell setup, registration, PDU session establishment, and continuous throughput
- B. Network slicing, edge computing, and artificial intelligence
- C. Software defined networking, network function virtualization, and cloud computing
- D. 5G NR, LTE, and Wi-Fi connectivity

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-433`）

</details>

**1.7.6-27.** What is the purpose of the Network Impairment Emulator in the described test case?

- A. To simulate network conditions and test the resilience of the O-RAN network.
- B. To monitor the performance of the gNB-CU and gNB-DU.
- C. To analyze the traffic flow between the gNB-CU and gNB-DU.
- D. To ensure the stability of the F1 link between the gNB-CU and gNB-DU.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-441`）

</details>

**1.7.6-28.** What is the primary purpose of O-RAN certification?

- A. To validate and certify the interoperability of a pair of vendor products.
- B. To prove interoperability of vendor products based on operator-specific features and parameters.
- C. To validate and certify that a vendor product complies with O-RAN specifications.
- D. To provide an indication of interoperability based on optional and advanced features.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-469`）

</details>

**1.7.6-29.** What is a key pass/fail criteria for the described O-RAN test?

- A. The transceiver must be able to support a specific range of fiber lengths based on digital diagnostics.
- B. The traffic must be forwarded correctly with no frame loss at specific steps in the test.
- C. The TNE must be operational without alarms at specific steps in the test.
- D. All of the above.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-475`）

</details>

**1.7.6-30.** What is the primary goal of the ORAN.WG8.IOT.015 test case?

- A. To assess the performance of a PDU session with multiple flows over a two-hour period.
- B. To evaluate the reliability of the F1AP connection between the O-DU and O-CU.
- C. To verify the successful synchronization of the O-DU and O-RU.
- D. To test the functionality of the RACH procedure and RRC setup.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-549`）

</details>

**1.7.6-31.** When conducting over-the-air (OTA) uplink tests for 1-O or 2-O radios, where is the test antenna placed?

- A. Inside an OTA chamber
- B. Outside an OTA chamber
- C. Directly connected to the radio
- D. On a separate test bench

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-806`）

</details>

## 1.7.7 自我組態與自我優化（SON）（16 題）

**1.7.7-1.** Which of the following O-RAN components is responsible for configuring Self Configuration SON functionality, including PCI Conflict detection/resolution and ANR?

- A. SMO
- B. Non-RT RIC
- C. Near-RT RIC
- D. E2 Node

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-90`）

</details>

**1.7.7-2.** What is the primary challenge associated with implementing SON solutions in multi-vendor Open RAN deployments?

- A. Lack of standardized interfaces between SON algorithms and RAN nodes.
- B. Limited availability of SON algorithms for Open RAN deployments.
- C. Difficulty in configuring and managing SON algorithms across multiple vendors.
- D. High cost of deploying SON solutions in Open RAN networks.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-645`）

</details>

**1.7.7-3.** What is the role of the Near-RT RIC in O-RAN Self Optimization (SON) functions?

- A. Near-RT RIC collects data from the E2 Node, trains an AI/ML model, and uses it to optimize the E2 Node's performance.
- B. Near-RT RIC is responsible for configuring the E2 Node's parameters and initiating actions like handover (HO) and cell reselection.
- C. Near-RT RIC acts as a bridge between the SMO/Non-RT RIC and the E2 Node, relaying instructions and data.
- D. Near-RT RIC monitors the performance of the E2 Node and triggers reconfiguration based on pre-defined thresholds.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1182`）

</details>

**1.7.7-4.** How can SON (Self-Organizing Networks) help guarantee the QoS (quality-of-service) requirement of URLLC (Ultra-reliable low-latency communications)?

- A. By building multiple logical sub-networks with reserved resources
- B. By providing intelligence, automatic, and distributed management and optimization
- C. By integrating SDN and NFV to reduce latency
- D. By integrating MEC to improve network scalability and flexibility
- E. By separating the control plane from the forwarding plane

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-757`）

</details>

**1.7.7-5.** What are the technology challenges driving the need for self-organization in disaster resilient heterogeneous small cell networks?

- A. Increased complexity of wireless radio access technologies
- B. Large number of sites/cells required to provide coverage with future high-frequency technologies
- C. Coexistence and coordinated exploitation of multiple heterogeneous access networks
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1124`）

</details>

**1.7.7-6.** What are the key gains from employing self-organization in disaster small cell networks?

- A. Reduction in labor intensity and suboptimal solutions in disaster wireless communication networks
- B. Increased capacity and coverage of indoor and hotspot scenarios
- C. Improved network efficiency and quality of service
- D. Enhanced network performance and service quality in disaster scenarios

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2485`）

</details>

**1.7.7-7.** What is the purpose of the self-configuration process in SON (self organizing network)-enabled DRHSCNs (disaster resilient heterogeneous small cell networks)?

- A. To configure the necessary basic system operation parameters for newly deployed nodes
- B. To optimize the radio resource management parameters for UE and eNB
- C. To collect measurement parameters for self-optimization tasks
- D. To provide operator with information and suggestions for network deployment

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3521`）

</details>

**1.7.7-8.** What is the difference between resilience and self-optimisation in a network?

- A. Resilience is the ability to self-optimise without external input
- B. Self-optimisation is the ability to maintain an acceptable level of service without disruptions
- C. Resilience is the ability to maintain an acceptable level of service in the event of faults or challenges
- D. Self-optimisation is the ability to predict potential disruptions
- E. Resilience is the ability to handle high network traffic

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3783`）

</details>

**1.7.7-9.** What are the advantages of H-SONs compared to C-SONs and D-SONs?

- A. Improved global optimality compared to D-SONs
- B. Improved energy efficiency compared to D-SONs
- C. Improved stability compared to D-SONs
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3818`）

</details>

**1.7.7-10.** What does the self-optimization process in SON (self organizing network)-enabled DRHSCNs (disaster resilient heterogeneous small cell networks) optimize?

- A. Radio channel characteristics
- B. Traffic and users' mobility states
- C. Power settings and antenna parameters
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4223`）

</details>

**1.7.7-11.** What are the intrinsic problems and shortcomings in the methodologies applied in heterogeneous small cells of disaster scenarios?

- A. Limited capacity of the damaged wireless networks in handling increased traffic
- B. Disabled backhaul of damaged base stations
- C. Conflict of the physical cell identity (PCI) for newly added base-stations
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5430`）

</details>

**1.7.7-12.** Which data is required as feedback for mobility optimization? [3GPP Release 17]

- A. QoS parameters of the handed-over UE
- B. Resource status information updates from target NG-RAN
- C. Performance information from target NG-RAN
- D. UE mobility information
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6725`）

</details>

**1.7.7-13.** What is the purpose of RACH (Random Access CHannel) optimization?

- A. To maximize the KPIs in the following frames
- B. To analyze the historical transmission receptions during the RACH
- C. To determine the number of access success devices
- D. To predict the forthcoming traffic statistic
- E. To identify the optimal strategy for RACH control parameters

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6763`）

</details>

**1.7.7-14.** What is the principal objective of introducing self-organization networks (SON)?

- A. To reduce the complexity of wireless radio access technologies
- B. To improve the capacity and coverage of indoor and hotspot scenarios
- C. To reduce human involvement in network optimization and improve network efficiency and quality of service
- D. To study disaster resilient communication networks comprehensively

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7373`）

</details>

**1.7.7-15.** Which of the following is NOT a component of self-organization networks (SON)?

- A. Self-configuration
- B. Self-optimization
- C. Self-healing
- D. Self-destruction

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7686`）

</details>

**1.7.7-16.** What triggers the self-configuration phase in SON (self organizing network)-enabled DRHSCNs (disaster resilient heterogeneous small cell networks)?

- A. Measurement of various parameters collected by the eNB or UE's feedback
- B. Introduction of a new service or network feature
- C. Advice of good deployment location
- D. Fully configured and operating radio access network

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-8073`）

</details>

## 1.7.8 最小化路測（MDT）（9 題）

**1.7.8-1.** In which state is QoE measurement collection supported? [3GPP Release 18]

- A. RRC_IDLE
- B. RRC_CONNECTED
- C. RRC_INACTIVE
- D. RRC_RECONFIGURED

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7146`）

</details>

**1.7.8-2.** What are the key functionalities of MDT enhancement? [3GPP Release 17]

- A. To optimize inter-system load balancing
- B. To enhance energy efficiency
- C. To improve mobility optimization
- D. To enhance network data analytics services

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2539`）

</details>

**1.7.8-3.** What is the supported service type for QoE Measurement Collection? [3GPP Release 18]

- A. QoE Measurement Collection for DASH streaming services
- B. QoE Measurement Collection for MTSI services
- C. QoE Measurement Collection for VR services
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3157`）

</details>

**1.7.8-4.** What is the purpose of RAN visible QoE measurements? [3GPP Release 18]

- A. To evaluate the user experience of a service
- B. To optimize the network
- C. To configure the QoE measurement
- D. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4819`）

</details>

**1.7.8-5.** What functionality does Signalling Based Activation provide? [3GPP Release 17]

- A. Activation of management services for UEs in a specified area
- B. Deactivation of management services for UEs in a specified area
- C. Temporary stop and restart of management services during RAN overload
- D. Request for end user service performance information for one specific UE
- E. Handling management services during handover

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1627`）

</details>

**1.7.8-6.** How is QoE measurement collection activated? [3GPP Release 18]

- A. Through direct configuration from the OAM system
- B. Through signalling from the OAM via the 5GC
- C. Both option 1 and option 2
- D. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2929`）

</details>

**1.7.8-7.** What functionality does Management Based Activation provide? [3GPP Release 17]

- A. Activation of management services for UEs in a specified area
- B. Deactivation of management services for UEs in a specified area
- C. Temporary stop and restart of management services during RAN overload
- D. Request for end user service performance information for one specific UE
- E. Handling management services during handover

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7977`）

</details>

**1.7.8-8.** What is the purpose of MDT data collection? [3GPP Release 18]

- A. To optimize resource usage in the RAN
- B. To capture user consent related to privacy
- C. To provide performance measurements on the Shared E-UTRAN/NG-RAN
- D. To improve signal strength for UEs

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1791`）

</details>

**1.7.8-9.** What advantages do measurements from user equipment (UE) have over drive tests in disaster small cell networks?

- A. Reduced labor intensity
- B. Measurements obtained from additional locations, such as inside buildings
- C. Better adaptation to specific characteristics and requirements in disaster scenarios
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7722`）

</details>
