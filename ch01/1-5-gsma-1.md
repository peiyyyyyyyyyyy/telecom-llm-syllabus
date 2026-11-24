# 1.5 開放與虛擬化　GSMA 練習題（909 題）（第 1／5 頁）

所屬：[1.5 開放與虛擬化](1-5.md)

只收 GSMA 訓練題；不含驗證集與測試集，並已去除和驗證／測試題相同或相似、重複、標註衝突的題目。題目依小節歸類（抽查正確率約 95%）。

頁次：**1**　[2](1-5-gsma-2.md)　[3](1-5-gsma-3.md)　[4](1-5-gsma-4.md)　[5](1-5-gsma-5.md)

## 1.5.1 O-RAN 架構與元件：O-CU、O-DU、O-RU、SMO（170 題）

**1.5.1-1.** What is the role of the OSS (operations support systems) in the O-RAN architecture?

- A. Handling communications between the multi-RAT O-CU and the AMF and UPF
- B. Monitoring and performing life cycle operation and management functions of the O-RU, O-DU, O-CU, and near-RT RIC components
- C. Connecting the CU to the DUs
- D. Enabling near-RT RAN control and optimization through xApps
- E. Facilitating AI-related parameter exchange between the non-RT and near-RT RICs

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3385`）

</details>

**1.5.1-2.** What is the purpose of ONAP in O-RAN? 

- A. Open Radio Access Networks
- B. Open Fronthaul
- C. Operation Support System
- D. Operating System
- E. Open Networking Automation Platform

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5388`）

</details>

**1.5.1-3.** How does O-RAN enable interchangeability of components?

- A. By using proprietary RAN hardware and software.
- B. By standardizing and opening the interfaces between logical components.
- C. By limiting network functionality for O-RAN components.
- D. By restricting the use of O-RAN components to a single vendor.
- E. By excluding MNOs from the development of O-RAN components.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-158`）

</details>

**1.5.1-4.** What advantage does ONAP offer as an automation platform for O-RAN Town related services? 

- A. Ability to integrate with multiple network domains
- B. Vendor independence in managing RAN components
- C. Support for virtualized open RAN deployment
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-205`）

</details>

**1.5.1-5.** What is the logical architecture for disaggregated RAN? 

- A. O-eNB, O-CU-CP, O-CU-UP, O-DU, O-RU, O-Cloud
- B. Open fronthaul, General-Purpose Processor, Service Management and Orchestration Framework
- C. X2, E2, F1-c, F1-u, NG-u, NG-c, Xn-u, Xn-c
- D. RAN interfaces, IOT, GPP, and COTS hardware
- E. Mobile network deployments, RAN vendors, and baseband workload processing

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-609`）

</details>

**1.5.1-6.** Which platform is used for data movement services from any source to any target?

- A. Virtual Event Streaming
- B. Non-RT RIC
- C. O-RAN SC
- D. ONAP
- E. DMaaP

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-645`）

</details>

**1.5.1-7.** What is one of the deployment requirements for an open RAN solution? 

- A. Low latency in the transport network
- B. High-capacity fronthaul transport
- C. Encryption for user traffic
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-699`）

</details>

**1.5.1-8.** What is the purpose of the Central Unit in the O-RAN architecture?

- A. To distribute the higher layers of the protocol stack
- B. To handle frequency-domain functionalities
- C. To perform management and control of the network at near-real-time
- D. To implement the physical layer

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-991`）

</details>

**1.5.1-9.** What are the main functional entities and interfaces in the O-RAN architecture?

- A. Non-RT RIC, Near-RT RIC, E2 Nodes, O-Cloud, AI Server
- B. Non-RT RIC, Near-RT RIC, E2 Interface, O1 Interface, O2 Interface
- C. SMO System, xApps, E2 Nodes, O-Cloud, AI Server
- D. E2 Nodes, Near-RT RIC, O-Cloud, AI Server, SMO Framework
- E. Non-RT RIC, Near-RT RIC, Service Orchestrator (SO), Data Collector, AI Server

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1456`）

</details>

**1.5.1-10.** What is the framework that manages and orchestrates all RAN nodes and the underlying cloud computing layer? 

- A. OFH M-Plane
- B. O-Cloud
- C. Service and Management Orchestration (SMO)
- D. O1 interface
- E. O2 interface

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1598`）

</details>

**1.5.1-11.** What are the key enablers of data-driven applications in cellular networks?

- A. Openness, programmability, and disaggregation
- B. Centralized approaches and low latency
- C. Data collection and aggregation
- D. Randomized initialization and offline training

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1623`）

</details>

**1.5.1-12.** What is the purpose of the vendor independent Service Management and Orchestration (SMO) framework? 

- A. To provide control and flexibility in the management of RAN components
- B. To automate RAN planning, deployment, and operations tasks
- C. To enable the introduction of innovation in RAN infrastructure
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1871`）

</details>

**1.5.1-13.** What are the components of the O-RAN architecture?

- A. O-CU Control Plane (O-CU-CP), O-CU User Plane (O-CU-UP), Near-Real Time RAN Intelligent Controller (Near-RT RIC)
- B. O-DU Control Plane (O-DU-CP), O-DU User Plane (O-DU-UP), O-RAN Intelligent Controller (Near-RT RIC)
- C. O-DU Control Plane (O-DU-CP), O-DU User Plane (O-DU-UP), O-RU Control Plane (O-RU-CP)
- D. O-RAN Central Unit (O-CU), O-RAN Distributed Unit (O-DU), O-RAN Radio Unit (O-RU), Near-Real Time RAN Intelligent Controller (Near-RT RIC)
- E. O-RAN Central Unit (O-CU), O-RAN Distributed Unit (O-DU), O-RAN Radio Unit (O-RU)

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2492`）

</details>

**1.5.1-14.** What is the purpose of the DMaaP (Data movement as a platform)?

- A. To collect RAN statistics for each slice
- B. To process JavaScript Object Notation (JSON) messages
- C. To transport and process data from any source to any target
- D. To predict the future values of target parameters
- E. To configure O-Cloud

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2619`）

</details>

**1.5.1-15.** What is required to ensure interoperability and alignment in the open RAN ecosystem? 

- A. Tight alignment between system components vendors
- B. Fast delivery of necessary software adaptations
- C. Consistent approach across all RAN components
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2829`）

</details>

**1.5.1-16.** What is the objective of the O-RAN framework?

- A. To enhance the performance of the radio access network through virtualization and open interfaces
- B. To improve the efficiency of cellular network management through data-driven approaches
- C. To introduce artificial intelligence into the deployment, operation, and maintenance of the network
- D. To enable the use of renewable energy sources in cellular networks
- E. To provide virtual network slices and dynamic spectrum sharing

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3057`）

</details>

**1.5.1-17.** What is the role of the Orchestrator in the O-RAN architecture?

- A. To control and monitor dApps
- B. To provide resource management for dApps
- C. To ensure conflict mitigation between dApps
- D. To determine which applications should be executed and where
- E. To leverage O-RAN interfaces for dApp deployment

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3279`）

</details>

**1.5.1-18.** What is the Partnership model for collaboration in a multi-vendor open RAN solution? 

- A. A system integrator takes overall responsibility for the end-to-end solution
- B. The operator takes end-to-end responsibility for the solution
- C. Multiple vendors collaborate on specific components
- D. There is no defined collaboration model

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4014`）

</details>

**1.5.1-19.** What is the advantage of the Open RAN (Radio Access Network) approach?

