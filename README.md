# Ecological-Drought-ML-Modeling
📊🛰️ Data processing scripts, ML models, and Explainable AI results created as part of my Masters Thesis @ Johns Hopkins: **An Interpretable Machine Learning Model to Explore Relationships between Drought Indices and Ecological Drought Impacts in the Cheyenne River Basin, USA**

## Links

- <a href="https://jscholarship.library.jhu.edu/handle/1774.2/68152"> Full Paper</a>

- <a href="https://drive.google.com/file/d/1yyk9-pplgeJCpb-upcfCP5oKQ2adIGhh/view?usp=share_link">Raw CSV Data (Post GEE-Aquisition)</a>

- <a href="https://drive.google.com/file/d/1r8hypfobqIRzTW_dCkcw36KLBlmPfArG/view?usp=share_link">Preprocessed CSV Data</a>

- <a href="https://drive.google.com/drive/folders/1xZtnHrp0XPtGvsER1OYK7yXf3AZV5u3m?usp=share_link">Basin Shapefile</a>

## Abstract 

Rangeland ecosystems across the United States have significant biological, economic, and cultural value. However, the increasing frequency and severity of droughts across the country may lead to unforeseen impacts on these ecosystems. To address this challenge, this study aimed to identify relationships between drought indices and vegetation health in the Cheyenne River Basin, USA, using machine learning (ML) and explainable artificial intelligence (XAI) methods. Using Terra Moderate Resolution Imaging Spectroradiometers (MODIS), University of Idaho Gridded Surface Meteorological Dataset (gridMET), and Daymet data, the study employed XGBoost Regressor and Extra Trees Regressor models in unison with SHapley Additive exPlanations (SHAP) to evaluate predictive performance and the connections between drought indices, environmental variables, and the Normalized Difference Vegetation Index (NDVI). Tests of model performance demonstrated that the XGBoost model performed moderately well at predicting NDVI and was therefore useful for further XAI analysis with SHAP. SHAP explainer results showed that the Palmer Drought Severity Index (PDSI), the 90-day Standardized Precipitation Index (SPI), and snow water equivalent (SWE), were the most important predictors of NDVI values and are therefore closely associated with vegetation health in the study area. The findings of this study first demonstrate the feasibility and usefulness of applying XAI, an underutilized method in the drought space, to study ecological drought indicators. Secondly, results provide an understanding of which commonly used drought indices correlate with effects on vegetation health in the study area, as well as the specific directionality of these relationships. These results can be used to inform drought research and monitoring practices and anticipate ecological drought impacts in the Cheyenne River Basin. 

**Advisor and Primary Reader:** Dr. Garrett Graham

**Secondary Reader:** Dr. Michael Schwebel
