# 1.3 服務與多媒體　GSMA 練習題（523 題）（第 1／3 頁）

所屬：[1.3 服務與多媒體](1-3.md)

只收 GSMA 訓練題；不含驗證集與測試集，並已去除和驗證／測試題相同或相似、重複、標註衝突的題目。題目依小節歸類（抽查正確率約 95%）。

頁次：**1**　[2](1-3-gsma-2.md)　[3](1-3-gsma-3.md)

## 1.3.1 語音：電路交換、CSFB、VoLTE／VoNR（IMS）與 SRVCC（72 題）

**1.3.1-1.** What falls under the network functions of MPS? [3GPP Release 18]

- A. Service Invocation, Authorization, and End-to-End Priority Treatment
- B. Service Invocation, End-to-End Priority Treatment, and Network Interconnection
- C. Service Invocation, Authorization, End-to-End Priority Treatment, and Network Interconnection
- D. Authorization, End-to-End Priority Treatment, and Network Interconnection

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7370`）

</details>

**1.3.1-2.** What is the indication used to invoke the terminal application in the peer end of a multimedia call? [3GPP Release 18]

- A. H.243 information
- B. H.223 and H.245 information
- C. Call Control Capabilities information
- D. H.324 information

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-103`）

</details>

**1.3.1-3.** What is the role of the bearer control function? [3GPP Release 18]

- A. To provide interfaces for supplementary services
- B. To define the characteristics of bearers
- C. To assign and release bearers for a call
- D. To enable subscribers to control services
- E. To adapt bearers for fixed network use

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-106`）

</details>

**1.3.1-4.** What does the SIP Reason header extension work item do? [3GPP Release 14]

- A. Specifies procedures for interworking of eCall over IMS to CS domain
- B. Introduces password protection for activation of supplementary services in IMS
- C. Ensures consistency of all the possible extensions of the SIP Reason header field
- D. Provides media handling extensions for IMS-based telepresence

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-240`）

</details>

**1.3.1-5.** How can the network request the mobile station to change the UMTS codec during a speech call? [3GPP Release 18]

- A. By sending a MODIFY message to the mobile station
- B. By sending a SETUP message to the mobile station
- C. By sending a NOTIFY message to the mobile station
- D. By sending the new selected codec type in the NAS Synchronisation Indicator IE

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-513`）

</details>

**1.3.1-6.** What information does the MSC retrieve from another MSC/VLR or the UE? [3GPP Release 17]

- A. Core network operator
- B. PLMN-id
- C. TAI/RAI
- D. Anchor PLMN
- E. IMSI

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-3622`）

</details>

**1.3.1-7.** In network interconnection and protocol interworking, which cases require the use of MPS? [3GPP Release 18]

- A. Voice, video, and data services over EPS or 5GS
- B. Only voice services over EPS or 5GS
- C. Only data services over EPS or 5GS
- D. Data and video services over EPS or 5GS

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3843`）

</details>

**1.3.1-8.** What is handed over to the target RAT in handover with SRVCC operation? [3GPP Release 18]

- A. All bearers except the voice bearer
- B. All data bearers
- C. Control plane data
- D. User plane data
- E. Only voice bearer

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4075`）

</details>

**1.3.1-9.** What happens when a remote non-PLMN user initiates call rearrangements? [3GPP Release 18]

- A. The network sends a MODIFY message to the mobile station
- B. The network informs the mobile station by means of a NOTIFY message
- C. The network initiates an inter-system handover to UTRAN Iu mode
- D. The network releases the call

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4402`）

</details>

**1.3.1-10.** What happens when an MPS session request cannot be immediately processed in the originating network? [3GPP Release 18]

- A. The session request is dropped
- B. The session request is terminated
- C. The session request is queued
- D. The session request is ignored
- E. The session request is delayed

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4682`）

</details>

**1.3.1-11.** What protocol is IP multimedia session control based on? [3GPP Release 18]

- A. H.324M
- B. SIP
- C. MMS
- D. GTT

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6272`）

</details>

**1.3.1-12.** What happens if the network detects that the called end does not support the requested call mode in a multimedia call? [3GPP Release 18]

- A. The network initiates the in-call modification procedure to modify the call mode
- B. The network releases the call
- C. The network sends a NOTIFY message to the mobile station
- D. The network sends a CALL REJECT message to the mobile station

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7960`）

</details>

**1.3.1-13.** What is the purpose of the User Configuration mechanism in the IMS Multimedia Telephony service? [3GPP Release 17]

- A. To support synchronization of communication logs between multiple devices
- B. To indicate which identities are active or inactive on a specific UE
- C. To provide user preferences for media handling capabilities
- D. To modify the Caller Identity Analytics function

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-66`）

</details>

**1.3.1-14.** Can any party in a multiparty call undergo voice call continuity? [3GPP Release 18]

- A. Yes, any party in a multiparty call can undergo voice call continuity
- B. No, only the calling party can undergo voice call continuity
- C. No, only the called party can undergo voice call continuity
- D. No, voice call continuity is not supported for multiparty calls

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-128`）

</details>

**1.3.1-15.** Are the MuD and MiD services mutually exclusive? [3GPP Release 16]

- A. Yes, a user can only use either MuD or MiD service at a time
- B. No, they can both be used at the same time
- C. No, a user can switch between MuD and MiD services
- D. Yes, a user can only use MuD service on one type of UE and MiD service on another
- E. No, a user can only use either MuD or MiD service based on their subscription

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-272`）

</details>

**1.3.1-16.** What is associated with a time and/or date setting in the IMS Multimedia Telephony service? [3GPP Release 17]

- A. Media capabilities
- B. Caller identity verification results
- C. Activation, deactivation, and invocation of services
- D. Allow/block lists for service activation

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-359`）

</details>

**1.3.1-17.** What is the definition of a group in the context of group call service?

- A. A set of members allowed to participate in the group call service
- B. A collection of members who do not participate in data transfer
- C. A logical entity that provides the group call service
- D. A single data unit transmitted by a source participant

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-428`）

</details>

**1.3.1-18.** What does the Robust Call Setup for VoLTE subscriber in LTE Work Item aim to address? [3GPP Release 14]

- A. Improvement of LTE RSRP for VoLTE
- B. Enhancement of voice and video for LTE
- C. Provision of emergency call information
- D. Reduction of roaming charges for VoLTE
- E. Optimization of LTE data sessions for VoLTE

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-700`）

</details>

**1.3.1-19.** What is the purpose of Immediate Divert in IP-PBX? [3GPP Release 17]

- A. To divert a call to a messaging system
- B. To explicitly transfer an in-progress call to another device
- C. To allow a call to be resumed from a different device
- D. To provide Connected Name and Number Display
- E. All of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-704`）

</details>

**1.3.1-20.** What action does the network take if a QCI-1 bearer setup request for VoLTE is rejected during a terminating session? [3GPP Release 14]

- A. The call will be dropped
- B. The network will retry the call setup over CS domain
- C. The call will fallback to 2/3G in weak coverage areas
- D. The network will initiate a handover to a stronger LTE signal

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-928`）

</details>

**1.3.1-21.** What aspect does the CT Work Item "V8-CT" focus on? [3GPP Release 14]

- A. Emergency call in Local breakout roaming architecture
- B. Location determination at IMS entities in the HPLMN
- C. Local number translation in VPLMN for legacy CS and Local Breakout
- D. Fetching and providing necessary information for emergency call
- E. Charging principles for S8HR roaming architecture

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1071`）

</details>

**1.3.1-22.** What is the purpose of the Caller Identity Verification Results Delivery to the User? [3GPP Release 17]

- A. To provide information to the end user about potential risks associated with the caller identity
- B. To modify the caller identity information based on the originating network's policy
- C. To deliver the full or partial name string to the UE
- D. To support synchronization of communication logs between multiple devices

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1370`）

</details>

**1.3.1-23.** What is the meaning of IMS Multimedia Telephony?

- A. A service that allows multimedia conversational communications between two or more users
- B. A service that provides real-time bidirectional conversational transfer of media
- C. A service that includes Supplementary Services and takes account of regulatory requirements
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1446`）

</details>

**1.3.1-24.** Which supplementary service is unaffected by the user's ability to undergo voice call continuity? [3GPP Release 18]

- A. Call Forwarding
- B. Call Hold
- C. Call Waiting
- D. Multiparty

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1573`）

</details>

**1.3.1-25.** What does VoIP stand for in telecommunications?

