# 1.5 開放與虛擬化　GSMA 練習題（909 題）（第 4／5 頁）

所屬：[1.5 開放與虛擬化](1-5.md)

只收 GSMA 訓練題；不含驗證集與測試集，並已去除和驗證／測試題相同或相似、重複、標註衝突的題目。題目依小節歸類（抽查正確率約 95%）。

頁次：[1](1-5-gsma-1.md)　[2](1-5-gsma-2.md)　[3](1-5-gsma-3.md)　**4**　[5](1-5-gsma-5.md)

## 1.5.3 O-RAN 介面：A1、E2、O1、O2、開放前傳（388 題）（續）

**1.5.3-303.** Which of the following elements in the CTI IM has a one-to-one relationship with a CTIFlow?

- A. CTISessionGroup
- B. CTISession
- C. CTIFlowsInUse
- D. CTIConnProfile

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1007`）

</details>

**1.5.3-304.** What is the default protocol stack for A1-related APIs in the current version of the O-RAN specification?

- A. HTTP
- B. FFS
- C. TCP
- D. UDP

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1008`）

</details>

**1.5.3-305.** What type of devices are used for conformance testing of Non-Real Time RIC and Near-Real Time RIC over the A1 interface?

- A. Real devices only
- B. Simulated devices only
- C. Both real and simulated devices
- D. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1016`）

</details>

**1.5.3-306.** Which of the following is NOT a data point that can be retrieved using the "o-ran-mplane-int" module?

- A. Temperature of the device
- B. VLAN ID range for searchable access VLANs
- C. IP address of the management plane interface
- D. Number of active users connected to the device

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1021`）

</details>

**1.5.3-307.** When using VLANs for C/U plane transport in an O-RU, what is the relationship between the VLANs assigned to the C-Plane and U-Plane for a given eAxC_ID?

- A. They must be different.
- B. They must be the same.
- C. They can be either the same or different.
- D. They are always assigned automatically by the O-RU.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1025`）

</details>

**1.5.3-308.** Which of the following protocols is NOT mentioned as being used for secure communication over the Y1 interface in the context provided?

- A. TLS
- B. SSH
- C. HTTPS
- D. TCP

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1027`）

</details>

**1.5.3-309.** Which of the following is an optional performance counter for O-DU that provides the distribution of PSCell UEs based on the number of activated SCells in the uplink?

- A. OR.CellUA.UeCellPscellActiveScellUl
- B. OR.CellUA.DistPscellUeXactiveScellUl
- C. OR.CellUA.DistPscellUeXactiveScellUl.NumScell
- D. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1030`）

</details>

**1.5.3-310.** In an O-RAN C-Plane message, what is the purpose of the 'symInc' field within a data section description?

- A. To indicate the number of symbols allocated to the section.
- B. To specify the starting symbol index for the section.
- C. To define the symbol increment between consecutive sections.
- D. To determine the total number of symbols in the message.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1032`）

</details>

**1.5.3-311.** What is the primary goal of the "Functional test of O-DU Synchronized from Embedded or Local non-PTP PRTC (LLS-C1/C2/C3/C4)" test described in the context?

- A. To evaluate the performance of the O-DU's fronthaul ports when configured as an ITU-T G.8275.1 synchronization master.
- B. To confirm that the O-DU can correctly synchronize to a non-PTP local time source and report its synchronization status accurately.
- C. To test the O-DU's ability to handle multiple time sources.
- D. To assess the O-DU's synchronization capabilities in the presence of degraded synchronization conditions.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1035`）

</details>

**1.5.3-312.** Which of the following is NOT a requirement for the successful execution of the data transfer test case described in the provided text?

- A. Successful completion of the EN-DC X2 setup procedure between the eNB and en-gNB.
- B. Successful completion of the F1 setup procedure between the en-gNB-CU and en-gNB-DU.
- C. The Test UE or UE emulator must be within the coverage area of the MN (eNB) cell and SN (en-gNB) cell.
- D. The Test UE or UE emulator must be connected to the Application Test Server via a wired connection.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1036`）

</details>

**1.5.3-313.** What does the O2 interface in O-RAN architecture facilitate?

- A. Secure communication between the SMO and O-Cloud.
- B. Management of O-Cloud infrastructures.
- C. Deployment life cycle management of O-RAN cloudified NFs.
- D. All of the above.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1038`）

</details>

**1.5.3-314.** What is the purpose of the Test Simulator in the context of Open Radio Access Networks (O-RAN)?

- A. To simulate real-world network conditions.
- B. To validate the received E2 messages against specified requirements.
- C. To generate synthetic traffic for testing purposes.
- D. To monitor and analyze network performance.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1043`）

</details>

**1.5.3-315.** What is the maximum allowed absolute packet time error (max|TEL|) for an Enhanced RU measured at the O-RU UNI using a Clock Tester?

- A. 1100ns
- B. 60ns
- C. 190ns
- D. 100ns

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1047`）

</details>

**1.5.3-316.** Which of the following is NOT a functional requirement for the A1 interface in an O-RAN network?

- A. Support communication of policies from Non-RT RIC to Near-RT RIC.
- B. Support AI/ML model deployment and update from Non-RT RIC to Near-RT RIC.
- C. Support communication of enrichment information from Non-RT RIC to Near-RT RIC.
- D. Support registration of services.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1049`）

</details>

**1.5.3-317.** Which of the following elements is NOT included in the 'RICsubscription-withCause-Item' sequence?

- A. ricRequestID
- B. ranFunctionID
- C. cause
- D. ProtocolIE-Container

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1050`）

</details>

**1.5.3-318.** Which of the following is NOT a test objective of the "Timing Resiliency in Ring Topology-O-DU connected to HSR and SYNC from Backhaul-Normal State" test?

- A. Verify the Clock Lock states on BRs, HSRs and CSRs.
- B. Verify the steady-state clock advertisements on BRs, HSRs and CSRs.
- C. Verify the Maximum Absolute 1PPS Time Error (𝑀𝑎𝑥|𝑇𝐸𝐿|) at O-RU UNI.
- D. Verify the Maximum Relative Packet Time Error (𝑀𝑎𝑥|𝑇𝐸𝑅𝐿|) between two O-RU UNI ports.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1052`）

</details>

**1.5.3-319.** What is the expected outcome of the test described in the context?

- A. The test is considered a pass if the payload binary sequences received from the DUT match the uplink test frame sent.
- B. The test is considered a pass if the C-Plane messages are successfully sent to the O-DU emulator.
- C. The test is considered a pass if the RF signal source plays the test waveforms on 10ms frame boundaries.
- D. The test is considered a pass if the DUT captures the fronthaul messages sent by the Test Equipment O-RU (TER).

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1055`）

</details>

**1.5.3-320.** How does an O-RU obtain the IP address of a NETCONF client if the client's identity is provided as an FQDN?

- A. The O-RU uses the DNS server address provided by the DHCP server to resolve the FQDN.
- B. The O-RU uses the NETCONF client's transport layer address provided by the DHCP server.
- C. The O-RU uses the event-collector's transport layer address provided by the DHCP server.
- D. The O-RU uses the SLAAC protocol to automatically configure its own IP address and then resolves the FQDN.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1056`）

</details>

**1.5.3-321.** In an O-RAN ring topology, what is the maximum allowed absolute time error (TEL) for a packet in a Regular Radio Unit (RU)?

- A. ≤1100ns
- B. ≤60ns
- C. ≤100ns
- D. ≤190ns

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1057`）

</details>

**1.5.3-322.** How does the O-RU determine which configuration entries to activate when receiving Section Type 3 C-plane messages?

- A. The O-RU uses a pre-defined mapping based on the message content.
- B. The O-DU provides a combination entry containing a set of configuration options, and the O-RU selects the appropriate entry based on the message context.
- C. The O-RU relies on its own internal logic to determine the best configuration.
- D. The O-RU uses a random selection process to activate configuration entries.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1058`）

</details>

**1.5.3-323.** How does O-RAN define new subcounters for an existing 3GPP measurement that already has subcounters defined?

- A. A new O-RAN measurement needs to be defined.
- B. Existing filters for the 3GPP measurement can be redefined in the new O-RAN measurement's Measurement Type.
- C. The O-RAN measurement must follow the guidance of 3GPP TS 32.404 [10] clause 3.3.
- D. The new subcounters are defined in the O-RAN specification document.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1062`）

