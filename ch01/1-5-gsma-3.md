# 1.5 開放與虛擬化　GSMA 練習題（909 題）（第 3／5 頁）

所屬：[1.5 開放與虛擬化](1-5.md)

只收 GSMA 訓練題；不含驗證集與測試集，並已去除和驗證／測試題相同或相似、重複、標註衝突的題目。題目依小節歸類（抽查正確率約 95%）。

頁次：[1](1-5-gsma-1.md)　[2](1-5-gsma-2.md)　**3**　[4](1-5-gsma-4.md)　[5](1-5-gsma-5.md)

## 1.5.3 O-RAN 介面：A1、E2、O1、O2、開放前傳（388 題）（續）

**1.5.3-103.** What are the two possible designs for an O-RU that does not support beamforming?

- A. Two tx-arrays each with one polarization and one tx-array with two polarizations.
- B. One tx-array with one polarization and one tx-array with two polarizations.
- C. One tx-array with one polarization and two tx-arrays with two polarizations.
- D. Two tx-arrays each with two polarizations.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-359`）

</details>

**1.5.3-104.** In an O-RAN system with a guard-band NB-IoT carrier, how does the O-DU handle the situation where the PRB grid of the NB-IoT carrier is not aligned with the PRB grid of the host carrier?

- A. The O-DU ignores the misalignment and processes data as usual.
- B. The O-DU reconfigures the O-RU to adjust the PRB grid alignment.
- C. The O-DU extracts required resources from adjacent PRBs in U-plane messages received from the O-RU.
- D. The O-DU requests the host carrier to adjust its PRB grid to match the NB-IoT carrier.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-364`）

</details>

**1.5.3-105.** What is a critical consideration in managing shared O-RUs during an O-DU software update?

- A. Preventing O-RU restart following the software update.
- B. Ensuring dedicated O-RUs are available for all O-DUs.
- C. Choosing an O-DU with the most up-to-date software version.
- D. Limiting the number of O-DUs sharing an O-RU.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-370`）

</details>

**1.5.3-106.** Which type of O-RU is this test applicable for?

- A. Category A
- B. Category B
- C. Category C
- D. All categories

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-372`）

</details>

**1.5.3-107.** Which of the following O-RAN WG5 defined YANG models allows for the O-DU to expose support for optional capabilities?

- A. "urn:ietf:params:xml:ns:yang:ietf-interfaces"
- B. "urn:ietf:params:xml:ns:yang:ietf-ip"
- C. "urn:ietf:params:xml:ns:yang:ietf-netconf"
- D. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-374`）

</details>

**1.5.3-108.** Which of the following is NOT a test scenario for the A1-EI Producer component in an O-RAN architecture?

- A. Query EI types
- B. Create EI job
- C. Update EI job
- D. Configure RIC platform

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-379`）

</details>

**1.5.3-109.** Which of the following conditions is NOT a prerequisite for installing software on an O-RU?

- A. The M-Plane NETCONF session is established.
- B. At least one software slot in the O-RU has the status "active::True" and "running::True".
- C. The software download is complete, and all necessary files are available on the O-RU.
- D. The O-RU Controller is subscribed to receive install-event notifications.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-383`）

</details>

**1.5.3-110.** What is the primary communication protocol used between the O-DU and the O-RU?

- A. F1AP
- B. NGAP
- C. FH-eCPRI
- D. FAPI

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-384`）

</details>

**1.5.3-111.** What is the purpose of the `<start-troubleshooting-logs>` RPC in an O-RU8?

- A. To stop collecting troubleshooting logs.
- B. To notify the O-RU8 controller that a troubleshooting log file has been created.
- C. To trigger the O-RU8 to start collecting and storing troubleshooting logs in a file.
- D. To delete existing troubleshooting log files.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-396`）

</details>

**1.5.3-112.** What is the primary purpose of the O-RAN O2 interface?

- A. To define O-RAN O-Cloud functions and protocols.
- B. To manage and control the O-RAN network.
- C. To provide a secure connection between O-RAN components.
- D. To ensure interoperability between different O-RAN vendors.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-406`）

</details>

**1.5.3-113.** What is the purpose of the "UC-Plane O-RU Scenario Class Beamforming 3GPP UL – Flexible Real Time Weights Beamforming" test?

- A. To ensure the radio can transmit a basic 3GPP test frame with weight-based beamforming.
- B. To ensure the radio can receive a basic 3GPP test frame with weight-based beamforming.
- C. To test the performance of the radio's signal analyzer.
- D. To verify the accuracy of the O-RU's antenna array characteristics.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-408`）

</details>

**1.5.3-114.** Which of the following is NOT a synchronization technology discussed in the provided context?

- A. PTP
- B. SyncE
- C. GNSS
- D. LTE

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-414`）

</details>

**1.5.3-115.** What is the purpose of the "laaMsgType" parameter in an O-RAN C-Plane message?

- A. To define the length of the LAA message.
- B. To identify the type of LAA message being transmitted.
- C. To provide a label for the LAA message.
- D. To manage the Listen Before Talk (LBT) operation.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-416`）

</details>

**1.5.3-116.** What is the purpose of the 'sectionId' field in the context of O-RAN?

- A. To identify a specific resource block.
- B. To ensure that a resource element is referenced by only one section description.
- C. To distinguish between section descriptions that are applicable to the same PRB and those that are not.
- D. To provide a unique identifier for each section description within a slot.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-418`）

</details>

**1.5.3-117.** In a Multi Operator Shared O-RU scenario, what is the purpose of the "callHomeClientInfo" field?

- A. To configure multiple call home addresses for each Shared O-RU towards the Shared O-RU Host O-DU.
- B. To provide information about the primary O-DU in a Single Operator Shared O-RU.
- C. To list the identities of Shared O-RUs connected to the Shared O-RU Host O-DU.
- D. To configure the secondary O-DUs in a Single Operator Shared O-RU.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-419`）

</details>

**1.5.3-118.** Which of the following is a mandatory configuration parameter for low-level-tx-endpoints and low-level-rx-endpoints in a Shared O-RU Host?

- A. sro-id
- B. tx-array-carriers
- C. rx-array-carriers
- D. static-low-level-tx-endpoints

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-424`）

</details>

**1.5.3-119.** What is the primary objective of the ORAN.WG8.IOT.057 test case?

- A. To verify the functionality of the O-RU's beam failure detection and recovery mechanisms.
- B. To ensure the proper configuration of the O-CU's NR RRC, NR PDCP, and SDAP modules.
- C. To test the communication between the O-DU and the 5GC through the NG interface.
- D. To evaluate the performance of the O-RAN network in a real-world scenario.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-429`）

</details>

**1.5.3-120.** In an O-RAN system, how does the O-RU determine the transmission scheme?

- A. By analyzing the signal strength of the received data.
- B. By using the txScheme field in the C-Plane precoding Section Extension.
- C. By consulting the precoding parameters defined in the 3GPP standards.
- D. By monitoring the network traffic patterns.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-437`）

</details>

**1.5.3-121.** What is the relationship between the frequency-related parameters of a PRACH occasion and the parameters startPrbc and numPrbc?

- A. The frequency-related parameters determine the values of startPrbc and numPrbc.
- B. startPrbc and numPrbc are independent of the frequency-related parameters.
- C. The frequency-related parameters are used to calculate the values of startPrbc and numPrbc.
- D. The relationship between the frequency-related parameters and startPrbc and numPrbc is not defined.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-439`）

</details>

**1.5.3-122.** In an O-RAN network, what interface is used for the Near-RT RIC to communicate with the RAN (Radio Access Network)?

- A. A1
- B. O1
- C. E2
- D. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-442`）

</details>

**1.5.3-123.** In the context of O-RAN Delay Management, what is the size of the control plane reception window on the O-RU?

- A. (T2a_max_up + Tcp_adv_dl) – (T2a_min_up + Tcp_adv_dl)
- B. T2a_max_up - T2a_min_up
- C. T2a_max_up + Tcp_adv_dl
- D. T2a_min_up + Tcp_adv_dl

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-443`）

</details>

**1.5.3-124.** What is the main objective of the "Transparency of eCPRI Ethertype" test?

- A. To verify that the device can be managed both in-band and out-of-band.
- B. To measure the latency, jitter, and throughput of different encapsulation protocols.
- C. To ensure that frames with eCPRI Ethertype are not discarded by the device.
- D. To compare the performance of different eCPRI Ethertype implementations.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-449`）

</details>

**1.5.3-125.** Which of the following beam configurations is NOT included in the "Coarse" beamIds test for O-RAN CUS Beamforming conformance?

- A. A coarse beam with 0 degrees azimuth (Φ) and elevation (θ) angles.
- B. A coarse beam with maximum supported azimuth angle (Φ) and minimum supported elevation angle (θ).
- C. A coarse beam with maximum supported azimuth angle (Φ) and 0 degrees elevation (θ) angles.
- D. A coarse beam with minimum supported azimuth angle (Φ) and minimum supported elevation angle (θ).

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-451`）

