# Pancancer-tissue-atlas

This repository is related to submitted manuscript 'Tissue Atlas for Pan-cancer Tumor Microenvironment Analysis' to npj Digital Medicine.

Using U-Net and Vgg networks, we generated tissue category segmentation map (referred as tissue atlas) and tumor map for giga-pixel diagnostic whole-slide images in 8 cohorts of TCGA Project (TCGA-BRCA, TCGA-COAD, TCGA-LUAD, TCGA-LUSC, TCGA-OV, TCGA-PAAD, TCGA-STAD, and TCGA-UCEC).

This repo will make all the tissue atlas and tumor map available to support advanced investigations. Currently, a few example maps have been made available. The full atlas resources will be available upon acceptance of this work.

You can access the maps via this link:




## Tissue Atlas

Tissue atlas is a single-channel gray-level image. The value of each pixel ranges from 0 to 15. Value 1 to 15 represent following classes, respectively：
1.  <font color=#ffffff>■■</font> Background
2.  <font color=#1c35a0>■■</font> Lymphocytes or immune infiltration
3.  <font color=#996633>■■</font> Necrosis
4.  <font color=#a6a6a6>■■</font> Adipose
5.  <font color=#ed7d31>■■</font> Fibrous stroma
6.  <font color=#ed7d31>■■</font> Muscle
7.  <font color=#9c5bcd>■■</font> Nerves
8.  <font color=#a6a6a6>■■</font> Alveolar
9.  <font color=#a6a6a6>■■</font> Cartilage
10. <font color=#e74862>■■</font> Blood cells
11. <font color=#f6cc33>■■</font> Micro-vessels
12. <font color=#b9d5cb>■■</font> Mucus or sediment
13. <font color=#000000>■■</font> Carbon deposition
14. <font color=#2bb346>■■</font> Epithelial-like tissue
15. <font color=#e6e0d0>■■</font> Artifacts

Value 0 represent irrelevant regions for analysis, such as glass background, out of focus, marker pen-polluted region, and folded tissues.

You may check the results visually in $Cohort$-vis folder. Here are some examples:

![image](images/example-tissuemap/TCGA-3L-AA1B-01Z-00-DX1.8923A151-A690-40B7-9E5A-FCBEDFC2394F.jpg)

![image](images/example-tissuemap/TCGA-3L-AA1B-01Z-00-DX2.17CE3683-F4B1-4978-A281-8F620C4D77B4.jpg)

Note that all the tissue atlas files are saved at pixel spacing of 8μm. The original files were saved at 0.5μm/pixel, which are too large to share.


## Tumor map