- A. Allows for disaggregation and choosing different RAN components from different vendors
- B. Reduces the need for advanced network architecture
- C. Increases the cost of RAN deployment
- D. Improves spectral efficiency
- E. None of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4135`）

</details>

**1.5.1-20.** What are the two integration areas required to manage the lifecycle of a new open RAN solution? 

- A. Vertical integration and horizontal integration
- B. COTS hardware integration and RAN software stack integration
- C. Virtualization technologies integration and RAN infrastructure integration
- D. O-Cloud HW layer integration and RAN virtualized O-BBU integration
- E. All of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4165`）

</details>

**1.5.1-21.** What are the different deployment options for open RAN? 

- A. Distributed RAN, O-CU/O-DU split, Fully centralized O-CU/O-DU
- B. Distributed RAN, Centralized O-CU, Fully centralized O-DU
- C. Centralized RAN, O-CU/O-DU split, Fully distributed O-RU
- D. Distributed O-CU, Centralized O-DU, Fully centralized RAN
- E. None of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4364`）

</details>

**1.5.1-22.** What are the four foundational principles for the Open RAN?

- A. Centralization, virtualization, closed interfaces, intelligent control
- B. Integration, virtualization, open interfaces, disaggregation
- C. Disaggregation, intelligent control, virtualization, closed interfaces
- D. Closed interfaces, disaggregation, integration, intelligent control
- E. Virtualization, open interfaces, centralization, integration

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4563`）

</details>

**1.5.1-23.** What does O-RAN stand for? 

- A. Open Fronthaul
- B. Open RAN Town
- C. Operating System
- D. Open Networking Automation Platform
- E. Open Radio Access Network

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5180`）

</details>

**1.5.1-24.** What does the O-RAN architecture encompass?

- A. RAN and OSS only
- B. RAN, OSS, and open interfaces
- C. RAN and radio engineering systems
- D. RAN, operations support systems, and radio engineering systems
- E. RAN and open interfaces only

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7038`）

</details>

**1.5.1-25.** What are the three main technical areas driving the transformation of RAN by open RAN? 

- A. Open interfaces, virtualization, and intelligence
- B. Highly efficient hardware, software disaggregation, and COTS
- C. Disaggregated RAN architecture, open fronthaul, and OFH interface
- D. General-Purpose Processor (GPP) based hardware, RAN virtualization, and cloudification
- E. Interoperability, scalability, and flexibility

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7154`）

</details>

**1.5.1-26.** Which of the following E2 node configurations is represented by the O-GNBCUUPFunction configuration structure?

- A. O-DU
- B. O-CU-CP
- C. O-CU-UP
- D. O-RRMPolicyRatio

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-2`）

</details>

**1.5.1-27.** Which of the following is a key advantage of Open Radio Access Networks (O-RAN)?

- A. Increased vendor lock-in
- B. Reduced network flexibility
- C. Enhanced interoperability between different vendors
- D. Limited innovation and development

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-6`）

</details>

**1.5.1-28.** What is a key component within the O-RAN architecture responsible for handling radio frequency processing?

- A. Transceiver Reference Design
- B. Hardware Specifications
- C. RF Processing Unit
- D. Interface Requirements

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-8`）

</details>

**1.5.1-29.** What are the typical power supply modes for an O-RAN indoor picocell?

- A. AC power only
- B. DC power only
- C. Power over Ethernet (POE) or optical electric composite cables
- D. Solar power

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-11`）

</details>

**1.5.1-30.** What is the maximum output power of the +12V rail in the O-DU7-2 chassis?

- A. 12A
- B. 15A
- C. 41A
- D. 0.2A

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-15`）

</details>

**1.5.1-31.** What does the acronym "O-RAN" stand for?

- A. Open Radio Access Network
- B. Optimized Radio Access Network
- C. Operational Radio Access Network
- D. Online Radio Access Network

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-27`）

</details>

**1.5.1-32.** What is the typical impedance value for RF inputs and outputs in an O-RAN system?

- A. 100 ohm
- B. 50 ohm
- C. 75 ohm
- D. 25 ohm

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-28`）

</details>

**1.5.1-33.** Which of the following components is responsible for handling the radio interface in an O-RAN network?

- A. O-CU
- B. O-DU
- C. O-RU
- D. OSS

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-36`）

</details>

**1.5.1-34.** What is the primary focus of the document section titled "High Level Description"?

- A. Providing a comprehensive overview of the O-RAN architecture and its functionalities.
- B. Defining key terms, symbols, and abbreviations used throughout the document.
- C. Listing relevant references and standards for O-RAN technology.
- D. Describing the revision and compatibility handling procedures.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-59`）

</details>

**1.5.1-35.** Which of the following describes an architecture where the O-RUx and O-DUx are physically separated?

- A. Integrated architecture
- B. Split architecture
- C. F1 interface architecture
- D. TRxP architecture

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-66`）

</details>

**1.5.1-36.** What type of processing instruction set does the SoC in the O-DU7-2 support?

- A. 128-bit
- B. 256-bit
- C. 512-bit
- D. 1024-bit

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-82`）

</details>

**1.5.1-37.** Which of the following technologies is used for data transmission in the O-RAN architecture?

- A. Circuit Switched
- B. Packet Switched
- C. Frequency Hopping
- D. Time Division Multiplexing

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-83`）

</details>

**1.5.1-38.** What is the maximum power consumption allowed for an integrated O-DU/O-RU using Power over Ethernet (PoE) at full load?

- A. 12.95W
- B. 25.5W
- C. 48.5W
- D. 75W

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-107`）

</details>

**1.5.1-39.** What is the primary source of power for an O-RU in an Outdoor Macrocell?

- A. Internal AC line power
- B. External telco -48V supply
- C. Solar panels
- D. Batteries

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-116`）

</details>

**1.5.1-40.** Which component of the O-RAN architecture is responsible for the control plane functions?

- A. O-DU
- B. O-RU
- C. O-CU-CP
- D. O-CU-UP

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-147`）

</details>

**1.5.1-41.** Which of the following is a key benefit of Open Radio Access Networks (O-RAN)?

- A. Increased vendor lock-in
- B. Reduced flexibility and customization
- C. Improved interoperability and vendor diversity
- D. Enhanced dependence on single vendors

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-152`）

</details>

**1.5.1-42.** Which of the following is a function of the O-DU in an Open Radio Access Network (O-RAN) system?

- A. Allow rApps to access measurement data and provide configuration recommendations via relevant R1 interface services.
- B. Send measurement data and RAN configurations to SMO/Non-RT RIC via the O1 interface.
- C. Support implementation of MIMO configuration parameters received from the SMO/Non-RT RIC via the O1 interface.
- D. Train and deploy AI/ML models for MIMO optimization.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-155`）

</details>

**1.5.1-43.** What does SMO stand for in the context of Open Radio Access Networks?

- A. Service Management and Orchestration
- B. System Management and Optimization
- C. Service Monitoring and Operations
- D. System Monitoring and Orchestration

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-165`）

</details>

**1.5.1-44.** What is the primary function of the Digital Processing Unit (DPU) in an O-RU?

- A. Handles fronthaul interface, lower L1 processing, synchronization, and beamforming.
- B. Performs synchronization, digital down-conversion (DDC), digital up-conversion (DUC), channel frequency response (CFR), and digital pre-distortion (DPD).
- C. Manages the antenna calibration process.
- D. Connects the O-RU to the O-DU.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-171`）

</details>

**1.5.1-45.** Which of the following is NOT a component typically found in an O-RAN radio unit?