</details>

**1.5.3-324.** What is the first step involved in configuring an O-RU for testing in an Open RAN environment?

- A. Connecting the signal source to the O-RU antenna ports.
- B. Calibrating the RF connections and cables.
- C. Synchronizing the O-RU using G.8275.1.
- D. Letting the DUT and TER warm to the normal operating temperature.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1064`）

</details>

**1.5.3-325.** What is the purpose of the OR.CellUA.MinPscellUeDl counter in an O-DU?

- A. To track the number of PSCell UEs for DL every 100ms.
- B. To provide the minimum number of PSCell UEs for DL every 100ms.
- C. To monitor the number of Activation/Deactivation MAC CEs transmitted for SCell activation.
- D. To measure the number of active SCells in the network.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1065`）

</details>

**1.5.3-326.** Which type of user account is required to successfully retrieve a file list using the o-ran-file-management YANG model in an O-RAN network?

- A. Default SUDO account
- B. Hybrid-ODU privileged account
- C. Standard user account
- D. Root account

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1068`）

</details>

**1.5.3-327.** When using SE 22 with ST 0, 1, 3, 5, 6, how is ACK/NACK feedback requested from the O-RU?

- A. Per section header
- B. Per Section Type 4 command
- C. Per slot
- D. Per endpoint

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1070`）

</details>

**1.5.3-328.** What is the primary purpose of the "Manufacturers’ defined list of beam indices and their associated beam directions with antenna array characteristics" in the context of O-RAN testing?

- A. To assess the performance of the radio's power amplifier.
- B. To verify the accuracy of the radio's beamforming capabilities.
- C. To measure the signal strength of the radio's transmissions.
- D. To determine the optimal frequency band for the radio's operation.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1079`）

</details>

**1.5.3-329.** What is the primary objective of the SYNC.TE.01 test in the context of O-RAN?

- A. To evaluate the performance of the O-RU's radio interface.
- B. To verify the accuracy of time synchronization at the O-RU UNI.
- C. To test the functionality of the O-DU's control plane.
- D. To assess the network's capacity and throughput.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1080`）

</details>

**1.5.3-330.** What data structure is supported by the HTTP PUT request body when interacting with an EI job resource?

- A. EiJobObject
- B. eiTypeId
- C. URI query parameters
- D. Response codes

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1083`）

</details>

**1.5.3-331.** What is the primary communication protocol used between the A1-EI Consumer and A1-EI Producer in the O-RAN A1-EI service?

- A. TCP
- B. UDP
- C. HTTP
- D. HTTPS

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1084`）

</details>

**1.5.3-332.** What is the main difference between PRTC-A and PRTC-B?

- A. PRTC-A is more accurate than PRTC-B.
- B. PRTC-B is more accurate than PRTC-A.
- C. PRTC-A is more suitable for outdoor deployments.
- D. PRTC-B is more suitable for outdoor deployments.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1085`）

</details>

**1.5.3-333.** In the context of O-RAN, what parameter indicates the offset to the start of a specific PRB range?

- A. freqOffset
- B. offStartPrb
- C. numPrb
- D. symbolMask

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1088`）

</details>

**1.5.3-334.** What is the maximum absolute packet time error allowed at the O-RU UNI for an Enhanced RU?

- A. 1465 ns
- B. 1000 ns
- C. 500 ns
- D. 2000 ns

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1089`）

</details>

**1.5.3-335.** Which message is sent from the Near-RT RIC to the E2 Node to initiate the E2 Removal procedure?

- A. E2 SETUP REQUEST
- B. E2 REMOVAL REQUEST
- C. E2 RESET REQUEST
- D. E2 INFORMATION REQUEST

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1093`）

</details>

**1.5.3-336.** Which Information Element (IE) is used to identify the type of RIC Service Action to be executed?

- A. Global RIC ID
- B. RIC Action ID
- C. RIC Action Type
- D. RIC Event Trigger Definition

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1099`）

</details>

**1.5.3-337.** What is the maximum allowed absolute packet time error for an Enhanced RU at the O-RU UNI, as measured by a Clock Tester?

- A. 1100ns
- B. 60ns
- C. 190ns
- D. 100ns

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1101`）

</details>

**1.5.3-338.** What is the purpose of the "Create single policy (positive case)" test scenario in the context of O-RAN A1-P Consumer testing?

- A. To test the deletion of a policy.
- B. To test the creation of a single policy as specified by A1AP clause 5.2.4.3.
- C. To test the modification of an existing policy.
- D. To test the retrieval of a policy.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1102`）

</details>

**1.5.3-339.** When an optional RIC Subscription End Time is present and the indicated time has expired, what action can the E2 Node take?

- A. Send an RIC SUBSCRIPTION DELETE REQUIRED message to the Near-RT RIC.
- B. Initiate an RIC Subscription Delete procedure.
- C. Ignore the expired time and continue operating as normal.
- D. Re-request the RIC Subscription with a new End Time.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1107`）

</details>

**1.5.3-340.** What is the primary objective of the "Measurement of Frequency Error, Maximum Absolute Time Error at O-RU UNI" test?

- A. Verify the timing accuracy of the O-RU UNI by measuring the maximum absolute packet time error and 1PPS time error.
- B. Evaluate the performance of the O-DU by measuring the maximum absolute time error at the O-RU UNI.
- C. Assess the reliability of the O-RAN network by simulating O-DU failure scenarios.
- D. Analyze the impact of different G.8275.1 timing profiles on the O-RU UNI.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1108`）

</details>

**1.5.3-341.** How are O-RU performance counters measured and managed in an Open RAN architecture?

- A. O-RU performance counters are measured and managed by the O-DU using 3GPP SA5 data model.
- B. The SMO controls the activation and deactivation of O-RU performance counters using an aggregation model.
- C. O-RU performance counters are measured by the O-RU and sent to the O-DU for aggregation and reporting.
- D. The O-RU is responsible for managing its own performance counters and reporting them to the SMO.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1113`）

</details>

**1.5.3-342.** What is a key aspect of Open Radio Access Networks (O-RAN) that is addressed in the provided context?

- A. Synchronization and Timing
- B. Data Rate and Throughput
- C. Security and Authentication
- D. Power Consumption

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1114`）

</details>

**1.5.3-343.** What is recommended to keep the time error and frequency error within limits at the input of the O-RU in LLS-C3/C2 topologies?

- A. Using PTP Hybrid (PTP + SyncE/eSyncE) network
- B. Having fewer hops on the path from T-GM towards O-RU
- C. Using mixed O-RAN topology (LLS-C1/LLS-C4)
- D. Ensuring O-RUs have good holdover characteristics

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1119`）

</details>

**1.5.3-344.** Which component is responsible for initiating a RIC Subscription Modification Request in the provided scenario?

- A. Near-RT RIC
- B. E2 Node
- C. RAN
- D. RIC

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1120`）

</details>

**1.5.3-345.** Which ITU-T standard is used for synchronizing O-RUs in the O-DU performance test described in the context?

- A. G.8271
- B. G.8275.1
- C. G.8261
- D. G.8275.2

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1122`）

</details>

**1.5.3-346.** Which of the following folders is used for storing configuration files in an O-DU?

- A. O-RAN/O-DU/PM/
- B. O-RAN/O-DU/CM/
- C. O-RAN/O-DU/NL/
- D. O-RAN/O-DU/OT/

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1123`）

</details>

**1.5.3-347.** What is the maximum configurable value for the n-ta-offset parameter in an O-RAN system?

- A. 33.3 µs
- B. 65535
- C. 1.96608 GHz
- D. 38.211

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1130`）

</details>

**1.5.3-348.** Which of the following protocols is used for communication between the E2 node and the Near-RT RIC?

- A. S1AP
- B. X2AP
- C. E2GAP
- D. NGAP

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1133`）

</details>

**1.5.3-349.** What is the purpose of verifying the Maximum Relative Packet Time Error (𝑀𝑎𝑥|𝑇𝐸𝑅𝐿|) between the O-RU UNI ports?

- A. To ensure accurate synchronization between the O-RU and the core network.
- B. To determine the latency of the O-RU UNI ports.
- C. To measure the jitter of the O-RU UNI ports.
- D. To evaluate the signal strength of the O-RU UNI ports.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1135`）

</details>

