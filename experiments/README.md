# Decentralized 3D Collision Avoidance for Multi-UAV Systems

## Statistical Results Over 100 Runs

The table below reports the mean values over 100 simulation runs for each experiment. Distances are given in meters.

| Exp. | Min. inter-UAV distance [m] | Mean lateral error [m] | Mean lateral RMSE [m] | Mean max path deviation [m] | Max path deviation [m] | Mean elongation index |
|---:|---:|---:|---:|---:|---:|---:|
| 1 | 11.4506 | 1.6325 | 2.8732 | 6.9095 | 6.9208 | 1.1749 |
| 2 | 5.9793 | 0.6791 | 1.2143 | 3.1878 | 6.9093 | 1.0828 |
| 3 | 11.2071 | 0.4839 | 0.8032 | 2.1950 | 4.3900 | 1.0426 |
| 4 | 5.6637 | 0.6292 | 1.3417 | 3.8980 | 3.9409 | 1.0734 |
| 5 | 4.2678 | 1.6095 | 2.4957 | 5.7642 | 8.2674 | 1.2115 |
| 6 | 4.5046 | 2.4898 | 3.2519 | 5.9276 | 7.8650 | 1.2891 |
| 7 | 5.1283 | 3.7877 | 5.0095 | 8.7681 | 9.9456 | 1.4987 |
| 8 | 5.1900 | 3.5282 | 4.5891 | 7.8490 | 9.8867 | 1.4514 |
| 9 | 5.9928 | 0.9142 | 1.3414 | 4.4095 | 4.7138 | 1.0490 |
| 10 | 7.9293 | 1.3002 | 2.0854 | 5.5891 | 7.8932 | 1.0719 |

---

## Detailed Statistical Summary

### Experiment 1 — Static Emergency UAV

| Metric | Mean | Std. | Var. | Median | Min. | Max. |
|---|---:|---:|---:|---:|---:|---:|
| Minimum inter-UAV distance [m] | 11.4506 | 0.0166 | 0.000276 | 11.4514 | 11.4093 | 11.4848 |
| Mean lateral error [m] | 1.6325 | 0.0050 | 0.000025 | 1.6324 | 1.6186 | 1.6440 |
| Mean lateral RMSE [m] | 2.8732 | 0.0045 | 0.000021 | 2.8730 | 2.8600 | 2.8837 |
| Mean maximum path deviation [m] | 6.9095 | 0.0082 | 0.000067 | 6.9091 | 6.8893 | 6.9344 |
| Maximum path deviation [m] | 6.9208 | 0.0099 | 0.000098 | 6.9212 | 6.8982 | 6.9419 |
| Mean trajectory elongation index | 1.1749 | 0.0029 | 0.000008 | 1.1750 | 1.1665 | 1.1820 |
| Success rate | 1.0000 | -- | -- | -- | -- | -- |
| Collision rate | 0.0000 | -- | -- | -- | -- | -- |

### Experiment 2 — Moving Emergency UAV

| Metric | Mean | Std. | Var. | Median | Min. | Max. |
|---|---:|---:|---:|---:|---:|---:|
| Minimum inter-UAV distance [m] | 5.9793 | 0.0269 | 0.000724 | 5.9783 | 5.9265 | 6.0509 |
| Mean lateral error [m] | 0.6791 | 0.0073 | 0.000053 | 0.6790 | 0.6652 | 0.6997 |
| Mean lateral RMSE [m] | 1.2143 | 0.0136 | 0.000186 | 1.2145 | 1.1870 | 1.2520 |
| Mean maximum path deviation [m] | 3.1878 | 0.0262 | 0.000687 | 3.1867 | 3.1352 | 3.2501 |
| Maximum path deviation [m] | 6.9093 | 0.0141 | 0.000199 | 6.9085 | 6.8783 | 6.9411 |
| Mean trajectory elongation index | 1.0828 | 0.0014 | 0.000002 | 1.0831 | 1.0795 | 1.0856 |
| Success rate | 1.0000 | -- | -- | -- | -- | -- |
| Collision rate | 0.0000 | -- | -- | -- | -- | -- |

### Experiment 3 — Predictive Avoidance Without Direct Proximity

| Metric | Mean | Std. | Var. | Median | Min. | Max. |
|---|---:|---:|---:|---:|---:|---:|
| Minimum inter-UAV distance [m] | 11.2071 | 0.0075 | 0.000056 | 11.2075 | 11.1910 | 11.2303 |
| Mean lateral error [m] | 0.4839 | 0.0025 | 0.000006 | 0.4835 | 0.4791 | 0.4913 |
| Mean lateral RMSE [m] | 0.8032 | 0.0089 | 0.000080 | 0.8028 | 0.7876 | 0.8251 |
| Mean maximum path deviation [m] | 2.1950 | 0.0469 | 0.002200 | 2.1988 | 2.0759 | 2.2881 |
| Maximum path deviation [m] | 4.3900 | 0.0938 | 0.008801 | 4.3977 | 4.1519 | 4.5761 |
| Mean trajectory elongation index | 1.0426 | 0.0011 | 0.000001 | 1.0426 | 1.0406 | 1.0459 |
| Success rate | 1.0000 | -- | -- | -- | -- | -- |
| Collision rate | 0.0000 | -- | -- | -- | -- | -- |

