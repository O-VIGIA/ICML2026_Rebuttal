## Table A.
**Metric:**  
$d_t^{rec} = \left\lVert \hat z_{0,t}^{2d} - \hat z_{0,t}^{3d} \right\rVert_2$

**Caption.** *Step-wise cross-modal Euclidean gap between the recovered clean latents. Smaller is better. The full tri-phase model is consistently better than the Phase1-only counterpart, with the largest gains in the medium/high-noise regime.*

| t | Phase1-only | Ours (Phase1+2+3) |
|---|------------:|------------------:|
| 10 | 0.24 | **0.18** |
| 20 | 0.29 | **0.22** |
| 30 | N/A | **0.26** |
| 40 | N/A | **0.29** |
| 50 | N/A | **0.31** |
| 60 | N/A | **0.36** |
| 70 | N/A | **0.42** |
| 80 | N/A | **0.51** |
| 90 | N/A | **0.63** |

