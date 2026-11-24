# 1.2 通訊協定　GSMA 練習題（1231 題）（第 3／7 頁）

所屬：[1.2 通訊協定](1-2.md)

只收 GSMA 訓練題；不含驗證集與測試集，並已去除和驗證／測試題相同或相似、重複、標註衝突的題目。題目依小節歸類（抽查正確率約 95%）。

頁次：[1](1-2-gsma-1.md)　[2](1-2-gsma-2.md)　**3**　[4](1-2-gsma-4.md)　[5](1-2-gsma-5.md)　[6](1-2-gsma-6.md)　[7](1-2-gsma-7.md)

## 1.2.6 無線介面協定：RRC、SDAP、PDCP、RLC、MAC、PHY（278 題）（續）

**1.2.6-132.** What does a UE prepends to an information field in a DCI format if its size is smaller than required? [3GPP Release 17]

- A. Zeros
- B. Ones
- C. The last value in the field
- D. Nothing, it discards the information field

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4550`）

</details>

**1.2.6-133.** What additional information is reported to the NAS if the UE supports E-UTRA connected to 5GC? [3GPP Release 17]

- A. Associated RSRP value
- B. Associated PLMN identity
- C. Associated CN type
- D. Associated CSG ID
- E. Associated cell parameters

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4583`）

</details>

**1.2.6-134.** What is the purpose of UL asynchronous HARQ transmission in the LTE network? [3GPP Release 14]

- A. To improve UL/DL bitrate recommendation
- B. To support multi-subframe channel estimation
- C. To utilize transmission time efficiently
- D. To enable PUSCH enhancement mode

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4601`）

</details>

**1.2.6-135.** What is the purpose of the PUCCH transmission with a link recovery request (LRR)? [3GPP Release 17]

- A. To request a link recovery from the network.
- B. To transmit PUCCH on a different cell than the PRACH transmission.
- C. To indicate the presence of periodic CSI-RS configuration or SS/PBCH block.
- D. To monitor PDCCH in all CORESETs on the SCell(s).

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4633`）

</details>

**1.2.6-136.** Which sublayer is responsible for mapping between a QoS flow and a data radio bearer? [3GPP Release 18]

- A. MAC sublayer
- B. RLC sublayer
- C. PDCP sublayer
- D. SDAP sublayer

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4739`）

</details>

**1.2.6-137.** When does the UE ignore the scheduling DCI for the n-th triggered CSI report? [3GPP Release 17]

- A. If the first uplink symbol to carry the n-th CSI report starts earlier than at symbol Z'ref(n)
- B. If the PUSCH indicated by the DCI is overlapping with another PUCCH or PUSCH
- C. If the number of triggered reports is one and no HARQ-ACK or transport block is multiplexed on the PUSCH
- D. If the first uplink symbol to carry the corresponding CSI report(s) starts earlier than at symbol Zref
- E. If the PDCCH reception includes two PDCCH candidates from two respective search space sets

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4759`）

</details>

**1.2.6-138.** What determines if an IAB-DU cell can transmit or receive on a symbol configured as a soft type? [3GPP Release 17]

- A. IAB-DU cell's configuration of hard or unavailable symbols
- B. Availability of soft symbols in the slot
- C. Detection of DCI format 2_5 with an AI index field value
- D. Configuration of RB set availability by Frequency-Domain HSNA Configuration List

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4843`）

</details>

**1.2.6-139.** What are the three factors that govern the PDCCH monitoring activity of the UE in RRC connected mode? [3GPP Release 17]

- A. DRX, BA, and DCP
- B. BA, DCP, and CA
- C. DRX, DCP, and CA
- D. DRX, BA, and CA
- E. DRX, BA, and DCP

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4844`）

</details>

**1.2.6-140.** What does a UE configure when provided with UplinkCancellation? [3GPP Release 17]

- A. Search space sets for monitoring the first PDCCH candidate
- B. Set of serving cell indexes and corresponding locations for fields in DCI format 2_4
- C. Number of fields in DCI format 2_4 for each serving cell
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4849`）

</details>

**1.2.6-141.** Which state supports QoE measurement reporting in UMTS networks? [3GPP Release 14]

- A. CELL_FACH state
- B. CELL_DCH state
- C. CELL_PCH state
- D. CELL_FDD state

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4865`）

</details>

**1.2.6-142.** What type of link adaptation is performed in uplink transmission? [3GPP Release 17]

- A. Adaptive transmission bandwidth
- B. Transmission power control
- C. Adaptive modulation and channel coding rate
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4904`）

</details>

**1.2.6-143.** When does the UE monitor PDCCH skipping duration? [3GPP Release 17]

- A. During measurement gaps
- B. During cross-slot scheduling
- C. During PDCCH monitoring adaptation mechanisms
- D. During the on-duration
- E. During BWP switching

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4950`）

</details>

**1.2.6-144.** What is the duration called that the UE waits for after waking up to receive PDCCHs? [3GPP Release 17]

- A. Cycle
- B. Active-time
- C. On-duration
- D. Inactivity-timer
- E. Retransmission-timer

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4989`）

</details>

**1.2.6-145.** What does a UE expect when receiving a DCI format with a BWP indicator field indicating an active UL BWP or DL BWP change? [3GPP Release 17]

- A. To receive or transmit in the cell during a time duration specified by a delay
- B. To receive or transmit in the cell only in the first slot of a set of slots for the DL SCS
- C. To detect the DCI format within the first 3 symbols of a slot
- D. To monitor PDCCH during RRM measurements

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5006`）

</details>

**1.2.6-146.** Which mode is used for multi-TRP PDCCH transmission? [3GPP Release 18]

- A. PDCCH repetition
- B. SFN based PDCCH transmission
- C. Both 1 and 2
- D. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5041`）

</details>

**1.2.6-147.** In a shared UTRAN/GERAN network, what does a non-supporting UE do after reading the broadcast system information? [3GPP Release 17]

- A. The UE sends an ATTACH REQUEST/ROUTEING AREA UPDATE/LOCATION AREA UPDATE message to the network
- B. The UE decodes the shared network information and supplies the available core network operator PLMN-ids as candidates to the PLMN selection procedure
- C. The UE performs network selection among available PLMNs
- D. The UE reads the system information in the shared RAN
- E. The UE reads the system information in the shared GERAN

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5045`）

</details>

**1.2.6-148.** What is the purpose of the L2 latency reduction techniques for LTE work item? [3GPP Release 14]

- A. To increase the effectiveness of available scheduling tools
- B. To improve the DL beamforming performance
- C. To reduce the grant request delay in the UL
- D. To reduce the end to end delay for connected UEs
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5059`）

</details>

**1.2.6-149.** What does AS stand for in the context of PLMN selection? [3GPP Release 17]

- A. Administrative System
- B. Authentication Server
- C. Application Server
- D. Access Server
- E. Availability System

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5062`）

</details>

**1.2.6-150.** What does the Child IAB-DU Restricted Beam Indication MAC CE indicate to the IAB-node? [3GPP Release 17]

- A. Multiplexing mode of the IAB-node
- B. Availability of RB resources for transmission
- C. Indication of quasi co-location properties of an IAB-DU cell
- D. Timing advance offset value for a serving cell

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5083`）

</details>

**1.2.6-151.** What should the UE do when receiving an RRC message on the BCCH, CCCH, PCCH, MCCH or a PC5 RRC message on SBCCH for which the abstract syntax is invalid? [3GPP Release 17]

- A. Ignore the message
- B. Treat the message as if the field were absent
- C. Apply the generic error handling
- D. Consider the 'parent' field to be set to a not comprehended value

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5104`）

</details>

**1.2.6-152.** What is the purpose of Radio Link Control?

- A. To control the configuration of radio interface Layers 1 and 2.
- B. To offer radio access to one or more core network operators.
- C. To provide a service for transfer of user data between User Equipment and CN.
- D. To support the exchange of information between peer application entities in a GERAN or UTRAN access network.
- E. A sublayer of radio interface Layer 2 providing transparent, unacknowledged and acknowledged data transfer service.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5140`）

</details>

**1.2.6-153.** What is the purpose of the scheduler in MAC in gNB? [3GPP Release 18]

- A. To allocate physical layer resources for the uplink and the downlink
- B. To manage the sharing of uplink resources between logical channels
- C. To enable coordination of TDM and FDM cell resources between MAC in the gNB and the corresponding entity in the ng-eNB
- D. To provide support for power-aware packet scheduling
- E. To provide support for QoS-aware packet scheduling

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5167`）

</details>

**1.2.6-154.** What is the purpose of the ARQ functionality in the RLC sublayer? [3GPP Release 17]

- A. Error detection
- B. Segmentation of RLC SDUs
- C. Sequence numbering
- D. Flow control
- E. Error correction

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5190`）

</details>

**1.2.6-155.** What are some of the technical aspects that need to be designed carefully for URLLC (Ultrareliable and low-latency communication) in the cellular network?

- A. Waveform numerology
- B. Frame structure
- C. Multiple access scheme
- D. Pilot design
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5231`）

