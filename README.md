# LAT
Ⓒ Llywelyn Hughes, Cardiff University. 2023

[![View LAT on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://uk.mathworks.com/matlabcentral/fileexchange/128554-lat)

The Lattice Analysis Tool (LAT) software is a matlab-based application, which can also be run as a standalone software for non-matlab users. 
LAT has the capabilities to analyse any image format such as JPEG, PNG, TIFF & BMP with automatic scaled measurements of the area, diameter, perimeter and centroid of each region, while also calculating averages, standard deviations and planar porosity. The tool has been tailored for additively manufactured lattice structures but also successfully trialed for heat exchanger channels and nanofluidic particle analysis.

# Latest Release
v2.0 - Ability to mask boundaries onto a CAD image for direct comparison. Updated UI for an improved and clearer experience.

# Install
1. **Matlab App:** Recommended installation if user has access to Matlab and the Image Processing Toolbox. 
   Open the LAT.mlappinstall file to automatically install the software into the matlab "My Apps" section.
   
2. **Standalone Software:** Download and install the LATInstaller_web.exe application. This will download the software through Matlab's Runtime Installer **Note:** It is recommended to restart computer following installation. 

# Tips
1. Ensure that input image doesn't have too much glare which generates bright spots and can impact binarisation process. 
2. At times an image with too high of a pixel resolution can slow down analysis and impact the interconnectivity of the pixels within the algorithm. In this case, resave the image with the Snipping Tool (or similar).
3. The heatmap function tends to work best for ordered structures (such as lattices) as opposed to stochastic porosities.
4. If using the CAD overlay function, ensure that both the Original and CAD images are scaled appropriately. 

# Modifications
The matlab file LAT.mlapp is also included for user modifications and adaptation of the current application.

# Citation
Please cite original code for any future developments: Hughes, L. Lattice Analysis Tool (LAT). [v2.0.0] 2023; Available from: https://github.com/llywelynhughes/LAT.


Any issues or queries, please get in touch.

Email: Hugheslr2@cardiff.ac.uk

LinkedIn: https://www.linkedin.com/in/llywelyn-hughes/