- A. Motherboard
- B. Chassis
- C. Cooling system
- D. Battery

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-181`）

</details>

**1.5.1-46.** Which of the following components are NOT considered part of the Open Radio Access Network (O-RAN) architecture?

- A. O-DU (Open Distributed Unit)
- B. O-CU (Open Centralized Unit)
- C. O-RU (Open Radio Unit)
- D. 5G Core

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-204`）

</details>

**1.5.1-47.** Which of the following is NOT a function typically offloaded to the L1 in an O-RAN architecture?

- A. LDPC encoding and decoding
- B. HARQ management
- C. Cell searching
- D. FFT/IFFT processing

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-213`）

</details>

**1.5.1-48.** Which of the following components is NOT a part of the Open Radio Access Network (O-RAN) architecture?

- A. SMO
- B. O-DU
- C. O-CU
- D. LTE eNodeB

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-217`）

</details>

**1.5.1-49.** What is the function of the O-RAN Radio Unit (O-RU)?

- A. Manages the overall network and user data.
- B. Handles the radio interface and signal processing.
- C. Provides centralized control and coordination for the network.
- D. Connects the O-RAN network to the core network.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-218`）

</details>

**1.5.1-50.** Which of the following is NOT a component of the O-RU Hardware Components?

- A. Digital Processing Unit
- B. RF Processing Unit
- C. Power Amplifier (PA) Reference Design
- D. Synchronization and Timing

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-220`）

</details>

**1.5.1-51.** Which of the following is NOT a core function of an Open Radio Access Network (O-RAN)?

- A. Data management and exposure
- B. Authentication and authorization
- C. Network slicing
- D. AI/ML workflow functions

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-227`）

</details>

**1.5.1-52.** What is the maximum power consumption of an O-RU7-2x Tri-band B1/n1+B3/n3+B7/n7 product, assuming 100% full loading, at 55°C and natural cooling?

- A. 500W
- B. 700W
- C. 950W
- D. 1300W

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-229`）

</details>

**1.5.1-53.** Which of the following is a use case discussed in the context provided?

- A. RAN Sharing
- B. Network Slicing
- C. 5G Core Integration
- D. Cloud Native Infrastructure

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-234`）

</details>

**1.5.1-54.** What does the acronym "O-CU-UP" stand for in the context of O-RAN?

- A. O-RAN Central Unit - User Plane
- B. O-RAN Control Unit - User Protocol
- C. O-RAN Central Unit - User Profile
- D. O-RAN Control Unit - User Plane

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-237`）

</details>

**1.5.1-55.** What is the priority level for the O-CU interface requirement that specifies the transport interface to connect with the O-DU7-2x at the cell site or data center?

- A. Low
- B. Medium
- C. High
- D. Very High

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-250`）

</details>

**1.5.1-56.** Which of the following components is responsible for registering the O-DU as online?

- A. O-CU
- B. O-RU
- C. SMO
- D. Near-RT RIC

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-259`）

</details>

**1.5.1-57.** In an O-RAN network, what is the primary function of the primary vO-DU?

- A. Processing only DRB (Data Radio Bearer) related functions.
- B. Processing SRB (Signalling Radio Bearer), DRB, and other vO-DU related functions.
- C. Configuring vO-DU and vO-CU for resource assignment.
- D. Collecting KPI data from the network.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-260`）

</details>

**1.5.1-58.** What is a key aspect of O-RAN that aims to create a more open and interoperable ecosystem?

- A. The use of proprietary interfaces for network components.
- B. The reliance on a single vendor for all network equipment.
- C. The adoption of open standards and interfaces for network elements.
- D. The exclusion of third-party vendors from the network infrastructure.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-261`）

</details>

**1.5.1-59.** In an Open RAN deployment with limited Fronthaul capacity and geographically dispersed O-RUs, what architectural approach is most suitable to maximize efficiency and meet latency requirements?

- A. Centralizing the O-CU and near-RT RIC network functions.
- B. Deploying a dedicated O-DU for each O-RU.
- C. Utilizing a separate FH GW for each O-RU.
- D. Decentralizing the O-CU and near-RT RIC network functions.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-266`）

</details>

**1.5.1-60.** What type of control interface is typically used for O-RAN transceivers?

- A. USB
- B. Ethernet
- C. SPI or I2C
- D. Bluetooth

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-267`）

</details>

**1.5.1-61.** What are the two main hardware components of the O-RU (O-RAN Radio Unit)?

- A. Digital Processing Unit and RF Processing Unit
- B. O-RU High-Level Functional Block Diagram and O-RU Hardware Components
- C. Synchronization and Timing and Accelerator Design
- D. O-RU Portion of Integrated Reference Design and O-RU High-Level Functional Block Diagram

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-278`）

</details>

**1.5.1-62.** In a four-layer Open Radio Access Network (O-RAN) architecture, which component is directly accessible by the end-user customer?

- A. Service Orchestrator
- B. Network Management System
- C. Radio Network Controller
- D. O-RU

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-281`）

</details>

**1.5.1-63.** What are the four modules that make up the O-RU7-2 hardware?

- A. Optical interface, digital processing unit, RF processing unit, and antenna unit
- B. Ethernet interface, digital processing unit, RF processing unit, and antenna unit
- C. Optical interface, digital processing unit, RF processing unit, and timing unit
- D. Ethernet interface, digital processing unit, RF processing unit, and timing unit

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-287`）

</details>

**1.5.1-64.** What does the abbreviation "O-CU-CP" stand for in the context of Open Radio Access Networks (O-RAN)?

- A. O-RAN Central Unit - Control Plane
- B. O-RAN Central Unit - User Plane
- C. O-RAN Distributed Unit - Control Plane
- D. O-RAN Radio Unit - Control Plane

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-290`）

</details>

**1.5.1-65.** What is the maximum output power of the +12V supply in the O-DU6 hardware system?

- A. 12A
- B. 15A
- C. 41A
- D. 0.2A

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-292`）

</details>

**1.5.1-66.** What does "O-DUx" stand for in the context of O-RAN?

- A. O-RAN Distributed Unit with a specific fronthaul split option
- B. O-RAN Unified Unit with a specific fronthaul split option
- C. O-RAN Centralized Unit with a specific fronthaul split option
- D. O-RAN Radio Unit with a specific fronthaul split option

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-293`）

</details>

**1.5.1-67.** Which of the following is a key characteristic of Open Radio Access Networks (O-RAN)?

- A. Proprietary hardware and software components
- B. Centralized control and management
- C. Standardized interfaces and open interfaces
- D. Limited interoperability between vendors

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-308`）

</details>

**1.5.1-68.** What does "FAPI" stand for in the context of O-RAN?

- A. Functional Application Platform Interface
- B. Forward Error Correction
- C. Fast Fourier Transform
- D. Fronthaul Gateway

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-313`）

</details>

**1.5.1-69.** What is the name of the firmware version mentioned in the provided context?

- A. ORAN-WG7.IPC-HRD-Opt7-2.0-v03.00
- B. O-DU7-2
- C. O-RAN ALLIANCE e.V.
- D. Annex ZZZ

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-331`）

</details>

**1.5.1-70.** What is the purpose of the "dirPattern" field in the TDD_CONFIG_PATTERN command?

- A. To specify the number of slots for which the command configuration is valid.
- B. To define the transmit/receive direction for each symbol in a slot.
- C. To indicate whether a symbol is a guard symbol or a data symbol.
- D. To determine the type of beamforming weight compression used.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-343`）

