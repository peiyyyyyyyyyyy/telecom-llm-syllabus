# 1.5 開放與虛擬化　GSMA 練習題（909 題）（第 5／5 頁）

所屬：[1.5 開放與虛擬化](1-5.md)

只收 GSMA 訓練題；不含驗證集與測試集，並已去除和驗證／測試題相同或相似、重複、標註衝突的題目。題目依小節歸類（抽查正確率約 95%）。

頁次：[1](1-5-gsma-1.md)　[2](1-5-gsma-2.md)　[3](1-5-gsma-3.md)　[4](1-5-gsma-4.md)　**5**

## 1.5.5 雲端平台：O-Cloud 與雲原生網路功能（89 題）（續）

**1.5.5-57.** What are the two main parts of the DMS in O-RAN?

- A. NF Deployment management and Resource management of NF Deployments
- B. Network Function Virtualization (NFV) and Containerized Infrastructure Management (CIM)
- C. Virtualized resources and containerized workloads
- D. Northbound interfaces and Southbound interfaces

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-614`）

</details>

**1.5.5-58.** Which API call is used to delete a threshold associated with an NF Deployment in the O2dms API profile?

- A. <<O2dms>> GET .../threshold/{thresholdId}
- B. <<O2dms>> DELETE .../threshold/{thresholdId}
- C. <<O2dms>> PUT .../threshold/{thresholdId}
- D. <<O2dms>> POST .../threshold/{thresholdId}

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-629`）

</details>

**1.5.5-59.** What is the primary purpose of the O2 Test?

- A. To validate the O-Cloud's compliance with the latest O2 Interface Specifications.
- B. To verify the functionality of the SMO (Service Management and Orchestration) system.
- C. To test the performance of O-RAN interfaces.
- D. To assess the security of the O-Cloud.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-635`）

</details>

**1.5.5-60.** Which of the following is NOT a key requirement for O-Cloud architecture?

- A. Hardware Requirements
- B. Operating System Requirements
- C. Cloud Platform Runtime Requirements
- D. User Interface Design

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-659`）

</details>

**1.5.5-61.** What is the purpose of the `initAal` function in the AALI-C-App API?

- A. To configure the AAL Application.
- B. To initialize the AAL Implementation.
- C. To allocate buffers for receive operations.
- D. To activate the ODU.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-669`）

</details>

**1.5.5-62.** Which of the following represents the Resource URI for accessing the Alarm List in the O2ims-infrastructureMonitoring API?

- A. {apiRoot}/o2ims-infrastructureMonitoring/{apiMajorVersion}/alarms
- B. {apiRoot}/o2ims-infrastructureMonitoring/{apiMinorVersion}/alarms
- C. {apiRoot}/o2ims-infrastructureMonitoring/alarms
- D. {apiRoot}/o2ims-infrastructureMonitoring/alarms/{apiMajorVersion}

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-681`）

</details>

**1.5.5-63.** What is the primary difference between synchronous and asynchronous receive buffer modes in O-RAN?

- A. Synchronous mode uses pre-allocated buffers, while asynchronous mode allocates buffers on demand.
- B. Synchronous mode requires a callback function, while asynchronous mode does not.
- C. Synchronous mode is faster for large data transfers, while asynchronous mode is more efficient for smaller transfers.
- D. Synchronous mode is used for real-time applications, while asynchronous mode is used for non-real-time applications.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-694`）

</details>

**1.5.5-64.** What is the primary function of the GET method with the subscriptionId variable in the O-RAN.WG6.O-Cloud Notification API?

- A. Creating a new subscription resource object.
- B. Modifying properties of an existing subscription resource object.
- C. Retrieving an individual subscription resource object and its associated properties.
- D. Deleting an existing subscription resource object.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-695`）

</details>

**1.5.5-65.** What is a Cloud Site in the context of Open Radio Access Networks (O-RAN)?

- A. A virtualized environment that hosts O-RAN functions.
- B. A physical location containing O-RAN infrastructure equipment.
- C. A software-defined network that connects O-RAN components.
- D. A centralized control point for managing O-RAN resources.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-726`）

</details>

**1.5.5-66.** Which of the following is NOT a type of O-Cloud Node Cluster defined in the context?

- A. Bare Metal Container Cluster
- B. VM-based Container Cluster
- C. Virtual Machine Cluster
- D. Cloud Native Container Cluster

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-755`）

</details>

**1.5.5-67.** Which of the following is NOT a requirement for the HW Accelerator Manager (HAM) to participate in resource management and AALI-C-Mgmt procedures?

- A. Successful registration with the IMS.
- B. Configuration of the HAM with the IMS service endpoint.
- C. Installation and configuration of the HAM.
- D. Successful communication with the App through the AALI-C-Mgmt API.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-786`）

</details>

**1.5.5-68.** Which of the following is NOT a function accelerated by the AAL_DOWNLINK_High-PHY Profile for PDSCH TBs?

- A. TB CRC attachment
- B. Channel Estimation
- C. LDPC encoding
- D. Rate matching

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-797`）

