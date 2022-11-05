---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a PhD student of Computer Science at George Washington University. I'm advised by [Dr. Robert Pless](https://www2.seas.gwu.edu/~pless/), with a research focus on understanding images cross long time period and its application in agriculture.  

About my work
======
I'm currently working on understanding the relationship of hundreds of sorghum cultivars using a large dataset from TERRA, that contains daily images of a large sorghum field. I use deep metric learning methods to build an image feature space. I use this feature space to interpret different kinds of phenotypes and genotypes then visualize the activation area of images. To better understand this learned feature space,  I built a [embedding visualization tool](https://github.com/zhzyx/embedding-visualization) that aim to understand relationship of different kind of labels of multimodal datasets in high dimensional space. For example it reveals the trends of time in each cultivar clusters, cultivars are not well clustered at the start of the season etc.

I previously worked on [sorghum leaf morphological phenotyping](https://github.com/GWUvision/Sorghum-Leaf) from 3D scanner data. I built a [semi-automated annotation tool](https://github.com/zhzyx/sorghum-annotator) to label leaves. Use annotated images to train deep convolutional neural network to segment leaves, then use point cloud to build leaf voxel adjacency graph to extract phenotypes like leaf length and curvature. 


Publications
======
- **Comparing Deep Learning Approaches for Understanding Genotype× Phenotype Interactions in Biomass Sorghum.**   
Zeyu Zhang, Madison Pope, Nadia Shakoor, Robert Pless, Todd C. Mockler, Abby Stylianou
Frontiers in Artificial Intelligence 5 (2022) [[paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9289439/pdf/frai-05-872858.pdf)
- **Metric Learning for Large Scale Agricultural Phenotyping.**   
Zeyu Zhang, Abby Stylianou, Robert Pless   
NAPPN 2021 [[paper]](https://www.essoar.org/doi/10.1002/essoar.10508292.1)
- **2-MAP: Aligned Visualizations for Comparison of High-Dimensional Point Sets”**   
Xiaotong Liu, Zeyu Zhang, Hong Xuan, Roxana Leontie, Abby Stylianou, Robert Pless   
WACV 2020 [[paper]](https://openaccess.thecvf.com/content_WACV_2020/papers/Liu_2-MAP_Aligned_Visualizations_for_Comparison_of_High-Dimensional_Point_Sets_WACV_2020_paper.pdf)
- **Visualizing Data Driven Phenotypes**   
Zeyu Zhang, Hong Xuan, Xiaotong Liu, Abby Stylianou, Robert Pless   
CVPPP 2019 [[paper]](https://www.plant-phenotyping.org/lw_resource/datapool/systemfiles/elements/files/c7538f5c-7552-11e9-b1c5-dead53a91d31/current/document/ZhangCVPPP2019.pdf)
- **Visualizing how embeddings generalize**   
Xiaotong Liu, Hong Xuan, Zeyu Zhang, Abby Stylianou, Robert Pless   
ICML Workshop 2019 [[paper]](https://arxiv.org/pdf/1909.07464.pdf)

