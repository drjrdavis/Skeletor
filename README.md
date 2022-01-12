# Skeletor
Watershed-based segmentation software, developed for segmenting Drosophila pupal abdominal epidermis

This programme has been developed for segmenting flattened projected movies of histoblasts and larval epithelial cells (LECs) that have been labelled with a membrane marker, such as ECadherin-GFP, during Drosophila pupal abdomen development. It is optimised for these cells but can be used for any epithelial monolayer, with fluorescently labelled cell boundaries. In essence, Skeletor is a filter and watershed segmentation programme used for the initial segmentation and groundtruthing to train further machine learning segmentation programmes developed in Davis et al. Current Biology 2022. 

It is programmed using Wolfram Mathematica and designed with a simple user-interface so no prior knowledge of coding is required. The programme requires a projected time-series of an epithelium saved as a multi-image tif file. Once the tif file is loaded all that is needed is to set a threshold and off it goes! If you want to examine the code, hidden cells are present throughout the notebook. 