</details>

**1.5.5-69.** Which of the following is a physical location that houses Cloud Infrastructure resources, potentially including both O-Clouds and non-O-Cloud resources?

- A. Central Cloud
- B. Edge Cloud
- C. Cloud Site
- D. CIDR

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-826`）

</details>

**1.5.5-70.** What mechanism is used to customize VM compute resources at boot time for NF Deployment units based on VMs?

- A. "boot data" defined in the NF Deployment descriptor
- B. MCIOPS configuration files
- C. Kubernetes® ConfigMaps
- D. Helm® Charts

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-857`）

</details>

**1.5.5-71.** What is an O-Cloud Attachment Circuit (OCAC)?

- A. A physical link connecting O-Cloud Sites.
- B. A logical connection allowing Site Networks within an O-Cloud Site to connect to external networks.
- C. A software component responsible for managing O-Cloud resources.
- D. A type of network protocol used for communication within an O-Cloud.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-861`）

</details>

**1.5.5-72.** Which of the following is NOT a supported event type for a cloud instance in Open Radio Access Networks (O-RAN)?

- A. Inventory Change
- B. Configuration Change
- C. Software Update
- D. Heartbeat

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-875`）

</details>

**1.5.5-73.** Which of the following hardware acceleration options can be used in Open Radio Access Networks (O-RAN)?

- A. Field Programmable Gate Arrays (FPGAs)
- B. Graphical Processing Units (GPUs)
- C. System on Chip (SoC)
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-895`）

</details>

**1.5.5-74.** What is an O-Cloud?

- A. A physical location where O-RAN components are housed.
- B. A collection of O-RAN resources, pools, and services managed as a single entity.
- C. A type of network fabric used to connect O-RAN components.
- D. A software application that manages O-RAN deployments.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-906`）

</details>

**1.5.5-75.** What is a possible configuration for an O-Cloud Compute Resource Pool where an O-Cloud Site Network Fabric is not present?

- A. The O-Cloud Compute Resources are connected to the O-RU through a front haul connection and to an external backhaul or midhaul transport.
- B. The O-Cloud Compute Resources are connected to the O-RU through a dedicated high-speed fiber link.
- C. The O-Cloud Compute Resources are connected to the O-RU through a wireless connection.
- D. The O-Cloud Compute Resources are connected to the O-RU through a shared Ethernet network.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-911`）

</details>

**1.5.5-76.** What is the definition of a "Cloudified NF" in the context of Open Radio Access Networks (O-RAN)?

- A. A software deployment on O-Cloud resources that realizes a RAN Network Function.
- B. A RAN Network Function software deployed in the O-Cloud via one or more NF Deployments.
- C. A physical network element that connects the RAN to the core network.
- D. A grouping of O-RAN related functionality in a tiered cloud architecture.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-918`）

</details>

**1.5.5-77.** What is the primary reason for ensuring that containers/VMs and their associated hardware accelerators/I/O devices are placed within the same NUMA region?

- A. To optimize data transfer speeds and minimize latency.
- B. To improve the security of the application by isolating it from other processes.
- C. To increase the overall processing power of the system by distributing the workload across multiple cores.
- D. To ensure compatibility between different hardware components.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-970`）

</details>

**1.5.5-78.** What is a Compute Node in the context of Open Radio Access Networks (O-RAN)?

- A. A software program that manages and abstracts computer system hardware and software resources.
- B. A computer system with a managed operating system that is network connected and can be represented as an O-Cloud Node.
- C. A type of operating system that allows for the creation of multiple virtual machines.
- D. A type of operating system that supports containers for resource isolation and management.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-977`）

</details>

**1.5.5-79.** What type of network interface is provided on the O-RAN accelerator hardware for connecting to FPGA2?

- A. 2xSFP28 optical interfaces
- B. PCIe Gen 3 x16 with Bifurcation
- C. Micro USB
- D. SMA for 1 PPS

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-990`）

</details>

**1.5.5-80.** Which of the following is NOT a valid format for a Cloudified NF Registration notification?

- A. SDO O1 format
- B. O-RAN-specified o1NotifyCloudNFRegistration notification
- C. VES O1 format
- D. 5G System Information Block Type 1

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1011`）

</details>

**1.5.5-81.** What is the O-Cloud Platform?

- A. A set of hardware and software components providing cloud computing capabilities for RAN network functions.
- B. A specific type of server used for running O-RAN applications.
- C. A network protocol designed for high-speed communication in O-RAN deployments.
- D. A software framework for managing and orchestrating O-RAN network functions.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1012`）

</details>

**1.5.5-82.** What is the primary interface used for an operator to initiate Application-level healing within an O-RAN O-Cloud?

- A. O2dms
- B. O1
- C. O-Cloud internal deployment management functions
- D. NF Deployment level healing

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1013`）

