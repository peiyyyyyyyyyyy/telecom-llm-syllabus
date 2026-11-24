# 1.5 開放與虛擬化　GSMA 練習題（909 題）（第 2／5 頁）

所屬：[1.5 開放與虛擬化](1-5.md)

只收 GSMA 訓練題；不含驗證集與測試集，並已去除和驗證／測試題相同或相似、重複、標註衝突的題目。題目依小節歸類（抽查正確率約 95%）。

頁次：[1](1-5-gsma-1.md)　**2**　[3](1-5-gsma-3.md)　[4](1-5-gsma-4.md)　[5](1-5-gsma-5.md)

## 1.5.2 RAN 智慧控制器：Near-RT RIC、Non-RT RIC、xApp、rApp（128 題）（續）

**1.5.2-31.** Which of the following is a function of the Near-RT RIC in an O-RAN network?

- A. Support deployment and execution of AI/ML models from Non-RT RIC.
- B. Perform optimized RAN (E2) actions to achieve RAN slice requirements based on O1 configuration, A1 policy, and E2 reports.
- C. Send UE specific performance reports to SMO/Non-RT RIC.
- D. Support slice specific performance measurements through O1.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-61`）

</details>

**1.5.2-32.** What is the purpose of the "dataProductionSchema" attribute in the context of O-RAN?

- A. To define the schema for data delivery mechanisms.
- B. To specify the type of data being produced.
- C. To define the schema for data requests or subscriptions.
- D. To provide information about the DME type.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-71`）

</details>

**1.5.2-33.** What delivery method is defined as a point-to-multipoint data streaming mechanism in the O-RAN R1 service API?

- A. HTTP
- B. KAFKA_DATA_STREAM
- C. PULL_DELIVERY
- D. PUSH_DELIVERY

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-73`）

</details>

**1.5.2-34.** What is the primary role of the Data Management and Exposure (DME) functions in the context of O-RAN?

- A. To manage and expose data for applications.
- B. To provide radio resource management.
- C. To handle user authentication and authorization.
- D. To control the physical layer of the network.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-74`）

</details>

**1.5.2-35.** In the O-RAN context, what is the primary role of the "AI/ML workflow functions" in relation to the "AI/ML training services Consumer rApp"?

- A. To receive training data from the Consumer rApp and store it in a model repository.
- B. To create and manage training jobs on behalf of the Consumer rApp.
- C. To provide real-time insights and predictions based on the trained models.
- D. To monitor and optimize the performance of the AI/ML training services.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-76`）

</details>

**1.5.2-36.** What is a key characteristic of services in an O-RAN system?

- A. They are always standardized by the O-RAN Alliance.
- B. They can be proprietary, standardized by other organizations, or by the O-RAN Alliance.
- C. They must be implemented within the Non-RT RIC.
- D. They are only available for use within the SMO.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-78`）

</details>

**1.5.2-37.** What HTTP response code indicates that the data payload is not yet ready for retrieval in the Pull data operation?

- A. 200 OK
- B. 202 Accepted
- C. 404 Not Found
- D. 500 Internal Server Error

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-85`）

</details>

**1.5.2-38.** Which of the following is NOT a valid data category defined in the provided context?

- A. PM counters
- B. Network Statistics
- C. Call Detail Records
- D. Location Information

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-87`）

</details>

**1.5.2-39.** In the context of O-RAN, what is the key simplification achieved by Option 2 in the provided text?

- A. The SMO/Non-RT RIC eliminates the need for 5GC NFs to discover NWDAF instances through the NRF and UDM.
- B. The AnLF functionality is duplicated in both the Non-RT RIC and the RT RIC.
- C. The SMO/Non-RT RIC directly interacts with the 5GC NFs, bypassing the DCCF/MFAF.
- D. The data mapping function is entirely handled by the 5G Core NF.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-89`）

</details>

**1.5.2-40.** Which of the following is NOT a procedure defined for data management and exposure functions in the O-RAN SMO/Non-RT RIC framework?

- A. Requesting data instances
- B. Discovering available DME types
- C. Configuring the data management and exposure functions
- D. Subscribing to notifications about changes in available DME types

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-93`）

</details>

**1.5.2-41.** Which of the following is NOT a valid resource type for Open Radio Access Networks (O-RAN) as defined in the provided context?

- A. PRB_DL
- B. DRB
- C. RRC
- D. UE_IP

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-108`）

</details>

**1.5.2-42.** What is the primary role of the Near-RT RIC in the context of Local Signaling Storm Protection?

- A. Detect local cell-level signaling storms and execute mitigation policies.
- B. Collect and report RAN signaling events and policy-specific statistics over E2.
- C. Establish data collection and sharing interfaces with non-RT RIC.
- D. Deploy and configure Signaling Storms Detection and Mitigation xApps over E2.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-126`）

</details>

**1.5.2-43.** Which of the following is NOT a management service exposed by the Near-RT RIC via the O1 interface?

- A. Provisioning management services
- B. Fault and event reporting services
- C. Network slicing management services
- D. Communication surveillance services

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-134`）

</details>

**1.5.2-44.** What is the intended performance result that is desired from the network, configured to the Near-RT RIC over O1?

- A. Traffic Steering Outer Loop
- B. Traffic Steering Processing Mode
- C. Traffic Steering Target
- D. Traffic Steering Actions

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-138`）

</details>

**1.5.2-45.** What is one of the key functionalities of the SMO-Sharing APP in O-RAN?

- A. Managing the handover of user equipment (UE) between different operators.
- B. Converting SLA data into condition steps for matching requests from the host operator.
- C. Providing real-time monitoring and control of the RAN.
- D. Optimizing the allocation of radio resources based on user location.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-173`）

</details>

**1.5.2-46.** What information does an rApp need to provide to unsubscribe from service availability notifications?

- A. rAppId and service identifier
- B. Subscription identifier
- C. Service identifier and information about the changes
- D. rAppId and information about the changes

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-175`）

</details>

**1.5.2-47.** Which of the following is a type of RIC (Radio Intelligence Controller) used in O-RAN?

- A. Near-RT RIC
- B. SMO
- C. NON
- D. E2 Nodes

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-180`）

</details>

**1.5.2-48.** In an O-RAN network, what component is responsible for detecting signaling storms and creating fine-grained filters to mitigate them?

- A. Near-RT RIC
- B. Non-RT RIC
- C. RAN nodes
- D. E2 Nodes

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-184`）

</details>

**1.5.2-49.** In the context of O-RAN, which component is responsible for storing and executing Quality of Experience (QoE) related machine learning (ML) models for optimization purposes?

- A. Non-RT RIC
- B. Near-RT RIC
- C. xApp
- D. O1

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-211`）

</details>

**1.5.2-50.** What role does the Near-RT RIC play in interference optimization within an O-RAN network?

- A. The Near-RT RIC is responsible for configuring the base station's reference signals to enable UE interference detection.
- B. The Near-RT RIC analyzes interference data from UEs and generates policies to control resource allocation in the RAN.
- C. The Near-RT RIC directly controls UE behavior to minimize interference.
- D. The Near-RT RIC monitors interference levels and reports them to the Non-RT RIC for further analysis.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-225`）

</details>

**1.5.2-51.** What HTTP method is used to register a DME type production capability in an Open RAN system?

- A. GET
- B. POST
- C. PUT
- D. DELETE

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-258`）

</details>

**1.5.2-52.** In the context of O-RAN, what is the primary goal of the QoE use case?

- A. To ensure efficient traffic distribution across multiple cells.
- B. To optimize radio resource allocation based on user traffic data and QoE measurements.
- C. To support real-time QoS optimization for bandwidth-intensive and latency-sensitive applications.
- D. To provide a framework for semi-static QoS management.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-274`）

</details>

**1.5.2-53.** Which of the following is NOT a step taken by Non-RT RIC in mitigating a distributed signaling storm attack?

- A. Analyzing network signaling activity levels based on statistics.
- B. Applying initial configurations to near-RT RIC elements regarding detection and mitigation parameters.
- C. Updating configuration to a stricter one in relevant near-RT RIC locations over the A1 interface.
- D. Performing detection and mitigation actions with stricter configuration in near-RT RIC.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-298`）

</details>

**1.5.2-54.** In an O-RAN sharing use case, what is the primary function of the Near-RT RIC (Operator B)?

- A. Collect and report RAN statistics to the RIC of Operator A.
- B. Execute remote E2 commands via the "E2 remote" interface.
- C. Update configuration of VNFs hosted in site B.
- D. Handle remote orchestration operations via "O1, O2 remote" interface.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-311`）

