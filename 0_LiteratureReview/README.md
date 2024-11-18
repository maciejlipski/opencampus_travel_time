# Literature Review

Approaches or solutions that have been tried before on similar projects.

**Summary of Each Work**:

- **Source 1**: Bicycle Data-Driven Application Framework: A Dutch Case Study on Machine Learning-Based Bicycle Delay Estimation at Signalized Intersections Using Nationwide Sparse GPS Data

  - **https://www.mdpi.com/1424-8220/23/24/9664#**
  - **Objective**:
  - **Methods**:
  - **Outcomes**:
  - **Relation to the Project**:

- **Source 2**: The Development of a Predictive Hiking Travel Time Model Accounting for Terrain Variations

  - **https://gispoint.de/fileadmin/user_upload/paper_gis_open/537521059.pdf**
  - **Objective**: To develop a predictive hiking speed model accounting for terrain variations.This predictive travel time model could be used in adventure travel planning, wild land accessibility evaluation, and emergency response evacuation planning to name a few. The potential of using hiking data collected via hand held 
of 40 hikes represented by global positioning system (GPS) data were downloaded from an outdoor adventure travel website to be used in the study.
  - **Methods**: They aimed to create a hiking speed model using GPS data by testing different mathematical equations like (linear, quadratic, cubic, compound, logistic, growth, and exponential equations) to understand how slope affects speed. The researchers compared their model with existing ones, like Tobler’s and Langmuir’s, which adjust for elevation changes. They applied Geographically Weighted Regression (GWR) to refine their predictions, analyzing speed variations across various terrains.
  - **Outcomes**: The GWR analysis improved the model’s accuracy, achieving an R² of 0.5255, meaning slope alone explains 52.55% of the hiking speed. This better fit suggests that slope-speed relationships vary across locations, and GWR accounts for this by using local data samples weighted by distance. This process smooths out extreme values, making the model more reliable and better suited for real-world conditions.
  - **Relation to the Project**:Reinforces the value of GPX data for predictive model training and help us to understand the methods to incorporate rider variability into travel time predictions. Offers insights into leveraging terrain and environmental data for accuracy. Aligns with using machine learning to improve model performance. Provides a framework adaptable for your dataset of 9 riders.

- **Source 3**: Bike Share Travel Time Modeling: San Francisco Bay Area Case Study

  - **https://doi.org/10.1109/MTITS.2017.8005582**
  - **Objective**: The study explores predictive modeling of bike-share travel times in the San Francisco Bay Area, using random forest (RF), least square boosting (LSBoost), and artificial neural network (ANN) techniques. With 33 predictors like distance, weather, and time of day, RF models achieved the best performance (MAE: 84.01 seconds; MAPE: 16.92%). Key factors affecting travel time include travel distance, subscription type, time of day, weekends, temperature, and humidity. The research highlights RF's superiority and emphasizes weather's role in bike travel time variability.
  - **Methods**: To develop the most accurate travel time prediction model, several statistical and machine learning techniques were evaluated. Initially, multiple linear regression (MLR) was employed as a baseline approach. Subsequently, advanced machine learning methods, including random forest (RF), least square boosting (LSBoost), and artificial neural networks (ANN), were investigated. These techniques were systematically compared to identify the most accurate model. This section outlines the methodologies applied to analyze the data.
  - **Outcomes**: Random forest (RF) models outperformed other techniques, including LSBoost and ANN, in predicting bike travel time. Using RF and forward stepwise regression, the key predictors identified were travel distance, subscription type, time-of-day, Saturday, mean temperature, mean humidity, and Sunday. Weather conditions, particularly temperature and humidity, were also found to significantly impact bike travel time.
  - **Relation to the Project**: In the BSS even though the data was limited to stations and service areas the main study and methodolgy was focused on bicycle travel time. Further the models used in this paper can be tested with our data set considering the variables used are same.
