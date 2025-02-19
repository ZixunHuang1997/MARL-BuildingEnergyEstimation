# MARL: [M]ulti-scale [A]rchetype [R]epresentation [L]earning and Clustering for Building Energy Estimation

### Recent Updates:
- 08/08/23: Our work is accepted to [ICCV 2023 Workshop](https://cvaad-workshop.github.io/): 1st Computer Vision Aided Architectural Design (CVAAD) Workshop.

### Citation:
If our work is useful or relevant to your research, please kindly recognize our contributions by citing our paper:
```
@InProceedings{Zhuang_2023_ICCV,
    author    = {Zhuang, Xinwei and Huang, Zixun and Zeng, Wentao and Caldas, Luisa},
    title     = {MARL: Multi-scale Archetype Representation Learning for Urban Building Energy Modeling},
    booktitle = {Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV) Workshops},
    month     = {October},
    year      = {2023},
    pages     = {1565-1572}
}
```

### Overview:
This repository is the implementation code of the paper "MARL: [M]ulti-scale [A]rchetype [R]epresentation [L]earning and Clustering for Building Energy Estimation" ([iccvw 2023](https://openaccess.thecvf.com/content/ICCV2023W/CVAAD/papers/Zhuang_MARL_Multi-scale_Archetype_Representation_Learning_for_Urban_Building_Energy_Modeling_ICCVW_2023_paper.pdf), poster).

![Frame_2](https://github.com/ZixunHuang1997/MARL-BuildingEnergyEstimation/assets/106426767/f03687f2-044c-48f5-818e-27b1f70a92cb)

We present Multi-scale Archetype Representation Learning (MARL), a method designed to **automate local building archetype** construction through representation learning. Our proposed method addresses the aforementioned challenges by refining the essential elements of building archetypes for **Urban Building Energy Modeling**. This is a **learning-based** pipeline for representing and clustering buildings in our urban environment. Our research can be used in building energy estimation and can significantly save computing time. 

### Dataset:
- For footprints and their meta info, please refer to this [directory](https://github.com/ZixunHuang1997/MARL-BuildingEnergyEstimation/tree/main/data).
- For building energy consumption data, all rights are reserved by the [Lawrence Berkeley National Lab](https://buildings.lbl.gov/). Please contact authors for more detailed information.

### Requirements:
Before running our data generation and annotation pipeline, you can activate a conda environment where Python Version >= 3.7:
```
conda create --name [YOUR ENVIR NAME] python = [PYTHON VERSION]
conda activate [YOUR ENVIR NAME]
```
then install all necessary packages:
```
pip install -r requirements.txt
```

### Train:
To run training of our model, please refer to [this notebook](https://github.com/ZixunHuang1997/MARL-BuildingEnergyEstimation/blob/main/notebooks/train_marl.ipynb), or run the following command:
```
python train.py
```
### Archetype Clustering:
To get latent representation and run clustering, please refer to [this notebook](https://github.com/ZixunHuang1997/MARL-BuildingEnergyEstimation/blob/main/notebooks/latent_clustering.ipynb).


