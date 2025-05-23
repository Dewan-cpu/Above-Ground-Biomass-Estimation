# Above-Ground-Biomass-Estimation
Last modified: 15 May 2025.


The codes have been implemented using Jupyter Hub and Google Earth Engine. The codes are jointly updated by Dewan Mohammad Enamul Haque, Dewan Ruksana Ruma, and Mashfiqur Shattique.

Leveraging Sentinel 2A imagery, GEDI LiDAR biomass data, and ESA’s Biomass products, we estimated AGB for three key periods: 2017 (pre-refugee influx), 2019 (early forest restoration), and 2023 (restoration progress). We employed machine learning regression models, including Random Forest (RF), Support Vector Machine (SVM), and Gradient Boosting (XGBoost) regression. 

I. 2017 Pre-refugee Influx

| Type              | Code                                           | 
| ------------------|:----------------------------------------------:| 
| Python Script     | PY02_agb_ForestBiomass_Sentinel2-Updated.ipynb | 

The original code is available at https://eo4society.esa.int/resources/copernicus-rus-training-materials/


II. 2019 (early forest restoration) & 2023 (restoration progress)

| Type                     | Code                                           | 
| -------------------------|:----------------------------------------------:| 
| Java Script for GEE      | AGB_Estimation_GEE.js                          | 

Original version of the code is available at https://spatialthoughts.com/2024/02/07/agb-regression-gee/

Installation Instruction for Jupyter Environment:
A .yml file is provided in order to create a Python environment using conda. This environment can be created by running:

conda env create -f PY02_agb.yml

If this command executes correctly and finishes without errors, it should print out instructions on how to activate and deactivate the new environment. To activate the environment, use:

conda activate PY02_agb

To deactivate the environment, use:

conda deactivate


## Recommended Citation:
Dewan Mohammad Enamul Haque. (2025). Data and Code for Rapid Above-Ground Biomass Change Estimation Using Machine Learning for the Rohingya Refugee Camp & Surrounding Areas in Bangladesh (Release1.1) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.15429786