**1.5.3-350.** In a multi-operator O-RAN deployment, which entity is responsible for controlling the Active Layer Device (ALD)?

- A. The participating operator's O-DU
- B. The shared O-RU
- C. The owner operator's O-DU
- D. Both the owner and participating operator's O-DUs

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1138`）

</details>

**1.5.3-351.** Which of the following compression formats is specifically tested in the "UC-Plane O-RU Scenario Class Compression Non-Static Format (NS) Block Floating Point + Selective RE Format" scenario?

- A. Modulation Compression + Selective RE
- B. Block Floating-Point + Selective RE
- C. Static Format
- D. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1139`）

</details>

**1.5.3-352.** Which of the following is NOT a required testing tool for evaluating Carrier Aggregation in an Open RAN environment?

- A. Test UE or UE emulator capable of Carrier Aggregation
- B. Core or Core emulator with 5GC capabilities
- C. Protocol Analyzer
- D. Network Simulator

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1141`）

</details>

**1.5.3-353.** What is the outcome of the E2 SUBSCRIPTION DELETE request in the given scenario?

- A. The request is successfully processed.
- B. The request is rejected.
- C. The request is ignored.
- D. The request is pending.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1143`）

</details>

**1.5.3-354.** What is the typical method for the SMO to receive alarm information from nodes terminating the O1 interface?

- A. Through the O1 interface
- B. Through the M-Plane
- C. Through the Near-RT RIC
- D. Through the Slice Manager

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1145`）

</details>

**1.5.3-355.** What data structure is used to carry the result of an EI job when using the HTTP POST method to deliver EI job results?

- A. EiJobStatusObject
- B. EiJobResultObject
- C. EiJobCreationObject
- D. EiJobDeliveryObject

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1146`）

</details>

**1.5.3-356.** What is the primary purpose of O-RAN.WG4.CTI-TCP.0-R003-v04.00 document?

- A. To define the scope and terminology related to O-RAN.
- B. To provide a detailed guide on implementing O-RAN solutions.
- C. To present a case study of a successful O-RAN deployment.
- D. To analyze the economic benefits of adopting O-RAN technology.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1147`）

</details>

**1.5.3-357.** What is the purpose of the E2 Reset procedure in an O-RAN network?

- A. To establish a new connection between the Near-RT RIC and the E2 Node.
- B. To update the configuration of the E2 Node and RIC Services.
- C. To reset the E2 interface and terminate any ongoing RIC Services.
- D. To send a notification to the Near-RT RIC about a failure in the E2 Node.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1148`）

</details>

**1.5.3-358.** What is the purpose of the 'ctiClientMacAddr' leaf in the provided configuration?

- A. To define the source MAC address of the CTI client.
- B. To define the destination MAC address for CTI messages sent to the server.
- C. To specify the IP address of the CTI client.
- D. To enable or disable the CTI client.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1150`）

</details>

**1.5.3-359.** What are the two formats that a PNF Registration notification can be in?

- A. SDO O1 format and VES O1 format
- B. pnfRegistration and o1NotifyPNFRegistration
- C. o1NotifyPNFRegistration and pnfRegistration
- D. SDO O1 format and pnfRegistration

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1153`）

</details>

**1.5.3-360.** In an O-RAN deployment, what happens if the O-RU sets the "st6-4byte-alignment-required" flag to "false"?

- A. The O-DU must send Section Type 6 messages with 4-byte alignment.
- B. The O-DU must send Section Type 6 messages without 4-byte alignment.
- C. The O-DU must send Section Type 6 messages with 1-byte alignment.
- D. The O-DU must send Section Type 6 messages with 2-byte alignment.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1156`）

</details>

**1.5.3-361.** Which of the following is a measurement object class for the OR.BF.DistUeBeamIndex performance counter?

- A. NRCellDU
- B. Switching Technology
- C. Packet Switched
- D. Generation

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1157`）

</details>

**1.5.3-362.** What is the primary purpose of the A1 interface in O-RAN?

- A. To enable communication between the SMO and the Near-RT RIC.
- B. To provide a standardized way for the Near-RT RIC to interact with the O1 interface.
- C. To facilitate the transfer of ML model performance data from the Near-RT RIC to the Non-RT RIC.
- D. To allow the Non-RT RIC to directly control radio resource management functions in the Near-RT RIC.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1160`）

</details>

**1.5.3-363.** What is the purpose of the "OR.CellUA.MultiplexRxPdsch" measurement in an O-RAN network?

- A. To measure the number of PDSCHs received with different levels of multiplexing.
- B. To track the maximum number of inactive UEs in a cell.
- C. To monitor the number of packets dropped due to network congestion.
- D. To evaluate the performance of the O-DU's radio frequency (RF) chain.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1161`）

</details>

**1.5.3-364.** What is the purpose of the @checksum attribute in the provided XML snippet?

- A. To identify the specific version of the file.
- B. To verify the integrity of the file on the O-RU side.
- C. To specify the path of the file relative to the package root folder.
- D. To provide a unique name for the file.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1163`）

</details>

**1.5.3-365.** What is a recommended resilience implementation for a reliable timing/sync architecture in O-RAN?

- A. Redundant timing solutions
- B. Partial Timing Supported Network
- C. Integrated APTS functions
- D. Backup timing source from the T-GM

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1164`）

</details>

**1.5.3-366.** What factors influence the determination of the number of clock node hops in an O-RAN network?

- A. Target time error budget, network path length, clock type, and Grandmaster type
- B. Number of RUs, type of synchronization protocol, and network latency
- C. Power consumption, network topology, and frequency of synchronization updates
- D. Bandwidth, data rate, and number of connected devices

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1165`）

</details>

**1.5.3-367.** What is the purpose of the global beamId/O-RU/local beamId mapping table in the context of selective transmission and reception with non-beamforming O-RUs?

- A. To configure the mapping between global beam IDs and local beam IDs for each O-RU.
- B. To enable beamforming capabilities for O-RUs that are not beamforming capable.
- C. To optimize the signal strength for each beam by adjusting the power levels.
- D. To determine the optimal number of beams for each O-RU based on network traffic.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1166`）

</details>

**1.5.3-368.** What is the expected outcome of a test that introduces a spelling mistake in the PolicyObject for schema validation error in the DUT?

- A. The test will pass if the DUT successfully validates the PolicyObject despite the spelling mistake.
- B. The test will pass if the DUT returns a "400 Bad Request" HTTP response code.
- C. The test will pass if the DUT returns a "200 OK" HTTP response code.
- D. The test will pass if the DUT successfully identifies and corrects the spelling mistake.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1167`）

</details>

**1.5.3-369.** In the context of O-RAN testing, what is the primary synchronization source for an O-RU when using the ITU-T G.8275.1 profile (LLS-C1)?

- A. GNSS
- B. PRTC
- C. O-DU with PTP Grand Master and SyncE Master
- D. Midhaul network

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1168`）

</details>

**1.5.3-370.** What NETCONF RPC is used to activate software on an O-RU8?

- A. software-activate
- B. software-update
- C. software-install
- D. software-load

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1172`）

</details>

**1.5.3-371.** What is the maximum allowable Time Error Limit (TEL) for a packet in an Enhanced Radio Unit (eRU) at the O-RU UNI?

- A. ≤1100ns
- B. ≤60ns
- C. ≤100ns
- D. ≤190ns

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1180`）

</details>

**1.5.3-372.** What is the purpose of the "Query all policy type identifiers" test case in the context of A1-P?

- A. To test the functionality of A1-P Consumer and A1-P Producer in querying all policy type identifiers.
- B. To validate the A1 procedure message sequences and contents.
- C. To determine the DUTs level of interoperability.
- D. To bring the DUTs into operational state.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1181`）

</details>

**1.5.3-373.** What is the maximum allowed Relative 1PPS Time Error between the O-RU UNI ports for an Enhanced RU operating on FR2?

- A. max|𝑇𝐸𝑅𝐿| (1,2) ≤60𝑛𝑠
- B. max|𝑇𝐸𝑅𝐿| (1,2) ≤190𝑛𝑠
- C. max|𝑇𝐸𝑅𝐿| (1,2) ≤100𝑛𝑠
- D. max|𝑇𝐸𝑅𝐿| (1,2) ≤1420𝑛𝑠

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1184`）

</details>

