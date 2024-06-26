# Estimating Above Ground Biomass with remote sensing and machine learning
Accurate aboveground biomass (AGB) estimation is crucial for forest management and carbon monitoring. This project explores the potential of integrating remote sensing data (optical and radar) and machine learning algorithms (random forest and deep learning) for AGB estimation.

Deforestation and forest degradation account for a significant portion of global greenhouse gas emissions. Forests store large amounts of carbon in biomass, and their degradation releases this carbon as CO2, contributing to increased greenhouse gas concentrations (Reichstein et al., 2019). Additionally, forests provide various ecosystem services such as soil protection, biodiversity conservation, and climate regulation (Brazilian Forest Service, 2019). Biomass analysis is crucial for the economic valuation of forests and the promotion of sustainable management practices (Oliveira et al., 2018).

The application of machine learning techniques in remote sensing and image processing has shown promising results in terms of accuracy and scalability, despite the need for field samples to calibrate and validate models (Ghosh & Behera, 2021). It is recommended to combine data from different sensor systems such as optical imagery, radar, and LiDAR to obtain more precise estimates of forest biomass (Molisse et al., 2022).

### Study Area: Indigenous Land Mangueirinha
Selected for the quality and relevance of field-collected AGB data, Indigenous Land Mangueirinha in western Paraná provides a reference set for model calibration and validation.

### Data Collection
- ESA CCI Global Forest Above Ground Biomass: Data derived from radar and LiDAR sensors, with a resolution of ~100m x 100m.
- Harmonized Sentinel-2 MSI: High-resolution multispectral imagery.
- Sentinel-1 SAR GRD: Synthetic Aperture Radar data.
- NASA SRTM Digital Elevation 30m: Digital Elevation Model, important for considering topography in biomass mapping.

After data collection, the main stages of this work include:

### Data Preprocessing:

- Cleaning and organizing collected data.
- Handling missing values and outliers.
- Data format conversion.

### Cross-Validation and Normalization:

- Splitting data into training and testing sets.
- Applying cross-validation techniques to assess model robustness.
- Normalizing data to ensure all variables are on the same scale and do not dominate model training.

### Model Fitting:

- Random Forest
- Neural networks, such as CNNs..


### Accuracy Assessment:

- Assessing the performance of tuned models using metrics such as RMSE, MAE, R².
- Comparing results with ground truth biomass estimates.

### Hyperparameter Tuning:

- Optimizing model hyperparameters to improve performance and avoid overfitting.
- Using techniques like Grid Search to find the optimal combination of hyperparameters.

### Model Explanation with SHAP (SHapley Additive exPlanations):

- Interpreting models using SHAP to understand how each variable contributes to predictions.
- Identifying key features influencing forest biomass estimation.
