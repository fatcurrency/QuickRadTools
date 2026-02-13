# QuickRadTools
A lightweight and easy-to-use toolkit for rapid implementation of medical image processing tasks, supporting common formats like DICOM/NIfTI and core operations such as visualization, preprocessing, and analysis.

## Project 1: PET-CT Medical Image Visualization and Fusion
- Link: [PET_CT_Image_Fusion.ipynb](PET_CT_Image_Fusion.ipynb)
- Purpose: load, resample, register, normalize, visualize and fuse PET and CT volumes (slice views, MIP).
- Contents: data loading (DICOM/NIfTI), spatial alignment, isotropic resampling, intensity normalization, fusion examples, interactive notebook visualizations.
- Requirements: Python 3.8+, numpy, scipy, matplotlib, nibabel, pydicom, SimpleITK, scikit-image, ipywidgets (install via pip).
- Run:
    - Place image data in ./data (or update paths in the notebook).
    - Launch: jupyter lab PET_CT_Image_Fusion.ipynb or jupyter notebook PET_CT_Image_Fusion.ipynb.
- Notes: update file paths and install GPU/SimpleITK variants if using large volumes for performance.

