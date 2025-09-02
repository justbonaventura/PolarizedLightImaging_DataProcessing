# Polarized Light Imaging Data Processing Notebooks
This repository contains 6 different juypeter notebooks for working with pixelwise resolved Mueller matrix data. 

Among these notebooks there are a variety of Mueller matrix decomposition functions as well as data visualization and further analysis which can be done from that point. 
Brief summaries of which are listed below-

Bulk_Lu_Chipman_Decomposition- performs a Lu Chipman decoposition or all named datasets in a given folder, returning pixelwise polarization properties of each wavelength of each dataset.

DOLP Calculation- Calculates the degree of linear polarization from the Mueller matrix parameters across all pixels in an image.

Find_Curvature_From_OCT- This notebook works with three dimensional datasets such as a three dimensional tiff file from an optical coherence tomography measurement to find the curvature of a tissue sample along a selected line. This is in complement to the analysis done with PLI data and can be then compared to polarization properties alond that same selected line.

MuellerDecomp3x3_w_4x4Compare- This notebook performs a 3x3 Mueller matrix decomposition with visualizations for comparing that to the 4x4 Lu CHipman decomposition data.

Mueller_Decomp_and_Analysis- This notebook performs a Lu Chipman decomposition for Mueller matrix data and has several different techniques for polarization visualization, ROI selection and analysis.

Registration_and_Processing_Rotational_Data- This notebook is meant to work with various datasets taken of the same sample rotated to different angles. This includes built in functions for rotational co-registration and analysis functions to relate sample measurement orientation to polarization property value. 
