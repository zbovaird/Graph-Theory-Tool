# Post-Incident Network Analysis Report

## Degree Distribution Comparison

![Degree Distribution Comparison](degree_distribution_comparison.png)

## Network Before Incident

![Network Before Incident](network_before.png)

## Network After Incident

![Network After Incident](network_after.png)

## Spectral Metrics

| Metric             |    Before |     After |    Change |
|:-------------------|----------:|----------:|----------:|
| Spectral Radius    | 2.95488   | 9.17427   | 6.21939   |
| Fiedler Eigenvalue | 0.0571823 | 0.0873856 | 0.0302033 |

## Other Network-Level Changes

| Metric                |      Change |
|:----------------------|------------:|
| Average Clustering    |  0.0473118  |
| Network Density       |  0.00645161 |
| Average Degree        |  0.193548   |
| Components            |  0          |
| Average Path Length   | -0.0580645  |
| Network Diameter      |  0          |
| Number of Communities | -1          |

## Structural Changes

| Structural Change          |   Value |
|:---------------------------|--------:|
| New Nodes                  |       0 |
| Removed Nodes              |       0 |
| New Edges                  |       3 |
| Removed Edges              |       0 |
| Degree Distribution Change |       3 |

## Node Metrics Changes

Changes in Node Metrics detected as anomalies by Isolation Forest:

|    Degree |   Betweenness |   Closeness |   Eigenvector |   anomaly |
|----------:|--------------:|------------:|--------------:|----------:|
| 0         |      0        | 0           |   -0.0508355  |         1 |
| 0         |     -0.298851 | 0           |   -0.0367362  |        -1 |
| 0.1       |      0.236782 | 0.078458    |    0.252463   |        -1 |
| 0         |      0        | 0           |   -0.0508355  |         1 |
| 0.0333333 |      0        | 0.00410397  |   -0.0151893  |        -1 |
| 0.0333333 |      0        | 0.00269542  |    0.0457659  |         1 |
| 0.0333333 |      0        | 0.00259605  |    0.0735757  |         1 |
| 0         |      0        | 0.00254842  |   -0.0538101  |         1 |
| 0         |      0        | 0.00168331  |   -0.0448421  |         1 |
| 0         |      0        | 0.00113611  |   -0.0195053  |         1 |
| 0         |      0        | 0.00113611  |   -0.0195053  |         1 |
| 0         |      0        | 0.00274725  |   -0.052422   |         1 |
| 0         |      0        | 0.00190476  |   -0.041636   |         1 |
| 0         |      0        | 0.00136042  |   -0.0337009  |         1 |
| 0         |      0        | 0.0009522   |   -0.0133905  |         1 |
| 0         |      0        | 0.0009522   |   -0.0133905  |         1 |
| 0         |      0        | 0.0009522   |   -0.0133905  |         1 |
| 0         |      0        | 0.00264504  |   -0.0812098  |         1 |
| 0         |      0        | 0.00170882  |   -0.0553     |         1 |
| 0         |      0        | 0.00119417  |   -0.0389722  |         1 |
| 0         |      0        | 0.00119417  |   -0.0389722  |         1 |
| 0         |      0        | 0.00170882  |   -0.0553     |         1 |
| 0         |      0        | 0.00187477  |   -0.0707261  |         1 |
| 0         |      0        | 0.00124069  |   -0.0358847  |         1 |
| 0         |      0        | 0.00124069  |   -0.0358847  |         1 |
| 0         |      0        | 0.00124069  |   -0.0358847  |         1 |
| 0         |      0        | 0.00124069  |   -0.0358847  |         1 |
| 0         |      0        | 0.0017616   |   -0.00239427 |         1 |
| 0         |      0        | 0.00124069  |   -0.0117439  |         1 |
| 0         |      0        | 0.000900739 |   -0.00810486 |         1 |
| 0         |      0        | 0.000670661 |   -0.00366903 |         1 |

## Additional Metrics

```plaintext
=== K-Core Numbers (After) ===
2: 2
1: 1
3: 2
4: 1
5: 2
6: 2
7: 2
8: 1
9: 1
10: 1
11: 1
12: 1
13: 1
14: 1
15: 1
16: 1
17: 1
18: 2
19: 2
20: 2
21: 2
22: 2
23: 1
24: 1
25: 1
26: 1
27: 1
28: 1
29: 1
30: 1
31: 1

=== Degree Assortativity Coefficient ===
Before: -0.524167, After: -0.235722

=== Local Efficiency ===
Before: 0.000000, After: 0.058602

=== Network Robustness ===
Before Removal:
  Largest_CC_After_Node_Removal: 6
  Largest_CC_After_Edge_Removal: 10
After Removal:
  Largest_CC_After_Node_Removal: 7
  Largest_CC_After_Edge_Removal: 20

```
