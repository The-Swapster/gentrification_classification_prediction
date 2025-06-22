# A Comprehensive Machine Learning and Geospatial Approach for Gentrification Detection and Prediction

## Key Contributions
1. Developed a robust pipeline to detect and forecast gentrification trends across U.S. counties by integrating heterogeneous datasets from Zillow, U.S. Census, and Eviction Lab.
2. Engineered socio-economic and housing features and utilized PCA to reduce dimensionality while retaining 95% data variance for downstream ML tasks.
3. Built and fine-tuned multiple classification models (Logistic Regression, Random Forest, LGBM) via stratified 5-fold cross-validation; achieved 85% accuracy and 0.77 ROC-AUC in distinguishing gentrifying vs. non-gentrifying regions.
4. Designed and implemented a SARIMAX-based time series model to forecast SEIFA scores, enabling early identification of regions at gentrification risk up to 5 years in advance.
5. Conducted spatial analysis using Moran’s I and Geographically Weighted Regression to model spillover effects of gentrification between neighboring counties.
6. Performed K-Means clustering on demographic and housing indicators to identify vulnerable population segments susceptible to displacement.
7. Applied SHAP explainability techniques on PCA-transformed features, enhancing interpretability for policy-oriented stakeholders.
8. Proposed actionable urban policy recommendations based on ML insights to mitigate displacement and support equitable development.

## For Dataset creation
Open File > [dataset_combine.ipynb](dataset_combine.ipynb) > Run All <br>
Open file > [data_label_creation.ipynb](data_label_creation.ipynb) > Run All

## For EDA
Open file > [dataprep_eda.ipynb](dataprep_eda.ipynb) > Run All

## For Feature Engineering, Binary classification models and SHAP analysis
Open file > [fe_models_shap.ipynb](fe_models_shap.ipynb) > Run All

## For cluster analysis (K-means)
Open file > [clustering.ipynb](clustering.ipynb) > Run All

## For Temporal and Spatial Analysis
Open file > [temporal and spatial.ipynb](<temporal and spatial.ipynb>) > Run All

## Dataset Files
Under raw folder > non processed data files

## Final Processed Files
[data_with_gentrification_classification_and_sd.csv](data_with_gentrification_classification_and_sd.csv)