</details>

**1.5.1-71.** What is the minimum efficiency requirement for a Power Amplifier (PA) in an O-RAN system operating on Band 48?

- A. > 33%
- B. > 42%
- C. > 45%
- D. > 50%

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-348`）

</details>

**1.5.1-72.** Which of the following O-RAN components is described in the provided context?

- A. FHGW
- B. O-RU
- C. O-DU
- D. O-CU

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-354`）

</details>

**1.5.1-73.** What is a key advantage of modularity in Open Radio Access Networks (O-RAN)?

- A. Improved security by isolating components.
- B. Reduced latency through optimized data flow.
- C. Enhanced flexibility by allowing different vendors to provide components.
- D. Lower power consumption through efficient resource allocation.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-361`）

</details>

**1.5.1-74.** What is the name of the unit that handles the digital processing in an O-RAN architecture?

- A. Power Amplifier
- B. Digital Processing Unit
- C. LNA
- D. Circulator

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-369`）

</details>

**1.5.1-75.** Which type of O-RU connector is used for communication between the O-RU and Antenna Line Devices?

- A. O-RU-EXTIO
- B. O-RU-CONNECTOR
- C. RS-485
- D. O-RAN

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-378`）

</details>

**1.5.1-76.** What does O-RU stand for in the context of O-RAN?

- A. Open Radio Unit
- B. O-RAN Radio Unit
- C. Open Radio Access Unit
- D. O-RAN Radio Access Unit

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-380`）

</details>

**1.5.1-77.** What type of data is transmitted or received via the High Speed Data interface in an O-RAN device?

- A. Time-domain baseband information
- B. Frequency-domain baseband information
- C. Control signals
- D. Power levels

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-382`）

</details>

**1.5.1-78.** Which of the following components is responsible for processing radio signals in an O-RAN architecture?

- A. Network Processing Unit (NPU)
- B. Radio Signal Processor (FPGA)
- C. Memory and Storage for CPU
- D. PCIe Interface

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-392`）

</details>

**1.5.1-79.** Which of the following O-RAN components is responsible for processing and forwarding user data between the Radio Unit (O-RU) and the Centralized Unit (O-CU)?

- A. O-RU
- B. O-DU
- C. O-CU
- D. nFAPI

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-407`）

</details>

**1.5.1-80.** What does O-DUx represent in the context of O-RAN?

- A. A specific O-RAN Distributed Unit with a defined fronthaul split option.
- B. A type of O-RAN Radio Unit used for fronthaul interface.
- C. A specific O-RAN Centralized Unit with a defined fronthaul split option.
- D. A type of O-RAN Power Amplifier used for fronthaul interface.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-417`）

</details>

**1.5.1-81.** In the O-RAN architecture, what is the primary responsibility of the O-DU (O-RAN Distributed Unit)?

- A. Handling the physical layer functions, including radio frequency (RF) signal processing.
- B. Providing the data plane functionality for the Radio Access Network (RAN).
- C. Managing the control plane functions for the RAN.
- D. Managing user authentication and authorization.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-428`）

</details>

**1.5.1-82.** What is the primary function of the O-RUx in an Open Radio Access Network (O-RAN)?

- A. To manage and control the radio network.
- B. To convert baseband signals into RF signals and vice versa.
- C. To handle user data and provide network services.
- D. To connect the O-DU to the core network.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-436`）

</details>

**1.5.1-83.** Which of the following is NOT a component of the O-RAN architecture as depicted in the provided context?

- A. OAM Functions
- B. Near-RT RIC
- C. E2 Node
- D. 5G Core

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-438`）

</details>

**1.5.1-84.** What is the primary function of the CPU in the FHGW?

- A. Handling the transport functions of the FHGW and running the network operating system (NOS).
- B. Processing radio signals and converting them to digital data.
- C. Managing the connection between the O-DU and the O-RU.
- D. Providing power to the FHGW components.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-466`）

</details>

**1.5.1-85.** In an O-RAN integrated picocell, what layer(s) of the protocol stack are implemented by the NPU?

- A. Layer 1 (Physical)
- B. Layer 2 (Data Link) and Layer 3 (Network)
- C. Layer 4 (Transport) and above
- D. All layers

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-473`）

</details>

**1.5.1-86.** What is the maximum operating temperature for the O-RU7-2x?

- A. -40℃
- B. +55℃
- C. 95℃
- D. 106Kpa

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-483`）

</details>

**1.5.1-87.** What is the primary focus of Chapter 2 in the provided context?

- A. Deployment scenarios and white box base station architecture
- B. White box hardware architecture
- C. O-CU hardware architecture
- D. O-CU functional module description

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-486`）

</details>

**1.5.1-88.** Which of the following is an abbreviation for "Digital Pre-Distortion"?

- A. DPD
- B. DFE
- C. DDC
- D. DU

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-490`）

</details>

**1.5.1-89.** What is the maximum AC input current for the O-DU7-2 chassis power supply unit?

- A. 12A
- B. 15A
- C. 6.6A
- D. 41A

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-505`）

</details>

**1.5.1-90.** What does "O-CU-UP" stand for in the context of O-RAN?

- A. O-RAN Central Unit - User Plane
- B. O-RAN Control Unit - User Plane
- C. O-RAN Central Unit - Update Plane
- D. O-RAN Control Unit - Update Plane

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-509`）

</details>

**1.5.1-91.** Which of the following is NOT a deployment scenario for Open Radio Access Networks (O-RAN)?

- A. Greenfield deployments
- B. Brownfield deployments
- C. Hybrid deployments
- D. Private network deployments

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-514`）

</details>

**1.5.1-92.** Which of the following modules is NOT included in the resource requirement for a 4T4R O-RU8, as per the provided table?

- A. DDC
- B. ChFIR
- C. AGC
- D. UL_ChFIR

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-515`）

</details>

**1.5.1-93.** What is the maximum power consumption of a fully loaded O-RAN system with three populated PCIe slots?

- A. 600W
- B. 400W
- C. 800W
- D. 320W

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-526`）

</details>

**1.5.1-94.** In an O-RAN architecture, what is the primary function of the O-DU?

- A. To control the operation of O-RUs.
- B. To handle real-time aspects of control and user plane communication with the O-RU.
- C. To provide C-Plane and U-Plane over the LLS interface.
- D. To define the split options for the eNB/gNB functions.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-527`）

</details>

**1.5.1-95.** Which of the following is a key feature of Open Radio Access Networks (O-RAN) that allows for flexibility and interoperability?

- A. Standardized interfaces between network elements
- B. Proprietary protocols for communication
- C. Centralized control of all network functions
- D. Limited support for virtualization

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-534`）

</details>

**1.5.1-96.** Which of the following is a key aspect of O-RAN that facilitates flexibility and interoperability?

- A. The use of standardized interfaces for communication between network elements.
- B. The deployment of centralized network management systems.
- C. The adoption of proprietary protocols for data transmission.
- D. The integration of artificial intelligence for network optimization.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-543`）

</details>

**1.5.1-97.** What type of processor is used in the digital processing unit of an O-RAN system?

- A. Single-core, 32-bit
- B. Multi-core, 64-bit
- C. Dual-core, 16-bit
- D. Quad-core, 32-bit

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-550`）

</details>

**1.5.1-98.** Which of the following is NOT a consideration when operating Open Radio Access Networks (O-RAN) in non-ideal transport environments?

- A. HARQ (Hybrid Automatic Repeat Request)
- B. RACH (Random Access Channel)
- C. Bandwidth limitations
- D. Network slicing

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-553`）