</details>

**1.5.3-126.** In an O-RAN LLS-C4 configuration with frequency backup from the T-GM, what happens if the link between the O-DU and HSR-F fails?

- A. The T-GM B becomes the active synchronization source.
- B. The PTP path from the O-DU+CU 2 to the HSR-F 1 becomes active.
- C. The HSR-B B becomes the active synchronization source.
- D. The HSR A becomes the active synchronization source.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-457`）

</details>

**1.5.3-127.** What is the proposed maximum latency network asymmetry for negligible impact on geolocation time measurement in O-RAN fronthaul?

- A. 10,000 ns
- B. 32.5 ns
- C. 3 ns
- D. 0.8 ns

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-458`）

</details>

**1.5.3-128.** Which standard defines the "Timing and synchronization aspects in packet networks"?

- A. ITU-T G.8261
- B. IEEE 1588v2
- C. IETF RFC 8200
- D. 3GPP TS 33.117 V16.2.0

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-460`）

</details>

**1.5.3-129.** In the downlink case, how does the FHM handle eCPRI messages received from the O-DU?

- A. FHM modifies the eCPRI message header and payload before forwarding to O-RUs.
- B. FHM only forwards the eCPRI payload to the O-RUs.
- C. FHM copies the entire eCPRI message (header and payload) without modification and forwards it to the O-RUs.
- D. FHM extracts the eCPRI payload and sends it to the O-RUs in a new Ethernet frame.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-474`）

</details>

**1.5.3-130.** What is the purpose of the "Policy feedback (positive case)" test scenario in the context of O-RAN?

- A. To test the functionality of the DUT to request and receive policy status updates.
- B. To test the ability of the DUT to generate a PolicyStatusObject based on the agreed policy type.
- C. To ensure the DUT has an HTTP server ready to receive HTTP requests from the test simulator.
- D. To verify the successful policy status request and reception by the DUT.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-477`）

</details>

**1.5.3-131.** In an LLS-C2 configuration, what happens if a Denial-of-Service (DoS) attack targets the master clock within the O-DU?

- A. All O-RUs connected to the affected O-DU will lose network timing.
- B. Only the O-RU directly connected to the affected O-DU will lose network timing.
- C. A neighboring O-DU can take over as the master clock and distribute timing to all affected O-RUs.
- D. The network will automatically reconfigure itself to use a different timing source.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-481`）

</details>

**1.5.3-132.** What is the purpose of the "numSlotsExt" field in the Section Type 4 command?

- A. To specify the number of slots for which the command configuration is valid.
- B. To extend the number of slots specified by the "numSlots" field.
- C. To identify the ACK/NACK request ID for a Section Type 8 command.
- D. To define the sleep mode for the device.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-484`）

</details>

**1.5.3-133.** How is the quality of the O-DU timing output measured for LLS C1/C2 performance tests?

- A. Through the DUT's Fronthaul Ethernet Port
- B. Through a spare Master PTP/SyncE Ethernet Port
- C. Through the 1 PPS output port
- D. Through a directly connected Time Reference

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-485`）

</details>

**1.5.3-134.** In an O-RU DUT supporting Digital Beamforming, how many beams can be tested per slot?

- A. One
- B. Two
- C. Four
- D. Eight

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-491`）

</details>

**1.5.3-135.** What is the main function of a Primary Reference Clock (PRC) in an O-RAN network?

- A. To provide a reference signal for timing and synchronization of clocks within a network or section of a network.
- B. To provide a high-quality clock source for the entire network.
- C. To regulate the flow of data packets within the network.
- D. To monitor the performance of the network.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-497`）

</details>

**1.5.3-136.** What is a recommended method for optimizing time distribution through the clock chain in an Open Radio Access Network (O-RAN)?

- A. Recommendation ITU-T G.8271.1
- B. Recommendation ITU-T G.8272 clause 6
- C. Recommendation ITU-T G.8275.1 BMCA
- D. Local PRTC/T-GM

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-500`）

</details>

**1.5.3-137.** What is the primary function of the O2 interface in the O-RAN architecture?

- A. Secure communication between the SMO and O-Cloud for managing O-Cloud infrastructure and deployment of O-RAN NFs.
- B. Providing a standardized interface for communication between RAN functions and the core network.
- C. Defining the physical layer interface between the gNB and the user equipment.
- D. Enabling interoperability between different vendor's O-RAN components.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-502`）

</details>

**1.5.3-138.** What is the purpose of the sReSMask2 parameter in an O-RAN system?

- A. To define the IQ usage mask for compression methods that involve selective RE sending with masks in the section header.
- B. To determine the number of resource blocks used for data transmission.
- C. To control the power level of the transmitted signal.
- D. To indicate the presence of a reference signal in a specific PRB.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-511`）

</details>

**1.5.3-139.** What is the nominal value for the CC_ID parameter in an O-RAN configuration?

- A. 000000b
- B. 0000b
- C. 0011b
- D. 0x0000

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-525`）

</details>

**1.5.3-140.** What is the primary purpose of the Cooperative Transport Interface (CTI) in O-RAN?

- A. To transfer control and management information between the O-DU and O-RU.
- B. To facilitate real-time and non-real-time cooperation between the eNB/gNB and the transport network.
- C. To manage the allocation of resources for upstream transmission.
- D. To decode T-plane messages and coordinate scheduling with O-DU.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-528`）

</details>

**1.5.3-141.** In an O-RAN LLS-C1 configuration, Option-B model, what acts as the timing master for downstream O-RU?

- A. O-RU
- B. O-DU
- C. T-GM
- D. ePRTC

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-535`）

</details>

**1.5.3-142.** Which of the following represents a configuration element used to define a low-level transmit link in an O-RAN system?

- A. <external-io xmlns="urn:o-ran:externalio:1.0”><output><name/></output></external-io>
- B. <o-ran-uplane-conf xmlns="urn:o-ran:uplane-conf.1.0”><low-level-tx-links><name/></low-level-tx-links></ o-ran-uplane-conf>
- C. <processing-elements xmlns="urn:o-ran:processing-element.1.0”><ru-elements><name/></ru-elements></processing-elements>
- D. <o-ran-supervision xmlns="urn:o-ran:supervision:1.0"><per-odu-monitoring><odu-id/></per-odu-monitoring></o-ran-supervision>

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-538`）

</details>

**1.5.3-143.** What are the three primary types of synchronization methods available over an Ethernet network for Open Radio Access Networks (O-RAN)?

- A. Frequency, Phase, Time
- B. Frequency, Phase, Latency
- C. Time, Bandwidth, Latency
- D. Phase, Bandwidth, Time

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-547`）

</details>

**1.5.3-144.** In O-RAN's FH M-plane traffic profile 2, what is the frame size used for each burst?

- A. Maximum allowed frame size
- B. Minimum allowed frame size
- C. Average frame size
- D. Interface rate

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-554`）

</details>

**1.5.3-145.** What protocol is used by the O-RU NETCONF Server to upload log files to the NETCONF Client?

- A. HTTP
- B. HTTPS
- C. SFTP/FTPES
- D. SSH

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-558`）

</details>

**1.5.3-146.** In a channel information based beamforming scenario with mixed numerologies, what is the role of the O-DU in determining beam direction for the beam ID based beam?

- A. The O-DU calculates the beamforming weights using algorithms like Zero-forcing or MMSE.
- B. The O-DU signals to the O-RU the beam ID based on manufacturer declaration.
- C. The O-DU emulates the channel estimate and reports it to the O-RU via C plane messages.
- D. The O-DU determines the beam direction based on the UE ID based beam.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-559`）

</details>

**1.5.3-147.** In an O-RAN scenario with overlapping TRX_CONTROL sleep modes, what happens to an array element that remains asleep during a transition?

- A. It inherits the sleep mode of the newly activated elements.
- B. It reverts to its default sleep mode.
- C. It retains its previous sleep mode.
- D. It enters a hybrid sleep mode based on the active elements.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-561`）

</details>

**1.5.3-148.** What is the role of the rApp in the A1 policy creation process described in the context?

- A. A1 policy management service Producer
- B. A1 policy management service Consumer
- C. Near-RT RIC
- D. A1 policy functions

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-562`）

</details>

**1.5.3-149.** Which of the following is NOT a function facilitated by the A1 interface specification in O-RAN?

- A. Enables Near-RT RIC to discover and request enrichment information.
- B. Allows Non-RT RIC to create, modify, and delete policies enforced by the Near-RT RIC.
- C. Facilitates the communication between the SMO and the Radio Access Network.
- D. Enables Non-RT RIC to monitor the enforcement status of A1 policies.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-566`）

