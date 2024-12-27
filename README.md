# Predict individual driving habits

## Repository Link

https://github.com/maciejlipski/opencampus_travel_time

## Description

Predicting cyclists speed based on the GPX files we retrieved from a free source. For the estimation of speed we considered following features.
- Elevation
- Slope
- Angle
- Distance
- Cumulative Slope

### Task Type
#### Preprocessing of Data
- Converting GPX files into xlsx using _openpyxl_ python library and retrieved Latitude, Longitude, Elevation and Time stamp.
- Based on retrieved information calculated distance and time difference using _geopy_ python library.
- Further processing was done to calculate slope and angle using goepy and math python libraries

#### Splitting the data set
- Train 90%
- Test 10% 

### Results Summary

- **Best Model:** Neural Network model & Linear Regression Model
- **Evaluation Metric:** ![image](https://github.com/user-attachments/assets/2b658eda-40a5-4ff6-8bc6-9f4697036e41)

- **Result:** [e.g., 95% accuracy, F1-score of 0.8]

## Documentation

1. **[Literature Review](0_LiteratureReview/README.md)**
2. **[Dataset Characteristics](1_DatasetCharacteristics/exploratory_data_analysis.ipynb)**
3. **[Baseline Model](2_BaselineModel/baseline_model.ipynb)**
4. **[Model Definition and Evaluation](3_Model/model_definition_evaluation)**
5. **[Presentation](4_Presentation/README.md)**

## Cover Image

![Cover Image](https://github.com/user-attachments/assets/df766913-9171-4ce0-9a3b-39d5a1d329fe)

