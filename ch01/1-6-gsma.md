# 1.6 指標與名詞　GSMA 練習題（79 題）

所屬：[1.6 指標與名詞](1-6.md)

只收 GSMA 訓練題；不含驗證集與測試集，並已去除和驗證／測試題相同或相似、重複、標註衝突的題目。題目依小節歸類（抽查正確率約 95%）。

## 1.6.1 訊號強度：RSRP、RSSI（2 題）

**1.6.1-1.** Which of the following metrics is NOT related to the uplink (UL) in the context of O-RAN?

- A. PUCCH SINR
- B. Path loss for FR2
- C. Distribution of path loss for FR1
- D. PRACH preamble correlation value

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-759`）

</details>

**1.6.1-2.** What do signal strength maps focus on?

- A. The transmission power of the source
- B. The coverage indication of the signal
- C. The aggregate effects of the channel on the transmitted signals
- D. The received power at the spatial location
- E. The signal-to-noise-power ratio (SNR)

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1414`）

</details>

## 1.6.2 訊號品質：RSRQ、SINR、CQI（0 題）

GSMA 沒有這個小節的題目。

## 1.6.3 吞吐量與延遲（30 題）

**1.6.3-1.** What is the maximum end-to-end delay that can be tolerated in virtual reality?

- A. 5-10 milliseconds
- B. 10-15 milliseconds
- C. 15-20 milliseconds
- D. 20-25 milliseconds
- E. 25-30 milliseconds

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-7040`）

</details>

**1.6.3-2.** Which applications require low latency in 5G networks?

- A. Smart home appliances
- B. Smart wearable devices
- C. Autonomous cars
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-7359`）

</details>

**1.6.3-3.** In O-RAN, what factors contribute to the end-to-end latency experienced by a user equipment (UE)?

- A. Proximity and physical path between the UE and Application Function (AF)
- B. Siting of gateway and AFs in relation to each other
- C. Delay characteristics of the physical media
- D. All of the above

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-304`）

</details>

**1.6.3-4.** What type of network testing involves evaluating the delay experienced by data packets travelling across the network?

- A. Frame Pre-emption Testing
- B. Auto-negotiation
- C. Latency TNE
- D. VLAN Manipulation Tests

<details><summary>看答案</summary>

正解：C　（GSMA `oranbench-train-656`）

</details>

**1.6.3-5.** What is a common perception regarding latency in Open Radio Access Networks (O-RAN)?

- A. All sources of additional latency must be limited to 0.5-1.0 ms.
- B. Virtual implementations of LTE L1 on commodity operating systems are preferred for their low latency.
- C. HARQ interleaving is not a viable option for reducing latency in O-RAN deployments.
- D. Split-7 architectures are the most efficient way to reduce latency in O-RAN deployments.

<details><summary>看答案</summary>

正解：A　（GSMA `oranbench-train-1117`）

</details>

**1.6.3-6.** How does packet duplication potentially reduce jitter?

- A. By providing frequency and path diversity
- B. By avoiding retransmissions
- C. By minimizing variance in latency
- D. By improving handover performance
- E. By improving throughput during TCP slow start phase

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-132`）

</details>

**1.6.3-7.** Which of the following is not a KPI (Key Performance Indicator) related to data rate?

- A. Peak data rate
- B. User experiences peak data rate
- C. Spectral efficiency
- D. Air latency
- E. Downlink data rate

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-190`）

</details>

**1.6.3-8.** What is the E2E (end-to-end) latency requirement for factory automation applications?

- A. 25-10 ms
- B. 10-100 ms
- C. 1 ms
- D. 100-1000 ms

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-248`）

</details>

**1.6.3-9.** What is the loopback latency of 4G under ideal operation conditions?

- A. Less than 5 ms
- B. 10-15 ms
- C. 20-25 ms
- D. 30-35 ms
- E. 40-45 ms

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-260`）

</details>

**1.6.3-10.** What is the definition of peak bit rate?

- A. The frequency range that the repeater operates in
- B. A measure of throughput
- C. The ability to track service and resource usage levels
- D. A dataset of personal or entity attributes
- E. The maximum bit rate offered to the user

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-381`）