</details>

**1.5.1-99.** What does the abbreviation "O-CU-UP" stand for in the context of O-RAN?

- A. O-RAN Central Unit – User Plane
- B. O-RAN Control Unit – User Plane
- C. O-RAN Central Unit – Upper Plane
- D. O-RAN Control Unit – Upper Plane

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-556`）

</details>

**1.5.1-100.** Which of the following interfaces is used for communication between the NPU and Radio signal processing unit in an O-RAN Fronthaul Gateway?

- A. Timing Interfaces
- B. Ethernet Interfaces
- C. NP Interfaces
- D. Radio Interfaces

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-565`）

</details>

**1.5.1-101.** What is the operating temperature range for the O-DU7-2 hardware system?

- A. -40°C to 70°C
- B. -5°C to +55°C
- C. 8% to 90%
- D. 5% to 95%

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-568`）

</details>

**1.5.1-102.** Which of the following is NOT a component of the O-RAN architecture as described in the context?

- A. Near-RT RIC
- B. O-RU
- C. E2-Node
- D. SMO / Non-RT RIC

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-569`）

</details>

**1.5.1-103.** What is the purpose of the clock synthesizer in an Open Radio Access Network (O-RAN)?

- A. To generate low jitter, high stability reference clocks.
- B. To amplify the signal strength of the radio waves.
- C. To filter out unwanted noise from the radio signal.
- D. To control the frequency of the radio waves.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-578`）

</details>

**1.5.1-104.** What is the primary focus of the O-RAN architecture in terms of RAN function design?

- A. Centralized control and management
- B. Open interfaces between logical nodes and physical partitions
- C. Enhanced security features
- D. Reduced latency for real-time applications

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-585`）

</details>

**1.5.1-105.** Which of the following factors can influence the density and frequency of O-RAN deployments?

- A. Indoor or outdoor deployment environment
- B. The number of users in the network
- C. The type of network equipment used
- D. The availability of skilled technicians

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-588`）

</details>

**1.5.1-106.** Which of the following components in an Open Radio Access Network (O-RAN) is responsible for the physical layer processing and radio frequency (RF) transmission?

- A. O-CU
- B. O-DU
- C. O-RU
- D. O-RAN.org

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-592`）

</details>

**1.5.1-107.** What is a key aspect of Open Radio Access Networks (O-RAN) that enables third-party vendors to develop and integrate their own components?

- A. Standardized interfaces
- B. Centralized control
- C. Proprietary software
- D. Closed-source hardware

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-594`）

</details>

**1.5.1-108.** Which of the following is NOT a logical node in an O-RAN architecture?

- A. O-CU
- B. O-DU
- C. O-RU
- D. O-SU

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-597`）

</details>

**1.5.1-109.** What are some key hardware components of the O-DU7-2x?

- A. Synchronization and Timing
- B. External Interface Ports
- C. Firmware
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-605`）

</details>

**1.5.1-110.** What is the primary function of the NPU in an O-RAN architecture?

- A. To provide high-speed data processing and routing for radio signals.
- B. To manage and control the O-RU's power consumption.
- C. To handle the authentication and authorization of user devices.
- D. To provide secure boot capabilities for the O-RU.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-610`）

</details>

**1.5.1-111.** What is a key element of the SAL requirements descriptor in Open Radio Access Networks (O-RAN)?

- A. Defining how to collect, analyze, and react to breaches of Service Availability Level (SAL) requirements.
- B. Specifying the type of radio interface used by the network.
- C. Describing the physical location of the O-RAN equipment.
- D. Defining the specific hardware used in the O-RAN network.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-611`）

</details>

**1.5.1-112.** What type of Ethernet port is used for management in an O-RAN system?

- A. 10GbE
- B. 1GbE
- C. 100GbE
- D. 40GbE

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-613`）

</details>

**1.5.1-113.** What is the primary purpose of the O-RAN Data Models?

- A. To define the relationships between O-RAN information entities.
- B. To provide a standardized way to represent and exchange information within an O-RAN network.
- C. To specify the attributes and classes used in O-RAN systems.
- D. To define the procedures for managing and controlling O-RAN network elements.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-628`）

</details>

**1.5.1-114.** What is the typical absolute phase noise of an Open Radio Access Network (O-RAN) device at a 10 MHz offset, measured in dBc/Hz?

- A. -148 dBc/Hz
- B. -157 dBc/Hz
- C. -158 dBc/Hz
- D. -113 dBc/Hz

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-644`）

</details>

**1.5.1-115.** What is the purpose of the O-DU in an O-RAN architecture?

- A. To manage the Radio Units (RU) and provide the interface to the core network.
- B. To handle the physical layer processing and transmit/receive radio signals.
- C. To provide a centralized management platform for the entire O-RAN system.
- D. To perform user data encryption and decryption.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-652`）

</details>

**1.5.1-116.** Which of the following standards defines the architecture of Open Radio Access Networks (O-RAN)?

- A. 3GPP TS 33.122: “Security aspects of Common API Framework (CAPIF) for 3GPP northbound APIs”
- B. O-RAN ALLIANCE TS: “O-RAN Architecture Description”
- C. 3GPP TS 23.501: “System Architecture for the 5G System (5GS); Stage 2”.
- D. RAIE Impacts on Near-RT RIC Architecture; discussion document, CMCC-2022.12.12-WG3-C-RAIE Impacts on RICARCH-v2.pptx

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-654`）

</details>

**1.5.1-117.** What is the first step in the process of resetting a shared O-RU?

- A. The host for the target shared O-RU is identified.
- B. The partner operator identifies the need to reset the target shared O-RU.
- C. The partner SMO identifies the proper host SMO for the target Shared O-RU.
- D. The partner shared operator SMO sends a request to the host SMO to initiate a coordinate reset of the target Shared O-RU.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-663`）

</details>

**1.5.1-118.** Which of the following is a class defined within the O-RAN context?

- A. SharedOruConfiguration
- B. SecondaryODuInfo
- C. CallHomeClientInfo
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-675`）

</details>

**1.5.1-119.** What is the primary function of the Application Server in the context of Open Radio Access Networks (O-RAN)?

- A. To establish A1 and E2 interface connectivity between the Near-RT RIC and the Non-RT RIC.
- B. To deploy and update AI/ML models in the Near-RT RIC.
- C. To generate Radio Access Network (RAN) side User Equipment (UE)-level policies.
- D. To convert policy to specific configuration parameter commands.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-678`）

</details>

**1.5.1-120.** Which of the following is a key component of an Open Radio Access Network (O-RAN) architecture that allows for the exchange of data and management information between different network elements?

- A. Data Model
- B. Notifications
- C. Error Handling
- D. HTTP based Push data API

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-696`）

</details>

**1.5.1-121.** Which of the following O-RAN components is responsible for the processing of user data and control signaling?

- A. O-RU
- B. O-DU
- C. FHM/Switch
- D. O-CU

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-704`）

</details>

**1.5.1-122.** Which of the following is a key component of an Open Radio Access Network (ORAN) architecture?

- A. Power Specifications
- B. RF Performance Specifications
- C. Hardware Design
- D. Antenna / Phased Array Reference Design

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-716`）

</details>

**1.5.1-123.** Which of the following components in an Open Radio Access Network (O-RAN) is responsible for the baseband processing and control functions?

