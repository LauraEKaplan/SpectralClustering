# SpectralClustering
Code associated with the paper "Revisiting Spectral Clustering Techniques on Images: 2-k way vs. k-way Partitioning"

-----------------------------------------
Code Produced by Laura Kaplan
Advised by Professor Louis Petingi
Start Date: Feb 2023
Current Date: Jun 2023
-----------------------------------------
-----------------------------------------
If used, please credit:

Kaplan, L. E., & Petingi, L. “Revisiting Spectral Clustering Techniques on Images: 2-k way vs. k-way Partitioning,” 2023 International Conference on Computational Science and Computational Intelligence (CSCI), Las Vegas, NV. (In press).

-----------------------------------------
-----------------------------------------
# OVERVIEW
This project functions as a testing environment for
spectral clustering and eigenvector-based clustering 
as it pertains to image data. 

-----------------------------------------
## FOLDERS

### Code : contains all .ipynb notebook files

### Code -> Measurements : contains optional raw-data outputs from steps such as eigenvector calculations & cluster results.

### Code -> Images : folder where generate_figures references non-generated images
Please keep all referenced images within the Images folder. You may use your own images, but we do not recommend exceeding 150x150 resolution due to computation time. The current set of images is a selection corresponding to the publication results.

-----------------------------------------
## TOP LEVEL FILES
This repository contains the following notebooks:  
```
   1. generate_figures.ipynb : the primary execution file
   2. def_file_spectral.ipynb : spectral clustering-specific functions
   3. def_file_system.ipynb : a compliation of many hand-coded image processing functions
                        which may or may not come in handy.
```
generate_figures.ipynb is the primary file, and should be used to test images. generate_figures.ipynb imports definitions from both def_file_spectral.ipynb and def_file_system.ipynb

-----------------------------------------
## SETUP

1. Install dependencies:
	Pillow==9.2.0
	matplotlib==3.5.2
	networkx==2.8.4
	numpy==1.21.5
	scipy==1.9.1
	scikit-learn==1.0.2
	seaborn==0.11.2

2. Run code from generate_figures:	
	Change paths
	Code may be ran cell-by-cell
	Do not Run-All (computationally challenging)