</details>

**1.2.6-156.** What is the purpose of the Early data transmission feature in NB-IoT? [3GPP Release 15]

- A. To allow the UE to transmit data in Msg3 of the random access procedure
- B. To improve the accuracy of narrowband measurement
- C. To enable the UE to request NPUSCH resources for BSR transmission
- D. To reduce UE power consumption during cell access
- E. To support small cell deployments with lower maximum transmit power

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5294`）

</details>

**1.2.6-157.** What is the purpose of Random Access Channel (RACH)? [3GPP Release 18]

- A. Transmit data themselves
- B. Carry control information for HARQ procedures
- C. Carry ACK/NAK feedback
- D. Carry scheduling requests
- E. Indicate resource and other transmission parameters

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5300`）

</details>

**1.2.6-158.** What is the purpose of the Semi-static CFI configuration in LTE? [3GPP Release 18]

- A. To improve the reliability of the uplink data channel
- B. To improve the reliability of the downlink data channel
- C. To provide a granular time reference
- D. To allow PDCP packet duplication

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5346`）

</details>

**1.2.6-159.** What is the motivation behind the transmission of extremely short packages?

- A. To achieve higher data rates
- B. To reduce the cost of transmission
- C. To enable control signaling
- D. To improve channel capacity

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5349`）

</details>

**1.2.6-160.** A UE monitors PDCCH for scheduling PDSCH receptions for which types of transmissions? [3GPP Release 17]

- A. Unicast and multicast
- B. Broadcast and multicast
- C. Unicast and broadcast
- D. Multicast and SPS

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5395`）

</details>

**1.2.6-161.** What is the maximum value for the DRX (discontinuous reception) cycle in the idle and inactive states in NR?

- A. 56 seconds
- B. 3 hours
- C. 24 seconds
- D. 76 seconds

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5397`）

</details>

**1.2.6-162.** What does CA stand for in the context of RRC? [3GPP Release 18]

- A. Code Assignment
- B. Channel Allocation
- C. Cell Association
- D. Connection Admission
- E. Carrier Aggregation

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5480`）

</details>

**1.2.6-163.** When can the UE trigger reporting of its RLM and BFD relaxation status? [3GPP Release 17]

- A. When the RLM and BFD relaxation status changes
- B. During the on-duration
- C. When the serving cell changes
- D. On every DRX cycle
- E. Whenever the UE wakes up

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5534`）

</details>

**1.2.6-164.** What is the purpose of sequence and cyclic shift hopping in PUCCH formats 0, 1, 3, and 4? [3GPP Release 17]

- A. To provide frequency diversity in the PUCCH transmission.
- B. To improve the orthogonality of the transmitted signals.
- C. To adapt the PUCCH transmission to the channel conditions.
- D. To reduce the interference between PUCCH transmissions.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5551`）

</details>

**1.2.6-165.** What message does the UE send to initiate the initial access procedure? [3GPP Release 17]

- A. RRC_CONNECTION_SETUP_COMPLETE
- B. RRCSetup
- C. RRCSetupRequest
- D. SecurityModeCommand
- E. RRCReconfiguration

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5746`）

</details>

**1.2.6-166.** What is the purpose of the PDCP (packet data convergence protocol) layer in LTE?

- A. To improve mobility robustness during handover
- B. To perform header compression and integrity protection
- C. To support both user and control planes
- D. To eliminate duplicate packets in the receiver
- E. To split user data in multiple carriers

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5751`）

</details>

**1.2.6-167.** What happens if the UE ignores the scheduling DCI when the first uplink symbol to carry the corresponding CSI report(s) starts earlier than at symbol Zref? [3GPP Release 17]

- A. The UE may ignore the scheduling DCI if no HARQ-ACK or transport block is multiplexed on the PUSCH
- B. The UE is not required to update the CSI for the n-th triggered CSI report
- C. The UE may ignore the scheduling DCI if the number of triggered reports is one and no HARQ-ACK or transport block is multiplexed on the PUSCH
- D. The UE should transmit the CSI report(s) on the PUSCH indicated by the DCI
- E. The UE should provide a valid CSI report for the n-th triggered report

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5854`）

</details>

**1.2.6-168.** What is the purpose of the Transport of NAS Messages in RRC? [3GPP Release 18]

- A. To enable reliable and in-sequence delivery of NAS messages
- B. To facilitate handover without packet loss
- C. To ensure proper synchronization between the UE and the network
- D. To support encryption and decryption of NAS messages
- E. To enable multi-hop communication in non-terrestrial networks

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5899`）

</details>

**1.2.6-169.** What message does the eNB send to perform redirection to another E-UTRAN frequency? [3GPP Release 14]

- A. GBR bearer message
- B. RRC Connection Release message
- C. Redirect message
- D. Frequency update message
- E. UE CONTEXT RELEASE REQUEST message

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6010`）

</details>

**1.2.6-170.** Which identity is used for unique UE identification and scheduling? [3GPP Release 17]

- A. AI-RNTI
- B. SI-RNTI
- C. TPC-PUCCH-RNTI
- D. RA-RNTI
- E. C-RNTI

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6046`）

</details>

**1.2.6-171.** What is a radio bearer?

- A. The service that the access stratum provides to the non-access stratum for transfer of user data between User Equipment and CN.
- B. The mode of the cell, FDD or TDD.
- C. The service provided by the Layer 2 for transfer of user data between User Equipment and UTRAN.
- D. Two or more CN operators share the same RAN.
- E. Radio Network Signaling over the Iu.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6096`）

</details>

**1.2.6-172.** What does the UE consider the term 'radio bearer' (RB) to cover? [3GPP Release 17]

- A. Secondary Radio Bearers (SRBs)
- B. Data Radio Bearers (DRBs)
- C. Message Radio Bearers (MRBs)
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6111`）

</details>

**1.2.6-173.** What are the two formats for the Physical Uplink Control Channel (PUCCH) used by MulteFire?

- A. Short-PUCCH (MF-sPUCCH) and Long-PUCCH (MF-lPUCCH)
- B. Short-PUCCH (MF-sPUCCH) and Extended PUCCH (MF-ePUCCH)
- C. Short-PUCCH (MF-sPUCCH) and Medium-PUCCH (MF-mPUCCH)
- D. Short-PUCCH (MF-sPUCCH) and Wide-PUCCH (MF-wPUCCH)

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6115`）

</details>

**1.2.6-174.** What is HARQ-ACK bundling? [3GPP Release 14]

- A. A feature that enables UEs to transmit multiple HARQ-ACK feedback for a single DL transport block.
- B. A feature that allows UEs to transmit a single HARQ-ACK feedback for multiple DL transport blocks.
- C. A technique for improving DL peak rate in half-duplex FDD operation.
- D. A method for improving link performance in DL-heavy TDD configurations.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6139`）

</details>

**1.2.6-175.** How is the contention window size determined in the LBT (listen-before-talk) algorithm for transmitting PDSCH (Physical Downlink Shared Channel) in LAA (LTE-U Licensed Spectrum Access)?

- A. It is fixed for all devices
- B. It is determined based on the channel frequency
- C. It is determined based on the device's priority class
- D. It is determined randomly
- E. It is determined based on the number of connected devices

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6145`）

</details>

**1.2.6-176.** Which approach cannot be simultaneously active with packet duplication?

- A. Duplicate bearer
- B. Path restriction
- C. RC connection
- D. Data split

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6294`）

</details>

**1.2.6-177.** How does the gNB allocate downlink resources for initial HARQ transmissions to UEs? [3GPP Release 17]

- A. Through the scheduling request channel
- B. Through power headroom reports
- C. Through activation of configured downlink assignments
- D. Through semi-persistent scheduling

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6328`）

</details>

**1.2.6-178.** What is grant-based access?

- A. When active users directly transmit predefined preambles and data to the base station (BS) without waiting for the grant
- B. When active users send a randomly selected orthogonal preamble to the base station (BS) and wait for the responses
- C. When the base station (BS) sends a contention-resolution message in response to received connection requests
- D. When the base station (BS) successfully decodes the contention request from active users
- E. When the limited number of preambles results in high overhead for small data packets

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6348`）

</details>

**1.2.6-179.** What is Extended DRX?

- A. A framework for extending the range of DRX cycles
- B. A power saving feature where paging cycles can range from seconds to several hours
- C. A feature for managing access conditions and data on the UICC
- D. A feature for managing end-users in a network

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6398`）

</details>

**1.2.6-180.** Which logical channel is used for transmitting control information between UEs and the network? [3GPP Release 18]

- A. BCCH
- B. PCCH
- C. CCCH
- D. DCCH

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6426`）

</details>

**1.2.6-181.** What is the term used for HARQ-ACK information associated with multicast DCI formats or multicast PDSCH receptions? [3GPP Release 17]

- A. Unicast HARQ-ACK information
- B. Dynamic HARQ-ACK information
- C. Multicast HARQ-ACK information
- D. Static HARQ-ACK information

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6427`）

