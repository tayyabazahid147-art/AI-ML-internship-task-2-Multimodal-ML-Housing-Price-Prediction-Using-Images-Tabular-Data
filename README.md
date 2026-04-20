## Multimodal Housing Price Prediction
# Objective

To build a machine learning model that predicts housing prices using both tabular data and image data by applying CNN-based feature extraction and feature fusion techniques.

# Methodology / Approach
Data Collection
Tabular dataset: area, bedrooms, bathrooms, location score
Image dataset: house images
Image Feature Extraction
Used pre-trained ResNet50 CNN
Extracted deep visual features
Feature Fusion
Combined image features with tabular features
Model Training
Dense neural network used for regression
Loss function: MSE
Optimizer: Adam
Evaluation Metrics
MAE (Mean Absolute Error)
RMSE (Root Mean Squared Error)
# Observations
Model successfully learned patterns from both image and tabular data
Feature fusion improved prediction accuracy
CNN helped extract meaningful visual representations
RMSE and MAE showed reasonable prediction error
#Technologies Used
Python
TensorFlow / Keras
NumPy, Pandas
Scikit-learn
ResNet50 (CNN)
