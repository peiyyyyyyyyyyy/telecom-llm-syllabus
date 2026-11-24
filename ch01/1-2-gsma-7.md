# 1.2 通訊協定　GSMA 練習題（1231 題）（第 7／7 頁）

所屬：[1.2 通訊協定](1-2.md)

只收 GSMA 訓練題；不含驗證集與測試集，並已去除和驗證／測試題相同或相似、重複、標註衝突的題目。題目依小節歸類（抽查正確率約 95%）。

頁次：[1](1-2-gsma-1.md)　[2](1-2-gsma-2.md)　[3](1-2-gsma-3.md)　[4](1-2-gsma-4.md)　[5](1-2-gsma-5.md)　[6](1-2-gsma-6.md)　**7**

## 1.2.10 網路介面：NG、Xn、F1、E1 與 N4（PFCP）（67 題）（續）

**1.2.10-37.** What type of information is transferred in the TL-Container? [3GPP Release 18]

- A. InterfaceConfiguration
- B. EndStationInterfaces
- C. Buffer capability
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1841`）

</details>

**1.2.10-38.** What is the purpose of the F1 interface in the O-RAN architecture?

- A. To connect the CU to the DUs
- B. To handle communications between the multi-RAT O-CU and the AMF and UPF of the 5G core network
- C. To connect the O-RU to the O-DU
- D. To enable control and optimization of the protocol stack functions of the RAN through the near-RT RIC
- E. To enable AI-related parameter exchange between the non-RT and near-RT RICs

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5179`）

</details>

**1.2.10-39.** What is considered a "successful with remarks" test result when analyzing F1 logs in an O-RAN environment?

- A. The Test UE or UE emulator receives all U-Plane data correctly.
- B. The "SCell Failed To Setup List" or "Criticality Diagnostics" IEs are observed in the "UE CONTEXT MODIFICATION RESPONSE".
- C. The F1 logs align with the NR C-Plane profile specification.
- D. Data transfer is ongoing after step 4 and step 9.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-109`）

</details>

**1.2.10-40.** Which of the following is NOT a function supported by the F1-C interface in an O-RAN network?

- A. User data transfer
- B. System Information management
- C. RRC message transfer
- D. Paging function

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-236`）

</details>

**1.2.10-41.** Which of the following is NOT a parameter included in the NeighborCell-Item-Choice-NR sequence?

- A. NR-CGI
- B. EUTRA-PCI
- C. NR-PCI
- D. NR-mode-info

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-345`）

</details>

**1.2.10-42.** In the context of O-RAN, what is the purpose of the "Final Frame Indication IE" with a value of '1' being sent from the gNB-DU to the gNB-CU?

- A. To indicate that the gNB-DU has successfully received all PDCP data from the UE.
- B. To signal that the gNB-DU has finished transmitting all PDCP data to the UE.
- C. To request the gNB-CU to initiate a handover procedure.
- D. To inform the gNB-CU that the gNB-DU has encountered an error during PDCP data transmission.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-347`）

</details>

**1.2.10-43.** What is the primary purpose of the NG-RAN node Configuration Update procedure?

- A. To transfer UE context data from a source MN to a target gNB.
- B. To enable transfer of NR RRC message container with NR measurements information.
- C. To update application level configuration data needed for NG-RAN nodes to interoperate correctly over the Xn-C interface.
- D. To manage the handover of a UE between different radio access technologies.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-381`）

</details>

**1.2.10-44.** Which of the following interfaces is used by the O-CU to communicate with the O-DU in the O-RAN architecture?

- A. F1
- B. F2
- C. F3
- D. F4

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-409`）

</details>

**1.2.10-45.** What is the primary purpose of the Reset procedure in the context of Open Radio Access Networks (O-RAN)?

- A. To verify the successful completion of the Xn Setup procedure between two gNBs from different vendors.
- B. To test the functionality of the S-NG-RAN NODE ADDITION procedure between two gNBs.
- C. To ensure the successful registration of multiple Test UEs or emulated UEs to the network.
- D. To verify the successful completion of the Reset procedure itself, ensuring that gNBs from different vendors can be reset and return to a functional state.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-506`）

</details>

**1.2.10-46.** What F1 log observation indicates a successful test with remarks, according to the provided context?

- A. The presence of "Criticality Diagnostics" in the "UE CONTEXT MODIFICATION RESPONSE" message.
- B. The absence of "Criticality Diagnostics" in the "UE CONTEXT MODIFICATION RESPONSE" message.
- C. The presence of "Criticality Diagnostics" in the "UE CONTEXT SETUP RESPONSE" message.
- D. The absence of "Criticality Diagnostics" in the "UE CONTEXT SETUP RESPONSE" message.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-533`）

