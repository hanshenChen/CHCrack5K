# CHCrack5K Dataset
A Comprehensive Dataset for Pixel-level Crack Detection

## Overview
**CHCrack5K** is a robust dataset designed for advanced crack detection research. It combines 11 publicly available crack datasets into a unified set, resulting in 5,014 labeled image samples. Each dataset undergoes specific preprocessing to standardize all samples to a resolution of **480×480 pixels**. This dataset offers a diverse range of crack structures, providing a more challenging and realistic benchmark for testing robust crack detection algorithms.

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

## Access the Dataset
The dataset is hosted on GitHub and can be accessed via the following link:

[Download CHCrack5K Dataset]([https://drive.google.com/file/d/1EdfHX78Ov5sFw90HSN2JRww5RWPs1Zc1/view?usp=drive_link])

## Citation
If you use **CHCrack5K** in your research, please cite this dataset as follows:
@dataset{CHCrack5K, author = {Your Name}, title = {CHCrack5K: A Comprehensive Crack Detection Dataset}, year = {2024}, url = {https://github.com/hanshenchen/CHCrack5K} }