### Experiment 4 — Mutual Avoidance With Future Trajectories

| Metric | Mean | Std. | Var. | Median | Min. | Max. |
|---|---:|---:|---:|---:|---:|---:|
| Minimum inter-UAV distance [m] | 5.6637 | 0.2441 | 0.059568 | 5.6898 | 5.1603 | 6.2135 |
| Mean lateral error [m] | 0.6292 | 0.0123 | 0.000152 | 0.6269 | 0.6084 | 0.6719 |
| Mean lateral RMSE [m] | 1.3417 | 0.0184 | 0.000338 | 1.3429 | 1.3063 | 1.3922 |
| Mean maximum path deviation [m] | 3.8980 | 0.0299 | 0.000893 | 3.8946 | 3.8213 | 3.9620 |
| Maximum path deviation [m] | 3.9409 | 0.0446 | 0.001991 | 3.9346 | 3.8292 | 4.0735 |
| Mean trajectory elongation index | 1.0734 | 0.0009 | 0.000001 | 1.0733 | 1.0721 | 1.0754 |
| Success rate | 1.0000 | -- | -- | -- | -- | -- |
| Collision rate | 0.0000 | -- | -- | -- | -- | -- |

### Experiment 5 — Opposing Emergency Trajectories

| Metric | Mean | Std. | Var. | Median | Min. | Max. |
|---|---:|---:|---:|---:|---:|---:|
| Minimum inter-UAV distance [m] | 4.2678 | 0.0853 | 0.007278 | 4.2892 | 4.0251 | 4.4005 |
| Mean lateral error [m] | 1.6095 | 0.0593 | 0.003512 | 1.6171 | 1.4609 | 1.7218 |
| Mean lateral RMSE [m] | 2.4957 | 0.0815 | 0.006647 | 2.5012 | 2.3189 | 2.6484 |
| Mean maximum path deviation [m] | 5.7642 | 0.2427 | 0.058900 | 5.8024 | 5.2922 | 6.3378 |
| Maximum path deviation [m] | 8.2674 | 0.6452 | 0.416276 | 8.5694 | 7.1214 | 9.2786 |
| Mean trajectory elongation index | 1.2115 | 0.0335 | 0.001120 | 1.1946 | 1.1783 | 1.3058 |
| Success rate | 1.0000 | -- | -- | -- | -- | -- |
| Collision rate | 0.0000 | -- | -- | -- | -- | -- |

### Experiment 6 — Perpendicular Emergency Trajectories

| Metric | Mean | Std. | Var. | Median | Min. | Max. |
|---|---:|---:|---:|---:|---:|---:|
| Minimum inter-UAV distance [m] | 4.5046 | 0.5113 | 0.261380 | 4.3044 | 4.0209 | 6.0086 |
| Mean lateral error [m] | 2.4898 | 0.1348 | 0.018182 | 2.4710 | 2.2657 | 2.7884 |
| Mean lateral RMSE [m] | 3.2519 | 0.1131 | 0.012783 | 3.2315 | 3.0581 | 3.4947 |
| Mean maximum path deviation [m] | 5.9276 | 0.2314 | 0.053528 | 5.9207 | 5.5922 | 6.4745 |
| Maximum path deviation [m] | 7.8650 | 0.6593 | 0.434702 | 7.8134 | 7.0706 | 9.4881 |
| Mean trajectory elongation index | 1.2891 | 0.0159 | 0.000253 | 1.2851 | 1.2624 | 1.3424 |
| Success rate | 1.0000 | -- | -- | -- | -- | -- |
| Collision rate | 0.0000 | -- | -- | -- | -- | -- |

### Experiment 7 — Scalability Test With 10 UAVs

| Metric | Mean | Std. | Var. | Median | Min. | Max. |
|---|---:|---:|---:|---:|---:|---:|
| Minimum inter-UAV distance [m] | 5.1283 | 0.4249 | 0.180572 | 5.1344 | 4.0957 | 5.8510 |
| Mean lateral error [m] | 3.7877 | 0.3201 | 0.102470 | 3.7131 | 3.2193 | 4.3079 |
| Mean lateral RMSE [m] | 5.0095 | 0.2584 | 0.066745 | 4.9440 | 4.5323 | 5.4391 |
| Mean maximum path deviation [m] | 8.7681 | 0.2274 | 0.051698 | 8.7352 | 8.2827 | 9.1537 |
| Maximum path deviation [m] | 9.9456 | 0.2712 | 0.073567 | 9.9928 | 9.2717 | 10.5086 |
| Mean trajectory elongation index | 1.4987 | 0.0630 | 0.003964 | 1.4918 | 1.3869 | 1.6710 |
| Success rate | 1.0000 | -- | -- | -- | -- | -- |
| Collision rate | 0.0000 | -- | -- | -- | -- | -- |