</details>

**1.2.6-182.** What RRC states can additional resources be used for RRM measurements? [3GPP Release 16]

- A. RRC IDLE
- B. RRC INACTIVE
- C. RRC CONNECTED
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6471`）

</details>

**1.2.6-183.** What can be used for intra-system inter-RAT handover if the UE is connected to the 5GC of the source E-UTRA cell? [3GPP Release 17]

- A. Delta configuration for PDCP and SDAP
- B. Source RAT configuration
- C. Reconfiguration message of target RAT
- D. Re-establishment procedure
- E. NULL algorithm for ciphering

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6506`）

</details>

**1.2.6-184.** When can a gNB transmit a DL transmission(s) on a channel after initiating a channel occupancy? [3GPP Release 17]

- A. Regardless of the duration of the gap between the DL transmission(s) and any previous transmission(s) corresponding to the channel occupancy initiated by the gNB.
- B. If the gap between the DL transmission(s) and any previous transmission(s) corresponding to the channel occupancy initiated by the gNB is more than a threshold.
- C. Both option 1 and option 2
- D. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6541`）

</details>

**1.2.6-185.** What information does the HandoverPreparationInformation message transfer? [3GPP Release 17]

- A. The SCG radio configuration for one or more candidate cells for Conditional PSCell Addition (CPA) or Conditional PSCell Change (CPC)
- B. The handover command as generated by the target gNB
- C. The NR RRC information used by the target gNB during handover preparation or UE context retrieval
- D. The radio paging information, covering both upload to and download from the 5GC, and between gNBs
- E. The UE radio access capability information, covering both upload to and download from the 5GC

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6615`）

</details>

**1.2.6-186.** What is used for downlink power control? [3GPP Release 17]

- A. Timing Advance
- B. Channel quality
- C. Transmit power reference
- D. Received signal strength
- E. Transmit power control commands

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6688`）

</details>

**1.2.6-187.** Which identity is used to control the power of PUSCH? [3GPP Release 17]

- A. SFI-RNTI
- B. TPC-PUCCH-RNTI
- C. TPC-PUSCH-RNTI
- D. TPC-SRS-RNTI
- E. RA-RNTI

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6734`）

</details>

**1.2.6-188.** What is the purpose of sidelink synchronization using SLSS signals? [3GPP Release 14]

- A. To align time and frequency references between UEs
- B. To support inter-PLMN operations
- C. To increase the maximum bandwidth of V2X services
- D. To enable simultaneous V2X operations over multiple carriers
- E. To reduce latency for V2X services

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6772`）

</details>

**1.2.6-189.** What is the purpose of the DTX/DRX enhancements in CELL_FACH state? [3GPP Release 14]

- A. To improve battery life of smart phones
- B. To improve resource utilization and latency
- C. To enhance uplink coverage of cells
- D. To support dual carrier operation
- E. To improve downlink data transmission

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6805`）

</details>

**1.2.6-190.** What is the function of the Sidelink Traffic Channel (STCH) in NR-V2X?

- A. To carry user data traffic
- B. To transmit the control information about the shared channel
- C. To carry the SL-BCH transport channel
- D. To transmit user information from a UE to other UE(s)

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6821`）

</details>

**1.2.6-191.** Which sublayer is responsible for transfer of upper layer PDUs? [3GPP Release 18]

- A. MAC sublayer
- B. RLC sublayer
- C. PDCP sublayer
- D. SDAP sublayer

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6921`）

</details>

**1.2.6-192.** What is the purpose of timing advance in uplink transmission? [3GPP Release 17]

- A. To advance/delay UE timings of transmissions to compensate for propagation delay
- B. To synchronize UE transmissions with the receiver window of the eNB
- C. To adjust the power spectral density of uplink transmissions
- D. To select the appropriate modulation and channel coding rate
- E. To allocate power to each carrier group in power control mode 1

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6943`）

</details>

**1.2.6-193.** What is the purpose of the MulteFire Primary Synchronization Signal (MF-PSS) and MulteFire Secondary Synchronization Signal (MF-SSS)?

- A. Provide frequency/time synchronization
- B. Allow differentiation between LAA and MulteFire eNodeBs
- C. Transmit system information
- D. Support UE in frequency/time synchronization and differentiate between LAA and MulteFire eNodeBs

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7129`）

</details>

**1.2.6-194.** What is the purpose of the scheduling assignments (SA) in V2V communications? [3GPP Release 14]

- A. To transmit control signaling over the Uu interface
- B. To enhance resource separation between transmitters
- C. To provide time synchronization using GNSS
- D. To handle high-speed communication between vehicles

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7215`）

</details>

**1.2.6-195.** What mapping service does SDAP (Service Data Adaptation Protocol) provide in NR SL (Sidelink)?

- A. Mapping between QoS flow and SL Data Radio Bearer (SL-DRB)
- B. Mapping between logical channels and transport channels
- C. Mapping between MAC and RLC entities
- D. Mapping between RRC messages and higher layers

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7245`）

</details>

**1.2.6-196.** How is the last symbol of the PDCCH triggering the CSI report(s) determined when the PDCCH reception includes two PDCCH candidates? [3GPP Release 17]

- A. The PDCCH candidate that ends earlier in time is used
- B. The PDCCH candidate that ends later in time is used
- C. The PDCCH candidate with the higher power is used
- D. The PDCCH candidate with the lower power is used
- E. The PDCCH candidate with the higher number of symbols is used

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7248`）

</details>

**1.2.6-197.** Which control mechanism allows the network to control the behavior of UEs in E-UTRAN in connected mode? [3GPP Release 18]

- A. Access Class Barring
- B. Service Specific Access Control
- C. Extended Access Barring
- D. Application Specific Congestion Control for Data Communication
- E. Prevention of mobile-originating signalling and/or data traffic

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7259`）

</details>

**1.2.6-198.** When does the UE use Listen-Before-Talk (LBT) for transmission on a cell with shared spectrum channel access? [3GPP Release 18]

- A. Only for sidelink transmissions
- B. After each transmission
- C. Only for uplink transmissions
- D. Only for downlink transmissions
- E. Before each transmission

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7268`）

</details>

**1.2.6-199.** What is Small Data Transmission (SDT)? [3GPP Release 18]

- A. A procedure allowing data and/or signalling transmission in RRC_SUSPEND state.
- B. A procedure allowing data and/or signalling transmission in RRC_CONNECTED state.
- C. A procedure allowing data and/or signalling transmission in RRC_IDLE state.
- D. A procedure allowing data and/or signalling transmission in RRC_RELEASE state.
- E. A procedure allowing data and/or signalling transmission while remaining in RRC_INACTIVE state.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7290`）

</details>

**1.2.6-200.** Which identity is used for identification of Paging and System Information change notification in the downlink? [3GPP Release 17]

- A. C-RNTI
- B. CI-RNTI
- C. CS-RNTI
- D. INT-RNTI
- E. P-RNTI

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7371`）

</details>

**1.2.6-201.** Which states does RRC support? [3GPP Release 18]

- A. RRC_IDLE
- B. RRC_INACTIVE
- C. RRC_CONNECTED
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7431`）

</details>

**1.2.6-202.** Which mechanisms in the LTE protocol are exploited to embed SA (standalone) LTE-U transmission into existing Wi-Fi networks?

- A. PCF and HCF mechanisms
- B. DRX and DTCH mechanisms
- C. PSS and SSS mechanisms
- D. CSICH and PDCCH mechanisms
- E. DTX and DRX mechanisms

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7434`）

</details>

**1.2.6-203.** What is the main purpose of mode 2 resource allocation in NR-V2X?

- A. To allocate resources by a gNB for in-coverage UEs
- B. To allocate resources autonomously by a UE based on a sensing procedure
- C. To perform error correction through ARQ in SL communication
- D. To provide prioritization between uplink and SL in a UE

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7519`）

</details>

**1.2.6-204.** Which transmission mode does the RLC sublayer use for dedicated traffic channels (DTCH)? [3GPP Release 18]

- A. Transparent Mode (TM)
- B. Unacknowledged Mode (UM)
- C. Acknowledged Mode (AM)
- D. All of the above

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7550`）

</details>

**1.2.6-205.** What is the inactivity timer of DRX used for? [3GPP Release 18]

- A. To switch the active BWP to the default one
- B. To monitor the PDCCH during the next occurrence of the on-duration
- C. To wait for a retransmission
- D. To go back to sleep after a period of inactivity

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7577`）

</details>

**1.2.6-206.** What does a UE use to determine the priority for a PUCCH transmission with multicast HARQ-ACK information? [3GPP Release 17]

- A. MCCH-RNTI
- B. G-RNTIs
- C. G-CS-RNTI
- D. CRC

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7578`）

</details>

**1.2.6-207.** Which RRC (radio resource control) state allows for a fast RRC connection setup once a packet arrives?

- A. RRC_IDLE
- B. RRC_CONNECTED
- C. RRC_INACTIVE
- D. RRC_INACTIVE_CONNECTED
- E. RRC_SUSPENDED

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7593`）