</details>

**1.6.3-11.** What is the measure of throughput called?

- A. PLMN Operator
- B. Pilot Identity
- C. Peak bit rate
- D. PLMN Area
- E. PLMN Operator

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-422`）

</details>

**1.6.3-12.** What are the components of user plane latency?

- A. Propagation delay, data rate delay, transmission delay
- B. Signal processing delay, scheduling delay, contention delay
- C. Physical layer delay, data link layer delay, transmission delay
- D. Processing delay, medium access delay, transmission delay
- E. Propagation delay, medium access delay, scheduling delay

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-612`）

</details>

**1.6.3-13.** What is the latency requirement for tele-diagnosis, tele-surgery, and tele-rehabilitation in healthcare?

- A. 1-10 ms
- B. 10-100 ms
- C. 50-200 ms
- D. 100-1000 ms

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-630`）

</details>

**1.6.3-14.** What does the 1ms-Challenge refer to?

- A. Achieving a round-trip latency of 1ms
- B. Delivering physical haptic experiences remotely
- C. Interconnecting with the wired internet and mobile internet
- D. Supporting large numbers of devices to communicate with each other simultaneously
- E. Realizing ultra-reliable and low latency network connectivity

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1394`）

</details>

**1.6.3-15.** What is the Round-Trip Time?

- A. The time it takes for a packet to be transmitted from the source to the destination and back to the source
- B. The time between two consecutive packet transmissions
- C. The time it takes for a packet to be generated by the source
- D. The time it takes for a packet to be received by the destination
- E. The time it takes for a packet to be acknowledged by the transmitter

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-1761`）

</details>

**1.6.3-16.** What is the definition of end-to-end latency?

- A. A set of network functions and corresponding resources necessary to provide telecommunication services
- B. The uninterrupted user experience of a service during an access change
- C. The maximum tolerable temporal separation of the onset of two stimuli
- D. The time taken to transfer a given piece of information from a source to a destination
- E. The time period available to repair the first priority timing source

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-2476`）

</details>

**1.6.3-17.** What is the maximum acceptable lapse between a moment (e.g. head rotation) and a frame's pixels corresponding to the new field of view (FOV) for providing a pleasant immersive VR (Virtual Reality) experience?

- A. 5-10 ms
- B. 15-20 ms
- C. 25-30 ms
- D. 35-40 ms
- E. 45-50 ms

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-2839`）

</details>

**1.6.3-18.** What does determinism refer to in communication? [3GPP Release 19]

- A. The stability of the delay between transmission and receipt of messages
- B. The periodicity of communication intervals
- C. The time-criticality of communication
- D. The availability of communication services
- E. The bounded variation of transmission intervals

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-2850`）

</details>

**1.6.3-19.** What are the two major parts of latency in the LTE system?

- A. User Plane (U-plane) latency and Control Plane (C-plane) latency
- B. Radio latency and Core latency
- C. Backhaul latency and Transport latency
- D. Radio latency and U-plane latency

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3005`）

</details>

**1.6.3-20.** What does 'Maximum throughput' refer to?

- A. The maximum power supported by the UE
- B. The root directory of the file system hierarchy on the UICC
- C. The maximum RF bandwidth supported by a BS within an operating band
- D. The maximum achievable throughput for a reference measurement channel
- E. Cells with no radio links

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3707`）

</details>

**1.6.3-21.** What is the phenomenon known as bufferbloat?

- A. The oversaturation of buffers in the network that leads to increased latency and packet loss.
- B. The loss of packets due to congestion in the network.
- C. The degradation of network performance in data centers.
- D. The delay caused by waiting for missing packets in Transmission Control Protocol.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4425`）

</details>

**1.6.3-22.** What is latency in telecommunications?

- A. The time it takes for data to travel from the source to the destination in a network.
- B. The capacity of a network connection to carry data.
- C. The total data transferred over a network in a given period.
- D. The number of errors in data transmission.

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-4680`）

</details>

**1.6.3-23.** What is Air Interface User Rate?