- A. Voice over Internet Protocol
- B. Virtual Operator Information Portal
- C. Video over IP
- D. Voice of Interconnected Phones

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1763`）

</details>

**1.3.1-26.** What is the purpose of Real-Time Text conversation? [3GPP Release 18]

- A. To support multimedia services with IP telephony
- B. To support multimedia services with circuit-switched technology
- C. To enable real-time, character by character, text conversation
- D. To provide streaming services using packet-switched technology

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2277`）

</details>

**1.3.1-27.** What is the purpose of the Evolution to and Interworking with eCall in IMS work item? [3GPP Release 14]

- A. To introduce password protection for activation of supplementary services in IMS
- B. To specify eMBMS enhancements for LTE
- C. To provide media handling extensions for IMS-based telepresence
- D. To introduce the support of end-to-end eCall over IMS

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2410`）

</details>

**1.3.1-28.** What conditions must be met for voice call continuity during emergency calls? [3GPP Release 18]

- A. The source network is IMS, the user is moving out of coverage, and the target network belongs to the same operator
- B. The source network is IMS, the target network supports emergency calls, and the user is moving into coverage
- C. The source network is CS, the target network supports emergency calls, and the user is moving out of coverage
- D. The source network is CS, the target network supports emergency calls, and the user is moving into coverage

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2500`）

</details>

**1.3.1-29.** What services can modify the originating network's caller identity information? [3GPP Release 17]

- A. IMS Multimedia Telephony service
- B. OIP service and eCNAM service
- C. Additional timing information services
- D. User configuration services

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2598`）

</details>

**1.3.1-30.** What is the maximum acceptable latency for voice telephony in a Voice over IP (Internet Protocol) network?

- A. 5 seconds
- B. 250 milliseconds
- C. Seconds of buffering delay
- D. 4 seconds
- E. 9 seconds

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2715`）

</details>

**1.3.1-31.** Which enhancement is applicable to 'on-network' operation in MCPTT service? [3GPP Release 14]

- A. Ambient listening call
- B. Updating the selected MC service user profile
- C. KMS (Key Management Server) URI for security domain
- D. V2X communication over PC5 interface

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2873`）

</details>

**1.3.1-32.** What is Active communication?

- A. A defined set of procedures at an interface between a user and a network
- B. A small program that is intended not to be run on its own, but rather to be embedded inside another application
- C. A PLMN where the UE has found a cell that satisfies certain conditions
- D. The ratio of the average power centered on the assigned channel frequency to the average power centered on an adjacent channel frequency
- E. A UE is in active communication when it has a CS connection established or when it has one or more Activated PDP contexts

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2890`）

</details>

**1.3.1-33.** What does the term 'North American Emergency Services Routing Digits' refer to?

- A. A telephone number used to identify an emergency services provider
- B. A telephone number used to identify an emergency services client
- C. A telephone number used to identify a specific base station or cell site
- D. A telephone number used to identify a specific location in North America

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2932`）

</details>

**1.3.1-34.** What codec should be preferred over a narrowband codec during codec negotiation? [3GPP Release 17]

- A. Opus
- B. G.711
- C. AMR
- D. G.729

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2971`）

</details>

**1.3.1-35.** What is the definition of a cellular text telephone modem?

- A. To balance between the QoS requirements of new connections request and the current network utilization
- B. A modulation and coding method intended for transmission of text in voice channels
- C. An architectural term relating to the part of 3GPP System which is independent of the connection technology of the terminal
- D. The avoidance of disclosure of information without the permission of its owner
- E. A modulation and coding method intended for transmission of text in voice channels for real-time text conversation

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2989`）

</details>

**1.3.1-36.** What is the purpose of the enhancements in the feature VoIMS via Trusted and Untrusted WLAN access? [3GPP Release 15]

- A. To enable QoS differentiation and better user experience
- B. To extend the reach of ProSe Direct Discovery
- C. To enforce operator policy on the use of unlicensed spectrum
- D. To enhance LTE operation in unlicensed spectrum

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3089`）

</details>

**1.3.1-37.** What is the definition of originating network?

- A. The network where the called party is located
- B. The network where the calling party is located
- C. The network where the billing occurs
- D. The network where the data originates

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3120`）

</details>

**1.3.1-38.** What happens when a call undergoes voice call continuity and becomes barred in the target domain/system? [3GPP Release 18]

- A. The call continues in the target domain/system
- B. The call terminates
- C. Voice call continuity is not executed for the call
- D. The call is put on hold

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3166`）

</details>

**1.3.1-39.** What is the impact on line identification services during voice call continuity? [3GPP Release 18]

- A. The line identity of the calling party is not available during voice call continuity
- B. The line identity of the calling party remains unchanged during voice call continuity
- C. The line identity of the calling party is restricted during voice call continuity
- D. The line identity of the calling party is replaced with IMS information during voice call continuity

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3479`）

</details>

**1.3.1-40.** What happens if the QCI=1 bearer setup request for VoLTE is rejected due to weak LTE coverage in originating session? [3GPP Release 14]

- A. UE performs UL asynchronous HARQ transmission
- B. UE performs SRVCC
- C. UE performs HARQ
- D. UE performs MU-MIMO
- E. UE performs CSFB

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-3606`）

</details>

**1.3.1-41.** What session can be supported in real time for an Evolved ProSe Remote UE using Indirect 3GPP Communication? [3GPP Release 17]

- A. Non-real time data services
- B. Real-time video
- C. Small data services
- D. Multimedia telephony

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3628`）

</details>

**1.3.1-42.** What does the SDP attribute 'ccc_list' allow for? [3GPP Release 14]

- A. Communication and negotiation of concurrent codec capabilities
- B. Enforcement of priority levels
- C. Authentication of users
- D. Management of network resources

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3957`）

</details>

**1.3.1-43.** What are the key features for LTE to provide voice service over 2/3G CS domain? [3GPP Release 14]

- A. VoLTE/ViLTE signaling optimization
- B. UL asynchronous HARQ transmission
- C. RAN-assisted codec adaptation
- D. Bundle frequency hopping
- E. Robust Call Setup for VoLTE subscriber in LTE (RobVoLTE)

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4326`）

</details>

**1.3.1-44.** Which types of emergency calls are possible? [3GPP Release 18]

- A. Police
- B. Ambulance
- C. Fire Brigade
- D. Marine Guard
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4445`）

</details>

**1.3.1-45.** What should be supported for end-to-end codec negotiation? [3GPP Release 17]

- A. Compression
- B. Decoding
- C. Encoding
- D. Transcoding

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4458`）

</details>

**1.3.1-46.** What is the purpose of the Multi-device and Multi-Identity feature in the IMS Multimedia Telephony service? [3GPP Release 17]

- A. To allow users to use any public user identities for outgoing and incoming calls
- B. To support synchronization of communication logs between multiple devices
- C. To enable the addition and deletion of identities for outgoing communications
- D. To provide information about potential risks associated with the caller identity

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4557`）

</details>

**1.3.1-47.** What is the impact of voice call continuity on the quality of the voice service? [3GPP Release 18]

- A. Voice call continuity may adversely impact the voice service quality
- B. Voice call continuity improves the voice service quality
- C. Voice call continuity has no impact on the voice service quality
- D. Voice call continuity reduces the voice service quality

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4572`）

</details>

**1.3.1-48.** What is the purpose of SCC AS Restoration in IMS? [3GPP Release 14]

- A. To provide continuity of service for incoming session requests in IMS
- B. To ensure Single Radio Voice Call Continuity (SRVCC) in IMS
- C. To store extra SRVCC related information in the HSS
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4939`）

</details>

**1.3.1-49.** Which services apply to UEs using mobile 3GPP access for IMS Multimedia Telephony? [3GPP Release 17]

- A. Originating Identification Restriction (OIR)
- B. Communication Waiting (CW)
- C. Communication Barring (CB)
- D. Message Waiting Indication (MWI)
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4999`）

</details>

**1.3.1-50.** Which of the following numbering and addressing schemes are supported for IP multimedia sessions? [3GPP Release 18]

- A. MSISDN and SIP URL
- B. H.324M and GTT
- C. UDI/RDI and MMS
- D. 1kHz Ext. PLMN and CS multimedia calls

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5191`）

</details>

**1.3.1-51.** What is one of the requirements for differentiated paging in the Evolved Packet System? [3GPP Release 17]

- A. Support for efficient streaming services
- B. No loss of data during handovers between different access systems
- C. Support for network resource utilization based on context information
- D. Support for resilient multicast and broadcast services
- E. Support for a distinction between voice and non-voice over E-UTRAN traffic

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5595`）

</details>

**1.3.1-52.** What happens to a call on hold after voice call continuity has been performed? [3GPP Release 18]

- A. The call on hold is terminated
- B. The call on hold is re-established
- C. The call on hold is transferred to the IMS domain
- D. The call on hold is transferred to another party on the call

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5664`）

