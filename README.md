# My Projects at TU Delft

A collection of public projects I have developed at TU Delft, showcasing advancements in 3D geoinformation and urban modeling.

## Projects Overview

### 1. [SUMS: Semantic Urban Mesh Segmentation](https://github.com/tudelft3d/SUMS-Semantic-Urban-Mesh-Segmentation-public)
![SUMS](/pics/proj_sum.png)  
**SUMS** is the official implementation of the paper: [*SUM: A Benchmark Dataset of Semantic Urban Meshes*](https://www.sciencedirect.com/science/article/pii/S0924271621001854). 
Specifically, it is an open-source program for automatic semantic segmentation of large-scale urban texture meshes.
It is mainly implemented in C++ and other open-source libraries, such as [CGAL](https://www.cgal.org/) and [Easy3D](https://github.com/LiangliangNan/Easy3D).
For more information, please visit our [project website](https://3d.bk.tudelft.nl/projects/meshannotation/).

### 2. [Urban Mesh Annotation Tool](https://github.com/tudelft3d/3D_Urban_Mesh_Annotator.git)
![Urban Mesh Annotation Tool](/pics/proj_annot.png)  
Mesh annotation tool for labelling urban scenes. 
Before you import your model, please check your input mesh is in ascii *.ply format.
Note that non-manifold meshes are not supported in this tool. 
If you still want to use it, please use [MeshLab](https://www.meshlab.net/) to repair it first.
For more information, please visit our [project website](https://3d.bk.tudelft.nl/projects/meshannotation/).

### 3. [PSSNet](https://github.com/tudelft3d/PSSNet)
![PSSNet](/pics/proj_pssnet.png)
This is the implementation of the paper: [*PSSNet: Planarity-sensible Semantic Segmentation of Large-scale Urban Meshes*](https://www.sciencedirect.com/science/article/pii/S0924271622003355). 
Specifically, it consists of two steps: *Step-1*: planarity-sensible over-segmentation; *Step-2*: semantic classification.   

### 4. [Roofline Extraction](https://github.com/tudelft3d/Roofline-extraction-from-orthophotos)
![roofline](/pics/proj_roofline.png)
This is the implementation part of the roofline extraction of the paper: [*Unsupervised Roofline Extraction from True Orthophotos*](https://arxiv.org/abs/2310.01067). 
First, we use a true orthophoto as input. 
Next, we perform line extraction to partition the building footprint, which generates separate roof parts. 
We then utilize a dense point cloud to extrude the partition results and create a LoD2 building model. For generating LoD2 building models, please refer to the repository [gfp-building-reconstruction](https://github.com/geoflow3d/gfp-building-reconstruction).

### 5. [Fill Building Holes](https://github.com/tudelft3d/Automatic-Repair-of-LoD2-Building-Models)
![fillholes](/pics/proj_fillholes.png)
This repository provides the implementation for the automatic repair of LoD2 building models. It is primarily developed using C++ and leverages open-source libraries such as [CGAL](https://www.cgal.org/) and [Easy3D](https://github.com/LiangliangNan/Easy3D).
Our paper, [Filling holes in LoD2 building models](https://isprs-annals.copernicus.org/articles/X-4-W5-2024/171/2024/), has been accepted for presentation at the 3D Geoinfo 2024 conference. 
We are currently releasing the core module of our code, which focuses on mesh hole filling, along with the corresponding executable. 

### 6. [Building-PCC](https://github.com/tudelft3d/Building-PCC-Building-Point-Cloud-Completion-Benchmarks)
![buildingpcc](/pics/proj_buildingpcc.png)
This is the implementation of the Builiding-PCC paper: [*Building-PCC: Building Point Cloud Completion Benchmarks*](https://isprs-annals.copernicus.org/articles/X-4-W5-2024/179/2024/).
This repository contains scripts for generating Building-PCC data, links for data downloads, test codes for state-of-the-art methods, pre-trained models, and evaluation results.