- A. O-RU
- B. O-CU
- C. O-DU
- D. FHGWx

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-723`）

</details>

**1.5.1-124.** Which of the following components is NOT directly related to the O-DUx requirements according to the provided context?

- A. Mechanical Requirements
- B. Thermal Requirements
- C. Power Requirements
- D. Interface Requirements

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-743`）

</details>

**1.5.1-125.** What is the primary function of the O-RU and O-DU in the context of an Open Radio Access Network (O-RAN)?

- A. To handle user authentication and security.
- B. To manage and distribute network resources.
- C. To perform radio signal processing and data transmission.
- D. To provide network management and control functionalities.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-761`）

</details>

**1.5.1-126.** What are the supported mounting options for an FR1 Indoor Picocell?

- A. Above ceiling and on the wall
- B. On the ceiling and on the floor
- C. Only on the wall
- D. Only above ceiling

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-767`）

</details>

**1.5.1-127.** Which component is responsible for generating clocks in the ADI-based O-RU 8T8R system?

- A. ADRV904x
- B. AD9576BPZ
- C. MAX6581TG9A+
- D. AD9545BCPZ

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-783`）

</details>

**1.5.1-128.** Where is the O-RU7-2x hardware typically placed in an outdoor environment?

- A. Inside a secure data center
- B. On the rooftop, pole, or wall of a building
- C. Within a dedicated radio equipment shelter
- D. Underground in a shielded vault

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-787`）

</details>

**1.5.1-129.** Which of the following is NOT a benefit of O-RAN architecture for IIoT use cases?

- A. Ability to use external enrichment information from MEC servers, APPs servers, or industrial control platforms.
- B. Utilization of AI/ML methods to generate IIoT key techniques strategies.
- C. Improved performance for system and users.
- D. Enhanced security features for IIoT applications.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-794`）

</details>

**1.5.1-130.** What is a key aspect of Open Radio Access Networks (O-RAN) that allows for flexibility and vendor interoperability?

- A. A standardized interface between the Radio Unit (RU) and the Distributed Unit (DU)
- B. The use of proprietary software for network management
- C. The reliance on a single vendor for all network components
- D. The use of closed-source protocols for data transmission

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-799`）

</details>

**1.5.1-131.** Which of the following is a component of an O-RAN architecture?

- A. O-CU
- B. CU
- C. DU
- D. All of the above

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-808`）

</details>

**1.5.1-132.** Which of the following is a component of the O-DU portion of the hardware reference design?

- A. O-CU Firmware
- B. Synchronization and Timing
- C. Digital Processing Unit
- D. Accelerator Design 1

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-810`）

</details>

**1.5.1-133.** What is the primary focus of Chapter 2 in the provided document?

- A. Defining key terms and abbreviations related to O-RAN.
- B. Outlining the scope of the document and its intended audience.
- C. Describing hardware reference designs for O-RAN components.
- D. Providing a comprehensive overview of the O-RAN architecture.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-816`）

</details>

**1.5.1-134.** What are the recommended queue assignment methods for hardware platforms supporting O-RAN?

- A. Multiple prioritized expedited forwarding queues with CPRI/eCPRI separation.
- B. Multiple prioritized expedited forwarding queues with CPRI/eCPRI sharing the queue.
- C. A single queue with no prioritization.
- D. A single queue with prioritization based on traffic type.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-824`）

</details>

**1.5.1-135.** What is the minimum combined output power per port for a dual-band O-RU7-2x under all operating conditions?

- A. 40W
- B. 60W
- C. 80W
- D. 100W

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-859`）

</details>

**1.5.1-136.** What role is responsible for facilitating the execution of O-DU SW updates and coordinating interactions between SMO services, rApps, and RAN Nodes?

- A. O-RU Sharing Coordinator
- B. Shared O-RU Orchestration rApp
- C. SMO (Service Management Orchestrator)
- D. O-DU SW Update Manager

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-866`）

</details>

**1.5.1-137.** In an Open Radio Access Network (O-RAN) architecture, which of the following components is responsible for performing MAC functions?

- A. O-CU
- B. O-RU6
- C. O-DU6
- D. O-RU5

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-881`）

</details>

**1.5.1-138.** Which of the following is a key component of an Open Radio Access Network (O-RAN) that is responsible for the amplification of radio signals before transmission?

- A. FPGA
- B. LNA
- C. TR switch
- D. PA

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-908`）

</details>

**1.5.1-139.** What are the two main deployment scenarios for Open Radio Access Networks (O-RAN)?

- A. Split RAN Architecture and Integrated gNB-DU Architecture
- B. Cloud-native and Virtualized
- C. Centralized and Distributed
- D. Macro and Micro Cell

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-912`）

</details>

**1.5.1-140.** What are the standard RF interfaces for O-RAN?

- A. 2-pin panel mount connector and M-LOC cluster/multiport connector
- B. 4.3-10+ Low PIM RF connector and M-LOC cluster/multiport connector
- C. RJ45 connector and 2-pin panel mount connector
- D. RJ45 connector and 4.3-10+ Low PIM RF connector

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-917`）

</details>

**1.5.1-141.** Which of the following is NOT a key component of an Open Radio Access Network (O-RAN)?

- A. O-RU (Radio Unit)
- B. O-DU (Distributed Unit)
- C. O-CU (Centralized Unit)
- D. O-RAN.io (Open Source Software)

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-927`）

</details>

**1.5.1-142.** What is the name of the hardware reference design discussed in Chapter 2?

- A. O-CU Hardware Reference Design
- B. O-RU Hardware Reference Design
- C. O-DU Hardware Reference Design
- D. O-RAN Hardware Reference Design

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-946`）

</details>

**1.5.1-143.** Which of the following is NOT a specific requirement for the O-RU7-2x?

- A. Performance
- B. Interfaces
- C. Environmental and EMC
- D. Split Option Specific Requirements

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-952`）

</details>

**1.5.1-144.** Which of the following is NOT a typical power supply requirement for an Open Radio Access Network (O-RAN) equipment center?

- A. 208V AC
- B. 220V AC
- C. 110V DC
- D. -48V DC

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-963`）

</details>

**1.5.1-145.** Which of the following is NOT a typical deployment location for an Open Radio Access Network (O-RAN) base station?

- A. Small cell
- B. Indoor
- C. Outdoor
- D. Urban/Suburban

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-976`）

</details>

**1.5.1-146.** Which of the following is a feature of the Board Management Controller (BMC) in an Open Radio Access Network (ORAN) system?

- A. Power sequencing and reset
- B. I2C bus access
- C. FPGA configuration and control
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-979`）

</details>

**1.5.1-147.** What is the function of the digital processing unit in an O-RAN system?

- A. To perform frequency conversion in the digital domain.
- B. To implement DPD and CFR algorithms to improve power amplifier efficiency.
- C. To interface with the Low-PHY block and the RF processing unit.
- D. All of the above.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-991`）

</details>

**1.5.1-148.** In an O-RAN scenario, which of the following components is responsible for scheduling resources for different slices?

- A. O-RU
- B. vO-DU
- C. SMO
- D. CU-CP

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-995`）

</details>

**1.5.1-149.** Which of the following is NOT a key aspect considered in the O-RAN Hardware Reference Design?

- A. Power
- B. Thermal
- C. Environmental and Regulations
- D. Network Security

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-998`）

</details>

**1.5.1-150.** What is a key feature of Open Radio Access Networks (O-RAN) that allows for flexibility and innovation in network deployments?

- A. Centralized control of network resources
- B. Proprietary interfaces between network elements
- C. Standardized interfaces between network elements
- D. Limited use of virtualization technologies

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1003`）