</details>

**1.5.3-150.** What is the user name used to access the remote server for file transfer?

- A. oranuser
- B. 1234
- C. 192.168.3.13
- D. local/log

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-567`）

</details>

**1.5.3-151.** What type of radio is this test applicable for?

- A. Category A radios only
- B. Category B radios only
- C. Category A and Category B radios
- D. Category C radios

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-571`）

</details>

**1.5.3-152.** In a coordinated reset scenario, how is the reset request sent from the Host O-DU to the Shared O-RU in Hierarchical Mode?

- A. Through the O1 interface
- B. Via the M-Plane
- C. As an RPC request over the Fronthaul
- D. As a notification over the O1 interface

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-577`）

</details>

**1.5.3-153.** What is a pre-condition for configuring the U-Plane interface between the O-DU and FHGW7-2→8?

- A. The M-Plane connection between the O-DU and FHGW7-2→8 must be established.
- B. The transceiver module must be inserted.
- C. The NETCONF client must be configured.
- D. The U-Plane data flow path must be configured.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-581`）

</details>

**1.5.3-154.** In an 8T8R configuration for an Open Radio Access Network (O-RAN) system, how many bits are used to represent each of the 16 transmit and receive paths?

- A. 8 bits
- B. 16 bits
- C. 32 bits
- D. 64 bits

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-586`）

</details>

**1.5.3-155.** What is the primary role of the Shared O-RU in an Open RAN network?

- A. To provide a centralized management point for all O-DUs in the network.
- B. To act as a physical interface between the O-DU and the antenna.
- C. To handle all data processing and user traffic for the network.
- D. To provide a common radio access point for multiple O-DUs.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-593`）

</details>

**1.5.3-156.** What is the primary focus of the ORAN.WG8.IOT.001 test?

- A. System information broadcast
- B. Cell setup and configuration
- C. Time synchronization
- D. Interoperability between different O-RAN components

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-601`）

</details>

**1.5.3-157.** Which of the following authentication methods are supported for file management in O-RAN?

- A. Certificate authentication for both O-RU and sFTP server
- B. Username and password authentication for both O-RU and sFTP server
- C. Only certificate authentication for O-RU
- D. Only username and password authentication for O-RU

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-604`）

</details>

**1.5.3-158.** Which of the following protocols is NOT mentioned in the provided context as being used for communication between O-RAN components?

- A. F1AP
- B. NGAP
- C. GTP
- D. FH-eCPRI

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-606`）

</details>

**1.5.3-159.** What is the primary method for managing software updates in an Open Radio Access Network (O-RAN)?

- A. NETCONF operations
- B. Software slots
- C. Factory reset
- D. Software activation

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-608`）

</details>

**1.5.3-160.** In the context of Open Radio Access Networks, what does PTS stand for?

- A. Partial Timing Support
- B. Precise Time Synchronization
- C. Packet Timing System
- D. Protocol Timing Service

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-616`）

</details>

**1.5.3-161.** What is the primary purpose of using section type 1 messages in the O-DU emulator for testing NR-FR1-TM1.1 signals?

- A. To define the timing windows for U-Plane message delivery.
- B. To describe the signal and the beam under test, including beam weights.
- C. To convey the beam direction through multiple measurements.
- D. To encapsulate the IQ data in U-Plane messages.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-618`）

</details>

**1.5.3-162.** What is the block size for μ-law compression in O-RAN?

- A. One physical resource block (PRB)
- B. Two physical resource blocks (PRB)
- C. One subcarrier
- D. One symbol

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-620`）

</details>

**1.5.3-163.** What is the purpose of the performance counter "OR.RLC.DlRlcSduVolDiscardFullBuffer.Pmgroup" in O-RAN?

- A. To count the number of exceeding maximum RLC retransmissions.
- B. To measure the volume of discarded DL RLC PDUs due to a full buffer.
- C. To track the number of received NACKs for the final retransmission in the RLC layer.
- D. To monitor the number of successful RLC retransmissions.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-621`）

</details>

**1.5.3-164.** Which latency measurement method is recommended for testing Open Radio Access Networks (O-RAN) as it captures the delay caused solely by the network under test?

- A. Store and Forward Latency
- B. Cut Through Latency
- C. MEF Frame Delay
- D. Forwarding Delay

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-623`）

</details>

**1.5.3-165.** Which of the following is a key aspect of O-RAN Fault Management?

- A. Software Activation Pre-Check
- B. Performance Data Streaming
- C. Fault Notification
- D. Measurement Job Control

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-624`）

</details>

**1.5.3-166.** Which of the following is NOT a supported feature in the Hierarchical-sudo M-Plane IOT Profile 1 for O-RAN?

- A. IPv6 for IP version
- B. VLAN Discovery with VLAN SCAN support
- C. HMAC-SHA2-256 for data integrity hashing
- D. SSH/TLS connection establishment using password-based authentication

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-626`）

</details>

**1.5.3-167.** When an O-RU receives a C-Plane message with a Section Extension 7 and an eAxC Mask, how does the O-RU determine which eAxC_IDs the message applies to?

- A. The O-RU applies the message to all eAxC_IDs configured over the M-Plane, regardless of the mask.
- B. The O-RU applies the message to all eAxC_IDs permitted by the mask, regardless of whether they are configured over the M-Plane.
- C. The O-RU applies the message to eAxC_IDs configured over the M-Plane that match the eAxC_ID in the message header, considering only the bits where the mask is non-zero.
- D. The O-RU applies the message to all eAxC_IDs configured over the M-Plane, but only if the mask is set to all ones.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-631`）

</details>

**1.5.3-168.** Which of the following messages is used to indicate a successful subscription deletion request in the E2 interface?

- A. E2SubscriptionDeleteRequest
- B. E2SubscriptionDeleteSuccess
- C. E2SubscriptionDeleteReject
- D. E2SubscriptionDeleteFailure

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-633`）

</details>

**1.5.3-169.** What is the value type of the "sync-state" notification event in the provided O-RAN specification?

- A. String
- B. Integer
- C. Enumeration
- D. Boolean

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-634`）

</details>

**1.5.3-170.** What is the type of the `RICactions-RemovedForModification-List` element in the `RICsubscriptionModificationResponse-IEs` protocol message?

- A. SEQUENCE (SIZE(0..maxofRICactionID)) OF ProtocolIE-SingleContainer {{RICaction-RemovedForModification-ItemIEs} }
- B. RICaction-RemovedForModification-ItemIEs
- C. RICaction-RemovedForModification-Item
- D. RICrequestID

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-639`）

</details>

**1.5.3-171.** Which of the following requirements is NOT related to alarm notifications within the Fault Supervision Management Services in O-RAN?

- A. REQ-FSDR_NF-FUN-1 for sending alarm notifications
- B. REQ-FSDR_NF-FUN-3 for alarm notification subscription
- C. REQ-FSDR_NF-FUN-6 for reading the alarm list
- D. REQ-FSDR_NF-FUN-8 for reading the alarm list with a filter

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-640`）

</details>

**1.5.3-172.** What is the purpose of the test defined by ORAN.WG8.IOT.045?

- A. Verify cell activation when the O-DU receives synchronization from an external timing source and experiences transitions in sync-state from locked to holdover and freerun.
- B. Verify the successful reception of synchronization from a secondary source when the primary source fails.
- C. Verify the O-CU and O-DU provisioning of HO configuration sent over the O1 interface by the SMO for inter-O-DU handover within an O-CU.
- D. Verify successful Intra frequency measurement based inter-O-DU handover within an O-CU.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-647`）

</details>

**1.5.3-173.** In the context of Open Radio Access Networks (O-RAN), what is the purpose of discarding unused parts of the PN23 sequence?

- A. To improve data transmission efficiency by reducing unnecessary data transmission.
- B. To enhance security by making it more difficult for unauthorized users to access data.
- C. To optimize resource allocation by freeing up bandwidth for other users.
- D. To comply with regulatory standards for data transmission.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-650`）

</details>

**1.5.3-174.** What is the maximum allowed absolute packet time error (Max|TEL|) at an O-RU UNI for a regular RU?

- A. ≤1465ns
- B. ≤1420ns
- C. ≤60ns (FR2)
- D. ≤100ns (FR1)

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-651`）

</details>

**1.5.3-175.** Which of the following MCS indices is represented by the value '1' in the "OR.DLHARQ.DistPdschMcsMuMimoInitialTxAck.MCSInitial.MCSTable" measurement type?

- A. IMCS = 0
- B. IMCS = 1
- C. IMCS = 28
- D. MCS index table 1 for PDSCH/PUSCH without transform precoding

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-655`）

