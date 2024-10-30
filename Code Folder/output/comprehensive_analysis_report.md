# ICS/OT Network Analysis Report

## Network Statistics
- Total Nodes: 31
- Total Edges: 31
- Network Density: 0.067
- Network Diameter: 10
- Is Tree: False
- Is Forest: False
- Number of Endpoints: 13

## Network Structure
### Components
- Number of Connected Components: 1
- Largest Component Size: 31

### Cycles
- Cycle 1: Device 4 -> Device 5 -> Device 6 -> Device 7 -> PLC 3 -> Device 4

## Critical Nodes Analysis
- Switch 1:
  * Splits network into 6 components
  * Degree: 6
  * Betweenness Centrality: 0.667
- PLC 4:
  * Splits network into 5 components
  * Degree: 5
  * Betweenness Centrality: 0.253
- HMI 1:
  * Splits network into 4 components
  * Degree: 4
  * Betweenness Centrality: 0.687
- PA Signal Line:
  * Splits network into 4 components
  * Degree: 4
  * Betweenness Centrality: 0.193
- I/O 1:
  * Splits network into 3 components
  * Degree: 3
  * Betweenness Centrality: 0.131
- HMI 2:
  * Splits network into 2 components
  * Degree: 2
  * Betweenness Centrality: 0.287
- HMI 3:
  * Splits network into 2 components
  * Degree: 2
  * Betweenness Centrality: 0.239
- PLC 1:
  * Splits network into 2 components
  * Degree: 2
  * Betweenness Centrality: 0.186
- PLC 2:
  * Splits network into 2 components
  * Degree: 2
  * Betweenness Centrality: 0.287
- segment coupler:
  * Splits network into 2 components
  * Degree: 2
  * Betweenness Centrality: 0.239
- PLC 3:
  * Splits network into 2 components
  * Degree: 3
  * Betweenness Centrality: 0.241
- Firewall 2:
  * Splits network into 2 components
  * Degree: 2
  * Betweenness Centrality: 0.186
- Switch 2:
  * Splits network into 2 components
  * Degree: 2
  * Betweenness Centrality: 0.129
- PLC 5:
  * Splits network into 2 components
  * Degree: 2
  * Betweenness Centrality: 0.067
- DMZ Internal Firewall:
  * Splits network into 1 components
  * Degree: 1
  * Betweenness Centrality: 0.000
- SCADA Server:
  * Splits network into 1 components
  * Degree: 1
  * Betweenness Centrality: 0.000
- EWS:
  * Splits network into 1 components
  * Degree: 1
  * Betweenness Centrality: 0.000
- Sensor 1:
  * Splits network into 1 components
  * Degree: 1
  * Betweenness Centrality: 0.000
- Actuator 1:
  * Splits network into 1 components
  * Degree: 1
  * Betweenness Centrality: 0.000
- Device 1:
  * Splits network into 1 components
  * Degree: 1
  * Betweenness Centrality: 0.000
- Device 2:
  * Splits network into 1 components
  * Degree: 1
  * Betweenness Centrality: 0.000
- Device 3:
  * Splits network into 1 components
  * Degree: 1
  * Betweenness Centrality: 0.000
- Device 4:
  * Splits network into 1 components
  * Degree: 2
  * Betweenness Centrality: 0.062
- Device 5:
  * Splits network into 1 components
  * Degree: 2
  * Betweenness Centrality: 0.002
- Device 6:
  * Splits network into 1 components
  * Degree: 2
  * Betweenness Centrality: 0.002
- Device 7:
  * Splits network into 1 components
  * Degree: 2
  * Betweenness Centrality: 0.062
- Device 8:
  * Splits network into 1 components
  * Degree: 1
  * Betweenness Centrality: 0.000
- Device 9:
  * Splits network into 1 components
  * Degree: 1
  * Betweenness Centrality: 0.000
- Device 10:
  * Splits network into 1 components
  * Degree: 1
  * Betweenness Centrality: 0.000
- Device 11:
  * Splits network into 1 components
  * Degree: 1
  * Betweenness Centrality: 0.000
- Crown Jewel:
  * Splits network into 1 components
  * Degree: 1
  * Betweenness Centrality: 0.000

