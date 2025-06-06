# RLD 
| Method                                 | Params (M) | FLOPs (G) | Val mIoU (%) |
|--------------------------------------|------------|-----------|--------------|
| T: DeepLabv3-Res101                  | 61.1M      | 2371.7G   | 78.07        |
| S: DeepLabv3-Res18                   | 13.6M      |           | 74.21        |
| +SKD [^1] (CVPR'19)                  | 13.6M      |           | 75.42        |
| +IFVD [^2] (ECCV'20)                 | 13.6M      |           | 75.64        |
| +CWD [^3] (ICCV'21)                  | 13.6M      |           | 76.04        |
| +CIRKD [^4] (CVPR'22)                | 13.6M      |           | 76.38        |
| +MasKD [^5] (ICLR'23)                | 13.6M      | 572.0G    | 77.00        |
| +CAD/LAD [^6] (WACV'24)              | 13.6M      |           | 76.81 / 76.78|
| +RDD [^7] (SCIS'24)                  | 13.6M      |           | 77.18        |
| +TD [^8] (PR'25)                     | 13.6M      |           | 76.57        |
| +DIST/DIST+ [^9] (TPAMI'25)          | 13.6M      |           | 77.10 / 77.36|
| **+RLD (Ours)**                      | 13.6M      |           | **77.80**    |
| S: DeepLabv3-MBV2                    | 3.2M       |           | 73.12        |
| +SKD [^1] (CVPR'19)                  | 3.2M       |           | 73.82        |
| +IFVD [^2] (ECCV'20)                 | 3.2M       |           | 73.50        |
| +CWD [^3] (ICCV'21)                  | 3.2M       |           | 74.66        |
| +CIRKD [^4] (CVPR'22)                | 3.2M       | 128.9G    | 75.42        |
| +MasKD [^5] (ICLR'23)                | 3.2M       |           | 75.26        |
| +RDD [^7] (SCIS'24)                  | 3.2M       |           | **76.38**    |
| +TD [^8] (PR'25)                     | 3.2M       |           | 75.14        |
| **+RLD (Ours)**                      | 3.2M       |           | 76.30        |
| S: PSPNet-Res18                      | 12.9M      |           | 72.55        |
| +SKD [^1] (CVPR'19)                  | 12.9M      |           | 73.29        |
| +IFVD [^2] (ECCV'20)                 | 12.9M      |           | 73.71        |
| +CWD [^3] (ICCV'21)                  | 12.9M      |           | 74.36        |
| +CIRKD [^4] (CVPR'22)                | 12.9M      | 507.4G    | 74.73        |
| +MasKD [^5] (ICLR'23)                | 12.9M      |           | 75.34        |
| +RDD [^7] (SCIS'24)                  | 12.9M      |           | 75.88        |
| +TD [^8] (PR'25)                     | 12.9M      |           | 76.24        |
| +DIST/DIST+ [^9] (TPAMI'25)          | 12.9M      |           | 76.31 / 76.52|
| **+RLD (ours)**                      | 12.9M      |           | **76.55**    |

[^1]: Liu et al., Structured Knowledge Distillation, CVPR 2019  
[^2]: Wang et al., Intra-Class Variation for Knowledge Distillation, ECCV 2020  
[^3]: Shu et al., Channel-wise Knowledge Distillation, ICCV 2021  
[^4]: Yang et al., Cross-Intra Relation Knowledge Distillation, CVPR 2022  
[^5]: Huang et al., Masked Knowledge Distillation, ICLR 2023  
[^6]: Liu et al., Rethinking Architecture-Aware Knowledge Distillation, WACV 2024  
[^7]: RDD (Realistic Data Distillation), SCIS 2024  
[^8]: Wu et al., Task-aware Distillation, PR 2025  
[^9]: DIST/DIST+: Dual Interaction Strategy Transfer, TPAMI 2025