**1.5.3-374.** Which of the following is NOT a benefit of ensuring time synchronization across all nodes in an O-RAN network?

- A. Simplifies the process of correlating logs and events across nodes.
- B. Enhances the security of the network by preventing unauthorized access.
- C. Ensures operational consistency for scheduled tasks and maintenance activities.
- D. Improves data integrity for applications and databases that rely on timestamps.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1185`）

</details>

**1.5.3-375.** In a Multi-Operator O-RU, which role is performed by the NETCONF client associated with the operator who manages the resource partitioning between operators?

- A. Shared Resource Operator
- B. Shared O-RU Host
- C. Synchronization Controller
- D. Grand Master

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1186`）

</details>

**1.5.3-376.** Which component in an O-RAN network is responsible for distributing timing to multiple CSRs and HSR-Fs?

- A. O-RU
- B. HSR
- C. O-DU
- D. T-GM

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1187`）

</details>

**1.5.3-377.** What is the primary purpose of the R1 interface in Open Radio Access Networks (O-RAN)?

- A. To enable communication between the Near-RT RIC and the Non-RT RIC.
- B. To facilitate the integration of rApps (radio applications) with the Non-RT RIC and SMO.
- C. To provide a standardized interface for xApps (cross-domain applications).
- D. To manage the flow of data between the RAN and the core network.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1190`）

</details>

**1.5.3-378.** What happens if the O-RU does not receive a response from the ALD within the reception window?

- A. The O-RU will send an error message to the ALD.
- B. The O-RU will retry the transmission.
- C. The O-RU will send an empty "ald-resp-msg" record in the <rpc-reply>.
- D. The O-RU will wait for an additional 3ms before attempting transmission again.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1192`）

</details>

**1.5.3-379.** Which of the following statements is TRUE regarding the A1-P Producer in Open Radio Access Networks (O-RAN)?

- A. The A1-P Producer can modify or delete existing policies.
- B. The A1-P Producer is responsible for creating and managing policy types.
- C. The A1-P Producer provides JSON schemas for policy types that can be retrieved by the A1-P Consumer.
- D. The A1-P Producer determines which internal function in the Near-RT RIC evaluates the policy.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1193`）

</details>

**1.5.3-380.** Which of the following is NOT a phase of the baseline configuration in O-RAN?

- A. Phase 1
- B. Phase 2
- C. Phase 3
- D. Phase 4

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1194`）

</details>

**1.5.3-381.** Which of the following is a measurement type used to track the volume of UL PDCP SDUs received via the Xn-U UL GTP-U tunnel for data forwarding?

- A. OR.Xn.UlPdcpSduVolRxXnUUlDataForward
- B. OR.Xn.DlPdcpSduVolTxXnUDlDataForward
- C. OR.Xn.UlPdcpSduVolRxXnUUlDataForward.QoS
- D. OR.Xn.UlPdcpSduVolRxXnUUlDataForward.SNSSAI

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1195`）

</details>

**1.5.3-382.** What is the significance of the 'Q' parameter in the O-RU antenna model?

- A. Represents the number of rows of array elements in the array.
- B. Represents the number of polarizations in the array.
- C. Represents the number of overlapping array elements (array-layers) in the array.
- D. Represents the position of the center of the leftmost, bottom element of the array.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1198`）

</details>

**1.5.3-383.** What is the purpose of the 're-call-home-no-ssh-timer' parameter in the O-RAN operations yang model?

- A. To determine the maximum number of call-home attempts an O-RU can make.
- B. To set the time interval between repeated call-home procedures to call-home servers.
- C. To trigger the restart of the call-home process.
- D. To establish an m-plane connection with the O-DU.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1201`）

</details>

**1.5.3-384.** What type of interface is used for communication between the O-DU and SMO in the described test scenario?

- A. F1AP
- B. NGAP
- C. O1
- D. PFCP

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1203`）

</details>

**1.5.3-385.** What type of beamforming does the test framework utilize when an O-RU DUT supports Digital Beamforming?

- A. Time domain beamforming
- B. Frequency domain beamforming
- C. Spatial domain beamforming
- D. Polarization domain beamforming

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1204`）

</details>

**1.5.3-386.** What O-RAN operations yang model parameters can be optimized to ensure the O-DU (Updated) is ready to receive call-home requests from the Shared O-RU?

- A. re-call-home-no-ssh-timer and max-call-home-attempts
- B. o-ran-operations.yang and restart-call-home RPC
- C. Shared O-RU and O-DU (Updated)
- D. m-plane connection establishment and call-home signals

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1206`）

</details>

**1.5.3-387.** Which of the following is NOT a valid DUID (DHCP Unique Identifier) type defined in the provided context?

- A. duid-llt
- B. duid-en
- C. duid-ll
- D. duid-mac

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1207`）

</details>

**1.5.3-388.** During antenna calibration, how does the O-DU handle user data scheduling?

- A. The O-DU schedules user data only in calibration symbols, regardless of the direction (DL or UL).
- B. The O-DU schedules user data only during calibration operation, using resources identified for calibration.
- C. The O-DU avoids scheduling user data in resources identified for calibration, but may schedule data in other resources.
- D. The O-DU schedules user data in all resources, regardless of whether they are used for calibration.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1208`）

</details>

## 1.5.4 網路功能虛擬化（NFV）（58 題）

**1.5.4-1.** What does the acronym SOA stand for? [ETSI NFV Release 5]

- A. Service Based Architecture
- B. System-Oriented Architecture
- C. Software-Oriented Architecture
- D. Standard-Oriented Architecture
- E. Service-Oriented Architecture

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6387`）

</details>

**1.5.4-2.** Who are the final consumers of the services provided by Telecommunications Service Providers (TSPs) in the NFV (Network Function Virtualization) environment?

- A. Telecommunications Service Providers (TSPs)
- B. VNF Providers (VNFPs) and Server Providers (SPs)
- C. Brokers
- D. Infrastructure Providers (InPs)
- E. End Users

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-837`）

</details>

**1.5.4-3.** In NFV (Network Function Virtualization) design considerations, what is a key security risk that should be considered in NFV infrastructure designs?

- A. Failure or security breach in one function affecting another
- B. Functions/services from different subscribers being protected/isolated
- C. Delivered subscriber services affecting the NFVI
- D. Reliability and availability of functions
- E. Support for heterogeneity

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-44`）

</details>

**1.5.4-4.** What are virtualisation-dependent items? [ETSI NFV Release 5]

- A. Items whose value depends on NFV management functions
- B. Items whose value depends on NFV infrastructure decisions
- C. Items whose value depends on both NFV infrastructure and management functions
- D. Items whose value depends on OSS/BSS

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-340`）

</details>

**1.5.4-5.** Which mitigation approaches are mentioned for network services management under migration? [ETSI NFV Release 5]

- A. Transferring management requests to another NFV-MANO system
- B. Duplicate NFV-MANO system in active-standby mode
- C. Implementing redundancy units
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-376`）

</details>

**1.5.4-6.** What is the scope of VNF configuration? [ETSI NFV Release 5]

- A. Configuration of virtual resources only
- B. Configuration of software resources only
- C. Configuration of both software and virtual resources
- D. Configuration of physical resources

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-420`）

</details>

**1.5.4-7.** What is the main advantage of disaggregated networks?

- A. Optimal resource utilization
- B. Lower OPEX and CAPEX
- C. Centralized control and management
- D. Higher network capacity
- E. Enhanced quality of service

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-442`）

</details>

**1.5.4-8.** What is an important advantage of network resource sharing using NFV (Network Function Virtualization) and SDN (Software Defined Networking)?

- A. Improved network resilience
- B. Increased network capacity
- C. Reduced network cost
- D. Enhanced QoS for end-users
- E. Faster data transfer speeds

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-657`）

</details>

**1.5.4-9.** What is the term used to refer to the management and orchestration of services? [ETSI NFV Release 5]

- A. RAN virtualisation
- B. Functional splits
- C. NFV-MANO
- D. NSMF
- E. PF

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-810`）

</details>

**1.5.4-10.** What is a Virtual Machine?

- A. A provider that offers virtual home environment services.
- B. A type of telecommunication service with a fixed bit rate.
- C. A software program that simulates a hypothetical computer central processing unit.
- D. A provider that offers services other than basic telecommunications service for additional charges.
- E. A type of telecommunication service with a bit rate that can vary within defined limits.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-944`）

</details>

**1.5.4-11.** Which organization standardized network function virtualization (NFV)?

- A. ITU
- B. ONF
- C. ETSI
- D. 3GPP
- E. ITU-T

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1024`）