</details>

**1.5.1-151.** What is the primary method of controlling the transceiver in an O-RAN system?

- A. SERDES
- B. SYSREF
- C. SPI or I2C
- D. GPIO

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1015`）

</details>

**1.5.1-152.** Which O-RAN component handles the radio frequency (RF) signal processing and transmission?

- A. O-CU
- B. O-DU
- C. O-RU
- D. nFAPI

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1018`）

</details>

**1.5.1-153.** What is the primary function of the RF Processing Unit in an O-RU8?

- A. Signal processing and amplification for radio transmission and reception
- B. Handling data transfer between the O-RU8 and the O-DU8
- C. Managing timing synchronization for the entire O-RAN system
- D. Power management and distribution for the O-RU8

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1029`）

</details>

**1.5.1-154.** Which of the following is NOT a key aspect of O-RAN's architecture, as described in the provided context?

- A. Resource structure and methods
- B. Service Operations
- C. Network slicing
- D. Data Model

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1040`）

</details>

**1.5.1-155.** What is a key principle of Open Radio Access Networks (O-RAN) in relation to hardware and software?

- A. Tight integration of hardware and software for optimal performance.
- B. Standardization of hardware and software to reduce vendor lock-in.
- C. Decoupling of hardware and software to enhance flexibility and choice.
- D. Centralization of hardware and software control for streamlined management.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1041`）

</details>

**1.5.1-156.** What is the primary role of the vO-CU in an Open Radio Access Network (O-RAN)?

- A. To handle user data and control plane functions for the radio network.
- B. To provide a physical connection between the O-RU and the 5G core.
- C. To manage and distribute radio resources across multiple O-RUs.
- D. To perform low-level radio signal processing and modulation.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1059`）

</details>

**1.5.1-157.** Which of the following is a potential use case for O-RAN technology?

- A. Signalling Storm Protection
- B. Congestion Prediction and Management
- C. Industrial IoT Optimization
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1067`）

</details>

**1.5.1-158.** Which of the following is the abbreviation for the O-RAN Central Unit – Control Plane?

- A. O-CU
- B. O-CU-CP
- C. O-CU-UP
- D. O-DU

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1075`）

</details>

**1.5.1-159.** What is the primary purpose of an Information Model in the context of O-RAN?

- A. To define the physical hardware components of a network.
- B. To specify the data semantics and relationships between objects in a chosen domain.
- C. To provide a detailed description of network protocols.
- D. To manage the configuration of individual network devices.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1096`）

</details>

**1.5.1-160.** What is a key feature of Open Radio Access Networks (O-RAN) that allows for flexibility and customization?

- A. Interoperability between different vendors' equipment
- B. Centralized control of network resources
- C. Proprietary software for network management
- D. Limited support for open-source technologies

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1103`）

</details>

**1.5.1-161.** What is the primary cooling method used for the O-RU7-2 unit?

- A. Active cooling
- B. Passive cooling
- C. Liquid cooling
- D. Air conditioning

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1118`）

</details>

**1.5.1-162.** Which of the following components is considered part of the O-RAN Radio Access Network (RAN) according to the provided context?

- A. Near-RT RIC
- B. O-CU
- C. O-DU
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1126`）

</details>

**1.5.1-163.** What is the function of the O-CU in an O-RAN network?

- A. Handles the upper layer (L2 and L3) functions.
- B. Provides the physical layer interface to the radio unit.
- C. Manages the connection between the O-DU and the core network.
- D. Connects the radio unit to the user equipment (UE).

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1131`）

</details>

**1.5.1-164.** What does O-DU stand for in the context of Open Radio Access Networks (ORAN)?

- A. Open Distributed Unit
- B. Open Data Unit
- C. Open Digital Unit
- D. Open Deployment Unit

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1132`）

</details>

**1.5.1-165.** Which of the following is NOT a key component of the O-RU reference design?

- A. Power Amplifier (PA)
- B. Low Noise Amplifier (LNA)
- C. Synchronization and Timing
- D. External Interface Ports

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1144`）

</details>

**1.5.1-166.** What is the primary function of the FPGA/Baseband processor in an O-RAN architecture?

- A. To manage the data flow between the radio and the core network.
- B. To generate and apply weights to the phased array antenna elements for beamforming.
- C. To handle user authentication and security protocols.
- D. To perform signal processing for channel estimation and equalization.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1152`）

</details>

**1.5.1-167.** What type of cable is used to connect the GNSS receiver to an external GNSS antenna in the reference design?

- A. Ethernet cable
- B. Fiber optic cable
- C. SMA cable
- D. Coaxial cable

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1176`）

</details>

**1.5.1-168.** In an O-RAN network, what is the primary function of the vO-DU?

- A. Process SRB and DRB
- B. Configure resource assignment for vO-DU and vO-CU
- C. Collect KPI data from the network
- D. Manage the creation of network slices

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1189`）

</details>

**1.5.1-169.** What are the typical mounting options for a Pico layer O-RAN cell?

- A. Rooftop, Side of Building (wall), Pole
- B. Rooftop, Side of Building (wall), Pole, Cabinet
- C. Rooftop, Side of Building (wall), Pole, Tower
- D. Rooftop, Side of Building (wall), Pole, Underground

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1199`）

</details>

**1.5.1-170.** Which of the following terms refers to the O-RAN component responsible for managing and controlling the radio access network?

- A. O-DU
- B. O-RU
- C. O-CU
- D. PNF

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1202`）

</details>

## 1.5.2 RAN 智慧控制器：Near-RT RIC、Non-RT RIC、xApp、rApp（128 題）

**1.5.2-1.** Which components are responsible for embedding intelligence in the O-RAN architecture?

- A. Non-RT RIC
- B. Near-RT RIC
- C. Both Non-RT RIC and Near-RT RIC
- D. O-Cloud

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-127`）

</details>

**1.5.2-2.** Which technology provides intelligent radio resource management and optimization using AI/ML models in open RAN? 

- A. RIC
- B. Near-RT RIC
- C. Non-RT RIC
- D. E2 interface
- E. A1 interface

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-316`）

</details>

**1.5.2-3.** What is the importance of orchestration in the execution of dApps?

- A. Orchestration determines the control and inference tasks executed via dApps
- B. Orchestration avoids conflicts between multiple O-RAN applications
- C. Orchestration satisfies operator intents and Service Level Agreements
- D. Orchestration distributes network intelligence
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-361`）

</details>

**1.5.2-4.** What is the purpose of the PCL (predictive closed loop) rAPP?

- A. To collect RAN statistics for each slice
- B. To provide programming capability for RAN components
- C. To configure O-Cloud
- D. To predict the future values of target parameters
- E. To prepare the RAN slice descriptor based on inference for configuring network resources

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-475`）

</details>

**1.5.2-5.** Which acronym represents a software tool used by a RAN Intelligent Controller (RIC) to manage network functions in near-real time? 

- A. SRAN
- B. RT
- C. RATS
- D. UPF
- E. xAPP

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-498`）

</details>

**1.5.2-6.** What is the role of the Near Real-Time RAN Intelligent Controller (Near-RT RIC)?

- A. To control the O-DUs through the E2 interface
- B. To serve as the user categorization module
- C. To compute the MAP vector for each O-RU
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-599`）

</details>

**1.5.2-7.** Which component is responsible for collecting RAN (Radio Access Network) statistics for each slice?