</details>

**1.2.6-208.** Which entity provides the error correction through ARQ in NR-V2X (Vehicle to everything)?

- A. Sidelink MAC
- B. Sidelink RLC
- C. Sidelink PDCP
- D. Sidelink SDAP

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7630`）

</details>

**1.2.6-209.** Which message is used to confirm the successful completion of a PC5 RRC AS reconfiguration? [3GPP Release 17]

- A. RRCReconfigurationSidelink
- B. MeasurementReportSidelink
- C. RRCReconfigurationCompleteSidelink
- D. NotificationMessageSidelink
- E. UECapabilityEnquirySidelink

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7632`）

</details>

**1.2.6-210.** What are the two coexistence methods proposed for harmonious LTE-U and WiFi coexistence?

- A. Listen before talk (LBT) and duty cycling
- B. Scheduling-based channel access and contention-based channel access
- C. Multi-user transmission and random backoff mechanism
- D. LTE-U and incumbent unlicensed systems
- E. None of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7675`）

</details>

**1.2.6-211.** What are RAN assistance parameters used for in RRC_IDLE? [3GPP Release 17]

- A. To define the timer value for traffic steering.
- B. To facilitate traffic steering from WLAN to E-UTRAN.
- C. To specify the backhaul available uplink bandwidth threshold.
- D. To determine the WLAN RSSI threshold.
- E. To notify upper layers in the UE about WLANs for traffic steering.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7692`）

</details>

**1.2.6-212.** Which sublayer is responsible for error correction through HARQ? [3GPP Release 18]

- A. RLC sublayer
- B. MAC sublayer
- C. PDCP sublayer
- D. SDAP sublayer

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7748`）

</details>

**1.2.6-213.** Which PDCP packet duplication is supported in LTE for improving reliability? [3GPP Release 18]

- A. For Data Radio Bearers (DRBs) using RLC TM
- B. For Data Radio Bearers (DRBs) using RLC AM
- C. For Signalling Radio Bearers (SRBs) using RLC AM
- D. For UL SPS (uplink Semi-Persistent Scheduling) transmissions

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7790`）

</details>

**1.2.6-214.** What does SI stand for in the context of RRC? [3GPP Release 18]

- A. Signal Integrity
- B. Service Interface
- C. Security Identifier
- D. Sidelink Information
- E. System Information

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7793`）

</details>

**1.2.6-215.** Which identity is used for identification of cancellation in the uplink? [3GPP Release 17]

- A. C-RNTI
- B. CI-RNTI
- C. CS-RNTI
- D. INT-RNTI
- E. P-RNTI

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7814`）

</details>

**1.2.6-216.** What does the CG-CandidateList message in ASN.1 define? [3GPP Release 17]

- A. The SCG radio configuration for one or more candidate cells for Conditional PSCell Addition (CPA) or Conditional PSCell Change (CPC)
- B. The handover command as generated by the target gNB
- C. The NR RRC information used by the target gNB during handover preparation or UE context retrieval
- D. The radio paging information, covering both upload to and download from the 5GC, and between gNBs
- E. The UE radio access capability information, covering both upload to and download from the 5GC

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7842`）

</details>

**1.2.6-217.** What is the role of Logical Channel Prioritization (LCP)?

- A. Handling scheduling requests
- B. Creating MAC PDUs
- C. Ordering SDUs
- D. Ciphering and deciphering
- E. Managing QoS

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7880`）

</details>

**1.2.6-218.** What channel is used by the eNodeB to broadcast whether a subframe is DL (downlink) or UL (uplink)?

- A. Common Physical Downlink Control Channel (C-PDCCH)
- B. MulteFire Primary Synchronization Signal (MF-PSS)
- C. MulteFire Secondary Synchronization Signal (MF-SSS)
- D. MulteFire Physical Broadcast Channel (MulteFire-PBCH)

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7922`）

</details>

**1.2.6-219.** Which identity is used for UE identification temporarily used for contention resolution purposes during the random access procedure? [3GPP Release 17]

- A. CI-RNTI
- B. RA-RNTI
- C. Temporary C-RNTI
- D. Random value for contention resolution
- E. I-RNTI

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7944`）

</details>

**1.2.6-220.** What does SPS stand for in the context of uplink and sidelink enhancements? [3GPP Release 14]

- A. Synchronized Power Sharing
- B. Synchronized Packet Scheduling
- C. Sidelink Power Saving
- D. Selective Power Scaling
- E. Semi-Persistent Scheduling

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7956`）

</details>

**1.2.6-221.** What does PDSCH repetition improve in LTE? [3GPP Release 18]

- A. Uplink data channel reliability
- B. Downlink data channel reliability
- C. Uplink latency
- D. Downlink latency

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1315`）

</details>

**1.2.6-222.** What is one benefit of packet duplication in 5G networks?

- A. Improved reliability by providing frequency and path diversity
- B. Reduced latency by avoiding retransmissions
- C. Reduced jitter by minimizing variance in latency
- D. Improved handover performance
- E. Improved throughput during TCP slow start phase

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1795`）

</details>

**1.2.6-223.** What can an NG-RAN node do with the paging enhancements mechanism? [3GPP Release 18]

- A. Page all UEs within a cell
- B. Page specific UE groups
- C. Page UE(s) in a restricted area using certain SSB(s)
- D. Page UEs located in neighboring cells

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5843`）

</details>

**1.2.6-224.** What is the purpose of PC5-RRC in NR V2X sidelink? [3GPP Release 16]

- A. To enable sensing operations
- B. To enable resource allocation
- C. To enable cross-RAT operations
- D. To enable V2X message delivery
- E. To enable location tracking

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6354`）

</details>

**1.2.6-225.** What happens when a mobile station (MS) attempts to camp on a cell for which it does not have service entitlement? [3GPP Release 18]

- A. The MS is granted access to the cell without any restrictions.
- B. The MS is denied access to the cell and enters a limited service state.
- C. The MS is allowed access to the cell but with reduced functionality.
- D. The MS is automatically redirected to a different cell with service entitlement.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-689`）

</details>

**1.2.6-226.** What is the purpose of allocating UEs into different Access Classes? [3GPP Release 18]

- A. To differentiate between CS and PS domains
- B. To determine the home and visited PLMNs
- C. To bar UEs from network access
- D. To specify the categories of subscribers who are barred from network access
- E. To assign specific priorities to UEs based on their special categories

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2895`）

</details>

**1.2.6-227.** In the context of cell status and cell reservations, what does the field 'cellBarred' indicate? [3GPP Release 17]

- A. If the cell is barred for connectivity to 5GC
- B. If the cell is reserved for operator use
- C. If the cell is barred for connectivity to EPC
- D. If the cell supports network-based CRS interference mitigation
- E. If the cell is barred for emergency calls

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4548`）

</details>

**1.2.6-228.** What is the purpose of Domain Specific Access Control?

- A. Obsolete term for Elementary File.
- B. Information coded as TLV objects, i.e. consisting of a Tag, a Length and a Value part.
- C. Access control functionality for access barring in either domain (i.e. CS domain or PS domain).
- D. The process of deactivating the personalisation so that the ME ceases to carry out the verification checks.
- E. A file containing access conditions and, optionally, Elementary Files (EFs) or other Dedicated Files (DFs).

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5170`）

</details>

**1.2.6-229.** What is the purpose of ACDC (Application Specific Congestion control for Data Communication)? [3GPP Release 18]

- A. To prevent overload of the access network and/or the core network
- B. To control access to network provided services or functions
- C. To allow/prevent new access attempts from particular applications
- D. To differentiate between CS and PS domains
- E. To specify the categories of subscribers who are barred from network access

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5182`）

</details>

**1.2.6-230.** What is the purpose of Access Class 10? [3GPP Release 18]

- A. To differentiate between CS and PS domains
- B. To indicate the network access for Emergency Calls
- C. To control UE capabilities
- D. To prevent overload of the access network and/or the core network
- E. To specify the categories of subscribers who are barred from network access

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5390`）

</details>

**1.2.6-231.** When is AS security applied in the SDT procedure? [3GPP Release 18]

- A. Before initiating the SDT procedure.
- B. During the ongoing SDT procedure.
- C. After successful completion of the SDT procedure.
- D. Before the UE transitions to RRC_IDLE state.
- E. Before the UE transitions to RRC_CONNECTED state.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5862`）

</details>

**1.2.6-232.** Which of the following IEs are indicative of a successful NR PDCP data transmission in an O-RAN system?

- A. Highest Transmitted NR PDCP SN Ind IE with the value '1' and Highest Delivered NR PDCP SN Ind IE with the value '1'
- B. Lost Packet Report IE with the value '1'
- C. Highest Retransmitted NR PDCP SN Ind IE with the value '1' and Highest Delivered Retransmitted NR PDCP SN Ind IE with the value '1'
- D. Cause Report IE with the value '1' and Cause value IE with the value '1', '3', or '4'

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-246`）

</details>

**1.2.6-233.** In the context of ORAN beam failure recovery, what is the primary purpose of scaling the backoff indicator (BI) to a smaller value and incrementing the preamble power?

- A. To reduce the likelihood of collisions during random access.
- B. To improve the accuracy of beamforming.
- C. To increase the power consumption of the UE.
- D. To ensure the UE can only access the network during specific time slots.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-397`）

