# Awesome-Anomaly-Image-Generation

# Anomaly Image Generation
In industrial scenarios, anomaly data is extremely scarce due to high acquisition costs. The scarcity of anomaly data limits the performance of anomaly detection algorithms. Therefore, anomaly image generation methods can be used to obtain more anomaly data and improve the performance of anomaly detection algorithms. anomaly image generation is a challenging task as it not only needs to generate a large number of diverse anomaly images with limited training data but also needs to generate corresponding pixel-level labels.

<!-- # Papers
## Gnerate Anomaly Images and Masks
* Jin Y, Peng J, He Q, et al. DualAnoDiff: Dual-Interrelated Diffusion Model for Few-Shot Anomaly Image Generation[J]. 2024. [[pdf]](https://arxiv.org/pdf/2408.13509)
* Hu T, Zhang J, Yi R, et al. Anomalydiffusion: Few-shot anomaly image generation with diffusion model[C]. AAAI2024. [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/28696/29348)
* Duan Y, Hong Y, Niu L, et al. Few-shot defect image generation via defect-aware feature manipulation[C]. AAAI2023. [[pdf]](https://ojs.aaai.org/index.php/AAAI/article/view/25132/24904)
* Liu Y, Gu J, Wang K, et al. Dream: Efficient dataset distillation by representative matching[C]. IEEE/CVF International Conference on Computer Vision. 2023. [[pdf]](https://openaccess.thecvf.com/content/ICCV2023/papers/Liu_DREAM_Efficient_Dataset_Distillation_by_Representative_Matching_ICCV_2023_paper.pdf)
* Lin D, Cao Y, Zhu W, et al. Few-shot defect segmentation leveraging abundant defect-free training samples through normal background regularization and crop-and-paste operation[C]. IEEE International Conference on Multimedia and Expo (ICME). 2021. [[pdf]](https://ieeexplore.ieee.org/abstract/document/9428468/)
* Zhang H, Wu Z, Wang Z, et al. Prototypical residual networks for anomaly detection and localization[C]. IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2023. [[pdf]](http://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Prototypical_Residual_Networks_for_Anomaly_Detection_and_Localization_CVPR_2023_paper.pdf)

## Only Anomaly Images
* Zhang G, Cui K, Hung T Y, et al. Defect-GAN: High-fidelity defect synthesis for automated defect inspection[C]. IEEE/CVF Winter Conference on Applications of Computer Vision. 2021. [[pdf]](http://openaccess.thecvf.com/content/WACV2021/papers/Zhang_Defect-GAN_High-Fidelity_Defect_Synthesis_for_Automated_Defect_Inspection_WACV_2021_paper.pdf)
* Niu S, Li B, Wang X, et al. Defect image sample generation with GAN for improving defect recognition[J]. IEEE Transactions on Automation Science and Engineering, 2020. [[pdf]](https://www.researchgate.net/profile/Hui-Lin-14/publication/339362792_Defect_Image_Sample_Generation_With_GAN_for_Improving_Defect_Recognition/links/5fbfc7f9a6fdcc6cc66a69ac/Defect-Image-Sample-Generation-With-GAN-for-Improving-Defect-Recognition.pdf)
* Ojha U, Li Y, Lu J, et al. Few-shot image generation via cross-domain correspondence[C]. IEEE/CVF conference on computer vision and pattern recognition. 2021. [[pdf]](http://openaccess.thecvf.com/content/CVPR2021/papers/Ojha_Few-Shot_Image_Generation_via_Cross-Domain_Correspondence_CVPR_2021_paper.pdf)
* Zhao S, Liu Z, Lin J, et al. Differentiable augmentation for data-efficient gan training[J]. NIPS. 2020. [[pdf]](https://proceedings.neurips.cc/paper_files/paper/2020/file/55479c55ebd1efd3ff125f1337100388-Paper.pdf) -->

# Papers
## Gnerate Anomaly Images and Masks
|  Title  |   Publication  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**DualAnoDiff: Dual-Interrelated Diffusion Model for Few-Shot Anomaly Image Generation**](https://arxiv.org/pdf/2408.13509) | arXiv 2024 | 2024.08 | [Github](https://github.com/yinyjin/DualAnoDiff) |
| [**AnomalyDiffusion: Few-Shot Anomaly Image Generation with Diffusion Model**](https://ojs.aaai.org/index.php/AAAI/article/view/28696/29348) | AAAI 2024 | 2023.12 | [Github](https://github.com/sjtuplayer/anomalydiffusion) |
| [**DREAM: Efficient Dataset Distillation by Representative Matching**](https://openaccess.thecvf.com/content/ICCV2023/papers/Liu_DREAM_Efficient_Dataset_Distillation_by_Representative_Matching_ICCV_2023_paper.pdf) | ICCV 2023 | 2023.08 | [Github](https://github.com/Yanqing0327/DREAM) |
| [**Few-Shot Defect Image Generation via Defect-Aware Feature Manipulation**](https://ojs.aaai.org/index.php/AAAI/article/view/25132/24904) | AAAI 2023 | 2023.03 | [Github](https://github.com/Ldhlwh/DFMGAN) |
| [**Prototypical Residual Networks for Anomaly Detection and Localization**](http://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Prototypical_Residual_Networks_for_Anomaly_Detection_and_Localization_CVPR_2023_paper.pdf) | CVPR 2023 | 2022.12 | - |
| [**Few-Shot Defect Segmentation Leveraging Abundant Defect-Free Training Samples Through Normal Background Regularization And Crop-And-Paste Operation**](https://ieeexplore.ieee.org/abstract/document/9428468/) | ICME 2021 | 2021.07 | - |

## Only Anomaly Images
|  Title  |   Publication  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**Few-shot Image Generation via Cross-domain Correspondence**](http://openaccess.thecvf.com/content/CVPR2021/papers/Ojha_Few-Shot_Image_Generation_via_Cross-Domain_Correspondence_CVPR_2021_paper.pdf) | CVPR 2021 | 2021.04 | - |
| [**Defect-GAN: High-Fidelity Defect Synthesis for Automated Defect Inspection**](http://openaccess.thecvf.com/content/WACV2021/papers/Zhang_Defect-GAN_High-Fidelity_Defect_Synthesis_for_Automated_Defect_Inspection_WACV_2021_paper.pdf) | WACV 2021 | 2021.03 | - |
| [**Differentiable Augmentation for Data-Efficient GAN Training**](https://proceedings.neurips.cc/paper_files/paper/2020/file/55479c55ebd1efd3ff125f1337100388-Paper.pdf) | NeurIPS 2020 | 2020.06 | [Github](https://github.com/mit-han-lab/data-efficient-gans) |
| [**Defect Image Sample Generation With GAN for Improving Defect Recognition**](https://www.researchgate.net/profile/Hui-Lin-14/publication/339362792_Defect_Image_Sample_Generation_With_GAN_for_Improving_Defect_Recognition/links/5fbfc7f9a6fdcc6cc66a69ac/Defect-Image-Sample-Generation-With-GAN-for-Improving-Defect-Recognition.pdf) | T-ASE 2020 | 2020.02 | - |