</details>

**1.5.4-12.** What is the benefit of wireless network virtualization in terms of service provisioning?

- A. Customization for specific services
- B. Limited service options
- C. Inflexible service provisioning
- D. All of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1265`）

</details>

**1.5.4-13.** Which player(s) in the NFV (Network Function Virtualization) environment lease resources from Infrastructure Providers (InPs) to run Virtual Network Functions (VNFs)?

- A. Telecommunications Service Providers (TSPs)
- B. VNF Providers (VNFPs) and Server Providers (SPs)
- C. Brokers
- D. Infrastructure Providers (InPs)
- E. End Users

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1447`）

</details>

**1.5.4-14.** What are the pre-conditions for estimating the energy consumption of VNF/VNFCs? [3GPP Release 18]

- A. Presence of embedded sensors in NFVI nodes
- B. Presence of external sensors in NFVI nodes
- C. Knowledge of which NFVI nodes the VNF/VNFC instances run on
- D. Low energy consumption of VNF/VNFC instances

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1716`）

</details>

**1.5.4-15.** What is a Virtual Network Function (VNF)?

- A. An implementation of an NF that is deployed on physical resources
- B. A functional block within a physical network infrastructure
- C. A virtualized version of a Network Function deployed on virtual resources
- D. A software component with hosting or routing functionality

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1753`）

</details>

**1.5.4-16.** What is the relationship between the VM (virtual machine) migration time and the amount of data migrated?

- A. As the amount of data migrated increases, the VM migration time decreases
- B. As the amount of data migrated increases, the VM migration time increases
- C. There is no relationship between the amount of data migrated and the VM migration time
- D. The VM migration time is independent of the amount of data migrated

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1835`）

</details>

**1.5.4-17.** What are the key elements of the NFV Architecture?

- A. Network Function Virtualization Infrastructure, Virtual Network Functions, and Network Function Virtualization Management and Orchestration
- B. Network Function Virtualization Infrastructure, Virtual Network Functions, and Network Flow Virtualization
- C. Network Function Virtualization Infrastructure, Virtual Network Functions, and Network Function Virtualization Interfaces
- D. Network Function Virtualization Infrastructure, Software-Defined Networking, and Network Function Virtualization Management and Orchestration

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2056`）

</details>

**1.5.4-18.** What are the common aspects of coexistence between SBA NFV-MANO systems? [ETSI NFV Release 5]

- A. Usage of service interfaces
- B. Usage of SBA specific common services
- C. Usage of communication service
- D. Authorization of consumers and producers
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2120`）

</details>

**1.5.4-19.** What is the purpose of the NFV (network function virtualization) management and orchestration (MANO)?

- A. To orchestrate and manage the US-NSIs
- B. To securely expose required services and capabilities to every US-NSI
- C. To dynamically allocate network resources to every US-NSI
- D. To translate tenant requirements to US-NSIs' requirements
- E. To provide centralized management and orchestration of P/V-NFs and their resources

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2369`）

</details>

**1.5.4-20.** What is the full form of NFV? [ETSI NFV Release 5]

- A. Network Function Virtualization
- B. Non-Functional Verification
- C. Network and Field Variation
- D. Non-Fungible Token Verification
- E. Network File Virtualization

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2440`）

</details>

**1.5.4-21.** Which architecture combines SDN (such as software-defined networking) and NFV characteristics and consists of entities such as the Network Management System (NMS), the Network Function Virtualization Infrastructure (NFVI), and the Operation/Business Support Scheme (OSS/BSS)?

- A. ETSI SDN-NFV MANO
- B. ETSI GANA
- C. 3GPP-ETSI MEC Architecture
- D. Microservices-based SDN Controller
- E. Multi-Agent System (MAS)

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2560`）

</details>

**1.5.4-22.** What is the goal of NFV (network function virtualization) in H-CRANs (heterogeneous cloud radio access networks)?

- A. To improve capacity and extend coverage
- B. To reduce interference and improve signal strength
- C. To optimize resource allocation and management
- D. To achieve cost-effective sharing of resources

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2607`）

</details>

**1.5.4-23.** What does NFV (Network Function Virtualization) enable in the Frugal 5G network?

- A. Wireless Backhaul Integration
- B. Multi-operator resource sharing
- C. Localized communication support
- D. Cloud-AN communication
- E. Flexible Fog control

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2763`）

</details>

**1.5.4-24.** What are the NFV management and orchestration capabilities that can be leveraged for applying energy efficiency policies? [ETSI NFV Release 5]

- A. There are no NFV management and orchestration capabilities that can be used for energy efficiency policies.
- B. NFV management and orchestration capabilities can be used to adjust power states of NFVI resources.
- C. NFV management and orchestration capabilities can be used to optimize VNF/NS placement based on power consumption savings.
- D. Both option 2 and option 3 are correct.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2795`）

</details>

**1.5.4-25.** What can network function virtualization (NFV) enable in wireless network virtualization?

- A. Efficient chaining of network functions
- B. Chain of virtual functions in appropriate order
- C. Creation of a service function chain (SFC)
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2853`）

</details>

**1.5.4-26.** What does NFV-MANO stand for? [ETSI NFV Release 5]

- A. Network Function Virtualization-Management and Operations
- B. Network Functional Virtualization-Management and Networking
- C. Network Function Virtualization-MANagement and Operations
- D. Network Functional Virtualization-Management and Operations

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2916`）

</details>

**1.5.4-27.** Which player(s) in the NFV (Network Function Virtualization) environment provide software implementations for Network Functions?

- A. Telecommunications Service Providers (TSPs)
- B. VNF Providers (VNFPs) and Server Providers (SPs)
- C. Brokers
- D. Infrastructure Providers (InPs)
- E. End Users

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2945`）

</details>

**1.5.4-28.** What can wireless network virtualization enable in terms of service innovation?

- A. Deployment of new services or techniques
- B. Limited service options
- C. Restrictions on new techniques/products
- D. All of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3520`）

</details>

**1.5.4-29.** According to NFV (Network Function Virtualization) design considerations, what is important for operators making the transition to NFV?

- A. Network scalability and automation
- B. Support for heterogeneity
- C. Legacy support
- D. Reliability and availability
- E. Security and resilience

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3672`）

</details>

**1.5.4-30.** What is the NFV Infrastructure (NFVI)?

- A. The combination of hardware and software resources used to deploy VNFs
- B. The physical resources used in a data center environment
- C. Virtual resources that abstract the computing, storage, and network resources
- D. A hypervisor layer that decouples virtual resources from physical resources

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3704`）

</details>

**1.5.4-31.** What are the design aspects of VNF and NS that influence their power consumption? [ETSI NFV Release 5]

- A. The design aspects of VNF and NS do not have any influence on their power consumption.
- B. Redundancy configurations of VNFs/NSs can influence their power consumption.
- C. The choice of compute resources used for VNF and NS deployment can influence their power consumption.
- D. Both option 2 and option 3 are correct.

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3844`）

</details>

**1.5.4-32.** Which player(s) in the Network Function Virtualization (NFV) environment deploy and manage physical resources in the form of data centers and physical networks?

- A. Telecommunications Service Providers (TSPs)
- B. VNF Providers (VNFPs) and Server Providers (SPs)
- C. Brokers
- D. Infrastructure Providers (InPs)
- E. End Users

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4188`）

</details>

**1.5.4-33.** What is the purpose of a Configuration Server? [ETSI NFV Release 5]

- A. Distribute and store configuration data in a centralized manner
- B. Manage virtual resources for VNFs
- C. Communicate with network elements
- D. Perform auto-scaling of VNF instances

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4560`）

</details>

**1.5.4-34.** What is the purpose of wireless network virtualization?

- A. To improve resource utilization
- B. To support diverse services/use cases
- C. To be cost-effective and flexible for new services
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4577`）

</details>

**1.5.4-35.** In the NFV (Network Function Virtualization) environment, which player(s) may act as a brokerage role, discovering, negotiating, and aggregating resources and functions from multiple entities?

- A. Telecommunications Service Providers (TSPs)
- B. VNF Providers (VNFPs) and Server Providers (SPs)
- C. Brokers
- D. Infrastructure Providers (InPs)
- E. End Users

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4720`）

