# 🎈Paper_List_And_Code_About_CBCT_Segmentation
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Flusunn111%2FPaper_List_And_Code_About_CBCT_Segmentation&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hints&edge_flat=false)](https://hits.seeyoufarm.com)
[![](https://img.shields.io/github/stars/lusunn111/Paper_List_And_Code_About_CBCT_Segmentation)](https://github.com/lusunn111/Paper_List_And_Code_About_CBCT_Segmentation)
[![](https://img.shields.io/github/forks/lusunn111/Paper_List_And_Code_About_CBCT_Segmentation)](https://github.com/lusunn111/Paper_List_And_Code_About_CBCT_Segmentation)
[![](https://img.shields.io/github/issues/lusunn111/Paper_List_And_Code_About_CBCT_Segmentation)](https://github.com/lusunn111/Paper_List_And_Code_About_CBCT_Segmentation)
[![](https://img.shields.io/github/license/lusunn111/Paper_List_And_Code_About_CBCT_Segmentation)](https://github.com/lusunn111/Paper_List_And_Code_About_CBCT_Segmentation/blob/main/LICENSE) 

---

# Codes

## ⌨️1.DilatedToothSegNet: Tooth Segmentation Network on 3D Dental Meshes Through Increasing Receptive Vision

[Code_Link](https://github.com/LucasKre/dilated_tooth_seg_net?tab=readme-ov-file)|**Time:2024**|**Not_Reproduction**

[Paper_Link](https://doi.org/10.1007/s10278-024-01061-6)|[Dataset_Link]([github.com/abenhamadou/3DTeethSeg22_challenge](https://github.com/abenhamadou/3DTeethSeg22_challenge))

## ⌨️2.MeshSegNet: Deep Multi-Scale Mesh Feature Learning for Automated Labeling of Raw Dental Surface from 3D Intraoral Scanners

[Code_Link](https://github.com/Tai-Hsien/MeshSegNet)|**Time:2023|2021**|**Not_Reproduction**

[Paper_Link1_2020](https://doi.org/10.1007/978-3-030-71881-7_10)|[Paper_Link2_2019](https://doi.org/10.1007/978-3-030-32226-7_93)|[Paper_Link3_2021](https://doi.org/10.1109/TMI.2020.2971730)|Dataset_Not_Found

## ⌨️3.T-Mamba: A unified framework with Long-Range Dependency in dual-domain for 2D & 3D Tooth Segmentation

[Code_Link](https://github.com/isbrycee/T-Mamba)|**Time:2024**|**Not_Reproduction**

[Paper_Link](https://arxiv.org/pdf/2404.01065)|Dataset_Loss

## ⌨️4.A fully automatic AI system for tooth and alveolar bone segmentation from cone-beam CT images

[Code_Link](https://github.com/ErdanC/Tooth-and-alveolar-bone-segmentation-from-CBCT)|**Time:2022**|**Not_Reproduction**

[Paper_Link](https://www.nature.com/articles/s41467-022-29637-2)|Dataset_Need_Apply

## ⌨️5.Tooth Decay Semantic Segmentation

[Code_Link](https://github.com/Momotoculteur/Tooth-decay-semantic-segmentation)|**Time:2019**|**Not_Reproduction**|[Relative_Code](https://github.com/qubvel/segmentation_models)

[Paper_Link](https://www.nature.com/articles/s41467-022-29637-2)|Dataset_Not_Found

## ⌨️6.Tooth Decay Semantic Segmentation

[Code_Link](https://github.com/Momotoculteur/Tooth-decay-semantic-segmentation)|**Time:2019**|**Not_Reproduction**|[Relative_Code](https://github.com/qubvel/segmentation_models)

[Paper_Link](https://www.nature.com/articles/s41467-022-29637-2)|Dataset_Not_Found

## ⌨️7.Tooth Decay Semantic Segmentation

[Code_Link](https://github.com/huiminxiong/TSegFormer)|**Time:2024**|**Not_Reproduction**

[Paper_Link(MICCAI 2023)](https://link.springer.com/chapter/10.1007/978-3-031-43987-2_41)|Dataset_Not_Found

**PS_From_Author:**

The preprocessing module performs the following functions:

1. Randomly downsamples N surfaces from the original mesh (in our implementation, N = 10,000).
2. Extracts 8-dimensional features for these surfaces from the mesh (details can be found in our paper).
3. Retrieves the corresponding labels for these surfaces.
   The features and labels are stored in the respective files, "u_aligned.json" / "l_aligned.json", representing the tooth point cloud information and segmentation labels. Each point in the point cloud corresponds one-to-one with the respective surface in the IOS mesh. You can implement this based on the provided description.

Thank you for your suggestions regarding the dataset and model. However, we regret that we are unable to share the dataset and pre-trained models due to privacy concerns. We appreciate your understanding and are happy to help with any other questions or clarifications.

**Data_Structure**

the dataset structure in `./data/DataSet/` should be organized as follows:

```
DataSet/
├── Case1_maxillary/
│   ├── u_aligned.stl
│   ├── u.txt
│   ├── u_aligned.json
├── Case1_mandibule/
│   ├── l_aligned.stl
│   ├── l.txt
│   └── l_aligned.json
└── ...
```

In this structure, the original data files for each case, such as "u_aligned.stl" and "u.txt," are placed together with the preprocessed file "u_aligned.json" (using "u" as an example; the same applies to "l").

## ⌨️8.ToothGroupNetwork：Team CGIP‘s Code In  Miccai2022 3D Teeth Scan Segmentation and Labeling Challenge

[Code_Link](https://github.com/johannx64/ToothGroupNetwork)|**Time:2024**|**Not_Reproduction**

[Paper_Link](https://arxiv.org/abs/2305.18277)|[Dataset_1](https://github.com/abenhamadou/3DTeethSeg22_challenge)|[Dataset_2](https://drive.google.com/drive/folders/15oP0CZM_O_-Bir18VbSM8wRUEzoyLXby)|[CheckPoint](https://drive.google.com/drive/folders/15oP0CZM_O_-Bir18VbSM8wRUEzoyLXby)

## ⌨️9.ToothGroupNetwork Implementation：A Test Code

[Code_Link](https://github.com/bobo9245/CBCT_Segmentation)|**Time:2025**|**Not_Reproduction**