- A. AI Server
- B. Non-RT RIC
- C. O-RAN SC
- D. ONAP
- E. Virtual Event Streaming

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-849`）

</details>

**1.5.2-8.** What does the xApp located in the Near-RT RIC control?

- A. The O-DU antennas
- B. The Inter-O-DU coordination interface
- C. The user categorization
- D. The fronthaul interface
- E. The digital beamforming

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1056`）

</details>

**1.5.2-9.** How can dApps receive Enrichment Information from the near-RT ran?

- A. Through the Southbound Interfaces
- B. Through the Northbound Interfaces
- C. Through the Orchestrator
- D. Through the dApp Controller and Monitor
- E. Through the Conflict Mitigation system

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1333`）

</details>

**1.5.2-10.** What type of conflict can happen between Near-RT RICs (RAN Intelligent Controllers)?

- A. Implicit conflicts
- B. Indirect conflicts
- C. Direct conflicts
- D. Explicit conflicts
- E. Parallel conflicts

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1470`）

</details>

**1.5.2-11.** What types of decisions does a non real-time control loop in O-RAN make?

- A. Decisions affecting up to thousands of User Equipments
- B. Decisions based on user-session aggregated data
- C. Decisions impacting the near real-time ran
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1536`）

</details>

**1.5.2-12.** How does the Direct Conflict Detection component detect conflicts?

- A. By exchanging information between Near-RT RICs
- B. By analyzing performance monitoring data
- C. By analyzing control messages
- D. By configuring the O-RAN infrastructure
- E. By redirecting control messages

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1820`）

</details>

**1.5.2-13.** Where are the dApps executed in the O-RAN architecture?

- A. At the Central Unit
- B. At the Distributed Unit
- C. At the Radio Unit
- D. At the near-RT ran
- E. At the non-RT ran

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-1991`）

</details>

**1.5.2-14.** What is the function of xAPPs?

- A. To collect RAN statistics for each slice
- B. To provide programming capability for RAN components
- C. To predict the future values of target parameters
- D. To transport and process data from any source to any target
- E. To configure O-Cloud

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2335`）

</details>

**1.5.2-15.** Which RIC layer has a control frequency below 1 second? 

- A. RIC
- B. Near-RT RIC
- C. Non-RT RIC
- D. E2 interface
- E. A1 interface

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2930`）

</details>

**1.5.2-16.** What is the function of the near-RT RIC (RAN Intelligent Controller) in the O-RAN architecture?

- A. To connect the CU to the DUs
- B. To handle communications between the multi-RAT O-CU and the AMF and UPF of the 5G core network
- C. To enable control and optimization of the protocol stack functions of the RAN through xApps
- D. To enable AI-related parameter exchange between the non-RT and near-RT RICs
- E. To forward collected measurements from the O-DU and O-CU to the near-RT RIC and send configuration commands back

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3609`）

</details>

**1.5.2-17.** What is the timescale of a non real-time control loop in O-RAN?

- A. At least one second
- B. Between 10 ms and 1 s
- C. Sub-10 ms
- D. Unknown

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3640`）

</details>

**1.5.2-18.** What workflow is supported in O-RAN networks for Artificial Intelligence/Machine Learning?

- A. Streaming telemetry from the Radio Access Network
- B. Deploying control actions and policies
- C. Integrating intelligent, data-driven closed-loop control
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4322`）

</details>

**1.5.2-19.** How can dApps access and share the physical resources in the Radio Access Network nodes?

- A. Through the Southbound Interfaces
- B. Through the Northbound Interfaces
- C. Through the Orchestrator
- D. Through the dApp Controller and Monitor
- E. Through the Conflict Mitigation system

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4733`）

</details>

**1.5.2-20.** Where is the dApp Controller and Monitor component hosted?

- A. In the Central Unit
- B. In the Distributed Unit
- C. In the Radio Unit
- D. In the near-RT ran
- E. In the non-RT ran

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4930`）

</details>

**1.5.2-21.** What does the O-RAN architecture propose for conflict mitigation between dApps, rApps, and xApps?

- A. Pre-action conflict resolution
- B. Post-action verification
- C. Both pre-action conflict resolution and post-action verification
- D. Implicit conflict detection
- E. Explicit conflict detection

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-5778`）

</details>

**1.5.2-22.** What is the function of the Message Infrastructure in CMF (conflict mitigation framework)?

- A. To detect conflicts between xApps
- B. To optimize network performance
- C. To configure the O-RAN infrastructure
- D. To redirect control messages from xApps
- E. To store data in the database

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5842`）

</details>

**1.5.2-23.** What is the difference between RAN (Radio Access Network) control in SON (Self-Organized Networks) and O-RAN?

- A. SON functions perform RAN control locally, while RAN control in O-RAN is executed centrally with RICs
- B. SON functions are more scalable than RICs in O-RAN
- C. SON functions are more effective in conflict mitigation than RICs in O-RAN
- D. SON functions cannot modify network behavior, while RICs in O-RAN can
- E. SON functions and RICs have similar approaches to conflict mitigation

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6513`）

</details>

**1.5.2-24.** What are the two main components to embed intelligence in O-RAN architecture?

- A. Non-RT RIC and Near-RT RIC
- B. E2 Nodes and O-Cloud
- C. Non-RT RIC and E2 Nodes
- D. Near-RT RIC and AI Server
- E. O-Cloud and AI Server

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6589`）

</details>

**1.5.2-25.** What are rApps and xApps in O-RAN?

- A. Components that optimize energy consumption in O-RAN.
- B. Components that influence the RAN operation.
- C. Components that maximize Quality of Service (QoS) in O-RAN.
- D. Components that manage radio resources in O-RAN.
- E. Components that run applications to influence the network operation.

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-7293`）

</details>

**1.5.2-26.** At what timescale does the near-RT control loop operate in O-RAN?

- A. Less than 1 ms
- B. Between 1 s and 10 ms
- C. Between 10 ms and 1 s
- D. More than 1 s
- E. Exactly 1 s

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7325`）

</details>

**1.5.2-27.** What are the three types of conflicts that can happen between xApps in O-RAN?

- A. Direct conflicts, indirect conflicts, and explicit conflicts
- B. Direct conflicts, indirect conflicts, and implicit conflicts
- C. Direct conflicts, parallel conflicts, and implicit conflicts
- D. Indirect conflicts, parallel conflicts, and implicit conflicts
- E. Parallel conflicts, indirect conflicts, and explicit conflicts

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-7845`）

</details>

**1.5.2-28.** What is the name of the protocol stack used in O-RAN for R1 services?

- A. REST based protocol stack
- B. TCP/IP
- C. HTTP
- D. gRPC

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-12`）

</details>

**1.5.2-29.** What type of information is expected to be exposed by Near-RT RIC to the application server, according to the provided text?

- A. UE positioning results, including location coordinates, coordinate system, position methods used, failure cause, and achieved location QoS accuracy.
- B. Radio performance analytics data.
- C. Velocity estimation.
- D. Massive SU/MU-MIMO Grouping Optimization.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-43`）

</details>

**1.5.2-30.** What is the purpose of the "detail" attribute within the ProblemDetails structure in O-RAN R1?

- A. To provide a URI reference that identifies the problem type.
- B. To provide a human-readable summary of the problem.
- C. To provide a human-readable explanation of the problem.
- D. To identify the specific occurrence of the problem.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-56`）

</details>

頁次：**1**　[2](1-5-gsma-2.md)　[3](1-5-gsma-3.md)　[4](1-5-gsma-4.md)　[5](1-5-gsma-5.md)
