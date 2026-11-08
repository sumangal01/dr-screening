# DR Screening (research prototype)
EfficientNet-B0 trained on APTOS 2019, tested on APTOS test and IDRiD.
Not a medical device.

| | APTOS test | IDRiD (external) |
|---|---|---|
| QWK | 0.893 | 0.783 |
| Exact grade accuracy | 0.847 | 0.530 |
| Referable DR sensitivity | 0.942 | 0.806 (0.974 after calibration on held-out half) |

Limits: single training source, severe grades under-estimated, no working
image-quality check, Grad-CAM not validated against lesion annotations.