## Security Risk Assessment
### High Risk Nodes (Risk Score >= 50)

#### HMI 1
Risk Score: 100.0/100
Security Metrics:
- PLC Connections: 3
- HMI Connections: 0
- Field Device Connections: 0
- Minimum Path to PLC: 1
- Minimum Path to HMI: 0
- Exposure Score: 11.50


#### Switch 1
Risk Score: 92.6/100
Security Metrics:
- PLC Connections: 0
- HMI Connections: 3
- Field Device Connections: 0
- Minimum Path to PLC: 2
- Minimum Path to HMI: 1
- Exposure Score: 7.42


#### PLC 4
Risk Score: 77.2/100
Security Metrics:
- PLC Connections: 0
- HMI Connections: 1
- Field Device Connections: 4
- Minimum Path to PLC: 0
- Minimum Path to HMI: 1
- Exposure Score: 8.75


#### PLC 5
Risk Score: 66.4/100
Security Metrics:
- PLC Connections: 0
- HMI Connections: 0
- Field Device Connections: 0
- Minimum Path to PLC: 0
- Minimum Path to HMI: 3
- Exposure Score: 2.38


#### HMI 3
Risk Score: 62.3/100
Security Metrics:
- PLC Connections: 0
- HMI Connections: 0
- Field Device Connections: 0
- Minimum Path to PLC: 3
- Minimum Path to HMI: 0
- Exposure Score: 2.00


#### PLC 3
Risk Score: 58.6/100
Security Metrics:
- PLC Connections: 0
- HMI Connections: 1
- Field Device Connections: 2
- Minimum Path to PLC: 0
- Minimum Path to HMI: 1
- Exposure Score: 6.75


#### HMI 2
Risk Score: 53.6/100
Security Metrics:
- PLC Connections: 1
- HMI Connections: 0
- Field Device Connections: 0
- Minimum Path to PLC: 1
- Minimum Path to HMI: 0
- Exposure Score: 5.50

## Detected Anomalies
### Centrality Measures for Anomalous Nodes
```
Node Label          Degree Centrality        Betweenness Centrality   Closeness Centrality     Eigenvector Centrality   
------------------------------------------------------------------------------------------------------------------------
HMI 1               0.133333                 0.687356                 0.348837                 0.417677                 
Switch 1            0.200000                 0.666667                 0.344828                 0.561154                 
PLC 4               0.166667                 0.252874                 0.236220                 0.214164                 
```

## Spectral Analysis
### Network Spectral Properties
- Spectral Radius: 7.272
- Fiedler Value (Algebraic Connectivity): 0.054

Fiedler vector interpretation:
- The Fiedler value measures the network's connectivity robustness
- Larger values indicate better connectivity and harder-to-disconnect networks
- The Fiedler vector components can identify natural network partitions

### Top 10 Nodes by Fiedler Vector Magnitude
```
Node Label          Fiedler Component   Interpretation
----------------------------------------------------------------------
Device 1            0.304603            Network splitter
Device 2            0.304603            Network splitter
Device 3            0.304603            Network splitter
PA Signal Line      0.288084            Network splitter
Crown Jewel         -0.264885           Network connector
PLC 5               -0.250521           Network connector
segment coupler     0.222908            Network splitter
Switch 2            -0.222571           Network connector
Device 8            -0.202675           Network connector
Device 9            -0.202675           Network connector
```

### Spectral Analysis Insights
- Network shows signs of weak connectivity and potential bottlenecks
- System may be vulnerable to disconnection through targeted attacks

- Spectral radius of 7.272 indicates high centralization with potential critical nodes

### Network Bisection Analysis
- Positive Fiedler component group: 16 nodes
- Negative Fiedler component group: 15 nodes
This natural bisection suggests a potential critical boundary in the network.

## Path Analysis
### Shortest Paths to Critical Assets
From Switch 1:
- To SCADA Server: Switch 1 -> SCADA Server (1 hops)
- To HMI 1: Switch 1 -> HMI 1 (1 hops)
- To HMI 2: Switch 1 -> HMI 2 (1 hops)
- To HMI 3: Switch 1 -> HMI 3 (1 hops)
- To Crown Jewel: Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (5 hops)

