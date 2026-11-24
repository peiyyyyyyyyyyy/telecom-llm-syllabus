# 1.1 網路架構　GSMA 練習題（440 題）（第 3／3 頁）

所屬：[1.1 網路架構](1-1.md)

只收 GSMA 訓練題；不含驗證集與測試集，並已去除和驗證／測試題相同或相似、重複、標註衝突的題目。題目依小節歸類（抽查正確率約 95%）。

頁次：[1](1-1-gsma-1.md)　[2](1-1-gsma-2.md)　**3**

## 1.1.8 雙連接與 NSA／SA 部署選項（51 題）（續）

**1.1.8-34.** What is one method that can be used to stimulate the user plane downlink data forwarding function in an Open Radio Access Network (O-RAN)?

- A. Transferring user plane data at high enough data rates to cause the eNB to buffer data before a cell change.
- B. Initiating inter-RAT mobility.
- C. Stopping data transfer between the Application Test Server and the Test UE.
- D. Configuring the eNB with a specific set of RAN parameters.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-445`）

</details>

**1.1.8-35.** In the context of a bearer type change from an SN terminated MCG bearer to an SN terminated split bearer initiated by the MN, what parameter condition is applied?

- A. The MeNB shall restrict the SgNB's selection process for suitable SCG bands provided by the UE.
- B. The MeNB sorts Allowed BC (bandCombinationIndex, FeatureSetEntryIndex) in order of MeNB recommendation and transmits to SgNB.
- C. The UE must initiate a separate RRC connection with the SgNB.
- D. The MeNB and SgNB must share a common PCell band.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-447`）

</details>

**1.1.8-36.** Which of the following procedures is NOT directly involved in the successful completion of the Inter-Master Node Handover (with SN Change, Option 3x) procedure as described in the provided context?

- A. F1 UE Context Setup
- B. UE Context Modification
- C. UE Context Release
- D. Secondary Node Addition (Option 3x)

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-517`）

</details>

**1.1.8-37.** Which of the following is NOT a UE connectivity option mentioned in the context?

- A. SN terminated SCG bearer
- B. SN terminated split bearer
- C. SN terminated MCG bearer
- D. DN terminated SCG bearer

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-539`）

</details>

**1.1.8-38.** What are the two main operational modes supported for data transfer in Open Radio Access Networks (O-RAN)?

- A. Standalone (SA) and Non-Standalone (NSA)
- B. LTE and 5G
- C. TDD and FDD
- D. Single-Cell and Multi-Cell

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-573`）

</details>

**1.1.8-39.** Which of the following radio quality assistance information types can be configured to be reported by the MgNB in an AID message?

- A. Average CQI
- B. Average HARQ Failure
- C. Power Headroom Report
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-637`）

</details>

**1.1.8-40.** Which of the following procedures is NOT defined in the EN-DC procedures section of the provided context?

- A. Cell Resource Coordination
- B. User Equipment (UE) Location Update
- C. Master Node to eNB/gNB Change
- D. RRC Transfer

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-737`）

</details>

**1.1.8-41.** What is the primary objective of performing an M-NG-RAN node initiated SN modification with QoS flow release?

- A. To verify the user plane data transmission operates correctly after the modification.
- B. To test the stability of the network under high data rate conditions.
- C. To measure the latency of data transfer between the Application Test Server and the Test UE.
- D. To assess the impact of QoS flow release on the performance of the network.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-774`）

</details>

**1.1.8-42.** What is the primary purpose of the Secondary Node Change (SN initiated, Option 3x) test case described in the provided context?

- A. To verify the functionality of the F1 UE Context Setup, Modification, and Release procedures with en-gNB-CU and en-gNB-DU from different vendors.
- B. To test the performance of the X2 interface between en-gNBs.
- C. To assess the interoperability of different O-RAN components.
- D. To evaluate the stability of the network under high traffic loads.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-800`）

</details>

**1.1.8-43.** In the context of EN-DC X2 Setup, what is a potential use case for the NR neighbour information IE when sent from an eNB to an en-gNB?

- A. Facilitating inter-en-gNB mobility.
- B. Configuring the en-gNB's scheduling parameters.
- C. Enabling handover to a different NR cell.
- D. Monitoring the en-gNB's resource usage.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-836`）

</details>

**1.1.8-44.** What is a key expected result of the PSCell Change procedure using SRB1 for RRC Reconfiguration in an O-RAN environment?

- A. Successful transmission of UL RRC messages.
- B. Successful completion of UE Context Setup, Modification, and Release procedures over F1.
- C. Successful completion of the PSCell Change procedure, enabling ongoing data transfer between the Application Test Server and the Test UE/UE emulator.
- D. All of the above.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-900`）

</details>

**1.1.8-45.** Which of the following is NOT a minimum requirement for testing Inter-Master Node Handover with Secondary Node Change (Option 3x) in an O-RAN environment?

- A. Two eNBs (Source eNB and Target eNB)
- B. Two en-gNBs (Source gNB and Target gNB)
- C. A test UE or UE emulator capable of supporting both LTE and NR
- D. A network simulator capable of emulating the entire network infrastructure

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1000`）

