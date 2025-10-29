---
title: ResBIM Dataset
---
# Introduction of ResBIM dataset
Welcome to **Res**idential Unit **BIM** dataset (**ResBIM** dataset), this is a totally PUBLIC dataset.

This dataset is a part of the contributions of our paper titled <b><i>"Fully automated synthetic BIM dataset generation using a deep learning-based framework"</i></b> in *Automation in Construction*.

ResBIM is a synthetic dataset created by CNN and rule-based algorithms, designed specifically for research in BIM automation and 2D-to-BIM reconstruction. The dataset comprises 1000+ paired samples, each consisting of a fully parametric 3D BIM (RVT format) and its corresponding annotated 2D floor plan, as shown in **Figures 1, 2, and 3** at the end of texts. 

If you use the ResBIM data or code please cite our work: 

Liang, X., Yabuki, N., & Fukuda, T. (2026). Fully automated synthetic BIM dataset generation using a deep learning-based framework. Automation in Construction, 181, 106584. https://doi.org/10.1016/j.autcon.2025.106584

## Tutorial: How to create your own dataset by using the source codes
Because ResBIM is a public dataset, so everyone can download and use it. But you can develop **new models** or even **new methodology** based on the source codes. 

This video tutorial introduces how you can laverage the source codes and start to develop and customerize your own dataset.  If you have a similar research with mine, I believe ResBIM dataset and the source codes are helpful to accelerate your research. 

- [YouTube](https://www.youtube.com/watch?v=5yEkafzuclk)

- [BiliBili](https://www.bilibili.com/video/BV1dvWmzTEcc)


## Usage of ResBIM dataset
ResBIM is intended for a wide range of applications, including multi-platform BIM interoperability, serving as a foundation for benchmarking 2D-to-BIM algorithms, and the development of computer vision models for architectural analysis. The dataset supports a wide range of use cases, including but not limited to the following:

- 2D-to-BIM evaluation and benchmarking support. These pairs enable not only training of advanced AI models but also reproducible evaluation of 2D-to-BIM algorithms using metrics reliant on RF BIMs. 
- Obtaining various types of 2D drawings. Because BIMs are semantically rich 3D representations, all BIMs in the dataset can be converted into various 2D views such as floor plans, elevations, and cross-sections. This also addresses a common limitation highlighted in previous studies: the lack of annotated elevation drawings with height information, which has largely restricted 2D-to-BIM data extraction to planar geometry instead of multi-view representations.
- Conversion to point cloud. As shown in **Figure. 3**. Every BIM model could be converted to a point cloud with RGB, which can support point cloud studies. 

**(Notice)** In the full size dataset, there are several **failure cases** in the dataset as mentioned in the paper (e.g., 313 no openings, 732 inserted out of the range, 327 collision). **Please be careful when you are using it**. 

## ResBIM dataset download 
- [One data sample](https://drive.google.com/file/d/1gh4TiEJGkcjuqtO2e13mVQOYxWl5oGbI/view?usp=drive_link)

- [100 models (700M)](https://drive.google.com/file/d/1WvWMU4Ox459QXr1kYLfTqaMp2rR0mfpO/view?usp=drive_link)

- [Full size dataset (7GB, 1000+ models)](https://drive.google.com/file/d/1MzY92Xw0bOjCWDHMJtWjqYzZew_MOhUS/view?usp=drive_link)

## Source codes (400M)　
[Source codes](https://drive.google.com/file/d/1KBy_ff7xQid32mTbLn__uJ6SuPaWu3vL/view?usp=drive_link) include C#-based Revit Add-Ins and python-based networks. 

## Get started　　
- Download the source code and there is a **readme.pdf**.
- The structure and the usage of each coding are introduced in the file.

## Citation （BibTeX）
```
@article{LIANG2026106584,
title = {Fully automated synthetic BIM dataset generation using a deep learning-based framework},
journal = {Automation in Construction},
volume = {181},
pages = {106584},
year = {2026},
issn = {0926-5805},
doi = {https://doi.org/10.1016/j.autcon.2025.106584},
url = {https://www.sciencedirect.com/science/article/pii/S0926580525006247},
author = {Xing Liang and Nobuyoshi Yabuki and Tomohiro Fukuda},
```

## License
This project is licensed under the [MIT License](./LICENSE) - see the LICENSE file for details.

## Figures

<h1 align="center"><img width="600" height="400" alt="image" src="https://github.com/user-attachments/assets/2346ea41-9b7f-45ea-8582-984eef955f8a" /></h1>

<h1 align="center"><b>Figure 1.</b> BIM in ResBIM dataset</h1>

<h1 align="center"><img width="500" height="510" alt="image" src="https://github.com/user-attachments/assets/11e1ece6-3e0d-4b56-80a4-74df1f7e8851" /></h1>

<h1 align="center"><b>Figure 2.</b> Corresponding annotated floor plan</h1>

<h1 align="center"><img width="680" height="490" alt="image" src="https://github.com/user-attachments/assets/29ef6ee5-9ccd-49a6-bce6-c216357bdf06" /></h1>

<h1 align="center"><b>Figure 3.</b> Corresponding RGB point cloud</h1>
