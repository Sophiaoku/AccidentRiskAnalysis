# Traffic accident frequency based on weather conditions and age group. 
**Datasets**: Traffic accident data, weather data, individual data.

**Data 1** : NYC ( Motor Vehicle Collisions - Crashes) (https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95/data )

**Data 2**: NYC open-meteo.com (extracted as CSV)

**Data 3**: NYC (Motor Vehicle Collisions - Person)  https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Person/f55k-p6yu/about_data 

**Github files**: excel sheets (all three unclean and clean datasets), model .ipynb and .py files.

### Questions seeking to answer : 

1. Are there seasonal patterns in accident occurrences, and do they correlate with specific weather conditions? Is there any relationship between weather conditions and collisions? 
2. Predict the likelihood of an accident based on time of day, season, and weather conditions.
3. Are certain age groups more likely to be involved in accidents under specific conditions? Identify high-risk age groups. Can we design targeted safety campaigns for high-risk age groups? We can classify the age group into seniors, teenagers, or maybe by generations (Genz, millennials and all) Any relationship between the type of vehicle and the frequency of the accident?

### Dataset Variables
This is a list of variables included in the original export. The final version of the cleaned dataset is available in this repository.

| Data 1 (Collision Data)      | Data 2 (Precipitation)                  | Data 3 (Demographic)     |
|------------------------------|-----------------------------------------|--------------------------|
| Crash date                   | Highest/Lowest Maximum Temperature      | UNIQUE_ID                |
| Crash Time                   | Highest/Lowest Minimum Temperature      | COLLISION_ID             |
| Borough                      | Highest Precipitation                   | CRASH_DATE               |
| Zip Code                     | Highest Snowfall                        | CRASH_TIME               |
| Latitude                     | Highest Snow Depth                      | PERSON_TYPE              |
| Longitude                    | Date                                    | PERSON_ID                |
| Location                     |                                         | PERSON_INJURY            |
| On street name               |                                         | VEHICLE_ID               |
| Number of persons injured    |                                         | EMOTIONAL_STATUS         |
| Number of persons killed     |                                         | BODILY_INJURY            |
| Number of pedestrians injured|                                         | POSITION_IN_VEHICLE      |
| Number of pedestrians killed |                                         | SAFETY_EQUIPMENT         |
| Number of cyclist injured    |                                         | PED_LOCATION             |
| Number of motorist injured   |                                         | EJECTION                 |
| Number of motorist killed    |                                         | PERSON_AGE               |
| Contributing factor 1        |                                         |                          |