</details>

**1.5.5-83.** What are the two types of resources used to realize NF Deployments in O-RAN?

- A. Virtualized resources and containerized workloads
- B. Physical resources and virtualized resources
- C. Containerized workloads and physical resources
- D. Virtualized resources and physical resources

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1034`）

</details>

**1.5.5-84.** What is the purpose of the o1NotifyCloudNFRegistration event in the context of O-RAN Cloudified NF Registration?

- A. To inform the Cloudified NF Registration MnS Consumer that a new Cloudified NF Registration MnS Producer is ready to be managed.
- B. To request a subscription for the Cloudified NF Registration MnS Producer from the Cloudified NF Registration MnS Consumer.
- C. To initiate a NETCONF session between the Cloudified NF Registration MnS Producer and Consumer.
- D. To trigger the final configuration and management of the Cloudified NF Registration MnS Producer by the Cloudified NF Registration MnS Consumer.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1066`）

</details>

**1.5.5-85.** Which of the following is NOT a capability that should be reported to the application regarding the AAL_DOWNLINK_High-PHY profile?

- A. Acceleration of channel functionality
- B. Interaction acceleration
- C. Network slicing capabilities
- D. Reporting of additional capabilities by the AALI implementation

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1069`）

</details>

**1.5.5-86.** What is an "O-Cloud" in the context of O-RAN?

- A. A collection of O-Cloud Resource Pools at one or more locations, managing Nodes and Deployments.
- B. A type of radio access technology used in 5G networks.
- C. A software framework for managing virtualized network functions.
- D. A physical infrastructure for deploying O-RAN components.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1074`）

</details>

**1.5.5-87.** What is the definition of an "Accelerated Function (AF)" in the context of O-RAN?

- A. A specialized hardware implementation that offloads processing from applications.
- B. A representation of a workload building block processed by an accelerator on behalf of an AAL Application.
- C. A common set of interfaces used for interaction with different types of hardware accelerators.
- D. A workload that can offload Accelerated Functions to AAL-LPUs.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1124`）

</details>

**1.5.5-88.** Which of the following APIs is **NOT** tested for unsupported method functionality in the provided scenario?

- A. Resource Pools
- B. Deployment Managers
- C. O-Cloud
- D. Alarm Subscriptions

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1155`）

</details>

**1.5.5-89.** What HTTP method is supported for the Alarm Record resource in an O-RAN O-Cloud?

- A. GET
- B. PUT
- C. PATCH
- D. DELETE

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1170`）

</details>

## 1.5.6 軟體定義網路（SDN）（36 題）

**1.5.6-1.** What does the RAT (Radio Access Technology) Agnostic Control Functions (RACFs) interface with?

- A. Flow Controller and RSCFs
- B. PCRF and UDF
- C. MLMF and SMF
- D. Service-based interfaces and RAT Specific Control Functions (RSCFs)
- E. Data plane entities and IP addresses

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7070`）

</details>

**1.5.6-2.** What is OpenDaylight?

- A. An open source cloud computing platform
- B. A networking protocol used in SDN
- C. A virtualization technology used in NFV
- D. A community-led and industry-supported open source framework for SDN and NFV
- E. A software-defined networking platform for data centers

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-214`）

</details>

**1.5.6-3.** What is the key challenge for SDON (Software Defined Optical Network) virtualization?

- A. High costs of optical infrastructures
- B. Creating multiple VONs over the optical network infrastructure
- C. Amortizing costs over relatively few users
- D. Accounting for the specific optical transmission and signal propagation characteristics

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-459`）

</details>

**1.5.6-4.** What is the relationship between SDN (Software Defined Networking) and NFV (Network Function Virtualization)?

- A. SDN and NFV are unrelated concepts
- B. SDN and NFV have similar goals and can enhance each other
- C. NFV replaces SDN in network management
- D. SDN requires NFV to operate efficiently
- E. SDN and NFV compete with each other in the networking industry

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-966`）

</details>

**1.5.6-5.** What are the two key 5G technologies that have moved modern communication networks towards software-based virtual networks?

- A. Software-Defined Networking (SDN) and Network Functions Virtualization (NFV)
- B. Radio Access Interfaces and Internet of Things
- C. Content caching and wireless power transfer
- D. Sensing and data collection
- E. Communications and content caching

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1166`）

</details>

**1.5.6-6.** What are the three architectural principles of Software Defined Networking (SDN)?