</details>

**1.5.3-176.** Which of the following components is responsible for sending a RIC CONTROL FAILURE message in the provided scenario?

- A. Near-RT RIC
- B. E2 Node
- C. R-RAN
- D. O-RU

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-657`）

</details>

**1.5.3-177.** What happens to an O-RU's "Lost O-DU ID based Supervision" alarm when supervision is successfully recovered after a "restart-call-home" RPC?

- A. The alarm remains active.
- B. The alarm is automatically cancelled.
- C. The alarm changes its severity level.
- D. The alarm is replaced with a new alarm.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-661`）

</details>

**1.5.3-178.** What happens when an O-RU receives a section description with Section Extension 22 and detects an O-RAN protocol error?

- A. The O-RU sends an ACK message to the O-DU.
- B. The O-RU drops the section description and sends an NACK message to the O-DU.
- C. The O-RU modifies the section description and sends an ACK message to the O-DU.
- D. The O-RU ignores the section description and continues processing other data.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-662`）

</details>

**1.5.3-179.** Which of the following scenarios is NOT covered by the provided text regarding O-RU Scenario Classes for UC-Plane testing?

- A. LAA
- B. LTE
- C. NR (5G)
- D. Section Type 3

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-665`）

</details>

**1.5.3-180.** What is the measurement type for the counter that tracks the minimum volume of UL PDCP PDUs transmitted via the F1-U UL GTP-U tunnel?

- A. OR.F1.MinUlPdcpPduVolTxF1U.Pmgroup
- B. OR.F1.DlPdcpPduRxF1UDl.Pmgroup
- C. OR.F1.UlPdcpPduTxF1U.Pmgroup
- D. OR.F1.MinDlPdcpPduVolRxF1U.Pmgroup

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-668`）

</details>

**1.5.3-181.** What happens to the performance counters RX_SEQID_ERR and RX_SEQID_ERR_C when sequence number checking is disabled on an O-RU?

- A. They are updated on both the O-RU and the O-DU.
- B. They are only updated on the O-DU.
- C. They are only updated on the O-RU.
- D. They are not updated on either the O-RU or the O-DU.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-672`）

</details>

**1.5.3-182.** Which of the following parameters is NOT directly related to beamforming in the provided context?

- A. number-of-beams
- B. p-dash
- C. fd-weights-mapping
- D. comp-bit-width

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-676`）

</details>

**1.5.3-183.** In the context of Open Radio Access Networks (O-RAN) with high fronthaul latency, what is a significant challenge that needs to be addressed for the Random Access Channel (RACH) procedure?

- A. Ensuring compatibility with legacy 3GPP standards.
- B. Handling the delay introduced by the fronthaul link.
- C. Optimizing the use of different preamble formats.
- D. Minimizing the impact of contention-based RACH procedures.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-679`）

</details>

**1.5.3-184.** Which of the following is NOT a step involved in configuring an O-RU during initial conditions for testing?

- A. Collecting O-RU capabilities
- B. Configuring the O-RU for operation using M-Plane commands
- C. Synchronizing the O-RU using G.8275.1
- D. Installing a new O-RAN software release

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-684`）

</details>

**1.5.3-185.** What type of O-RU is this test applicable for?

- A. Category A
- B. Category B
- C. Category C
- D. All categories

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-685`）

</details>

**1.5.3-186.** What prefix is used for O-RAN defined measurements that are new and not extensions of existing 3GPP measurements?

- A. OR
- B. O-RAN
- C. 3GPP
- D. MF

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-691`）

</details>

**1.5.3-187.** What is a crucial requirement for the radio unit in an O-RAN system?

- A. Support for the reMask Parameter received from the M-Plane.
- B. Ability to decode the uplink shared channel.
- C. Compatibility with legacy network equipment.
- D. Integration with third-party applications.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-697`）

</details>

**1.5.3-188.** In the context of O-RAN testing, what is the primary objective of the "UC-Plane O-RU Scenario Class DLM Test #2: Uplink – Positive testing"?

- A. To verify the proper synchronization of the O-RU using G.8275.1.
- B. To confirm that the O-RU can successfully receive and decode data transmitted from the CUSM-ECUSM-E.
- C. To assess the O-RU's ability to handle downlink traffic.
- D. To evaluate the performance of the RF signal analyzer.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-698`）

</details>

**1.5.3-189.** What type of compression method is supported for beamforming weights in Open Radio Access Networks?

- A. Block Floating Point
- B. Beam Space Compression
- C. U-Law
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-699`）

</details>

**1.5.3-190.** What is the purpose of a software slot in an O-RU8?

- A. To store multiple software builds for easy switching between them.
- B. To provide independent storage locations for individual software builds.
- C. To allow for the creation and deletion of software builds as needed.
- D. To compress and cipher software builds for enhanced security.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-706`）

</details>

**1.5.3-191.** What action does an O-RU take if it detects that all ODU IDs in its tx-array-carriers and rx-array-carriers lists are expired?

- A. It sends an alarm notification and performs an autonomous reset.
- B. It sends an alarm notification but does not perform an autonomous reset.
- C. It immediately terminates all radio transmission.
- D. It disables the watchdog timers and starts the Call Home procedure.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-711`）

</details>

**1.5.3-192.** What is the primary function of the O2 interface in an O-RAN architecture?

- A. To provide platform resources and workload management between the SMO and the O-Cloud.
- B. To manage leased resources from multiple resource pools.
- C. To manage all resources of DMSes and resources not allocated to any DMS.
- D. To assign resources to resource pools and DMSes using blueprints or pre-configuration templates.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-715`）

</details>

**1.5.3-193.** Which of the following is a key feature of the "OR.F1.UlPdcpPduCellVolTxF1UUl" performance counter in O-RAN?

- A. It measures the volume of UL PDCP PDUs transmitted via the F1-U UL GTP-U tunnel.
- B. It is mandatory for all O-DU implementations.
- C. It is only collected for a single S-NSSAI.
- D. It measures the volume of DL PDCP PDUs transmitted via the F1-U UL GTP-U tunnel.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-717`）

</details>

**1.5.3-194.** What is the primary purpose of an ePRTC (enhanced Primary Reference Time Clock) in O-RAN?

- A. To provide a stable and reliable source of time for synchronization in the network.
- B. To provide a backup timing source for the inter-working function (IWF).
- C. To assist in the aggregation of timing data from multiple sources.
- D. To improve the accuracy of GNSS-based timing signals.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-724`）

</details>

**1.5.3-195.** Which of the following protocols is used for frequency and time synchronization in O-RAN?

- A. TCP
- B. UDP
- C. Synchronous Ethernet and IEEE 1588 Precision Time Protocol (PTP)
- D. HTTP

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-727`）

</details>

**1.5.3-196.** Which of the following is NOT a property defined in the o-ran-transceiver YANG module for a transceiver module?

- A. Interface Name
- B. Port Number
- C. Operating System Version
- D. Vendor ID

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-731`）

</details>

**1.5.3-197.** In O-RAN testing, what is the maximum acceptable difference between compressed and uncompressed EVM measurements for a PDSCH signal?

- A. 2 percentage points
- B. 3 percentage points
- C. 4 percentage points
- D. 5 percentage points

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-732`）

</details>

**1.5.3-198.** Which user is associated with the 'carrier' group in the provided configuration?

- A. oranuser1
- B. oranuser2
- C. oranuser3
- D. oranuser4

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-733`）

</details>

**1.5.3-199.** In an O-RAN ring topology with an O-DU connected to HSR and SYNC from backhaul, what is the maximum allowable absolute time error (TEL) for a packet in an enhanced RU?

- A. ≤1100ns
- B. ≤60ns
- C. ≤100ns
- D. ≤190ns

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-734`）

</details>

**1.5.3-200.** What is the purpose of the "OR.RLC.UlRlcPduVolDiscardRlcReest" measurement counter in the context of O-RAN?

- A. To measure the volume of UL RLC PDUs discarded due to RLC re-establishment.
- B. To measure the number of UL RLC PDUs successfully transmitted.
- C. To measure the number of RLC re-establishment attempts.
- D. To measure the time taken for RLC re-establishment.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-739`）

</details>

**1.5.3-201.** Which compression methods are supported for O-RU troubleshooting log files?

- A. DEFLATE, LZ4, LZMA2, zlib
- B. DEFLATE, LZ4, LZMA2, ZIP
- C. DEFLATE, LZ4, XZ, ZIP
- D. GZIP, LZ4, XZ, ZIP

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-741`）

</details>

**1.5.3-202.** Which of the following is NOT a factor that can impact the performance of an Open Radio Access Network (O-RAN)?

