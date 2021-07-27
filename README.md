# syGlassScriptsDirectory

Welsome to the syGlass Python Script Library! This document will grow as new scripts are submitted by syGlass engineers or members of the community. Please feel free to submit a PR to add your own script, or write us at info@syglass.io for help getting your script hosted.

## Index

### Image Extractor
https://github.com/IstoVisio/script_image_extractor

Convert a syGlass Porject back into a series of TIFF files. Never lose the raw data, as any image data can be extracted.

### ROI Extractor
https://github.com/IstoVisio/script_roi_extractor

Extract out both the raw image data within an ROI, as well as the volumetric labels painted on with the ROI volume painting tool. Great for pulling out segmented regions to train a deep neural network or other machine learning tasks!

### Inject Label Data Into ROI
https://github.com/IstoVisio/script_inject_label_data_into_roi

Push a 3D block of integer labels (segmentation where each voxel represents a class of object) back into an ROI. Useful for taking some machine learning output and pushing it back into syGlass for visualization and mesh creation.

### Cellpose for ROI
https://github.com/IstoVisio/script_cellpose_for_roi

Run Cellpose (https://www.cellpose.org/) (https://github.com/MouseLand/cellpose) on a ROI directly from syGlass! Produce volumetric segmentation for cellular objects automatically.

### Batch Project Creator
https://github.com/IstoVisio/script_batch_project_creator

Have a bunch of folders of serial images? Tired of converting them one by one? This script accepts an input directory, and an output directory. It will scan the input directory for subfolders with images in them, then create syGlass Projects for each one. 
