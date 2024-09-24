# Awesome-Anomaly-Image-Generation

# Anomaly Image Generation
In industrial scenarios, anomaly data is extremely scarce due to high acquisition costs. The scarcity of anomaly data limits the performance of anomaly detection algorithms. Therefore, anomaly image generation methods can be used to obtain more anomaly data and improve the performance of anomaly detection algorithms. Anomaly image generation is a challenging task as it not only needs to generate a large number of diverse anomaly images with limited training data but also needs to generate corresponding pixel-level labels.

# Papers
## Generate Anomaly Images and Masks
|  Title  |   Publication  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**DualAnoDiff: Dual-Interrelated Diffusion Model for Few-Shot Anomaly Image Generation**](https://arxiv.org/pdf/2408.13509) | arXiv 2024 | 2024.08 | [Github](https://github.com/yinyjin/DualAnoDiff) |
| [**AnomalyFactory: Regard Anomaly Generation as Unsupervised Anomaly Localization**](https://arxiv.org/pdf/2408.09533) | ECCVW 2024 | 2024.08 | - |
| [**CUT: A Controllable, Universal, and Training-Free Visual Anomaly Generation Framework**](https://arxiv.org/pdf/2406.01078) | arxiv 2024 | 2024.06 | [Github](https://github.com/google/nerfies) |
| [**LogicAL: Towards Logical Anomaly Synthesis for Unsupervised Anomaly Localization**](https://openaccess.thecvf.com/content/CVPR2024W/VAND/papers/Zhao_LogicAL_Towards_Logical_Anomaly_Synthesis_for_Unsupervised_Anomaly_Localization_CVPRW_2024_paper.pdf) | CVPRW 2024 | 2024.05 | - |
| [**AnomalyXFusion: Multi-modal Anomaly Synthesis with Diffusion**](https://arxiv.org/pdf/2404.19444)| arxiv 2024 | 2024.04 | - |
| [**AnomalyDiffusion: Few-Shot Anomaly Image Generation with Diffusion Model**](https://ojs.aaai.org/index.php/AAAI/article/view/28696/29348) | AAAI 2024 | 2023.12 | [Github](https://github.com/sjtuplayer/anomalydiffusion) |
| [**DREAM: Efficient Dataset Distillation by Representative Matching**](https://openaccess.thecvf.com/content/ICCV2023/papers/Liu_DREAM_Efficient_Dataset_Distillation_by_Representative_Matching_ICCV_2023_paper.pdf) | ICCV 2023 | 2023.08 | [Github](https://github.com/Yanqing0327/DREAM) |
| [**Few-Shot Defect Image Generation via Defect-Aware Feature Manipulation**](https://ojs.aaai.org/index.php/AAAI/article/view/25132/24904) | AAAI 2023 | 2023.03 | [Github](https://github.com/Ldhlwh/DFMGAN) |
| [**Prototypical Residual Networks for Anomaly Detection and Localization**](http://openaccess.thecvf.com/content/CVPR2023/papers/Zhang_Prototypical_Residual_Networks_for_Anomaly_Detection_and_Localization_CVPR_2023_paper.pdf) | CVPR 2023 | 2022.12 | - |
| [**Few-Shot Defect Segmentation Leveraging Abundant Defect-Free Training Samples Through Normal Background Regularization And Crop-And-Paste Operation**](https://ieeexplore.ieee.org/abstract/document/9428468/) | ICME 2021 | 2021.07 | - |
| [**CutPaste: Self-Supervised Learning for Anomaly Detection and Localization**](https://openaccess.thecvf.com/content/CVPR2021/papers/Li_CutPaste_Self-Supervised_Learning_for_Anomaly_Detection_and_Localization_CVPR_2021_paper.pdf) | CVPR 2021 | 2021.04 | - |


## Generate Anomaly Images Only
|  Title  |   Publication  |   Date   |   Code   |
|:--------|:--------:|:--------:|:--------:|
| [**Few-shot Image Generation via Cross-domain Correspondence**](http://openaccess.thecvf.com/content/CVPR2021/papers/Ojha_Few-Shot_Image_Generation_via_Cross-Domain_Correspondence_CVPR_2021_paper.pdf) | CVPR 2021 | 2021.04 | - |
| [**Defect-GAN: High-Fidelity Defect Synthesis for Automated Defect Inspection**](http://openaccess.thecvf.com/content/WACV2021/papers/Zhang_Defect-GAN_High-Fidelity_Defect_Synthesis_for_Automated_Defect_Inspection_WACV_2021_paper.pdf) | WACV 2021 | 2021.03 | - |
| [**Differentiable Augmentation for Data-Efficient GAN Training**](https://proceedings.neurips.cc/paper_files/paper/2020/file/55479c55ebd1efd3ff125f1337100388-Paper.pdf) | NeurIPS 2020 | 2020.06 | [Github](https://github.com/mit-han-lab/data-efficient-gans) |
| [**Defect Image Sample Generation With GAN for Improving Defect Recognition**](https://www.researchgate.net/profile/Hui-Lin-14/publication/339362792_Defect_Image_Sample_Generation_With_GAN_for_Improving_Defect_Recognition/links/5fbfc7f9a6fdcc6cc66a69ac/Defect-Image-Sample-Generation-With-GAN-for-Improving-Defect-Recognition.pdf) | T-ASE 2020 | 2020.02 | - |

# Performance
## Generation quality
### Mvtec
| Motheds | IS | LPIPS |
|:--------|:--------:|:--------:|
| DiffAug | 1.58 | 0.09|
| CropPaste | 1.51 | 0.14|
| CDC | 1.65 | 0.07 |
|SDGAN | 1.71 | 0.13 |
| DGAN | 1.69 | 0.15 |
| Defect-GAN | 1.69 | 0.15 |
| DFMGAN | 1.72 | 0.20 |
| AnomalyDiffusion | 1.80 | 0.32|
| AnomalyXDiffusion | 1.82 | 0.33 |
| DualAnoDiff | 1.90 | 0.37 |


## Performance of Anomaly Localization
### Mvtec
#### Pixel-level Anomaly Localization
| Motheds | AUC | AP | F1 |
|:--------|:--------:|:--------:|:--------:|
| Dream | 92.2 | 54.1 | 53.1 |
| PRN | 96.9 | 66.2 | 64.7 |
| DFMGAN | 90.0 | 62.7 | 62.1 |
| AnomalyDiffusion | 99.1 | 81.4 | 76.3 |
| AnomalyXDiffusion | 99.3 | 86.1 | 80.6 |
| DualAnoDiff | 99.1 | 84.5 | 78.8 |

#### Image-level Anomaly Localization
| Motheds | AUC | AP | F1 |
|:--------|:--------:|:--------:|:--------:|
| LogicAL | 98.8 | - | - |
| AnomalyXDiffusion | 99.2 | 99.8 | 98.7 |

### MADsim
#### Pixel-level Anomaly Localization
| Motheds | AUC | AP | F1 |
|:--------|:--------:|:--------:|:--------:|
| LogicAL | 86.0 | - | - |

#### Image-level Anomaly Localization
| Motheds | AUC | AP | F1 |
|:--------|:--------:|:--------:|:--------:|
| LogicAL | 67.6 | - | - |

### VisA
#### Pixel-level Anomaly Localization
| Motheds | AUC | AP | F1 |
|:--------|:--------:|:--------:|:--------:|
| Dream | 88.8 | 25.4 | - |
| LogicAL | 97.4 | 47.2 | - |

#### Image-level Anomaly Localization
| Motheds | AUC | AP | F1 |
|:--------|:--------:|:--------:|:--------:|
|Dream| 84.1 | - | - |
| LogicAL | 95.3 | - | - |