- A. Separation of control plane and data plane functions, centralization of control, and programmability of network functions.
- B. Separation of control plane and data plane functions, decentralization of control, and programmability of network functions.
- C. Combination of control plane and data plane functions, centralization of control, and programmability of network functions.
- D. Combination of control plane and data plane functions, decentralization of control, and programmability of network functions.
- E. Decentralization of control plane functions, centralization of data plane functions, and programmability of network functions.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1817`）

</details>

**1.5.6-7.** Which architectural framework uses microservices to decompose the SDN (software defined networking) controller and implement it as a set of distributed components?

- A. ETSI SDN-NFV MANO
- B. ETSI GANA
- C. 3GPP-ETSI MEC Architecture
- D. Microservices-based SDN Controller
- E. Multi-Agent System (MAS)

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1822`）

</details>

**1.5.6-8.** What are the three generally accepted layers of SDN (Software Defined Networking) abstraction?

- A. Infrastructure layer, control layer, and application layer.
- B. Data plane layer, control plane layer, and application plane layer.
- C. Software layer, hardware layer, and application layer.
- D. Physical layer, logical layer, and virtual layer.
- E. NorthBound Interface layer, SouthBound Interface layer, and EastBound Interface layer.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1958`）

</details>

**1.5.6-9.** What is the interface between the application layer and the control layer called?

- A. SouthBound Interface (SBI).
- B. NorthBound Interface (NBI).
- C. EastBound Interface (EBI).
- D. WestBound Interface (WBI).
- E. Control Plane Interface (CPI).

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2432`）

</details>

**1.5.6-10.** What is the purpose of the infrastructure layer in the system architecture?

- A. To provide smart Network Service, compute, and resource orchestration capabilities
- B. To manage the underlying mobile infrastructure and orchestrate the resources
- C. To provide a common abstraction view of the managed resources to the Service & Computation Orchestrator
- D. To support enhanced security features
- E. To provide reprogrammable mechanisms and algorithms

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2727`）

</details>

**1.5.6-11.** What technique is used to synchronize the views of multiple controllers in the distributed control plane?

- A. Optimal placement of multiple controllers
- B. Dynamic control traffic balancing
- C. Distributed controller consensus
- D. Multi-user detection for downlink receivers
- E. Anticipatory mobility management and intelligent resource allocation

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2754`）

</details>

**1.5.6-12.** Which network architecture plays an important role in network management due to its flexibility and programmability?

- A. Star topology
- B. Mesh topology
- C. Hybrid hierarchical topology
- D. SDN-based network
- E. Cluster-based network

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2811`）

</details>

**1.5.6-13.** What is the tradeoff between control-plane overheads and user-plane QoS (Quality-of-Service) in SDN (Software-Defined Network) architectures?

- A. High control-plane overheads and low user-plane QoS
- B. Low control-plane overheads and high user-plane QoS
- C. High control-plane overheads and high user-plane QoS
- D. Low control-plane overheads and low user-plane QoS
- E. Equal control-plane overheads and user-plane QoS

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3343`）

</details>

**1.5.6-14.** What is the benefit of SDN (software defined networking) in C-RANs (cloud radio access networks)?

- A. Higher bit rates
- B. Control and data decoupling
- C. Seamless coverage
- D. Load sharing
- E. All of the above

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-3351`）

</details>

**1.5.6-15.** What is Software Defined Networking (SDN)?

- A. A network concept that proposes to use virtualization technologies to manage core networking functions using a software based approach
- B. A physical network infrastructure that provides virtualization capabilities for network functions
- C. A network architecture that replaces physical network functions with virtual ones
- D. A network architecture that transfers control functionality to software-based entities and uses commodity servers and switches over proprietary appliances

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3523`）

</details>

**1.5.6-16.** Which architecture decomposed the SDN (software-defined networking) controller into microservices components that can run in a distributed fashion?

- A. ETSI GANA
- B. ETSI SDN-NFV MANO
- C. 3GPP-ETSI MEC Architecture
- D. Microservices-based SDN Controller
- E. Multi-Agent System

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3740`）

</details>

**1.5.6-17.** What is SDWN in the context of network slicing based 5G systems?

- A. A distributed edge cloud
- B. A hierarchical control plane
- C. A software-defined wireless network
- D. A unified interface protocol
- E. An open interface for signaling interactions

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3907`）

</details>

**1.5.6-18.** What do the data plane and control plane consist of in future softwarized communication networks?

- A. Data centers and distributed databases
- B. Virtual network functions (VNFs) and SDN controllers
- C. Hypervisors and network nodes
- D. Machine learning algorithms and resource mapping
- E. Big data and general-purpose hardware

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4656`）

</details>

**1.5.6-19.** What is the purpose of the control layer in SDN (Software Defined Networking)?

- A. It abstracts the data forwarding plane from the control plane
- B. It provides network management functionalities
- C. It is responsible for programming the network elements
- D. It connects the SDN architecture with external network architectures

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4659`）

</details>

**1.5.6-20.** Which trend involves the virtualization of optical resources and the convergence of network operators and content providers?