- A. A small program that is intended not to be run on its own, but rather to be embedded inside another application
- B. A performance criterion that describes the degree of correctness with which a function is performed
- C. A set of security attributes associated with a file
- D. The user rate between Mobile Termination and IWF
- E. Generic name for the transport signalling protocols used to set-up and tear-down transport bearers

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5654`）

</details>

**1.6.3-24.** What is the ratio of the average traffic capacity to the volume of the covered region called?

- A. Multi-cell coverage probability
- B. Coverage density
- C. Local data traffic capacity
- D. Energy efficiency
- E. Secrecy throughput

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5727`）

</details>

**1.6.3-25.** What is the goodput?

- A. The capacity of the channel
- B. The rate of successful delivery of data packets over a communication channel
- C. The signal-to-noise ratio
- D. The bit error rate
- E. The modulation technique

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6314`）

</details>

**1.6.3-26.** What is the meaning of Information Data Rate?

- A. Rate of the user information processing
- B. Rate of the user information computation
- C. Rate of the user information storage
- D. Rate of the user information transmitted over the Air Interface
- E. Rate of the user information encryption

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6379`）

</details>

**1.6.3-27.** What is latency?

- A. The time it takes for a packet to be acknowledged by the transmitter
- B. The time it takes for a packet to be generated by the source
- C. The time it takes for a packet to be received by the destination
- D. The time it takes for a packet to be transmitted from the source to the destination
- E. The time it takes for a packet to be transmitted by the destination

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6697`）

</details>

**1.6.3-28.** Which approach can help reduce latency in wireless communication?

- A. Small packets/short TTI
- B. Subcarrier spacing
- C. Flexible OFDMA based TDD subframe
- D. All of the above
- E. None of the above

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-772`）

</details>

**1.6.3-29.** What is a trade-off for low-latency communication?

- A. Latency and reliability
- B. Reliability and energy consumption
- C. Throughput and energy consumption
- D. Throughput and reliability
- E. Latency and energy consumption

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3577`）

</details>

**1.6.3-30.** Which part of the U-plane latency is the main focus for low latency communication?

- A. Radio transmission time
- B. Backhaul time
- C. Core processing time
- D. Transport delay

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6742`）

</details>

## 1.6.4 接通率（Accessibility）、掉話率（Retainability）與可用率（Availability）（3 題）

**1.6.4-1.** Which of the following describes the purpose of the "OR.CONNECTSTATUS.AbnormallRelCalls" measurement in an O-RAN network?

- A. To track the number of successful handover attempts between cells.
- B. To monitor the number of user equipment (UE) contexts that have been released abnormally.
- C. To measure the number of times a UE has successfully connected to the network.
- D. To identify the number of UE contexts that have been released due to network congestion.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1090`）

</details>

**1.6.4-2.** What is the definition of end-to-end service communication availability?

- A. A network deployment that does not interact with a public network
- B. The uninterrupted user experience of a service during an access change
- C. The percentage value of the amount of time the end-to-end communication service is delivered according to a specified QoS
- D. The time taken to transfer a given piece of information from a source to a destination
- E. A set of network functions and corresponding resources necessary to provide telecommunication services

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2420`）

</details>

**1.6.4-3.** What is reliability defined as in the context of communication systems?

- A. The probability that the latency does not exceed a pre-described deadline
- B. The delay a packet experiences from the ingress of a protocol layer at the transmitter to the egress of the same layer at the receiver
- C. The probability of packet drop or packet error
- D. The relation between outage, reliability, latency, and deadline
- E. The trade-offs arising in relation to the definition of time-frequency resources

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6969`）

</details>

## 1.6.5 資源使用率：PRB、處理器、傳輸（4 題）

**1.6.5-1.** Which of the following performance counters is NOT related to NR Cell Utilization in Open RAN?

- A. PUSCH slots
- B. PDSCH slots
- C. PDCCH slots
- D. Distribution of Activated BWP ID

<details><summary>看答案</summary>

正解：D　（GSMA `oranbench-train-729`）

</details>

**1.6.5-2.** What is the time period over which the PRB usage is averaged for the RRU.PrbTotUlDist.BinX counter in O-RAN?

- A. 10 milliseconds
- B. 1 second
- C. 1 minute
- D. 1 hour

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-926`）

