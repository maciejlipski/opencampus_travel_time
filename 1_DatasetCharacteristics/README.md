# Dataset Characteristics

The dataset, presented in the technical report by Samo Rauter, Iztok Fister Jr., and Iztok Fister, comprises sport activity data collected from nine cyclists. The data was sourced from their Strava or Garmin Connect accounts and is structured in XML-based formats such as GPX or TCX. These formats include various attributes suitable for analysis, enabling diverse research in the domain of sports science, data mining, and performance analytics.

**Attributes Captured:**
- GPS location data
- Elevation
- Duration of activities
- Distance covered
- Average and maximal heart rate

**Source: Data was voluntarily contributed by cyclists, who remain anonymous for ethical reasons.**



## Data Conversion and Data overview [Colab Notebook](1_DatasetCharacteristics/preprocessing.ipynb)


#### Mounting to Drive
![image](https://github.com/user-attachments/assets/2c2ebca4-12f9-42e6-8c69-8d3e11ea8393)


#### Converting 9 GPX files to xlsx files
  ![image](https://github.com/user-attachments/assets/01d0acf3-3b31-49df-b3ca-154c4eb0babb)

#### Preview of Data
![image](https://github.com/user-attachments/assets/3f8fc2d0-fc26-468f-bc63-38271f61501a)


#### Preprocessing data
- Deleted files recorded outside europe
- Repair currupted file
- Convert Timestamp to Seconds