</details>

**1.2.6-234.** Which of the following protocols is responsible for controlling the radio resources in an O-RAN network?

- A. RRC
- B. RLC
- C. SDAP
- D. PHY

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-599`）

</details>

**1.2.6-235.** Which of the following physical channels carries information originating from higher layers in a 5G NR downlink?

- A. Physical Downlink Shared Channel (PDSCH)
- B. Physical Downlink Control Channel (PDCCH)
- C. Physical Broadcast Channel (PBCH)
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-764`）

</details>

**1.2.6-236.** Which of the following is NOT a performance counter related to the Radio Link Control (RLC) layer in a Downlink (DL) scenario?

- A. The number of exceeding maximum RLC retransmissions
- B. IP Latency DL in gNB-DU
- C. Received paging records
- D. DL RLC PDUs discarded due to full buffer

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-793`）

</details>

**1.2.6-237.** Which protocol is responsible for controlling radio resources in an O-RAN network?

- A. RLC
- B. RRC
- C. SDAP
- D. SMO

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1159`）

</details>

**1.2.6-238.** What is the maximum number of PRBs of a UE carrier, for any SCS?

- A. 275
- B. 12
- C. 60
- D. 100

<details><summary>看答案</summary>

正解：A　（GSMA `srsranbench-train-617`）

</details>

**1.2.6-239.** What is eDRX?

- A. Extended Dynamic Resource Exchange
- B. Enhanced Device Radio Exchange
- C. Extreme Data Rate Expansion
- D. Extended Discontinuous Reception

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4735`）

</details>

**1.2.6-240.** What does the Relaxed monitoring for cell reselection feature in NB-IoT allow the UE to do? [3GPP Release 15]

- A. Avoid monitoring neighbouring cells for 24 hours in stationary or non-changing network topology
- B. Request NPUSCH resources for BSR transmission
- C. Reduce system acquisition time for the UE
- D. Support small cell deployments with lower maximum transmit power
- E. Improve the accuracy of narrowband measurement

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-110`）

</details>

**1.2.6-241.** Which power saving scheme achieves power consumption reduction by potentially skipping PDCCH monitoring at subsequent slots of PDSCH/PUSCH transmission? [3GPP Release 16]

- A. Cross-slot scheduling
- B. Same slot scheduling
- C. Multi-slot scheduling
- D. Dynamic DRX configuration

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-209`）

</details>

**1.2.6-242.** What are the enhanced RRM requirements in DRX in connected mode? [3GPP Release 14]

- A. Reduced cell identification delay and measurement period.
- B. Reduced cell detection delay, measurement period, and evaluation time.
- C. Reduced cell identification delay, measurement period, and evaluation time.
- D. Reduced cell detection delay and measurement period.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-311`）

</details>

**1.2.6-243.** How can power saving be enabled during active-time? [3GPP Release 18]

- A. By enabling PDCCH monitoring
- B. By eDRX configuration
- C. By adapting the minimum scheduling offsets
- D. By cross-slot scheduling

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-845`）

</details>

**1.2.6-244.** What is the on-duration of DRX? [3GPP Release 18]

- A. The duration that the UE monitors PDCCH
- B. The duration until a retransmission can be expected
- C. The duration that the UE waits for, after waking up, to receive PDCCHs
- D. The total duration that the UE monitors PDCCH

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-956`）

</details>

**1.2.6-245.** Which access control mechanisms are supported by NG-RAN? [3GPP Release 18]

- A. RACH back off
- B. RRC Connection Reject
- C. RRC Connection Release
- D. UE based access barring mechanisms
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1045`）

</details>

**1.2.6-246.** What is the purpose of dynamic resource schedulers in MAC in gNB? [3GPP Release 17]

- A. To allocate physical layer resources for downlink and uplink
- B. To configure the parameters of gNB and UE
- C. To measure radio conditions at the gNB
- D. To provide support for QoS-aware packet scheduling

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1275`）

</details>

**1.2.6-247.** Which feature in Rel-16 enables reduced UE power consumption in idle mode by transmitting a wakeup signal to a group of UEs? [3GPP Release 16]

- A. Scheduling of multiple DL/UL transport blocks with single DCI
- B. Mobile-terminated early data transmission (MT-EDT)
- C. Support for Preconfigured uplink resources (PUR) in idle mode
- D. UE-group wake-up signals (GWUS)
- E. Presence of NRS on a non-anchor carrier for paging

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1450`）

</details>

**1.2.6-248.** How can UE power consumption due to false paging alarms be reduced? [3GPP Release 17]

- A. By switching to a target SSSG
- B. By reducing PDCCH monitoring
- C. By relaxing UE measurements for RLM and/or BFD
- D. By providing TRS/CSI-RS occasions to idle/inactive-mode UEs
- E. By dividing UEs into multiple subgroups

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1524`）

</details>

**1.2.6-249.** What are the enhancements for idle/inactive-mode UE power saving in NR? [3GPP Release 17]

- A. Enhanced search space set group (SSSG) switching
- B. Provision of potential TRS/CSI-RS occasion(s) to idle/inactive-mode UEs
- C. Relaxation of UE measurements for RLM and/or BFD
- D. Paging enhancements to reduce UE reception power consumption
- E. PDCCH skipping mechanism

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1646`）

</details>

**1.2.6-250.** What is the purpose of the Provision of potential TRS/CSI-RS occasion(s) to idle/inactive-mode UEs? [3GPP Release 17]

- A. To reduce UE power consumption during data scheduling
- B. To reduce UE power consumption for PDCCH monitoring
- C. To reduce UE power consumption for RLM and/or BFD measurements
- D. To reduce UE power consumption for synchronization
- E. To reduce UE power consumption during subframe transmission

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1751`）

</details>

**1.2.6-251.** What is the purpose of the PDCCH-based power saving signal/channel for wake-up purpose? [3GPP Release 16]

- A. To provide assistance information to the network
- B. To skip the PDCCH during the next occurrence of the drx-onDurationTimer
- C. To indicate UE preference of transitioning out of RRC_CONNECTED state
- D. To reduce PDCCH monitoring on activated SCells
- E. To monitor the PDCCH during the next occurrence of the drx-onDurationTimer

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1783`）

</details>

**1.2.6-252.** What are the power components recommended to be considered for RRM measurement power saving evaluation in the CONNECTED state? [3GPP Release 16]

- A. Sleep
- B. PDCCH-only monitoring during active time
- C. SSB measurement
- D. Neighboring cell search
- E. Loop convergence (AGC, TTL & FTL) / time-frequency tracking

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1887`）

</details>

**1.2.6-253.** What is the purpose of Discontinuous Reception (DRX) in idle mode? [3GPP Release 17]

- A. To increase power consumption
- B. To reduce power consumption
- C. To increase data transfer rate
- D. To reduce data transfer rate
- E. To improve network coverage

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2152`）

</details>

**1.2.6-254.** How can UE power saving be enabled by relaxing measurements for RLM/BFD? [3GPP Release 17]

- A. By reducing PDCCH monitoring in connected mode
- B. By reducing UE power consumption during synchronization
- C. By reducing UE power consumption during idle/inactive mode
- D. By reducing UE power consumption during RAR/MsgB window monitoring
- E. By reducing UE power consumption during data scheduling

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2583`）

</details>

**1.2.6-255.** Which power saving scheme can potentially reduce the UE power consumption by reducing the number of PDCCH blind decoding? [3GPP Release 16]

- A. Triggering of PDCCH monitoring
- B. PDCCH skipping
- C. Go-to-sleep signaling
- D. Dynamic DRX configuration

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2694`）

</details>

**1.2.6-256.** How is power saving enabled during active-time? [3GPP Release 17]

- A. Cross-slot scheduling
- B. PDCCH monitoring adaptation mechanisms
- C. BWP switching
- D. DRX configuration
- E. RLM and BFD relaxation

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3396`）

</details>

**1.2.6-257.** What is VarRLF-Report used for? [3GPP Release 17]

- A. To store the radio link failure or handover failure information
- B. To store the successful handover information
- C. To store the random-access related information
- D. To store the mobility history information
- E. To store the connection establishment failure and/or connection resume failure information

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3446`）

</details>

**1.2.6-258.** What is the purpose of UE adaptation to BWP switching? [3GPP Release 16]

- A. To enhance the UE mobility
- B. To increase the data throughput
- C. To improve the network coverage
- D. To reduce the UE power consumption

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3846`）

</details>

**1.2.6-259.** How can UE power saving be achieved in RRC_IDLE/RRC_INACTIVE? [3GPP Release 17]