From DMZ Internal Firewall:
- To SCADA Server: DMZ Internal Firewall -> Switch 1 -> SCADA Server (2 hops)
- To HMI 1: DMZ Internal Firewall -> Switch 1 -> HMI 1 (2 hops)
- To HMI 2: DMZ Internal Firewall -> Switch 1 -> HMI 2 (2 hops)
- To HMI 3: DMZ Internal Firewall -> Switch 1 -> HMI 3 (2 hops)
- To Crown Jewel: DMZ Internal Firewall -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (6 hops)

From SCADA Server:
- To SCADA Server: SCADA Server (0 hops)
- To HMI 1: SCADA Server -> Switch 1 -> HMI 1 (2 hops)
- To HMI 2: SCADA Server -> Switch 1 -> HMI 2 (2 hops)
- To HMI 3: SCADA Server -> Switch 1 -> HMI 3 (2 hops)
- To Crown Jewel: SCADA Server -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (6 hops)

From EWS:
- To SCADA Server: EWS -> Switch 1 -> SCADA Server (2 hops)
- To HMI 1: EWS -> Switch 1 -> HMI 1 (2 hops)
- To HMI 2: EWS -> Switch 1 -> HMI 2 (2 hops)
- To HMI 3: EWS -> Switch 1 -> HMI 3 (2 hops)
- To Crown Jewel: EWS -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (6 hops)

From HMI 1:
- To SCADA Server: HMI 1 -> Switch 1 -> SCADA Server (2 hops)
- To HMI 1: HMI 1 (0 hops)
- To HMI 2: HMI 1 -> Switch 1 -> HMI 2 (2 hops)
- To HMI 3: HMI 1 -> Switch 1 -> HMI 3 (2 hops)
- To Crown Jewel: HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (6 hops)

From HMI 2:
- To SCADA Server: HMI 2 -> Switch 1 -> SCADA Server (2 hops)
- To HMI 1: HMI 2 -> Switch 1 -> HMI 1 (2 hops)
- To HMI 2: HMI 2 (0 hops)
- To HMI 3: HMI 2 -> Switch 1 -> HMI 3 (2 hops)
- To Crown Jewel: HMI 2 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (6 hops)

From HMI 3:
- To SCADA Server: HMI 3 -> Switch 1 -> SCADA Server (2 hops)
- To HMI 1: HMI 3 -> Switch 1 -> HMI 1 (2 hops)
- To HMI 2: HMI 3 -> Switch 1 -> HMI 2 (2 hops)
- To HMI 3: HMI 3 (0 hops)
- To Crown Jewel: HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (4 hops)

From PLC 1:
- To SCADA Server: PLC 1 -> HMI 1 -> Switch 1 -> SCADA Server (3 hops)
- To HMI 1: PLC 1 -> HMI 1 (1 hops)
- To HMI 2: PLC 1 -> HMI 1 -> Switch 1 -> HMI 2 (3 hops)
- To HMI 3: PLC 1 -> HMI 1 -> Switch 1 -> HMI 3 (3 hops)
- To Crown Jewel: PLC 1 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (7 hops)

From I/O 1:
- To SCADA Server: I/O 1 -> PLC 1 -> HMI 1 -> Switch 1 -> SCADA Server (4 hops)
- To HMI 1: I/O 1 -> PLC 1 -> HMI 1 (2 hops)
- To HMI 2: I/O 1 -> PLC 1 -> HMI 1 -> Switch 1 -> HMI 2 (4 hops)
- To HMI 3: I/O 1 -> PLC 1 -> HMI 1 -> Switch 1 -> HMI 3 (4 hops)
- To Crown Jewel: I/O 1 -> PLC 1 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (8 hops)

