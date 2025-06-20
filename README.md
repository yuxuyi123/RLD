# A Region-based Logit Distillation Framework for Semantic Segmentation
Code will be released following manuscript acceptance.

| Method   ( on Cityscapes)                              | Params (M) | FLOPs (G) | Val mIoU (%) |
|--------------------------------------|------------|-----------|--------------|
| T: DeepLabv3-Res101                  | 61.1M      | 2371.7G   | 78.07        |
| S: DeepLabv3-Res18                   | 13.6M      |           | 74.21        |
| +SKD                 | 13.6M      |           | 75.42        |
| +IFVD               | 13.6M      |           | 75.64        |
| +CWD                | 13.6M      |           | 76.04        |
| +CIRKD               | 13.6M      |           | 76.38        |
| +MasKD                 | 13.6M      | 572.0G    | 77.00        |
| +CAD/LAD               | 13.6M      |           | 76.81 / 76.78|
| +RDD                | 13.6M      |           | 77.18        |
| +TD                    | 13.6M      |           | 76.57        |
| +DIST/DIST+         | 13.6M      |           | 77.10 / 77.36|
| **+RLD (Ours)**                      | 13.6M      |           | **77.80** [Download](https://pan.baidu.com/s/1xpScZSTZS2DcB7nGc_KK7g)   |
|||||
| Method                                 | Params (M) | FLOPs (G) | Val mIoU (%) |
| S: DeepLabv3-MBV2                    | 3.2M       |           | 73.12        |
| +SKD                | 3.2M       |           | 73.82        |
| +IFVD                | 3.2M       |           | 73.50        |
| +CWD              | 3.2M       |           | 74.66        |
| +CIRKD               | 3.2M       | 128.9G    | 75.42        |
| +MasKD [^5]             | 3.2M       |           | 75.26        |
| +RDD [^7]                | 3.2M       |           | **76.38**    |
| +TD [^8]                   | 3.2M       |           | 75.14        |
| **+RLD (Ours)**                      | 3.2M       |           | 76.30        |
|||||
| Method                                 | Params (M) | FLOPs (G) | Val mIoU (%) |
| S: PSPNet-Res18                      | 12.9M      |           | 72.55        |
| +SKD [^1]                | 12.9M      |           | 73.29        |
| +IFVD [^2]                | 12.9M      |           | 73.71        |
| +CWD [^3]                  | 12.9M      |           | 74.36        |
| +CIRKD [^4]               | 12.9M      | 507.4G    | 74.73        |
| +MasKD [^5]                | 12.9M      |           | 75.34        |
| +RDD [^7]                 | 12.9M      |           | 75.88        |
| +TD [^8]                 | 12.9M      |           | 76.24        |
| +DIST/DIST+ [^9]          | 12.9M      |           | 76.31 / 76.52|
| **+RLD (ours)**                      | 12.9M      |           | **76.55**    |