</details>

**1.5.2-55.** Which of the following is NOT a data type defined in the O-RAN specification for API version information?

- A. KeyValuePairs
- B. ApiVersionInformation
- C. NotificationLink
- D. Simple data types

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-324`）

</details>

**1.5.2-56.** What does the "DmeTypeProdCapRegistration" data type represent in O-RAN?

- A. Information about a DME type.
- B. Registration information for a DME type production capability.
- C. Constraints related to the DME type based on the dataProductionSchema.
- D. Endpoint to send the data subscription request.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-330`）

</details>

**1.5.2-57.** What is the purpose of the DELETE method in the context of O-RAN DME type production capability registration?

- A. To register a new DME type production capability.
- B. To retrieve information about a specific DME type production capability.
- C. To update an existing DME type production capability.
- D. To remove an existing DME type production capability registration.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-362`）

</details>

**1.5.2-58.** What role does the Non-RT RIC play when it presents itself to 5GC NFs as an NWDAF?

- A. It acts as a Network Function.
- B. It acts as a Management Function.
- C. It acts as a Data Management Function.
- D. It acts as a Data Analytics Function.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-391`）

</details>

**1.5.2-59.** In the context of downlink transmit power optimization in O-RAN, what is a potential consequence of evenly distributing transmit power across all User Equipments (UEs)?

- A. Improved cell capacity at the expense of individual UE quality.
- B. Enhanced user experience for all UEs.
- C. Optimal SINR for all UEs, regardless of their location.
- D. Increased downlink SINR for cell edge UEs.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-412`）

</details>

**1.5.2-60.** What is the purpose of the "namespace" attribute within the DmeTypeIdStruct data type?

- A. To indicate the version of the DME type.
- B. To specify the name of the DME type.
- C. To identify the entity responsible for defining the DME type.
- D. To define the allowed characters for the DME type name.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-413`）

</details>

**1.5.2-61.** What is the first step a Data Producer rApp must take before initiating the Create data offer procedure?

- A. Register a DME type for the data instance it will produce.
- B. Set up an endpoint for data availability notifications.
- C. Terminate the data offer.
- D. Communicate with the DME functions about data delivery services.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-452`）

</details>

**1.5.2-62.** Which of the following HTTP response codes indicates that the requested data is not yet available and the client should retry later?

- A. 200 OK
- B. 202 Accepted
- C. 4xx/5xx
- D. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-470`）

</details>

**1.5.2-63.** What is the purpose of the API DISCOVERY REQUEST message sent by an xApp to a Near-RT RIC platform?

- A. To authenticate the xApp with the RIC platform.
- B. To request a list of available Near-RT RIC APIs.
- C. To initiate a data transfer session with the RIC platform.
- D. To inform the RIC platform of the xApp's capabilities.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-471`）

</details>

**1.5.2-64.** Which of the following is NOT a function of E2 Nodes in the RAN domain?

- A. Support sending connection establishment messages over the E2 interface.
- B. Support control and policy enforcement from near-RT RIC over the E2 interface.
- C. Detect localized signaling storms based on "default parameters".
- D. Collect and report RAN signaling events and policy-specific statistics over E2.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-488`）

</details>

**1.5.2-65.** In the context of Open Radio Access Networks (O-RAN), what is the primary role of an rApp when it receives notifications about service availability changes?

- A. To send notifications to the SME functions about changes in service availability.
- B. To  process the changes in the available services.
- C. To determine the need for service updates or deregistrations.
- D. To register new services with the SME functions.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-498`）

</details>

**1.5.2-66.** In an O-RAN network, what is the primary consideration for routing traffic for a High Mobility UE?

- A. Maximizing bandwidth usage on the unlicensed band.
- B. Maintaining a consistent connection, even if it means using the licensed band.
- C. Routing all traffic over the secondary cell to avoid congestion on the primary cell.
- D. Prioritizing voice traffic over all other data traffic.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-513`）

</details>

**1.5.2-67.** What attribute is used to signal the full API versions supported in the context of O-RAN?

- A. aefId
- B. aefLocation
- C. vendorSpecific-o-ran.org
- D. domainName

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-540`）

</details>

**1.5.2-68.** What information is provided by the Data management and exposure functions in an update data subscription request?

- A. Data stream endpoint
- B. Data type identifier and scope
- C. Subscription identifier and data subscription update information
- D. Periodicity of reporting

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-545`）

</details>

**1.5.2-69.** Which of the following is NOT a capability provided by the CM service Producer over the R1 interface in an O-RAN network?

- A. Retrieving configuration schemas
- B. Reading configuration data
- C. Writing configuration changes
- D. Managing user authentication and authorization

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-546`）

</details>

**1.5.2-70.** What are the key aspects of an Open Radio Access Network (O-RAN) application development lifecycle?

- A. Application package model, app development lifecycles, app onboarding lifecycles, and app operation lifecycles.
- B. Network slicing, RAN intelligence, and cloud-native infrastructure.
- C. Hardware virtualization, software-defined networking, and network function virtualization.
- D. 5G NR, LTE, and Wi-Fi integration.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-548`）

</details>

**1.5.2-71.** In the initial phase of O-RAN, where is the ML model training primarily conducted?

- A. O-DU
- B. Near-RT RIC
- C. Non-RT RIC
- D. O-RU

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-563`）

</details>

**1.5.2-72.** What are the three types of catalogs used in O-RAN?

- A. Design-time catalog, training/deployment-time catalog, and run-time catalog
- B. Network catalog, service catalog, and resource catalog
- C. Data catalog, model catalog, and inference catalog
- D. Configuration catalog, management catalog, and orchestration catalog

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-590`）

</details>

**1.5.2-73.** What is the primary purpose of the Near-Real Time RAN Intelligent Controller (Near-RT RIC)?

- A. To provide a platform for AI/ML-based tools to manage and optimize RAN elements.
- B. To replace existing RAN networks with self-organizing networks (SON).
- C. To enable real-time control over user equipment (UE) and cell data.
- D. To create a closed system for managing and orchestrating RAN resources.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-598`）

</details>

**1.5.2-74.** Which of the following is a function of the SMO in Near-RT Beam-based Mobility Robustness Optimization (bMRO)?

- A. Retrieve necessary configurations, performance indicators, measurement reports and other data from E2 nodes for the purpose of training of relevant AI/ML models.
- B. Trigger bMRO configuration.
- C. Monitor the performance of all the cells; when the optimization objective fails, initiate fall back procedure; meanwhile, trigger the AI/ML model re-training, data analytics and optimization in Non-RT RIC.
- D. Apply beam management strategies following SMO and Near-RT RIC configuration and constraints.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-609`）

</details>

**1.5.2-75.** What is the primary responsibility of the Non-RT RIC regarding A1 policies in the Near-RT RIC?

- A. Defining and administering A1 policies.
- B. Enforcing A1 policies in the RAN.
- C. Monitoring the performance of A1 policies.
- D. Creating and managing the persistent configuration of the RAN.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-615`）

</details>

**1.5.2-76.** What is the preference for the first set of cells in the QoS optimization with resource directive?

- A. PREFER
- B. AVOID
- C. NONE
- D. DEFAULT

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-627`）

</details>

**1.5.2-77.** Which E2 Related API is used by the Near-RT RIC platform to inform xApps about the deletion of a subscription?

- A. E2 Subscription Delete Query (accept)
- B. E2 Subscription Delete Query (decline)
- C. E2 Subscription Delete Notification (Deleted)
- D. E2 Subscription Delete Notification (Pending)

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-636`）

</details>

**1.5.2-78.** In an Open Radio Access Network (O-RAN) system, which of the following acts as an OAuth 2.0 resource owner/server?

- A. rApp
- B. xApps
- C. Near-RT RIC platform
- D. OAuth 2.0 Authorization server

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-646`）

</details>

**1.5.2-79.** In the context of O-RAN, what is the primary role of the rApp in the data subscription process?

- A. To provide data management and exposure services to the Data management and exposure functions.
- B. To consume data by subscribing to it and receiving the subscribed data.
- C. To configure data stream endpoints for point-to-multipoint data stream delivery.
- D. To authorize access to the Data management and exposure services.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-683`）