</details>

**1.3.1-53.** What is a group call initiator?

- A. A member (or third party) authorised to initiate a group call
- B. A logical entity that provides the group call service
- C. A member of a group participating in a particular group call
- D. The member responsible for the group creation and membership control
- E. An MS identifier allocated by the serving MSC

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5865`）

</details>

**1.3.1-54.** What are the three aspects that voice and video enhancements in RAN2 and RAN3 focus on? [3GPP Release 14]

- A. RAN-assisted codec adaptation, VoLTE/ViLTE signalling optimization, and voice/video coverage enhancement
- B. UL/DL bitrate recommendation, PUSCH enhancement mode, and multi-subframe channel estimation
- C. RobVoLTE, QCI-1 bearer setup, and handover thresholds
- D. LTE radio signal improvement, CS fallback, and UE-1MSC communication

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5905`）

</details>

**1.3.1-55.** What is the purpose of the Media Handling Extensions of IMS-based Telepresence work item? [3GPP Release 14]

- A. To introduce password protection for activation of supplementary services in IMS
- B. To specify eMBMS enhancements for LTE
- C. To provide media handling extensions for IMS-based telepresence
- D. To introduce the support of end-to-end eCall over IMS

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5947`）

</details>

**1.3.1-56.** What is the definition of MSD?

- A. A UE, which acts as a gateway providing access to and from the 3GPP network for one or more non-3GPP devices that are connected to the gateway UE
- B. A TV service which is characterised by requiring a subscription (to content owner, content provider, or MNO) in order to access the service
- C. Data traffic of which the user is aware he/she initiated, e.g. based on the screen/keypad lock being deactivated, length of time since the UE last received any input from the user, known type of application
- D. The Minimum Set of Data forming the data component of an eCall sent from a vehicle to a Public Safety Answering Point or other designated emergency call centre
- E. An ME with multiple USIMs

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6170`）

</details>

**1.3.1-57.** What does the AULC feature improve? [3GPP Release 14]

- A. User location calculation
- B. Core network overload
- C. User location change awareness
- D. Emergency call handling

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6246`）

</details>

**1.3.1-58.** What does the abbreviation IMS stand for?

- A. Interactive Media System
- B. Integrated Messaging Service
- C. International Mobile System
- D. Internet Multimedia Subsystem

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6318`）

</details>

**1.3.1-59.** What media capabilities are included in the IMS Multimedia Telephony service? [3GPP Release 17]

- A. Full duplex speech, real-time video, and fax
- B. Real-time text communication, file transfer, and data (CS)
- C. Video clip sharing, picture sharing, and audio clip sharing
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6498`）

</details>

**1.3.1-60.** What is the default media handling capability of the IMS Multimedia Telephony service? [3GPP Release 17]

- A. Adding and removing individual media components in a communication
- B. Supporting synchronized video and speech in real time
- C. Full duplex speech and real-time text communication
- D. Allowing users to add and delete identities for outgoing communications

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6724`）

</details>

**1.3.1-61.** Which access control mechanism specifically applies to CSFB? [3GPP Release 18]

- A. Access Class Barring
- B. Service Specific Access Control
- C. Extended Access Barring
- D. Application Specific Congestion Control for Data Communication
- E. Access Control for Indirect 3GPP Communications

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6766`）

</details>

**1.3.1-62.** What is the characteristic of handover with SRVCC operation? [3GPP Release 17]

- A. Only data forwarding of voice bearer is supported
- B. In-sequence and lossless handover is supported
- C. The target NR node decides to handover the UE with ongoing IMS voice from NR to UTRAN
- D. Handover to UTRA-FDD and UTRA-TDD are both supported
- E. The source eNB initiates the handover preparation for all active bearers

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7130`）

</details>

**1.3.1-63.** What is the purpose of the eVoLTE CE technologies? [3GPP Release 14]

- A. Support UL asynchronous HARQ transmission
- B. Achieve voice and video enhancement for LTE
- C. Provide voice service over 2/3G CS domain
- D. Enable multi-subframe channel estimation
- E. Reuse existing CE technologies in eMTC CE mode A

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7176`）

</details>

**1.3.1-64.** What is the purpose of CS fallback in the Evolved Packet System? [3GPP Release 17]

- A. To optimize routing for user plane traffic
- B. To support mobility within and across access systems
- C. To minimize packet loss during inter- and/or intra-access technology changes
- D. To provide continuous service during and following changes of access systems
- E. To enable the delivery of CS services over UTRAN or GERAN in the CS domain

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7448`）

</details>

**1.3.1-65.** How are voice calls delivered to a dual/multi mode terminal in a hybrid network? [3GPP Release 18]

- A. Based on the radio access systems available
- B. Based on network conditions from the serving network
- C. Based on roaming agreements between operators
- D. Based on the CS CN domain
- E. Based on preferences of service delivery within the user profile

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7560`）

</details>

**1.3.1-66.** What is the purpose of interworking between the IMS domain and the CS domain? [3GPP Release 17]

- A. To provide multimedia telephony communications
- B. To improve network security
- C. To optimize network efficiency
- D. To enhance user experience

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7690`）

</details>

**1.3.1-67.** What factors can be considered when activating VCC in the 3GPP system? [3GPP Release 18]

- A. Radio conditions and coverage availability
- B. Terminal capabilities and roaming conditions
- C. Data usage and network congestion
- D. Security mechanisms and emergency situations

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7962`）

</details>

**1.3.1-68.** What is the purpose of the Recovery/Restoration functionality in the MPS system? [3GPP Release 18]

- A. To expedite service recovery and restoration after a disruption
- B. To provide priority treatment for supplementary services
- C. To enforce policy control for MPS application services
- D. To prioritize handover of MPS voice calls to CS
- E. To support MPS when roaming outside the home country

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5313`）

</details>

**1.3.1-69.** What is the process of verifying if a Service User is authorized for MPS called? [3GPP Release 18]

- A. End-to-End Priority Treatment
- B. Service Invocation
- C. Network Interconnection
- D. Authorization

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6250`）

</details>

**1.3.1-70.** Which of the following messages triggers the increment of the 'OR.MOBILITY.CompEpsFallback' counter?

- A. NG-AP: PDU Session Resource Modify Request (EPS Fallback)
- B. NG-AP: UE Context Release Command (EPS Fallback)
- C. NG-AP: Handover Request (EPS Fallback)
- D. NG-AP: PDU Session Release Command (EPS Fallback)

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-930`）

</details>

**1.3.1-71.** What mobility is supported in handover with SRVCC operation? [3GPP Release 18]

- A. Inter RAT mobility
- B. NR-E-UTRA mobility
- C. NR-UTRA mobility
- D. Intra 5GC mobility
- E. Handover from 5GC to EPC

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3767`）

</details>

**1.3.1-72.** What is the purpose of the Coverage and Handoff Enhancements for Multimedia (CHEM) feature? [3GPP Release 16]

- A. To enable the network to delay or reduce handoffs of a Multimedia Telephony Service for IMS terminal by providing additional information about packet losses
- B. To enable the network to prioritize handoffs of a Multimedia Telephony Service for IMS terminal by providing additional information about packet losses
- C. To enable the network to avoid handoffs of a Multimedia Telephony Service for IMS terminal by providing additional information about packet losses
- D. To enable the network to switch handoffs of a Multimedia Telephony Service for IMS terminal by providing additional information about packet losses
- E. To enable the network to identify handoffs of a Multimedia Telephony Service for IMS terminal by providing additional information about packet losses

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6022`）

</details>

## 1.3.2 簡訊與訊息服務（11 題）

**1.3.2-1.** Which interface is used to transfer short messages between the SGSN and SMS-GMSC/SMS-IWMSC? [3GPP Release 17]

- A. Gn/Gp-interface
- B. Gr-interface
- C. Gs-interface
- D. Gb-interface
- E. Gd-interface

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-147`）

</details>

**1.3.2-2.** What services enable the 5GS to interact with the Messaging Framework? [3GPP Release 18]

- A. Nmfaf_3caDataManagement Service
- B. Nmfaf_3daDataManagement Service
- C. Ndccf_DataManagement Service
- D. Nnwdaf_DataManagement Service
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5251`）

</details>

**1.3.2-3.** Which reference point is used for SMS transfer between UE and AMF via NAS? [3GPP Release 18]

- A. N1
- B. N8
- C. N19
- D. N20
- E. N21

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7211`）

</details>

**1.3.2-4.** What triggers the AF to request the network to send an Application trigger to the UE? [3GPP Release 18]

- A. The NEF invokes the Nnef_Trigger_Delivery request service.
- B. The AF determines the need to trigger the device.
- C. The NEF checks that the AF is authorized to send trigger requests.
- D. The NEF invokes Nudm_SDM_Get (Identifier Translation, GPSI and AF Identifier).
- E. The UDM may invoke the Nudr_DM_Query service to retrieve a list of AF's that are allowed to trigger the UE.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7579`）

