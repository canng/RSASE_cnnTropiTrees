# Leveraging Convolutional Neural Networks and Textural Features for Tropical Fruit Tree Species Classification 

This repository archives scripts and sample data that use CNN model and spectral and textural information from publicly available remote sensing datasets of [Sentinel-2](https://dataspace.copernicus.eu/explore-data/data-collections/sentinel-data/sentinel-2) and [Planet-NICFI mosaics](https://developers.google.com/earth-engine/datasets/catalog/projects_planet-nicfi_assets_basemaps_asia) to classify fruit tree species.

![general workflow](/workflow.jpg)

## Instruction ##
Before running the scripts, you need to:
1. Install Python at least version 3.10
2. Create virtual environment
3. Install the required package in the `requirements.txt` using `pip`.

## Guide to the Scripts ##
This archive consists:
`cnnTropiTrees.ipynb`

>This Jupyter Notebook includes codes to load the trained CNN model and sample data to classify the normalized data of spectral and textural bands into different fruit tree species: Pomelo, Coconut, Coconut Intercropping, Rambutan, and Durian. 

## Reference

[Nguyen, C. T+](https://orcid.org/0000-0003-0471-4062), Diem, K. P.+, Nghia, D. H., Diem, N. K., Diep, N. T. H., Phan, T. N., Minh, V. Q., Quang, N. H., 2025. **Leveraging Convolutional Neural Networks and Textural Features for Tropical Fruit Tree Species Classification**. Remote Sensing Applications: Society and Environment, 101633 [DOI: 10.1016/j.rsase.2025.101633](https://doi.org/10.1016/j.rsase.2025.101633)

### Related read

*Zhang, Chenchen, et al. "Effect of textural features in remote sensed data on rubber plantation extraction at different levels of spatial resolution." Forests 11.4 (2020): 399. [DOI: 10.3390/f11040399](https://doi.org/10.3390/f11040399)*

*Habibie, Muhammad Iqbal, et al. "The development land utilization and cover of the Jambi district are examined and forecasted using Google Earth Engine and CNN1D." Remote Sensing Applications: Society and Environment 34 (2024): 101175. [DOI: 10.1016/j.rsase.2024.101175](https://doi.org/10.1016/j.rsase.2024.101175)*