</details>

**1.1.8-46.** Which of the following is NOT a minimum requirement for testing the general behavior of MgNB and SgNB from different vendors in an Open Radio Access Network (O-RAN) environment?

- A. Two gNBs (MgNB – MN, SgNB – SN)
- B. RLC-AM specified in NR U-Plane profile specification
- C. Overlapping coverage of MgNB and SgNB cells
- D. A network emulator capable of simulating a 5G core network

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1115`）

</details>

**1.1.8-47.** What is the primary purpose of the EN-DC X2 Setup procedure initiated by the en-gNB?

- A. To establish a secure SCTP association between the en-gNB and the eNB.
- B. To verify interoperability between en-gNB and eNB from different vendors in an EN-DC network.
- C. To configure the en-gNB's X2 interface for data transmission.
- D. To initiate the handover process from the en-gNB to the eNB.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1171`）

</details>

**1.1.8-48.** What is the primary purpose of the "Security Key Change procedure" (MN initiated) in the context of Open Radio Access Networks (O-RAN)?

- A. To establish an initial secure connection between the user equipment (UE) and the network.
- B. To update the encryption keys used for data transmission between the UE and the network.
- C. To authenticate the UE and ensure it is authorized to access the network.
- D. To change the radio resource allocation for the UE, potentially improving performance.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1177`）

</details>

**1.1.8-49.** What is the purpose of data split in DC (dual connectivity)?

- A. Decrease latency
- B. Increase reliability
- C. Improve throughput
- D. Reduce complexity

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2085`）

</details>

**1.1.8-50.** What is an example of multi-connectivity technique that enhances reliability in wireless networks?

- A. Proactive computing
- B. Task replication
- C. Federated machine learning
- D. Multi-frequency carrier aggregation
- E. Proximity-based computing

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5528`）

</details>

**1.1.8-51.** Simultaneous connectivity to multiple BSs (Base Stations) in 5G multi-tier networks would enhance _________.

- A. System throughput
- B. Outage ratio
- C. Both system throughput and outage ratio
- D. Interference mitigation
- E. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6128`）

</details>

## 1.1.9 網路與用戶識別碼：SUPI、GUTI、DNN、gNB／Cell ID（22 題）

**1.1.9-1.** What does NEF translate into a SUPI or Internal-Group-Id? [3GPP Release 18]

- A. UE location information
- B. GPSI or External-Group-Id
- C. Service Experience Contribution Weight
- D. Network Slice instance
- E. Area of Interest

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4094`）

</details>

**1.1.9-2.** What is RNTI?

- A. The service provided by the Layer 2 for transfer of user data between User Equipment and UTRAN.
- B. Functionality supporting the exchange of information, via the Core Network, between peer application entities located in a GERAN or in a UTRAN access network.
- C. A generic term for an identifier for a UE when a connection exists, such as C-RNTI, S-RNTI, U-RNTI, and G-RNTI.
- D. Two or more CN operators share the same RAN.
- E. Specific 2nd or 3rd generation radio access technology, such as UTRAN or GERAN.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5208`）

</details>

**1.1.9-3.** What is the meaning of EHPLMN?

- A. Evolved HPLMN
- B. Equivalent Home Power Limit
- C. Equivalent HPLMN List
- D. Equivalent Handover PLMN
- E. Equivalent Home PLMN

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6211`）

</details>

**1.1.9-4.** What is the role of a Cell Radio Network Temporary Identifier (C-RNTI)?

- A. To indicate the general characteristics of a mobile station
- B. To allocate UE identifiers unique within one cell controlled by the allocating CRNC
- C. To monitor system information and paging information
- D. To allow the transfer of information among service users without the need for end-to-end call establishment procedures
- E. To format and transfer information related to a chargeable event

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6659`）

</details>

**1.1.9-5.** Which identity is used to identify an AMF in NG-RAN? [3GPP Release 18]

- A. NSAG
- B. NID
- C. gNB ID
- D. MCCH-RNTI
- E. AMF Name

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7345`）

</details>

**1.1.9-6.** Which identity is used for identification of the Random Access Response in the downlink? [3GPP Release 17]

- A. CI-RNTI
- B. RA-RNTI
- C. Temporary C-RNTI
- D. Random value for contention resolution
- E. I-RNTI

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-642`）

</details>

**1.1.9-7.** What is the definition of a Registered PLMN (RPLMN)?