</details>

**1.6.5-3.** What is the purpose of the "OR.CellUB.PuschSlot" performance counter in an Open Radio Access Network (O-RAN)?

- A. To measure the number of slots when PDSCH was transmitted.
- B. To measure the number of slots when PUSCH was received.
- C. To measure the number of times a specific user equipment (UE) has been connected to the network.
- D. To measure the overall network bandwidth usage.

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1042`）

</details>

**1.6.5-4.** What KPIs (key performance indicators) are used to calculate the average utilization of PRB (Physical Resource Blocks) over each bearer?

- A. Number of DRBs in the DU, amount of PDCP SDU bits in the downlink
- B. Number of active UEs per 5QI, data volume per 5QI
- C. Number of active users per traffic bearer, total volume of data carried over each bearer, total downlink PRB (DL-PRB) utilization
- D. Number of active users, volume of data, PRB utilization
- E. Number of bearers, number of cells, number of eNBs

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1847`）

</details>

## 1.6.6 常見縮寫（40 題）

**1.6.6-1.** What does the abbreviation (g)PTP stand for? [3GPP Release 18]

- A. General Packet Transfer Protocol
- B. Generic Precision Timing Protocol
- C. Global PTP
- D. Group-based Precision Timing Protocol
- E. Gateway PTP

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6362`）

</details>

**1.6.6-2.** Abbreviate 'EDGE'

- A. Extended Digital Graphics Environment
- B. Electronic Data Generation Equipment
- C. Efficient Data Gateway Encryption
- D. Enhanced Data Rates for Global Evolution

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3217`）

</details>

**1.6.6-3.** What does the acronym OPEX stand for? [ETSI NFV Release 5]

- A. Open Expansion
- B. Operational Expenditure
- C. Organiational Performance Evaluation
- D. Optical Extender
- E. Otherworldly Performance Enhancement X-factor

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4168`）

</details>

**1.6.6-4.** What is the abbreviation for "Lost of Signal" in the context of O-RAN specifications?

- A. LOF
- B. LOS
- C. RAI
- D. SDI

<details><summary>看答案</summary>

正解：B　（GSMA `oranbench-train-1205`）

</details>

**1.6.6-5.** What does the Packet Error Rate (PER) represent?

- A. The rate of PDUs that are successfully delivered by the receiver.
- B. The rate of PDUs that are not successfully delivered by the receiver.
- C. The rate of PDUs that are processed by the sender.
- D. The rate of PDUs that are lost due to congestion.

<details><summary>看答案</summary>

正解：B　（GSMA `srsranbench-train-1129`）

</details>

**1.6.6-6.** What does TRP stand for?

- A. Total Received Power
- B. Total Recovery Power
- C. Total Radiated Power
- D. Total Reflective Power
- E. Total Residual Power

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-10`）

</details>

**1.6.6-7.** What is the definition of Active communication?

- A. The process of apportioning charges between the Home Environment, Serving Network and User.
- B. A UE is in active communication when it has a CS connection established.
- C. Set of radio links simultaneously involved in a specific communication service between an UE and a UTRAN.
- D. The ratio of the average power centered on the assigned channel frequency to the average power centered on an adjacent channel frequency.
- E. The user rate between Mobile Termination and IWF.

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-223`）

</details>

**1.6.6-8.** What does CDMA stand for?

- A. Coherent Digital Modulation Algorithm
- B. Channel Distribution Matrix Association
- C. Circular Dispersive Multipath Analysis
- D. Carrier Detection Multiple Amplification
- E. Code Division Multiple Access

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-485`）

</details>

**1.6.6-9.** What does RNP stand for?

- A. Radio Network Performance
- B. Radio Network Provider
- C. Radio Network Protocol
- D. Radio Network Parameters
- E. Radio Network Planning

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-715`）

</details>

**1.6.6-10.** What does GSM stand for?

- A. Group Session and Management
- B. GSM/EDGE Radio Access Network
- C. GPRS MS and Session
- D. Group Controller and Membership
- E. Global System for Mobile Communications

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-733`）