</details>

**1.3.2-5.** Which protocol is used for Short message Distribution Service (SDS) in MCData? [3GPP Release 14]

- A. HTTP
- B. FTP
- C. SMTP
- D. Signaling channel or media bearer

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7740`）

</details>

**1.3.2-6.** What is the purpose of the ePWS feature? [3GPP Release 16]

- A. To enhance the Public Warning System by improving the comprehension of Warning Notifications for users with disabilities and non-fluent users
- B. To define behaviours for UEs with no user interface
- C. To specify additional requirements for PWS-UEs
- D. To enable language-independent content in Warning Notifications
- E. To specify how graphical symbols or images can be used in Warning Notifications

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-568`）

</details>

**1.3.2-7.** What are the categories of users that the ePWS feature aims to better disseminate Warning Notifications to? [3GPP Release 16]

- A. Users with disabilities who use text assistive technologies
- B. Users with disabilities who use assistive technologies beyond text assistive technologies
- C. Users who are fluent in the language of the Warning Notifications
- D. Users with no user interface on their UEs
- E. Users who have UEs with user interfaces incapable of displaying text-based Warning Notifications

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-858`）

</details>

**1.3.2-8.** What does the abbreviation SMS stand for?

- A. Service Measurement System
- B. Subscriber Management System
- C. Short Message Service
- D. Session Management Server

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-876`）

</details>

**1.3.2-9.** What is a teleaction service?

- A. A telecommunication service that uses short messages requiring a low transmission rate
- B. A service offered by a PLMN operator or service provider to satisfy a specific telecommunication requirement
- C. A type of telecommunication service that provides complete capability for communication between users according to standardised protocols
- D. A type of telecommunication service that uses text conversation between users in at least two locations

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2245`）

</details>

**1.3.2-10.** What basic requirements are supported for MMS? [3GPP Release 18]

- A. Real-time character by character text conversation
- B. Store-and-forward multimedia messaging service
- C. Automatic device detection
- D. IP multimedia session control

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3072`）

</details>

**1.3.2-11.** What is the definition of a CBS DRX cycle?

- A. The combined losses of all transmission system components
- B. A piece of information indicating general 3GPP System mobile station characteristics
- C. The time interval between successive readings of CBS messages
- D. The UE is in idle mode and has chosen a cell
- E. A modulation and coding method intended for the transmission of text in voice channels

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6497`）

</details>

## 1.3.3 數據服務與 QoS（106 題）

**1.3.3-1.** What does redundant transmission at the transport layer in URLLC require? [3GPP Release 18]

- A. Support for IEEE FRER protocol in the application layer.
- B. Redundant GTP-U tunnel over N3 between UPF and NG-RAN.
- C. Two disjoint transport paths between UPF and NG-RAN.
- D. Synchronization between NG-RAN and PSA UPF.
- E. Specific 3GPP protocol impact.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4144`）

</details>

**1.3.3-2.** When does the PCF include the Duplicated notification indication in the PCC rule? [3GPP Release 18]

- A. When the AF initiates an AF session
- B. When the PCF makes the policy decision
- C. When the L-PSA UPF detects a QoS monitoring event
- D. When the AF revokes the AF session

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5413`）

</details>

**1.3.3-3.** What does the NEF (PFDF) distribute to the SMF(s) in the Nnef_PFD_Management_Notify message? [3GPP Release 18]

- A. Application Identifier
- B. PFDs
- C. PFDs operation
- D. PFD notifications

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-8000`）

</details>

**1.3.3-4.** What does QCI-1 represent in LTE? [3GPP Release 14]

- A. Best effort
- B. Real-time interactive
- C. Streaming
- D. Background
- E. Signaling

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-544`）

</details>

**1.3.3-5.** What is the purpose of the QoS profile in NG-RAN? [3GPP Release 18]

- A. To establish PDU sessions
- B. To determine radio interface treatment
- C. To identify QoS flows
- D. To map packets to DRBs

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-797`）

</details>

**1.3.3-6.** What should URSP rules based on AF guidance not be set as? [3GPP Release 18]

- A. Match all traffic descriptor
- B. URSP rules with low priority
- C. URSP rules without traffic descriptor
- D. URSP rules for specific locations

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-814`）

</details>

**1.3.3-7.** What is the purpose of load-balancing steering mode enhancements? [3GPP Release 17]

- A. To provide better network performance measurements
- B. To prioritize non-3GPP access over 3GPP access in load balancing
- C. To enable the UE and UPF to freely select split percentages for each access type
- D. To enhance the functionality of the AMF

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-937`）

</details>

**1.3.3-8.** What aspect of the URSP rule does the Application Traffic Descriptor from the AF guidance affect? [3GPP Release 18]

- A. Route Selection Descriptor Precedence
- B. URSP Traffic Descriptor
- C. DNN selection component
- D. Location Criteria

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1162`）

</details>

**1.3.3-9.** What is negotiated QoS?

- A. A label used for identification of end users
- B. In response to a QoS request, the network shall negotiate each QoS attribute
- C. A discrete telecommunications entity which can be managed over a specific interface
- D. A unit of data passed between the user and the GPRS network across a Network Service Access Point
- E. An association established by a network layer between two users

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1203`）

</details>

**1.3.3-10.** What is the definition of an IP-CAN bearer?

- A. A logical interface between two RNCs in the same network.
- B. A logical interface between two RNCs in different networks.
- C. The data communications bearer provided by the IP-Connectivity Access Network.
- D. The collection of network entities and interfaces that provides the underlying IP transport connectivity between the UE and the IMS entities.
- E. The interface between a UE and the IMS entities.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1210`）

</details>

**1.3.3-11.** What does the UE do when 3GPP PS Data Off is activated? [3GPP Release 18]

- A. Informs the network that 3GPP PS Data Off is activated
- B. Ceases the sending of uplink IP Packets of all services
- C. Ceases the sending of uplink traffic over non-IP PDN types
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1827`）

</details>

**1.3.3-12.** What is Non-Seamless WLAN offload (NSWO) in the context of 5GS? [3GPP Release 17]

- A. A network function that supports authentication for NSWO
- B. A capability of a UE to route specific IP flows via WLAN access
- C. A service-based interface for NSWO authentication
- D. A configuration for NSWO roaming

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1865`）

</details>

**1.3.3-13.** What is an E-RAB?

- A. An entity associated with one or multiple subscriptions in a network
- B. A file containing access conditions and data on the UICC
- C. A power saving feature where paging cycles can range from seconds to several hours
- D. An identifier for the concatenation of an S1 Bearer and the corresponding Data Radio Bearer

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1872`）

</details>

**1.3.3-14.** What controls the additional behavior of the SMF for 3GPP PS Data Off? [3GPP Release 18]

- A. Local configuration from the PCF.
- B. The list(s) of 3GPP Data Off Exempt Services provisioned in the UE.
- C. The ATSSS feature.
- D. The IMS domain policy.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2566`）

</details>

**1.3.3-15.** What does SIPTO@LN stand for? [3GPP Release 17]

- A. Signaling Transport Protocol Over Local Network
- B. Secure Internet Protocol Tunneling Over Local Network
- C. Session Initiation Protocol Transfer Option for Local Network
- D. Service Implementation for Public Telephony Over Local Network
- E. System Integration for Private Telecommunications Operators

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3119`）

</details>

**1.3.3-16.** What is the purpose of the UE-assistance indication in load-balancing steering mode? [3GPP Release 17]

- A. To allow the UE to decide on split percentages based on its internal state
- B. To dictate fixed split percentages for load balancing
- C. To optimize network performance measurements
- D. To provide guidelines to the UPF on load balancing

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3761`）

</details>

**1.3.3-17.** Which type of PRAs information is provisioned by the PCRF/OCS to the MME each time the IP-CAN session is established? [3GPP Release 14]

- A. UE dedicated PRA
- B. Predefined PRA
- C. PRA set

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4218`）

</details>

**1.3.3-18.** When is priority treatment applied in MPS? [3GPP Release 18]

- A. Only after the MPS session is released
- B. During the invocation and session establishment and until the MPS session is released
- C. Before the invocation
- D. Only during the invocation

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4467`）

</details>

**1.3.3-19.** What does E-RAB stand for?

- A. End-User Radio Access Bearer
- B. Elementary Radio Access Bearer
- C. Equivalent Radio Access Bearer
- D. E-UTRAN Radio Access Bearer
- E. Evolved Radio Access Bearer

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5286`）

