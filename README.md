# Image Lists

## Files

| File | Purpose |
|---|---|
| [test_S1.csv](lists/test_S1.csv) | Test images in scene group S1: relatively homogeneous sky. |
| [test_S2.csv](lists/test_S2.csv) | Test images in scene group S2: heterogeneous or cloudy sky. |
| [test_S3.csv](lists/test_S3.csv) | Test images in scene group S3: buildings. |
| [test_S4.csv](lists/test_S4.csv) | Test images in scene group S4: vegetation and natural textures. |
| [test_S5.csv](lists/test_S5.csv) | Test images in scene group S5: extremely small targets in sky backgrounds. |
| [test_S6.csv](lists/test_S6.csv) | Test images in scene group S6: extremely small targets in structurally complex backgrounds. |
| [train.csv](lists/train.csv) | Images used to train the learning-based baselines. |
| [validation.csv](lists/validation.csv) | Images used for network model selection and detection-threshold selection. |

## Source datasets

The versions used are identified below by their dataset variants and image–mask pair counts.

| Dataset used | Version used | Official access | Reference |
|---|---|---|---|
| SIRST | Original 427-pair version (SIRST-v1; recorded as `NUAA-SIRST` in the lists) | [Official repository](https://github.com/YimianDai/sirst) | [1] |
| NUDT-SIRST | 1,327-pair version | [Official repository](https://github.com/YeRen123455/Infrared-Small-Target-Detection) | [2] |
| IRSTD-1k | 1,001-pair version | [Official repository](https://github.com/RuiZhang97/ISNet) | [3] |

## References

[1] Y. Dai, Y. Wu, F. Zhou, and K. Barnard, “Asymmetric Contextual Modulation for Infrared Small Target Detection,” in *Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)*, 2021, pp. 949–958. [DOI](https://doi.org/10.1109/WACV48630.2021.00099).

[2] B. Li et al., “Dense Nested Attention Network for Infrared Small Target Detection,” *IEEE Transactions on Image Processing*, vol. 32, pp. 1745–1758, 2023. [DOI](https://doi.org/10.1109/TIP.2022.3199107).

[3] M. Zhang, R. Zhang, Y. Yang, H. Bai, J. Zhang, and J. Guo, “ISNet: Shape Matters for Infrared Small Target Detection,” in *Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)*, 2022, pp. 867–876. [DOI](https://doi.org/10.1109/CVPR52688.2022.00095).