</details>

**1.6.6-11.** What does RSU stand for?

- A. Remote Service Unit
- B. Road Safety Unit
- C. Road Side Unit
- D. Random Signal Unit

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-824`）

</details>

**1.6.6-12.** What does DSL stand for in telecommunications?

- A. Dynamic Spectrum Leasing
- B. Data System Link
- C. Distributed Signal Line
- D. Digital Subscriber Line

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-841`）

</details>

**1.6.6-13.** What does RLSS stand for?

- A. Received Location Query Signal
- B. Received Location Signal Strength
- C. Registered Location Query Protocol
- D. Registered Location Secure Server

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-973`）

</details>

**1.6.6-14.** What does the acronym GPS stand for?

- A. General purpose system
- B. Global power source
- C. Global programming system
- D. General public service
- E. Global positioning system

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1389`）

</details>

**1.6.6-15.** What does the abbreviation QoS stand for?

- A. Quality of Signals
- B. Quantum of Solace
- C. Queueing of Signals
- D. Quality of Service
- E. Quality of Systems

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1475`）

</details>

**1.6.6-16.** What does SINR stand for?

- A. Signal-Interference-Noise Relation
- B. Signal-Interference-Noise Reduction
- C. Signal-to-Interference-Noise Ratio
- D. Signal-in-Noise Ratio

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-1730`）

</details>

**1.6.6-17.** What does EE stand for?

- A. Efficiency Enhancement
- B. Error Exponent
- C. Error Efficiency
- D. Energy Exponent
- E. Energy Efficiency

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1735`）

</details>

**1.6.6-18.** What does TDD stand for?

- A. Universal Mobile Telecommunications System
- B. Uniform Linear Array
- C. Urban Microcell
- D. Time-Division Duplex
- E. Small-Cell Base Station

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-1855`）

</details>

**1.6.6-19.** What does the acronym OFDM stand for?

- A. Open frequency distribution model
- B. Optimal frequency division model
- C. Optical frequency display method
- D. Organic food division mechanism
- E. Orthogonal frequency-division multiplexing

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-1973`）

</details>

**1.6.6-20.** What does OFDM stand for?

- A. Orthogonal Fuzzy Decision Method
- B. Outer Fractional Division Multiplexing
- C. Orthogonal Frequency-Division Multiplexing
- D. Optimal Fractional Differential Method
- E. Optimal Fast Demodulation

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2249`）

</details>

**1.6.6-21.** What does MAC stand for?

- A. Messages Authentication Code
- B. Medium Authentication Control
- C. Media Access Control
- D. Mobile Authentication Control
- E. Multiple Access Control

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-2995`）

</details>

**1.6.6-22.** What does EARFCN stand for? [3GPP Release 18]

- A. EARly Frequency Channel Number
- B. Early Frequency Resource Channel Number
- C. E-UTRA Absolute Radio Frequency Channel Number
- D. Ethernet Absolute Radio Frequency Channel Number
- E. Eventual Absolute Radio Frequency Channel Number

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3289`）

</details>

**1.6.6-23.** What does PDR stand for?

- A. Packet Delay Ratio
- B. Packet Duplication Rate
- C. Packet Data Rate
- D. Packet Delivery Ratio
- E. Packet Loss Rate

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-3294`）

</details>

**1.6.6-24.** What does the acronym 'LAN' stand for?

- A. Local Access Network
- B. Long Area Network
- C. Local Area Network
- D. Wide Area Network

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3519`）

</details>

**1.6.6-25.** What does SE stand for?

- A. Standard Results
- B. Single-Cell Minimum Mean-Squared Error
- C. Spectral Efficiency
- D. Small Cell
- E. Matrix Analysis

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-3532`）

</details>

**1.6.6-26.** What does the term 'NG-RAN' stand for?

- A. Next Generation Radio Access Network
- B. Network Group - Radio Access Node
- C. New Generation - Radio Access Node
- D. Next Generation - Radio Access Node

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3571`）

</details>

**1.6.6-27.** What does the abbreviation WAS stand for?

