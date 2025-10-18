# Introduction of ResBIM dataset
Welcome to **Res**idential Unit **BIM** dataset (**ResBIM** dataset), this is a totally PUBLIC dataset.

This dataset is a part of the contributions of our paper titled "Fully automated synthetic BIM dataset generation using a deep learning-based framework" in Automation in Construction.

ResBIM is a synthetic dataset created by CNN and rule-based algorithms, designed specifically for research in BIM automation and 2D-to-BIM reconstruction. The dataset comprises 1000+ paired samples, each consisting of a fully parametric 3D BIM (RVT format) and its corresponding annotated 2D floor plan. 

## Usage of ResBIM dataset
<img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/2346ea41-9b7f-45ea-8582-984eef955f8a" />

Figure 1. BIM in ResBIM dataset


<img width="500" height="510" alt="image" src="https://github.com/user-attachments/assets/11e1ece6-3e0d-4b56-80a4-74df1f7e8851" />

Figure 2. Corresponding annotated floor plan


<img width="680" height="490" alt="image" src="https://github.com/user-attachments/assets/29ef6ee5-9ccd-49a6-bce6-c216357bdf06" />

Figure 3. Corresponding RGB point cloud


A sample could be download here: https://drive.google.com/file/d/1gh4TiEJGkcjuqtO2e13mVQOYxWl5oGbI/view?usp=drive_link

There are several BAD cases in the dataset as mentioned in the paper (e.g., 313 no openings, 732 inserted out of the range, 327 collision), please be careful when you are using it. ResBIM is intended for a wide range of applications, including multi-platform BIM interoperability, serving as a foundation for benchmarking 2D-to-BIM algorithms, and the development of computer vision models for architectural analysis. The dataset supports a wide range of use cases, including but not limited to the following:

- 2D-to-BIM evaluation and benchmarking support. These pairs enable not only training of advanced AI models but also reproducible evaluation of 2D-to-BIM algorithms using metrics reliant on RF BIMs. 
- Obtaining various types of 2D drawings. Because BIMs are semantically rich 3D representations, all BIMs in the dataset can be converted into various 2D views such as floor plans, elevations, and cross-sections. This also addresses a common limitation highlighted in previous studies: the lack of annotated elevation drawings with height information, which has largely restricted 2D-to-BIM data extraction to planar geometry instead of multi-view representations.
- Conversion to point cloud. As shown in Fig.3 every BIM model could be converted to a point cloud with RGB, which can support point cloud studies.


## ResBIM dataset download 
100 models (700M): https://drive.google.com/file/d/1WvWMU4Ox459QXr1kYLfTqaMp2rR0mfpO/view?usp=drive_link

Full size dataset (7GB, 1000+ models): https://drive.google.com/file/d/1MzY92Xw0bOjCWDHMJtWjqYzZew_MOhUS/view?usp=drive_link

## Source codes (400M)　
Revit Add-Ins and networks: https://drive.google.com/file/d/1KBy_ff7xQid32mTbLn__uJ6SuPaWu3vL/view?usp=drive_link

## Get started　　
- Read the readme.pdf in the source code folder.

## Citation
If you use the ResBIM data or code please cite our work:
```
Liang, X., Yabuki, N., & Fukuda, T. (2026). Fully automated synthetic BIM dataset generation using a deep learning-based framework. Automation in Construction, 181, 106584. https://doi.org/10.1016/j.autcon.2025.106584
```