- A. Disaggregated networks
- B. Network slicing
- C. Software-Defined Metro Network (SDMN)
- D. Elastic Transmission System
- E. Artificial Intelligence for optical data transport

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4850`）

</details>

**1.5.6-21.** What is the advantage of combining SDN (Software Defined Networking) and NFV (Network Function Virtualization) in a networking solution?

- A. Increased network performance
- B. Simplified network management
- C. Reduced operational complexity
- D. Extend the life of existing infrastructure hardware
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4914`）

</details>

**1.5.6-22.** How can the overhead load and delays be distributed within a network?

- A. By improving processing capacity of network nodes
- B. By increasing the transmission capacity
- C. By reducing the propagation latency
- D. By optimizing the data center structure
- E. By having distributed SDN controllers

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5264`）

</details>

**1.5.6-23.** Which consortium led the development of software-defined networking (SDN)?

- A. ITU
- B. ONF
- C. ETSI
- D. 3GPP
- E. ITU-T

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5267`）

</details>

**1.5.6-24.** How can SDN (software defined networking) enable the interoperation between cloud and fog computing?

- A. By providing a logical controller and programmable interfaces
- B. By dynamically steering user requests among fogs and the cloud
- C. By unleashing the full potential of local pooling resources
- D. By improving network operators' management capabilities
- E. All of the above

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5283`）

</details>

**1.5.6-25.** Which architectural framework uses gRPC protocol family for microservices intercommunication?

- A. ETSI GANA
- B. ETSI SDN-NFV MANO
- C. 3GPP-ETSI MEC Architecture
- D. Microservices-based SDN Controller
- E. Multi-Agent System

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5310`）

</details>

**1.5.6-26.** What are the key principles of Software Defined Networking (SDN)?

- A. Separation of data plane resources from control and management functions
- B. Centralization of the management-control functions
- C. Programmabillity of network functionality through device-neutral and vendor-neutral abstractions and APIs
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5984`）

</details>

**1.5.6-27.** What is the purpose of the application layer in SDN (Software Defined Networking)?

- A. It provides network management functionalities
- B. It connects the SDN architecture with external network architectures
- C. It abstracts the data forwarding plane from the control plane
- D. It comprises network applications and services

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6229`）

</details>

**1.5.6-28.** Which technology enables dynamic resource allocation, mobility management, and cooperative communications in C-RAN?

- A. Ultra-dense small cells
- B. Network Function Virtualization (NFV)
- C. Cloud Radio Access Network (C-RAN)
- D. Massive MIMO
- E. Software-Defined Networking (SDN)

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6542`）

</details>

**1.5.6-29.** What is the interface between the control layer and the infrastructure layer called?

- A. WestBound Interface (WBI).
- B. NorthBound Interface (NBI).
- C. EastBound Interface (EBI).
- D. SouthBound Interface (SBI).
- E. Control Plane Interface (CPI).

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6597`）

</details>

**1.5.6-30.** What is the role of SDN (software defined networking) controllers in handover management in network slicing based 5G systems?

- A. To replace physical network elements with logical servers
- B. To handle handovers in a single network slice
- C. To support centralized control plane handover decisions
- D. To simplify multi-RAT cooperation
- E. To cooperatively carry out handover management in complex application scenarios

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6692`）

</details>

**1.5.6-31.** What is the role of the RAT (Radio Access Technology) Specific Control Functions (RSCFs)?

- A. Perform device configuration, information broadcast, resource allocation, and QoS management
- B. Allocate resources and establish paths for traffic flows
- C. Analyze individual traffic flows and associate QoS attributes with them
- D. Manage distributed SDN controllers in each Fog element
- E. Provide an abstract view of the underlying radio access network to the higher level control entities

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-6857`）

</details>

**1.5.6-32.** What is the purpose of SDN (software defined networking) in H-CRANs (heterogeneous cloud radio access networks)?

- A. To simplify network construction and operational costs
- B. To provide gigabit data rate service
- C. To manage RRHs
- D. To provide cloud computing services
- E. To improve the intelligences and self-organizing capabilities

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6867`）

</details>

**1.5.6-33.** Which architecture provides a unified architecture combining SDN (software-defined networking) and NFV (network function virtualization) characteristics?

- A. ETSI GANA
- B. ETSI SDN-NFV MANO
- C. 3GPP-ETSI MEC Architecture
- D. Microservices-based SDN Controller
- E. Multi-Agent System

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6910`）

</details>

**1.5.6-34.** What is the advantage of using SDN (software defined network) in the EPC (evolved packet core)?

- A. SDN can bypass several protocol layers in the EPC
- B. SDN can improve the scalability of controllers in the EPC
- C. SDN can decrease the latency in the EPC
- D. SDN can increase the flexibility of flow distribution in the EPC
- E. SDN can ensure seamless operation in the EPC

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7025`）

</details>

**1.5.6-35.** What is one advantage of using distributed SDN (Software Defined Networking) as a management framework for the CUs (Central Units)?

- A. It allows for easy control of the network behavior
- B. It requires a detailed knowledge of the managing software of the switches
- C. It requires a wired fronthaul
- D. It is not scalable for a wide deployment

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7943`）

