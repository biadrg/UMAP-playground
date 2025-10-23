
[![DOI](https://zenodo.org/badge/207660516.svg)](https://zenodo.org/badge/latestdoi/207660516)

# Examples for UMAP-dimensionality reduction using 3D models of prehistoric animals


The models are taken from the [Smithsonians 3D-scanning efforts](https://3d.si.edu/). I have included the datapoints for a Wolly Mammoth and a Tyrannosaur eating a Triceratops in the two .csv-files. 

The Jupyter-Notebook contains code to produce [UMAP-embeddings](https://github.com/lmcinnes/umap), which are continously shifting with changes in the hyperparameters, as can be seen below. I tend to think that such animations should, wherever possible, be produced when UMAP-plots are published, so that the viewers can judge for themselves which properties remain constant under different parameters, and which are mere artefacts of a specific hyperparameter-setting or random-state.

## Here is an image of the original Mammoth:
![](mammoth_render2.png)

## And here are 2D-embeddings of it with shifting hyperparameters:
![](anim_min_dist_param.gif)

![](anim_nearest_neighbours.gif)

## And this is the T-Rex, and a series of embeddings with different random-states
![](T-rex_render.png)
![](t-rex-random.gif)

# Citation

If this dataset is useful in your research, please consider citing it:

Noichl, M. (2025). *Examples for UMAP-dimensionality reduction using 3D models of prehistoric animals* (Version 0.0.1) [Dataset]. Zenodo. [https://doi.org/10.5281/zenodo.17290165](https://doi.org/10.5281/zenodo.17290165)


And consider giving credit to the 3D-scans of the Smithsonian Institution:

Smithsonian Institution. (2020). Mammuthus primigenius (Blumbach). [3D model]. Smithsonian 3D. https://3d.si.edu/object/3d/mammuthus-primigenius-blumbach:341c96cd-f967-4540-8ed1-d3fc56d31f12