- A. A particular version of the 3GPP system standards produced by the 3GPP project
- B. A service entitlement to only certain geographical part(s) of a PLMN
- C. The network which receives the number in the porting process
- D. The PLMN on which the UE has performed a location registration successfully
- E. The process of camping on a cell of the PLMN and doing any necessary LRs

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1251`）

</details>

**1.1.9-8.** What is the definition of Selected PLMN?

- A. The PLMN selected by the S-RNTI
- B. The PLMN with the strongest signal strength
- C. The PLMN with the lowest service subscription cost
- D. The PLMN that has been selected by the non-access stratum
- E. The PLMN with the highest data transfer rate

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4707`）

</details>

**1.1.9-9.** What is a G-RNTI?

- A. The identifier of a mobile station (MS) allocated by the Gateway GPRS Support Node (GGSN)
- B. The identifier of a mobile station (MS) allocated by the Base Station Controller (BSC)
- C. The identifier of a radio network temporary identifier (RNTI) allocated by the Serving GPRS Support Node (SGSN)
- D. The identifier of a radio network temporary identifier (RNTI) allocated by the Base Station Controller (BSC)
- E. The identifier of a mobile station (MS) allocated by the Serving GPRS Support Node (SGSN)

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6613`）

</details>

**1.1.9-10.** What does the MME indicate to the UE in the GUTI? [3GPP Release 17]

- A. Anchor PLMN
- B. IMSI
- C. LAI/RAI
- D. Target CGI/RNC ID
- E. Selected PLMN

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7231`）

</details>

**1.1.9-11.** What does DNN stand for in the 5G System? [3GPP Release 18]

- A. Distinct Network Name
- B. Direct Network Node
- C. Default Network Node
- D. Dynamic Networking Node
- E. Data Network Name

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-3984`）

</details>

**1.1.9-12.** What is an End-User Identity (EUI)?

- A. An identity used for administration purposes of the operator
- B. An identity used for managing network elements
- C. An identity used for power saving features
- D. An identity used for billing purposes

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4073`）

</details>

**1.1.9-13.** What is the purpose of the Permanent Equipment Identifier (PEI)? [3GPP Release 18]

- A. To support user confidentiality protection
- B. To enable roaming scenarios
- C. To address a 3GPP subscription in different data networks
- D. To uniquely identify the UE within the AMF
- E. To identify the user equipment accessing the 5G System

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4088`）

</details>

**1.1.9-14.** Which identifier contains a Network Access Identifier (NAI) when a network-specific identifier is used? [3GPP Release 18]

- A. IMSI
- B. SUPI
- C. GCI
- D. PEI
- E. SUCI

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6669`）

</details>

**1.1.9-15.** What does the abbreviation IMSI stand for?

- A. Internet Mobile Service Identifier
- B. Integrated Mobile Subscriber Identity
- C. International Mobile Subscriber Identity
- D. Interactive Media Service Identifier

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6808`）

</details>

**1.1.9-16.** Which of the following identifies a specific gNB within an O-RAN network?

- A. MME-Group-ID
- B. EN-GNB-ID
- C. NGENB-CU-UE-W1AP-ID
- D. SubscriberProfileIDforRFP

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-3`）

</details>

**1.1.9-17.** Which of the following is a valid Mobile Country Code (MCC) according to the provided context?

- A. 1234
- B. 123
- C. 12
- D. 12345

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-62`）

</details>

**1.1.9-18.** Which of the following fields is NOT required for the "GuMmeI" object in the provided O-RAN context?

- A. plmnId
- B. mmeGroupId
- C. mmeCode
- D. amfSetId

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-572`）

</details>

**1.1.9-19.** What does GUAMI stand for?

- A. Globally Unique AMF Identifier
- B. Globally Unique MME Identifier
- C. Globally Unique Access Network Identifier
- D. Globally Unique Application Identifier

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-823`）

</details>

**1.1.9-20.** Which of the following is a temporary UE Identifier in a cell within a Radio Network?

- A. NR SSB-Index
- B. C-RNTI
- C. E2SM-COMMON-IEs
- D. maxE1APid

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1100`）

</details>

**1.1.9-21.** What is the HNB Name?

- A. The identifier for a cell with all its broadcasting indicators set to true
- B. The name of the PLMN where the Home NodeB/eNodeB is located
- C. The identifier for a hybrid cell accessible by UEs in a specific group
- D. The name of the service provider that collaborates with the Home Environment
- E. A human-readable name for the Home NodeB/eNodeB

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-264`）

</details>

**1.1.9-22.** What is the International Mobile Station Equipment Identity (IMEI)?

- A. A unique number allocated to each individual mobile station equipment in the PLMN
- B. A dialable number allocated to a 3GPP System user
- C. An application residing on the UICC for accessing IP Multimedia Services
- D. An IMS security data and functions for IMS access by a terminal
- E. An identifier for an Interconnecting unit in the 3G Core Network

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2106`）

</details>

頁次：[1](1-1-gsma-1.md)　[2](1-1-gsma-2.md)　**3**