- A. Wireless Access Systems
- B. Radio Local Area Networks
- C. Fixed Wireless Access
- D. Unlicensed National Information Infrastructure
- E. None of the above

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-3875`）

</details>

**1.6.6-28.** What does NB-IoT stand for?

- A. Non-Broadcast Internet of Things
- B. Narrow Band Integrated Optimization Technology
- C. Narrow Band Intelligent Optimization Task
- D. Narrow Band Internet of Things
- E. Non-Broadcast Integrated Optimization Task

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-4213`）

</details>

**1.6.6-29.** What is the definition of COT?

- A. Channel access priority class
- B. Channel Occupancy Time
- C. Licensed Assisted Access
- D. Max Channel Occupancy Time
- E. Autonomoulsy Uplink\_Downlink Feedback Indication

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-4238`）

</details>

**1.6.6-30.** What does the acronym 3G stand for?

- A. Third-geographical
- B. Three-generation
- C. Third-generation
- D. Third-generation partnership project
- E. Third-generation network

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-4302`）

</details>

**1.6.6-31.** What does BWP stand for?

- A. Bandwidth Wave Propagation
- B. Broadcast Wave Protocol
- C. Binary Wave Parameter
- D. Baseband Wave Processing
- E. Bandwidth Part

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-4518`）

</details>

**1.6.6-32.** What does the acronym IoT stand for?

- A. Internet of technology
- B. Industrial Internet-of-things
- C. Intranet of things
- D. Internet of transport
- E. International telecommunications organization

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-5243`）

</details>

**1.6.6-33.** What does ELF stand for in the context of frequency bands? [IEEE C95.1]

- A. Electromagnetic Frequency Limit
- B. Electronic Low Frequency
- C. Excessive Light Frequency
- D. Elevated Frequency Levels
- E. Extremely Low Frequency

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5367`）

</details>

**1.6.6-34.** What does the acronym LTE-A stand for?

- A. Low-energy transmission algorithm
- B. Long Term Evolution automation
- C. Long-range transmission enhancement
- D. LTE-Advanced
- E. Latency tracking enhancement

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-5657`）

</details>

**1.6.6-35.** What does DSRC stand for in the context of Vehicular Ad-hoc Networks (VANET)?

- A. Dual Spectrum Radar Communications
- B. Dynamic Signal Routing Communications
- C. Digital Sensor Radar Communications
- D. Distributed Server Routing Communications
- E. Dedicated Short Range Communications

<details><summary>看答案</summary>

正解：E　（GSMA `teleqna-train-5698`）

</details>

**1.6.6-36.** What does the abbreviation 'MCS' stand for?

- A. Modulation and coding scheme
- B. Multicast broadcast services
- C. Master cell group
- D. Timing advance
- E. Radio resource management

<details><summary>看答案</summary>

正解：A　（GSMA `teleqna-train-6156`）

</details>

**1.6.6-37.** What is the abbreviation for 'Sounding reference signal'?

- A. RS
- B. SRS
- C. PRACH
- D. DL-SCH
- E. CS-RNTI

<details><summary>看答案</summary>

正解：B　（GSMA `teleqna-train-6304`）

</details>

**1.6.6-38.** What does the acronym SDM stand for?

- A. Switching and Demultiplexing
- B. Spatial Divisive Multiplexing
- C. Spatial Decomposition Multiplexer
- D. Spatial Division Multiplexing
- E. Systematic Data Manipulation

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6351`）

</details>

**1.6.6-39.** What does RF stand for?

- A. Relay Forwarding
- B. Remote Feedback
- C. Resource Fragmentation
- D. Radio Frequency

<details><summary>看答案</summary>

正解：D　（GSMA `teleqna-train-6526`）

</details>

**1.6.6-40.** What does CCI stand for?

- A. Carrier Channel Interference
- B. Cooperative Communication Interface
- C. Co-Channel Interference
- D. Cross-Correlation Indicator

<details><summary>看答案</summary>

正解：C　（GSMA `teleqna-train-6372`）

</details>

## 1.6.7 移動性指標：換手成功率（0 題）

GSMA 沒有這個小節的題目。