</details>

**1.5.6-36.** What is the main difference between OpenConfig and OpenROADM in terms of ROADM system management?

- A. OpenConfig assumes a vendor-specific controller for ROADM switches, while OpenROADM uses a more open and vendor-agnostic approach.
- B. OpenConfig is designed for smaller, simpler ROADM systems, while OpenROADM is suitable for larger, more complex networks.
- C. OpenConfig focuses on optical layer management, while OpenROADM handles both optical and electrical layers.
- D. OpenConfig is a newer technology, while OpenROADM is a more established standard.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-658`）

</details>

## 1.5.7 E2 服務模型：KPM、RC（40 題）

**1.5.7-1.** Which of the following is NOT a possible reason for a RIC Request failure as defined in the provided code?

- A. RAN Function ID Invalid
- B. Control Timer Expired
- C. Transport Resource Unavailable
- D. Excessive Actions

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-4`）

</details>

**1.5.7-2.** When the Near-RT RIC executes a control action, what does it need to specify in order to control RAN configuration structures?

- A. The specific RAN function that needs to be controlled.
- B. The E2 node responsible for managing the RAN configuration structures.
- C. The specific instances of the RAN configuration structures being controlled.
- D. The type of control action being executed (e.g., add, delete, modify).

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-10`）

</details>

**1.5.7-3.** Which of the following is NOT a format for E2SM-RC-EventTrigger?

- A. E2SM-RC-EventTrigger-Format1
- B. E2SM-RC-EventTrigger-Format2
- C. E2SM-RC-EventTrigger-Format3
- D. E2SM-RC-EventTrigger-Format4

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-33`）

</details>

**1.5.7-4.** Which of the following identifies a specific RAN function within an O-RAN network?

- A. id-E2connectionSetup
- B. id-GlobalRIC-ID
- C. id-RANfunctionID
- D. id-RICactionID

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-55`）

</details>

**1.5.7-5.** What is the primary purpose of the test case described in the provided context?

- A. To evaluate the interoperability between Near-RT RIC and E2 Node for O-RAN-E2SM-KPM.
- B. To test the functionality of E2AP functional procedures for E2SM-KPM.
- C. To validate the performance of the E2 Node in handling RIC subscription and indication procedures.
- D. To assess the security of the E2 interface between the Near-RT RIC and E2 Node.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-99`）

</details>

**1.5.7-6.** What is the main purpose of the test case described in the provided context?

- A. To evaluate the performance of the Near-RT RIC's E2 interface.
- B. To verify the Near-RT RIC's ability to handle RIC Service Update procedures when a RAN Function is modified.
- C. To assess the compatibility of the Near-RT RIC with different E2 Service Models.
- D. To test the functionality of the Test Simulator's E2 Node in initiating RIC Service Update procedures.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-135`）

</details>

**1.5.7-7.** Which E2SM-RC IE format is used for the CONTROL Service style that carries the outcome of processing an incoming RIC Control Request message?

- A. E2SM-RC Call Process ID Format 1
- B. E2SM-RC Control Outcome Format 1
- C. E2SM-RC Control Request Format 1
- D. E2SM-RC RIC Control Outcome Format 1

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-150`）

</details>

**1.5.7-8.** Which of the following is a function of the E2 Node in an O-RAN architecture?

- A. Collect configurations, performance indicators and measurement reports from E2 Node(s).
- B. Infer an optimized RF Channel configuration for EE/ES based on the data collected using R1 interface.
- C. Report cell configuration, performance indicators and measurement reports.
- D. Provide optimized A1 policy for EE/ES based on the data collected using R1 interface.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-187`）

</details>

**1.5.7-9.** Which of the following actions can be initiated by event triggers defined in the RIC Event Trigger Definition IE?

- A. REPORT
- B. INSERT
- C. POLICY
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-199`）

</details>

**1.5.7-10.** Which of the following best describes the purpose of REPORT Service Style 4 in the context of O-RAN?

- A. To collect performance measurement information from a group of UEs based on common subscribed conditions.
- B. To provide real-time control over individual UE's radio parameters.
- C. To configure the network infrastructure for optimal performance.
- D. To manage the network resources for specific user groups.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-238`）

</details>

**1.5.7-11.** Which of the following Information Elements (IEs) is used to uniquely identify an action of a specific RIC Control style?

- A. RAN Function Name
- B. Control Action ID
- C. RIC Style Type
- D. RIC Style Name

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-357`）

</details>

**1.5.7-12.** Which of the following is NOT a test case related to the E2AP Global Procedures for Near-RT RIC conformance testing?

- A. E2 Setup (positive case)
- B. Reset procedure (initiated by E2 Node) (positive case)
- C. Error Indication procedure
- D. RIC Service Update procedure with RAN Function modified (positive case)

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-360`）