</details>

**1.5.2-80.** Which of the following is a requirement for Near-RT RIC platforms in O-RAN?

- A. Support for resolution of conflicts between xApps and Near-RT RIC services.
- B. Ability to communicate with xApps using Near-RT RIC APIs.
- C. Support for subscription merging from multiple xApps to reduce network load.
- D. All of the above.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-687`）

</details>

**1.5.2-81.** In an O-RAN architecture, which of the following components is responsible for configuring the vO-DU and vO-CU for resource assignment?

- A. O-RU
- B. Near-RT RIC
- C. SMO
- D. CU-CP

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-689`）

</details>

**1.5.2-82.** What is the purpose of the `DmeTypeProdCapRegistration` data type in O-RAN?

- A. To define the data production schema for a DME type.
- B. To register information about a DME type's production capability.
- C. To specify the data request and subscription endpoints for a DME type.
- D. To formulate producer constraints related to the DME type.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-693`）

</details>

**1.5.2-83.** What is the primary goal of the "Query the status of an A1 policy" use case in the O-RAN context?

- A. To allow rApps to create new A1 policies.
- B. To enable rApps to modify existing A1 policies.
- C. To provide rApps with information about the current state of an A1 policy.
- D. To help rApps delete A1 policies.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-700`）

</details>

**1.5.2-84.** In the O-RAN framework, what is the primary role of the rApp (RAN Application)?

- A. To manage and control the radio access network.
- B. To provide services to end users.
- C. To process service availability changes.
- D. To handle network configuration and optimization.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-707`）

</details>

**1.5.2-85.** Which of the following IEs is used to represent a list of 5QIs within a partitionFlowList?

- A. pLMNInfo
- B. rRMPolicyMemberList
- C. bWPList
- D. 5QIList

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-708`）

</details>

**1.5.2-86.** What is the maximum value allowed for the "PacketLossRate" parameter in the "NotificationTriggerEvent" object?

- A. 1000
- B. 100
- C. 10
- D. 1

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-718`）

</details>

**1.5.2-87.** What is the primary function of the Near-RT RIC (O-RAN Near-Real-Time RAN Intelligent Controller)?

- A. Providing long-term planning and resource allocation for the RAN.
- B. Enabling near-real-time control and optimization of RAN elements and resources.
- C. Managing the overall network topology and configuration.
- D. Developing and deploying new 5G features and capabilities.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-720`）

</details>

**1.5.2-88.** In an O-RAN network using Style 3 (Connected Mobile Mobility) and Policy Action ID 1 (Policy for Handover control), what is the purpose of the Policy Action IE parameters?

- A. To define the RAN parameters used to map a UE to an appropriate Policy Action.
- B. To define a set of offsets to modify default measurement thresholds for handover decisions.
- C. To determine the outcome of the handover decision and trigger subsequent actions.
- D. To store UE context information and results of network transactions.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-722`）

</details>

**1.5.2-89.** Which of the following fields are required for the "GuRanUeId" object in the provided context?

- A. globalGnbId and ranUeId
- B. plmnId and gnbId
- C. guRanUeId
- D. gnbCuUeF1apId and gnbCuCpUeE1apId

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-730`）

</details>

**1.5.2-90.** Which component is responsible for detecting local cell-level signaling storms and executing mitigation policies in the context of O-RAN signaling storm protection?

- A. E2 Nodes
- B. Near-RT RIC
- C. SMO
- D. RAN

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-738`）

</details>

**1.5.2-91.** Which of the following functions is NOT considered part of the rApp management functions within the Non-RT RIC framework?

- A. rApp conflict mitigation
- B. rApp orchestration
- C. rApp service exposure
- D. rApp authentication

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-747`）

</details>

**1.5.2-92.** Which of the following is NOT a component of the Non-RT RIC Framework in a functional view?

- A. xApp
- B. rApp
- C. Near-RT RIC
- D. Non-RT RIC

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-768`）

</details>

**1.5.2-93.** In the O-RAN energy saving use case, which component is responsible for analyzing the performance of AI/ML models and initiating fallback mechanisms if energy saving objectives are not met?

- A. O-RU
- B. E2 Node
- C. SMO
- D. Non-RT RIC

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-775`）

</details>

**1.5.2-94.** Which of the following is NOT a policy type definition discussed in the context of O-RAN?

- A. QoS target
- B. QoE target
- C. Traffic steering preferences
- D. Network slicing

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-778`）

</details>

**1.5.2-95.** Which of the following is NOT a function supported by an E2 node in the context of Energy Saving (ES) in O-RAN?

- A. Enabling ES optimization actions through E2.
- B. Gathering ES-related performance measurements through O1.
- C. Generating ES-related performance reports through E2.
- D. Providing real-time control of individual UE power consumption.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-782`）

</details>

**1.5.2-96.** Which of the following components are involved in the policy generation and performance evaluation process in an O-RAN network?

- A. Non-RT RIC, Near-RT RIC, SMO
- B. RAN, gNB, UE
- C. O-DU, O-RU, CU
- D. xHaul, Fronthaul, Backhaul

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-788`）

</details>

**1.5.2-97.** What are the possible methods for RAI notifications?

- A. PERIODIC and EVENT_TRIGGERED
- B. OVERLOAD and UNKNOWN
- C. START_TIME and DURATION_MILLISECOND
- D. FILTER_PARAMETERS

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-805`）

</details>

**1.5.2-98.** What type of message can an xApp send to the Near-RT RIC platform if an error is detected in a received message?

- A. E2 CONTROL (Request)
- B. E2 CONTROL (Success)
- C. E2 INDICATION (Push)
- D. E2 INDICATION (Failure)

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-825`）

</details>

**1.5.2-99.** In the context of Open Radio Access Networks (O-RAN), how can Distributed Service Software (DSS) over Radio Intelligence Controller (RIC) improve resource management efficiency in multi-cell scenarios?

- A. By dynamically allocating spectrum resources based on real-time user mobility data and predicted bandwidth requirements.
- B. By using near-real-time RIC to identify overlapping cell edges and optimize resource allocation for cell center users.
- C. By centralizing control over all radio resources, allowing for more efficient allocation.
- D. By eliminating the need for complex scheduling algorithms.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-832`）

</details>

**1.5.2-100.** In the context of O-RAN, what is the primary role of Near-RT RIC in the Massive MIMO Beam-based Mobility Robustness Optimization process?

- A. To monitor network performance and trigger fallback mechanisms when necessary.
- B. To configure and optimize parameters in E2 Nodes based on operator targets.
- C. To collect data for training and updating AI/ML models.
- D. All of the above.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-838`）

</details>

**1.5.2-101.** In the context of O-RAN, what is the primary purpose of the "Data management and exposure functions" when responding to an rApp's DME type registration query?

- A. To provide the rApp with the DME type registration information.
- B. To initiate the authorization process with SME functions.
- C. To query the registered DME type from the database.
- D. To verify the rApp's identity and access permissions.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-855`）

</details>

**1.5.2-102.** What are the two entities involved in the end-to-end lifecycle of O-RAN applications?

- A. Network Provider and Service Provider
- B. Solution Provider and Service Provider
- C. Application Developer and Network Operator
- D. Hardware Vendor and Software Vendor

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-884`）

</details>

**1.5.2-103.** What is one of the key services provided by the Data Management and Exposure Service in O-RAN?

- A. Data Registration
- B. Network Slicing
- C. Radio Resource Management
- D. User Authentication

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-886`）

</details>

**1.5.2-104.** What is the purpose of the "dataCategory" property in the provided O-RAN context?

- A. To define the radio access technology used, such as 5G.
- B. To specify the type of schema supported by Data Producers.
- C. To categorize the type of DME data, such as PM counters.
- D. To configure the delivery method for data streams.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-916`）

</details>

**1.5.2-105.** Which of the following is NOT a required field within the 'dataProduction' schema in O-RAN?

- A. dataDelivery
- B. dataTypeId
- C. dataAvailabilityNotificationUri
- D. dataDeliverySchemaId

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-924`）

</details>

**1.5.2-106.** What is the data type for the 'plmnId' attribute within the 'GlobalGnbId' data type?