</details>

**1.5.4-36.** Which player(s) in the NFV (Network Function Virtualization) environment provide industry standard servers on which VNFs can be deployed?

- A. Telecommunications Service Providers (TSPs)
- B. VNF Providers (VNFPs) and Server Providers (SPs)
- C. Brokers
- D. Infrastructure Providers (InPs)
- E. End Users

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4725`）

</details>

**1.5.4-37.** What procedure is followed to estimate the energy consumption of VNF/VNFCs based on the vCPU usage of virtual compute resources? [3GPP Release 18]

- A. Collect PEE measurements from NFVI nodes
- B. Collect vCPU usage of virtual compute resources from VIM
- C. Collect vCPU usage of virtual compute resources from VNFM
- D. Collect vCPU usage of virtual compute resources from VNF/VNFC instances

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4881`）

</details>

**1.5.4-38.** What can influence the variations on per-instance NF load and resource usage? [3GPP Release 18]

- A. The Reporting Threshold
- B. The load itself
- C. The Validity Period
- D. The Analytics ID
- E. The number of running NF instances

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5290`）

</details>

**1.5.4-39.** What is the significance of virtualization technologies in 5G? 

- A. To increase network capacity
- B. To improve network security
- C. To enable network slicing
- D. To reduce hardware cost and power consumption
- E. To provide low-latency communication

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5398`）

</details>

**1.5.4-40.** What is NFV power consumption? [ETSI NFV Release 5]

- A. Power consumption associated with physical infrastructure
- B. Power consumption associated with virtualized resources and containerized workloads
- C. Power consumption associated with network service instances
- D. Power consumption associated with NFV-MANO system

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5495`）

</details>

**1.5.4-41.** What is NFV?

- A. Networked File Virtualization
- B. Network Function Virtualization
- C. Network Forwarding Virtualization
- D. Network File Virtualization
- E. Network Function Visualization

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5550`）

</details>

**1.5.4-42.** How can NFV-MANO and the service provider acquire power consumption and energy efficiency related measurements of virtualized resources and containerized workloads? [ETSI NFV Release 5]

- A. Through the use of estimated values
- B. Through backup procedures
- C. Through power restoration
- D. Through monitoring interfaces

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5581`）

</details>

**1.5.4-43.** Which technology is used to manage core networking functions using a software-based approach?

- A. ICN
- B. SDN
- C. NFV
- D. Network Slicing

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5809`）

</details>

**1.5.4-44.** What is a service in the context of NFV (Network Function Virtualization)?

- A. A virtualized implementation of a Network Function
- B. A single Virtual Network Function deployed on multiple VMs
- C. A functional block within a network infrastructure
- D. An offering provided by a Telecommunication Service Provider composed of one or more NFs

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5829`）

</details>

**1.5.4-45.** What is the main difference between SBA approach and conventional approach in specifying interactions between functional blocks? [ETSI NFV Release 5]

- A. Conventional approach does not specify interactions between functional blocks
- B. SBA approach focuses on information flows, while conventional approach focuses on services offered
- C. SBA approach does not specify interactions between functional blocks
- D. SBA approach focuses on services offered by the architecture, while conventional approach focuses on information flows

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5896`）

</details>

**1.5.4-46.** What are the motivations for wireless network virtualization?

- A. To reduce operational complexity
- B. To increase network capacity
- C. To provide value-added services
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5953`）

</details>

**1.5.4-47.** Which design consideration for NFV (Network Function Virtualization) refers to the need for dynamic environments and the ability to deploy and remove VNFs on demand?

- A. Network architecture and performance
- B. Security and resilience
- C. Reliability and availability
- D. Support for heterogeneity
- E. Network scalability and automation

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6423`）

</details>

**1.5.4-48.** Which key issues are related to the process of migration of NFV-MANO system towards SBA? [ETSI NFV Release 5]

- A. O: SBA coexistence
- B. N: Migration strategy of the operator
- C. O: SBA coexistence and N: Migration strategy of the operator
- D. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6892`）

</details>

**1.5.4-49.** What is the relationship between NFV (Network Function Virtualization) and cloud computing?

- A. NFV and cloud computing are unrelated concepts
- B. NFV runs on existing cloud environments
- C. NFV requires adaptations to cloud environments in order to achieve carrier-class behavior
- D. NFV replaces cloud computing in the telecommunications industry
- E. NFV improves the performance of cloud computing

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7114`）

</details>

**1.5.4-50.** What are some aspects of NFVI provisioning and HW/SW management that are expected to be affected in vRAN deployments? [ETSI NFV Release 5]

- A. Overall VNF design and requirements
- B. Connection Points (CP) and Service Access Points (SAP)
- C. Hardware acceleration and time synchronization
- D. Network slicing and spectrum management
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7657`）

</details>

**1.5.4-51.** What is Network Function Virtualization (NFV)?

- A. A network concept that proposes to use virtualization technologies to manage core networking functions using a software based approach
- B. A physical network infrastructure that provides virtualization capabilities for network functions
- C. A network architecture that replaces physical network functions with virtual ones
- D. A virtualization technology that allows for the creation of multiple virtual networks on a shared physical infrastructure

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-8041`）

</details>

**1.5.4-52.** What is the primary benefit of using NFV technologies in wireless networks?

- A. Improving network security
- B. Reducing capital expenditure (CAPEX)
- C. Increasing network latency
- D. Enhancing user experience

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-19`）

</details>

**1.5.4-53.** What does the acronym "MANO" stand for in the context of Open Radio Access Networks (O-RAN)?

- A. Mobile Access Network Optimization
- B. Management and Orchestration
- C. Multi-Access Network Orchestration
- D. Mobile Application Network Orchestration

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-580`）

</details>

**1.5.4-54.** Which HTTP method is supported for modifying an individual VNF instance?

- A. POST
- B. GET
- C. PUT
- D. PATCH

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-728`）

</details>

**1.5.4-55.** Which of the following attributes is NOT necessarily present in VnfExtCpConfig, even when conditions allow for its presence?

- A. resourceProviderId
- B. cpProtocolData
- C. VnfExtCpData
- D. IpOverEthernetAddressData

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-844`）

</details>

**1.5.4-56.** Which of the following data structures is used by the DMS to provide information about a completed VNF lifecycle operation to the SMO?

- A. VnfLcmOpOcc
- B. NF Deployment
- C. Individual VNF LCM operation occurrence
- D. VNF Lifecycle Management Operation Occurrence Notification

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-849`）

</details>

**1.5.4-57.** Which of the following is NOT a supported connectivity change for an NF Deployment using the 'Change external connectivity' operation?

- A. Disconnecting external CPs from one external VL and connecting them to another.
- B. Deleting external CP instances representing subports in a trunk.
- C. Creating a new external CP representing the parent port of a trunk.
- D. Changing the L3 address of an existing external CP.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-907`）

</details>

**1.5.4-58.** What is the initial state of the "Individual VNF instance" resource representing the NF Deployment after it is created?

- A. INSTANTIATED
- B. NOT_INSTANTIATED
- C. PROCESSING
- D. COMPLETED

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1197`）

</details>

## 1.5.5 雲端平台：O-Cloud 與雲原生網路功能（89 題）

**1.5.5-1.** Which service model provides middleware-style services such as database and component services for use by applications?

- A. Software as a service (SaaS)
- B. Platform as a service (PaaS)
- C. Infrastructure as a service (IaaS)
- D. Cloud bursting
- E. Cloud infrastructure management

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-293`）

</details>

**1.5.5-2.** Which service model of cloud computing allows the user to use the provider's applications running on a cloud infrastructure?

- A. Infrastructure as a Service (IaaS)
- B. Platform as a Service (PaaS)
- C. Software as a Service (SaaS)
- D. Application as a Service (AaaS)
- E. Software only Service (SoS)

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4351`）

</details>

**1.5.5-3.** Which component is responsible for configuring O-Cloud?

- A. PCL rAPP
- B. SDN-C/R
- C. xAPP
- D. AI Server
- E. ONAP

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-631`）

</details>

**1.5.5-4.** What is the purpose of the O2 Client?