</details>

**1.5.7-13.** What type of information is used to define specific RAN Function E2AP Information Elements (IEs) in E2AP procedures?

- A. OCTET STRING
- B. INTEGER
- C. BOOLEAN
- D. STRING

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-366`）

</details>

**1.5.7-14.** Which of the following is NOT a valid value type for the 'RANParameter-ValueType' field in the 'RANParameter-STRUCTURE-Item' definition?

- A. RANParameter-Value
- B. RANParameter-STRUCTURE
- C. RANParameter-LIST
- D. RANParameter-Testing

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-385`）

</details>

**1.5.7-15.** What is the purpose of the "E2nodeComponentConfigAdditionAck-ItemIEs" structure in the provided context?

- A. To acknowledge the addition of a new E2 node component configuration.
- B. To request the removal of an E2 node component configuration.
- C. To update an existing E2 node component configuration.
- D. To monitor the performance of E2 node components.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-386`）

</details>

**1.5.7-16.** What happens when the Report Type IE is set to 'All' in an O-RAN E2 node?

- A. The E2 node generates a report only for instances of the RAN configuration structure that have undergone a change.
- B. The E2 node generates a report for all instances of the RAN configuration structure, regardless of whether there have been changes.
- C. The E2 node only reports the attribute-value pairs for the specific list of attributes defined in the List of Attributes IE.
- D. The E2 node generates a report only for the specified cell(s) defined in the Global Cell Id IE.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-394`）

</details>

**1.5.7-17.** Which of the following is NOT a required field in the "RANFunctionName" schema?

- A. ranFunctionShortName
- B. ranFunctionServiceModelOID
- C. ranFunctionDescription
- D. ranFunctionInstance

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-404`）

</details>

**1.5.7-18.** What is the purpose of the `RANfunction-Name` sequence in the provided O-RAN specification?

- A. To define the unique identifier for a specific RAN function.
- B. To specify the type of RAN parameter being used.
- C. To define a list of RAN parameters and their values.
- D. To describe the imperative policies for a particular RAN function.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-405`）

</details>

**1.5.7-19.** Which of the following is NOT a POLICY service supported by the "RAN Control" RAN Function?

- A. Radio Bearer Policy
- B. Network Slicing Policy
- C. Radio Resource Allocation Policy
- D. Idle Mode Mobility Policy

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-421`）

</details>

**1.5.7-20.** What action should the E2 Node take if it receives a RIC CONTROL REQUEST message with an invalid RIC Call Process ID IE?

- A. Respond with a RIC CONTROL SUCCESS message.
- B. Respond with a RIC CONTROL FAILURE message with an appropriate cause value.
- C. Ignore the request and continue processing other messages.
- D. Send a notification to the Near-RT RIC.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-462`）

</details>

**1.5.7-21.** Which of the following is a CHOICE type defined in the E2SM-NI protocol for representing the outcome of a control message?

- A. E2SM-NI-ControlMessage-Format1
- B. E2SM-NI-ControlOutcome
- C. E2SM-NI-RANfunction-Description
- D. E2SM-NI-RANfunction-Item

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-499`）

</details>

**1.5.7-22.** Which of the following messages is used to indicate that an E2 subscription request has been rejected?

- A. E2ActionAdmittedItem
- B. E2ActionNotAdmittedItem
- C. E2SubscriptionFailure
- D. E2SubscriptionReject

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-503`）

</details>

**1.5.7-23.** When an E2 Node wants to establish an additional SCTP association with a Near-RT RIC, what E2AP procedure is triggered first?

- A. RIC Subscription TNLA Binding Update
- B. E2 Node Configuration Update
- C. E2 Interface Configuration Update
- D. SCTP Association Setup

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-510`）

</details>

**1.5.7-24.** Which of the following attributes describes the maximum delay for downlink packets in milliseconds, communicated to the Near-RT RIC?

- A. maxUlPacketDelay
- B. maxDlPacketDelayPerUe
- C. Packet Delay Budget
- D. maxDlPdcpSduPac

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-542`）

</details>

**1.5.7-25.** What action does the E2 node take upon receiving a RIC Control Request message with the Downlink PDCP Data Split IE present?

- A. It splits downlink PDCP traffic between the Master Node and Secondary Node based on the recommended ratio.
- B. It invokes procedures related to DRB Split Ratio Control, such as Bearer Context Management and UE Context Management.
- C. It sends a RIC Control Failure message if the DRB ID is missing.
- D. It includes IEs corresponding to parameters related to PDCP Duplication Control in the related interface messages.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-612`）

</details>

**1.5.7-26.** Which E2SM-RC IE format is used for the INSERT Service style's RIC Action Definition in the context of Open Radio Access Networks?

- A. E2SM-RC Action Definition Format 1
- B. E2SM-RC Action Definition Format 2
- C. E2SM-RC Action Definition Format 3
- D. E2SM-RC Action Definition Format 4

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-664`）