- A. integer
- B. PlmnId
- C. GnbId
- D. GlobalGnbId

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-943`）

</details>

**1.5.2-107.** Which of the following is NOT a function of the Near-RT RIC in an O-RAN architecture?

- A. Support deployment and execution of AI/ML models from Non-RT RIC
- B. Receive slice SLA assurance xApps from SMO
- C. Retrieve RAN slice SLA target from respective entities such as SMO, NSSMF
- D. Perform optimized RAN (E2) actions to achieve RAN slice requirements based on O1 configuration, A1 policy, and E2 reports

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-953`）

</details>

**1.5.2-108.** What message does the Near-RT RIC Platform send to the xApp if it rejects an API Event Subscription Delete Request?

- A. API EVENT SUBSCRIPTION DELETE SUCCESS
- B. API EVENT SUBSCRIPTION DELETE FAILURE
- C. API EVENT NOTIFICATION
- D. API EVENT NOTIFICATION ACK

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-958`）

</details>

**1.5.2-109.** During the software update process of an existing O-DU, what is the purpose of the O-DU SW Change Management rApp?

- A. To identify the software version to be updated and recommend the specifics of the change to the SMO.
- B. To initiate the configuration of the Shared O-RU Common aspects.
- C. To provision the common aspects of the Shared O-RU, including security, operational, transmission, and connectivity parameters.
- D. To establish the call home procedure for the Shared O-RU.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-982`）

</details>

**1.5.2-110.** When resource consumption in a specific area exceeds a predetermined threshold, what action does the Non-RT RIC take?

- A. It configures the RAN scheduler to prioritize all users in the area equally.
- B. It requests more detailed observability data for individual UEs.
- C. It automatically adjusts the RAN configuration to meet the increased demand.
- D. It triggers an alarm to alert the network operator of the resource shortage.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-993`）

</details>

**1.5.2-111.** Which of the following is NOT a procedure that a Service Producer can utilize to manage their R1 service registration?

- A. Deregister service
- B. Update service registration
- C. Query registered services
- D. Discover services

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1017`）

</details>

**1.5.2-112.** What is the purpose of the "dataDeliveryMechanisms" field in the O-RAN.WG2.R1AP-R003-v04.00 specification?

- A. To define the delivery mechanism supported by the Data Consumer.
- B. To define the delivery mechanism supported by the Data Producer.
- C. To define the data type identifier.
- D. To define the delivery schema supported by the producer.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1048`）

</details>

**1.5.2-113.** What is the purpose of the `MatchingUeCondPerSubList` data structure in the provided context?

- A. To define a list of conditions that, if met, trigger an event.
- B. To store information about the reporting period for events.
- C. To define a list of UE IDs that are relevant for a particular event.
- D. To store measurement reports from UEs.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1053`）

</details>

**1.5.2-114.** Which of the following is NOT a required field within the "GuAmfUeNgapId" object definition?

- A. guAmI
- B. amfUeNgapId
- C. globalGnbId
- D. amfRegionId

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1073`）

</details>

**1.5.2-115.** What is the primary function of the Near-RT RIC Platform?

- A. To connect xApps with the Near-RT RIC platform
- B. To host xApps
- C. To define the Near-RT RIC API design principles
- D. To provide real-time control of the RAN

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1077`）

</details>

**1.5.2-116.** What is the purpose of the 'dataCategory' attribute within the Metadata data type?

- A. To specify the identifier of the DME type being registered.
- B. To define the category of the DME type, for example, PM counters.
- C. To provide a list of delivery schemas supported by the producer.
- D. To define the schema for data production and delivery.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1094`）

</details>

**1.5.2-117.** In an O-RAN network, what role does the Non-RT RIC play when a RAN slice's Service Level Specification (SLS) cannot be met due to insufficient resources?

- A. The Non-RT RIC analyzes the situation and configures the RAN to prioritize emergency traffic.
- B. The Non-RT RIC automatically adjusts the QoS parameters to ensure all users receive adequate service.
- C. The Non-RT RIC uses A1 policies to improve the situation based on information from the SMO.
- D. The Non-RT RIC triggers a network upgrade to increase capacity and meet the SLS.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1095`）

</details>

**1.5.2-118.** Which of the following is a key component of an O-RAN architecture that provides centralized control and intelligence for the RAN?

- A. eNodeB
- B. gNodeB
- C. RAN Intelligent Controller (RIC)
- D. SMO Functions

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1097`）

</details>

**1.5.2-119.** What is the primary purpose of the "ORAN_QoSandTSP_4.0.0" policy type identifier?

- A. To manage network security policies.
- B. To optimize QoS and traffic steering preferences.
- C. To define network slicing configurations.
- D. To control user authentication and authorization.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1125`）

</details>

**1.5.2-120.** Which of the following is a use case related to Open Radio Access Networks (O-RAN)?

- A. Managing service registration
- B. Optimizing network performance
- C. Developing new mobile applications
- D. Creating personalized user experiences

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1137`）

</details>

**1.5.2-121.** Which component in an O-RAN architecture is responsible for receiving and interpreting A1 policies from the Non-RT RIC to optimize radio resource allocation?

- A. OAM Functions
- B. Near-RT RIC
- C. E2 Node
- D. Non-RT RIC

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1158`）

</details>

**1.5.2-122.** Which of the following is a viable approach for mapping "generally useful" data structures from an SMO/Non-RT RIC to the structures defined in [i.24]?

- A. The SMO/Non-RT RIC presents the façade of an NWDAF towards a separate NWDAF, which acts as an Aggregation NWDAF.
- B. The SMO/Non-RT RIC maps the data structures into the structures defined in [i.24], with each rApp using data type registration to communicate its own mapping.
- C. The NWDAF directly accesses the SMO/Non-RT RIC's data structures without any mapping.
- D. The SMO/Non-RT RIC uses a separate interface to communicate with the NWDAF, independent of [i.24].

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1169`）

</details>

**1.5.2-123.** Which of the following data delivery mechanisms is NOT defined within the O-RAN.WG2.R1AP-R003-v04.00 specification?

- A. Pull Delivery Details HTTP
- B. Data Availability Notification URI
- C. Push Delivery Details HTTP
- D. Streaming Configuration MQTT

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-1179`）

</details>

**1.5.2-124.** Which of the following values represents the preference to avoid selecting a specific network resource unless connection retainability is at risk?

- A. SHALL
- B. PREFER
- C. AVOID
- D. FORBID

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1183`）

</details>

**1.5.2-125.** When reusing the CAPIF_Discover_Service_API in O-RAN, which attribute is required to be set to the value of "rAppId" if an rApp produces the API?

- A. serviceAPICategory
- B. aefId
- C. shareableInfo
- D. apiSuppFeats

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1188`）

</details>

**1.5.2-126.** Which of the following is NOT a key focus area for O-RAN A1 policy specifications?

- A. Defining procedures for A1 enrichment information.
- B. Describing lifecycle management aspects for A1 enrichment information services.
- C. Specifying the physical hardware components of the O-RAN radio access network.
- D. Enriching descriptions of A1 policy scope and content.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-1200`）

</details>

**1.5.2-127.** Which performance metrics related to slices are collected by the non-RT RIC (Radio Intelligent Controller)?

- A. Network functions
- B. Resource specifications
- C. Resource allocation
- D. SLA requirements
- E. Key Performance Indicators (KPIs)

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4411`）

</details>

**1.5.2-128.** What is the difference between real-time and near real-time?

- A. Real-time has deterministic latency guarantees, while near real-time has probabilistic guarantees.
- B. Real-time has shorter latency than near real-time.
- C. Real-time is intended for human-machine communication, while near real-time is intended for human-human communication.
- D. Real-time and near real-time have the same meaning.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5369`）

</details>

## 1.5.3 O-RAN 介面：A1、E2、O1、O2、開放前傳（388 題）

**1.5.3-1.** What is the purpose of E2 interface in O-RAN? 

- A. Operations, Administration and Maintenance
- B. Radio Access Technologies
- C. Near-Real-Time RAN Intelligent Controller
- D. Fault Management
- E. Interface between O-CU and O-DU

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-2156`）

</details>

**1.5.3-2.** What is the key interface that enables RAN disaggregation? 

