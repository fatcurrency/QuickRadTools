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

## Project 2: Medical Image Cropping Tool
- Link: [Med_Image_Cropping.ipynb](Med_Image_Cropping.ipynb)
- Purpose: Interactive cropping tool for 3D medical images. Supports isotropic resampling, center-slice visualization, interactive slider-based positioning, centered cubic cropping with optional largest-inscribed-sphere masking and zero-padding, and saving results as NIfTI for downstream processing.
- Contents: parameter setup, image I/O and resampling, visualization utilities, interactive slice navigation, cropping and save examples (including code and widgets).
- Requirements: Python 3.8+, numpy, scipy, matplotlib, SimpleITK, ipywidgets
- Run:
    - Place image data in `./data` (or update paths in the notebook).
    - Launch: `jupyter lab Med_Image_Cropping.ipynb` or `jupyter notebook Med_Image_Cropping.ipynb`.
- Notes: Run in an environment that supports `ipywidgets` (Jupyter Lab/Notebook). For large volumes, resample or downsample first to reduce memory usage.

