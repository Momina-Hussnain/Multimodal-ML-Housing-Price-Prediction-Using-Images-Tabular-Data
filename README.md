# Multimodal-ML-Housing-Price-Prediction-Using-Images-Tabular-Data
This project aims to predict housing prices by leveraging both structured tabular features (like square footage, bedrooms, bathrooms, year built) and visual information from house images. Combining these two modalities allows the model to capture richer information about properties, improving prediction accuracy.
# Multimodal Housing Price Prediction

This project predicts housing prices using both tabular data and house images.

## Project Overview

Housing prices are influenced by many factors. This project combines structured features like square footage, number of bedrooms/bathrooms, year built, and unstructured data like house images to improve prediction accuracy. 

The model uses a Convolutional Neural Network (CNN) to extract image features and merges them with tabular features for regression.

Example CSV:

| id | image_path      | sqft | bedrooms | bathrooms | year_built | price       |
|----|----------------|------|----------|-----------|------------|------------|
| 0  | image_00000.jpg | 1698 | 3        | 1         | 1973       | 114752.07  |
| 1  | image_00001.jpg | 1604 | 2        | 1         | 1962       | 76264.51   |