From Sensor 1:
- To SCADA Server: Sensor 1 -> I/O 1 -> PLC 1 -> HMI 1 -> Switch 1 -> SCADA Server (5 hops)
- To HMI 1: Sensor 1 -> I/O 1 -> PLC 1 -> HMI 1 (3 hops)
- To HMI 2: Sensor 1 -> I/O 1 -> PLC 1 -> HMI 1 -> Switch 1 -> HMI 2 (5 hops)
- To HMI 3: Sensor 1 -> I/O 1 -> PLC 1 -> HMI 1 -> Switch 1 -> HMI 3 (5 hops)
- To Crown Jewel: Sensor 1 -> I/O 1 -> PLC 1 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (9 hops)

From Actuator 1:
- To SCADA Server: Actuator 1 -> I/O 1 -> PLC 1 -> HMI 1 -> Switch 1 -> SCADA Server (5 hops)
- To HMI 1: Actuator 1 -> I/O 1 -> PLC 1 -> HMI 1 (3 hops)
- To HMI 2: Actuator 1 -> I/O 1 -> PLC 1 -> HMI 1 -> Switch 1 -> HMI 2 (5 hops)
- To HMI 3: Actuator 1 -> I/O 1 -> PLC 1 -> HMI 1 -> Switch 1 -> HMI 3 (5 hops)
- To Crown Jewel: Actuator 1 -> I/O 1 -> PLC 1 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (9 hops)

From PLC 2:
- To SCADA Server: PLC 2 -> HMI 1 -> Switch 1 -> SCADA Server (3 hops)
- To HMI 1: PLC 2 -> HMI 1 (1 hops)
- To HMI 2: PLC 2 -> HMI 1 -> Switch 1 -> HMI 2 (3 hops)
- To HMI 3: PLC 2 -> HMI 1 -> Switch 1 -> HMI 3 (3 hops)
- To Crown Jewel: PLC 2 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (7 hops)

From segment coupler:
- To SCADA Server: segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> SCADA Server (4 hops)
- To HMI 1: segment coupler -> PLC 2 -> HMI 1 (2 hops)
- To HMI 2: segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 2 (4 hops)
- To HMI 3: segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 3 (4 hops)
- To Crown Jewel: segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (8 hops)

From PA Signal Line:
- To SCADA Server: PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> SCADA Server (5 hops)
- To HMI 1: PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 (3 hops)
- To HMI 2: PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 2 (5 hops)
- To HMI 3: PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 3 (5 hops)
- To Crown Jewel: PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (9 hops)

From Device 1:
- To SCADA Server: Device 1 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> SCADA Server (6 hops)
- To HMI 1: Device 1 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 (4 hops)
- To HMI 2: Device 1 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 2 (6 hops)
- To HMI 3: Device 1 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 3 (6 hops)
- To Crown Jewel: Device 1 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (10 hops)

From Device 2:
- To SCADA Server: Device 2 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> SCADA Server (6 hops)
- To HMI 1: Device 2 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 (4 hops)
- To HMI 2: Device 2 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 2 (6 hops)
- To HMI 3: Device 2 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 3 (6 hops)
- To Crown Jewel: Device 2 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (10 hops)

From Device 3:
- To SCADA Server: Device 3 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> SCADA Server (6 hops)
- To HMI 1: Device 3 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 (4 hops)
- To HMI 2: Device 3 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 2 (6 hops)
- To HMI 3: Device 3 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 3 (6 hops)
- To Crown Jewel: Device 3 -> PA Signal Line -> segment coupler -> PLC 2 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (10 hops)

From PLC 3:
- To SCADA Server: PLC 3 -> HMI 1 -> Switch 1 -> SCADA Server (3 hops)
- To HMI 1: PLC 3 -> HMI 1 (1 hops)
- To HMI 2: PLC 3 -> HMI 1 -> Switch 1 -> HMI 2 (3 hops)
- To HMI 3: PLC 3 -> HMI 1 -> Switch 1 -> HMI 3 (3 hops)
- To Crown Jewel: PLC 3 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (7 hops)

From Device 4:
- To SCADA Server: Device 4 -> PLC 3 -> HMI 1 -> Switch 1 -> SCADA Server (4 hops)
- To HMI 1: Device 4 -> PLC 3 -> HMI 1 (2 hops)
- To HMI 2: Device 4 -> PLC 3 -> HMI 1 -> Switch 1 -> HMI 2 (4 hops)
- To HMI 3: Device 4 -> PLC 3 -> HMI 1 -> Switch 1 -> HMI 3 (4 hops)
- To Crown Jewel: Device 4 -> PLC 3 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (8 hops)

