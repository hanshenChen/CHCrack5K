# CHCrack5K Dataset
A Comprehensive Dataset for Pixel-level Crack Detection

## Overview
**CHCrack5K** is a comprehensive crack dataset containing 5,014 annotated images by integrating 11 publicly available, high-quality, labeled datasets. Details of the datasets are provided in Table 1. Each dataset undergoes specific processing to standardize the samples at a resolution of 480 × 480 pixels. For datasets such as CFD, MCD-Crack, and Road420, padding is applied to maintain spatial structure. High-resolution datasets such as Crack500 and SUT-Crack are resized and cropped. Other datasets, such as CrackTree260 and DeepCrack537 are resized, with the latter also requiring padding to achieve uniformity in dimensions. This combined dataset provides a diverse set of samples, encom-passing various materials, crack structures, and fluctuating lighting conditions, thereby creating a more challenging and robust environment for crack detection. The dataset is randomly split into 3,510 training samples, 501 validation samples, and 1,003 testing samples. 

## Dataset Details and Processing
Each of the 11 contributing datasets has been processed to ensure consistent dimensions and quality:

- **CFD**, **MCD-Crack**, and **Road420**: Padding applied to retain spatial structure.
- **Crack500** and **SUT-Crack**: High-resolution images resized and cropped.
- **DeepCrack537**: Padding and resizing applied for uniform dimensions.
- **CrackTree260** and other datasets: Resized with necessary adjustments to standardize dimensions.

## Dataset Composition
The dataset is divided as follows:

- **Training set**: 3,510 samples
- **Validation set**: 501 samples
- **Testing set**: 1,003 samples

### Table I: Overview of the CHCrack5K Dataset
| Dataset            | Original Resolution | Post-Processing       | Samples |
|---------------------|---------------------|-----------------------|---------|
| CFD                 | 480×320             | Padding               | 117     |
| Crack500            | 2560×1440/...       | Cut + Resize          | 1,000   |
| Road420             | 448×480             | Padding               | 420     |
| MCD-Crack           | 480×320             | Padding               | 235     |
| SUT-Crack           | 3024×4032           | Cut + Resize          | 260     |
| CamCrack789         | 640×640             | Resize                | 789     |
| DeepCrack537        | 544×384             | Padding + Resize      | 537     |
| CrackTree260        | 800×600             | Padding + Resize      | 260     |
| CrackLS315          | 512×512             | Resize                | 315     |
| CRKWH100            | 512×512             | Resize                | 100     |
| TunnelCrack         | 512×512             | Resize                | 981     |

*For detailed subset download links, please refer to the references provided in the [paper](https://doi.org/10.1016/j.eswa.2025.128144).

## Access the Dataset
The dataset is hosted on GitHub and can be accessed via the following link:

[Download CHCrack5K Dataset](https://drive.google.com/file/d/1EdfHX78Ov5sFw90HSN2JRww5RWPs1Zc1/view?usp=drive_link)

## Citation
If you use **CHCrack5K** in your research, please cite this dataset as follows:
@article{CHEN2025128144,
title = {HACNet V2: Rethinking the full-resolution architecture for pixel-level crack detection},
journal = {Expert Systems with Applications},
pages = {128144},
year = {2025},
issn = {0957-4174},
doi = {https://doi.org/10.1016/j.eswa.2025.128144},
url = {https://www.sciencedirect.com/science/article/pii/S0957417425017646},
author = {Hanshen Chen and Hao Chen}
}