- A. Open fronthaul (OFH) interface
- B. X2 interface
- C. O-RAN interface
- D. RAN interoperability (IOT) interface
- E. General-Purpose Processor (GPP) interface

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2377`）

</details>

**1.5.3-3.** Which interface is used for the fronthaul in O-RAN?

- A. F1 interface
- B. E2 interface
- C. CPRI interface
- D. O1 interface
- E. A1 interface

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2848`）

</details>

**1.5.3-4.** Which split option does the O-RAN use for the PHY (Physical layer) layer?

- A. 3-7x
- B. 5-6x
- C. 2-7x
- D. 7-2x
- E. 6-3x

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3091`）

</details>

**1.5.3-5.** What is the purpose of the A1-controller?

- A. To collect RAN statistics for each slice
- B. To process JavaScript Object Notation (JSON) messages
- C. To configure O-Cloud
- D. To prepare the RAN slice descriptor based on inference for configuring network resources
- E. To trigger the scaling up/down of network resources

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4076`）

</details>

**1.5.3-6.** What is the interface used between Near-RT RIC (Radio Intelligent Controller) and E2 Nodes?

- A. E2
- B. O1
- C. O2
- D. SMO
- E. AI Server

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4368`）

</details>

**1.5.3-7.** What are the standardized interfaces introduced by O-RAN for collecting and distributing data?

- A. O1
- B. A1
- C. O-RAN ML
- D. NFV MANO

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-5056`）

</details>

**1.5.3-8.** Which interface is used for fault, configuration, and performance management of the RAN (Radio Access Network) nodes?

- A. A1 interface
- B. O1 interface
- C. E1 interface
- D. O2 interface
- E. N2 interface

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6591`）

</details>

**1.5.3-9.** Which split option locates (de-)modulation, channel estimation, and equalization in the O-DU?

- A. 7-2x
- B. 3-7x
- C. 5-6x
- D. 2-7x
- E. 6-3x

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-7263`）

</details>

**1.5.3-10.** What is the primary function of the Fronthaul Gateway (FHGW) in O-RAN?

- A. To terminate O-RAN fronthaul user, control, synchronization, and management planes for option 7-2x and translate signals to and from CPRI interfaces.
- B. To provide a secure connection between the O-RU and the O-DU.
- C. To manage and distribute radio resources to multiple O-RUs.
- D. To perform real-time signal processing for the O-RAN system.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-16`）

</details>

**1.5.3-11.** What is the primary purpose of the O-RAN Information Model and Data Models?

- A. To define the physical specifications of O-RAN components.
- B. To provide a standardized way to represent and exchange data between O-RAN elements.
- C. To ensure interoperability between different O-RAN vendors.
- D. To manage the radio spectrum allocation in an O-RAN network.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-18`）

</details>

**1.5.3-12.** What type of information does the management system need to have regarding O-DUs for a successful software update?

- A. The configuration data for provisioning the SW updated O-DU based on the change management plan for SW update
- B. The configuration information of carriers of the SW updated O-DU configured on the Shared O-RU
- C. The state and status details of O-DUs to identify the right candidate to be used for SW update
- D. The alarm history and alarm data of the shared O-RU to verify functionality and sanity of the SW updated O-DU

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-20`）

</details>

**1.5.3-13.** What is the primary purpose of the test case TC_FH_MPLANE_SSH-PASSWORD-BASED_AUTHENTICATION_AUTHORIZATION?

- A. To ensure secure communication between the O-RU and O-DU over the FH interface using SSH.
- B. To verify the functionality of the NETCONF protocol on the FH interface.
- C. To test the performance of the O-RU and O-DU devices under high load conditions.
- D. To assess the security of the O-RAN network against external threats.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-22`）

</details>