</details>

**1.3.3-20.** What is the meaning of IP Flow Mobility?

- A. The distribution of IP flows on a UE between 3GPP and WLAN available accesses
- B. The flow of IP packets between two network entities
- C. The mobility of IP addresses between different networks
- D. The mobility of IP packets between different radio systems

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5599`）

</details>

**1.3.3-21.** In Rel-17, how are load-balancing split percentages determined? [3GPP Release 17]

- A. They are fixed and pre-defined by the network
- B. They are based on the network's strong steering requirements
- C. They are determined by the UE and UPF using RTT measurements
- D. They are always 50% on 3GPP access and 50% on non-3GPP access

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5737`）

</details>

**1.3.3-22.** How is the packet delay measured for a QoS Flow in URLLC? [3GPP Release 18]

- A. By performing end-to-end UL/DL packet delay measurement between UE and PSA UPF.
- B. By estimating the RAN part of UL/DL packet delay based on QoS Monitoring request from SMF.
- C. By performing GTP-U Echo Request/Response for the corresponding transport path.
- D. By activating QoS monitoring for GTP-U path between UPF and (R)AN.
- E. By mapping QoS Flows to appropriate network instances based on QoS monitoring results.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5962`）

</details>

**1.3.3-23.** What is the purpose of Explicit Congestion Notification (ECN) in 5G? [3GPP Release 18]

- A. To identify GBR and non-GBR flows
- B. To allocate and retain resources for QoS flows
- C. To support reliable and low-delay data transfer
- D. To enable congestion control in the network

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6951`）

</details>

**1.3.3-24.** What is the purpose of access performance measurements per QoS flow in ATSS? [3GPP Release 17]

- A. To optimize network performance measurements
- B. To estimate the RTT and/or Packet Loss Rate over each access of an MA PDU Session
- C. To prioritize non-3GPP access over 3GPP access in load balancing
- D. To establish a Multi Access (MA) PDU Session

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7201`）

</details>

**1.3.3-25.** What is the purpose of the Direct event notification method in the PCC rule? [3GPP Release 18]

- A. To indicate that the AF should subscribe to QoS monitoring notifications
- B. To provide the QoS monitoring parameters to the SMF
- C. To indicate that both direct and PCF/SMF notifications are required
- D. To activate N4 reporting for QoS monitoring results

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7296`）

</details>

**1.3.3-26.** What is the purpose of RSVP in networking?

- A. Resource Sharing and Virtualization Platform
- B. Real-time Streaming Protocol
- C. Reliability and Stability Verification
- D. Routing and Switching of Voice and Data
- E. Resource Reservation Protocol

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-8036`）

</details>

**1.3.3-27.** What are the main services provided by fifth-generation (5G) networks?

- A. Enhanced massive broadband
- B. Ultra-reliable and low-latency (URLL) communications
- C. Massive machine type communications
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-40`）

</details>

**1.3.3-28.** What does the Load-Balancing steering mode do? [3GPP Release 17]

- A. Splits the traffic of a data flow across 3GPP and non-3GPP accesses
- B. Balances the load on the core network nodes
- C. Restricts the UE to a single access type
- D. Improves network performance measurements

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-141`）

</details>

**1.3.3-29.** What are the high quality-of-service (QoS) requirements for the supported applications?

- A. Extremely high data rates
- B. Ultra-high reliability
- C. Ultra-low latency
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-300`）

</details>

**1.3.3-30.** What QoS characteristics does the MPS system support? [3GPP Release 18]

- A. Specific QoS characteristics for MPS Voice, Video, and Data
- B. Equal QoS characteristics for all MPS sessions
- C. No QoS characteristics for MPS sessions
- D. Priority QoS characteristics for MPS sessions
- E. Higher QoS characteristics for MPS Voice than Video or Data

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-342`）

</details>

**1.3.3-31.** What types of services can be included in a subscription? [3GPP Release 18]

- A. Basic Services, PS services, and IM-Services
- B. Teleservices, Bearer services, and Value added services
- C. PS CN service profile and QoS parameter ranges
- D. Network operator services and value added services
- E. Access services and radio access systems

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-465`）

</details>

**1.3.3-32.** Which of the following is not a reason for the introduction of survival time as a quality of service requirement?

- A. To ensure the control application does not fail
- B. To trigger more cautious transmission in survival mode
- C. To reduce the chance of a burst of consecutive errors
- D. To increase the end-to-end latency
- E. To discriminate between normal mode and survival mode of operation

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-761`）

</details>

**1.3.3-33.** What is the requirement for network traffic patterns in service capabilities? [3GPP Release 18]

- A. To consider the overheads and signalling surge caused by frequent transmissions of large amounts of data
- B. To consider the discontinuous and symmetric nature of most teleservices and user applications
- C. To consider the discontinuous and asymmetric nature of most teleservices, multimedia services, and user applications
- D. To consider the continuous and symmetric nature of most teleservices and user applications

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-879`）

</details>

**1.3.3-34.** What is predictive service?

- A. A service type in which data is sent to all service subscribers or a pre-defined subset of all subscribers within an area
- B. A unit of data specified in an (N)-protocol layer
- C. A service model which provides reliable performance, but allowing a specified variance in the measured performance criteria
- D. A value of the service attribute communication configuration denoting a communication involving only two network terminations
- E. The act of seeking a User Equipment

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1216`）

</details>

**1.3.3-35.** What is a multi-modal communication service? [3GPP Release 17]

- A. Service that supports communication between different MNOs
- B. Service that enables communication between different devices and networks
- C. Service that allows input and output from multiple sources and destinations
- D. Service that provides communication through multiple communication modes
- E. Service that supports communication with multiple users simultaneously

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1232`）

</details>

**1.3.3-36.** What is best effort QoS?

- A. The lowest of all QoS traffic classes
- B. A service model which provides minimal performance guarantees
- C. A transmission function requested by the UE to the network
- D. The capabilities to allocate, release, and manage specific radio resources
- E. A value denoting unidirectional distribution to all users

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1364`）

</details>

**1.3.3-37.** What aspects are combined to determine Quality of Service?

- A. Service operability performance
- B. Service accessibility performance
- C. Service retainability performance
- D. Service integrity performance
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1533`）

</details>

**1.3.3-38.** Which new services drive the need for very low latency and high service availability in 5G? [3GPP Release 15]

- A. Enhanced Mobile Broadband (eMBB)
- B. Massive Internet of Things (mIoT)
- C. Critical Communications (CC)
- D. Flexible network operations
- E. Efficient content delivery

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1637`）

</details>

**1.3.3-39.** How can high reliability be achieved in URLLC (Ultra-Reliable Low-Latency Communication)?

- A. By increasing the bandwidth and obtaining more available channel uses
- B. By decreasing the channel use time duration or increasing the number of channel uses in frequency
- C. By using different types of diversity such as access point diversity, spatial diversity, and interface diversity
- D. By considering the statistics of rare events occurring within the packet duration
- E. By optimizing the coding and transmission of metadata

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1707`）

</details>

**1.3.3-40.** How does the UE report its 3GPP PS Data Off status? [3GPP Release 18]

- A. Through the PDU Session Establishment procedure.
- B. Through the inter-RAT mobility to NG-RAN.
- C. Through the inter-LADN mobility.
- D. Through the ATSSS feature.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1737`）

</details>

**1.3.3-41.** What is prioritization of URLLC (Ultra-Reliable Low Latency Communication) traffic?

- A. Using multi-antenna communication
- B. Increasing the number of connections
- C. Giving more resources to URLLC services compared to other types of services
- D. Increasing the number of base stations

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1742`）

</details>

**1.3.3-42.** What is the purpose of the Policy and Charging Rules Function (PCRF)?

- A. To control or monitor charges related to service usage
- B. To perform credit reservation and deduction
- C. To enforce policy and manage charging rules
- D. To handle offline charging information

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1937`）

</details>

**1.3.3-43.** What is a bearer service?

- A. A network element responsible for radio transmission and reception in one or more cells
- B. A type of telecommunication service that provides transmission of signals between access points
- C. The time during which the base station is receiving data subframes or UpPTS
- D. A transmission function requested by the UE to the network
- E. A value denoting unidirectional distribution to all users

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2242`）

</details>

**1.3.3-44.** Who is considered a Service User in the context of MPS?