From Device 5:
- To SCADA Server: Device 5 -> Device 4 -> PLC 3 -> HMI 1 -> Switch 1 -> SCADA Server (5 hops)
- To HMI 1: Device 5 -> Device 4 -> PLC 3 -> HMI 1 (3 hops)
- To HMI 2: Device 5 -> Device 4 -> PLC 3 -> HMI 1 -> Switch 1 -> HMI 2 (5 hops)
- To HMI 3: Device 5 -> Device 4 -> PLC 3 -> HMI 1 -> Switch 1 -> HMI 3 (5 hops)
- To Crown Jewel: Device 5 -> Device 4 -> PLC 3 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (9 hops)

From Device 6:
- To SCADA Server: Device 6 -> Device 7 -> PLC 3 -> HMI 1 -> Switch 1 -> SCADA Server (5 hops)
- To HMI 1: Device 6 -> Device 7 -> PLC 3 -> HMI 1 (3 hops)
- To HMI 2: Device 6 -> Device 7 -> PLC 3 -> HMI 1 -> Switch 1 -> HMI 2 (5 hops)
- To HMI 3: Device 6 -> Device 7 -> PLC 3 -> HMI 1 -> Switch 1 -> HMI 3 (5 hops)
- To Crown Jewel: Device 6 -> Device 7 -> PLC 3 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (9 hops)

From Device 7:
- To SCADA Server: Device 7 -> PLC 3 -> HMI 1 -> Switch 1 -> SCADA Server (4 hops)
- To HMI 1: Device 7 -> PLC 3 -> HMI 1 (2 hops)
- To HMI 2: Device 7 -> PLC 3 -> HMI 1 -> Switch 1 -> HMI 2 (4 hops)
- To HMI 3: Device 7 -> PLC 3 -> HMI 1 -> Switch 1 -> HMI 3 (4 hops)
- To Crown Jewel: Device 7 -> PLC 3 -> HMI 1 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (8 hops)

From PLC 4:
- To SCADA Server: PLC 4 -> HMI 2 -> Switch 1 -> SCADA Server (3 hops)
- To HMI 1: PLC 4 -> HMI 2 -> Switch 1 -> HMI 1 (3 hops)
- To HMI 2: PLC 4 -> HMI 2 (1 hops)
- To HMI 3: PLC 4 -> HMI 2 -> Switch 1 -> HMI 3 (3 hops)
- To Crown Jewel: PLC 4 -> HMI 2 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (7 hops)

From Device 8:
- To SCADA Server: Device 8 -> PLC 4 -> HMI 2 -> Switch 1 -> SCADA Server (4 hops)
- To HMI 1: Device 8 -> PLC 4 -> HMI 2 -> Switch 1 -> HMI 1 (4 hops)
- To HMI 2: Device 8 -> PLC 4 -> HMI 2 (2 hops)
- To HMI 3: Device 8 -> PLC 4 -> HMI 2 -> Switch 1 -> HMI 3 (4 hops)
- To Crown Jewel: Device 8 -> PLC 4 -> HMI 2 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (8 hops)

From Device 9:
- To SCADA Server: Device 9 -> PLC 4 -> HMI 2 -> Switch 1 -> SCADA Server (4 hops)
- To HMI 1: Device 9 -> PLC 4 -> HMI 2 -> Switch 1 -> HMI 1 (4 hops)
- To HMI 2: Device 9 -> PLC 4 -> HMI 2 (2 hops)
- To HMI 3: Device 9 -> PLC 4 -> HMI 2 -> Switch 1 -> HMI 3 (4 hops)
- To Crown Jewel: Device 9 -> PLC 4 -> HMI 2 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (8 hops)