- A. By configuring TRS with CSI-RS
- B. By relaxing RLM/BFD measurements
- C. By utilizing PDCCH skipping
- D. By enabling cross-slot scheduling
- E. By configuring low mobility state

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4048`）

</details>

**1.2.6-260.** What is the purpose of the HandoverCommand message? [3GPP Release 17]

- A. To transfer the SCG radio configuration for one or more candidate cells for Conditional PSCell Addition (CPA) or Conditional PSCell Change (CPC)
- B. To transfer the handover command as generated by the target gNB
- C. To transfer the NR RRC information used by the target gNB during handover preparation or UE context retrieval
- D. To transfer the radio paging information, covering both upload to and download from the 5GC, and between gNBs
- E. To transfer UE radio access capability information, covering both upload to and download from the 5GC

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4353`）

</details>

**1.2.6-261.** What are the power components recommended to be considered for RRM measurement power saving evaluation in the IDLE/INACTIVE state? [3GPP Release 16]

- A. Loop convergence (AGC, TTL & FTL) / time-frequency tracking
- B. SSB bursts used for Loop convergence
- C. Paging
- D. SIB1 decoding
- E. Sleep

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4687`）

</details>

**1.2.6-262.** What is Access Class Barring (ACB) in the context of random access?

- A. A scheme to prioritize access based on access periodicity
- B. A scheme to prioritize access for certain devices
- C. A scheme to allocate resources dynamically
- D. A scheme to control back-off times for devices
- E. A scheme to defer devices to transmit preamble

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4732`）

</details>

**1.2.6-263.** What power saving gain range is observed for the power saving scheme with PDCCH skipping or 'go-to-sleep' signal? [3GPP Release 16]

- A. 9% - 83%
- B. 2% - 15%
- C. 50% - 85%
- D. 4% - 11%

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5027`）

</details>

**1.2.6-264.** What happens to packet duplication during MgNB (Master gNB) handover event?

- A. Packet duplication is deactivated
- B. Packet duplication is retained
- C. Packet duplication is enhanced
- D. Packet duplication is dropped

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5153`）

</details>

**1.2.6-265.** What is the purpose of packet duplication for signaling radio bearers?

- A. To split user data in multiple carriers
- B. To achieve robustness and RRC diversity
- C. To improve mobility robustness during handover
- D. To dynamically control packet duplication
- E. To eliminate duplicate packets in the receiver

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5211`）

</details>

**1.2.6-266.** What is the purpose of the proportional fair scheduler?

- A. To maximize the average throughput for all users
- B. To prioritize users with the highest requested rates
- C. To ensure fairness among users with asymmetric channel conditions
- D. To minimize the latency time-scale of the system

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5247`）

</details>

**1.2.6-267.** What is the impact of increasing paging cycle durations for delay-tolerant M2M (machine-to-machine) devices?

- A. Increases power consumption
- B. Decreases power consumption
- C. Has no impact on power consumption
- D. Stabilizes power consumption

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5440`）

</details>

**1.2.6-268.** What does 'Camped on a cell' mean?

- A. The combined losses of all transmission system components
- B. A piece of information indicating general 3GPP System mobile station characteristics
- C. A link between the card and the external world
- D. The UE is in idle mode and has chosen a cell
- E. A modulation and coding method intended for the transmission of text in voice channels

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5911`）

</details>

**1.2.6-269.** What relaxation is allowed for neighbor cell RRM (radio resource management) measurements in Release 16?

- A. No relaxation is allowed
- B. Relaxation based on inter-arrival times of data packets
- C. Relaxation based on low-mobility and not-at-cell-edge conditions
- D. Relaxation based on interference levels

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5941`）

</details>

**1.2.6-270.** What is the purpose of Bandwidth Adaptation (BA)? [3GPP Release 18]

- A. To adjust the width, location, and subcarrier spacing of the UE's receive and transmit bandwidth
- B. To compress and decompress headers
- C. To map QoS flows to data radio bearers
- D. To multiplex and demultiplex MAC SDUs

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6034`）

</details>

**1.2.6-271.** What is the purpose of packet duplication for mobility robustness?

- A. To split user data in multiple carriers
- B. To perform make-before-break handover
- C. To dynamically control packet duplication
- D. To eliminate duplicate packets in the receiver
- E. To improve the robustness of data and RRC signaling during handover

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6282`）

</details>

**1.2.6-272.** What is the power saving gain range for the power saving schemes with UE adaptation to BWP switching? [3GPP Release 16]

- A. 5% - 16%
- B. 16% - 31%
- C. 45% - 57.75%
- D. 5% - 45%

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6496`）

</details>

**1.2.6-273.** Which mobility is supported for cell reselection between NR RRC_IDLE and E-UTRA RRC_IDLE? [3GPP Release 18]

- A. Intra 5GC
- B. From 5GC to EPC
- C. From EPC to 5GC
- D. NR-UTRA mobility
- E. NR-E-UTRA mobility

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6904`）

</details>

**1.2.6-274.** What does URA updating refer to?

- A. A family of procedures that updates the UTRAN registration area of a UE
- B. A radio interface between UTRAN and the User Equipment
- C. A physically secure device used for accessing services provided by mobile networks
- D. A unidirectional radio link for the transmission of signals from a UE to a base station
- E. A set of actions taken by the network to monitor and control the offered traffic

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6989`）

</details>

**1.2.6-275.** What is the aim of throughput fairness scheduling?

- A. To optimize the utilization of resources
- B. To maximize the system throughput
- C. To ensure fairness among individual nodes
- D. To minimize the implementation complexity
- E. To meet QoS criteria

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7095`）

</details>

**1.2.6-276.** When is DCP monitored by the UE? [3GPP Release 18]

- A. During active-time and BWP switching
- B. During on-duration and retransmission
- C. During measurement gaps and CFRA preamble transmission
- D. During active-time and before the on-duration

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7392`）

</details>

**1.2.6-277.** Which relaxation criteria should be treated with higher priority in RRM measurement relaxation? [3GPP Release 16]

- A. UE mobility status and serving cell beam status
- B. Link quality and UE mobility status
- C. UE is not at cell edge and UE mobility status
- D. UE mobility status and exact relaxation criteria
- E. UE mobility status and UE type

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7900`）

</details>

**1.2.6-278.** What benefit does packet duplication provide in the control plane?

- A. Improved reliability by providing frequency and path diversity
- B. Reduced latency by avoiding retransmissions
- C. Reduced jitter by minimizing variance in latency
- D. Improved handover performance
- E. RRC diversity for important signaling messages

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7959`）

</details>

## 1.2.7 核心網信令：NAS、NGAP、GTP、Diameter、SBI（75 題）

**1.2.7-1.** What is the purpose of the Signalling gateway function? [3GPP Release 17]

- A. To interconnect different signalling networks
- B. To provide voice and other CS-domain services
- C. To support charging and billing mechanisms
- D. To facilitate communications with packet data networks and applications
- E. To enable Proximity-based Services

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1960`）

</details>

**1.2.7-2.** What is the definition of 5GMM-CONNECTED mode?

- A. A UE in 5GMM-CONNECTED mode means the UE is connected to the 5G core network via 3GPP access.
- B. A UE in 5GMM-CONNECTED mode means the UE is connected to the 5G core network via non-3GPP access.
- C. A UE in 5GMM-CONNECTED mode means the UE can be either in 5GMM-CONNECTED mode over 3GPP access or in 5GMM-CONNECTED mode over non-3GPP access.
- D. A UE in 5GMM-CONNECTED mode means the UE is not connected to any access network.
- E. A UE in 5GMM-CONNECTED mode means the UE is not registered with any PLMN or SNPN.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7035`）

</details>

**1.2.7-3.** What does the AMF do after purging the subscriber data and MM context of a deregistered UE? [3GPP Release 18]

- A. Initiates an AMF initiated Deregistration procedure
- B. Unsubscribes to changes to subscription data using Nudm_SDM_Unsubscribe request operation
- C. Updates UE context in UDR by Nudr_DM_Update (SUPI, Subscription Data)
- D. Sets the UE Purged flag associated with the Access Type

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7061`）

</details>

**1.2.7-4.** What are the two main parts of the network selection procedure for the UE? [3GPP Release 18]

- A. PLMN selection and access network selection
- B. PEI check and EIR authentication
- C. RRC Connection and NAS message transmission
- D. Unified Access Control and AMF request
- E. Operator-defined access category and Lawful Interception

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7401`）

</details>

**1.2.7-5.** What is the purpose of PLMN selection in the UE? [3GPP Release 17]

- A. To identify the selected PLMN
- B. To automatically connect to the strongest cell
- C. To optimize PLMN search using stored information
- D. To report available PLMNs to the NAS on request
- E. To perform cell selection procedure for camp on

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7683`）

</details>

**1.2.7-6.** When does a Multi-USIM UE indicate the supported Multi-USIM features to the AMF during the Registration procedure? [3GPP Release 18]

- A. When it has more than one USIM active
- B. When it has only one USIM active
- C. When it requests connection release
- D. When it requests paging restriction
- E. None of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-508`）

