# Predict individual driving habits

## Repository Link

https://github.com/maciejlipski/opencampus_travel_time

## Description

This project primarily focuses on predicting cyclists' speed based on GPX files retrieved from Slovenian pro-cyclists. Initially, the idea was to calculate the estimated time based on the GPX files. However, as we built our base model and conducted further evaluations, we found that the data was insufficient to predict the estimated time. Hence, we decided to focus on predicting speed instead.

 For the estimation of speed we considered following features.
- Elevation
- Slope
- Angle
- Distance
- Cumulative Slope

### Task Type
#### Preprocessing of Data
- Converting GPX files into xlsx using _openpyxl_ python library and retrieved Latitude, Longitude, Elevation and Time stamp.
- Delete files recorded outside of Europe
- Based on retrieved information calculated distance and time difference using _geopy_ python library.
- Further processing was done to calculate slope and angle using goepy and math python libraries

#### Splitting the data set
- Train 90%
- Test 10%

#### Model Configuration
- Sequential model
- Input Layer
- Hidden layers
- Output Layer
- Model Compliation
- Callbacks

#### Model Evaluation
- Trainig the model
- Testing the model

### Results Summary

- **Best Model:** Simple Neural Network
- **Evaluation Metric:**
- Training = ETA: 16s - loss: 4.9479 - mae: 1.5318
- Testing = Linear Regression (Mean Absolute Error: 1.9240215480755247) / Neural Network (Mean Absolute Error: 1.86628655022557)

- **Result:**
- Absolute percentage difference in Linear Regression model: 24.186693000542977
- Absolute percentage difference in Neural Network model: 17.36073262240657

## Documentation

1. **[Literature Review](0_LiteratureReview/README.md)**
2. **[Dataset Characteristics](1_DatasetCharacteristics/exploratory_data_analysis.ipynb)**
3. **[Baseline Model](2_BaselineModel/baseline_model.ipynb)**
4. **[Model Definition and Evaluation](3_Model/model_definition_evaluation)**
5. **[Presentation](4_Presentation/README.md)**

## Cover Image

![Cover Image](https://github.com/user-attachments/assets/df766913-9171-4ce0-9a3b-39d5a1d329fe)