- A. An individual authorized to use MPS and who has been granted a user priority level assignment by a regional/national authority
- B. An individual utilizing multimedia telephony services
- C. An individual utilizing virtual private networks
- D. An individual utilizing over-the-top services
- E. An individual with a personal identification number

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2306`）

</details>

**1.3.3-45.** What is the purpose of the Access Traffic Steering, Switching and Splitting (ATSS) feature in 5G networks? [3GPP Release 17]

- A. To establish a Multi Access (MA) PDU Session for data communication between the UE and UPF
- B. To improve network performance measurements in Rel-16
- C. To support 3GPP access over EPC only
- D. To prioritize 3GPP access over non-3GPP access in load balancing

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2381`）

</details>

**1.3.3-46.** What is the purpose of the QFI in the downlink? [3GPP Release 18]

- A. To indicate QoS flow mapping in RQoS
- B. To differentiate GBR and non-GBR flows
- C. To establish PDU sessions
- D. To determine radio interface treatment

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2441`）

</details>

**1.3.3-47.** What is a teleservice?

- A. A telecommunication service that uses short messages requiring a low transmission rate
- B. A type of telecommunication service that provides complete capability for communication between users according to standardised protocols
- C. A service offered by a PLMN operator or service provider to satisfy a specific telecommunication requirement
- D. A type of telecommunication service that uses text conversation between users in at least two locations

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2621`）

</details>

**1.3.3-48.** What is Variable bit rate service?

- A. A service that offers virtual home environment portability across network boundaries and between terminals.
- B. A service that simulates a hypothetical computer central processing unit.
- C. A type of telecommunication service with a fixed bit rate.
- D. A service that offers virtual machine services.
- E. A type of telecommunication service with a bit rate that can vary within defined limits.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-3047`）

</details>

**1.3.3-49.** What are the fundamental characteristics for QoS in the Streaming class? [3GPP Release 17]

- A. Preserve time relation
- B. Stringent and low delay
- C. Low bit error rate
- D. Transparent payload transfer

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3130`）

</details>

**1.3.3-50.** What is a QoS session?

- A. A network connection with defined characteristics
- B. A performance expectation placed on the bearer network
- C. A collective effect of service performances
- D. A period between the opening and closing of a network connection
- E. A number of QoS parameters

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3357`）

</details>

**1.3.3-51.** What is the purpose of the MPS system? [3GPP Release 18]

- A. To provide preferential treatment based on the subscription for MPS
- B. To enable access and core network resources for MPS sessions
- C. To assign priority levels to Service Users
- D. To support Priority Data Bearer Service
- E. To provide MPS for roaming Service Users

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3431`）

</details>

**1.3.3-52.** What is the purpose of the Policy Control functionality in the MPS system? [3GPP Release 18]

- A. To assign priority levels to Service Users
- B. To handle MPS interactions with supplementary services
- C. To retain MPS invoked during transient network degradation
- D. To make and enforce policy decisions for MPS application services
- E. To support MPS during and after handover

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3471`）

</details>

**1.3.3-53.** What is the definition of a basic telecommunication service?

- A. A common reference to both bearer services and teleservices
- B. A network element responsible for radio transmission and reception
- C. A transmission function requested by the UE to the network
- D. An information transmission path of defined capacity, delay, and bit error rate
- E. Code generated by a Java compiler and executed by the Java interpreter

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3486`）

</details>

**1.3.3-54.** What does priority treatment refer to?

- A. Mechanisms and features that prioritize multimedia telephony services
- B. Mechanisms and features for seamless WLAN offload
- C. Mechanisms and features that increase the success rate for MPS session invocation, establishment, and maintenance until release
- D. Mechanisms and features for personal identification number authentication
- E. Mechanisms and features that enable virtual private network connections

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3549`）

</details>

**1.3.3-55.** What are the two challenging requirements for URLLC (Ultra reliable and low latency communications)?

- A. Low latency and high reliability
- B. Low latency and high throughput
- C. High reliability and high throughput
- D. Low latency and low reliability
- E. High reliability and low throughput

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3574`）

</details>

**1.3.3-56.** What is the goal of quality of service (QoS) prediction in mobile networks?

- A. To deliver a minimum guaranteed performance
- B. To handle performance fluctuations caused by highly mobile user equipments
- C. To ensure continuous guaranteed performance for services
- D. To exploit spare capacity for large bulk data transfers
- E. To improve the energy efficiency of drone-assisted base stations

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3681`）

</details>

**1.3.3-57.** What is a subscription in the context of service delivery? [3GPP Release 18]

- A. A commercial relationship between a subscriber and a service provider
- B. A set of services provided by a network operator
- C. A domain to which a user has access
- D. The identity of a subscriber within a domain
- E. The radio access systems available to a subscriber

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3695`）

</details>

**1.3.3-58.** What is the definition of MPS session?

- A. A session that prioritizes the allocation and maintenance of radio and network resources
- B. A session that provides multimedia telephony services
- C. A session that enables seamless WLAN offload
- D. A session that utilizes virtual private networks
- E. A session that facilitates over-the-top services

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3816`）

</details>

**1.3.3-59.** What is the purpose of the Session-AMBR? [3GPP Release 18]

- A. To limit the aggregate bit rate of GBR flows
- B. To limit the aggregate bit rate of non-GBR flows
- C. To limit the aggregate bit rate across all non-GBR flows in a PDU session
- D. To limit the aggregate bit rate of all QoS flows in a PDU session

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3896`）

</details>

**1.3.3-60.** What are the abilities provided by subscription-related priority mechanisms? [3GPP Release 18]

- A. Invoking, modifying, and maintaining QoS Flows with priority
- B. Classifying and differentiating specific services
- C. Delivering QoS Flow packets according to the QoS characteristics
- D. Establishing prioritized QoS Flows
- E. Preserving differentiated treatment for prioritized QoS Flow and resource distribution prioritization

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4153`）

</details>

**1.3.3-61.** What does Invocation-to-Release Priority Treatment include? [3GPP Release 18]

- A. Priority treatment during session release only
- B. Priority treatment during session invocation only
- C. Priority treatment during both session invocation and release
- D. Priority treatment during network interconnection

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4235`）

</details>

**1.3.3-62.** What is the meaning of "5G QoS Identifier"?

- A. A unique identifier for a 5G device.
- B. An identifier used to classify different types of 5G traffic.
- C. An identifier used to authenticate a 5G device.
- D. An identifier used to track the location of a 5G device.
- E. An identifier used to encrypt data transmitted by a 5G device.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4337`）

</details>

**1.3.3-63.** Which access class value is assigned to Multimedia Priority Service? [3GPP Release 18]

- A. Access Class 10
- B. Access Class 11
- C. Access Class 12
- D. Access Class 13
- E. Access Class 14

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4658`）

</details>

**1.3.3-64.** What aspects should be taken into account when developing URLLC (Ultrareliable and low-latency communication) techniques?

- A. Variety of different traffic characteristics
- B. QoS requirements
- C. Packet size and arrival model
- D. Low-latency and ultra-reliability
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4744`）

</details>

**1.3.3-65.** What does the Allowed Delay parameter indicate? [3GPP Release 18]

- A. The time interval for provisioning PFDs to SMFs
- B. The authorization status of the AF
- C. The list of PFDs in the request
- D. The operator policies for PFD provisioning

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4867`）

</details>

**1.3.3-66.** What is the primary purpose of MPS for DTS? [3GPP Release 18]

- A. To provide priority voice communication sessions in periods of severe network congestion
- B. To provide priority video communication sessions in periods of severe network congestion
- C. To provide priority data transport service in periods of severe network congestion
- D. To provide priority access to enterprise networks in periods of severe network congestion

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4978`）

</details>

**1.3.3-67.** What is the definition of AMBR?

- A. Aggregate Maximum Bit Rate
- B. Allocation and Retention Priority
- C. Access Mobility Bandwidth Ratio
- D. Arbitrary Maximum Bit Rate
- E. Activity Mobility Bandwidth Rate

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5210`）

</details>

**1.3.3-68.** What marks the completion of the PDU (Protocol Data Unit) session establishment process?

- A. Communication of the SM parameters to UE and RAN
- B. Successful configuration of the SM parameters at UE and RAN
- C. IPv6 Address Configuration information (i.e., an IPv6 Prefix) sent to the UE
- D. Successful communication between the UE and SMF
- E. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5271`）

</details>

**1.3.3-69.** What is the main distinguishing factor between UMTS QoS classes? [3GPP Release 17]

- A. Round trip delay
- B. Bit error rate
- C. Transfer delay
- D. Payload content

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5281`）

</details>

**1.3.3-70.** What is the purpose of Time Sensitive Communication Assistance Information (TSCAI) in the support of NR Industrial Internet of Things? [3GPP Release 16]

