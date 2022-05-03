# ba-thesis-cellpose
Cellpose notebook for automatic segmentation of 3D image data

Project for AI in image segmentation as part of my bachelor´s thesis. 
Uses cellpose 2.0.5 (https://github.com/MouseLand/cellpose), napari 0.4.15 (https://github.com/napari/napari) and Jupyter Notebook.
Thanks to all of their authors for their great work for the next step in bioimage analysis.
Special thanks also to the help from the image.sc forum community for their help while troubleshooting and choosing the best-suited frameworks.

The presented algorithm segments 3D z-stacks from a Zeiss ApoTome.2 for automatic counting of nuclear marker-positive cells (i.e. MCM2 and BrdU), plots initial views and opens the image for analysis in npari. The resulting segmentation is also saved in the cellpose appropriate format.

Due to size limitations, the segmented image TIF-files are found in Google Drive (https://drive.google.com/drive/folders/1TgMa4zSE7wOEe20f3rzUGoLXEKc891My?usp=sharing)

May 2022
Paul Wagner