</details>

**1.2.10-47.** What is the purpose of the "gnbCuUeF1apId" field within the "ueId" scope identifier?

- A. To identify a specific gNB-CU within a cell.
- B. To uniquely identify a UE within a gNB-CU.
- C. To distinguish between different slices within a gNB-CU.
- D. To indicate the QoS requirements of a specific UE.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-555`）

</details>

**1.2.10-48.** What is the primary objective of the Resource Status Reporting procedure in the context of Open Radio Access Networks (O-RAN)?

- A. To ensure successful completion of the traffic load procedures.
- B. To verify that the Xn logs recorded in the Protocol Analyzer are aligned with the NR C-Plane profile specification.
- C. To monitor and report the status of available resources within the O-RAN network.
- D. To analyze the message flows specified in the NR C-Plane profile specification.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-564`）

</details>

**1.2.10-49.** In an O-RAN network, what is considered a successful outcome for the UE Context Modification procedure?

- A. The procedure is completed, and the S-NG-RAN node initiates SN modification without MN involvement.
- B. Data transfer from the Application Test Server to the Test UE or UE emulator and vice versa is ongoing/possible.
- C. Both 1 and 2 are correct.
- D. The procedure is completed, and the Test UE or UE emulator is able to receive and transmit U-Plane data correctly.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-579`）

</details>

**1.2.10-50.** Which of the following is a method for updating the System Information Block (SIB) information generated by the gNB-CU in an O-RAN network?

- A. Stimulate cell activation using an O&M command in the gNB-CU.
- B. Perform a gNB-CU Configuration Update procedure.
- C. Stimulate cell deactivation using an O&M command in the gNB-CU.
- D. Perform a gNB-CU Configuration Update procedure to bar cells managed by the gNB-CU.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-630`）

</details>

**1.2.10-51.** Which of the following is considered a successful test result with remarks in the context of observing F1 logs in a Protocol Analyzer?

- A. The "Criticality Diagnostics" IE is observed in the "RESOURCE STATUS RESPONSE" message.
- B. The Resource Status Reporting Initiation procedure is successfully completed in all three steps.
- C. The F1 logs are not aligned with the message flows specified in the NR C-Plane profile specification.
- D. The cell addition for the measurement is not completed.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-638`）

</details>

**1.2.10-52.** What is the primary purpose of the Resource Status Reporting procedure in an O-RAN network?

- A. To verify the successful completion of the Xn Setup procedure between gNBs.
- B. To report the results of ongoing load measurements from one gNB to another.
- C. To initiate the Resource Status Reporting Initiation procedure.
- D. To observe and analyze Protocol Analyzer Xn logs.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-642`）

</details>

**1.2.10-53.** What is the primary purpose of the UE context creation procedure in an Open Radio Access Network (O-RAN)?

- A. To establish a data connection between the UE and the core network.
- B. To perform an initial registration of a UE in the network, creating a signaling-only connection.
- C. To configure the UE's radio parameters for optimal performance.
- D. To authenticate the UE and establish a secure connection.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-667`）

</details>

**1.2.10-54.** What is the primary objective of the ORAN.WG8.IOT.044 test case?

- A. Verify gNB-CU Configuration Update procedure when O-DU synchronization is not locked.
- B. Test the O-DU's ability to receive synchronization from an external timing source.
- C. Evaluate the performance of the O-DU under varying network conditions.
- D. Assess the security of the O-DU's communication with the SMO.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-725`）

</details>

**1.2.10-55.** What is the F1 interface in the context of O-RAN?

- A. The interface between the O-RU and the O-DU.
- B. The open interface between the O-CU and the O-DU.
- C. The interface between the O-DU and the UE.
- D. The interface between the O-CU and the O-RU.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-772`）

</details>

**1.2.10-56.** What does the abbreviation "DDDS" stand for in the context of Open Radio Access Networks (O-RAN)?

- A. Downlink Data Delivery Status
- B. Data Delivery Status
- C. Downlink Data Delivery System
- D. Data Delivery System

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-798`）

</details>

**1.2.10-57.** What is the purpose of the Partial Reset procedure in an Open Radio Access Network (O-RAN) environment?

- A. To verify that the gNB-CU initiated Partial Reset procedure with gNB-CU and gNB-DU from different vendors can be successfully completed.
- B. To test the performance of the gNB-CU and gNB-DU in handling large amounts of data traffic.
- C. To ensure that the gNB-CU and gNB-DU are properly synchronized with each other.
- D. To allow the gNB-CU to perform a software update on the gNB-DU.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-811`）

</details>

**1.2.10-58.** What is the expected behavior of the gNB-CU in the scenario described?

- A. The gNB-CU should transfer data frequently enough to prevent timer expiration.
- B. The gNB-CU should disconnect the UE after a certain inactivity period.
- C. The gNB-CU should align with the requirements outlined in Section 4.1.2.4 of the NR U-Plane profile.
- D. The gNB-CU should utilize a specific DRX inactivity timer value defined in 3GPP TS 36.331.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-874`）