- A. Interference
- B. Dynamic capacity variations
- C. Band and Carrier Aggregation
- D. Holdover Spec of BC function on the wireless transport node

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-742`）

</details>

**1.5.3-203.** What information does the O-RU convey to the O-DU via the M-plane when the LAA feature is enabled?

- A. The O-RU's support for LAA and its capabilities, such as the number of supported LAA SCarriers and maximum LAA buffer size.
- B. The O-RU's network configuration details, including IP addresses and MAC addresses.
- C. The O-RU's hardware specifications, such as processor speed and memory capacity.
- D. The O-RU's location and geographical coordinates.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-744`）

</details>

**1.5.3-204.** What is the purpose of the "Cause" IE in the RICcontrolFailure message?

- A. To indicate the reason for the RIC control failure.
- B. To provide information about the criticality of the failure.
- C. To identify the specific RIC request that failed.
- D. To indicate the outcome of the RIC control operation.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-745`）

</details>

**1.5.3-205.** In the context of O-RAN, what is the maximum transport delay between the O-RU and FHM#1 for a particular cell with only one O-RU?

- A. T_FH1_max
- B. T_FH2-1_max
- C. T_FH3-1_max
- D. T_Comb

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-746`）

</details>

**1.5.3-206.** What is the prefix used to indicate that a performance measurement is defined by O-RAN?

- A. OP
- B. OR
- C. O-RAN
- D. RAN

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-751`）

</details>

**1.5.3-207.** Which of the following techniques is NOT typically used in an O-RAN accelerator design for fronthaul compression?

- A. LDPC coding
- B. Virtualization
- C. Bump-in-wire
- D. HARQ retransmission

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-752`）

</details>

**1.5.3-208.** What message does the O-DU send to the O-RU to initiate the software activation process?

- A. <rpc><software-activation>
- B. <rpc><reset>
- C. <notification><activation-event>
- D. <rpc-reply>

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-756`）

</details>

**1.5.3-209.** What is the maximum allowed value for the Packet max|TEL| at the O-RU UNI for an Enhanced RU?

- A. ≤1100ns
- B. ≤2200ns
- C. ≤32ppb
- D. ≤1000ns

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-758`）

</details>

**1.5.3-210.** What prefix is used for O-RAN defined performance measurements?

- A. OR
- B. VS
- C. 3GPP
- D. 5G

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-766`）

</details>

**1.5.3-211.** What is the purpose of the E2 NODE CONFIGURATION UPDATE ACKNOWLEDGE message sent to the DUT (E2 Node) after successful validation?

- A. To inform the DUT that the configuration update has been successfully applied.
- B. To request the DUT to initiate a new SCTP connection.
- C. To initiate the removal of the first TNL Association.
- D. To validate the DUT's response to the configuration update.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-771`）

</details>

**1.5.3-212.** What is the primary goal of the "UC-Plane O-RU Scenario Class Extended 3GPP DL – Resource Allocation" test?

- A. To verify the O-RU's ability to accurately transmit data in the downlink.
- B. To ensure the O-RU can correctly interpret C-Plane messages and allocate resources.
- C. To test the O-RU's ability to handle complex resource allocation scenarios.
- D. To measure the O-RU's performance in terms of EVM.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-776`）

</details>

**1.5.3-213.** What is the primary advantage of using harmonized VES events over legacy VES events in O-RAN?

- A. Harmonized VES events are more efficient in terms of data transmission.
- B. Harmonized VES events offer improved security compared to legacy VES events.
- C. Harmonized VES events reduce the number of notification variations for producers and consumers.
- D. Harmonized VES events are easier to implement and configure.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-777`）

</details>

**1.5.3-214.** What is the maximum permissible value for the Relative 1PPS Time Error (TERL) between two O-RU UNI ports in an Enhanced RU operating in FR1?

- A. 60 ns
- B. 100 ns
- C. 190 ns
- D. 1100 ns

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-780`）

</details>

**1.5.3-215.** What is the maximum allowable absolute time error (TEL) for packet synchronization in an Enhanced Open Radio Access Network (O-RAN) unit?

- A. ≤1100 ns
- B. ≤60 ns
- C. ≤100 ns
- D. ≤190 ns

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-781`）

</details>

**1.5.3-216.** Which of the following is NOT a test configuration for the NR TDD IOT Profile 3 - NR-TDD-FR2-CAT-A-ABF?

- A. NR-TDD-FR2-CAT-A-ABF_[100MHz-SSB120kHz&PRACHA3-eAxCID2644-llsC1C2]
- B. NR-TDD-FR2-CAT-A-ABF_[200MHz-SSB120kHz&PRACHA3-eAxCID2644-llsC1C2]
- C. NR-TDD-FR2-CAT-A-ABF_[300MHz-SSB120kHz&PRACHA3-eAxCID2644-llsC1C2]
- D. NR-TDD-FR2-CAT-A-ABF_[100MHz-SSB240kHz&PRACHC2-eAxCID4246-llsC1C2]

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-784`）

</details>

**1.5.3-217.** What is the maximum number of PRB blocks or SymPrbPattern that can be specified using one instance of Section Extension 23 in PRB-BLOCK mode?

- A. The number of non-empty frequency ranges in the Section Extension 23
- B. The value of the O-RU advertised M-Plane parameter 'max-prb-blks-per-sec-ext-23'
- C. The value of the O-RU advertised M-Plane parameter 'max-mcscaleremask-per-prb'
- D. The number of sets of {mcScaleReMask, csf, mcScaleOffset} values per symPrbPattern

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-785`）

</details>

**1.5.3-218.** In the context of LTE precoding schemes, what does the "TxD" layerId indicate?

- A. Transmit Diversity
- B. Spatial Multiplexing
- C. Large Delay CDD
- D. Antenna Port Configuration

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-790`）

</details>

**1.5.3-219.** In the context of Open Radio Access Networks (O-RAN), what is the purpose of the "csf" (constellation shift flag) parameter in modulation compression?

- A. To determine the number of bits used for I and Q values in the U-Plane representation.
- B. To indicate whether to shift the constellation during compression and decompression.
- C. To calculate the scale factor applied to unshifted constellation points during decompression.
- D. To define the format of Section Extension 4, which carries modulation compression parameters.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-791`）

</details>

**1.5.3-220.** How does the 'coupling via frequency and time with priorities optimized' optimization address the issue of duplicated highest priority section descriptions?

- A. By sending the duplicated sections to different O-RUs.
- B. By assigning unique section IDs to the highest priority sections.
- C. By prioritizing the highest priority sections based on their frequency and time.
- D. By removing the duplicated sections from the message.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-792`）

</details>

**1.5.3-221.** What is the maximum permissible Time Wander for an O-DU Class-A in an O-RAN network?

- A. 1465ns
- B. 1420ns
- C. 36ppb
- D. 1PPS

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-795`）

</details>

**1.5.3-222.** What is the minimum guaranteed range for the O-DU and O-RU combination across all three SCS?

- A. 148 µs
- B. 120 µs
- C. 110 µs
- D. 100 µs

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-796`）

</details>

**1.5.3-223.** In an O-RAN network, what component is responsible for detecting supervision failures with an O-DU and ceasing transmission on the associated partitioned carrier?

- A. O-DU
- B. Shared O-RU
- C. Non-RT RIC
- D. Fault Management

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-801`）

</details>

**1.5.3-224.** In the context of Open Radio Access Networks (O-RAN), what is the reference point for uplink C-Plane messages that do not describe PRACH channels?

- A. The reception of the earliest IQ sample in the time domain at the start of the cyclic prefix for the earliest symbol referenced by the message.
- B. The reception of the earliest IQ sample in the time domain at the start of the cyclic prefix for the latest symbol referenced by the message.
- C. The reception of the earliest IQ sample in the time domain at the start of the cyclic prefix for the symbol with the largest symbolId.
- D. The reception of the earliest IQ sample in the time domain at the start of the cyclic prefix for the symbol with the smallest symbolId.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-803`）

</details>

**1.5.3-225.** What is the purpose of the "OR.PDCPB.DlPdcpSduDataVolX2" measurement in O-RAN?

- A. To measure the amount of data transmitted over the X2 interface in the downlink direction.
- B. To measure the amount of data transmitted over the Uu interface in the uplink direction.
- C. To measure the amount of data transmitted over the X2 interface in the uplink direction.
- D. To measure the amount of data transmitted over the Uu interface in the downlink direction.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-807`）

</details>

**1.5.3-226.** What type of radios are specifically targeted for this test?

- A. Category A radios
- B. Category B radios
- C. Category C radios
- D. All types of radios

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-812`）

</details>

