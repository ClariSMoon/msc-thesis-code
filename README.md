# Code for MSc thesis
This repository contains the code used in my MSc thesis:  
**Bias detection and correction for Modis land surface temperature in Scandinavia - Using additive and mixed regression models**

## Running Process
1. Run the Java Script in https://code.earthengine.google.com/e4b77dfb297900ffb97cedb8cdb25828 to download Modis datasets.
2. Obtain in-Situ dataset from erda. https://erda.ku.dk/archives/e5544b25d94c11f3748555303b9a198d/published-archive.html
3. Run `merge_data.ipynb/` to combine the in-Situ data and one Modis dataset into one data frame.
4. Run `exploratory_analysis.ipynb/` to do exploratory analysis, including missing data analysis and extreme data analysis.
5. Run `modeling.ipynb/` to build LMM, GMM and GAMM models in thesis Section 3.

Note that in step 1, 4, 5, we need to adjust the code to apply for Modis datasets that use different buffers.