</details>

**1.2.10-59.** In the context of O-RAN, what is the purpose of setting the Assistance Information Report polling Flag IE to '1' when sending Downlink User Data PDU(s) from MgNB-CU to MgNB-DU?

- A. To trigger the immediate transmission of Downlink User Data PDU(s) after the S-NG-RAN NODE ADDITION procedure.
- B. To request MgNB-DU to buffer Downlink User Data PDU(s) until a specific trigger is received.
- C. To enable MgNB-DU to prioritize the delivery of Downlink User Data PDU(s) based on user priority.
- D. To signal MgNB-DU to initiate a data transfer procedure with the Application Test Server.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-880`）

</details>

**1.2.10-60.** What is the maximum value allowed for the "gnbCuCpUeE1apId" field in the O-RAN specification?

- A. 255
- B. 65535
- C. 4294967295
- D. 18446744073709551615

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-902`）

</details>

**1.2.10-61.** What is the purpose of sending downlink user data PDUs with the Assistance Information Report polling flag set to '1' before the assistance information is available?

- A. To trigger the gNB-DU to report assistance information immediately.
- B. To create a scenario where the gNB-DU cannot report assistance information due to its unavailability.
- C. To test the gNB-DU's ability to handle large data transfers.
- D. To ensure that the gNB-DU buffers downlink data before reporting assistance information.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-951`）

</details>

**1.2.10-62.** Which of the following is NOT an expected log observation after the beginning of step 6 in the Report Polling test scenario?

- A. gNB-DU sends gNB-CU DDDS including Final Frame Indication IE with the value ‘1’
- B. gNB-DU continues to send gNB-CU DDDS including updated instances of Highest successfully delivered NR PDCP Sequence Number IE
- C. gNB-DU stops sending gNB-CU DDDS including any updated instances of Highest transmitted NR PDCP Sequence Number IE
- D. gNB-DU stops sending gNB-CU DDDS including any updated instances of Highest retransmitted NR PDCP Sequence Number IE

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-996`）

</details>

**1.2.10-63.** Which of the following components are involved in the Xn setup procedure?

- A. MgNB, SgNB, T-gNB
- B. gNB-CUs, gNB-DUs
- C. S-SN-CU, S-SN-DU
- D. Application Test Server, Test UE

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1078`）

</details>

**1.2.10-64.** What is the purpose of the "DL report NR PDCP PDU SN" IE in Open Radio Access Networks?

- A. To indicate the sequence number of the last NR PDCP PDU that has been successfully received.
- B. To trigger the corresponding node to send a Delivery Status Report (DDS) when a specific NR PDCP PDU has been successfully delivered.
- C. To request the corresponding node to retransmit a specific NR PDCP PDU that has been lost in transmission.
- D. To signal the beginning of a new NR PDCP PDU transmission.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1105`）

</details>

**1.2.10-65.** What is the purpose of setting the Assistance Information Report polling Flag IE to '1' in the Downlink User Data PDUs sent from the SgNB to the MgNB?

- A. To request the MgNB to perform handover to the SgNB.
- B. To trigger the S-NG-RAN NODE ADDITION procedure.
- C. To request the MgNB to send assistance information to the SgNB.
- D. To indicate the SgNB is ready to receive user data.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1112`）

</details>

**1.2.10-66.** Which of the following is NOT expected to be included in the Assistance Information Data message sent from gNB-DU to gNB-CU after step 1?

- A. Assistance Information Indication IE with a value of '0'
- B. Assistance Information Type IE
- C. Number of octets for Radio Quality Assistance Information Fields IE
- D. Radio Quality Assistance Information IE

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1162`）

</details>

**1.2.10-67.** What is the purpose of the DDDS message with Cause Value IE set to '2', '5', or '6' sent from the eNB to the en-gNB?

- A. To indicate a successful handover to the en-gNB.
- B. To confirm the completion of the Radio Link Outage operation.
- C. To request the en-gNB to initiate a new connection.
- D. To report a radio link failure to the en-gNB.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1175`）

</details>

頁次：[1](1-2-gsma-1.md)　[2](1-2-gsma-2.md)　[3](1-2-gsma-3.md)　[4](1-2-gsma-4.md)　[5](1-2-gsma-5.md)　[6](1-2-gsma-6.md)　**7**