From Device 10:
- To SCADA Server: Device 10 -> PLC 4 -> HMI 2 -> Switch 1 -> SCADA Server (4 hops)
- To HMI 1: Device 10 -> PLC 4 -> HMI 2 -> Switch 1 -> HMI 1 (4 hops)
- To HMI 2: Device 10 -> PLC 4 -> HMI 2 (2 hops)
- To HMI 3: Device 10 -> PLC 4 -> HMI 2 -> Switch 1 -> HMI 3 (4 hops)
- To Crown Jewel: Device 10 -> PLC 4 -> HMI 2 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (8 hops)

From Device 11:
- To SCADA Server: Device 11 -> PLC 4 -> HMI 2 -> Switch 1 -> SCADA Server (4 hops)
- To HMI 1: Device 11 -> PLC 4 -> HMI 2 -> Switch 1 -> HMI 1 (4 hops)
- To HMI 2: Device 11 -> PLC 4 -> HMI 2 (2 hops)
- To HMI 3: Device 11 -> PLC 4 -> HMI 2 -> Switch 1 -> HMI 3 (4 hops)
- To Crown Jewel: Device 11 -> PLC 4 -> HMI 2 -> Switch 1 -> HMI 3 -> Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (8 hops)

From Firewall 2:
- To SCADA Server: Firewall 2 -> HMI 3 -> Switch 1 -> SCADA Server (3 hops)
- To HMI 1: Firewall 2 -> HMI 3 -> Switch 1 -> HMI 1 (3 hops)
- To HMI 2: Firewall 2 -> HMI 3 -> Switch 1 -> HMI 2 (3 hops)
- To HMI 3: Firewall 2 -> HMI 3 (1 hops)
- To Crown Jewel: Firewall 2 -> Switch 2 -> PLC 5 -> Crown Jewel (3 hops)

From Switch 2:
- To SCADA Server: Switch 2 -> Firewall 2 -> HMI 3 -> Switch 1 -> SCADA Server (4 hops)
- To HMI 1: Switch 2 -> Firewall 2 -> HMI 3 -> Switch 1 -> HMI 1 (4 hops)
- To HMI 2: Switch 2 -> Firewall 2 -> HMI 3 -> Switch 1 -> HMI 2 (4 hops)
- To HMI 3: Switch 2 -> Firewall 2 -> HMI 3 (2 hops)
- To Crown Jewel: Switch 2 -> PLC 5 -> Crown Jewel (2 hops)

From PLC 5:
- To SCADA Server: PLC 5 -> Switch 2 -> Firewall 2 -> HMI 3 -> Switch 1 -> SCADA Server (5 hops)
- To HMI 1: PLC 5 -> Switch 2 -> Firewall 2 -> HMI 3 -> Switch 1 -> HMI 1 (5 hops)
- To HMI 2: PLC 5 -> Switch 2 -> Firewall 2 -> HMI 3 -> Switch 1 -> HMI 2 (5 hops)
- To HMI 3: PLC 5 -> Switch 2 -> Firewall 2 -> HMI 3 (3 hops)
- To Crown Jewel: PLC 5 -> Crown Jewel (1 hops)

From Crown Jewel:
- To SCADA Server: Crown Jewel -> PLC 5 -> Switch 2 -> Firewall 2 -> HMI 3 -> Switch 1 -> SCADA Server (6 hops)
- To HMI 1: Crown Jewel -> PLC 5 -> Switch 2 -> Firewall 2 -> HMI 3 -> Switch 1 -> HMI 1 (6 hops)
- To HMI 2: Crown Jewel -> PLC 5 -> Switch 2 -> Firewall 2 -> HMI 3 -> Switch 1 -> HMI 2 (6 hops)
- To HMI 3: Crown Jewel -> PLC 5 -> Switch 2 -> Firewall 2 -> HMI 3 (4 hops)
- To Crown Jewel: Crown Jewel (0 hops)

## Analysis Details- Analysis completed at: 2024-10-30 10:19:07
- Output directory: C:\Users\Service Casket\Desktop\Network Analysis Tool\output

## Generated Files- risk_level_visualization.png
- network_analysis_report.txt
- security_analysis_report.txt
- comprehensive_analysis_report.md

## Summary Statistics- Average node degree: 2.0
- Graph diameter: 10
- Average shortest path length: 4.67
- Graph density: 0.067
- Number of high-risk nodes: 7
- Number of anomalous nodes: 3