</details>

**1.5.7-27.** What are the two types of Radio Intelligent Controller (RIC) that can be used to enable, disable, or modify carrier aggregation (CA) and dual connectivity in an Open Radio Access Network (O-RAN)?

- A. RIC POLICY and RIC CONTROL
- B. RIC Near-RT and RIC Non-RT
- C. RIC E2 and RIC O1
- D. RIC gNB and RIC O-RU

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-682`）

</details>

**1.5.7-28.** What type of information can be reported along with Network Interface or RRC messages in the REPORT Service Style 1?

- A. Only Network Interface or RRC message copies.
- B. UE and E2 Node specific information related to the messages.
- C. Only UE specific information.
- D. Only E2 Node specific information.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-740`）

</details>

**1.5.7-29.** Which of the following is NOT an application of the POLICY Service Style 3: Connected Mode Mobility Control in O-RAN?

- A. Handover decision and target cell selection
- B. RRC connection admission
- C. Measurement configuration for handover candidate cell detection
- D. Dual Active Protocol Stack (DAPS) usage

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-763`）

</details>

**1.5.7-30.** Which of the following is NOT an application of CONTROL Service Style 8 in O-RAN?

- A. Adding or removing a UE from an Explicit UE list
- B. Requesting a list of supported Explicit UE lists
- C. Configuring the RAN's radio parameters
- D. Requesting UE information, including Explicit UE list assignments

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-789`）

</details>

**1.5.7-31.** When an E2 node reports an O-RRMPolicyRatio_PRB_2 update, what value is reported for the ChangeType IE?

- A. Modification
- B. None
- C. Addition
- D. Deletion

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-846`）

</details>

**1.5.7-32.** Which of the following is a common set of RAN parameters used across all POLICY service styles?

- A. Radio Bearer Control
- B. RIC Event Trigger Definition IE
- C. Policy Conditions
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-870`）

</details>

**1.5.7-33.** Which RAN configuration structures are used for defining event triggers in Event Trigger Style 2?

- A. Node-level RAN Configuration Structures only
- B. Cell-level RAN Configuration Structures only
- C. Both Node-level and Cell-level RAN Configuration Structures
- D. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-929`）

</details>

**1.5.7-34.** In the context of O-RAN, which E2SM-RC IE format is utilized for the Control Service style's RIC Call Process ID?

- A. E2SM-RC Call Process ID Format 1
- B. E2SM-RC Call Process ID Format 2
- C. E2SM-RC Call Process ID Format 3
- D. E2SM-RC Call Process ID Format 4

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-948`）

</details>

**1.5.7-35.** Which of the following is NOT a type of reporting for RAN Configuration Structures?

- A. All
- B. Change
- C. Partial
- D. Incremental

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1004`）

</details>

**1.5.7-36.** Which E2SM-RC Indication Message Format IE is used by the INSERT Service style described in the context?

- A. Format 1
- B. Format 2
- C. Format 6
- D. Format 9

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1006`）

</details>

**1.5.7-37.** In the context of O-RAN, what happens if the DRB ID is missing in a RIC Control Request message?

- A. The E2 node will ignore the request and proceed to the next message.
- B. The E2 node will send a RIC Control Failure.
- C. The E2 node will attempt to deduce the DRB ID from the UE Group Definition IE.
- D. The E2 node will request the missing information from the RIC.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1104`）

</details>

**1.5.7-38.** In an O-RAN network, what is a potential use case for configuration change event triggers using the O-RRMPolicyRatio RAN configuration structure?

- A. Managing radio resource allocation for different slices in the same NR Cell.
- B. Monitoring the performance of the gNB.
- C. Configuring the network for different frequency bands.
- D. Updating the location of the gNB.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1127`）

</details>

**1.5.7-39.** Which of the following O-RAN policy service styles does not support the "offset" approach?

- A. Add MR Configuration
- B. Modify MR Configuration
- C. Delete MR Configuration
- D. Non-GoB BF Mode Configuration

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1151`）

</details>

**1.5.7-40.** When an E2 Node modifies attribute values, what information does it report to the Near-RT RIC to identify the affected configuration structures?

- A. The E2 Node reports the timestamp of the modification.
- B. The E2 Node reports the old and new values of the modified attributes.
- C. The E2 Node reports the ID of the user who made the modification.
- D. The E2 Node reports the number of instances affected by the modification.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1196`）

</details>

頁次：[1](1-5-gsma-1.md)　[2](1-5-gsma-2.md)　[3](1-5-gsma-3.md)　[4](1-5-gsma-4.md)　**5**