- A. To collect RAN statistics for each slice
- B. To process JavaScript Object Notation (JSON) messages
- C. To transport and process data from any source to any target
- D. To trigger the scaling up/down of network resources
- E. To predict the future values of target parameters

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2016`）

</details>

**1.5.5-5.** What are the essential characteristics of cloud computing?

- A. On-demand self-start, Broad network access, Resource pooling, Rapid expansion, Metered performance
- B. On-demand self-service, Narrow network access, Resource pooling, Slow elasticity, Abstracted service
- C. On-command self-service, Broad network access, Resource sharing, Rapid elasticity, Measured service
- D. On-demand self-service, Broad network access, Resource pooling, Rapid elasticity, Measured service
- E. On-demand self-service, Broad network access, Resource pooling, Rapid elasticity, Abstracted service

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4129`）

</details>

**1.5.5-6.** Which acronym represents a platform used to host O-RAN functions? 

- A. KR
- B. PRACH
- C. O-Cloud
- D. OSS
- E. MME

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4299`）

</details>

**1.5.5-7.** Which deployment scenario in O-RAN Town involves vO-DU on the cell site and vO-CU at the aggregation location? 

- A. Scenario 1 - Distributed RAN
- B. Scenario 2 - Centralized vO-CU
- C. Scenario 3 - Centralized RAN
- D. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5038`）

</details>

**1.5.5-8.** Which virtualization technology is more flexible for packaging and deploying software infrastructure services?

- A. Virtual Machine
- B. Container
- C. Network Functions Virtualization
- D. Software-defined Networking
- E. Network Slicing

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5204`）

</details>

**1.5.5-9.** Which deployment scenario in O-RAN Town involves vO-CU and vO-DU on the cell site? 

- A. Scenario 1 - Distributed RAN
- B. Scenario 2 - Centralized vO-CU
- C. Scenario 3 - Centralized RAN
- D. None of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6012`）

</details>

**1.5.5-10.** What is the difference between virtual machines (VMs) and containers?

- A. VMs have lower virtualization overhead
- B. Containers fully emulate the OS kernel and hardware
- C. Containers share the hardware and kernel with their host machines
- D. VMs occupy much less resources
- E. Containers have higher adaptability

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6445`）

</details>

**1.5.5-11.** Which type of cloud-based infrastructure is comprised of various proximate and distant computing nodes, either mobile or immobile?

- A. Distant immobile clouds
- B. Proximate immobile computing entities
- C. Proximate mobile computing entities
- D. Hybrid

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6588`）

</details>

**1.5.5-12.** What is the main idea behind building hybrid resources in cloud-based infrastructures?

- A. To employ heterogeneous computing resources
- B. To create a balance between user requirements and available options
- C. To maximize the utilization costs of nearby resources
- D. To deliver enhanced security and privacy features

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7333`）

</details>

**1.5.5-13.** What is the purpose of CNF in O-RAN? 

- A. Control Plane
- B. Common Public Radio Interface
- C. Containers or Cloud-Native Network Functions
- D. Carrier aggregation
- E. Cell Site Gateway

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7714`）

</details>

**1.5.5-14.** What is the advantage of cloud computing for service providers?

- A. Customize their level of service on a pay-as-you-go basis
- B. Reduce capital expenditure and operational expenditure
- C. Provide large scale storage and compute resource pooling
- D. Deliver services from the cloud
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7744`）

</details>

**1.5.5-15.** Which of the following is a potential commercial cloud platform for central cloud deployment?

- A. Openstack
- B. Amazon Web Services
- C. Microsoft Azure
- D. Google App Engine
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7794`）

</details>

**1.5.5-16.** Which of the following is a use case scenario discussed in the context?

- A. Alarm query with TE&IV services
- B. Network slicing for 5G
- C. QoS monitoring and optimization
- D. O-RAN interoperability testing

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-0`）

</details>

**1.5.5-17.** What is the main topic of the document mentioned in the context?

- A. O-RAN Adopter License Agreement
- B. Cloud Platform Reference Designs for O-RAN
- C. Technical Specification for O-RAN WG6
- D. IPR Policy for O-RAN

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-5`）

</details>

**1.5.5-18.** What is the primary method for enabling automatic scaling of an NF Deployment using the O2dms API profile?

- A. Setting the "isAutoscaleEnabled" attribute in the "VnfInstance" data type.
- B. Manually configuring scaling parameters in the NF Deployment instance.
- C. Using a third-party scaling tool integrated with the NFVO.
- D. Triggering a scaling event through the NFVO's API.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-21`）

</details>

**1.5.5-19.** Which of the following is NOT a benefit of O-Cloud software management?

- A. Prevents unauthorized software from being installed
- B. Ensures security
- C. Provides cost management
- D. Allows for the creation of O-RAN Cloudified Network Functions

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-26`）

</details>

**1.5.5-20.** What is the purpose of an Affinity rule in O-RAN deployments?

- A. To ensure deployments with the same rule are spread across different scopes.
- B. To ensure deployments with the same rule are located within the same scope.
- C. To specify that deployments with the same rule cannot be collocated.
- D. To specify that deployments with the same rule must be located in different server groups.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-40`）

</details>

**1.5.5-21.** Which of the following is NOT a typical provider of Cloud Infrastructure Resources?

- A. Internal Cloud Provider
- B. External Cloud Provider
- C. Public Cloud Provider
- D. O-RAN Alliance

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-53`）

</details>

**1.5.5-22.** Which of the following functionalities is NOT supported by TE&IV services as outlined in the provided context?

- A. Bulk uploading TE&IV resources
- B. Deleting TE&IV resources
- C. Notifying subscribers about changes in TE&IV resources
- D. Monitoring real-time network traffic

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-58`）

</details>

**1.5.5-23.** What is the primary responsibility of the Infrastructure Management Services (IMS) in an O-RAN architecture?

- A. Managing the deployment of Network Functions (NFs) into the O-Cloud.
- B. Managing the hardware accelerators used in the O-Cloud.
- C. Managing the O-Cloud resources and the software used to manage them.
- D. Providing connectivity to networks outside the data center.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-88`）

</details>

**1.5.5-24.** What is the purpose of validation rules in the context of Open Radio Access Networks (O-RAN)?

- A. To ensure that only authorized users can access the O-Cloud.
- B. To prevent unwanted functionality from being introduced into the O-Cloud.
- C. To define the data models used for O-RAN provisioning.
- D. To monitor network performance and identify potential issues.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-98`）

</details>

**1.5.5-25.** Which of the following is NOT an example of an O-Cloud Resource?

- A. Compute
- B. HW-Accelerator
- C. Storage
- D. User Interface

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-101`）

</details>

**1.5.5-26.** What type of interface is used for the inter-chip communication between the FPGA components in an O-RAN accelerator?

- A. PCIe Gen3x16
- B. 100G Ethernet
- C. 10/25G Ethernet
- D. eCPRI

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-110`）

</details>

**1.5.5-27.** Which of the following functions allows an AAL Application to release internal resources allocated during initialization?

- A. initAal
- B. cleanupAal
- C. getAalLpuInfo
- D. AAL-Profile-Queue

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-136`）

</details>

**1.5.5-28.** What is the primary role of the O2ims_InfrastructureInventory services in an O-RAN environment?

- A. Providing read-only access to the O-Cloud's inventory for asset management purposes.
- B. Configuring and managing physical, software, and logical resources within the O-Cloud.
- C. Exposing the O-Cloud's capabilities to the Service Management and Orchestration (SMO) for control.
- D. Ensuring the security and integrity of the O-Cloud infrastructure.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-149`）

</details>

**1.5.5-29.** What is the primary function of a Site Gateway in an O-RAN network?

- A. To provide Layer 2 connectivity between Computer Systems and Gateways within a Cloud Site.
- B. To separate cloud internal and external traffic for security, traffic management, and operational purposes.
- C. To provision O-Cloud Site Networks as a special type of O-Cloud Resources.
- D. To limit the span of Layer 2 connectivity within a Cloud Site.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-158`）

</details>

**1.5.5-30.** Which of the following is NOT a key location identified in the context for O-RAN deployments?

- A. Cell Site
- B. Edge Cloud
- C. Regional Cloud
- D. Core Cloud

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-166`）

</details>

**1.5.5-31.** What type of hardware is typically used to accelerate computationally intensive functions in an O-DU8 system?