### Experiment 8 — Large-Scale Scenario With One Emergency UAV

| Metric | Mean | Std. | Var. | Median | Min. | Max. |
|---|---:|---:|---:|---:|---:|---:|
| Minimum inter-UAV distance [m] | 5.1900 | 0.5051 | 0.255104 | 5.2282 | 4.0970 | 6.0098 |
| Mean lateral error [m] | 3.5282 | 0.2592 | 0.067197 | 3.5679 | 3.0863 | 4.0414 |
| Mean lateral RMSE [m] | 4.5891 | 0.2023 | 0.040915 | 4.6102 | 4.2141 | 4.9563 |
| Mean maximum path deviation [m] | 7.8490 | 0.1571 | 0.024683 | 7.8665 | 7.3615 | 8.0774 |
| Maximum path deviation [m] | 9.8867 | 0.4237 | 0.179520 | 9.8963 | 8.6148 | 11.1764 |
| Mean trajectory elongation index | 1.4514 | 0.0659 | 0.004344 | 1.4454 | 1.3335 | 1.6484 |
| Success rate | 1.0000 | -- | -- | -- | -- | -- |
| Collision rate | 0.0000 | -- | -- | -- | -- | -- |

### Experiment 9 — A\*-Based Global Trajectories Over Curved Terrain

| Metric | Mean | Std. | Var. | Median | Min. | Max. |
|---|---:|---:|---:|---:|---:|---:|
| Minimum inter-UAV distance [m] | 5.9928 | 0.0374 | 0.001397 | 5.9959 | 5.8994 | 6.0812 |
| Mean lateral error [m] | 0.9142 | 0.0007 | 0.000001 | 0.9141 | 0.9126 | 0.9164 |
| Mean lateral RMSE [m] | 1.3414 | 0.0016 | 0.000003 | 1.3412 | 1.3373 | 1.3457 |
| Mean maximum path deviation [m] | 4.4095 | 0.0195 | 0.000380 | 4.4087 | 4.3578 | 4.4586 |
| Maximum path deviation [m] | 4.7138 | 0.0353 | 0.001249 | 4.7128 | 4.6367 | 4.7987 |
| Mean trajectory elongation index | 1.0490 | 0.0001 | 0.000000 | 1.0490 | 1.0486 | 1.0493 |
| Success rate | 1.0000 | -- | -- | -- | -- | -- |
| Collision rate | 0.0000 | -- | -- | -- | -- | -- |

### Experiment 10 — Emergency UAV With A\*-Based Global Trajectories

| Metric | Mean | Std. | Var. | Median | Min. | Max. |
|---|---:|---:|---:|---:|---:|---:|
| Minimum inter-UAV distance [m] | 7.9293 | 0.0105 | 0.000110 | 7.9295 | 7.9069 | 7.9471 |
| Mean lateral error [m] | 1.3002 | 0.0015 | 0.000002 | 1.3002 | 1.2964 | 1.3036 |
| Mean lateral RMSE [m] | 2.0854 | 0.0016 | 0.000002 | 2.0854 | 2.0828 | 2.0902 |
| Mean maximum path deviation [m] | 5.5891 | 0.0031 | 0.000009 | 5.5891 | 5.5815 | 5.5945 |
| Maximum path deviation [m] | 7.8932 | 0.0059 | 0.000035 | 7.8928 | 7.8776 | 7.9097 |
| Mean trajectory elongation index | 1.0719 | 0.0013 | 0.000002 | 1.0719 | 1.0686 | 1.0746 |
| Success rate | 1.0000 | -- | -- | -- | -- | -- |
| Collision rate | 0.0000 | -- | -- | -- | -- | -- |

---

## Metrics

- **Minimum inter-UAV distance [m]**: smallest Euclidean distance observed between any pair of UAVs during a simulation.
- **Mean lateral error [m]**: mean distance between executed trajectory points and the planned reference path.
- **Mean lateral RMSE [m]**: mean per-UAV root mean squared lateral deviation from the planned path.
- **Mean maximum path deviation [m]**: average, across UAVs, of the maximum deviation from the planned path.
- **Maximum path deviation [m]**: largest path deviation observed in the simulation.
- **Mean trajectory elongation index**: ratio between executed path length and planned path length, averaged across the UAVs considered in trajectory metrics.
- **Success rate**: fraction of runs in which the simulation completed successfully.
- **Collision rate**: fraction of runs in which the minimum inter-UAV distance fell below the collision threshold.

---

## Notes

- Each experiment was repeated over **100 independent simulation runs**.
- All reported experiments achieved a **100% success rate** and **0% collision rate**.
- The collision threshold used in the simulations was defined as a minimum inter-UAV distance of **1.0 m**.
- Some scenarios exclude stationary or non-evaluated UAVs from trajectory-deviation metrics, while still considering them for inter-UAV distance evaluation when relevant.

---