- A. To measure packet delay between UE and PSA UPF
- B. To provide information about TSC traffic characteristics for more efficient scheduling
- C. To support strict synchronization accuracy requirements of TSC applications
- D. To enhance the inter UE transmission prioritization and multiplexing
- E. To optimize handling of a mixture of URLLC and eMBB traffic

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5669`）

</details>

**1.3.3-71.** What is the main target of air interface, physical layer, and media access control layer advancements in 3rd generation partnership project Release 15?

- A. Enable 99.999% reliability within a 1 ms latency for 32 bytes packet size
- B. Achieve 1 ms latency for small size packets used in applications such as remote surgery and machine control
- C. Enable low latency and ultra-reliable services
- D. Replace traditional industrial wireline connectivity solutions such as Sercos or EtherCAT
- E. Support low latency and ultra-reliable services

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5678`）

</details>

**1.3.3-72.** What is a point-to-point service?

- A. Billing arrangement between customer and operator/service provider where the customer deposits an amount of money in advance
- B. A service type in which data is sent from a single network termination to another network termination
- C. A measure of throughput
- D. A unit of data specified in an (N)-protocol layer
- E. The geographical area in which a PLMN provides communication services

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5722`）

</details>

**1.3.3-73.** Who can obtain priority access to the next available radio channel in MPS? [3GPP Release 18]

- A. Only PLMN users
- B. Only MPS Service Provider network
- C. Qualified and authorized users
- D. Only machine interactions

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5921`）

</details>

**1.3.3-74.** What is the finest granularity of QoS differentiation at NAS level? [3GPP Release 18]

- A. QoS Profiles
- B. DRBs
- C. PDU Sessions
- D. QoS Flows

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6059`）

</details>

**1.3.3-75.** What are the characteristics of conversational services? [3GPP Release 18]

- A. Real-time, bi-directional, and low delay variation
- B. Store and forward, user-to-user communication
- C. Retrieval of information stored in information centers
- D. Access to flow of information without user control

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6190`）

</details>

**1.3.3-76.** What is the purpose of the Access Traffic Steering, Switch, and Splitting (ATSSS) feature? [3GPP Release 16]

- A. To establish a PDU Session that can use one 3GPP access network and one non-3GPP access network simultaneously
- B. To provide QoS control on wireline access networks
- C. To support the provisioning of configuration and remote management of 5G-RG
- D. To enhance the NG interface protocols for Trusted Non-3GPP Access and Wireline Access
- E. To specify charging requirements and procedures for 5WWC scenarios

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6709`）

</details>

**1.3.3-77.** What priority treatment is provided to MPS-subscribed UEs before the MPS application service session invocation? [3GPP Release 18]

- A. Priority treatment for access and attachment to the network
- B. Priority treatment for QoS rule enforcement
- C. Priority treatment for incoming sessions from other networks
- D. Priority treatment for supplementary services
- E. Priority treatment for handover

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6723`）

</details>

**1.3.3-78.** What does End-to-End Priority Treatment include? [3GPP Release 18]

- A. Priority treatment by the origination network only
- B. Priority treatment by all transit networks only
- C. Priority treatment by the originating and termination networks only
- D. Priority treatment by all MPS capable networks involved in the MPS session path

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6785`）

</details>

**1.3.3-79.** What are QoS (quality-of-service) identifiers used for in 5G?

- A. To specify the type of traffic carried by each bearer
- B. To represent RAN slices
- C. To calculate the average utilization of PRB over each bearer
- D. To train and test the ML models
- E. To forecast the future traffic load

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6894`）

</details>

**1.3.3-80.** What is the goal of ultra-reliable and low-latency communication (URLLC)?

- A. To achieve high spectral efficiency
- B. To satisfy stringent reliability and latency requirements of mission and safety-critical applications
- C. To capture non-stationary channel dynamics
- D. To leverage visual data for improved indoor positioning and navigation
- E. To overcome occlusions in computer vision

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6944`）

</details>

**1.3.3-81.** What resources are released when a PDU (Protocol Data Unit) session is released?

- A. Allocated IP address and UPF resources only
- B. UPF resources and RAN resources only
- C. Allocated IP address, UPF resources, and RAN resources
- D. UPF resources only
- E. Allocated IP address only

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6987`）

</details>

**1.3.3-82.** What is the meaning of MPS-subscribed UE?

- A. A UE with a personal identification number
- B. A UE that utilizes virtual private networks
- C. A UE that has a subscription to a mobile network operator supporting MPS
- D. A UE that utilizes over-the-top services
- E. A UE with multimedia telephony capabilities

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6998`）

</details>

**1.3.3-83.** What happens when the network cannot provide the required QoS for a data service? [3GPP Release 18]

- A. The service will be provided with a reduced QoS
- B. Both the originating and terminating application will be informed about the QoS configuration
- C. The service delivery will be based on network conditions only
- D. The requested service will not be provided
- E. The service will be delivered over the PS CN domain

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7485`）

</details>

**1.3.3-84.** What is the definition of guaranteed service?

- A. A service model that guarantees a dedicated network connection.
- B. A service model that provides consistent measured performance criteria.
- C. A service model that provides a high-speed data transfer.
- D. A service model that guarantees coverage in all geographical areas.
- E. A service model that provides highly reliable performance.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7562`）

</details>

**1.3.3-85.** What is a QoS profile?

- A. A network connection with defined characteristics
- B. A performance expectation placed on the bearer network
- C. A collective effect of service performances
- D. A period between the opening and closing of a network connection
- E. A number of QoS parameters

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-8060`）

</details>

**1.3.3-86.** What is the purpose of Usage Parameter Control (UPC)?

- A. To update the UTRAN registration area when a connection exists.
- B. To access services provided by mobile networks.
- C. To monitor and control the offered traffic and the validity of the connection.
- D. To transmit signals from a UE to a base station.
- E. To perform radio transmission and reception within the UTRAN.

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-935`）

</details>

**1.3.3-87.** What is the purpose of QoS Monitoring in the enhancement of URLLC support in the 5G Core network? [3GPP Release 16]

- A. To measure packet delay between UE and PSA UPF
- B. To calculate the core network Packet Delay Budget (CN PDB)
- C. To provide support for up to eight simultaneously active semi-persistent scheduling (SPS) configurations
- D. To support accurate reference timing delivery for Time Sensitive Communications
- E. To enhance the inter UE transmission prioritization and multiplexing

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5958`）

</details>

**1.3.3-88.** What does AULC decouple between the PCRF and the OCS? [3GPP Release 14]

- A. UE subscription
- B. User location information
- C. Presence Reporting Area (PRA) subscription
- D. Charging behavior

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6491`）

</details>

**1.3.3-89.** What is the purpose of traffic classification?

- A. To increase the computational overhead of network traffic
- B. To encrypt network traffic for security purposes
- C. To categorize network traffic into appropriate classes
- D. To obfuscate data packet inspection

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6959`）

</details>

**1.3.3-90.** What is one of the challenges of using port numbers for traffic classification?

- A. Port numbers are not widely used in practice
- B. Port numbers are highly accurate for categorizing network traffic
- C. New applications use well-known port numbers to disguise their traffic
- D. Port numbers have low computational overhead

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7076`）

</details>

**1.3.3-91.** What is the purpose of redundant transmission for high reliability communication in URLLC? [3GPP Release 18]

- A. To establish two independent user plane paths for increased reliability.
- B. To support dual connectivity between the UE and the SMF.
- C. To ensure time-sensitive networking for URLLC services.
- D. To provide redundancy in the RAN and UPF deployment.
- E. To guarantee the physical network topology and function distribution support.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3039`）

</details>

**1.3.3-92.** What is a key aspect of ensuring high-quality service in packet-switched networks within the context of O-RAN?

- A. Building flexible L3VPN service topologies
- B. Constraints-based traffic steering in L3VPNs
- C. Quality of Service (QoS) mechanisms
- D. Transport network core interface marking structure

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-277`）

</details>

**1.3.3-93.** What is the primary objective of the ORAN.WG8.IOT.010 test case?

- A. Verify the network initiated PDU Modification procedure in an end-to-end environment.
- B. Test the performance of the O-DU and O-CU in a 5G network.
- C. Evaluate the security of the O-RAN architecture.
- D. Analyze the impact of different network configurations on user experience.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-403`）

</details>

**1.3.3-94.** Which of the following is a mandatory field within the "qosObjectives" object in the O-RAN specification?

- A. gfbr
- B. mfbr
- C. priorityLevel
- D. pdb

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-453`）

</details>

**1.3.3-95.** Which RFC specifies the "Assured Forwarding PHB Group"?

- A. RFC 2545
- B. RFC 2597
- C. RFC 2598
- D. RFC 2745

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-552`）

</details>

**1.3.3-96.** What is the definition of residual error rate?