**1.5.3-227.** What type of communication protocol is used for establishing a secure connection between the O-DU and the SMO?

- A. SSH
- B. FTP
- C. TLS
- D. HTTP

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-813`）

</details>

**1.5.3-228.** What is the purpose of the Cooperative Transport Interface (CTI) in O-RAN?

- A. To enable communication between O-DUs and O-RUs over a packet-based transport network.
- B. To manage the routing of data packets between O-DUs and O-RUs.
- C. To provide a secure connection between O-DUs and O-RUs.
- D. To manage the power consumption of O-DUs and O-RUs.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-815`）

</details>

**1.5.3-229.** What capability does a PNF Software Management Service Producer require to ensure that software activation requests are valid before proceeding?

- A. The ability to activate valid software packages.
- B. The ability to verify the validity of software activation requests.
- C. The ability to perform data migration during software activation.
- D. The ability to reset the PNF Software Management Service Producer.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-817`）

</details>

**1.5.3-230.** What is the highest priority synchronization method for the O-CU?

- A. GNSS Synchronization
- B. 1588v2 Synchronization
- C. BeiDou Synchronization
- D. Galileo Synchronization

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-822`）

</details>

**1.5.3-231.** What is the primary objective of the "Delay variation" test described in the provided context?

- A. To determine the maximum delay variation at which the TNE can receive frames without any loss.
- B. To assess the impact of different frame sizes on the TNE's delay variation.
- C. To measure the delay variation experienced by different QoS traffic types.
- D. To evaluate the TNE's ability to handle frame fragmentation.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-827`）

</details>

**1.5.3-232.** Which of the following statements accurately describes the role of the PNF Software MnS Consumer in the process of retrieving software inventory information?

- A. The PNF Software MnS Consumer is responsible for storing and managing software inventory information.
- B. The PNF Software MnS Consumer initiates a NETCONF session with the PNF Software MnS Producer to request software inventory data.
- C. The PNF Software MnS Consumer analyzes the retrieved software inventory data and makes decisions about software updates.
- D. The PNF Software MnS Consumer is responsible for distributing software packages to the network elements.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-828`）

</details>

**1.5.3-233.** In the context of testing an O-RAN system, what is the primary responsibility of the CUSM Emulator within the Test Equipment (TER)?

- A. Generating and transmitting the uplink signal to the O-RU.
- B. Receiving the uplink signal from the O-RU, extracting IQ data, and decoding it into bits.
- C. Coordinating the timing of downlink and uplink transmissions.
- D. Building the appropriate C-Plane messages that describe the signal.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-829`）

</details>

**1.5.3-234.** What notification method does an O-RU use to inform the O-DU about the time-frequency resources needed for antenna self-calibration when coordinated-calibration-support is set to true?

- A. antenna-calibration-required notification
- B. antenna-calibration-coordinated notification
- C. antenna-calibration-prepared notification
- D. antenna-calibration-configured notification

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-831`）

</details>

**1.5.3-235.** Which of the following best describes the role of the A1 component within the O-RAN architecture?

- A. A1 is responsible for managing the overall network infrastructure, including resource allocation and traffic routing.
- B. A1 is a centralized control unit that handles the core network functions and interactions with external networks.
- C. A1 is responsible for managing the radio access network (RAN) and providing interfaces for connecting to the core network.
- D. A1 is a distributed intelligence component that enables flexible and dynamic radio resource management.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-834`）

</details>

**1.5.3-236.** How does the O-DU request an O-RU to deactivate specific TRX control configuration when using the M-Plane interface for energy saving?

- A. The O-DU periodically processes known energy saving policies and, when conditions for deactivation are met, sends a request through the M-Plane interface.
- B. The O-DU uses the C-Plane interface to request the O-RU to deactivate the TRX control configuration.
- C. The O-DU uses the M-Plane interface to collect capabilities related to energy saving support from the O-RU.
- D. The O-DU uses the M-Plane interface to request the O-RU to activate the TRX control configuration.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-839`）

</details>

**1.5.3-237.** Which of the following is a mandatory requirement for the pull mode event notification test case in O-RAN?

- A. The O-CU/O-DU must be from the same vendor as the O-Cloud.
- B. The O-CU/O-DU must be able to initiate an event query.
- C. The O-Cloud must support push mode event notification.
- D. The Protocol Analyzer must be able to capture messages between the DUTs.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-840`）

</details>

**1.5.3-238.** Which of the following network layer setup methods has the highest priority when assigning networking parameters to interfaces?

- A. Dynamic configuration by O-RAN management system
- B. Static configuration by user
- C. DHCP
- D. Link-local addressing

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-841`）

</details>

**1.5.3-239.** Which YANG module defines the aggregation of multiple O-RUs into a single logical entity?

- A. o-ran-o1-ctiOdu.yang
- B. o-ran-aggregation-base.yang
- C. o-ran-o1-odu.yang
- D. o-ran-o1-cti.yang

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-842`）

</details>

**1.5.3-240.** What is the primary goal of the TC_FH_U-PLANE_UNEXPECTED_PAYLOAD_SIZE test?

- A. To evaluate the O-DU's ability to handle unexpected payload sizes in user plane packets.
- B. To test the O-DU's performance under heavy traffic loads.
- C. To verify the O-RU's ability to generate user plane packets with unexpected payload sizes.
- D. To assess the security vulnerabilities of the O-DU.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-847`）

</details>

**1.5.3-241.** What is the purpose of the OR.BF.DistUeBeamIndex performance counter in an O-RAN network?

- A. To monitor the distribution of UEs across different beam indices.
- B. To measure the performance of beamforming algorithms.
- C. To analyze the distribution of traffic across different beam indices.
- D. To track the number of UEs connected to each beam.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-848`）

</details>

**1.5.3-242.** Which protocol is used for configuring network devices in Open RAN, enabling automation and remote management?

- A. LDP
- B. MP-BGP
- C. NETCONF
- D. IS-IS

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-850`）

</details>

**1.5.3-243.** What is the primary purpose of the "RIC Service Update" procedure in an Open RAN network?

- A. To configure and manage the RAN functions within the network.
- B. To establish a secure connection between the Near-RT RIC and the E2 Node.
- C. To update the software and firmware of the gNBs within the network.
- D. To monitor and analyze network performance data.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-851`）

</details>

**1.5.3-244.** What synchronization method is used between the O-DU and O-RU in the described O-RAN network?

- A. O-RAN Fronthaul Transport Synchronization profile (LLS-C3)
- B. GPS
- C. NTP
- D. PTP

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-856`）

</details>

**1.5.3-245.** Which of the following is **NOT** a function handled by the O-RU in the O-RAN PRACH processing flow?

- A. CP removal
- B. Frequency shift
- C. ZC sequence generation
- D. FFT

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-858`）

</details>

**1.5.3-246.** What is the primary objective of the "UC-Plane O-RU Scenario Class Beamforming 3GPP UL – Weight-based Dynamic Beamforming" test?

- A. Verify the radio's ability to transmit a 3GPP test frame with weight-based beamforming in the uplink direction.
- B. Evaluate the radio's performance in receiving a 3GPP test frame with weight-based beamforming in the downlink direction.
- C. Determine the radio's capability to handle multiple spatial streams (eAxC) during uplink transmission.
- D. Assess the radio's ability to adjust beam direction based on signal strength and quality.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-863`）

</details>

**1.5.3-247.** Which of the following is NOT a parameter that can be configured by the SMO towards the RAN using the O1 interface?

- A. Horizontal beam width
- B. Maximum transmitted power per beam
- C. Network latency
- D. Beam azimuth

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-865`）

</details>

**1.5.3-248.** What is the primary purpose of the "UC-Plane O-RU Scenario Class Extended 3GPP UL – Resource Allocation" test?

- A. To validate the receiver sensitivity of the O-RU.
- B. To ensure the O-RU correctly processes uplink data according to 3GPP standards.
- C. To test the performance of the O-RU's antenna connector.
- D. To evaluate the compatibility of the O-RU with different types of fronthaul interfaces.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-867`）

</details>

**1.5.3-249.** What type of antenna ports are required for the O-RU in the test environment?

- A. Conducted antenna ports (FR1)
- B. TAB connectors
- C. Both 1 and 2
- D. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-868`）

</details>

**1.5.3-250.** What are the three capabilities that an O-DU can report to the SMO regarding its transmission/reception window determination?

- A. Not-Configured, Configured, Both
- B. Fixed, Dynamic, Adaptive
- C. Manual, Automatic, Hybrid
- D. Open, Closed, Partial

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-869`）

</details>

**1.5.3-251.** What happens if an E2SM information element carried as an OCTET STRING in an E2AP message is received but is not constructed as defined in the document?

