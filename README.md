# Parking Availibity Prediction in San Francisco
## Intro
As the streets in San Francisco are reaching their capacities, people working and living here are suffering from the parking problem. In this in-class competition, we are aimed to answer the question whether or not we could predict the likelihood of finding a parking spot on a street given time. 

## Dataset
- The dataset is provided by [Parknav](https://parknav.com/), an app serves drivers open on-street parking information in real time, which includes basic data on available parking spots upon observation. 
- Additional datasets include [parking meter data](https://data.sfgov.org/Transportation/Parking-meters/44tz-8bvs/data) and [parking sensor data](http://sfpark.org/wp-content/uploads/2014/06/docs_sensordata.pdf) in San Francisco.

## Methods
### Feature engineering 
- Time series data
	- Date time features
	- Lag features
	- Rolling window statistics
- Geospatial data
	- GPS coordinates - address conversion
	- K-means clustering

### Modeling
- Random Forest
- Logistic Regression
- XGBoost
- Stacking ensemble

## Results
Achieved a F-0.5 score of 0.580, ranking in the second place out of 40 teams. 
For more details, please refer to the report and slides. 
*Due to NDA with Parknav, we are unable to provide codes and the dataset.*