- A. A parameter describing service accuracy.
- B. The maximum gain of the receiver antenna in the horizontal plane.
- C. The bandwidth in which an emission level is specified.
- D. The pointer, which addresses one record in an EF.
- E. The difference between the power of a RE and the average RE power for a BS at maximum output power.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-899`）

</details>

**1.3.3-97.** What is the concept of Quality of Service (QoS) in telecommunications?

- A. A measure of how well the telecommunications system is working
- B. A measure of how happy the customer is with the service
- C. A measure of the loudness rating during a call
- D. A measure of the percentage of lost calls during the busy hour
- E. A measure of the delay before receiving dial tone

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3975`）

</details>

**1.3.3-98.** What is the definition of SDU transfer rate?

- A. The ratio of total incorrect service data units (SDUs) to total successfully transferred service data units plus incorrect service data units in a specified sample.
- B. The ratio of total lost service data units (SDUs) to total transmitted service data units in a specified sample.
- C. The ratio of total misdelivered service data units (SDUs) to total service data units transferred between a specified source and destination user in a specified sample.
- D. The value of elapsed time between the start of transfer and successful transfer of a specified service data unit (SDU).
- E. The total number of successfully transferred service data units (SDUs) in a transfer sample divided by the input/output time for that sample.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4405`）

</details>

**1.3.3-99.** What is Delivered QoS?

- A. The requested QoS parameter values for a session.
- B. The maximum achievable QoS parameter values for a session.
- C. The average QoS parameter values for a session.
- D. The minimum required QoS parameter values for a session.
- E. The actual QoS parameter values with which the content was delivered over the lifetime of a QoS session.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4603`）

</details>

**1.3.3-100.** What is Extra SDU delivery probability?

- A. The ratio of total requested SDUs to total service data units received
- B. The ratio of total extra service data units to total service data units received
- C. The probability of receiving extra service data units in a specified sample
- D. The probability of receiving unrequested service data units in a specified sample

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5043`）

</details>

**1.3.3-101.** What is the survival time metric used for?

- A. To measure the time it takes for a packet to be transmitted by the destination
- B. To measure the time it takes for a packet to be generated by the source
- C. To measure the time it takes for a packet to be received by the destination
- D. To measure the time it takes for a packet to be acknowledged by the transmitter
- E. To measure the time that an application consuming a communication service may continue without an anticipated message

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6621`）

</details>

**1.3.3-102.** What is the definition of SDU loss probability?

- A. The ratio of total incorrect service data units (SDUs) to total successfully transferred service data units plus incorrect service data units in a specified sample.
- B. The ratio of total lost service data units (SDUs) to total transmitted service data units in a specified sample.
- C. The ratio of total misdelivered service data units (SDUs) to total service data units transferred between a specified source and destination user in a specified sample.
- D. The time elapsed from the invocation of the service request to the corresponding service request indication at the Service Receiver.
- E. The total number of successfully transferred service data units (SDUs) in a transfer sample divided by the input/output time for that sample.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6693`）

</details>

**1.3.3-103.** What is the definition of SDU error probability?

- A. The ratio of total incorrect service data units (SDUs) to total successfully transferred service data units plus incorrect service data units in a specified sample.
- B. The ratio of total lost service data units (SDUs) to total transmitted service data units in a specified sample.
- C. The ratio of total misdelivered service data units (SDUs) to total service data units transferred between a specified source and destination user in a specified sample.
- D. The time elapsed from the invocation of the service request to the corresponding service request indication at the Service Receiver.
- E. The total number of successfully transferred service data units (SDUs) in a transfer sample divided by the input/output time for that sample.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7081`）

</details>

**1.3.3-104.** How can reliability be improved in URLLC (Ultra reliable and low latency communications) applications?

- A. By utilizing resources in the frequency, antenna, and spatial domain
- B. By utilizing resources in the time domain
- C. By utilizing resources in the power domain
- D. By utilizing resources in the modulation domain
- E. By utilizing resources in the channel domain

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-321`）

</details>

**1.3.3-105.** What is the purpose of steering of access in the Evolved Packet System? [3GPP Release 17]

- A. To optimize routing for user plane traffic
- B. To support mobility within and across access systems
- C. To minimize packet loss during inter- and/or intra-access technology changes
- D. To provide continuous service during and following changes of access systems
- E. To enable the operator to request the use of a specific access technology

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4570`）

</details>

**1.3.3-106.** What is the role of radio resources in wireless communications?

- A. To transmit data over long distances
- B. To optimize users' Quality of Service (QoS)
- C. To limit the usage of facilities
- D. To minimize operators' revenue
- E. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6373`）

</details>

## 1.3.4 漫遊（26 題）

**1.3.4-1.** Which entity is used as an SGSN for only some GTP signalling messages in a GLR-equipped VPLMN? [3GPP Release 17]

- A. Intermediate Mobile-services Switching Centre (IM-MSC)
- B. Gateway Location Register (GLR)
- C. Intermediate GPRS Serving Node (IM-GSN)
- D. GGSN - packet data networks
- E. CSCF/IBCF - Multimedia IP networks

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5100`）

</details>

**1.3.4-2.** What is the purpose of the IM-MSC in a GLR-equipped VPLMN? [3GPP Release 17]

- A. To handle location management of roaming subscribers
- B. To relay messages between home network and serving MSC
- C. To handle GTP signalling messages
- D. To optimize signalling traffic between PLMNs
- E. To provide IMS services

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5302`）

</details>

**1.3.4-3.** What is the purpose of an alternative route in the context of routing the subscription identity back to its Home Environment? [3GPP Release 18]

- A. To determine the lowest cost to the end user.
- B. To reach a given Home Environment.
- C. To maintain a list of all known Home Environments.
- D. To establish a commercial roaming agreement with the serving network operators.
- E. To enable interworking between the home environment and serving network operators.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6972`）

</details>

**1.3.4-4.** What does GLR stand for? [3GPP Release 17]

- A. General Location Register
- B. Gateway Location Routing
- C. Global Location Register
- D. Global Location Routing
- E. Gateway Location Register

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7946`）

</details>

**1.3.4-5.** What is the purpose of the IM-GSN in a GLR-equipped VPLMN? [3GPP Release 17]

- A. To handle location management of roaming subscribers
- B. To relay messages between home network and serving MSC
- C. To handle GTP signalling messages
- D. To optimize signalling traffic between PLMNs
- E. To provide IMS services

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2617`）

</details>

**1.3.4-6.** Which entities are involved in the PDU Session establishment for supporting HR-SBO in VPLMN? [3GPP Release 18]

- A. AMF and V-SMF
- B. AMF and H-SMF
- C. UE and H-SMF
- D. UE and V-SMF

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5309`）

</details>

**1.3.4-7.** What action does the AMF take when the updated subscription data indicates that the UE is not allowed to roam in the network? [3GPP Release 18]

- A. Initiating an SMF initiated PDU Session Modification procedure
- B. Initiating an AMF initiated Deregistration procedure
- C. Updating UE context stored at RAN to modify the UE-Slice-MBR corresponding to an S-NSSAI
- D. Initiating UE Configuration Update procedure

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6273`）

</details>

**1.3.4-8.** Which entity handles location management of roaming subscribers in the visited network without involving HLR? [3GPP Release 17]

- A. Intermediate Mobile-services Switching Centre (IM-MSC)
- B. Intermediate GPRS Serving Node (IM-GSN)
- C. Gateway Location Register (GLR)
- D. GGSN - packet data networks
- E. CSCF/IBCF - Multimedia IP networks

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7197`）

</details>

**1.3.4-9.** What does the home environment need to provide to the visited network when allowing a subscriber to roam to different domains? [3GPP Release 18]

- A. Service data
- B. Authentication data
- C. Subscription data
- D. Capabilities data
- E. Roaming agreement data

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-143`）

</details>

**1.3.4-10.** What does MINT stand for? [3GPP Release 17]

- A. Maximum Internet Network Transmission
- B. Minimization of Interruption Network Technology
- C. Maximization of Internet Network Traffic
- D. Minimization of Service Interruption
- E. Maximum Internet Network Technology

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-624`）

</details>

**1.3.4-11.** What is the key characteristic of a roaming broker enabled Home Environment? [3GPP Release 18]

- A. It has a direct commercial agreement with different serving networks.
- B. It interworks with one or more serving network operators.
- C. It uses fraud and cost control mechanisms to ensure charges do not exceed credit limits.
- D. It routes registration requests to its serving networks.
- E. It is capable of operating as a roaming broker.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-906`）

</details>

頁次：**1**　[2](1-3-gsma-2.md)　[3](1-3-gsma-3.md)