- A. The message is accepted and processed as usual.
- B. The message is ignored and discarded.
- C. The message is considered an Abstract Syntax Error and handled accordingly.
- D. The message is flagged as a potential security threat.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-871`）

</details>

**1.5.3-252.** Which of the following compression schemes is NOT mentioned in the provided context for O-RAN?

- A. Block-Floating-Point
- B. Modulation-Compression
- C. Adaptive-Compression
- D. Beam-Space-Compression

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-876`）

</details>

**1.5.3-253.** Which of the following O-RAN test cases verifies the success of cell bring-up with a specific configuration of beams and antenna ports for FR2?

- A. ORAN.WG8.IOT.031: Verify DL and UL scheduling information IE’s during an end-to-end UDP FDX data transmission for FR1 configuration.
- B. ORAN.WG8.IOT.032: Verify cell bring up is successful with 64 beams and 64 antenna ports configuration received from SMO to O-DU for FR2 configuration.
- C. ORAN.WG8.IOT.033: Verify cell bring up is successful with 8 beams and 64 antenna ports configuration received from SMO to O-DU for FR1 configuration.
- D. ORAN.WG8.IOT.034: Verify cell bring up is successful and UE attach when the O-DU is configured with 32 punctured SSB beams for FR2 configuration.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-877`）

</details>

**1.5.3-254.** In an O-RAN network where all O-DUs lose their GNSS connection, what is the failover synchronization path for the O-RU1 and O-RU2?

- A. T-GM A -> HSR-4 -> HSR-2 -> O-DU1 & O-DU2
- B. T-GM A -> HSR-4 -> CSR-1 -> O-RU1 & O-RU2
- C. T-GM A -> HSR-4 -> HSR-3 -> O-DU-3 & O-DUn
- D. T-GM A -> HSR-4 -> CSR-2 -> O-RU3 & O-RUn

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-878`）

</details>

**1.5.3-255.** What is the name of the module that handles delay management in O-RAN?

- A. o-ran-wg5-delay-management
- B. o-ran-int:port-reference
- C. synce-master-enabled-local-port-numbers
- D. window-determine-capability

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-879`）

</details>

**1.5.3-256.** What feature in the o-ran-wg4-features.yang file indicates that an O-RU has U-Plane message processing limits?

- A. UPLANE-MESSAGE-PROCESSING-LIMITS
- B. uplane-message-processing-limits-required
- C. max-section-headers-per-uplane-message
- D. uplane-message-section-header-limit-enabled

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-885`）

</details>

**1.5.3-257.** Which of the following fields is NOT a part of the 'software-slot' data structure within the o-ran-software-management YANG module?

- A. product-code
- B. local-logical-file-path
- C. build-version
- D. vendor-code

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-887`）

</details>

**1.5.3-258.** What type of data is used to represent a MAC address in the provided context?

- A. string
- B. uint32
- C. yang:mac-address
- D. inet:ip-address

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-888`）

</details>

**1.5.3-259.** Which of the following is NOT a parameter that can be used to express available bandwidth in an Open Radio Access Network (O-RAN)?

- A. Real-time IQ sample variable-bit-width
- B. IQ Compression
- C. Number of users connected to the network
- D. Beam count / compression

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-890`）

</details>

**1.5.3-260.** What is the maximum phase transient at the output due to reference switching for an Option-1 EEC clock?

- A. 1000 nanoseconds of phase error
- B. 4.6 ppm
- C. 1000 microseconds of phase error
- D. 1000 milliseconds of phase error

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-891`）

</details>

**1.5.3-261.** What type of transport synchronization profile is used for time synchronization between the O-DU and O-RU?

- A. LLS-C1
- B. LLS-C2
- C. LLS-C3
- D. LLS-C4

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-892`）

</details>

**1.5.3-262.** What is the criticality of the TransactionID information element in the E2RemovalFailure message?

- A. ignore
- B. reject
- C. ignore or reject
- D. optional

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-896`）

</details>

**1.5.3-263.** In the context of O-RAN, what are the two main types of synchronization mechanisms used?

- A. GNSS and Ethernet
- B. IEEE-1588v2 and Wi-Fi
- C. GNSS and IEEE-1588v2
- D. Wi-Fi and Bluetooth

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-898`）

</details>

**1.5.3-264.** What is the primary objective of the described test related to O-RU functionality?

- A. To verify the O-RU's ability to interpret section extension 13 for frequency hopping in the uplink.
- B. To assess the O-RU's receiver sensitivity levels for uplink signals.
- C. To evaluate the O-RU's performance in handling various data rates and modulation schemes.
- D. To test the O-RU's ability to correctly decode uplink signals with specific power levels.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-901`）

</details>

**1.5.3-265.** In the context of O-RAN, what is the primary purpose of the Shared O-RU notifying other connected O-DUs as SROs during a Shared O-RU reset?

- A. To inform the O-DUs about the reset process and ensure coordinated actions.
- B. To request assistance from the O-DUs in performing the reset.
- C. To transfer control of the Shared O-RU to the other O-DUs.
- D. To request data synchronization from the other O-DUs.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-904`）

</details>

**1.5.3-266.** What happens to the O-RU's PTP lock-state using the M-Plane if the received clockClass does not match the configured list of accepted values?

- A. LOCKED and PARENT
- B. NOK
- C. HOLDOVER or FREERUN
- D. LOCKED and NOK

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-905`）

</details>

**1.5.3-267.** Which of the following interfaces connects the O-RU and O-DU in a split architecture of an O-RAN?

- A. NG interface
- B. F1 interface
- C. Fronthaul interface
- D. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-909`）

</details>

**1.5.3-268.** What protocol is used to establish a session between the PNF Software MnS Consumer and the PNF Software MnS Producer in the given scenario?

- A. HTTP
- B. NETCONF
- C. RESTCONF
- D. SNMP

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-910`）

</details>

**1.5.3-269.** Which O-RAN interface is used to configure the default behavior of RAN for slices, including the ratio of physical resources reserved for a slice?

- A. O2
- B. O1
- C. O3
- D. O4

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-915`）

</details>

**1.5.3-270.** What is the role of a CTI client in an O-RAN network?

- A. A process in the Transport Node that exchanges CTI messages with one or multiple CTI servers.
- B. A process in the O-DU that exchanges CTI messages to one or multiple CTI servers, for example, to request a given transport capacity.
- C. A process that generates CTI messages.
- D. A process that receives CTI messages.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-922`）

</details>

**1.5.3-271.** Which of the following is NOT a valid bin for the OR.PDCPA.DistUeUlRxData.binX measurement type in O-RAN?

- A. bin 1: 0 Byte < x < 1 kByte
- B. bin 13: 2 MByte ≤ x < 5 MByte
- C. bin 6: 20 kByte ≤ x < 50 kByte
- D. bin 9: 200 kByte ≤ x < 500 kByte

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-925`）

</details>

**1.5.3-272.** What is the expected accuracy of time synchronization in an O-RAN element using NTP version 4, as specified in RFC5905?

- A. Within 1 millisecond
- B. Within 1 second
- C. Within 1 minute
- D. Within 1 hour

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-928`）

</details>

**1.5.3-273.** Which of the following describes the purpose of the "OR.ORU.RX.Corrupt" performance counter in an Open Radio Access Network (O-RAN)?

- A. It counts the number of control plane messages with sequence number errors.
- B. It counts the number of inbound messages with correct sequence numbers that are dropped due to protocol errors.
- C. It counts the number of uplink frames with corrupt contents.
- D. It counts the number of messages received from the O-RU that are not in the correct format.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-932`）

</details>

**1.5.3-274.** Which of the following is a pre-requisite for the ORAN.WG8.IOT.035 test case?

- A. The O-RU is configured to use a specific number of CB-preambles per SSB.
- B. The O-DU and O-RU are connected via a fronthaul interface.
- C. The O-CU is configured to use a specific number of CB-preambles per SSB.
- D. The O-RU is managed by the O-CU using a non-hierarchical approach.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-933`）

</details>

**1.5.3-275.** Which of the following protocols is used for communication between the O-DU and O-RU in an O-RAN network?

- A. F1AP
- B. NGAP
- C. FH-eCPRI
- D. HTTP2

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-935`）

</details>

**1.5.3-276.** In the O-RAN hierarchical model, what is the O-DU responsible for managing?

- A. Only O-DU alarms
- B. Only O-RU alarms
- C. Both O-DU and O-RU alarms
- D. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-936`）

</details>

**1.5.3-277.** What is the name associated with the rx-array carrier object unit?