**1.5.3-14.** What is the primary method used by the Shared O-DU Host (O-DU #1) to detect a loss of connection with the Shared O-RU?

- A. Monitoring the Shared O-RU's Call Home Signal.
- B. Detecting a lack of polling responses from the Shared O-RU.
- C. Analyzing the Shared O-RU's reset sequence.
- D. Monitoring the open front-haul interface for errors.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-29`）

</details>

**1.5.3-15.** Which of the following protocols is used for managing O-RAN configurations?

- A. SFF-8472v11
- B. IEEE 802.1ag
- C. NETCONF
- D. G.8275.1

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-31`）

</details>

**1.5.3-16.** What transport synchronization profiles are used for time synchronization between the O-DU and O-RU?

- A. LLS-C1 to LLS-C4
- B. IPv4 or IPv6
- C. NGAP, HTTP2, PFCP
- D. F1AP, NGAP, FH-eCPRI, FAPI, NAS, HTTP2, PFCP

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-32`）

</details>

**1.5.3-17.** Which of the following is a configuration model used in Open Radio Access Networks (O-RAN)?

- A. Hierarchical Model
- B. Hybrid Model
- C. Aggregation Model
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-35`）

</details>

**1.5.3-18.** Which type of clock recovers time and phase using PTP packet exchange and utilizes physical layer clock (like Sync-E) for frequency recovery, and is used in full timing support networks as per G.8275.1 profile?

- A. T-BC-P
- B. T-TSC
- C. T-BC-A
- D. T-TSC-P

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-37`）

</details>

**1.5.3-19.** Which standard defines the application error handling for Open Radio Access Networks (O-RAN)?

- A. 3GPP TS 29.501
- B. O-RAN TS R1GAP
- C. 3GPP TS 29.222
- D. CAPIF_Events_API

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-38`）

</details>

**1.5.3-20.** In the context of O-RAN, what is the purpose of the 'symInc' parameter within a data section description?

- A. To determine the starting symbol ID for a data section.
- B. To indicate whether a data section is referenced by multiple data section descriptions.
- C. To specify the number of symbols within a data section.
- D. To control the symbol range covered by a data section description.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-46`）

</details>

**1.5.3-21.** What are the two main types of transport encapsulation used in O-RAN?

- A. Ethernet and IP/UDP
- B. TCP and UDP
- C. Fiber and Coax
- D. Wireless and Wired

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-52`）

</details>

**1.5.3-22.** What NETCONF access privilege does the O-DU8 use when accessing the O-RU8 as a NETCONF Client?

- A. Read-Only
- B. Read-Write
- C. Sudo
- D. Administrative

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-54`）

</details>

**1.5.3-23.** What is the best acceptable configured value for SyncE Nominal QL, as determined by the O-RU?

- A. Determined by the M-Plane specification
- B. Defined in the relevant YANG models
- C. The "Received Value" reported by the O-RU
- D. The value considered optimal by the O-RU

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-57`）

</details>

**1.5.3-24.** What does the "acceptance-list-of-ssm" parameter in the "synce-config" section of the O-RAN specification control?

- A. The list of supported synchronization sources for the device.
- B. The time interval for re-synchronization attempts.
- C. The maximum number of synchronization sources that can be accepted.
- D. The priority of different synchronization sources.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-60`）

</details>

**1.5.3-25.** What does a beamId of 0 indicate in the context of O-RAN U-Plane data?

- A. The O-RU will apply phase and amplitude weights to the U-Plane data.
- B. The O-RU will perform digital beamforming.
- C. The O-RU will perform analog beamforming.
- D. No beamforming operation will be performed.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-64`）

</details>

**1.5.3-26.** What document defines the term "E2 Node" used in the context?

- A. E2GAP [2]
- B. <Standard Organization acronym> <document number><version number/date of publication>
- C. <Title>
- D. Definition of terms, symbols and abbreviations

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-67`）

</details>

**1.5.3-27.** What is the default setting for the 'multicast-mac-address' parameter when using the G.8275.1 profile in O-RAN?

- A. 01-1B-19-00-00-00
- B. 01-80-C2-00-00-0E
- C. 01-00-5E-00-00-01
- D. 01-00-5E-FF-FF-FF

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-72`）

</details>

**1.5.3-28.** How does the O-DU request an O-RU to deactivate Advanced Sleep Mode when using the M-Plane interface?

- A. The O-DU requests the O-RU to deactivate Advanced Sleep Mode based on a predefined energy saving policy.
- B. The O-DU sends a message through the Fronthaul C-Plane interface to the O-RU to deactivate Advanced Sleep Mode.
- C. The O-DU sends a message through the Fronthaul M-Plane interface to the O-RU to deactivate Advanced Sleep Mode.
- D. The O-DU directly controls the O-RU through a separate management channel to deactivate Advanced Sleep Mode.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-77`）

</details>

**1.5.3-29.** Which of the following is a possible interface between the O-DU and O-RU in a lower level split O-RAN architecture?

- A. F1 interface
- B. Open fronthaul interface
- C. Both F1 and open fronthaul interface
- D. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-91`）

</details>

**1.5.3-30.** Which Section Extension allows the O-DU to send channel information with dynamic PRB group size, reducing fronthaul traffic?

- A. Section Extension 20
- B. Section Extension 21
- C. Section Extension 6
- D. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-92`）

</details>

**1.5.3-31.** What happens when the LBM configuration is inconsistent between two models and the coordination is external to the O-RU?

- A. The O-RU's LBM behavior is specified by the present document.
- B. The O-RU's LBM behavior is not specified by the present document.
- C. The O-RU will automatically adjust its LBM configuration to match the other model.
- D. The O-RU will reject any LBM requests.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-96`）

</details>

**1.5.3-32.** How does an O-DU determine if an O-RU supports the Extended PRB Grid method for accommodating guard-band NB-IoT carriers?

- A. By checking if the O-RU's maximum supported PRB range exceeds the number of PRBs in the host carrier.
- B. By querying the O-RU for its supported filter pass bandwidth.
- C. By analyzing the O-RU's signal strength and frequency range.
- D. By examining the O-RU's hardware configuration.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-100`）

</details>

**1.5.3-33.** Which type of radio is this test applicable for?

- A. Category A and Category B radios
- B. Category C and Category D radios
- C. Category B and Category C radios
- D. Category A and Category D radios

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-103`）

</details>

**1.5.3-34.** When performing diagnostic tests on an O-RU using the 1PPS output, what criteria should be used to determine if the test has passed?

- A. The measured values must be within the limits specified in Table 3.3.3-2 and Table 3.3.3-3.
- B. The measured values must be significantly different from the pass/fail criteria defined for the air interface.
- C. The measured values must be within the limits specified in Table 3.3.3-2 and Table 3.3.3-3, but the actual criteria can vary depending on the O-RU.
- D. The measured values must be within the limits specified in Table 3.3.3-2 and Table 3.3.3-3, and the O-RU vendor must provide a target performance indication.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-105`）

</details>

**1.5.3-35.** Which authentication method is supported by O-RAN for NETCONF sessions using TLS?

- A. Password-based authentication
- B. X.509 certificate-based authentication
- C. SSH key-based authentication
- D. MAC address-based authentication

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-106`）

</details>

**1.5.3-36.** Which parameter in the O-RAN specification defines the starting PRB for a puncturing pattern?

- A. numPuncPatterns
- B. symbolMask
- C. startPuncPrb
- D. numPuncPrb

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-113`）

</details>

**1.5.3-37.** What happens to the order of U-Plane messages for eAxCs belonging to different ordering groups or having the same relative order within a group?

- A. The O-RU transmits them in a specific order based on their priority.
- B. The order is determined by the transmission window offset and size.
- C. The order is unspecified.
- D. The O-RU transmits them in the order they are received.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-114`）

</details>

**1.5.3-38.** What is the meaning of "c_eAxC" in the context of O-RAN?

- A. A portion of an eAxC flow assigned to a specific O-DU processing element.
- B. A type of antenna used in O-RAN.
- C. A specific protocol used for communication between O-DU and O-RU.
- D. A method for managing power consumption in O-RAN.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-120`）

</details>

**1.5.3-39.** What is the allowed value for the "oDuRoleOfSharedORu" attribute in an O-RAN network?

- A. "HOST_AND_SRO", "HOST", "SRO"
- B. "HOST", "SRO", "GUEST"
- C. "PRIMARY", "SECONDARY", "TERTIARY"
- D. "MASTER", "SLAVE", "DEPENDENT"

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-121`）

</details>

**1.5.3-40.** What is the name of the module responsible for synchronizing the CPRI interface in an O-RAN system?

- A. o-ran-sync-cpri
- B. cpri-interface
- C. o-ran-int-cpri
- D. sync-status

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-123`）

</details>

**1.5.3-41.** What is the term used to describe the minimal spacing guaranteed by the O-DU between the generation time of the CTI message and the start boundary at Ra of the mobile slot N being reported in the message?

- A. TN CTI message timing performance
- B. O-DU CTI message timing performance
- C. CTI message transmission latency
- D. RAN scheduler decision time

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-124`）

</details>

**1.5.3-42.** Which of the following states indicates that the O-RU is synchronized and ready to transmit/receive data?

- A. LOCKED
- B. UNLOCKED
- C. SYNCHRONIZING
- D. CONFIGURING

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-125`）

</details>

**1.5.3-43.** Which of the following clock types is used in a full timing support network according to the G.8275.1 profile?

- A. T-BC-P
- B. T-BC
- C. T-TSC-P
- D. T-BC-A

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-128`）

</details>

**1.5.3-44.** Which of the following compression formats is NOT mentioned in the provided context?

- A. Block-Floating-Point-Selective-Re-Sending
- B. Block-Scaling
- C. Adaptive-Compression
- D. Beam-Space-Compression

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-129`）

</details>

**1.5.3-45.** Which of the following is NOT a data point included in the "multiple-rx-window-measurement-result" section of the O-RAN YANG model?

- A. Start time
- B. End time
- C. Transport session type
- D. Object unit ID

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-130`）

</details>

**1.5.3-46.** In the context of O-RAN user plane configuration, what type of information is represented by the "o-du-port-bitmask" field within the "tx-endpoints" and "rx-endpoints" sections?

- A. The specific O-DU port(s) associated with the endpoint.
- B. The compression algorithm used for the endpoint.
- C. The type of endpoint (e.g., static, dynamic).
- D. The delay characteristics of the endpoint.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-131`）

</details>

**1.5.3-47.** What is the purpose of the "jobStatusNotificationUri" parameter in the Create EI job procedure?

- A. To provide the DUT with a unique identifier for the EI job.
- B. To allow the DUT to receive notifications about the status of the EI job.
- C. To specify the type of EI job being created.
- D. To indicate the priority of the EI job.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-132`）

</details>

**1.5.3-48.** What is the maximum number of transmit EAXC ID groups supported by a particular O-RAN RU, as defined in the context?

- A. max-num-tx-eaxc-id-groups
- B. max-num-tx-eaxc-ids-per-group
- C. representative-tx-eaxc-id
- D. member-tx-eaxc-id

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-133`）

</details>

**1.5.3-49.** What is the primary purpose of the CTI (Control and Transport Interface) functionality in Open RAN?

- A. To provide a fixed bandwidth allocation for the fronthaul traffic.
- B. To enable dynamic bandwidth allocation for fronthaul traffic based on variations in traffic load.
- C. To minimize latency in the downstream direction.
- D. To ensure secure communication between the O-DU and the O-RU.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-137`）

</details>

**1.5.3-50.** Which of the following is NOT a signaling element related to IQ compression in the UC-Plane of an O-RAN system?

- A. U-Plane IQ data field
- B. C-Plane udCompHdr
- C. U-Plane udComphdr
- D. C-Plane ueCompHdr

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-151`）

</details>

**1.5.3-51.** Which of the following is a type of fronthaul interface used in Open Radio Access Networks (O-RAN)?

- A. eCPRI
- B. O-RAN 7.2x Fronthaul
- C. Radio over Ethernet (RoE)
- D. All of the above

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-153`）

</details>

**1.5.3-52.** What happens to user plane data exceeding the maximum packet size?

- A. It is discarded and not transmitted.
- B. It is compressed further to fit within the packet size.
- C. It is split into multiple packets.
- D. It is sent as a single large packet.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-163`）

</details>

**1.5.3-53.** What is the purpose of the O-RAN.WG5.O-DU-O1.0-R003-v09.00 document?

- A. To define the specifications for an Open Radio Access Network (O-RAN) distributed unit (O-DU).
- B. To provide a guide for deploying and configuring O-RAN networks.
- C. To outline the security protocols used in O-RAN networks.
- D. To describe the history and evolution of O-RAN technology.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-170`）

</details>

**1.5.3-54.** How can CTI Session IDs be populated in O-DUs and TNs?

- A. Statically through preconfiguration via their OAM systems
- B. Dynamically through an auto-discovery mechanism
- C. Both 1 and 2
- D. None of the above

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-172`）

</details>

**1.5.3-55.** What is the maximum permissible short-term phase transient error during reference switching for an eEEC clock?

- A. 50 ns/s
- B. 10 ns/s
- C. 100 ns/s
- D. 20 ns/s

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-174`）

</details>

**1.5.3-56.** Which of the following parameters is NOT included in the O-DU delay profile provided by the O-RU Controller to an O-RU that supports adaptive timing capability?

- A. T1a_max_up
- B. TXmax
- C. Ta4_max
- D. T2_max

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-176`）

</details>

**1.5.3-57.** What is the definition of "C-Plane" in the context of Open Radio Access Networks (O-RAN)?

- A. The control plane that manages the communication between the user equipment (UE) and the network.
- B. The control plane responsible for real-time control between the O-DU and the O-RU.
- C. The data plane that handles user traffic between the O-DU and the O-RU.
- D. The control plane that manages the configuration and operation of the O-RAN network.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-177`）

</details>

**1.5.3-58.** In O-RAN, how is the "non-scheduled" information, indicating that certain PRBs are not allocated to any user equipment (UE), conveyed in the C-Plane message?

- A. By using a specific section type with a unique section extension value.
- B. By using a reserved UE identifier (ueId) value of 0x7FFF.
- C. By sending separate C-Plane messages for each port or eAxC_ID.
- D. By using a specific beam group type value.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-178`）

</details>

**1.5.3-59.** Which standard specifies the maximum phase-transient at the output of a device under test for O-RAN SyncE and ESMC/eESMC verification?

- A. ITU-T G.8273.2
- B. ITU-T G.8262/G.8262.1
- C. IEEE 1588
- D. O-RAN WG9

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-186`）

</details>

**1.5.3-60.** Which O-RAN configuration(s) require the O-RU to support network timing as a mandatory synchronization capability?

- A. LLS-C1 only
- B. LLS-C2 only
- C. LLS-C1, LLS-C2, and LLS-C3
- D. LLS-C4 only

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-189`）

</details>

**1.5.3-61.** In an O-RAN system, how is the number of frequency hops (R) for a Section Extension 13 determined?

- A. R is derived from the "max-freq-hops-per-sec-ext-13" M-Plane parameter.
- B. R is calculated as R = extLen / 2.
- C. R is determined by the symbolMask parameter.
- D. R is defined by the startSymbolId parameter in the message header.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-192`）

</details>

**1.5.3-62.** Which of the following tasks is NOT directly related to data transmission or reception in an O-RAN system?

- A. L2 FAPI processing
- B. Timing events processing
- C. UL task scheduling
- D. PDSCH processing

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-207`）

</details>

**1.5.3-63.** What is the purpose of the Shared O-RU in an Open Radio Access Network?

- A. To manage the original O-DUs of the owning operator.
- B. To act as a central point of connection for multiple O-DUs from different operators.
- C. To provide a new management system for the Owning Operator's SMO.
- D. To handle the management of Participating Operator O-DUs.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-210`）

</details>

**1.5.3-64.** What protocol is used by the TER NETCONF Client to activate energy, power, and environmental performance measurement on the O-RU NETCONF Server?

- A. HTTP
- B. TCP
- C. NETCONF
- D. SNMP

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-214`）

</details>

**1.5.3-65.** What is the main difference between the 'static-low-level-tx-endpoint' and 'static-tx-endpoint' configurations in O-RAN's U-plane modeling?

- A. 'static-tx-endpoint' is a new definition with reference to 'static-low-level-tx-endpoint', while the latter is not supported in CPRI Option8.
- B. 'static-low-level-tx-endpoint' is a new definition with reference to 'static-tx-endpoint', while the latter is not supported in CPRI Option8.
- C. 'static-tx-endpoint' is a new definition with reference to 'static-low-level-tx-endpoint', and both are supported in CPRI Option8.
- D. 'static-low-level-tx-endpoint' is a new definition with reference to 'static-tx-endpoint', and both are supported in CPRI Option8.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-219`）

</details>

**1.5.3-66.** What is the purpose of M-Plane monitoring in an O-RAN network?

- A. To monitor the performance of the O-RU and O-DU.
- B. To provide time synchronization between O-RUs and O-DU.
- C. To identify and isolate faulty O-RUs in the event of a malfunction.
- D. To manage the frequency spectrum used by the O-RAN network.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-221`）

</details>

**1.5.3-67.** What is the primary objective of the test case ORAN.WG8.IOT.063?

- A. Verify the successful collection and transfer of MAC statistics for MU-MIMO from the O-DU-OAM-Agent to the SMO.
- B. Ensure the proper configuration of O-CU modules, including NR RRC, NR PDCP, and SDAP.
- C. Test the end-to-end IP connectivity between O-DU and SMO.
- D. Verify the successful establishment of a TLS secure connection between O-DU and SMO.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-222`）

</details>

**1.5.3-68.** What is the primary function of Fronthaul in O-RAN?

- A. Connecting the O-DU to the O-RU
- B. Connecting the O-RU to the core network
- C. Connecting the O-DU to the user equipment
- D. Connecting the O-RU to the O-CU

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-226`）

</details>

**1.5.3-69.** In a hybrid O-RAN management mode, which entity is responsible for configuring the shared O-RU's common aspects like security, operational, transmission, and connectivity parameters?

- A. O-DU
- B. SMO
- C. RAN Intelligent Controller (RIC)
- D. Tenant Operator

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-233`）

</details>

**1.5.3-70.** What are the two methods used to determine network delay in Open Radio Access Networks (O-RAN)?

- A. Defined Transport Method and Measured Transport Method
- B. Pre-defined Delay Method and Computed Delay Method
- C. Static Delay Method and Dynamic Delay Method
- D. Network Delay Method and User Delay Method

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-239`）

</details>

**1.5.3-71.** Which of the following O-RAN test cases verifies the successful reconfiguration of a slice when the RRM policy is updated on the O1 interface?

- A. ORAN.WG8.IOT.040: Verify key performance metrics with the sub-counters at S-NSSAI level.
- B. ORAN.WG8.IOT.041: Verify successful slice re-configuration when RRM Policy is updated on the O1 interface.
- C. ORAN.WG8.IOT.042: Verify slice reconfiguration failure in-case of incorrect S-NSSAI is updated on the O1 interface.
- D. ORAN.WG8.IOT.043: Verify cell activation when O-DU is receiving synchronization from external timing source and sync-state is locked.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-241`）

</details>

**1.5.3-72.** What is the maximum size of the "ald-req-msg" parameter sent by the NETCONF Client to the O-RU in an ALD communication request?

- A. 1200 bytes
- B. 1024 bytes
- C. 512 bytes
- D. 256 bytes

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-242`）

</details>

**1.5.3-73.** What is the primary reason for a Non-RT RIC to delete an A1 policy?

- A. To update the policy with new parameters.
- B. To resolve conflicts with other policies.
- C. Due to the state of the A1 policy type or received policy status information.
- D. To optimize resource utilization.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-243`）

</details>

**1.5.3-74.** What is the primary objective of the SYNC.SE.05 test in the context of O-RAN?

- A. Verify the stability of the primary reference clock.
- B. Evaluate the performance of the HSR/CSR fronthaul interface.
- C. Assess the TIE/MTIE during a brief interruption of the primary reference clock.
- D. Determine the maximum holdover time of the DUT.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-245`）

</details>

**1.5.3-75.** What type of radios are applicable for the test described in the provided context?

- A. Category A and Category B radios
- B. Category C and Category D radios
- C. Only Category A radios
- D. Only Category B radios

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-251`）

</details>

**1.5.3-76.** In an O-RAN network, what is a potential solution to address a situation where emergency traffic exceeds the allocated resources for an emergency slice?

- A. Utilize A1 policies to adjust resource allocation based on real-time network conditions.
- B. Increase the default PRB ratio for the emergency slice to 100%.
- C. Disable video streaming for non-emergency users in the affected area.
- D. Contact the emergency control command to request additional network resources.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-257`）

</details>

**1.5.3-77.** Which of the following PTP packet rates (PPS) is allowed for a variable configuration in an O-RAN system?

- A. Fixed packet rate.
- B. Sync/Delay-Req/Resp messages: 16 PPS and Announce: 8 PPS
- C. Variable (Configurable up to 128PPS)
- D. Variable (Configurable up to 128 PPS)

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-262`）

</details>

**1.5.3-78.** Which YANG modules are used to configure the transmit and receive antenna arrays in an O-RAN system?

- A. o-ran-uplane-conf.yang and ietf-interfaces.yang
- B. o-ran-beamforming.yang and ietf-interfaces.yang
- C. o-ran-uplane-conf.yang and o-ran-beamforming.yang
- D. o-ran-uplane-conf.yang, ietf-interfaces.yang and o-ran-beamforming.yang

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-263`）

</details>

**1.5.3-79.** Which HTTP method is supported for retrieving policy type identifiers in the O-RAN A1 interface?

- A. HTTP PUT
- B. HTTP GET
- C. HTTP DELETE
- D. HTTP POST

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-265`）

</details>

**1.5.3-80.** What is the maximum allowed absolute packet time error at the O-RU UNI for a Regular RU?

- A. 1100ns
- B. 60ns
- C. 190ns
- D. 100ns

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-268`）

</details>

**1.5.3-81.** What is the current status of IEEE 802.1X-2020 support for Open Fronthaul network access control?

- A. Mandatory for all Open Fronthaul interfaces.
- B. Optional, but intended to become mandatory in the future.
- C. Fully implemented and widely adopted in Open Fronthaul networks.
- D. Not supported by the O-RAN Alliance.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-275`）

</details>

**1.5.3-82.** Which of the following timing elements is responsible for providing timing to the O-RU (regular) in an O-RAN network?

- A. T-TSC
- B. PRTC
- C. ePRTC
- D. T-GM

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-276`）

</details>

**1.5.3-83.** What is the purpose of the crsReMask field in relation to the CRS shift pattern?

- A. To differentiate the CRS location for different layers.
- B. To adjust the CRS shift pattern based on the number of antenna ports.
- C. To ensure consistent CRS location assignment across all antenna ports.
- D. To distinguish the CRS shift pattern for different antenna ports.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-283`）

</details>

**1.5.3-84.** What is a primary function of the A1 policy function in an O-RAN architecture?

- A. Managing and enforcing A1 policies.
- B. Providing network slicing capabilities.
- C. Handling radio resource management.
- D. Optimizing data transmission rates.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-288`）

</details>

**1.5.3-85.** Which of the following actions in the Non-RT RIC always causes the policy to be considered as deleted?

- A. Create policy
- B. Delete policy
- C. Update policy
- D. Query policy status

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-296`）

</details>

**1.5.3-86.** Which interface is used by Near-RT RIC to receive measurement data for interference optimization?

- A. A1
- B. E2
- C. O1
- D. None of the above

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-297`）

</details>

**1.5.3-87.** What is the maximum allowed low pass filtered frequency error for an O-DU in Class A?

- A. ±15 ppb
- B. ±5 ppb
- C. 0.1Hz
- D. ±1420ns

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-300`）

</details>

**1.5.3-88.** Which of the following O-DU topologies is considered CONDITIONAL-MANDATORY for the performance test described in the context?

- A. LLS-C3
- B. LLS-C4
- C. LLS-C1
- D. LLS-C2

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-301`）

</details>

**1.5.3-89.** What timing synchronization protocol is used for O-RAN nodes?

- A. NTP
- B. IEEE1588
- C. SNTP
- D. PTP

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-302`）

</details>

**1.5.3-90.** What HTTP method is used to create a policy in an O-RAN A1-P Consumer?

- A. GET
- B. POST
- C. PUT
- D. DELETE

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-307`）

</details>

**1.5.3-91.** When retrieving O-RU controller, event controller, and CA/RA information using DHCPv4, an O-RU can identify itself with both O-RAN registered IANA Enterprise Number and 3GPP registered Enterprise Number using which option?

- A. Option 60
- B. Option 124
- C. Option 128
- D. Option 255

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-310`）

</details>

**1.5.3-92.** Which interface is used for the realization of time-sensitive SON functions implemented within the Near-RT RIC through xApps?

- A. O1
- B. A1
- C. E2
- D. Open Fronthaul

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-316`）

</details>

**1.5.3-93.** What is a potential issue with RACH handling for long latency fronthaul transport links, even if timers are set to their maximum values?

- A. The maximum value of the ra-ResponseWindowSize timer is too short, leading to potential delays in processing RACH messages.
- B. The time required for L1 processing of RACH detection is too long, causing delays in RACH message handling.
- C. The fronthaul transport latency can significantly impact the time required for RACH message processing and resource allocation.
- D. The MAC processing time for allocating DL and UL resources is too long, delaying the response to RACH requests.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-321`）

</details>

**1.5.3-94.** In an O-RAN network, how can HSRs (High-Speed Ring) detect and mitigate the impact of a rogue master clock (GM)?

- A. By comparing the clock attributes of different GMs and selecting the best master based on these attributes.
- B. By monitoring the timestamps generated by the GMs and raising an alarm if inconsistencies are detected.
- C. By utilizing passive port monitoring to detect abnormal timestamps and triggering a manual switch to a trusted GM.
- D. By implementing a distributed consensus mechanism to ensure the accuracy of the time reference.

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-334`）

</details>

**1.5.3-95.** Which of the following standards defines the O1 interface specification for the O-DU component in Open Radio Access Networks (O-RAN)?

- A. 3GPP TS 38.460: NG-RAN; E1 general aspects and principles
- B. O-RAN.WG5.O-DU-O1.0-v07.00: O1 Interface specification for O-DU
- C. O-RAN.WG2.A1AP-v04.00: O-RAN Working Group 2 (Non-RT RIC and A1 interface WG) A1 interface: Application Protocol
- D. 3GPP TS 28.623: Telecommunication management; Generic Network Resource Model (NRM) Integration Reference Point (IRP); Solution Set (SS) definitions

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-335`）

</details>

**1.5.3-96.** Which of the following udCompMeth values results in a udCompParam field length of 16 bits?

- A. 0000b
- B. 0100b
- C. 0101b
- D. 0011b

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-336`）

</details>

**1.5.3-97.** What is the maximum allowed "effective fronthaul round-trip delay" for the O-DU to successfully schedule a response to a RACH preamble within the valid RAR window?

- A. 12 ms
- B. 20 ms
- C. 32 ms
- D. 40 ms

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-339`）

</details>

**1.5.3-98.** What is the recommended mode of network deployment for ORAN specifications?

- A. PTP unaware mode
- B. PTP aware mode
- C. Both PTP aware and unaware modes are recommended
- D. Neither PTP aware nor unaware modes are recommended

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-342`）

</details>

**1.5.3-99.** Which of the following scenarios is most suitable for using Section Extension 12 for C-Plane optimization?

- A. Allocating contiguous PRBs in both time and frequency domains.
- B. Allocating non-contiguous PRBs in both time and frequency domains.
- C. Allocating PRBs with intra-slot frequency hopping.
- D. Allocating contiguous PRBs in frequency domain but non-contiguous in time domain.

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-349`）

</details>

**1.5.3-100.** What is the primary function of the synchronization reference sources (PRTC/T-GM) in an O-RAN architecture?

- A. To provide a secure communication channel between the O-RU and the O-CU.
- B. To ensure accurate time synchronization across the network.
- C. To manage the distribution of radio resources among O-RUs.
- D. To control the power consumption of O-RUs.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-351`）

</details>

**1.5.3-101.** What happens when an O-DU receives a "ready" message from an O-RU, but then the message is dropped before reaching the O-DU?

- A. The O-DU will immediately send a new wake-up command to the O-RU.
- B. The O-DU will wait for a specified timeout period before assuming the O-RU is not ready.
- C. The O-DU will immediately declare the O-RU as unavailable.
- D. The O-DU will continue to operate as if the O-RU is ready.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-355`）

</details>

**1.5.3-102.** What type of notification is sent by the O-RU NETCONF Server to the TER NETCONF Client when the TER supplementary circuitry randomly shorts one or more input lines to the ground?

- A. <external-output-change>
- B. <external-input-change>
- C. <input-state-update>
- D. <port-status-change>

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-356`）

</details>

頁次：[1](1-5-gsma-1.md)　**2**　[3](1-5-gsma-3.md)　[4](1-5-gsma-4.md)　[5](1-5-gsma-5.md)