</details>

**1.2.7-7.** What happens when the Control Plane data back-off timer is running? [3GPP Release 18]

- A. The UE cannot initiate any data transfer via Control Plane CIoT 5GS Optimization
- B. The AMF stops processing any further requests (except for exception reporting and paging response) for data transport via Control Plane Service Request from that UE
- C. The UE is allowed to initiate Service Request procedures for activating User Plane connection
- D. The UE is allowed to initiate Session Management procedures for emergency services

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-569`）

</details>

**1.2.7-8.** In which mode does an MS store the forbidden tracking area identity (TAI) in a list for regional provision of service? [3GPP Release 18]

- A. A/Gb mode
- B. Iu mode
- C. S1-mode
- D. N1-mode

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-647`）

</details>

**1.2.7-9.** What information is included in the Location Report message when the NG-RAN detects that the UE has moved out of or into multiple areas of interest? [3GPP Release 18]

- A. UE Location
- B. UE Presence in Area Of Interest
- C. Request Reference ID
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-941`）

</details>

**1.2.7-10.** What happens when a registration attempt is rejected with a cause of 'permanent' PLMN restriction? [3GPP Release 18]

- A. The PLMN is added to the forbidden PLMNs list
- B. The UE enters the limited service state
- C. The UE stores the location area or tracking area in a forbidden list
- D. The UE searches for a suitable cell in the same PLMN
- E. The UE performs an investigation scan for a higher priority PLMN

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1135`）

</details>

**1.2.7-11.** Which event notification is used to monitor the movement of candidate UEs in/out of the monitoring area? [3GPP Release 18]

- A. Namf_EventExposure_Subscribe service
- B. Npcf_PolicyAuthorization_Create request
- C. Nnef_AFsessionWithQoS_Revoke
- D. Namf_EventExposure_Notify service
- E. PDU session modification

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1176`）

</details>

**1.2.7-12.** Which USIM registration triggers the allocation of a new 5G-GUTI for the Paging Timing Collision Control feature? [3GPP Release 18]

- A. Emergency registration
- B. Normal registration
- C. Connection release
- D. Paging restriction
- E. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1263`）

</details>

**1.2.7-13.** What is the responsibility of the network in the call control protocol? [3GPP Release 18]

- A. Establishing a MM connection
- B. Activating integrity protection
- C. Exchanging messages across the radio interface
- D. Communicating internally with other protocol (sub)layers

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1488`）

</details>

**1.2.7-14.** How does a Multi-USIM UE indicate to the network that it does not accept the paging and requests to return to CM-IDLE state? [3GPP Release 17]

- A. By sending a specific AT command.
- B. By sending a Paging Restriction request to the network.
- C. By sending a UEAssistanceInformation message.
- D. By sending a Reject Paging response to the network.
- E. By sending a Service Request message.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1677`）

</details>

**1.2.7-15.** What procedure can be initiated by the network or the UE (User Equipment) to release an ongoing PDU (Protocol Data Unit) session?

- A. UE Configuration Update
- B. Registration
- C. PDU Session Release
- D. PDU Session Establishment
- E. AMF Relocation

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1979`）

</details>

**1.2.7-16.** How does a Multi-USIM UE modify the timing of paging occasions in 5GS? [3GPP Release 17]

- A. By obtaining a new 5G-GUTI through a specific indication.
- B. By triggering a new 5G-GUTI reallocation without any specific indication.
- C. By requesting a 5G-GUTI reallocation from the network.
- D. By providing an IMSI offset value in the Attach Request message.
- E. By performing a MRU and obtaining a new 5G-GUTI.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2212`）

</details>

**1.2.7-17.** What is Location Registration (LR)?

- A. The control of logical resources owned by the RNC
- B. The command/response communication context between the ME and the UICC
- C. The process of a UE registering its presence in a specific area
- D. The transfer of a specific type of information over the radio interface
- E. The signalling associated with the control of logical resources

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2270`）

</details>

**1.2.7-18.** What does the NEF (PFDF) send in response to the SMF after PFD retrieval? [3GPP Release 18]

- A. Nnef_PFDManagement_Subscribe
- B. Nudr_DM_Query
- C. Nnef_PFDManagement_Create/Update/Delete
- D. Nnef_PFDManagement_Fetch

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2320`）

</details>

**1.2.7-19.** How does the RNC indicate the UE selected core network operator to the CN for supporting UEs? [3GPP Release 17]

- A. By sending a Target ID in the Relocation Required message
- B. By sending an RRC signalling message
- C. Implicitly from an already existing signalling connection
- D. By transmitting it in broadcast system information
- E. By using the SNA Access Information IE

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2421`）

</details>

**1.2.7-20.** What does the NEF (PFDF) do after determining whether to create/update/delete PFDs? [3GPP Release 18]

- A. Invokes Nudr_DM_Query
- B. Invokes Nnef_PFD_Management_Notify
- C. Invokes Nnef_PFDManagement_Subscribe
- D. Invokes Nnef_PFDManagement_Create/Update/Delete

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2471`）

</details>

**1.2.7-21.** When does the need for NG-RAN to continue reporting the UE's location cease? [3GPP Release 18]

- A. When the UE transitions to CM-IDLE state
- B. When the UE receives a cancel indication from the AMF
- C. When the NG-RAN sends a cancel indication to the AMF
- D. When the UE moves out of or into an area of interest
- E. When Dual Connectivity is activated

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2479`）

</details>

**1.2.7-22.** What does the NG-RAN do immediately following step 1a of the Connection Inactive procedure? [3GPP Release 18]

- A. Sends N2 MT Communication Handling request message to AMF
- B. Sends RRC message to suspend the RRC Connection towards the UE
- C. Sends Nsmf_PDUSession_UpdateSMContext Request to AMF
- D. Sends N4 Session Modification Request to UPF

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2537`）

</details>

**1.2.7-23.** What happens if a UE wants to access the 5GS and is configured for Extended Access Barring (EAB)? [3GPP Release 18]

- A. Unified Access Control checks are performed for Access Category 1
- B. Unified Access Control checks are ignored for Access Category 1
- C. Unified Access Control checks are performed for Access Category 2
- D. Unified Access Control checks are ignored for Access Category 2
- E. Unified Access Control checks are not supported by the UE

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2564`）

</details>

**1.2.7-24.** Does a UE support a secure mechanism for the home operator to disallow selection of one or more of its radio technologies, regardless of PLMNs? [3GPP Release 18]

- A. Yes
- B. No

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2677`）

</details>

**1.2.7-25.** How does the UE report a change in its 3GPP PS Data Off status? [3GPP Release 18]

- A. Through the ATSSS Control procedure.
- B. Through the non-Allowed Area reporting procedure.
- C. Through the UE requested PDU Session Modification procedure.
- D. Through the IMS domain enforcement procedure.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3077`）

</details>

**1.2.7-26.** What message is sent by the MS to the network to request the release of a GMM context? [3GPP Release 18]

- A. Detach request (mobile terminated detach)
- B. Detach request (mobile originating detach)
- C. Detach accept (mobile terminated detach)
- D. Detach accept (mobile originating detach)

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3262`）

</details>

**1.2.7-27.** What does the NAS protocol on N1 comprise of? [3GPP Release 18]

- A. NAS-MM and NAS-SM
- B. NAS-LTE and NAS-3GPP
- C. NAS-RAN and NAS-AN
- D. NAS-UPF and NAS-SMF
- E. NAS-NSA and NAS-SA

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3474`）

</details>

**1.2.7-28.** What is the definition of Signalling?

- A. The exchange of information between the user equipment and the core network
- B. The transfer of higher layer information between entities in the non-access stratum
- C. The establishment and control of connections in a telecommunications network
- D. The transmission of user data over a radio link
- E. The switching of calls between different networks

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3559`）

</details>

**1.2.7-29.** What is the definition of 5GMM-IDLE mode over 3GPP access?

- A. A UE is in 5GMM-IDLE mode over 3GPP access when an N1 NAS signalling connection between the UE and network over 3GPP access exists.
- B. A UE is in 5GMM-IDLE mode over 3GPP access when no N1 NAS signalling connection between the UE and network over 3GPP access exists.
- C. A UE is in 5GMM-IDLE mode over 3GPP access when there is no RRC connection via the Uu reference point.
- D. A UE is in 5GMM-IDLE mode over 3GPP access when there is no IPsec tunnel via the NWu reference point.
- E. A UE is in 5GMM-IDLE mode over 3GPP access when there is no access stratum connection between the UE and the NG-RAN for 3GPP access.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3971`）

</details>

**1.2.7-30.** What is the behavior of a mobile station in the MM IDLE state with service state NO IMSI? [3GPP Release 18]

- A. Perform normal location updating when a new location area is entered
- B. Perform default cell selection
- C. Not perform IMSI detach if powered down
- D. Reject any request from CM entities for MM connections except for emergency calls
- E. Only perform periodic updating

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3985`）

</details>