- A. PA1
- B. RX-ARRAY-CARRIER1
- C. PROC_ELEMENT1
- D. ALL-UL-SYMBOLS

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-937`）

</details>

**1.5.3-278.** What is the maximum allowed value for the Relative 1PPS Time Error (TERL) between the Master ports of CSR1 and CSR2 at the O-RU UNI for a Regular RU operating in FR1?

- A. ≤60𝑛𝑠
- B. ≤100𝑛𝑠
- C. ≤190𝑛𝑠
- D. ≤1100𝑛𝑠

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-940`）

</details>

**1.5.3-279.** Which protocol is used to establish the initial connection between the Performance Assurance MnS Consumer and the Performance Assurance MnS Producer in the provided scenario?

- A. WebSocket
- B. HTTP/TLS
- C. UDP
- D. TCP

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-941`）

</details>

**1.5.3-280.** What is the initial beamforming configuration used in the test signal injection process for O-RAN testing?

- A. All beamweights set to a specific value, resulting in a focused beam.
- B. All beamweights set to zero, resulting in no beamforming.
- C. All beamweights set to random values, simulating a random beam pattern.
- D. All beamweights set to be equal, resulting in a uniform beam pattern.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-942`）

</details>

**1.5.3-281.** Which protocol is specified for configuration management in O-RAN?

- A. SNMP
- B. RESTCONF
- C. NETCONF
- D. gRPC

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-944`）

</details>

**1.5.3-282.** What is the maximum value allowed for the RIC-InsertIndication-ID?

- A. 255
- B. 65535
- C. 150
- D. 1024

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-947`）

</details>

**1.5.3-283.** What is the initial step in configuring the O-RU for testing?

- A. Connecting the signal analyzer to the O-RU antenna port.
- B. Collecting the O-RU capabilities.
- C. Synchronizing the O-RU using G.8275.1.
- D. Playing U-Plane messages to the O-RU.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-950`）

</details>

**1.5.3-284.** In the context of O-RAN beamforming conformance testing, which of the following beam configurations is NOT evaluated for an O-RU that supports attribute-based dynamic beamforming?

- A. An attribute-based beam with maximum supported azimuth and minimum supported elevation angles, with the widest beamwidth and lowest sidelobe suppression.
- B. An attribute-based beam with minimum supported azimuth and maximum supported elevation angles, with the narrowest beamwidth and highest sidelobe suppression.
- C. An attribute-based beam with maximum supported azimuth and maximum supported elevation angles, with the narrowest beamwidth and highest sidelobe suppression.
- D. An attribute-based beam with minimum supported azimuth and minimum supported elevation angles, with the narrowest beamwidth and highest sidelobe suppression.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-955`）

</details>

**1.5.3-285.** What is the maximum allowed value for the T12_max parameter in Open RAN?

- A. 125 us
- B. 160 us
- C. 232 us
- D. 392 us

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-957`）

</details>

**1.5.3-286.** What attribute within the CTIConfig structure is read-only?

- A. ctiSessionId
- B. ctiReportRateCategory
- C. ctiNominalReportMsgInterval
- D. ctiReportMessagingUseOfType1Ext

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-959`）

</details>

**1.5.3-287.** Which of the following O-RAN performance counters provides the distribution of UE's fraction of RLC SDU packets dropped on the downlink due to high traffic load, traffic management, etc.?

- A. OR.DRB.RlcPacketDropRateDlDist.Bin
- B. OR.DRB.UEThpDlDist.Bin.SNSSAI.PmGroup
- C. OR.DRB.UEThpDlDist.Bin
- D. OR.DRB.RlcPacketDropRateDlDist

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-960`）

</details>

**1.5.3-288.** What is the purpose of the RIC CONTROL ACKNOWLEDGE message sent to the Near-RT RIC in the described test scenario?

- A. To inform the Near-RT RIC that the validation process in step 3 was successful.
- B. To request the Near-RT RIC to send a specific configuration to the gNB.
- C. To trigger the Near-RT RIC to initiate a new measurement campaign.
- D. To acknowledge receipt of a previous message from the Near-RT RIC.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-961`）

</details>

**1.5.3-289.** Which of the following O-RAN synchronization configurations involves distributing network timing from the O-DU to the O-RU via a direct connection between their respective sites?

- A. Configuration LLS-C1
- B. Configuration LLS-C2
- C. Configuration LLS-C3
- D. Configuration LLS-C4

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-962`）

</details>

**1.5.3-290.** What is the primary objective of the WDM.OAM.03 test?

- A. To verify the functionality of the OAM service layer in active WDM equipment.
- B. To test the communication between the optical modules and the active WDM equipment.
- C. To measure the bit error rate of the service channel.
- D. To configure the OAM connections between the testing management systems and the TRXs.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-965`）

</details>

**1.5.3-291.** In a test involving the SymInc bit, which two symbols within a slot are specifically used to verify the radio's ability to increment the current symbol ID?

- A. Symbol #1 and Symbol #2
- B. Symbol #3 and Symbol #4
- C. Symbol #5 and Symbol #6
- D. Symbol #7 and Symbol #8

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-966`）

</details>

**1.5.3-292.** What is the purpose of a timing domain in an O-RAN fronthaul network?

- A. To define the set of O-DU and O-RU ports to which a single set of O-DU delay parameters apply.
- B. To ensure that all O-DUs in the network operate at the same clock frequency.
- C. To provide a mechanism for synchronizing the timing of U-plane and C-plane traffic.
- D. To enable the use of different fronthaul transport technologies.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-969`）

</details>

**1.5.3-293.** Which of the following O-RAN planes is responsible for managing the deactivation of antenna carriers in an O-RU?

- A. C-Plane
- B. M-Plane
- C. U-Plane
- D. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-971`）

</details>

**1.5.3-294.** What parameter defines the time difference between the start of the sub-frame and the beginning of the first Cyclic Prefix in a PRACH pattern?

- A. frame-number
- B. sub-frame-id
- C. time-offset
- D. re-offset

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-974`）

</details>

**1.5.3-295.** In the context of Open Radio Access Networks (O-RAN), what is the maximum number of symbols that the "numSymbol" parameter can represent in a section description without Section Extension 6, 12, or 19?

- A. 1
- B. 14
- C. 16
- D. 30

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-975`）

</details>

**1.5.3-296.** What HTTP method is used to delete an EI job in an O-RAN system?

- A. GET
- B. POST
- C. DELETE
- D. PUT

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-978`）

</details>

**1.5.3-297.** What is the purpose of the "ecpriMessage" parameter within an eCPRI common header?

- A. To indicate the size of the payload in bytes.
- B. To identify the type of service being conveyed by the message.
- C. To specify the maximum supported payload size.
- D. To define the length of the eCPRI message.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-980`）

</details>

**1.5.3-298.** What is the role of an O-DU in relation to synchronization in an O-RAN network?

- A. O-DU acts as a synchronization slave towards the fronthaul interface.
- B. O-DU acts as a synchronization master towards the fronthaul interface.
- C. O-DU does not play a role in synchronization.
- D. O-DU acts as a synchronization slave towards the upstream network.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-981`）

</details>

**1.5.3-299.** What is the purpose of using the DHCPv4 Option 60 Vendor Class Identifier in O-RAN?

- A. To identify the O-RU8 device during the DHCP process.
- B. To assign a specific IP address to the O-RU8.
- C. To configure the M-plane interface of the O-RU8.
- D. To manage the VLAN configuration of the O-RU8.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-983`）

</details>

**1.5.3-300.** What is the primary purpose of the Logging Level concept in O-RAN?

- A. To manage the amount of data stored in Fault and Debug Logs.
- B. To determine the severity of faults detected by O-Cloud resources.
- C. To control the frequency of alarm notifications sent by the IMS.
- D. To filter the types of alarms that are raised by the Alarm Manager.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-985`）

</details>

**1.5.3-301.** When evaluating weight-based dynamic beamforming conformance for an O-RU in a UC-Plane scenario, which beam angles should be tested?

- A. 0 degrees azimuth and elevation, maximum supported azimuth and elevation, maximum supported azimuth and minimum supported elevation, minimum supported azimuth and maximum supported elevation, minimum supported azimuth and minimum supported elevation.
- B. Only the maximum supported azimuth and elevation angles.
- C. Only the minimum supported azimuth and elevation angles.
- D. Only the 0 degrees azimuth and elevation angles.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-986`）

</details>

**1.5.3-302.** What is the purpose of the document mentioned in the provided context?

- A. To specify test cases for the A1 interface.
- B. To provide a comprehensive overview of O-RAN technology.
- C. To define the terminology used in O-RAN specifications.
- D. To establish guidelines for drafting O-RAN specifications.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-988`）

</details>

頁次：[1](1-5-gsma-1.md)　[2](1-5-gsma-2.md)　**3**　[4](1-5-gsma-4.md)　[5](1-5-gsma-5.md)
