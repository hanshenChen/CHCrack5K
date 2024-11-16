CHCrack5K Dataset
Comprehensive Crack Detection Dataset

Overview
The CHCrack5K dataset is a comprehensive collection of crack images, curated by combining 11 publicly available crack detection datasets. This dataset consists of 5,014 labeled image samples, carefully processed to standardize dimensions and facilitate high-accuracy crack detection research.

Composition and Preprocessing
The dataset integrates images of varying resolutions and crack structures to create a more challenging benchmark for crack detection algorithms. All images are standardized to a resolution of 480×480 pixels, with specific processing methods applied to ensure uniformity:

CFD [52], MCD-Crack [53], and Road420 [54] datasets include padding to maintain spatial integrity.
High-resolution datasets such as Crack500 [7] and SUT-Crack [55] are resized and cropped.
CrackTree260 [56] and DeepCrack537 [57] are resized, with DeepCrack537 also requiring padding.
This standardized approach ensures that the dataset provides a diverse range of samples, making it a robust tool for developing and testing crack detection models.

Dataset Splits
The dataset is randomly divided into:

3,510 training samples
501 validation samples
1,003 testing samples
These splits allow for balanced model training, fine-tuning, and evaluation.

Data Table
Table I summarizes the details of each subset in the CHCrack5K dataset, including the number of samples, pixel dimensions, and post-processing steps:

Dataset	Resolution	Post-Processing	Samples
CFD [52]	480×320	Padding	117
Crack500 [7]	2560×1440/...	Cut + Resize	1,000
Road420 [54]	448×480	Padding	420
MCD-Crack [53]	480×320	Padding	235
SUT-Crack [55]	3024×4032	Cut + Resize	260
CamCrack789 [58]	640×640	Resize	789
DeepCrack537 [57]	544×384	Padding + Resize	537
CrackTree260 [56]	800×600	Padding + Resize	260
CrackLS315 [8]	512×512	Resize	315
CRKWH100 [8]	512×512	Resize	100
TunnelCrack [59]	512×512	Resize	981
Access and Usage
The CHCrack5K dataset is freely available for academic and research purposes. Access it here:

Download the CHCrack5K Dataset : https://

Note: Please cite our paper if you use this dataset in your research.

Citation
If you use CHCrack5K in your work, please cite:

css
复制代码
@dataset{CHCrack5K,
  author = {Your Name},
  title = {CHCrack5K: A Comprehensive Crack Detection Dataset},
  year = {2024},
  url = {https://github.com/hanshenchen/CHCrack5K}
}