- A. Multi-core processors
- B. Field Programmable Gate Arrays (FPGAs)
- C. Application Specific Integrated Circuits (ASICs)
- D. Both 2 and 3

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-167`）

</details>

**1.5.5-32.** How can the AAL Implementation software be deployed in relation to containers or VMs running AAL Applications?

- A. The AAL Implementation software must be entirely contained within the containers or VMs running AAL Applications.
- B. The AAL Implementation software can be partially or fully located inside or outside the containers or VMs.
- C. The AAL Implementation software must be entirely outside the containers or VMs running AAL Applications.
- D. The AAL Implementation software cannot be used in conjunction with containers or VMs.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-183`）

</details>

**1.5.5-33.** In an O-RAN context, what is considered the "source of truth" for fault information?

- A. The SMO (Service Management and Orchestration)
- B. The O-Cloud resource
- C. The fault notification recipient
- D. The IMS (Information and Management System)

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-223`）

</details>

**1.5.5-34.** Which of the following attributes is NOT necessarily present in the ResourcePlacement data type, even when conditions allow for its presence?

- A. snapshotResDef
- B. NF Deployment
- C. Resource Constraints
- D. Placement Information

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-224`）

</details>

**1.5.5-35.** What is the purpose of an O-Cloud Site Network?

- A. To provide a logical network connection for Compute Nodes within their cluster and across O-Cloud Sites.
- B. To physically connect O-Cloud Sites to external networks.
- C. To manage the physical network infrastructure within an O-Cloud Site.
- D. To provide a secure connection for user data traffic.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-230`）

</details>

**1.5.5-36.** Which of the following hardware acceleration designs is NOT mentioned in the context?

- A. Structured ASIC Accelerator Design
- B. FPGA-based Hardware Acceleration
- C. Software-defined Networking (SDN) Acceleration
- D. PCIe-based Accelerator Design

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-235`）

</details>

**1.5.5-37.** Which of the following is a key component of the O-RAN architecture that allows for the creation of virtualized network functions?

- A. O-Cloud Node
- B. Heartbeat Subscription
- C. Network Slice Deletion
- D. Underlay Network

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-249`）

</details>

**1.5.5-38.** What is the name of the information object class that represents an AAL Profile Instance?

- A. AalLpu
- B. AalProfileInstance
- C. AalProfileQueue
- D. Top_

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-279`）

</details>

**1.5.5-39.** In the context of O-RAN, what does the blue text in the NF Deployment descriptor represent?

- A. Modeling of AAL-related information and requirements.
- B. Modeling of TOSCA-specific capabilities according to ETSI GS NFV-SOL 001.
- C. Modeling of general NF capabilities unrelated to AAL.
- D. Modeling of runtime configuration information injected into a VM-based NF Deployment unit.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-299`）

</details>

**1.5.5-40.** Which attribute in the OsContainerDesc information element is used to describe acceleration capabilities for containerized deployments in Open Radio Access Networks (O-RAN)?

- A. extendedResourcesRequests
- B. accelerationCapabilities
- C. containerPlacementConstraints
- D. VDUCapabilities

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-368`）

</details>

**1.5.5-41.** What is the initial state of the "Individual VNF instance" resource representing the NF Deployment for the auto-healing procedure to begin?

- A. INSTANTIATED
- B. STARTING
- C. RUNNING
- D. STOPPED

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-389`）

</details>

**1.5.5-42.** What is a primary benefit of using Custom Resource Definitions (CRDs) to configure an O-Cloud for Near-RT RIC, compared to using API Aggregation?

- A. CRDs are more flexible in terms of API behaviors.
- B. CRDs require programming to implement.
- C. CRDs are easier to implement and require no programming.
- D. CRDs provide more advanced lifecycle management capabilities for the Near-RT RIC.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-398`）

</details>

**1.5.5-43.** Which of the following is NOT a type of Network Function (NF) used in O-RAN systems?

- A. VNF (Virtual Network Function)
- B. CNF (Cloud-native Network Function)
- C. PNF (Physical Network Function)
- D. DNF (Distributed Network Function)

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-400`）

</details>

**1.5.5-44.** What is the primary goal of the described test regarding the O2 interface?

- A. To ensure data is transmitted without modification or alteration.
- B. To verify the speed and efficiency of data transmission.
- C. To test the compatibility of different O-RAN components.
- D. To evaluate the security of the O2 interface against unauthorized access.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-402`）

</details>

**1.5.5-45.** What is the primary advantage of using hardware acceleration in Open Radio Access Networks?

- A. Improved network security.
- B. Increased data processing speed.
- C. Reduced network latency.
- D. Enhanced network capacity.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-411`）

</details>

**1.5.5-46.** What is the primary role of the rApp in the context of O-Cloud Node draining?

- A. To identify the need for fault recovery or maintenance and provide recommendations for draining.
- B. To perform NF relocation and drain the O-Cloud Node.
- C. To monitor O1 and O2 PM, FM data for any undesirable behavior.
- D. To inform the operator about the status of the O-Cloud Node.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-440`）

</details>

**1.5.5-47.** What is a key function of Site Gateways in O-RAN?

- A. Connecting O-Cloud Nodes to a centralized management system
- B. Separating Layer 2 domains between the Cloud Sites Site Network Fabric and external transport domains
- C. Providing radio interface functionality for user devices
- D. Managing the distribution of radio resources across multiple cells

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-448`）

</details>

**1.5.5-48.** What type of device can be assigned to a container or VM instance to accelerate specific functions in an O-RAN system?

- A. Storage Device
- B. Network Interface Card
- C. Accelerator (e.g., FPGA, GPU)
- D. CPU

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-461`）

</details>

**1.5.5-49.** What is a key challenge in managing cloudified RAN network functions in Open RAN?

- A. The dynamic mapping between logical network functions and physical hardware.
- B. The lack of standardized interfaces for managing the network.
- C. The limited availability of cloud-based management tools.
- D. The complexity of managing distributed network elements.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-479`）

</details>

**1.5.5-50.** What are the valid modes of operation for the AAL FEC PDSCH Profile interface?

- A. CB-mode and TB-mode
- B. CRC-mode and TB-mode
- C. CB-mode and CRC-mode
- D. Code Block mode and Transport Block mode

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-480`）

</details>

**1.5.5-51.** What are the three layers involved in decoupling hardware and software in O-RAN?

- A. Hardware Layer, Cloud Stack Layer, Virtual RAN Functions Layer
- B. Hardware Layer, Acceleration Abstraction Layer, Cloud Stack Layer
- C. Hardware Layer, Acceleration Abstraction Layer, Virtual RAN Functions Layer
- D. Hardware Layer, Cloud Stack Layer, Virtual RAN Functions Layer, Acceleration Abstraction Layer

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-493`）

</details>

**1.5.5-52.** What is a benefit of allowing VMs to leverage advanced features of selected CPU architectures in the context of Open Radio Access Networks (O-RAN)?

- A. Enhanced security for O-RAN components.
- B. Improved performance for vO-CU and vO-DU functions.
- C. Reduced storage requirements for O-RAN components.
- D. Simplified notification subscription frameworks for vO-DU.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-529`）

</details>

**1.5.5-53.** What is an example of a fault-tolerant strategy in O-RAN?

- A. Using a single data center for all network functions.
- B. Deploying network functions in a single geographic location.
- C. Utilizing geo-redundancy and Data Center Zones.
- D. Relying on manual intervention for fault recovery.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-551`）

</details>

**1.5.5-54.** What is the primary focus of the O-Cloud architecture in Open RAN?

- A. Centralizing radio network control and management functions.
- B. Enabling flexible deployment of RAN components.
- C. Providing a cloud-native platform for RAN functions.
- D. All of the above.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-576`）

</details>

**1.5.5-55.** Which pattern do notifications issued on the O2dms_DeploymentFault Service API adhere to?

- A. Publish/Subscribe
- B. Subscribe/Notify
- C. Request/Response
- D. Client/Server

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-584`）

</details>

**1.5.5-56.** Which of the following scenarios can lead to the discovery of a new Resource Type in an O-RAN network?

- A. A new software update is deployed.
- B. A query service is initiated.
- C. A new O-Cloud Resource Type is discovered during runtime.
- D. All of the above.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-600`）

</details>

頁次：[1](1-5-gsma-1.md)　[2](1-5-gsma-2.md)　[3](1-5-gsma-3.md)　**4**　[5](1-5-gsma-5.md)