**1.2.7-31.** Which state exists when the network has received an answer but the network has not yet awarded the call? [3GPP Release 18]

- A. Connect request (N8)
- B. Mobile terminating call confirmed (N9)
- C. Active (N10)
- D. Disconnect indication (N12)

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4023`）

</details>

**1.2.7-32.** What happens when an IP packet arrives at the UPF for a UE that is CM-IDLE? [3GPP Release 18]

- A. The UE sends a Data Notification to the SMF.
- B. The SMF sends a Paging Priority to the AMF.
- C. The UPF sends a Data Notification to the SMF.
- D. The AMF updates the ARP for the Signalling QoS Flows.
- E. The SMF updates the ARP for the Signalling QoS Flows.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4282`）

</details>

**1.2.7-33.** What does the NAS-SM support in the control plane between the UE and the SMF? [3GPP Release 18]

- A. Handling of Session Management between the UE and the SMF
- B. Interpretation of SM signalling messages by the AMF
- C. Creating and processing of SM signalling messages by the AMF
- D. Transport of SM signalling messages between the UE and the AMF
- E. Decryption and encryption of SM signalling messages by the AMF

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4367`）

</details>

**1.2.7-34.** What can the AMF do if it accepts the Paging Restriction Information requested by the UE? [3GPP Release 18]

- A. Store the Paging Restriction Information in the UE context
- B. Reject the Paging Restriction Information
- C. Trigger the AN release procedure
- D. Provide the UE with a new 5G-GUTI
- E. None of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4584`）

</details>

**1.2.7-35.** When is PSCell information reported by the NG-RAN? [3GPP Release 18]

- A. Only when requested by the AMF
- B. Only when Dual Connectivity is activated
- C. Both when requested by the AMF and when Dual Connectivity is activated
- D. PSCell information is never reported by the NG-RAN
- E. PSCell information is always reported by the NG-RAN

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4666`）

</details>

**1.2.7-36.** What is the procedure for notifying a mobile station of an appropriate call-related event during the 'active' state? [3GPP Release 18]

- A. Sending a MODIFY message to the mobile station
- B. Sending a SETUP message to the mobile station
- C. Sending a CALL CONFIRMED message to the mobile station
- D. Sending a NOTIFY message to the mobile station

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4700`）

</details>

**1.2.7-37.** What is the purpose of the Message Priority header in messages exchanged over service-based interfaces? [3GPP Release 18]

- A. To prioritize flows based on subscription information
- B. To indicate priority information
- C. To establish prioritized QoS Flows
- D. To fulfill the QoS characteristics of QoS Flows
- E. To differentiate treatment for prioritized QoS Flow

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4817`）

</details>

**1.2.7-38.** Which of the following situations can lead to the MS being unable to obtain normal service from a PLMN or SNPN? [3GPP Release 18]

- A. Failure to find a suitable cell of the selected PLMN or SNPN
- B. No SIM in the MS
- C. A PLMN not allowed response in case of PLMN
- D. An illegal ME response when an LR is received
- E. MS supporting CAG is camped on a CAG cell

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4847`）

</details>

**1.2.7-39.** What is the mode of operation of the MS when connected to the Core Network via GERAN and the A and/or Gb interfaces?

- A. ANCFS
- B. Active Set
- C. Access Stratum
- D. Access protocol
- E. A/Gb mode

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5007`）

</details>

**1.2.7-40.** What happens during the PDU (Protocol Data Unit) Session Establishment process?

- A. UE authentication/authorization with external DN, UPF(s) selection, IP address allocation, and communicating the SM parameters to UE and RAN
- B. UE authentication/authorization with external DN, PCF selection, UPF(s) selection, IP address allocation, and communicating the SM parameters to UE and RAN
- C. UE authentication/authorization with external DN, PCF selection, IP address allocation, and session establishment with AMF
- D. Session Management (SM) subscription retrieval, PCF selection, UPF(s) selection, IP address allocation, and communicating the SM parameters to UE and RAN
- E. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5103`）

</details>

**1.2.7-41.** When does a Multi-USIM UE include Paging Restriction Information in the Service Request or Registration Request message? [3GPP Release 18]

- A. When it wants to restrict all paging
- B. When it wants to restrict paging for voice service only
- C. When it wants to restrict paging for certain PDU session(s)
- D. When it wants to restrict paging for voice service and certain PDU session(s)
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5337`）

</details>

**1.2.7-42.** How can N2 overload control be achieved by the AMF? [3GPP Release 18]

- A. By adjusting the weight factor of the AMF
- B. By invoking the N2 overload procedure to 5G-AN nodes
- C. By sending a Control Plane data back-off timer to the UE
- D. By using Session Management Congestion Control Experience analytics provided by NWDAF

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5400`）

</details>

**1.2.7-43.** Which interface is used to support mobility and bearer management between the MME and S-GW? [3GPP Release 17]

- A. S1-MME-interface
- B. S1-U-interface
- C. S11-interface
- D. S6a-interface
- E. S5-interface

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5407`）

</details>

**1.2.7-44.** In a shared UTRAN/GERAN network, what does the RAN node do when the UE is allowed to attach? [3GPP Release 17]

- A. The RAN node forwards the NAS message to the UE and cleans up any stored redirect data
- B. The RAN node selects a CN node based on the NRI received from the UE
- C. The RAN node sends a Reroute Command message to the Core Network
- D. The RAN node queries the SGSN to determine if the UE is allowed to attach
- E. The RAN node sends an ATTACH REQUEST message to the network

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5428`）

</details>

**1.2.7-45.** Which component provides priority handling for the Initial UE Message during Registration procedures? [3GPP Release 18]

- A. (R)AN
- B. PCF
- C. UPF
- D. SMF
- E. AMF

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5496`）

</details>

**1.2.7-46.** Which procedures are involved in the PDU (Protocol Data Unit) Session (Re-)Establishment process?

- A. UE authentication/authorization with external DN, PCF selection, UPF(s) selection, IP address allocation, and communicating the SM parameters to UE and RAN
- B. UE authentication/authorization with external DN, PCF selection, UPF(s) selection, Session Management (SM) subscription retrieval, and IP address allocation
- C. UE authentication/authorization with external DN, PCF selection, IP address allocation, session establishment with AMF, and communicating the SM parameters to UE and RAN
- D. Session Management (SM) subscription retrieval, PCF selection, UPF(s) selection, and IP address allocation
- E. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5796`）

</details>

**1.2.7-47.** What does RANAP stand for?

- A. The service that the access stratum provides to the non-access stratum for transfer of user data between User Equipment and CN.
- B. The mode of the cell, FDD or TDD.
- C. Functionality supporting the exchange of information between peer application entities located in a GERAN or in a UTRAN access network.
- D. Two or more CN operators share the same RAN.
- E. Radio Network Signaling over the Iu.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5977`）

</details>

**1.2.7-48.** What is the primary service state selected after power on? [3GPP Release 18]

- A. No IMSI
- B. Location Update Needed
- C. Normal Service
- D. Limited Service
- E. eCall Inactive

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6017`）

</details>

**1.2.7-49.** What is the recommended behavior for a UE regarding excessive signaling load during the Paging Timing Collision Control procedure? [3GPP Release 18]

- A. Avoid signaling load from UE
- B. Initiate the AN release procedure
- C. Continue with the normal registration procedure
- D. Request the network to reduce signaling load
- E. None of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6087`）

</details>

**1.2.7-50.** What criteria are considered for periodic network selection attempts? [3GPP Release 18]

- A. Signal quality and coverage area
- B. Priority and availability of PLMNs
- C. User preferences and network agreements
- D. Forbidden PLMNs and hysteresis function
- E. Potential for PS services and PLMN restrictions

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6122`）

</details>

**1.2.7-51.** How does the network provide the paging cause field for voice service to a Multi-USIM UE? [3GPP Release 17]

- A. By sending a specific indication to the UE.
- B. By including the field in the paging message.
- C. By sending a separate notification message.
- D. By sending a dedicated paging request.
- E. By providing an indication in the downlink data.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6448`）

</details>

**1.2.7-52.** When does a mobile station enter the GMM-DEREGISTERED state? [3GPP Release 18]

- A. When a GPRS attach or combined GPRS attach procedure is performed
- B. When a GMM procedure has failed
- C. When a GPRS detach or combined GPRS detach procedure is performed
- D. When the MS is switched on
- E. When the MS is IMSI attached for GPRS services only

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6481`）

</details>

**1.2.7-53.** What message does the AMF send to the NG-RAN during mobility registration, AM policy modification, and handover procedures? [3GPP Release 18]

- A. 5G access stratum time distribution indication
- B. Uu time synchronization error budget
- C. Clock quality detail level
- D. UE Context Modification Request
- E. N2 connection

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6596`）

</details>

頁次：[1](1-2-gsma-1.md)　[2](1-2-gsma-2.md)　**3**　[4](1-2-gsma-4.md)　[5](1-2-gsma-5.md)　[6](1-2-gsma-6.md)　[7](1-2-gsma-7.md)
